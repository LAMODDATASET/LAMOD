## LAMOD Dataset
**LAMOD (Low-Altitude Moving Object Detection)** is an extended dataset compiled from various sequences of [VIVID](http://vision.cse.psu.edu/data/vividEval/datasets/datasets.html) and [UAV123](https://ivul.kaust.edu.sa/Pages/pub-benchmark-simulator-uav.aspx) datasets.  The primary aim of this work is to provide a reliable and well-maintained dataset for moving object detection evaluation, especially for moving aerial platforms.

Sequences are hand-annotated for moving objects in every frame.
Ground-truth annotation includes the values for *top left x*, *top left y* , *width* and *height*.
```shell
top_left_x,top_left_y, width, height
```
The annotations are available in .txt format for each frame.

In the first batch, annotations for 14 sequences are released. 


| VIVID Sequences  | UAV123 Sequences |
| ------------- | ------------- |
| egtest01, egtest02, egtest03, egtest04, egtest05, redteam| car1, car2, car3, car4, car6, car8, car10, person12|


## Contributions
If you find any mistakes in the labels, please report them in the GitHub issues section.

If you want to contribute via adding labels for new sequences, we suggest you to do so for publicly available dataset sequences (i.e. UAV123 Dataset).

## Citing LAMOD Dataset
```shell
@InProceedings{Logoglu_2017_ICCV,
author = {Berker Logoglu, K. and Lezki, Hazal and Kerim Yucel, M. and Ozturk, Ahu and Kucukkomurler, Alper and Karagoz, Batuhan and Erdem, Erkut and Erdem, Aykut},
title = {Feature-Based Efficient Moving Object Detection for Low-Altitude Aerial Platforms},
booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
month = {Oct},
year = {2017}
}
```
