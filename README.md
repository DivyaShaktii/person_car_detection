# person_car_detection
Custom trained Yolov3 for car and person detection


Model name  : Yolo v3

Link to Framework :  https://github.com/ultralytics/yolov3  
Inference : https://github.com/DivyaShaktii/person_car_detection/tree/main/yolo/results


**About model**  
YOLOv3 (You Only Look Once, Version 3)  a real-time object detection algorithm that identifies specific objects in videos, live feeds, or images. YOLO uses features learned by a deep convolutional neural network to detect an object.

**Primary Analysis**
Had a glance of images and found that images containes lot of challanging scenarios like crowding , occlusion , lighting conditions , different car models , peoples in fancy dresses and lot of variation in bonding box size.



**Assumptions**  
Yolo models are not good at small objects detection, as given classes were car and person so was this model was best choice beacuse of high speed and comperatively good prediction.

**Approach**  
Used pretrained weights and customised model on given dataset by freezing initial layers.

**Training metrices and Performance Validation**
https://github.com/DivyaShaktii/person_car_detection/tree/main/yolo/train_stats

**Conclusion**


**Recommendations**
More robust models like EfficientDet or faster RCNN can work better compromising with speed to get more accuracy in prediction depending on application.


