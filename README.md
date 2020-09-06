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

These tasks are performed without using inbuilt Python libraries. The only libraries used are Numpy & PIL

---
### :city_sunset: Image Rotation

The image is rotated by angles which are multiples of 90 degrees
  
![Original Image](https://user-images.githubusercontent.com/64036185/92142268-32203080-ee31-11ea-9c30-9fa8f51d3b74.png) 

**Output**
|<img width="316" height="598" src="https://user-images.githubusercontent.com/64036185/92317946-b508dd00-f023-11ea-91df-31e1c6f0caeb.png">|<img width="316" height="598" src="https://user-images.githubusercontent.com/64036185/92317968-e08bc780-f023-11ea-9010-8ff23631f475.png">|
|:---:|:---:|
|90 Degrees Clockwise|270 Degrees Clockwise|

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

![Cube](https://user-images.githubusercontent.com/64036185/92311996-1c9a3a80-efda-11ea-933c-aa736515b5af.jpg)

![Dog](https://user-images.githubusercontent.com/64036185/92312000-3045a100-efda-11ea-94e9-35a21ea14d18.png)

**Output**

|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312033-a8ac6200-efda-11ea-86b2-1f3db1b96094.png">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312045-c679c700-efda-11ea-8ac1-ca712ed6ae4a.png">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312054-d98c9700-efda-11ea-8af6-5acf3981e815.png">
|:---:|:---:|:---:|
|Vertical Edge|Horizontal Edge|Sobel|

|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312276-dc888700-efdc-11ea-90e9-2e12632c3c73.png">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312243-874c7580-efdc-11ea-8983-1cc1474e8d2e.png">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312246-9501fb00-efdc-11ea-9c1c-559c9d598ffd.png">
|:---:|:---:|:---:|
|Vertical Edge|Horizontal Edge|Sobel|

|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312347-68021800-efdd-11ea-918f-71c0e638f9c2.jpg">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312364-836d2300-efdd-11ea-87b3-c6b7c0e6470c.jpg">
|:---:|:---:|
|Cube Canny|Dog Canny|


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
