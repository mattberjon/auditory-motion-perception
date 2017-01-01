Laboratory
==========
.. _ref_chap_lab:

In order to measure the phenomena that we were interested in (see
chapter :ref:`ref_chap_filehne`). We created for the Perception group of the
School of Psychology of Cardiff University a new audiovisual lab. In audio
research, there is no standard measurement system but according to the needs we
will give a priority to two main techniques:


- :term:`VAS`
- :term:`RAS`

.. _ref_chap_lab_sec_vas_ras:
Virtual Auditory Space vs Real Auditory Space
---------------------------------------------

The :term:`VAS` is the ability to create the illusion of any free-field
environment using a closed-field sound system such as headphones or
loudspeakers. This technique assumes that identical stimuli will be perceived
identically at a listener's eardrum whatever the physical mode of delivery. It
is now accepted that the simulation of acoustical space is best achieved using
closed-field systems since headphones allow a complete control over the signal
delilvered to the listener's eardrums.  The disadvantage of this technique is
that it requires compensation of the transfer function of the sound delivery
system itself. Moreover, in order to give to the listener the perfect illusion
of a 3D audio scene, you will need to use the binaural technique. To achieve
that, it is necessary to recreate at each ear, the signals that would be
perceived naturally. The use of the :term:`HRTF` is the best way to reproduce
the localisation cues needed.
         
Binaural broadcasting technique
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


The binaural synthesis is based on the use of the pair of binaural filters
obtained from the :term:`HRTF`. At each source position in the space :math:`r,
\theta, \phi` it exists a pair of :term:`HRTF`, that we can obtain through a
model or a set of measurements. In order to place a virtual source at a given
position, it is necessary to find the pair of :term:`HRIR` corresponding to the
position in a database if available or calculate the interpolation and deduce a
pair of binaural filters :math:`x_L` and :math:`x_R` adapted to the chosen
implementation.  For the headphone diffusion, the simplest way is to convolve
the monophonic and anechoic signal :math:`x` with each filter in order to
obtain the signals :math:`x_L` and :math:`x_R` that will be broadcast on the
headphones (see :numref:`ref_fig_binaural_technique`). In addition, it is
necessary to compensate for the headphone that act as a filter.


.. _ref_fig_binaural_technique:
.. figure:: _static/binaural_technique.svg

   Binaural techique on headphones. After :cite:`Guillon2009`.

The spectral filtering of a sound source before it reaches the eardrum is
called the :term:`HRTF`. The binaural :term:`HRTF` can be thought of as a
frequency-dependent and amplitude and time-delay differences that result
primarily from the complex shaping of the pinnae. :cite:`Batteau1967` claimed
that the folds of the pinnae cause time delays within a range of $0$ to
:math:`300\mu`. This is a cause of a significant change in the spectral content
at the eardrum. Because of the asymetric shape of the pinnae, this spectral
changes vary with the source position.  Moreover, the shape of pinnae differ
from one subject to another. This means that in theory, we should measure the
:term:`HRIR` for an infinite number of positions in order to reconstruct
perfectly the signal at the eardrums. Because it is impossible to measure an
infinite number of points and because, measuring impulse responses of a subject
is still nowaday is difficult and long task suggesting a sampling of a finite
number position and then interpolate the missing positions. Another way is to
use a bank a average :term:`HRTF` and use the same bank for all subject. Both
techniques bring artefacts once convolved with the signals. Results are
localisation and externalisation of sounds problems. The externalisation
problem is not still perfectly known. Nevertheless, :cite:`Guillon2009`
suggested several possibilities that could have an impact on the
externalisation such as the fact that the listener knows that signal is
broadcast through the headphones, and feel the pressure of it on his ears. The
absence of visual cues, or incoherent signals between the visual and audio
modalities. The acoustics signals at the eardrums can be as well degrade due
the the distortion brought by the headphones.


Multi loudspeakers technique
++++++++++++++++++++++++++++

The use of loudspeakers instead of headphones avoid troubles about
externalisation of the sound and a difficult :term:`HRTF` measuring process.
Spatialisation of sound is more robust, all spatialisation cues are naturally
available and don't need to be recreated. Nevertheless, several problems still
exist such as the interpolation of sounds located between two speakers.

.. todo::
  Becareful, in both cases (VAS and RAS), the interpolation is not a real
  problem for the simple reason that in VAS, we can't measure an infinite 
  number of points, hence, we will interpolate several positions. In RAS, we
  will not have an infinite number of speakers, thus, we will interpolate any
  position that is located between two speakers.

Multi loudspeakers technique
++++++++++++++++++++++++++++

The use of loudspeakers instead of headphones avoid troubles about
externalisation of the sound and a difficult :term:`HRTF` measuring process.
Spatialisation of sound is more robust, all spatialisation cues are naturally
available and don't need to be recreated. Nevertheless, several problems still
exist such as the interpolation of sounds located between two speakers.

.. todo::
  Becareful, in both cases (VAS and RAS), the interpolation is not a real
  problem for the simple reason that in VAS, we can't measure an infinite 
  number of points, hence, we will interpolate several positions. In RAS, we
  will not have an infinite number of speakers, thus, we will interpolate any
  position that is located between two speakers.
