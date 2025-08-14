# Heterogeneous Skeleton-Based Action Representation Learning, CVPR 2025
[Heterogeneous Skeleton-Based Action Representation Learning](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Heterogeneous_Skeleton-Based_Action_Representation_Learning_CVPR_2025_paper.pdf), [Arxiv](https://arxiv.org/abs/2506.03481) 

Please refer to https://github.com/wengwanjiang/USDRL for implemetation. The main differences are as follows:
1) For 2D skeleton dataset, please download from https://github.com/kennymckormick/pyskl/blob/main/tools/data/README.md
2) 3D Pose Estimation can be implemented using a small netwrok with FC layer followd by BN. We find that the 3D pose estimation module has less impact on the NTU dataset but greater impact on the PKU-MMD dataset.

```
@inproceedings{wang2025heterogeneous,
  title={Heterogeneous Skeleton-Based Action Representation Learning},
  author={Wang, Hongsong and Ma, Xiaoyan and Kuang, Jidong and Gui, Jie},
  booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
  pages={19154--19164},
  year={2025}
}
