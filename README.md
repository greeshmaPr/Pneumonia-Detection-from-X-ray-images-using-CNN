# Pneumonia Detection from X-ray images using PyTorch Deep Learning Framework

This is an end-to-end project for classification of x-ray images as either pneumonia or normal using PyTorch deep learning framework.

## Data

The data available on Kaggle is sourced from [here](https://data.mendeley.com/datasets/rscbjbr9sj/2).
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5216 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

## Frameworks and Packages
 
 * PyTorch framework for deep learning model
 * OpenCV, numpy, pandas for image preprocessing
 * Seaborn, matplotlib for data visualization
 * Scikit-learn for performance metrics calculation
 * Project is hosted on Jupyter Notebook
 
## Project Organization
 * Exploratory Data Analysis
 * Data preprocessing
 * Correction for class imbalance in training data using PyTorch WeightedRandomSampling class
 * Building and training the classifier - Convolutional Neural Network
 * Performance Metrics calculation.






## Acknowledgements

License: CC BY 4.0

Data Citation: Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification”, Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2  http://dx.doi.org/10.17632/rscbjbr9sj.2