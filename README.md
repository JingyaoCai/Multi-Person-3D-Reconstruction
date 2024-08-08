# Multiple Photorealistic Human 3D Reconstruction from Single Image
## Abstract
Reconstructing human pose and shape from a monocular view is a longstanding problem in the field of computer graphics. The goal is to reconstruct the 3D model of human body surface from an image or a video. Most existing monocular human reconstruction methods have achieved great progress which primarily focus on single-person reconstruction. However, research on multi-person reconstruction from a monocular perspective still face certain challenges. In this project, I present a novel learning framework capable of reconstructing multiple individuals with full details, including their clothing, faces, hair, and more, from a single image. For this method, I first employ a segmentation model to extract all elements from an input image. Then, I train a network to select the segmented images containing entire human figures. After image processing, I construct my own depth estimation network using UNet and ResNet to predict the depth information in the image, as it can be regarded as location in 3D space. Finally, I use an implicit function model for single-person reconstruction from a single image and position the individual 3D human models at the predicted locations in 3D space. The final results show great performance in my method.
## Introduction
## Literature Review
## Methodology
## Result
## Future Work
## Conclusion
