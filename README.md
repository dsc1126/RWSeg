## Collaborative Propagation on Multiple Instance Graphs for 3D Instance Segmentation with Single-point Supervision (ICCV2023)

Code for the paper **Collaborative Propagation on Multiple Instance Graphs for 3D Instance Segmentation with Single-point Supervision**, ICCV 2023.

**Authors**: Shichao Dong, Ruibo Li, Jiacheng Wei, Fayao Liu, Guosheng Lin

## Introduction
Instance segmentation on 3D point clouds has been attracting increasing attention due to its wide applications, especially in scene understanding areas. However, most existing methods operate on fully annotated data while manually preparing ground-truth labels at point-level is very cumbersome and labor-intensive. To address this issue, we propose a novel weakly supervised method RWSeg that only requires labeling one object with one point. With these sparse weak labels, we introduce a unified framework with two branches to propagate semantic and instance information respectively to unknown regions using self-attention and a cross-graph random walk method. Specifically, we propose a Cross-graph Competing Random Walks (CRW) algorithm that encourages competition among different instance graphs to resolve ambiguities in closely placed objects, improving instance assignment accuracy. RWSeg generates high-quality instance-level pseudo labels. Experimental results on ScanNet-v2 and S3DIS datasets show that our approach achieves comparable performance with fully-supervised methods and outperforms previous weaklysupervised methods by a substantial margin.

## Contact
If you have any questions or suggestions about this repo, please feel free to contact me (scdong@ntu.edu.sg).

## Citation
If you find this project useful, please consider citing:
```
@InProceedings{Dong_2023_ICCV,
    author    = {Dong, Shichao and Li, Ruibo and Wei, Jiacheng and Liu, Fayao and Lin, Guosheng},
    title     = {Collaborative Propagation on Multiple Instance Graphs for 3D Instance Segmentation with Single-point Supervision},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2023},
    pages     = {16665-16674}
}
```
