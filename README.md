# gender-recognition-hikey970

Gender Recognition on Hikey 970
===============================
This application detects a face using Haarcascade in OpenCV, then recognizes a gender from the face detected using Tensorflow and plays a song according to the gender of the person.

Hardware required:
------------------

  * Hikey 970
  * USB Sound Adapter
  * Speaker 
  * USB Video Camera

Pre-requisites for Hikey970:
----------------------------
This project has these software pre-requisites to run on Hikey970

  * tensorflow
  * python3
  * python3-pip
  * OpenCV on python3
  
Except for OpenCV on python3 all the other pre-requisites can be installed by running these commands.Tensorflow is already installed in Hikey970 with pre-built Tensorflow.

```
$ sudo apt-get update
$ sudo apt install python3-dev python3-pip
```

Steps for the Gender Recognition Demo:
---------------------------------------
To run Run a demo of this project please follow these steps.
We assume that you have already installed the pre-requisites before following these steps

Step 1 : Cloning the Project
----------------------------
on Hikey970 run command to clone this project
```
$ git clone https://github.com/shunyaos/gender-recognition-hikey970.git
```
Step 2: Starting the Demo on Hikey970
-------------------------------------
Run the Demo program
```
$ python3 webcam_cv3.py haarcascade_frontalface_default.xml
```
When you run the code, the application detects a face and recognizes the gender of the person using that face.Once, the gender is recognized it plays "Who let the dogs" out for a man and "beautiful" for a girl(just an ongoing gag). 

