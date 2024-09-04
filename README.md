# Vehicle-Number-Plate-Detection

Vehicle Number Plate Detection is identifying the part of the car that is predicted to be the number plate. Recognition is identifying the values that make up the license plate. 
Vehicle Number Plate Detection is the technology that uses computer vision to detect and recognize a license plate from an input image of a car.

This technology applies in many areas. On roads, it is used to identify the cars that are breaking the traffic rules. In security, it is used to capture the license plates of the vehicles getting into and out of certain premises. In parking lots, it is used to capture the license plates of the cars being parked. The list of its applications goes on and on.

## Introduction 
Python gives us the ability to create our license plate detection and recognition program. We achieve this by using three of its libraries; pytesseract, imutils, and OpenCv.

In this tutorial, we are going to learn the processes software passes to detect and recognize a number plate, how to use the three libraries we did mention above to create our program, and finally how to create a program that is capable of detecting and recognizing a license plate. We will use the pycharm community edition as our IDE since it is freely available on the internet. A person using Windows or Linux can follow through.

## Table of contents
* Prerequisites
* Processes a software undergoes to detect and recognize a license plate
* Creating a license plate detection and recognition program
* Results
* Conclusion
  
## Prerequisites
To follow through this tutorial, the reader needs to:

* Be familiar with the python programming language
* Have pycharm installed on their computer. You can download pycharm community edition [here](https://www.jetbrains.com/pycharm/download/?section=windows).
  
## Processes a software undergoes to detect and recognize a license plate 
For software to detect and recognize a license plate, it undergoes three major processes.

* **Taking an image of a car as input** - The program takes in the input of the car in which the license plate is to be detected.
* **Processing the input** - The image taken as the input undergoes processing to detect the part of the car that is the license plate.
* **Recognizing the number plate** - The values of the detected license plate are extracted from the number plate image.

## Creating a license plate detection and recognition program 

1. First things first, let's prepare our workspace. Open pycharm and click on create a new project.
2. We now need to install the python libraries we will need to create our program. To achieve this, open the terminal and type the following command then hit enter:
  ```
  pip install opencv-contrib-python
  ```
  Wait for a few seconds till it is installed successfully. We also refer to this library as      cv2. We will use it to preprocess our image and also display the images that have undergone     processing.
4. To installimutilsuse the following command:
  ```
  pip install imutils
  ```
   We will need this library to resize our images.
5. To install pytesseract use the following command:
  ```
  pip install pytesseract
  ```
   We will need this library to extract the license plate text from the detected license plate.
6. We now need one more thing which is the tesseract. This is software that pytesseract will use to recognize characters from an image.
Installing tesseract 

Download tesseract from [here](https://github.com/UB-Mannheim/tesseract/wiki) and install it.

7. Now ready to run.

## Result
When the program has run successfully, its output is as follows:

**Input image:**

![Inputimage](https://github.com/ChethanS24/Vehicle-Number-Plate-Detection/blob/main/Screenshots/s1.jpg)

**Output:**

![output1](https://github.com/ChethanS24/Vehicle-Number-Plate-Detection/blob/main/Screenshots/s2.png)

**IMAGE OF VEHICLE WITH DETECTED NUMBER PLATE:**

![output2](https://github.com/ChethanS24/Vehicle-Number-Plate-Detection/blob/main/Screenshots/s3.png)

**CROPPED NUMBER PLATE:**

![output3](https://github.com/ChethanS24/Vehicle-Number-Plate-Detection/blob/main/Screenshots/s4.png)

**STORED DATA:**

![output4](https://github.com/ChethanS24/Vehicle-Number-Plate-Detection/blob/main/Screenshots/s5.png)

## Conclusion

You now have all the skills required to create a program that detects and recognizes license plates. Capture more images of vehicles and input them into the program then sit back and watch as the program does its magic.
