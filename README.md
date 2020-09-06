# SRA Practice Assignment
Here, I have compiled the codes of the SRA tasks I've completed.

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
## :computer: Image Processing Tasks 

These tasks are performed without using inbuilt Python libraries. The only libraries used are Numpy & cv2

---
### :city_sunset: Image Rotation

The image is rotated by angles which are multiples of 90 degrees
  
![Original Image](https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Image%20Rotation/original.png) 

**Output**
90 Degrees Anti-Clockwise
<img width="640" height="640" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Image%20Rotation/90rot.png">

270 Degrees Anti-Clockwise
<img width="640" height="640" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/Image%20Rotation/270rot.png">

### :sunrise: Applying Kernels

The Kernel filters are doing the following tasks:
1. Blurring (Normal Blur, Box Blur & Gaussian Blur)
2. Sharpening the Image

![Original Image](https://user-images.githubusercontent.com/64036185/92143212-8ed01b00-ee32-11ea-8315-c57b111ce552.png)

**Output**
|<img width="300" height="300" src="https://user-images.githubusercontent.com/64036185/92144804-deafe180-ee34-11ea-9ee6-259f5dbe4326.png">|<img width="300" height="300" src="https://user-images.githubusercontent.com/64036185/92144938-14ed6100-ee35-11ea-888f-bb64c2f35fe3.png">|<img width="300" height="300" src="https://user-images.githubusercontent.com/64036185/92143827-6f85bd80-ee33-11ea-831d-e9a08b36d204.png">
|:---:|:---:|:---:|
|Box Filter|Gaussian Filter|Sharpen|

### :city_sunset: Edge Detection

**Original Images**

![Cube](https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/original2.png)

![Dog](https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/original1.png)

**Output**
Vertical Edge
<img src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/ver1.png">
|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/hor1.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor">
|:---:|:---:|
|Horizontal Edge|Sobel|

|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/ver.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/hor.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Edge%20Detect%20Ver%20Hor/h">
|:---:|:---:|:---:|
|Vertical Edge|Horizontal Edge|Sobel|

|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/canny_edges1.png">|<img width="208" height="203" src="https://github.com/purvankbhiwgade/SRA-tasks/blob/master/edgeDetect/Canny%20Edge/canny_edges2.png">
|:---:|:---:|
|Canny Edge Cube|Canny Edge Dog|


## Future Work
* See [todo.md](https://todo.md) for seeing developments of this project
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
