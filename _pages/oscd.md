---
layout: archive
title: "Onera Satellite Change Detection Dataset"
permalink: /oscd/
author_profile: true
---

{% include base_path %}


![Beirut images](/images/beirut-conc.png)

The Dataset
======
The Onera Satellite Change Detection dataset addresses the issue of detecting changes between satellite images from different dates.

It comprises 24 pairs of multispectral images taken from the [Sentinel-2 satellites](https://sentinel.esa.int/web/sentinel/missions/sentinel-2) between 2015 and 2018. Locations are picked all over the world, in Brazil, USA, Europe, Middle-East and Asia. For each location, registered pairs of 13-band multispectral satellite images obtained by the Sentinel-2 satellites are provided. Images vary in spatial resolution between 10m, 20m and 60m.

Pixel-level change ground truth is provided for all 14 training and 10 test image pairs. The annotated changes focus on urban changes, such as new buildings or new roads. These data can be used for training and setting parameters of change detection algorithms.


The Benchmark
======
The algorithms can be tested in a benchmark for change detection.

~~The ground truth for the 10 remaining images remain undisclosed. Change prediction maps can be uploaded for evaluation on the [IEEE GRSS DASE website](http://dase.grss-ieee.org/). Various metrics such as per-class accuracy and confusion matrices are automatically computed on the website, and are available for participants. Comparison to the best performing methods is provided in the leaderboard associated with this benchmark.~~ Update: the ground truth labels for the test images are now openly available.
  
References
======
If you use this work for your projects, please take the time to cite our paper:

[**Daudt, R.C.**, Le Saux, B., Boulch, A. and Gousseau, Y., 2018, July. *Urban Change Detection for Multispectral Earth Observation Using Convolutional Neural Networks*. In IEEE International Geoscience and Remote Sensing Symposium (IGARSS) 2018 (pp. 2115-2118). IEEE.](https://rcdaudt.github.io/publication/2018-08-22-urban-change-detection)

[[Preprint]](https://arxiv.org/abs/1810.08468) [[PDF]](http://rcdaudt.github.io/files/2018igarss-change-detection.pdf) [[BibTeX]](http://rcdaudt.github.io/files/daudt2018urban.bib) [[Dataset]](https://rcdaudt.github.io/oscd/) [[GitHub]](https://github.com/rcdaudt/patch_based_change_detection)


Links
======
You can download the dataset on IEEE DataPort webpage:

* [https://ieee-dataport.org/open-access/oscd-onera-satellite-change-detection](https://ieee-dataport.org/open-access/oscd-onera-satellite-change-detection)
* Mirrors:
  * [Images](https://partage.mines-telecom.fr/index.php/s/G93tRIAgLs1sVBM)
  * [Train labels](https://partage.mines-telecom.fr/index.php/s/2D6n03k58ygBSpu)
  * [Test labels](https://partage.imt.fr/index.php/s/gpStKn4Mpgfnr63)

<!---
Online evaluation using the hidden test annotations can be done using the IEEE GRSS DASE webpage:

#* [http://dase.grss-ieee.org/](http://dase.grss-ieee.org/)



--->

The Team
======
* [Rodrigo Caye Daudt](https://rcdaudt.github.io/), rodrigo.daudt@onera.fr
* [Bertrand Le Saux](https://blesaux.github.io/), bls@ieee.org
* [Alexandre Boulch](https://aboulch.github.io/), alexandre.boulch@valeo.com
* [Yann Gousseau](https://perso.telecom-paristech.fr/gousseau/), yann.gousseau@telecom-paris.fr
  

