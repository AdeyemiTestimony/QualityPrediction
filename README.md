# Automatic Inspection of Casting Defects in Casting Products Using Deep Learning

[LINK TO DEPLOYED PROJECT](https://casting-quality-prediction.streamlit.app/)

## Project Overview

### Context
In the manufacturing industry, minimizing processing errors is crucial for maximizing profits. Manual inspection, while widely used, presents challenges such as variable accuracy among inspectors and increased labor costs. This project aims to address these challenges by automating the inspection process through machine learning.

Casting is a crucial manufacturing process involving the pouring of liquid material into a mold, allowing it to solidify into the desired shape. Unfortunately, the casting process is prone to defects such as blow holes, pinholes, burr, shrinkage defects, mould material defects, pouring metal defects, and metallurgical defects. Manual inspection, the traditional approach to identify and rectify defects, is time-consuming and lacks precision, leading to potential financial losses for companies.

### Project Objective
The primary goal of this project is to automate the inspection process by identifying defects in casting products by developing a deep learning classification model. By leveraging machine learning, we aim to enhance accuracy, reduce manual labor, and mitigate the risk of defective product rejection, ultimately optimizing the manufacturing process.

### Dataset
The dataset comprises top-view images of submersible pump impellers, obtained under stable lighting conditions. The dataset includes a total of 7348 grayscale images, each with dimensions of (300*300) pixels. Augmentation has been applied to all images to enrich the training data.

Additionally, a set of images with a size of 512x512 pixels, without augmentation, has been uploaded. This subset contains 519 images labeled as 'defective' and 781 images labeled as 'ok_front.'

#### Categories:
1. **Defective**
2. **Ok**

#### Dataset Split:
- **Training Data:**
  - Defective (def_front): 3758 images
  - Ok (ok_front): 2875 images

- **Testing Data:**
  - Defective (def_front): 453 images
  - Ok (ok_front): 262 images

### Significance
Automating the inspection process can potentially eliminate the bottleneck associated with manual inspection, leading to improved accuracy, reduced labor costs, and increased overall efficiency in the manufacturing of casting products.

By leveraging deep learning, this project strives to revolutionize the quality assurance process, ensuring that defects are identified and addressed with precision, ultimately contributing to the overall success of casting manufacturing.

### How to Test
Click on this [link](https://github.com/AdeyemiTestimony/QualityPrediction/tree/main/archive/casting_data/casting_data/test) to go to the [path](https://github.com/AdeyemiTestimony/QualityPrediction/tree/main/archive/casting_data/casting_data/test) of the images and you can upload images from either `def_front` or `ok_front`
