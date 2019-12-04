---
layout: single
title: pETSI 2019
sidebar:
  nav: "side"
toc: true
rtt: true
---
**Exoplanet Transmission Spectroscopy Imager (ETSI)**

__Allison Glantzberg and Samantha Hudson__

## Introduction
The Exoplanet Transmission Spectroscopy Imager (ETSI) is an astronomical instrument designed to measure the atmospheres of exoplanets that orbit bright stars (brighter than 12th magnitude) on small telescopes (1-2 meters). Both ETSI and a previous prototype (pETSI) are made of commercial parts. Several key changes were made to the prototype including upgrading the prism and optimizing the location of some optical components. A series of images taken during a transit are used to identify absorptions and emissions associated with the atmospheric features of an exoplanet by looking for a relative change in color between the 5 bands during the transit. ETSI was used to observe exoplanet transits on the 0.9m telescope at McDonald Observatory and preliminary reduction shows improved results over pETSI. In the future, a customized version of ETSI, along with a custom data reduction pipeline, will be able to conduct the first large survey of exoplanet atmospheres, performing preliminary ground-based follow up of Transiting Exoplanet Survey Satellite (TESS) targets so that astronomers can identify the best candidates for more precise observations using the James Webb Space Telescope (JWST) and large ground-based telescopes

<figure>
  <a href="/instruments/assets/hrdiag.png" target="_blank"><img src="/instruments/assets/hrdiag.png" alt="HR Diagram"></a>
  <figcaption>Figure 1: Example Hertzsprung-Russell Diagram. The axis can be converted to R vs. B-R to obtain a color-magnitude diagram. Source: European Southern Observatory.</figcaption>
</figure>

## Science Goal
With over 4000 exoplanets already discovered, and more on the way, ETSI provides an efficient way to characterize atmospheres. Measuring the chemical composition of an atmosphere provides insight into a planet’s formation history, climate, and habitability. ETSI utilizes a method known as transit spectroscopy—observing a host star in multiple wavelengths as its exoplanet passes in front of it—to identify atmospheric features. During transit, a small fraction of stellar light filters through the exoplanet’s atmosphere and allows us to capture the spectroscopic signature of the planet (Fig. 1). The fractional drop in flux, or transit depth, caused by the planet is wavelength dependent. Light curves which measure total brightness over time can be constructed for multiple regions of light, thus isolating specific atmospheric emission and absorption features[1].

Figure 1: Model Spectrum fro WASP-3 b with water, sodium, and titanium oxide features. (Model provided by Anna Ross)

## ETSI Design
During observation, light goes through the telescope and enters ETSI where it travels through long-pass and multi-bandpass filters and is then collimated with a 200 mm focal length lens. The collimated light is dispersed by an equilateral prism into 5 distinct bands for each star in the field of view. These bands are focused by a 105 mm focal length lens and captured by an SBIG STF-8300 Charged-Coupled Device (CCD). The light path is shown in Figure 2.

Figure 2: Light path from Telescope through ETSI. Components from left to right: mounting plate, focal plane, long-pass and quad bandpass filters, collimator, equilateral prism, 105 mm lens, and camera.

ETSI is designed using commercial parts and has a field of view of 4.99’ by 3.76’, a wavelength range of 435nm to 1050 nm, and a spectral resolution (λ/Δ λ) of 22. Figure 3 shows the SolidWorks model of ETSI.

Figure 3: SolidWorks model of ETSI provided by Leonarda A. Barba.

Components
(1) Long-pass and Quad (Alluxa) Bandpass filters

(2) 200 mm collimato

(3) Equilateral Prism

(4) 105 mm lens

(5) SBIG STF-8300 camera

(6) Support rails

Figure 4: Lab setup of ETSI.

Figure 5: ETSI attached to the 0.9 m telescope at McDonald Obseratory.

## Data Collection and Reduction
Data is collected using CCDOpps version 5. There is not currently a data reduction pipeline, but MATLAB, Python, and AstroImageJ have been used during and after observations.

Figure 6: Images taken at McDonald Obseratory. Right: Science image of HD 189733 b (boxed) and reference stars. Left: Science image of WASP-3 b (boxed) and reference stars.

## The Future of ETSI
The current performance of ETSI can be improved with an updated optical design and customized optical components. The next phase of ETSI will require these mechanical upgrades as well as the creation of a customized data reduction pipeline.

## References
[1] Kreidberg 2017 arXiv:astroph/1709.05941