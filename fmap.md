---
layout: default
title: OmniZoomer Learning to Move and Zoom in on Sphere at High-Resolution
description: arxiv
---



<!-- <a href="https://www.youtube.com/watch?v=ty531p2Me7Q">
  <img src="assets/images/cvpr23/egvsr.png" alt="eres" style="width: 500""/>
</a> -->

<!-- [video](https://www.youtube.com/watch?v=ty531p2Me7Qng) -->
[![png](https://i.328888.xyz/2023/03/16/K5vCL.png)](https://www.youtube.com/watch?v=ty531p2Me7Qng)

# Abstract

Omnidirectional images (ODIs) have become increasingly popular, as their large field-of-view (FoV) can offer viewers the chance to freely choose the view directions in immersive environments such as virtual reality. The M\"obius transformation is typically employed to further provide the opportunity for movement and zoom on ODIs, but applying it to the image level often results in blurry effect and aliasing problem. In this paper, we propose a novel deep learning-based approach, called \textbf{OmniZoomer}, to incorporate the M\"obius transformation into the network for movement and zoom on ODIs. By learning various transformed feature maps under different conditions, the network is enhanced to handle the increasing edge curvatures, which alleviates the blurry effect. Moreover, to address the aliasing problem, we propose two key components. Firstly, to compensate for the lack of pixels for describing curves, we enhance the feature maps in the high-resolution (HR) space and calculate the transformed index map with a spatial index generation module. Secondly, considering that ODIs are inherently represented in the spherical space, we propose a spherical resampling module that combines the index map and HR feature maps to transform the feature maps for better spherical correlation. The transformed feature maps are decoded to output a zoomed ODI. Experiments show that our method can produce HR and high-quality ODIs with the flexibility to move and zoom in to the object of interest. 


# Publication

```
@article{fmapHua2023,
  title={FMapping: Factorized Efficient Neural Field Mapping for Real-Time Dense RGB SLAM},
  author={Yunfan Lu, Zipeng Wang, Minjie Liu, Hongjian Wang, Lin Wang},
  year={2023arxiv}
}
```
