# Sigma ML - Quiz 3

This project showcases several common image processing techniques implemented using Python and OpenCV. It involves processing a portrait image to perform contrast enhancement, extracting a binary mask, detecting edges using morphological operations and the Canny edge detector, and segmenting the foreground using the GrabCut algorithm.

## Features
- **Contrast Enhancement**: Uses Histogram Equalization on the HSV Value channel to improve contrast.
- **Mask Extraction**: Applies Otsu's Thresholding to extract the person's binary mask.
- **Edge Detection**: Extracts edges using both Morphological Gradient and the Canny Edge Detector.
- **Image Segmentation**: Utilizes OpenCV's GrabCut algorithm to segment the foreground (person) from the background.

### Input: 
- **Input Image**  
  ![Input Image](./reports/portrait_lady.png)

### Output:

- **Contrast Enhanced Image**  
  ![Contrast Enhanced Image](./reports/outputs/contrast_enhanced_image.png)

- **Binary Mask with Otsu’s Thresholding**  
  ![Binary Mask with Otsu’s Thresholding](./reports/outputs/binary_mask_otsu.png)

- **Edge Detection using Morphological Gradient**  
  ![Edge Detection using Canny](./reports/outputs/morphological_edges.png)
  
- **Edge Detection using Canny Edge Detector**  
  ![Edge Detection using Canny](./reports/outputs/canny_edges.png)

- **Image Segmentation with GrabCut**  
  ![Image Segmentation with GrabCut](./reports/outputs/segmented_image_grabcut.png)

### License

This project is licensed under the MIT License.
