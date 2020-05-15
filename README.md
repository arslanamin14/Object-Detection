# Object-Detection
Object detection is a technique of computer vision and image processing that deals with detecting instances of semantic objects of a certain class such as humans, buildings and cars in digital images and videos.

# Folders
├── _Architechtures_       
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Network Diagrams   
├── _Notebooks_     
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Colab Notebooks of models       
├── _Trained Model Weights_     
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the pre-trained model weights
├── _Results_                   
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the results of models  
├── _Test_                      
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Colab Notebooks for testing the models by using pretrained weight  
├── _Train_                     
│ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└──It contains the Colab Notebooks for training the models  


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
   # Training
| Model | Loss | Accuracy | F1 Score | Dice Score |
| ----- | ---- | ---- | ---- | ---- |
| UNET | 0.0869 | 0.9633 | 0.9328 | 0.9848 
| SEGNET | 0.2399 | 0.8965 | 0.8085 | 0.9572 
| DeepLabV3Plus | 0.0455 | 0.9806 | 0.9645 | 0.9919
  # Validation
| Model | Loss | Accuracy | F1 Score | Dice Score |
| ----- | ---- | ---- | ---- | ---- |
| UNET | 0.1100 | 0.9555 | 0.9216 | 0.9809 
| SEGNET | 0.2431 | 0.8946 | 0.8090 | 0.9560 
| DeepLabV3Plus | 0.1035 | 0.9635 | 0.9347 | 0.9847

 # Testing 
| Model | Loss | Accuracy | F1 Score | Dice Score |
| ----- | ---- | ---- | ---- | ---- |
| UNET | 0.2981 | 0.9054 | 0.7715 | 0.9587 
| SEGNET | 0.2250 | 0.9028 | 0.9581 | 0.7663 
| DeepLabV3Plus | 0.2250 | 0.9028 | 0.9581 | 0.7663

# Qualitative Results
Some predicted results are shown below.
# 1.UNET
### Graphs

Accuracy             |  Loss
:-------------------------:|:-------------------------:
![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/UNET/Graph%20between%20Training%20and%20Validation%20Accuracy.PNG)  |  ![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/UNET/Graph%20between%20Training%20and%20Validation%20Loss.PNG)
F1 Score             |  Dice Coefficient
![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/UNET/Graph%20between%20Training%20and%20Validation%20F1%20Score.PNG)  |  ![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/UNET/Graph%20between%20Training%20and%20Validation%20Dice.PNG)
### Result
![test1](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/UNET/Testing%20Image%20With%20Ground%20Truth%20and%20Predicted.PNG)
# 2.SEGNET
### Graphs

Accuracy             |  Loss
:-------------------------:|:-------------------------:
![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/SEGNET/Graph%20between%20Training%20and%20Validation%20Accuracy.PNG)  |  ![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/SEGNET/Graph%20between%20Training%20and%20Validation%20Loss.PNG)
F1 Score             |  Dice Coefficient
![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/SEGNET/Graph%20between%20Training%20and%20Validation%20F1%20Score.PNG)  |  ![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/SEGNET/Graph%20between%20Training%20and%20Validation%20Dice.PNG)
### Result
![test2](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/SEGNET/Testing%20Image%20With%20Ground%20Truth%20and%20Predicted.PNG)
# 3.Deep Lab V3 Plus
### Graphs
### Learning Curves
Accuracy             |  Loss
:-------------------------:|:-------------------------:
![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/DeepLabV3plus/Graph%20between%20Training%20and%20Validation%20Accuracy.PNG)  |  ![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/DeepLabV3plus/Graph%20between%20Training%20and%20Validation%20Loss.PNG)
F1 Score             |  Dice Coefficient
![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/DeepLabV3plus/Graph%20between%20Training%20and%20Validation%20F1%20Score.PNG)  |  ![](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/DeepLabV3plus/Graph%20between%20Training%20and%20Validation%20Dice.PNG)
### Result
![test3](https://github.com/arslanamin14/Image-Segmentation/blob/master/Results/DeepLabV3plus/Testing%20Image%20With%20Ground%20Truth%20and%20Predicted.PNG)
