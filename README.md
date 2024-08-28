# Brain Tumor Detection

This repository contains the code and resources for detecting brain tumors using various advanced image processing techniques. The methodologies employed in this project include fuzzy clustering, texture segmentation, the watershed algorithm, and a support vector machine (SVM) with semi-supervised clustering. The goal of this project is to enhance the accuracy, time efficiency, and reliability of brain tumor detection, ultimately contributing to improved diagnostic and treatment planning.

## Table of Contents

- [Introduction](#introduction)
- [Methodologies](#methodologies)
- [Tools Used](#tools-used)
- [Installation](#installation)
- [Dependencies](#dependencies).
- [Usage](#usage)
- [Accuracy Detection](#accuracy-detection)
- [Contributors](#contributors)

## Introduction

Brain tumor detection is a critical area of medical imaging research aimed at enhancing diagnostic accuracy and treatment efficacy. This project integrates various advanced methodologies to improve the precision and reliability of identifying tumor regions within brain images, thereby empowering clinicians with early and accurate diagnostic insights.

## Preview


![image](https://github.com/user-attachments/assets/5d74fe47-baa1-4d19-b36f-e99ef664eebf)



The above image provides a preview of the brain tumor detection process using random forest and other image processing algorithms.

## Methodologies

### Fuzzy Clustering
Fuzzy clustering is used to segment complex brain tissue structures by assigning pixels a membership value representing their likelihood of belonging to multiple clusters. This probabilistic approach helps in accurately delineating tumor boundaries where tissue overlaps or is ambiguous.

### Texture Segmentation
Texture segmentation analyzes patterns and variations in pixel intensities to differentiate between different tissue types. By capturing intricate textural features, this method enhances the segmentation accuracy and specificity of tumor regions within brain images.

### Watershed Algorithm
The watershed algorithm is employed to refine segmentation by simulating a flooding process that delineates boundaries between distinct regions. In this project, it is particularly useful for pinpointing the exact location of blood leakage or other abnormalities within the brain.

### Support Vector Machine (SVM)
SVM with semi-supervised clustering leverages both labeled and unlabeled data to improve classification accuracy. This approach is essential for distinguishing between tumor and non-tumor regions, especially when labeled data is limited.

## Tools Used

- **MATLAB**
  
  <img src="https://github.com/user-attachments/assets/7f589ea9-2624-44a9-9d6e-0cf2aa8127e2" alt="image" width="100" />

  
  MATLAB is used for implementing and testing various image processing algorithms, such as fuzzy clustering and texture segmentation.

- **C++**
 
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" alt="C++" width="100" />
  
  C++ is utilized for optimizing the performance of computationally intensive algorithms, including the watershed algorithm and SVM.


  
## Dependencies

Ensure you have the following software installed:

- **MATLAB**
- **C++ compiler** (e.g., GCC, Visual Studio)
- **Python** (if using additional scripts for data processing)
- **OpenCV** (for image processing)

## Usage

To run the algorithms, follow these steps:

1. **Preprocess the images** using the provided scripts in the `preprocessing/` directory.
2. **Run the segmentation algorithms** in MATLAB by executing the scripts in the `fuzzy_clustering/` and `texture_segmentation/` directories.
3. **Apply the watershed algorithm** using the C++ code provided in the `watershed/` directory.
4. **Classify tumor regions** with the SVM implementation in `svm/`.

Refer to the individual directories for detailed instructions and code usage examples.

## Accuracy Detection

The graph below illustrates the accuracy, time, and error rate for brain tumor detection using various algorithms such as K-means, Naïve classifier, and Random Forest.


![image](https://github.com/user-attachments/assets/fcb7a4f4-bbd7-4b9d-a1c2-c80d9af1a6a7)


As shown in the image, the Random Forest algorithm achieves the highest accuracy with a relatively low error rate compared to other methods.



## Installation

To clone and run this project locally, follow these steps:

``bash
git clone https://github.com/jai-nithish/brain_tumor_detection.git
cd brain_tumor_detection

## Contributors

- **Your Name** - [GitHub Profile](https://github.com/jai-nithish)
- **Collaborator Name** - [GitHub Profile](https://github.com/jai-nithish)

