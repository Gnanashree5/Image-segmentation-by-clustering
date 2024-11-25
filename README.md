###Image Processing and Segmentation Techniques
##Introduction
This repository explores various image processing techniques, focusing on image segmentation using clustering methods. We delve into concepts such as Human Stereopsis, Binocular Fusion, and different clustering techniques like K-means, DBScan, and Agglomerative clustering. Additionally, we implement short boundary detection and background subtraction.

#Contents
Introduction to Image Processing Techniques

Image Segmentation Using K-means Clustering

Enhanced Image Processing: Grayscale, Boundary Detection, and Background Subtraction

##1. Introduction to Image Processing Techniques
In this section, we provide an overview of key concepts in image processing, including:

#Segmentation by Clustering: Techniques like K-means, DBScan, and Agglomerative clustering.

#Applications: Implementing short boundary detection and background subtraction.

#Image Segmentation by Clustering Pixels: Detailed exploration of clustering methods to segment images effectively.

##2. Image Segmentation Using K-means Clustering
This section demonstrates how to perform image segmentation using K-means clustering. Image segmentation is the process of partitioning an image into multiple segments to simplify or change the representation of an image into something more meaningful.

#Steps Followed:
Image Loading:

Load the image from a specified path and convert it to RGB color space for better processing.

#Reshape Image:

Reshape the image from a 3D array (height, width, color channels) to a 2D array of pixels. This makes it suitable for applying K-means clustering.

#Apply K-means Clustering:

Define the number of clusters (K) and apply K-means clustering to group similar pixels together.

#Reshape Segmented Image:

Reshape the clustered pixels back to the original image dimensions to view the segmented image.

#Display Images:

Use matplotlib to display the original and segmented images side-by-side for comparison.

##3. Enhanced Image Processing: Grayscale, Boundary Detection, and Background Subtraction
Building upon the previous code, this section introduces grayscale conversion, boundary detection, and background subtraction with a blue background.

#Steps Followed:
Image Loading and Display:

Load the image from a specified path, verify it's loaded correctly, and display it using matplotlib.

#Grayscale Conversion:

Convert the RGB image to a grayscale image to simplify the boundary detection process.

#K-means Clustering for Segmentation:

Similar to the previous code, apply K-means clustering to segment the image into different clusters.

#Boundary Detection:

Use the Canny edge detection algorithm on the grayscale image to detect edges and display the result.

#Background Subtraction:

Apply a mask to subtract the background, setting it to blue while keeping the foreground (greenery) intact.

#Display Processed Images:

Display the original image, grayscale image, segmented image, edge detection result, and the final image with background subtraction using matplotlib.

##Acknowledgement
This project is done under guidance of https://github.com/Victor-Ikechukwu
