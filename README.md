# Image Processing

This repository contains various image processing tasks implemented using Python. It covers a range of fundamental techniques in image processing. Below is a description of each notebook and the tasks they contain.

### 1. Image Sampling
Change the spatial resolution of an image from 256x256 to 128x128, 64x64, and 32x32 pixels using sub-sampling by factors of 2, 4, and 8 respectively. For comparison, resize the sub-sampled images back to the original size of 256x256. Use the "lenna" and "peppers" images to demonstrate the results.

### 2. Image Quantization
Reduce the number of gray levels (L) in a PGM image from 256 to 128, 32, 8, and 2. Display the results for the "lenna" and "peppers" images.

### 3. Histogram Equalization
Implement histogram equalization and apply it to the "boat" and "f_16" images. Display histograms before and after equalization.

### 4. Histogram Specification
Implement histogram specification and apply it to the "boat" and "f_16" images. Use the histogram of the "sf" image for the "boat" image and the histogram of the "peppers" image for the "f_16" image.

### 5. Correlation
Perform spatial filtering (correlation) on an image using provided images to define the weights of the mask.

### 6. Averaging and Gaussian Smoothing
Smooth the "lenna" and "sf" images using 7x7 and 15x15 averaging and Gaussian filters.

### 7. Median Filtering
Implement median filtering and apply it to "lenna" and "boat" images corrupted with salt and pepper noise. Compare results with averaging.

### 8. Unsharp Masking and High Boost Filtering
Implement unsharp masking and high-boost filtering. Apply them to the "lenna" and "f_16" images.

### 9. Gradient and Laplacian
Sharpen the "lenna" and "sf" images using Prewitt, Sobel, and Laplacian masks. Visualize the gradient magnitude and partial derivatives.

### 10. Noise Removal
Remove periodic noise from an image using band-reject and notch filters. Compare results with Gaussian filtering.

### 11. Convolution in the Frequency Domain
Perform convolution in the frequency domain using the "lenna" image and compare with spatial domain results.

### 12. Homomorphic Filtering
Apply homomorphic filtering to an image to correct shading problems due to uneven illumination. Experiment with different parameter values.

## Contributing
Feel free to contribute by opening an issue or submitting a pull request. Any contributions towards improving the implementations or adding new features are welcome.
