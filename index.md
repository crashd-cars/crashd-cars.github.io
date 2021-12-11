Alexander Lehner \* &nbsp; Stefano Gasperini \* &nbsp; Alvaro Marcos-Ramiro \
Michael Schmidt &nbsp; Mohammad-Ali Nikouei Mahani &nbsp; Nassir Navab \
Benjamin Busam &nbsp; Federico Tombari

\* equal contribution

Technical University of Munich &nbsp; BMW Group &nbsp; Johns Hopkins University &nbsp; Google

### Download the CrashD dataset
- __[Part 1](https://drive.google.com/file/d/18tOcuHBzYEkMDOKoPshUBVOIKAHxEvnp/view?usp=sharing)__ - Scenes with undamaged cars
- __[Part 2](https://drive.google.com/file/d/1b4bVVpPcIwCSnFTU9B8S33fsQNCTPE8j/view?usp=sharing)__ - Scenes with damaged cars
- __[Data format description](data_format.txt)__

License: [CC BY 4.0 International](https://creativecommons.org/licenses/by/4.0/)

### Paper
- available on __[arXiv](https://arxiv.org/abs/2112.04764)__

### Abstract

As 3D object detection on point clouds relies on the geometrical relationships between the points, non-standard object shapes can hinder a method's detection capability. However, in safety-critical settings, robustness on out-of-distribution and long-tail samples is fundamental to circumvent dangerous issues, such as the misdetection of damaged or rare cars. In this work, we substantially improve the generalization of 3D object detectors to out-of-domain data by taking into account deformed point clouds during training. We achieve this with 3D-VField: a novel method that plausibly deforms objects via vectors learned in an adversarial fashion. Our approach constrains 3D points to slide along their sensor view rays while neither adding nor removing any of them. The obtained vectors are transferrable, sample-independent and preserve shape smoothness and occlusions. By augmenting normal samples with the deformations produced by these vector fields during training, we significantly improve robustness against differently shaped objects, such as damaged/deformed cars, even while training only on KITTI. Towards this end, we propose and share open source CrashD: a synthetic dataset of realistic damaged and rare cars, with a variety of crash scenarios. Extensive experiments on KITTI, Waymo, our CrashD and SUN RGB-D show the high generalizability of our techniques to out-of-domain data, different models and sensors, namely LiDAR and ToF cameras, for both indoor and outdoor scenes.

### Citation
```
@misc{lehner20213dvfield,
      title={{3D-VField: Learning to Adversarially Deform Point Clouds for Robust 3D Object Detection}}, 
      author={Alexander Lehner and Stefano Gasperini and Alvaro Marcos-Ramiro and Michael Schmidt and Mohammad-Ali Nikouei Mahani and Nassir Navab and Benjamin Busam and Federico Tombari},
      year={2021},
      eprint={2112.04764},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
