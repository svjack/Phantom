# Phantom: Subject-Consistent Video Generation via Cross-Modal Alignment

<div align="center">
  
[![arXiv](https://img.shields.io/badge/arXiv%20paper-2502.11079-b31b1b.svg)](https://arxiv.org/abs/2502.11079)&nbsp;
[![project page](https://img.shields.io/badge/Project_page-More_visualizations-green)](https://phantom-video.github.io/Phantom/)&nbsp;
  
</div>


> [**Phantom: Subject-Consistent Video Generation via Cross-Modal Alignment**](https://arxiv.org/abs/2502.11079)<br>
> [Lijie Liu](https://liulj13.github.io/)<sup> * </sup>, [Tianxiang Ma](https://tianxiangma.github.io/)<sup> * </sup>, [Bingchuan Li](https://scholar.google.com/citations?user=ac5Se6QAAAAJ)<sup> * &dagger;</sup>, [Zhuowei Chen](https://scholar.google.com/citations?user=ow1jGJkAAAAJ)<sup> * </sup>, [Jiawei Liu](https://scholar.google.com/citations?user=X21Fz-EAAAAJ), [Qian He](https://scholar.google.com/citations?user=9rWWCgUAAAAJ), Xinglong Wu
> <br><sup> * </sup>Equal contribution,<sup> &dagger; </sup>Project lead
> <br>Intelligent Creation Team, ByteDance<br>

## Overview
Phantom is a unified video generation framework for single and multi-subject references, built on existing text-to-video and image-to-video architectures. It achieves cross-modal alignment using text-image-video triplet data by redesigning the joint text-image injection model. Additionally, it emphasizes subject consistency in human generation while enhancing ID-preserving video generation.

## Comparative Results 🆚
- **Identity Preserving Video Generation**.
![image](./assets/images/id_eval.png)
- **Single Reference Subject-to-Video Generation**.
![image](./assets/images/ip_eval_s.png)
- **Multi-Reference Subject-to-Video Generation**.
![image](./assets/images/ip_eval_m_00.png)

## Acknowledgements
We would like to express our gratitude to the SEED team for their support. Special thanks to Lu Jiang, Haoyuan Guo, Zhibei Ma, and Sen Wang for their assistance with the model and data. In addition, we are also very grateful to Siying Chen, Qingyang Li, and Wei Han for their help with the evaluation.

## BibTeX
```bibtex
@article{liu2025phantom,
  title={Phantom: Subject-Consistent Video Generation via Cross-Modal Alignment},
  author={Liu, Lijie and Ma, Tianxaing and Li, Bingchuan and Chen, Zhuowei and Liu, Jiawei and He, Qian and Wu, Xinglong},
  journal={arXiv preprint arXiv:2502.11079},
  year={2025}
}
```