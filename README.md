# Experiment-6-IPMV
In Image Processing and Machine Vision (IPMV), Mean, Median, and Max filters are commonly used for noise reduction and image smoothing.

1 - Mean Filter (Averaging Filter)

It replaces each pixel with the average (mean) of the neighboring pixels in a defined window (e.g., 3×3 or 5×5).
Purpose: Reduces random noise and smooths the image.
Effect: Blurs edges and fine details.

2 - Median Filter

It replaces each pixel with the median value of the neighboring pixels.
Purpose: Excellent for removing salt-and-pepper noise while preserving edges.
Effect: Retains sharpness better than the mean filter.

3 - Max Filter

It replaces each pixel with the maximum value of the neighboring pixels.
Purpose: Enhances bright regions and removes black (minimum intensity) noise.
Effect: Useful in edge detection and feature enhancement.
These filters are often implemented using FPGA for real-time image processing due to their parallel processing capability. Let me know if you need a deeper explanation or implementation details! 🚀
