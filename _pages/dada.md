---
layout: archive
title: "Guided Depth Super-Resolution by Deep Anisotropic Diffusion"
permalink: /dada/
author_profile: false
---

{% include base_path %}



**[<img src="/images/github-mark.svg" alt="GitHub" width="30"> Code](https://github.com/prs-eth/Diffusion-Super-Resolution) &emsp; -- &emsp; [<img src="/images/dada/CVRP2023.png" alt="CVPR23" width="100"> Proceedings](https://openaccess.thecvf.com/content/CVPR2023/html/Metzger_Guided_Depth_Super-Resolution_by_Deep_Anisotropic_Diffusion_CVPR_2023_paper.html) &emsp; -- &emsp; [<img src="/images/arxiv-logomark-small.svg" alt="arXiv" width="20"> arXiv](https://arxiv.org/abs/2211.11592)**


![Diffusion](/images/diffusion_6_x32.gif)


# Abstract

Performing super-resolution of a depth image using the guidance from an RGB image is a problem that concerns several fields, such as robotics, medical imaging, and remote sensing. While deep learning methods have achieved good results in this problem, recent work highlighted the value of combining modern methods with more formal frameworks. In this work we propose a novel approach which combines guided anisotropic diffusion with a deep convolutional network and advances the state of the art for guided depth super-resolution. The edge transferring/enhancing properties of the diffusion are boosted by the contextual reasoning capabilities of modern networks, and a strict adjustment step guarantees perfect adherence to the source image. We achieve unprecedented results in three commonly used benchmarks for guided depth super resolution. The performance gain compared to other methods is the largest at larger scales, such as x32 scaling. Code for the proposed method will be made available to promote reproducibility of our results.


![Main schematic](/images/dada_schematic.png)


# CVPR 2023 Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/7RgXJz_3kcg" title="CVPR Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/7RgXJz_3kcg?autoplay=1" title="CVPR Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->
  


# Additional Results


| Image | x8 | x32 |
| :----: | :----: | :----: |
| <img src="/images/dada/img-00.png" alt="CVPR23" width="100"> | [Video link](https://www.youtube.com/watch?v=GI4ZnGsVK9s) | [Video link](https://www.youtube.com/watch?v=9fy24viqDDw) |
| <img src="/images/dada/img-06.png" alt="CVPR23" width="100"> | [Video link](https://www.youtube.com/watch?v=-SZQDWfdOYw) | [Video link](https://www.youtube.com/watch?v=U1vatYukmqg) |
| <img src="/images/dada/img-30.png" alt="CVPR23" width="100"> | [Video link](https://www.youtube.com/watch?v=XlRsXHW4vME) | [Video link](https://www.youtube.com/watch?v=1jx8jobP-a8) |
| <img src="/images/dada/img-31.png" alt="CVPR23" width="100"> | [Video link](https://www.youtube.com/watch?v=23TdoJclEcY) | [Video link](https://www.youtube.com/watch?v=G6iD4HrcPck) |
| <img src="/images/dada/img-59.png" alt="CVPR23" width="100"> | [Video link](https://www.youtube.com/watch?v=H9njLjNXTKA) | [Video link](https://www.youtube.com/watch?v=86NvzElw3Ts) |





<!-- <div class="video-container"><iframe width="560" height="315" src="https://www.youtube.com/embed/7RgXJz_3kcg" title="CVPR Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div> <div class="video-container"><iframe width="560" height="315" src="https://www.youtube.com/embed/7RgXJz_3kcg" title="CVPR Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div> -->

# BibTeX citation

```
@InProceedings{Metzger_2023_CVPR,
    author    = {Metzger, Nando and Daudt, Rodrigo Caye and Schindler, Konrad},
    title     = {Guided Depth Super-Resolution by Deep Anisotropic Diffusion},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2023},
    pages     = {18237-18246}
}
```