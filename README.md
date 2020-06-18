# Real-Time Grab Detection in Videos


This project proposes to implement an object detection network using deep learning techniques to predict in real-time if an RGB video contains a hand grasping an object.

Presentation Video: https://www.youtube.com/watch?v=y7nI9wQG0e8

Grab detection is the detection of hands grasping objects

![Imgur](https://i.imgur.com/r7Ke0FO.png)


This is a fork of the implementation of AlexeyAB's implementation of YoloV4 on darknet. 
linked here: https://github.com/AlexeyAB/darknet

## How to use:

First install the required dependencies as described in the YOLOv4 github: https://github.com/AlexeyAB/darknet#requirements

Alternatively Augmented startups provides a great 2-part step-by-step guide for Windows on Youtube: 
https://www.youtube.com/watch?v=5pYh1rFnNZs

https://www.youtube.com/watch?v=sUxAVpzZ8hU
In this video clone this github instead of the YOLO4 github

### Download the required trained weights:
https://drive.google.com/file/d/1B9WDT8EKs0NLcTynmniGzeyvvGuh_Fcc/view?usp=sharing

### Put the weights in the folder
~/darknet/build/darknet/x64/backup 

### To use on videos go to the directory: 
~/darknet/build/darknet/x64

### then run on the command line: 
darknet.exe detector demo data/obj.data yolo-obj.cfg backup/yolo-obj_best.weights filename_of_your_video


# Our Grab Dataset:
A human grasping dataset taken from different angles.

 ![Imgur](https://i.imgur.com/LqGTzbb.png)


https://drive.google.com/file/d/1xeTGrnWud8X1A9PuonK_mwIHl6UsHeUr/view?usp=sharing






### DEMO VIDEOS


## Results on a video from the Grab Dataset Evaluation Set
https://drive.google.com/open?id=1Hs_dKiOXMXJupfJTYxankmKEhLa_U2Q0



## Results on a video from the UTGrasp Dataset 
https://drive.google.com/open?id=1L9LAARDvmwcIoDtLduz9YnWYOrOeSDeK


## Experimental Results:
Average Precision results at IoU of 0.5 


 ![Imgur](https://i.imgur.com/tDVXYCB.png)
 
 
Average FPS on Videos

![Imgur](https://i.imgur.com/aD0wbOa.png)

Comparison with other Object Detection Architectures in the task of Grab detection:

![Imgur](https://i.imgur.com/t1CBfsG.png)









 


