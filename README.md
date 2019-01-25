# Yolo-Model-Zoo

**This is an experimental project , try to use different backbone models with yolov3 detector

## VOC

Train on VOC2007 and VOC2012 trainval and test on VOC2007

network|mAP|resolution|macc|param|
:---:|:---:|:---:|:---:|:---:|
[PVA-YOLOv3](https://github.com/sanghoon/pva-faster-rcnn)|0.703|416|2.55G|4.72M|
[Pelee-YOLOv3](https://github.com/Robert-JunWang/Pelee)|0.703|416|4.25G|3.85M|
[DenseNet_121-YOLOv3](https://github.com/shicai/DenseNet-Caffe)||416|9.86G|7.07M|
Resnet-18|0.714|416|6.33G|11.24M|

* All of the models trained from imagenet pre-train weights , you can easlity to find download link from author's page
* These models are not optimized , but you can modify architecture and try to find best accuracy and inference speed. 

## Linux Platform

[Run on linux](https://github.com/eric612/MobileNet-YOLO)

## Windows Platform

[Run on windows](https://github.com/eric612/Caffe-YOLOv2-Windows)
