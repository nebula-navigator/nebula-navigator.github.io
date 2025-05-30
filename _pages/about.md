---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am interested in developing new techniques to analyze observational data from space
as well as ground based telescopes in order to maximize the yield of information from data. With interests spanning exoplanet characterization, binary stars, black holes in globular clusters, and fundamental questions like the <b>search for life beyond Earth</b>, I aim to develop tools that push observational
boundaries. As observational data grows, my goal is to leverage advanced techniques, including machine learning
and AI, to enhance data interpretation in these fields.I am particularly inspired by the potential of JWST’s high-resolution capabilities to
characterize Earth-like planets, and I look forward to contributing to this frontier research.

<h2 style="text-align: center; font-size: 1.5em; font-weight: bold; margin-bottom: 5px;">
    I am conducting my master's research on Exoplanet Atmospheric Retrievals of WASP-107b using Taurex3 (A. F. Al-Refaie et al 2021). This is a work in progress. Here I present some preliminary models fits with posterior distributions for two of our latest runs. The first run was performed on NIRCam spectrum only while the second run is from the combined NIR+MIR spectra spanning 2.4 to 13.7 microns. 
</h2>
<!-- Second Figure -->
<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin-top: 40px;">
    <figure style="text-align: center; max-width: 800px; width: 100%;">
        <img src="./images/Screenshot from 2025-05-30 11-00-11.png" alt="Additional Plot or Visualization" style="width: 100%; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.2em; text-align: center; color: #555;">
            Best fit model from NIR+MIR spectra together with retrieved gases. The spectrum has been clipped to 5 microns for emphasis on selective species in NIR spectrum. It can be seen that the current chemistry profile and prior configuration fails to capture muted species e.g. SO2
        </figcaption>
    </figure>
</div>
<!-- Second Figure -->
<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin-top: 40px;">
    <figure style="text-align: center; max-width: 800px; width: 100%;">
        <img src="./images/prior_bounds_table_3e-1.png" alt="Additional Plot or Visualization" style="width: 100%; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.2em; text-align: center; color: #555;">
            Priors used for our latest runs compared to the priors from CHIMERA and AURORA models from Welbanks et al. 2024
        </figcaption>
    </figure>
</div>
<!-- Second Figure -->
<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin-top: 40px;">
    <figure style="text-align: center; max-width: 800px; width: 100%;">
        <img src="./images/corner_NIR_(iteration1).png" alt="Additional Plot or Visualization" style="width: 100%; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.2em; text-align: center; color: #555;">
            Posterior distributions of selected retrievals from NIR spectrum
        </figcaption>
    </figure>
</div>

<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin-top: 40px;">
    <figure style="text-align: center; max-width: 800px; width: 100%;">
        <img src="./images/corner_NIRplusMIR_(iteration4).png" alt="Additional Plot or Visualization" style="width: 100%; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.2em; text-align: center; color: #555;">
            Posterior distributions of selected retrievals from NIR+MIR spectrum
        </figcaption>
    </figure>
</div>

<h2 style="text-align: center; font-size: 1.5em; font-weight: bold; margin-bottom: 5px;">
    Check out my latest work on creating mock JWST Images 
</h2>
<!-- First Row -->
<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin: 20px; gap: 20px;">
    <!-- Row of figures -->
    <div style="display: flex; justify-content: space-between; gap: 20px; width: 100%;">
        <!-- Left side figure -->
        <figure style="text-align: center; flex: 1; max-width: 100%;">
            <img src="./images/Figure_2.png" alt="Phase-folded lightcurve from Tarleton" style="width: 100%; max-width: 800px; height: auto;"/>
        </figure>
        <!-- Right side figure -->
        <figure style="text-align: center; flex: 1; max-width: 48%;">
            <img src="./images/090_277_444.png" alt="Another lightcurve or figure" style="width: 100%; max-width: 1200px; height: auto;"/>
        </figure>
    </div>
    <!-- Single caption for both figures -->
    <figcaption style="margin-top: 5px; font-size: 1.2em; text-align: center; color: #555;">
        Color composites generated from MOCCA binary maps integrated with JWST NIRCam wide filters F090W, F150W, F277W, and F444W. The cluster's distance is set to 5kpc
    </figcaption>
</div>

<!-- Second Figure -->
<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin-top: 40px;">
    <figure style="text-align: center; max-width: 800px; width: 100%;">
        <img src="./images/potm2404a.jpg" alt="Additional Plot or Visualization" style="width: 100%; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.2em; text-align: center; color: #555;">
            As a reference, this is NGC 6440, a globular cluster that resides roughly 28000 light-years from Earth in the constellation Sagittarius. The object was first 
            discovered by William Herschel in May of 1786.(Credits: NASA/ESA/CSA Webb)
        </figcaption>
    </figure>
</div>

<h2 style="text-align: center; font-size: 1.5em; font-weight: bold; margin-bottom: 5px;">
    Created from simulated massive star clusters such as this:
</h2>

The plot is interactive so feel free to dive into the center and see the IMBH in a binary with a low-mass main sequence star. The snapshot was taken after 12 billion years of evolution. Check out more in [publications](/publications/observational-properties-star-clusters)
,where you can find my in-prep publications.

<!-- Interactive Plot -->
<div style="margin-top: 20px; text-align: center;">
  <figure style="display: inline-block; text-align: center;">
    <iframe src="./images/scatter_plot.html" style="width: 120%; max-width: 1800px; height: 800px; border: none;"></iframe>
    <figcaption style="margin-top: 10px; font-size: 1.2em; color: #555;">                    Projected stellar distribution of a massive globular cluster (Z~0.0005,IMF= 0.08 Msun to 150 Msun, N=2000k, bf=10%, rh = 0.5, Rgc= 5 kpc)</figcaption>
  </figure>
</div>



<!-- Second Figure -->
<!--<div class="page-content" style="display: flex; flex-direction: column; align-items: center; margin-top: 40px;">
    <figure style="text-align: center; max-width: 800px; width: 100%;">
        <img src="./images/PosteriorDist-WASP107b.png" alt="Additional Plot or Visualization" style="width: 100%; height: auto;"/>
        <figcaption style="margin-top: 10px; font-size: 1.2em; text-align: center; color: #555;">
                                       Posterior Probability Distributions of Retrievals
        </figcaption>
    </figure>
</div>-->
