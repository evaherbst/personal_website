---
permalink: /Resources/
title: "Resources"
excerpt: ""
header:
  overlay_color: "#333"
  actions:
    - label: "GitHub"
      url: "https://github.com/evaherbst"
    - label: "FigShare"
      url: https://figshare.com/authors/Eva_Herbst/5711444
    - label: "Morphosource"
      url: https://www.morphosource.org/users/11388
    - label: "Finite Element Zurich"
      url: https://fez-finite-element-zurich.github.io/
      


remeshing:
  - image_path: /assets/images/mesh_cleaning.png
    alt: "Blender Remeshing Guide"
    title: "Blender Remeshing Guide"
    excerpt: "[Workflow](https://github.com/evaherbst/Blender_remeshing_guide) for preparing meshes for FEA, 3D printing, or other biomechanical experiments. [Video tutorial here.](https://www.youtube.com/watch?v=XzAUn76NLXM&t=49s&ab_channel=FunkyMUG)"

segmentation:
  - image_path: /assets/images/trabecular_segmentation_video_EH_CBA_No3_20W_cropped.gif
    alt: "Trabecular Segmentation"
    title: "Trabecular Segmentation"
    excerpt: "[Code and guide](https://github.com/evaherbst/Trabecular_Segmentation_Avizo) on how to segment cortical and trabecular bone, using Avizo. Featured on èofficial Avizo plugin website!(https://www.thermofisher.com/software-em-3d-vis/xtra-library/xtras/trabecular-segmentation-workflow-for-murine-tibial-bone). [Video tutorial here.](https://youtu.be/cQ9sBu6SpJw)"


alpha:
  - image_path: /assets/images/alpha.png
    alt: "Alpha Shape Matlab Code"
    title: "Alpha Shape Matlab Code"
    excerpt: "[Matlab code](https://github.com/evaherbst/Alpha_graphs) for graphing and exporting alpha shapes from joint range of motion data, along with individual joint poses."
    
muscles:
  - image_path: /assets/images/Blender_muscles.png
    alt: "Muscles"
    title: "3D Muscle Modeling Add-on in Blender"
    excerpt: "[Blender add-on](https://github.com/evaherbst/MyoGenerator) for interactive 3D modeling of muscles"  
    
SFP:
  - image_path: /assets/images/SFP_gif.gif
    alt: "Spherical Frame Projections"
    title: "Spherical Frame Projections"
    excerpt: "[Matlab code](https://github.com/eeberhard/SFP) for visualizing joint range of motion, including interaction of degrees of freedom"
---
{% include feature_row id="SFP" type="left" %}
{% include feature_row id="segmentation" type="right" %}
{% include feature_row id="muscles" type="left" %}
{% include feature_row id="alpha" type="right" %}
{% include feature_row id="remeshing" type="left" %}



