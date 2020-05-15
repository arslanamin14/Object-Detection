# Object-Detection
Object detection is a technique of computer vision and image processing that deals with detecting instances of semantic objects of a certain class such as humans, buildings and cars in digital images and videos.

# Folders
├── _Architechtures_       
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Network Diagrams   
├── _Notebooks_     
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Colab Notebooks of models        
├── _Results_                   
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the results of models  
├── _Train_                     
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Colab Notebooks for training the models    
├── _Test_                      
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Colab Notebooks for testing the models by using pretrained weight  
├── _Trained Model Weights_     
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the pre-trained model weights 



# Dataset
The dataset used for Object detection is Satellite Imagery Multi-vehicles Dataset (SIMD). It comprises 5,000 images of resolution 1024
x 768 and collectively contains 45,303 objects in 15 different classes of vehicles including cars,trucks, buses, long vehicles, various types of aircrafts and boats. The source images are taken from public satellite imagery available in Google Earth and contain images of multiple locations from seven countries.

# Requirements
Keras 2.x  
Python 3.x  
Tensorflow 1.x


# Models
The following three models have been trained.  
# 1.RetinaNet
![RetinaNet](https://github.com/arslanamin14/Object-Detection/blob/master/Architectures/retinanet.png)
# 2.YOLOV3
![YoloV3](https://github.com/arslanamin14/Object-Detection/blob/master/Architectures/yolo.png)
# 3.Faster RCNN
![Faster RCNN](https://github.com/arslanamin14/Object-Detection/blob/master/Architectures/faster%20rcnn.png)
# Quantitative Results
The results are shown below

# RetinaNet-Resnet50
3678 instances of class car with average precision: 0.7160  
446 instances of class truck with average precision: 0.2215  
874 instances of class van with average precision: 0.2513  
222 instances of class longvehicle with average precision: 0.1196  
366 instances of class bus with average precision: 0.1649  
161 instances of class airliner with average precision: 0.6309  
25 instances of class propeller with average precision: 0.0780  
49 instances of class trainer with average precision: 0.0998  
103 instances of class chartered with average precision: 0.2433  
8 instances of class fighter with average precision: 0.0104  
85 instances of class other with average precision: 0.0039  
83 instances of class stairtruck with average precision: 0.0007  
55 instances of class pushback with average precision: 0.0000  
9 instances of class helicopter with average precision: 0.0181  
1820 instances of class boat with average precision: 0.6426  
Inference time for 747 images: 0.3017  
mAP using the weighted average of precisions among classes: 0.5439  
mAP: 0.2134  

# RetinaNet-Vgg16
3678 instances of class car with average precision: 0.8276  
446 instances of class truck with average precision: 0.3610  
874 instances of class van with average precision: 0.5500  
222 instances of class longvehicle with average precision: 0.2334  
366 instances of class bus with average precision: 0.5706  
161 instances of class airliner with average precision: 0.6081  
25 instances of class propeller with average precision: 0.0326  
49 instances of class trainer with average precision: 0.5270  
103 instances of class chartered with average precision: 0.3725  
8 instances of class fighter with average precision: 0.0044  
85 instances of class other with average precision: 0.0102  
83 instances of class stairtruck with average precision: 0.0593  
55 instances of class pushback with average precision: 0.0116  
9 instances of class helicopter with average precision: 0.0244  
1820 instances of class boat with average precision: 0.9044  
Inference time for 747 images: 0.1090  
mAP using the weighted average of precisions among classes: 0.7217  
mAP: 0.3398  
# YoloV3
airliner: 0.9376  
boat: 0.8672  
bus: 0.6284  
car: 0.8032    
chartered: 0.8815  
fighter: 1.0000  
helicopter: 0.7987  
longvehicle: 0.5687  
other: 0.0220  
propeller: 0.8011  
pushbacktruck: 0.0998  
stairtruck: 0.2107  
trainer: 0.9319  
truck: 0.5036  
van: 0.6275  
mAP: 0.6455  
# FasterRCNN
car AP: 0.3939031293374823  
boat AP: 0.33702536967079494  
bus AP: 0.31243369607873334  
van AP: 0.4702393149732447  
fighter AP: 0.2920869443431776  
stairtruck AP: 0.4486486486486487  
airliner AP: 0.5491043265902382  
chartered AP: 0.5673478860149023  
longvehicle AP: 0.21648951480923828  
trainer AP: 0.19529633757176953  
truck AP: 0.29913125730246914  
helicopter AP: 0.06922111159399295  
other AP: 0.8333333333333334  
propeller AP: 0.22938127845808728  
pushback AP: 1.0  
mAP = 0.4142428099150742  
mean average precision is 0.424  
# Qualitative Results
Some predicted results are shown below.
# RetinaNet-Resnet50
![RetinaNet-Resnet50](https://github.com/arslanamin14/Object-Detection/blob/master/Results/RetinaNet-Resnet50/Predicted%201.PNG)
# 1.RetinaNet-Vgg16
![RetinaNet-Vgg16](https://github.com/arslanamin14/Object-Detection/blob/master/Results/RetinaNet-Vgg16/Predicted%20%201.PNG)  
# 2.YOLOV3
![YoloV3](https://github.com/arslanamin14/Object-Detection/blob/master/Results/YoloV3/0011%20(1).jpg)
![YoloV31](https://github.com/arslanamin14/Object-Detection/blob/master/Results/YoloV3/0035%20(1)%20(2).jpg)
# 3.Faster RCNN
![Faster RCNN](https://github.com/arslanamin14/Object-Detection/blob/master/Results/FasterRCNN/Predicted%201.PNG)
![Faster RCNN 2](https://github.com/arslanamin14/Object-Detection/blob/master/Results/FasterRCNN/Predicted%202.PNG)
![Faster RCNN 3](https://github.com/arslanamin14/Object-Detection/blob/master/Results/FasterRCNN/Predicted%203.PNG)
![Faster RCNN 4](https://github.com/arslanamin14/Object-Detection/blob/master/Results/FasterRCNN/Predicted%204.PNG)

