# FT_Image_Mixer-Task

## Overview
This is a desktop application developed in Python using PyQt5 that allows users to manipulate and mix components of up to four images. The application provides various features such as converting colored images to grayscale, resizing images to a uniform size, displaying specific components of an image (Magnitude, Phase, Real Part, Imaginary Part), and more.

## Features
- **Converting to Grayscale**
  - Convert colored images to grayscale immediately.

- **Uniform Resizing**
  - Resize all loaded images to a uniform size for consistency.
    
- **Component Display**
  - Display and visualize specific components of an image, including Magnitude, Phase, Real Part, and Imaginary Part.
    
- **Mixing Components (Mood 1)**
  - Mix any of the four components with another image's components at a chosen ratio. Users can control the percentage contribution of each image's component.

- **Region Mixing (Mood 2)**
  -  Mix a region from a component of one image with other images. Regions can be either inner or outer, corresponding to high frequencies.

- **Multithreading**
  - The application is designed to execute two processes synchronously, improving performance and responsiveness.
  
- **Logging Results**
  - All results, including processed images and user interactions, are logged into a results.log file for future reference and analysis.

- **Brightness and Contrast Modification**
  - Easily modify the brightness and contrast of an image by clicking on the image and dragging the mouse in the vertical or horizontal direction.



## Demo

https://github.com/salsabilmostafa/FT_Image_Mixer-Task/assets/115428975/8b9a2a0f-31dc-4009-b86a-ccbadea2a728


## Usage
1. Clone the repository.
    ```bash
    git clone https://github.com/salsabilmostafa/FT_Image_Mixer-Task.git
    ```
2. Run the application.
    ```bash
    python Image_Mixer.py
    ```
3. Explore the features and functionalities provided by the FT_Image_Mixer.

## Dependencies
Ensure you have the following dependencies installed before running the application:
- Python 3.7 or above
- PyQt5.QtCore: Core functionality for the PyQt5 framework.
- cv2: OpenCV library for image processing.
- numpy: Fundamental package for scientific computing with Python.
- partial from Functools 

## Contributions
Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.
