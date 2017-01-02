.. _ref-chap-localisation:

Background on hearing
=====================

.. _ref-sec-localisation:

Auditory localisation
---------------------

The auditory system is able, even in the absence of visual cues to derive a
representation of the world thanks to its two sensors, the ears. The location
of a sound source relative to the listener's head can be described in terms of
azimuth, elevation and distance.

Localisation in azimuth is mainly attributed to a binaural processing of
acoustic cues based on time and intensity differences between the ears.
Localisation in elevation is explained by the use of monaural cues although
these cues also play a role in azimuth localisation. Localisation in distance
can be determined from various acoustic cues related to the transmission of
sound over distance, such as intensity and spectral content, and to the effects
of acoustic reflections, such as interaural coherence and reverberant tails.

Localisation in azimuth
^^^^^^^^^^^^^^^^^^^^^^^
The duplex theory
+++++++++++++++++

:cite:`Rayleigh1876` attempted to account for localisation in azimuth in terms
of interaural difference cues. He appreciated that when a sound is presented
from the side, the listener's head interrupts the path from the source to the 
opposite ear. The result is a difference in pressure between the closest ear
(ipsilateral) and the farthest ear (contralateral) known as :term:`ILD`. The
relative difference will increase with frequency. However, for sources below 
:math:`1000` Hz, because the sound wavelength will be several times larger than
the head, the head does not present a significant obstacle. Rayleigh pointed
out that at these low frequencies, the :term:`ILD` between the two ears would
consequently be too small to be perceptible. :cite:`Rayleigh1907` demonstrated
that humans are also sensitive to the :term:`ITD` of low frequency pure tones.
:term:`ITD` reflect the difference in path distance to each ear when sound
source is located to one side (see :numref:`fig-itd-ild-representation`).
However Rayleigh pointed out that, for a pure tone, the azimuth corresponding
to a given :term:`ITD` is ambiguous if the tone's wavelength is less than the
width of the of the head. For pure tones, therefore, :term:`ITD` are effective
for frequencies whose wavelengths are well below about :math:`20~cm`, whereas,
:term:`ILD` are effective for frequencies whose wavelengths are well above
:math:`20~cm`. This two-mechanism account of sound localisation in azimuth
became known as the duplex theory.

.. _fig-itd-ild-representation:


.. figure:: _static/itd_ild_scheme.svg
   :align:  center

.. figure:: _static/itd_ild_data.svg
   :align:  center

   Representation of the binaural cues :term:`ITD` and :term:`ILD` (After
   :cite:`Daniel2011`). Representation of Interaural time and intensity
   differences for a monochromatic sound sound.

.. todo::
  Convert the TeX images into SVG and save them into the _static folder.


The duplex theory was supported by several studies such as :cite:`Stevens1936`, 
who found a minimum in accuracy for pure-tone localisation at around
:math:`3000~Hz` (:math:`\sim{11}~cm`). :cite:`Sandel1955` found a minimum
around :math:`1500~Hz` (:math:`\sim{23}~cm`). These results suggest that there
is a range between :math:`1500` and :math:`3000 Hz` where the wavelength is too
high to provide adequate :term:`ILD`. At low frequencies, where the wavelength
is important compared to the radius head, the sound wave is reflected to a
negligible degree, meaning that the :term:`ILD` will be close to :math:`0`. It
should be noted, however, that this is only true for a source beyond about
:math:`1~m` where the wave can be treated as planar. Close to the head, the
wave front will be spherical and thus subject to the inverse-square
relationship between sound intensity and distance, which will have the same
effect at all frequencies. The difference in path distance to each ear can thus
result in a significant difference in intensity between the two ears, even if
no head shadowing occurs :cite:`Shinn-Cunningham2000`.

Limitation of the binaural cues
+++++++++++++++++++++++++++++++

:term:`ITD` and :term:`ILD` depend on both frequency and elevation.
:cite:`Wallach1939` described a form of geometrical locus which has the shape 
of a cone centred on the interaural axis and corresponding to an infinite 
number of positions for which the :term:`ITD` and :term:`ILD` are roughly
constant.  This locus id known as the "cone of confusion" :cite:`Woodworth1954` 
(see :numref:`fig-cones-of-confusion`). Because many positions on these cones
surfaces can correspond to the same pairing of :term:`ITD` and :term:`ILD`,
ambiguities in localisation occur, even within the horizontal plane, resulting
in front/back errors. :cite:`Young1931` showed that head movement can
compensate for the lack of pinnae in localisation. This was confirmed later on
by :cite:`Fisher1968` who used a broadband noise pulse and subjects were asked
the position of the source according to several conditions such as head
restrained of free and with their own pinnae, an artificial pinnae or no
pinnae. His finding was that head movements brought in all conditions a very
good disambiguation of the source position. :cite:`Wallach1940` introduced
a general description of the nature of head movements during localisation tasks
and pointed out the need for dynamic cues for localisation disambiguation. This
was confirmed by :cite:`Burger1958` who compared front/back errors with clamped
or free head and with or without covering one or two ears using a noise (per
octave band). His conclusions were that disambiguation was almost complete when
the head was free. The disambiguation slightly decreased when using noise
between :math:`800` and :math:`2400~Hz` and decreased dramatically at higher
frequencies (above :math:`2400~Hz`) when both ears are covered\footnote{The ear
away from the loudspeaker was covered with an earphone, which was fed with a
wide band random noise in order to mask it at all frequencies.}.


.. _fig-cones-of-confusion:

.. figure:: _static/cones-confusion-schematic.svg
   :align:  center

   The cone of confusion. Identical values of :term:`ILD` and :term:`ITD` of
   two opposite points anywhere on the surface of the cone represented by the
   hyperbolia in two dimensions (After :cite:`Blauert1983`).

Localisation in elevation
^^^^^^^^^^^^^^^^^^^^^^^^^

The presented localisation cues, based on interaural differences are not
sufficient to explain discrimination within the cones of confusion when the
head is stationary. :cite:`Rayleigh1876` suggested that spectral cues may
play a role. He later confirmed that distorting the acoustics of the pinna (by
adding "little reflective flaps") could adversely affect accuracy of front/back
judgements (:cite:`Rayleigh1907`). Monaural cues (or spectral cues) can be used 
to explain discrimination of elevation because the sound is spectrally
distorted by reflections and diffractions around the torso, shoulders, head and
pinnae before reaching the ear in a way that is dependent on elevation. The
resulting colorations for each ear of the source spectra, depending on both
direction and frequency, provide a localisation cue. :cite:`Langendijk2002`
showed that spectral cue has an impact in localisation in high frequencies and
especially, by testing narrow band noises, they suggested that up-down
localisation depend upon frequencies between :math:`4` and :math:`16~kHz` and
front-back localisation on frequencies between :math:`8` and :math:`16~kHz`. In
case of remaining confusion about a source position, :cite:`Wightman1999`
showed that head movements will solve these ambiguities and support the
Wallach's theory (:cite:`Wallach1940,Thurlow1967`).

.. _fig-cue-frequency-repartition:

.. figure:: _static/cue_frequency_repartition.svg

   Representation of main auditory cues used for localisation according to the
   frequency.

.. todo::
   Check if this figure is at its right place

Localisation in distance
^^^^^^^^^^^^^^^^^^^^^^^^

According to :cite:`Rumsey2012`, there is mainly :math:`4` cues in localisation
in distance:

- the inverse-square law of intensity.
- direct to reverberant ratio.
- small path differences between direct sound and reflections.
- high frequencies attenuation.

Intensity
+++++++++

In the earliest studies, intensity was considered the primary acoustic cue to
distance (:cite:`Thompson1892`). :cite:`Edwards1955` in two experiments using a
metronome and the ticking of a clock. He measured that the :term:`JND` in
distance was about :math:`20~\%` of overall distance. For a stationary sound
source in acoustic free field and emitting uniform spherical waves, the sound
source intensity is related to distance from the sound source by an inverse
square law. The intensity is related the distance :math:`R`, from the source to
the listener by a factor :math:`\frac{1}{R^{2}}`. Since sound pressure is
proportional to the square root of intensity, pressure obeys a
:math:`\frac{1}{R}` relation.

Reverberation
+++++++++++++

In any environments with sound reflecting surfaces, the ratio of energy
reaching a listener directly to energy reaching a listener after reflecting the
surface contact varies systematically with distance. This cue is called the
direct-to-reverberant energy ratio and decreases as distance between the
listener and source increases. In rooms, change in direct-to-reverberant energy
ratio is primarily due to the effect of the inverse-square law on the direct
sound because the energy in the later part (all the reflection of an order
:math:`n > 0`) is relatively constant for varying source distance
:cite:`Blauert1983`. 

Spectral shape
++++++++++++++

Under certain circumstances, sound source spectrum varies as a function of
distance. At greater distance (above :math:`15~m` :cite:`Blauert1983`), the
sound absorbing properties of air significantly modify the higher frequencies
of the source. Moreover, these properties depend on environmental factors such
as relative humidity or the temperature. :cite:`Ingaard1953` suggested that
at :math:`40~\%` of humidity, the attenuation peak was at $4000$~Hz and was
about :math:`6~dB` every :math:`100~m`. Some studies suggested that humans take
advantage of binaural cues in their distance judgement. :cite:`Coleman1968`
showed that perceived distance varies when you cut off the high frequencies of
an click stimulus. He tested several distances (from :math:`2.5` to
:math:`8.5~m`) and observed that for closer source the perceived distance
increases when you remove high frequencies (above :math:`7680~Hz`). For further
sources, the perceived distance is roughly accurate. But these results are
challenged by several other studies such as :cite:`Koehnke2000,Cochran1968`

.. todo::
  These last two articles need to be read more deeply.

Other factors in distance perception
++++++++++++++++++++++++++++++++++++

  Vision 
    is known to affect percept of auditory space, including perceived distance.

  Familiarity
    and prior information about the characteristics of a sound can
    significantly influence the auditory distance perception.

Dynamic cues
^^^^^^^^^^^^

As we briefly explain above, localisation can be improved or remove
disambiguation through head movements and hence dynamic cues changes either by
a source movement or a listener's movement. 

For localisation of sound source in space, a listener naturally seeks to
orientate his head toward this one and face it. It is in that position that
sounds are localise the most accurately. However, :cite:`Perrett1997a`
suggested that an improvement of localisation accuracy in azimuth can be
obtained by dynamic cues even if the sound is too short for the listener to
face it. This result showed that localisation cues called "dynamic" introduced
by head movements contribute in themselves to the localisation percept of a
source. According to :cite:`Macpherson2008,Macpherson2009`, head movements
from :math:`5^\circ` (at :math:`50^\circ/s`) generate usable dynamic cues. This
is why head movements are beneficial even for short sound as described by
:cite:`Perrett1997a` comparing a localization performances of a low-pass noise
stimulus lasting :math:`3` or :math:`0.5` seconds with or without slight head
movements.  The front/back ambiguities are reduced by analysing the dynamic
changes of :term:`ITD` and :term:`ILD`. For example, for a source in front of
the listener. If the listener turn his head to the right along the horizontal
plan, the sound source will be perceived closer to the left ear. If he turn his
head to the left, the sound source will be perceived closer to the right ear.
If the source is behind the listener's head, the effect will be the opposite

.. todo::
  create a figure explaining that. 

:cite:`Perrett1997` studied the effect of dynamic cues in the elevation plan
and suggested that head movement in this plan are beneficial for sources
really high or low (:math:`\pm30^\circ`). :cite:`Wallach1939,Wallach1940`
explained this by the fact that in these conditions the amplitude of dynamic
variations of interaural cues lead by the head rotations are lower than sources
closer of the horizontal plane. By using a low-pass noise, :cite:`Perrett1997`
suggested that :term:`ITD` changes are more reliable than :term:`ILD`.
