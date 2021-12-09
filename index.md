Alexander Lehner \*,1,2 &nbsp; Stefano Gasperini \*,1,2 &nbsp; Alvaro Marcos-Ramiro 2 \
Michael Schmidt 2 &nbsp; Mohammad-Ali Nikouei Mahani 2 &nbsp; Nassir Navab 1,3\
Benjamin Busam 1 &nbsp; Federico Tombari 1,4

\* equal contribution\
1 Technical University of Munich\
2 BMW Group\
3 Johns Hopkins University\
4 Google

### Download the CrashD dataset
- __[Part 1](https://drive.google.com/file/d/18tOcuHBzYEkMDOKoPshUBVOIKAHxEvnp/view?usp=sharing)__ - Scenes with undamaged cars
- __[Part 2](https://drive.google.com/file/d/1b4bVVpPcIwCSnFTU9B8S33fsQNCTPE8j/view?usp=sharing)__ - Scenes with damaged cars
- __[Data format description](data_format.txt)__

License: [CC BY 4.0 International](https://creativecommons.org/licenses/by/4.0/)

### Paper
- (soon) available on __[arXiv](https://arxiv.org/)__

### Abstract

As 3D object detection on point clouds relies on the geometrical relationships between the points, non-standard object shapes can hinder a method's detection capability. However, in safety-critical settings, robustness on out-of-distribution and long-tail samples is fundamental to circumvent dangerous issues, such as the misdetection of damaged or rare cars. In this work, we substantially improve the generalization of 3D object detectors to out-of-domain data by taking into account deformed point clouds during training. We achieve this with 3D-VField: a novel method that plausibly deforms objects via vectors learned in an adversarial fashion. Our approach constrains 3D points to slide along their sensor view rays while neither adding nor removing any of them. The obtained vectors are transferrable, sample-independent and preserve shape smoothness and occlusions. By augmenting normal samples with the deformations produced by these vector fields during training, we significantly improve robustness against differently shaped objects, such as damaged/deformed cars, even while training only on KITTI. Towards this end, we propose and share open source CrashD: a synthetic dataset of realistic damaged and rare cars, with a variety of crash scenarios. Extensive experiments on KITTI, Waymo, our CrashD and SUN RGB-D show the high generalizability of our techniques to out-of-domain data, different models and sensors, namely LiDAR and ToF cameras, for both indoor and outdoor scenes.

Citation: TBD
