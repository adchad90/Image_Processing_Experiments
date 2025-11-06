# Image_Processing_Experiments

This repository contains the lab work for the **Image Processing Laboratory (R5IT3102L)** conducted during the **Odd Semester AY 2025–26** at **Veermata Jijabai Technological Institute (VJTI), Mumbai**.

Each experiment focuses on a different concept in **digital image processing**, implemented using **Python**, **NumPy**, **OpenCV**, and **Matplotlib**.

---

## Table of Contents

1. [Basic Image Manipulations and Transformations](#1-basic-image-manipulations-and-transformations)  
2. [Histogram Display and Equalization](#2-histogram-display-and-equalization)  
3. [Linear and Non-Linear Filtering for Noise Smoothing](#3-linear-and-non-linear-filtering-for-noise-smoothing)  
4. [Edge Detection using Operators](#4-edge-detection-using-operators)  
5. [Filtering in the Frequency Domain](#5-filtering-in-the-frequency-domain)  
6. [Morphological Operations and Feature Extraction](#6-morphological-operations-and-feature-extraction)  
7. [Image Segmentation](#7-image-segmentation)  
8. [Image Compression and Decompression](#8-image-compression-and-decompression)  
9. [Color Image Reading, Writing, and Manipulations](#9-color-image-reading-writing-and-manipulations)  
10. [Color Image Enhancement and Histogram Manipulation](#10-color-image-enhancement-and-histogram-manipulation)

---

## 1. Basic Image Manipulations and Transformations

**Description:**  
This experiment focuses on setting up the necessary image processing libraries in a Python environment (like **NumPy**, **Matplotlib**, and **OpenCV/scikit-image**). It includes performing core operations such as reading, displaying, and writing images, along with simple transformations like **resizing**, **rotation**, and **changing color spaces**.

---

## 2. Histogram Display and Equalization

**Description:**  
This program demonstrates the creation and visualization of an image's histogram, which shows the distribution of pixel intensities. The main goal is to implement **Histogram Equalization**, a technique used to stretch the intensity range, thereby enhancing the contrast of the image.

---

## 3. Linear and Non-Linear Filtering for Noise Smoothing

**Description:**  
This experiment explores different methods for reducing noise in an image. It includes implementing **linear filters** (such as the Mean/Averaging filter) and **non-linear filters** (such as the Median filter). The primary objective is to smooth the image while preserving edges as much as possible.

---

## 4. Edge Detection using Operators

**Description:**  
This program is dedicated to determining and highlighting the sharp discontinuities in an image, known as edges. It involves the implementation of basic **gradient-based operators** like the **Roberts**, **Prewitt**, or **Sobel** operators to compute the magnitude and direction of the image gradient.

---

## 5. Filtering in the Frequency Domain

**Description:**  
This experiment moves from spatial domain processing to the frequency domain using the **Fourier Transform (DFT/FFT)**. The code implements and applies various frequency domain filters, such as the **Ideal**, **Butterworth**, or **Gaussian** filters, to perform operations like **blurring (low-pass)** or **sharpening (high-pass)**.

---

## 6. Morphological Operations and Feature Extraction

**Description:**  
This covers fundamental **morphological operations** (**Erosion** and **Dilation**) and their combinations (**Opening** and **Closing**). It also demonstrates advanced operations like **Skeletonizing** (thinning objects to a single-pixel skeleton) and **extracting object boundaries** from binary images.

---

## 7. Image Segmentation

**Description:**  
This is a two-part experiment focusing on dividing an image into meaningful regions or objects. It includes implementing the **Split and Merge Technique** (a region-based method) and the **Watershed Transform** (a contour-based method that uses image topography and markers) for effective image partitioning.

---

## 8. Image Compression and Decompression

**Description:**  
This experiment focuses on **lossless image compression techniques** used to reduce image storage size without losing any information. Two algorithms are implemented:

- **Huffman Coding and Decoding** — encodes image data based on symbol frequency to achieve efficient bit-level compression.  
- **Arithmetic Coding and Decoding** — achieves higher compression efficiency by representing entire image data as a single fractional value within [0,1), based on symbol probabilities.

The experiment demonstrates both **compression and decompression pipelines** for grayscale and color images.

---

## 9. Color Image Reading, Writing, and Manipulations

**Description:**  
This program demonstrates how to handle **color images** in Python using libraries like **OpenCV** and **Matplotlib**. It includes reading and displaying color images, separating and merging the **RGB channels**, and performing basic manipulations such as **color inversion**, **intensity scaling**, and **channel swapping**.  
The goal is to understand how color information is represented and processed digitally.

---

## 10. Color Image Enhancement and Histogram Manipulation

**Description:**  
This experiment deals with **enhancement techniques** that improve the visual quality of color images. It focuses on operations such as **contrast stretching**, **gamma correction**, and **color normalization**.  
The experiment also implements **Histogram Equalization** and **Histogram Matching** for color images to enhance **dynamic range** and **color balance** across channels.

---

## Tools & Libraries Used

- **Python 3.12+**
- **NumPy**
- **Matplotlib**
- **OpenCV**
- **scikit-image**

---

## Author

**Aditya V Chavan**  
B.Tech in Information Technology  
**Veermata Jijabai Technological Institute (VJTI), Mumbai**

---

## License

This repository is intended for academic and educational use under the Image Processing Laboratory course (R5IT3102L).  
Feel free to use or reference the experiments for learning purposes.
