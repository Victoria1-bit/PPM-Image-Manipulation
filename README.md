# PPM Image Manipulation Project

This project is a C++ application that loads and manipulates images in the **PPM (Portable Pixmap)** format.  
The program uses **SFML** to display the image and provides several image processing features through a simple GUI.

## Features

The application allows the user to:

- Load and display a PPM image
- Save the modified image
- Apply colour filters:
  - Red filter
  - Green filter
  - Blue filter
- Convert the image to **Greyscale**
- **Flip the image horizontally**
- **Flip the image vertically**
- Advanced features:
  - Rotate image 90 degrees
  - Mirror image
  - Sepia filter

## How it Works

The image is stored as a **vector of RGB structs**, where each struct represents one pixel:
