# Kaggle Global Wheat Detection 

My attempts to solve the now closed [competition](https://www.kaggle.com/c/global-wheat-detection). Notice that both the attempts are liscenced and cannot be used to submit to the competition. This was actually my internship project.

### Used:

I have used a YOLOv5 ([ultralytics](https://github.com/ultralytics/yolov5)) and Faster-RCNN ([model config file](https://github.com/facebookresearch/detectron2/blob/master/configs/COCO-Detection/faster_rcnn_X_101_32x8d_FPN_3x.yaml)) ([Detectron2](https://github.com/facebookresearch/detectron2)) approach to detect bounding boxes for wheatheads. With the latter I achieved good AP score averaged across various IoU.

