# SRA Practice Assignment
Here, I have compiled the codes for the SRA tasks I've completed.

## Table of Contents

* [About the Project](#about-the-project)
  * [Tech Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Results and Demo](#results-and-demo)
* [Future Work](#future-work)
* [Contributors](#contributors)
* [Acknowledgements and Resources](#acknowledgements-and-resources)

## About The Project
This projects has all the implementation of basic computer vision processes without using any defined function.

### Tech Stack
* [Python](https://python.org/)
* [PIL](https://google.com/)
* [Google colab](https://colab.research.google.com/)
* [GitHub](https://github.com/)

### File Structure
    .
    ├── Image Rotation         
    │   ├── 90rot.png
    │   ├── 180rot.png
    │   ├── 270rot.png
    │   ├── original.png
    │   └── imRotation.ipynb
    ├── kernels.ipynb                    
    │   ├── report.pdf          
    │   └── results             
    ├── edgeDetect                    
    │   ├── Canny Edge 
    │   │    ├── result
    │   │    └── canny_edge.ipynb
    │   ├── Edge Detect Ver Hor  
    │   │    ├── result
    │   │    └── edge_detection_ver_hori.ipynb
    │   └── Edge Detection  
    │        ├── result
    │        └── edge_detection.ipynb
    └── README.md 
    
    
## Getting Started

## Installation

1. Clone the repo
```sh
git clone https://github.com/purvankbhiwgade/SRA-tasks.git
```
2. Upload the files to your google drive

3. Open your google drive and navigate to that folder

4. Right Click on the .ipynb file and Open with Google Colaboratory.

## Results
## Image Processing Tasks 

These tasks are performed without using inbuilt Python libraries. The only libraries used are Numpy & cv2

---
### Image Rotation

The image is rotated by angles which are multiples of 90 degrees
  
![Original Image](https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Image%20Rotation/original.png) 

**Output**
90 Degrees Anti-Clockwise
<img width="640" height="640" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Image%20Rotation/90rot.png">

270 Degrees Anti-Clockwise
<img width="640" height="640" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Image%20Rotation/270rot.png">

### Applying Kernels

The Kernel filters are doing the following tasks:
1. Blurring (Normal Blur, Box Blur & Gaussian Blur)
2. Sharpening the Image

![Original Image](https://user-images.githubusercontent.com/64036185/92143212-8ed01b00-ee32-11ea-8315-c57b111ce552.png)

**Output**
|<img width="300" height="300" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Kernels/Box%20Filter.png">|<img width="300" height="300" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Kernels/Gaussian.png">|<img width="300" height="300" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Kernels/Sharpen.png">
|:---:|:---:|:---:|
|Box Filter|Gaussian Filter|Sharpen|

### :city_sunset: Edge Detection

**Original Images**

![Cube](https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/original2.png)

![Dog](https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/original1.png)

**Output**

|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/ver1.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/hor1.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detection/original2_edge.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/canny_edges2.png">
|:---:|:---:|:---:|:---:|
|Vertical Edge|Horizontal Edge|Sobel|Canny Edge Dog|

|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/ver.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/hor.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detection/original_edge.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/canny_edges1.png">
|:---:|:---:|:---:|:---:|
|Vertical Edge|Horizontal Edge|Sobel|Canny Edge Cube|

### : Morphology

|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Morphology/morphological.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Morphology/dilation.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Morphology/erroded.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Morphology/dilated_edge.png">
|:---:|:---:|:---:|:---:|
|Morphology|Dilation|Eroded|Dilated Edge|


## Future Work
- [x] Image Rotation
- [x] Applying Kernel
- [x] Edge Detection
- [ ] Morphological Transformation
- [ ] Masking
- [ ] ROI

## Contributors
* [Purvank Bhiwgade](https://github.com/purvankbhiwgade/)

## Acknowledgements and Resources
* [SRA VJTI](http://sra.vjti.info/) Eklavya 2020
