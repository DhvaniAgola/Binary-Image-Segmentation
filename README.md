# Binary-Image-Segmentation
Classifying pixels of an image in two categories using Min-Cut algorithm.

Programming Language : C++

Library used : OpenCV

## Project Description

This project is aimed to differentiate tow categories (foreground and background) of the image. After identifying both the are the resultant image will be colored by white in foreground and black in backgroud. The output image will be black and white image and will have the same size as input image.

In this project the identification of foreground and background is based on the configuration file in which its given the pixels of foreground and background.

### Config file contains the pixels of format:

first line : number of pixels(N)

next N lines : <X-coordinate> <Y-coordinate> <category-bit>

Category-bit : 1 for foreground, 0 for background

**NOTE :** 
Sample input file and config file is given in the 'code/assets/'

Detailed description is attached to the repository.

## Compile and Run the project
**There are 3 arguments**
1. Input image
2. Config file that provides the initial sets of foreground and backgound points.
3. Output image

```
g++ -o main main.cpp

./main <input_file> <config_file> <output_file>
```
