---
permalink: /research/
title: "Research"
excerpt: ""
header:
  overlay_color: "#333"


light_sheet_gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"

sim_gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"


sub_cellular_light_sheet:
  - image_path: /assets/images/research.png
    alt: "Sub-cellular light sheet microscopy"
    title: "Sub-cellular light sheet microscopy"
    excerpt: "At the [MRC LMB](https://www2.mrc-lmb.cam.ac.uk), I have constructed a high resolution light sheet microscope which I am now using with biologists to study sub-cellular biological processes.
    This microscope is easy to construct and use, uses only open-source software for control and data processing, and is capable of generating different light sheet profiles through field synthesis (see below).
    We hope to make the design openly available, along with detailed documentation, in due course.
    For now, if you are interested in copying our design, please contact me via email."

light_sheet_illumination_performance:
  - image_path: /assets/images/light_sheet_mtf_comparison.png
    alt: "Light sheet illumination performance"
    title: "Light sheet illumination performance"
    excerpt: "Key to the performance of a light sheet microscope is the profile of illumination used.
    I have theoretically and experimentally investigated advanced profiles presented in the literature and drawn some surprising conclusions.
    A manuscript describing these results is currently in the final stages of preparation, with a selection of my results being presented [in my FOM2019 talk](/jmanton/assets/presentations/FOM2019.pptx)."

improved_axial_resolution_through_field_synthesis:
  - image_path: /assets/images/light_sheet_resolution.png
    alt: "Improved axial resolution through field synthesis"
    title: "Improved axial resolution through field synthesis"
    excerpt: "Reto Fiolka and co-workers recently introduced a new Fourier theorem: [field synthesis](https://doi.org/10.1038/s41592-019-0327-9).
    As this allows for illumination with a 100 % spatial duty-cycle irrespective of the pupil function, I have been investigating different beam profiles to see if overall instrument resolution and contrast can be improved.
    In addition, I have devised a method that further exploits the experimental apparatus used for field synthesis to enhance axial resolution and improve deconvolution."

oblique_plane_microscopy_imaging_performance:
  - image_path: /assets/images/opm.png
    alt: "Oblique plane microscopy imaging performance"
    title: "Oblique plane microscopy imaging performance"
    excerpt: "Until recently, [oblique plane microscopy](https://doi.org/10.1364/OE.16.020306) was limited to low numerical aperture systems. Now, Bin Yang and colleagues have [developed a method](https://doi.org/10.1038/s41592-019-0401-3) that allows for higher numerical aperture by exploiting refraction at a carefully positioned interface. This has [further been developed](https://andrewgyork.github.io/high_na_single_objective_lightsheet/) by Alfred Millett-Sikking and Andrew York such that almost no numerical aperture is sacrificed. However, both these systems now operate in a manner very different from a conventional light sheet microscope or even other oblique plane variants. I am now developing a theoretical description of their behaviour that explains the unusual PSF seen in experimental data and which will allow for a fair comparison of performance to other light sheet approaches."


enhanced_axial_resolution_through_mirrored_illumination:
  - image_path: /assets/images/mirrored_sim.png
    alt: "Enhanced axial resolution through mirrored illumination"
    title: "Enhanced axial resolution through mirrored illumination"
    excerpt: "Wide-field fluorescence microscopy, while much faster than confocal microscopy, suffers from a lack of optical sectioning and poor axial resolution. 3D structured illumination microscopy (SIM) has been demonstrated to provide optical sectioning and to double the achievable resolution both laterally and axially, but even with this the axial resolution is still worse than the lateral resolution of unmodified wide-field detection. Interferometric schemes using two high numerical aperture objectives, such as 4Pi confocal and I5S microscopy, have improved the axial resolution beyond that of the lateral, but at the cost of a significantly more complex optical setup. Along with Reto Fiolka and Florian Ströhl, I have developed a simpler dual-objective scheme which we propose can be easily added to an existing 3D-SIM microscope, providing lateral and axial resolutions in excess of 125 nm with conventional fluorophores. For more information, [read our preprint](https://arxiv.org/abs/1810.04590)."


ellipsoid_localisation_microscopy:
  - image_path: /assets/images/elm.png
    alt: "Ellipsoid localisation microscopy"
    title: "Super-resolution measurements from diffraction-limited data"
    excerpt: "As part of my PhD work, I developed a method that could make sub-diffraction measurements of certain structures given conventional microscopy data. Using a geometric model of the structure of interest in combination with a description of the image formation process, our method fits simulated images to real data, extracting model parameters such as shell radius and orientation. Using this, we made measurements of bacterial spore coats with 10 nm precision, despite the 200 nm resolution limit inherent in the raw data. For more information, read our publications describing [the open source software I developed](https://doi.org/10.1088/2050-6120/aac28e), [our initial biological results](https://doi.org/10.1016/j.bpj.2015.09.023), and [further results in another species](https://doi.org/10.1128/AEM.00760-18). Other examples of its use are given for [Bacillus megaterium](https://doi.org/10.1093/femsle/fnz146) and [Newcastle disease virus and influenza](https://doi.org/10.7554/eLife.40183)."

trispim:
  - image_path: /assets/images/trispim.png
    alt: "An approach for isotropic super-resolution in light sheet microscopy"
    title: "An approach for isotropic super-resolution in light sheet microscopy"
    excerpt: "As part of my PhD work, I proposed a three-objective light sheet microscopy geometry which, through a combination of skewed lattice light sheet excitation through two objectives and the computational fusion of images taken from two separate lens pairings, would allow for isotropic super-resolution in mesoscopic samples. I also showed that simultaneous coherent excitation through two excitation objectives could further substantially increase resolution. Simulations demonstrate that my design could achieve a resolution of 120 nm for EGFP imaging while minimizing photodamage. For more details, [read the publication](https://doi.org/10.1364/OL.41.004170)."

diffraction:
  - image_path: /assets/images/balalaika_beam.gif
    alt: "High numerical aperture beam forming"
    title: "High numerical aperture beam forming"
    excerpt: "At high numerical apertures, it is important to account for the curvature of the Ewald sphere and the vectorial nature of light in order to obtain accurate simulations of the electric field in the focal region of an objective lens. As part of my PhD, I implemented the fast Debye diffraction integral approach of [Leutenegger et al.](https://doi.org/10.1364/OE.14.011277) and used this to investigate the effect of aberrations in STED microscopy and novel confocal and light sheet PSFs. I also generated some interesting non-diffracting beam profiles, such as the 'Balalaika' beam shown to the left. If you have an idea how this might be useful please let me know, as I failed to find a use for them... For more details and to obtain a copy of the simulation code, check the [Software](/jmanton/software/) page."

nat:
  - image_path: /assets/images/flybrain.png
    alt: "Computational tools for neuroanatomy"
    title: "Computational tools for neuroanatomy"
    excerpt: "Before starting my PhD, I worked as a Research Assistant for a year in [Greg Jefferis' neurobiology group](https://jefferislab.org/). In addition to some functional imaging, I spent most of my time developing computational tools for neuroanatomy, adding to Greg's [nat](https://github.com/natverse/nat) package and [associated tools](https://github.com/natverse). I am also responsible for the [online result browser](http://flybrain.mrc-lmb.cam.ac.uk/si/nblast/www/clusters/) and [tools](http://flybrain.mrc-lmb.cam.ac.uk/si/nblast/www/nblast_online/) for [NBLAST](http://flybrain.mrc-lmb.cam.ac.uk/si/nblast/www/paper/), a neuron similarity tool developed by Greg and Marta Costa. I also helped develop [bridging registrations](https://doi.org/10.1101/006353), unifying data from over 30,000 publicly available images, with resources including the 3D atlas embodying the new standard Drosophila anatomical nomenclature and the largest single neuron databank yet available in any species."
---

# Current research
<!-- {% include gallery id="light_sheet_gallery" %} -->

{% include feature_row id="sub_cellular_light_sheet" type="left" %}
{% include feature_row id="light_sheet_illumination_performance" type="right" %}
{% include feature_row id="improved_axial_resolution_through_field_synthesis" type="left" %}
{% include feature_row id="oblique_plane_microscopy_imaging_performance" type="right" %}

<!-- {% include gallery id="sim_gallery" %} -->

{% include feature_row id="enhanced_axial_resolution_through_mirrored_illumination" type="left" %}


# Previous Research
<!-- {% include gallery id="previous_research_gallery" %} -->

{% include feature_row id="ellipsoid_localisation_microscopy" type="left" %}
{% include feature_row id="trispim" type="right" %}
{% include feature_row id="diffraction" type="left" %}
{% include feature_row id="nat" type="right" %}
