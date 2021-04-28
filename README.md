# Capstone_Object_detection

## To use this Repo, please run the files in the following order:

    1. YOLOv4_Training_code.ipynb
      This notebook is used to train dataset to obtain model weight.
      
    2. generate_train.py
      This python script is used to generate the train.txt file which includes image data paths. The training model would find relative image by these paths.
    
    3.obj.data
      This file includes contents like class number, train.txt file address path, obj.names file address path and trained weight preservation path.

    4.obj.names
      This file includes different object names.
     
    5.yolov4-obj.cfg
      This file includes all kinds of training model parameters and these parameters' values.
    
    6.yolov4_object_detection_webcam_images.ipynb
      This notebook is used to do YOLOv4 object detection on local webcam by using trained weight.


Note: To run GitHub project, you may need to download several files in https://drive.google.com/drive/folders/1i4j39fyD5GPjxqU-fFCVULl1qNbcuFdw. I strongly recommend you to visit my guideline website and follow the guideline to do object detection step by step.

The guideline website link: https://qianyisun.github.io/Yolov4_guideline.GitHub.io/

![Image](image/website_outlook.png)
    
    
