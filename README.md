# SRA - Image Processing Tasks
## Tables of Contents
  * [About](#about)
  * [Task 1](#task-1-image-rotation)
  * [Task 2](#task-2)
  * [Task 3](#task-3) 
  * [Task 4](#task-4)
  * [Task 5](#task-5) 
  * [Task 6](#task-6) 
   
## About
All the tasks are performed using libraries such as Numpy and Pillow, without using other inbuilt functions from libraries like Open-CV.        

## Task 1- Image Rotation :

Rotating the given image by various angles without the use of inbuilt rotate functions of numpy, PIL or OpenCV. 

### Rotation Matrix:
![Rotation Matrix](https://legacy.voteview.com/images/homework_1_1_18_2011.jpg)
Original image                     |  Result After Rotation(90 degrees)
:-------------------------:|:-------------------------:
<img width="640" height="450" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/Image%20Rotation/rotate.png">|<img width="640" height="450" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/Image%20Rotation/rotated.png">
## Task 2 - Applying Kernels :

### Blurring And Sharpening An Image
Blurring the image with 5x5 kernels. Box-Blur and Gaussian Blur Kernels are used.   

 Original image  | Gaussian Blur | Average Blur | Sharpen Image  
:-----:|:-----:|:-----:|:-----:
<img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/kernel/kernel.png">|<img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/kernel/gauss%20blur.png">|<img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/kernel/average%20blur.png">|<img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/kernel/sharpen.png">
## Task 3 - Edge Detection :
Edge Detection done using 3x3 kernels.
 Original Image  | Vertical Edge Detection  | Horizontal Edge Detection
:-----:|:-----:|:-----:
<img width="340" height="340" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/edge%20detection/cube_edge_detection.png">|<img width="340" height="340" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/edge%20detection/vertical-edge.png">|<img width="340" height="340" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/edge%20detection/horizontal-edge.png">
  **Sobel Edge Detection**  | **Canny Edge Detection**
<img width="340" height="340" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/edge%20detection/sobel.png">|<img width="340" height="340" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/edge%20detection/canny.png">


## Task 4 - Morphology :
### Erosion and Dilation 
 Original Image  | Erosion  | Dilation  
 :-----:|:-----:|:-----:|
 <img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/morphological_transformation/Morphological_Transformation.png">|<img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/morphological_transformation/Erosion.png">|<img width="240" height="300" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/morphological_transformation/Dilation.png">
 
 ## Task 5 - Masking :
Input Image                     |  Blue Ball Detection
:-------------------------:|:-------------------------:
<img width="640" height="450" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/masking/masking.png">|<img width="640" height="450" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/masking/masked.jpeg">

 ## Task 6 - ROI
### Region of Interest extraction
Input Image                     |  Output Image
:-------------------------:|:-------------------------:
<img width="640" height="450" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/ROI/ROI.png">|<img width="640" height="450" src="https://github.com/SaminaAttari786/sra-task_Image_Processing/blob/main/sra-tasks_Image_Processing/ROI/ROI-result.png">
