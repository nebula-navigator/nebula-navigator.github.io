---
title: "Growth of Intermediate-Mass Black Hole Seeds in Dense Star Clusters (in-prep)"
collection: publications
category: manuscripts
permalink: 
excerpt: 'Tidal Disruption Events, Eccentric Gravitational Wave Mergers, and Light Intermediate- Mass Ratio Inspirals'
date: 2025-06-30
venue: 
slidesurl: 
paperurl: 
citation: 
---
<!-- ---
title: "Paper Title Number 3"
collection: publications
category: manuscripts
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2015-10-01
venue: 'Journal 1'
slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
--- -->

Intermediate-mass black holes (IMBHs) are the elusive missing link between stellar-mass black holes and supermassive black holes. The interplay between gravitational dynamics and stellar evolution can lead to IMBH formation and growth of dense stellar environments, such as globular clusters. We analyzed simulation results from dense and massive globular cluster models simulated using MOCCA code in order to create detailed histories of IMBH growth in star clusters of varying initial central density, half-mass radius, binary fraction, mass, metallicty and initial mass function. A series of python based automated scripts were developed to analyze how IMBH seed was growing in simulations where IMBH formed through runaway collisions of stars and mergers with other black holes. The scripts were later assembled into MOCCA-BH-Forge (MOCCA-Blackhole-Forge). MOCCA-BH-Forge is an open-source simulation data visualization pipeline, designed to work with MOCCA output snapshots and history files. 

Detailed analysis of IMBH growth history was conducted using history files in MOCCA-BH-Forge. We found 2756 mergers with main-sequence stars out of which 2635 were collisions, 182 mergers were found involving evolved stars, 1523 involving white dwarfs, 137 involving neutron stars and 486 mergers involving stellar mass black holes. These collisions between MS stars, evolved stars, compact objects and IMBH are likely to lead to tidal disruption events. We also found hundreds of gravitational wave candidates with gravitational waves corresponding to the LISA detection range. These candidates were extracted from MOCCA-Survey Database I (Askar et al. 2017) using MOCCA-BH-Forge (see Figure 2)


Our research finds that globular clusters with initial densities of the order 10^7 M_sun/pc^3 tend to host the formation of an IMBH seed of ~1000 - 5000 M_sun through runaway collisions within few to tens of Myr. During the first Gyr of cluster evolution the IMBH grows by merging with other stellar mass black holes and by tidally disrupting stars.  At late times it also merges with other compact objects. These mergers between IMBH-compact objects emit low-frequency gravitational waves which lie within the observable range of space-based gravitational-wave detectors like LISA. These tidal disruption events are relevant for future transient sky surveys. 



Figures 1 and 2 show summaries of all dynamical interaction events experienced by the IMBH from the time of its formation until the end of simulation, spanning 15 billion years, from one of our models. These events include tidal disruption events, binary-single interactions, binary-binary interactions, evolution and binary evolutions. Plots are generated from MOCCA-BH-Forge history file analysis. 



<h2 style="text-align: center; font-size: 1.5em; font-weight: bold; margin-bottom: 5px;">Merger Events Leading to IMBH Growth in model-1-z0001</h2>
<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <figure style="text-align: center; flex: 1; max-width: 100%;">
        <img src="/images/subplots1.png" alt="Phase-folded lightcurve from Tarleton" style="width: 100%; max-width: 1800px; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.1em;">Figure 1: A summary of dynamical interactions in the life-time of IMBH. subplots (from top left to right) (a) IMBH Mass Evolution from 0-2Gyr (b) Interaction event frequency, it should be noted that 'COLLISION' here refers to tidal disruption events (c) IMBH position changes observed due to dynamical interactions (d) IMBH growth over 15 billion years (e) Cumulative encounter cases over time. Each encounter case ID corresponds to a particular interaction outcome (f) Summary of these encounter/interaction outcomes. We see number of mergers, fly-byes and exchanges, and binaries unbounded during the process  </figcaption>
    </figure>
</div>
<div style="display: flex; flex-direction: column; align-items: center; margin: 10px;">
    <figure style="text-align: center;">
        <img src="/images/subplots2.png" alt="Phase-folded lightcurve from Tarleton" style="width: 100%; max-width: 1800px; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.1em;">Figure 2: A detailed analysis of merger events with the IMBH. subplots (from top left to right) (a) Frequency of events leading to mergers: tidal disruption events (COLLISIONS), binary-binary events leading to mergers (BIN_BIN), binary evolutions leading to mergers (BIN_EVOL), binary and single star interactions leading to mergers (BIN_STAR) (b) Each merger event counted separately for the stellar types involved. 0: low-mass main sequence 1:main sequence 2: Hertzsprung-gap star 3: First giant branch star 4: Core helium burning star 5: Early asymptotic giant branch star 6: Thermally pulsing asymptotic giant branch star 7: Naked helium star MS 8: Naked helium star Hertzsprung gap 9: Naked helium star giant branch 10: Helium white dwarf 11: Carbon-oxygen white dwarf 12: Oxygen-neon white dwarf 13: Neutron star 14: Black hole 15: Massless supernova. (c) How merger events counts changes with time. It can be seen that tidal disruption events dominated throughout the evolution (d) A summary of merger counts with each stellar type categorized by merger events (e) Mergers with each stellar type resolved over time (f) The stats for IMBH merger with white dwarfs, neutron stars and other black holes. These events were extracted and hundreds of gravitational wave candidates were identifed with their evolution histories leading to low frequency LISA range gravitational waves.
 </figcaption>
    </figure>
</div>


