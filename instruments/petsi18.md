---
layout: single
title: pETSI 2018
sidebar:
  nav: "side"
toc: true
rtt: true
---
**Development of pETSI: the prototype Exoplanet Transmission Spectroscopy Imager**

__Taylor Plattner - University of Kansas__

## Abstract
The goal of this project was to build a device, called pETSI, which is specifically designed to identify and directly measure atmospheres around a large number of exoplanets orbiting bright stars. Light from the telescope will enter pETSI and be collimated by a 200 mm camera lens. The collimated beam will pass through a prism, which provides a precise amount of dispersion (high enough to separate the resulting multi-band images). After dispersion, the light passes through a multi-band filter and the filter will transmit a large number of well-defined bands onto a detector. From the resulting spectra, we will be able to observe hundreds of transits and use the presence of known atmospheric features to signify the presence of an exoplanet atmosphere. In future work, pETSI will be used for a campaign to observe hundreds of targets from the Transiting Exoplanet Survey Satellite (TESS). pETSI will observe these identified targets using relatively small telescopes (1-2m-class), with the goal of determining which targets are most valuable for follow-up by larger and more precious resources such as JWST and large ground-based facilities.

## Introduction
The study of exoplanet atmospheres is relatively new and exciting because it offers the chance to determine atmospheric composition, climate, potential habitability, and other insights in environments different from any found in our solar system. Transmission spectroscopy has been the most successful method of detecting exoplanet atmospheres. Essentially, during an exoplanet transit, the exoplanet’s atmosphere imprints an absorption spectrum onto the stellar 
<figure>
  <a href="/instruments/assets/duooptics.png" target="_blank"><img src="/instruments/assets/duooptics.png" alt="DuOCam Optics"></a>
  <figcaption>Figure 2: Optical system for DuOCam.</figcaption>
</figure>
light and then the light that is transmitted to our detector will contain information about the atmospheric composition of the exoplanet [2], like Figure 1. TESS will produce a large amount of targets, so it will be crucial to examine the candidates on smaller telescopes, where observing time is plentiful, and determine which are the most valuable to look at on larger telescopes. 

## Experimental Setup
To detect the signatures of exoplanet atmospheres during transits, pETSI will obtain separate images of the host star and the comparison stars using a prism and a multiband filter to attain a low-resolution spectrum of the exoplanet host star during transits. pETSI is designed with the following parameters: 10’x10’ field of view, 400-1000 nm wavelength coverage, and spectral resolution of 30. The large field of view will allow measurement of several bright reference stars simultaneously with the host star; these measurements will be used to remove the effects of the Earth’s atmosphere. The general layout of pETSI can be seen in Figure 2.

Light from the telescope will enter pETSI and be collimated by a 200 mm camera lens. The collimated beam will pass through a prism, which provides a precise amount of dispersion to separate the resulting multi-band images. After dispersion, the light passes through a multi-band filter and the filter will transmit a large number of well-defined bands onto a spot on a CCD camera. From the resulting spectra,  we will be able to observe hundreds of transits and use the presence of known atmospheric features to signify the presence of an exoplanet atmosphere. Figure 3 and 4 show the final design of pETSI.

## Results
Observational data was first taken with pETSI on the .9m telescope at McDonald Observatory. There were some technical difficulties with the focus of the telescope at first, but we were able to get a relatively focused image. As seen in Figure 5, we were able to get a focused image of an 11.7 magnitude star with comparison stars surrounding it.  Thus, we can confirm that pETSI works, however, there are still some issues that need to be addressed, such as the elongated images of the stars. Due to time limitations we were not able to obtain a full spectrum of Kepler 1274, but Figure 6 exhibits pETSI’s ability to measure an exoplanet atmosphere.


## Conclusion
This research project confirms that pETSI was indeed successful and works well on smaller telescopes, such as the .9m telescope at McDonald Observatory. This instrument will be important when confirming atmospheres of TESS-identified targets with the goal of determining which targets are most valuable for future work by larger telescopes, like JWST and large ground based facilities. 


## References
[1] DePoy et al. 2018, ETSI proposal, 1-16  
[2] Kreidberg 2017 arXiv:astro-ph/1709.05941  
[3] Sing et al. 2016 Nature, 529, 59  