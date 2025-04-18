# Advnaced Image Processing Operations

This repository contains a Jupyter Notebook that demonstrates various image processing operations using OpenCV and Matplotlib. The notebook is organized into sections, each focusing on a specific type of image processing technique.

## Table of Contents

1. [Geometric Transformations](#geometric-transformations)
    - Translation
    - Rotation
    - Scaling
    - Affine Transformation
    - Perspective Transformation
    - Flipping
2. [Image Filtering](#image-filtering)
    - Average Blurring
    - Gaussian Blurring
    - Median Blurring
    - Bilateral Filtering
    - Sharpening
3. [Color Manipulation](#color-manipulation)
    - Color Space Conversion
    - Brightness and Contrast Adjustment
    - Channel Extraction and Merging
4. [Image Histograms](#image-histograms)
    - Histogram Calculation
    - Histogram Equalization
    - Adaptive Histogram Equalization (CLAHE)
5. [Image Segmentation](#image-segmentation)
    - Thresholding
    - Color-based Segmentation
    - Watershed Algorithm
    - GrabCut Algorithm
6. [Morphological Operations](#morphological-operations)
    - Erosion
    - Dilation
    - Opening
    - Closing
    - Morphological Gradient
    - Top Hat
    - Black Hat

---

## Geometric Transformations

Geometric transformations involve altering the spatial relationship of pixels in an image. These include:
- **Translation**: Shifting the image.
- **Rotation**: Rotating the image around a specified center.
- **Scaling**: Resizing the image.
- **Affine Transformation**: Mapping three points to their new locations.
- **Perspective Transformation**: Correcting perspective using four point correspondences.
- **Flipping**: Flipping the image horizontally, vertically, or both.

---

## Image Filtering

Image filtering techniques are used to enhance or modify images. These include:
- **Average Blurring**: Smoothing by averaging neighbors.
- **Gaussian Blurring**: Smoothing with a Gaussian kernel.
- **Median Blurring**: Effective for removing salt-and-pepper noise.
- **Bilateral Filtering**: Edge-preserving smoothing.
- **Sharpening**: Enhancing edges using convolution with a sharpening kernel.

---

## Color Manipulation

Color manipulation techniques include:
- **Color Space Conversion**: Converting between RGB, Grayscale, HSV, LAB, etc.
- **Brightness and Contrast Adjustment**: Adjusting the overall lightness and contrast of the image.
- **Channel Extraction and Merging**: Working with individual color channels.

---

## Image Histograms

Image histograms provide a frequency distribution of pixel values. Techniques include:
- **Histogram Calculation**: Calculating the frequency of pixel intensities.
- **Histogram Equalization**: Improving contrast in grayscale images.
- **Adaptive Histogram Equalization (CLAHE)**: Equalizing contrast in local regions.

---

## Image Segmentation

Image segmentation is the process of partitioning an image into meaningful regions. Techniques include:
- **Thresholding**: Creating binary images based on pixel intensity.
- **Color-based Segmentation**: Isolating objects based on their color.
- **Watershed Algorithm**: Separating touching objects.
- **GrabCut Algorithm**: Interactive foreground extraction.

---

## Morphological Operations

Morphological operations are used to process binary images. These include:
- **Erosion**: Shrinking foreground objects.
- **Dilation**: Expanding foreground objects.
- **Opening**: Erosion followed by dilation (removes small objects).
- **Closing**: Dilation followed by erosion (fills small holes).
- **Morphological Gradient**: Highlights the boundaries of objects.
- **Top Hat**: Highlights small bright objects.
- **Black Hat**: Highlights small dark objects.

---

## Requirements

- Python 3.x
- OpenCV
- Matplotlib
- NumPy

---

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the cells to explore various image processing techniques.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.