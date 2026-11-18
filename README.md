# Edge-Linking-using-Hough-Transformm
## NAME : SHRAVANI M
## REG NO : 212224230263
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image

<img width="596" height="442" alt="image" src="https://github.com/user-attachments/assets/10af4074-646b-4813-85fe-b273a8139a28" />

<img width="646" height="437" alt="image" src="https://github.com/user-attachments/assets/32555585-32b4-4678-9290-3f5cd70b8553" />


### Canny Edge detector output

<img width="710" height="437" alt="image" src="https://github.com/user-attachments/assets/17e7806d-b6fd-4c93-b091-e5d33e097c63" />


### Display the result of Hough transform

<img width="682" height="446" alt="image" src="https://github.com/user-attachments/assets/6c883873-5d26-4fff-8cb2-f73c13f24ada" />


## Result

Thus, the lane detection pipeline is successfully implemented by completing the missing code sections. The system detects and highlights lane lines effectively.



