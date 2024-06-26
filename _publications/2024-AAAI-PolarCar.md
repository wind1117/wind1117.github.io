---
layout: archive
title: "Exploiting Polarized Material Cues for Robust Car Detection"
collection: publications
permalink: /publication/2024-AAAI-PolarCar
paperurl: 'https://arxiv.org/abs/2401.02606'
---

Wen Dong<sup>1</sup>, Haiyang Mei<sup>1,2</sup>, Ziqi Wei<sup>3,4,\*</sup>, Ao Jin<sup>1</sup>, Sen Qiu<sup>1</sup>, Qiang Zhang<sup>1</sup>, Xin Yang<sup>1,\*</sup>  
<sup>1</sup> Key Laboratory of Social Computing and Cognitive Intelligence, Dalian University of Technology  
<sup>2</sup> Show Lab, National University of Singapore  
<sup>3</sup> Institute of Automation, Chinese Academy of Sciences  
<sup>4</sup> State Key Laboratory of Structural Analysis for Industrial Equipment, Dalian University of Technology  

Contact us: xinyang@dlut.edu.cn  

The 38th Annual AAAI Conference on Artificial Intelligence (AAAI 2024)  

![](..\images\teaser_aaai24_pcdnet.png)

### Abstract

Car detection is an important task that serves as a crucial prerequisite for many automated driving functions. The large variations in lighting/weather conditions and vehicle densities of the scenes pose significant challenges to existing car detection algorithms to meet the highly accurate perception demand for safety, due to the unstable/limited color information, which impedes the extraction of meaningful/discriminative features of cars. In this work, we present a novel learning-based car detection method that leverages trichromatic linear polarization as an additional cue to disambiguate such challenging cases. A key observation is that polarization, characteristic of the light wave, can robustly describe intrinsic physical properties of the scene objects in various imaging conditions and is strongly linked to the nature of materials for cars (*e.g.*, metal and glass) and their surrounding environment (*e.g.*, soil and trees), thereby providing ***reliable*** and ***discriminative*** features for robust car detection in challenging scenes. To exploit polarization cues, we first construct a pixel-aligned RGB-Polarization car detection dataset, which we subsequently employ to train a novel multimodal fusion network. Our car detection network dynamically integrates RGB and polarization features in a request-and-complement manner and can explore the intrinsic material properties of cars across all learning samples. We extensively validate our method and demonstrate that it outperforms state-of-the-art detection methods. Experimental results show that polarization is a powerful cue for car detection.

### Downloads

\[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27922)\|[Pre-trained model](https://pan.baidu.com/s/1Bjb6IeQuhbt1zvypJZ-cXQ?pwd=ujzb)\|[Source code](https://github.com/wind1117/AAAI24-PCDNet)\]

### Dataset

Both training set and testing set can be obtained via form request at [here](http://rgbp.dluticcd.com/).

### Recommended citation

@InProceedings{Wen_2024_AAAI_PCDNet,  
    title = {Exploiting Polarized Material Cues for Robust Car Detection},  
    author = {Dong, Wen and Mei, Haiyang and Wei, Ziqi and Jin, Ao and Qiu, Sen and Zhang, Qiang and Yang, Xin},  
    booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence},  
    year = {2024}  
}
{: .notice}
