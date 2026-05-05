---
layout: archive
title: "PolarDepth: Monocular Transparent Object Depth from Polar-Physics Priors"
collection: publications
permalink: /publication/2026-ICML-PolarDep
paperurl: '.'
---

Wen Dong<sup>1,2</sup>, Haiyang Mei<sup>1,3</sup>, Yinglian Ji<sup>1</sup>, Zijun Zhang<sup>1</sup>, Wenyuan Zhang<sup>1</sup>, Pengwei Luo<sup>1</sup>, Bo Dong<sup>4</sup>, Shengfeng He<sup>2</sup>, Xin Yang<sup>1,\*</sup>  
<sup>1</sup> Key Laboratory of Social Computing and Cognitive Intelligence (Ministry of Education), Dalian University of Technology  
<sup>2</sup> School of Computing and Information Systems, Singapore Management University  
<sup>3</sup> Show Lab, National University of Singapore  
<sup>4</sup> Cephia AI, INC.  

Contact us: xinyang@dlut.edu.cn  

Forty-third International Conference on Machine Learning (ICML 2026)  

![](..\images\teaser_icml26_polardep.png)

### Abstract

Depth estimation for transparent objects remains a fundamental challenge, as RGB-based cues often fail in regions affected by refraction and light transmission. Polarization provides physically grounded information related to surface orientation and material properties, offering reliable geometric cues even in the absence of texture. In this work, we introduce PolarDepth, a monocular framework that incorporates both RGB and polarization inputs, including the degree and angle of linear polarization (DoLP and AoLP), to estimate dense depth and localize transparent regions. PolarDepth injects polarization-derived physical priors by estimating the refractive index, zenith angle, and azimuth angle from polarization measurements and embedding them into an implicit geometric representation that constrains depth inference in ambiguous transparent regions. To support model development and evaluation, we introduce PTOD, a dataset with synchronized RGB, polarization, and depth data and manually annotated transparent region masks. Experimental results demonstrate that PolarDepth achieves state-of-the-art performance in transparent object depth estimation. The findings highlight the effectiveness of embedding polarization-derived physical priors into learned representations for robust perception in complex visual environments.

### Downloads

\[[Paper](/publication/2026-ICML-PolarDep)\|[Pre-trained model](/publication/2026-ICML-PolarDep)\|[Source code](/publication/2026-ICML-PolarDep)\]

### Dataset

Both training set and testing set can be obtained via form request at [here](/publication/2026-ICML-PolarDep).

### Recommended citation

@article{dong2026polardep,  
  title={PolarDepth: Monocular Transparent Object Depth from Polar-Physics Priors},  
  author={Dong, Wen and Mei, Haiyang and Ji, Yinglian and Zhang, Zijun and Zhang, Wenyuan and Luo Pengwei and Dong, Bo and He, Shengfeng and Yang, Xin},  
  journal={Forty-third International Conference on Machine Learning}, 
  year={2026}, 
}
{: .notice}