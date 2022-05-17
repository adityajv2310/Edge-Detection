# Edge-Detection
## Aim:
To perform edge detection using Sobel, Laplacian, and Canny edge detectors.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
Import the necessary modules.

### Step2:
For performing edge detection on a image.
* Sobel
```python
sobelx=cv2.Sobel(img,cv2.CV_64F,1,0,5)
sobely=cv2.Sobel(img,cv2.CV_64F,0,1,5)
sobelxy=cv2.Sobel(img,cv2.CV_64F,1,1,5)
```
* Laplacian
```python
Laplacian=cv2.Laplacian(img,cv2.CV_64F)
```
* Canny
```python
canny=cv2.Canny(img,120,150)
```

### Step3:
Display all the images with their respective edge detected images.

 
## Program:

``` Python
# Import the packages


# Load the image, Convert to grayscale and remove noise



# SOBEL EDGE DETECTOR



# LAPLACIAN EDGE DETECTOR



# CANNY EDGE DETECTOR




```
## Output:
### SOBEL EDGE DETECTOR
<br>
<br>
<br>
<br>
<br>
<br>


### LAPLACIAN EDGE DETECTOR
<br>
<br>
<br>
<br>
<br>
<br>


### CANNY EDGE DETECTOR
<br>
<br>
<br>
<br>
<br>
<br>

## Result:
Thus the edges are detected using Sobel, Laplacian, and Canny edge detectors.
