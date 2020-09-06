## Image Processing Task

The following operations have been performed mainly using only Numpy and Pillow library is used just to load and save image.

### 1. Image Rotation

The image can be rotated by any angle bound or inbound.
|<img width="640" height="450" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Rotation/image.png">| 
|:---:|
|Input Image|

**Output**
|<img width="600" height="322" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Rotation/rotated_nobound.png">|<img width="640" height="450" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Rotation/rotated.png">|
|:---:|:---:|
|No Bound|Bound|

### 2. Applying Kernels

Applying 5X5 filters to do the following task
1. Blurring 
2. Sharpening

|<img width="446" height="447" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Blurring/blur.jpeg">|
|:---:|
|Input Image|

**Output**
|<img width="640" height="450" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Blurring/box_blur.png">|<img width="640" height="450" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Blurring/gaussian_blur.png">|<img width="640" height="450" src="https://github.com/MannDoshi/Image-Processing/blob/master/Image-Sharpening/sharpened_image.png">|
|:---:|:---:|:---:|
|Box Filter|Gaussian Filter|Sharpen|

### 3. Edge Detection
Applying Edge Detection in following sequence 
1. Vertical edge detection
2. Horizontal edge detection
3. Sobel edge detection (right, left, top, bottom)
4. Canny edge detection  

|<img width="602" height="452" src="https://github.com/MannDoshi/Image-Processing/blob/master/Edge-Detection/edge-detection.png">|
|:---:|
|Input Image|

**Output**
|<img width="602" height="452" src="https://github.com/MannDoshi/Image-Processing/blob/master/Edge-Detection/vertical-edge-output.png">|<img width="602" height="452" src="https://github.com/MannDoshi/Image-Processing/blob/master/Edge-Detection/horizontal-edge-output.png">|
|:---:|:---:|
|Vertical Edge Detection|Horizontal Edge Detection|
|<img width="602" height="452" src="https://github.com/MannDoshi/Image-Processing/blob/master/Edge-Detection/sobel-edge-output.png">|<img width="602" height="452" src="https://github.com/MannDoshi/Image-Processing/blob/master/Edge-Detection/canny_output.png">|
|Sobel Edge Detection|Canny Edge Detection|

### 4. Morphological Transformation
Applying dilation and erosion transformation to the image

**Output**
|<img width="112" height="150" src="https://github.com/MannDoshi/Image-Processing/blob/master/Morphological-Transformations/morphological.png">|<img width="112" height="150" src="https://github.com/MannDoshi/Image-Processing/blob/master/Morphological-Transformations/dilation_output.png">|<img width="112" height="150" src="https://github.com/MannDoshi/Image-Processing/blob/master/Morphological-Transformations/erosion_output.png">|<img width="112" height="150" src="https://github.com/MannDoshi/Image-Processing/blob/master/Morphological-Transformations/sobel-edge-output.png">|
|:---:|:---:|:---:|:---:|
|Input-Image|Dilation|Erosion|Edge-Detection|


