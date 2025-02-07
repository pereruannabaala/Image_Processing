# OpenCV Image Processing with Python

## Overview
This project provides an introduction to basic image processing using OpenCV and Python. It covers topics such as reading and displaying images, working with grayscale and color images, manipulating color channels, converting between color spaces, and saving processed images.

## Prerequisites
To run the code successfully, ensure you have the following installed:
- Python 3.x
- OpenCV (cv2)
- NumPy (numpy)
- Matplotlib (matplotlib

## Features
1 **Download and Extract Assets**
- The script downloads image assets required for processing and extracts them for use.

2 **Displaying Images**
- Uses OpenCV (cv2.imread) to read images.
- Displays images using both IPython.display.Image and matplotlib.pyplot.imshow.
  
3 **Working with Grayscale Images**
- Reads grayscale images.
- Prints image data as 2D NumPy arrays.
- Displays images with a grayscale colormap.

4 **Working with Color Images**

- Reads and displays color images.
- Demonstrates the difference between BGR (OpenCV default) and RGB (Matplotlib expected format).
- Corrects color display by reversing color channels.

5 **Splitting and Merging Color Channels**

- Splits an image into its Blue, Green, and Red channels.
- Displays each color channel separately.
- Merges channels back into a complete image.

6 **Converting Between Color Spaces**

- Converts images from BGR to RGB for proper visualization.
- Converts images to HSV color space.
- Displays Hue, Saturation, and Value (HSV) components separately.

7 **Modifying Image Channels**

- Adjusts the Hue channel to shift colors.
- Merges modified channels and converts back to RGB.

8 **Saving Images**

- Saves processed images using cv2.imwrite.
- Reads and displays saved images to verify successful storage.

## Conclusion
This project provides a foundational understanding of image processing with OpenCV. By working with grayscale and color images, manipulating channels, and converting color spaces, users gain essential skills for more advanced computer vision tasks.
