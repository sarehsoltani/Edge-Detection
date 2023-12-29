# Edge Detection with OpenCV

## Introduction

The objective of this project is to explore different edge detection algorithms available in OpenCV and analyze their effectiveness in identifying edges within images. The primary focus algorithms used in this project are Canny, Sobel, and Laplacian.

## Results
The project results demonstrate the effectiveness of edge detection algorithms based on comparative analysis. The conclusion drawn from the experiment is that Canny provides the most optimal edge detection results among the tested algorithms due to its ability to reduce noise while accurately detecting edges.

### Original Image

![Original Image](https://github.com/sarehsoltani/Edge-Detection/assets/23232055/ffed22a6-26ee-4f15-b330-16ddc2509e2f)


### Canny Edge Detection Result

![Canny Edge Detection](https://github.com/sarehsoltani/Edge-Detection/assets/23232055/e09fddb1-5768-46ea-9e1d-25fac195d6a9)


### Sobel Edge Detection Result

![Sobel Edge Detection](https://github.com/sarehsoltani/Edge-Detection/assets/23232055/58851322-3711-4a39-82a9-f4263a012333)


### Laplacian Edge Detection Result

![Laplacian Edge Detection](https://github.com/sarehsoltani/Edge-Detection/assets/23232055/8c1b82c6-ac31-4087-834e-378786f1ecdb)

### Why Canny Edge Detection Stands Out

Among various edge detection algorithms available, Canny edge detection emerges as a prominent choice due to its exceptional accuracy, robustness against noise, and precise edge localization capabilities. The Canny algorithm boasts a low error rate by minimizing false edge detections through edge thinning and preserving strong edges. Its ability to accurately locate edges, even in noisy images, makes it a preferred choice for many computer vision applications. Canny's utilization of hysteresis thresholding aids in distinguishing between strong and weak edges, resulting in more continuous and meaningful edge maps. Moreover, its parameter tunability, computational efficiency, and widespread acceptance in the field of image processing further solidify its position as a go-to algorithm for tasks demanding accurate edge detection.
