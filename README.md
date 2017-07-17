# Pretrained simplified_mobilenet model on ImageNet
A simplify version of mobilenet, with less group and feature maps, trained on Imagenet with Caffe.
The top-1/5 accuracy rates by using single center crop (crop size: 224x224, image size: 256x256):

Network|Top-1|Top-5|Download|Architecture
:---:|:---:|:---:|:---:|:---:
MobileNet| 66.6%| 87.4%| [caffemodel (11 MB)](https://pan.baidu.com/s/1jHK0gaa)| [deploy](https://github.com/farmingyard/simplified_mobilenet/blob/master/simplified_mobilenet_deploy.prototxt)
