 Enhanced Semantic Segmentation of Drone Point Cloud Data for Autonomous Landing via Multi-Scale Feature Extraction and Attentive Pooling
==========

<p align="center">
        <img src="Pictures/09label.png" title="SemanticKITTI Point Cloud" width="42%"> <img src="Pictures/09 .png" title="AASPN Prediction" width="48%"><br>
        <em>LiDAR scan visualization of SemanticKITTI dataset(left) and the prediction result of PolarNet(right).</em>
</p>
We have developed the Aero Auto Pilot Segmentation Network (AAPSN) to enhance semantic segmentation of laser point cloud data from unmanned aerial vehicles (UAVs).  This approach addresses challenges such as the loss of spatial features during training and the variability in point cloud densities across different object scales.  By integrating a multi-scale feature extraction module and an attentive pooling mechanism, AAPSN effectively captures features of objects at varying scales and emphasizes spatial structure features during pooling.  This leads to significant improvements in segmentation accuracy and efficiency, with a mean Intersection over Union (mIoU) increase of 3.3% and 19.2% on two real urban LiDAR datasets, respectively.  These results demonstrate the effectiveness of AAPSN in enhancing the autonomy of UAV landing systems.

## Aero Auto Pilot Segmentation Network 





## How to get datasets:
```
Paris-lille-3D datasets: https://npm3d.fr/paris-lille-3d


semanticKITTI datasets: https://semantic-kitti.org/dataset.html#download
```

The folder structure for the datasets should be arranged as follows:
```
├── data
│   ├── semantickitti
│   │   ├── sequences
│   │   │   ├── 00
│   │   │   │   ├── labels
│   │   │   │   ├── velodyne
│   │   │   ├── 01
│   │   │   ├── ..
│   │   │   ├── 22
```

## How to get pretrained weights:
```
Pretrained weights: https://drive.google.com/drive/folders/1VAkqCPZxOqnCIragI0Xr0nJ0bdhsi0j1?usp=drive_link
```


🏆 期刊关联声明  
本项目是The Visual Computer期刊(ISSN 0178-2789)候选论文的官方实现，引用请使用：
```Bibtex:
@article{2025,
  title={Enhanced Semantic Segmentation of Drone Point Cloud Data for Autonomous Landing via Multi-Scale Feature Extraction and Attentive Pooling},
  author={Qian Gao},
  journal={The Visual Computer},
  year={2023},
  publisher={Springer}
}
