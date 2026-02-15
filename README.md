# Lab 5 – Face Detection and Clustering using K-Means

## Aim

The objective of this lab is to detect faces in an image and group them using clustering based on color features.

## Methodology

* Face detection was performed using OpenCV’s Haar Cascade classifier.
* Detected face regions were converted from BGR to HSV color space.
* Hue and Saturation values were extracted as features.
* K-Means clustering was applied to group faces based on these features.
* A template face image was classified into one of the clusters and visualized.

## Results

Faces in the given image were successfully detected and grouped into clusters.
The template image was also assigned to a cluster based on its hue and saturation values.

## Conclusion

This lab demonstrates how computer vision techniques and unsupervised learning algorithms like K-Means can be used together for basic face analysis and grouping tasks.

## Tools & Libraries Used

Python, OpenCV, NumPy, Matplotlib, Scikit-learn
