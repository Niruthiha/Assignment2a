# Comparative Study of Artificial Neural Networks (ANNs) in Binary and Multi-class Classification Tasks

## Overview
This project explores the implementation and performance of Artificial Neural Networks (ANNs) in two distinct classification tasks: Credit Card Customer Churn Prediction and Maternal Health Risk Assessment. It demonstrates the application of ANNs to real-world problems, highlighting the challenges and effectiveness of these models in different scenarios.

## Author
Niruthiha Selvnayagam (Student ID: 002413183)

## Course
INFO6105 Fall 2024

## Datasets
1. Credit Card Customers Dataset
   - 23 attributes, 10,000 instances
   - Source: [Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

2. Maternal Health Risk Dataset
   - 6 attributes, 1,013 instances
   - Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/863/maternal+health+risk)

## Key Features
- Data preprocessing techniques including null value handling, label encoding, and feature scaling
- ANN model architecture design for binary and multi-class classification
- Performance analysis using metrics such as accuracy, precision, recall, and F1-score
- Comparative study of ANN performance on datasets of different sizes and complexities

## Requirements
- Python 3.7+
- TensorFlow 2.x
- Scikit-learn
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Setup and Installation
1. Clone this repository

2. Install required packages

## Results
- Credit Card Churn model: 93% accuracy
- Maternal Health Risk model: 70% accuracy
- Detailed analysis and visualizations available in the respective notebooks

## Conclusions
This study highlights the significant impact of dataset size and complexity on ANN performance in classification tasks. While the Credit Card Churn model demonstrated strong performance with a larger, more complex dataset, the Maternal Health Risk model faced challenges typical of limited data scenarios.

## Future Work
- Explore advanced techniques for handling limited data in critical domains like healthcare
- Implement ensemble methods to improve model performance
- Investigate the use of transfer learning for the smaller dataset

## References
1. C. Li, J. Wang, L. Wang, L. Hu and P. Gong, "Comparison of Classification Algorithms and Training Sample Sizes in Urban Land Classification with Landsat Thematic Mapper Imagery," Remote Sensing, vol. 6, no. 2, 2014.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
