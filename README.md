# Exploring Egocentric Vision through OST-HMD

This project involves exploring the various factors which affects egocentric vision and inventing ways in order to improve it. 
For the purposes of the project, I used Magic Leap One (MLO) as a platform for Optical See-Through Head Mounted Display.
The idea for the application, which was developed on MLO in order to simulate the experience of egocentric vision, came from the Seek app for mobile platform, which essentially identifies 
plants and animals upto their species classification based on the distance between the user and the object of interest, viewing angle, etc.
Therefore, I developed a similar application for MLO using YOLO v3-tiny object detection model and iNat dataset in order to see the differences in 
performance of mobile phone and a head mounted display and how it can be improved. The implementation of the application was done using
Unity game engine, which supports development for MLO. The primary languages used for development were C# for Unity game engine and Python for YOLO v3-tiny object detection model.

## Getting Started

In order to inititate this application on your MLO, you need to -

* Install Unity game engine (and get familiar with it if you are not)
* Follow the procedure given on MLO website in order to set up the development environmnet for MLO on Unity.
* Clone the project 
* Get the OpenCVForUnity asset from asset store
* Build the project and enjoy!

### Prerequisites

For the application to work, you need the following:

* Magic Leap One device
* Unity game engine
* OpenCVForUnity asset from Unity asset store (since these example were very useful in understanding the development process on Unity using OpenCV)

## Built With

* [Unity](https://unity.com/) - The game engine used (Unity version 2019.1.6f1 was used)
* [OpenCVForUnity](https://assetstore.unity.com/packages/tools/integration/opencv-for-unity-21088) - The asset used to understand the code
* [MagicLeapWithOpenCVForUnity](https://unitylist.com/p/jqz/Magic-Leap-With-Open-CV-For-Unity-Example) - The main asset whose OpenCVImageCaptureExample and DnnMLCameraPreviewExample scenes were used

## Demos
![alt text](https://raw.githubusercontent.com/username/projectname/branch/path/to/img.png)

## Authors

* **Pranjal Mittal** - [magic_leap_yolo](https://github.com/PranjalMittal0409/magic_leap_yolo/)

## Acknowledgments

* Harald Haraldsson, Cornell Tech
* Prof. Serge Belongie, Cornell Tech
* Masters and Phd students at Cornell Tech whose inputs were very valuable for my project
* Magic Leap Engineers for their crucial guidance during the development process

