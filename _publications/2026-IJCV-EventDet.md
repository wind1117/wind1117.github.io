---
layout: archive
title: "You Only Look Intensity Once: Event-Driven Long-Term High-Speed Object Detection"
collection: publications
permalink: /publication/2026-IJCV-EventDet
paperurl: 'https://link.springer.com/article/10.1007/s11263-026-02749-8'
---

Wen Dong<sup>1,2</sup>, Haiyang Mei<sup>1,3</sup>, Yinglian Ji<sup>1</sup>, Yutong Jiang<sup>4</sup>, Ziqi Wei<sup>5</sup>, Shengfeng He<sup>2</sup>, Xin Yang<sup>1,\*</sup>  
<sup>1</sup> Key Laboratory of Social Computing and Cognitive Intelligence (Ministry of Education), Dalian University of Technology  
<sup>2</sup> School of Computing and Information Systems, Singapore Management University  
<sup>3</sup> Show Lab, National University of Singapore  
<sup>4</sup> Chinese Scholartree Ridge State Key Laboratory, Vehicle Research Institute  
<sup>5</sup> Institute of Automation, Chinese Academy of Sciences  

Contact us: xinyang@dlut.edu.cn  

International Journal of Computer Vision (IJCV 2026)  

![](..\images\teaser_ijcv26_dpnet.png)

### Abstract

Cooperating intensity/RGB frames with event signals offers a practical and effective solution for high-speed object detection, while existing methods rely on frequent RGB frame updates, typically every 0.2 seconds, to preserve scene context. This leads to high computational costs, redundancy across frames, and latency issues, especially on edge devices. In this work, we propose the **D**elta **P**erception **Net**work (DPNet), a novel learning-based detector that requires only a single RGB frame at the beginning of a sequence to detect high-speed objects over a 5-second duration, 25 times longer than prior methods. The key insight is that the initial frame can serve as a durable scene prior, while the continuous event stream supplies sufficient motion information to update this prior without needing further intensity frames. This design allows DPNet to track dynamic scene changes efficiently and accurately over extended periods. At the core of DPNet is a Delta Perception module that emphasizes temporal changes, and a Grid Sampling GRU that incrementally maintains and refines the scene representation. Extensive experiments show that DPNet outperforms state-of-the-art frame-based, event-based, and fusion-based detectors. Our results demonstrate that long-duration, high-speed object detection is not only feasible but also efficient using a single intensity/RGB frame and continuous event input, enabling real-time performance with reduced computational demands.

### Downloads

\[[Paper](https://link.springer.com/article/10.1007/s11263-026-02749-8)\|[Pre-trained model](/publication/2026-IJCV-EventDet)\|[Source code](https://github.com/wind1117/YOLIO)\]

### Dataset

Both training set and testing set can be obtained via form request at [here](/publication/2026-IJCV-EventDet).

### Recommended citation

@article{dong2026you,
  title={You Only Look Intensity Once: Event-Driven Long-Term High-Speed Object Detection},
  author={Dong, Wen and Mei, Haiyang and Ji, Yinglian and Jiang, Yutong and Wei, Ziqi and He, Shengfeng and Yang, Xin},
  journal={International Journal of Computer Vision},
  volume={134},
  number={4},
  pages={149},
  year={2026},
  publisher={Springer}
}
{: .notice}