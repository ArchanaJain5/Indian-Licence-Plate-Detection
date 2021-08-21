# Indian-Licence-Plate-Detection

The objective of the project is to create a system that detects and recognizes Indian number plate of cars using YOLO for number plate detection, image processing techniques for segmentation and CNN for recognition of plate.  
<br>
The proposed system is to detect Indian car license plates and recognize them.
The system is divided into two parts. 
1. License plate Detection
2. License plate Recognition

The dataset can be downloaded from https://www.kaggle.com/a16bce1290/indian-car-dataset

Execution Steps <br>
For using YOLO algorithm YOLOv3 was used. 
darknet-yolov3.cfg and lapi.weights needs to be downloaded to execute YOLO algorithm which would detect the licence plate.
<br>
character_recognition.h5 is the model trained to recognize the plates
<br>
execute final.ipynb 
