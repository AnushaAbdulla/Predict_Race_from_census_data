## Predict Race from Census Data

# Project Overview

My final project from the Summer ML Course at Cornell through Break Thru Tech AI focused on developing a machine learning model to classify individuals based on race using census data. This binary classification project aimed to address challenges in model performance, feature optimization, and data imbalance, while also highlighting the broader issue of algorithmic bias.

# Objectives and Goals

- Build a Random Forest (RF) model for binary racial classification.
- Understand and minimize misclassifications, particularly false negatives.
- Optimize model performance through hyperparameter tuning and feature selection.
- Explore multi-class classification as an alternative approach.
- Address challenges related to data imbalance and algorithmic bias.

## Methodology
1. Data Preparation:
  - Processed census data to create a binary classification dataset.
  - Explored feature distributions and their contributions to the target variable.
2. Model Development:
  - Built an initial Random Forest model and evaluated performance using confusion matrices.
  - Identified high rates of false negatives and focused on improving these results.
3. Hyperparameter Tuning:
  - Conducted a grid search to optimize parameters for better accuracy and balanced predictions.
4. Feature Selection:
  - Analyzed feature importance and retained the top 20 features to simplify the model.
5. Exploration of Multi-Class Classification:
  - Encoded the dataset for multi-class predictions and compared results to the binary model.
6. Bias Analysis:
  - Investigated the impact of imbalanced class distributions on model performance and explored undersampling strategies.

# Results and Key Findings
- The refined Random Forest model achieved a 90% accuracy rate with the top 20 features.
- Despite optimization, the binary model struggled with high false negative rates, particularly in misclassifying individuals as black when they were not.
- Multi-class classification did not surpass the accuracy of the binary classification model.
- Attempts to mitigate class imbalance through undersampling led to diminished overall performance.
- Highlighted the importance of addressing algorithmic bias to prevent perpetuation of stereotypes inherent in the data.

# Visualizations
- Feature importance rankings and their impact on classification.
- Confusion matrix visualizations to analyze misclassifications.
- Accuracy trends during hyperparameter tuning.

#Potential Next Steps
- Obtain or adjust datasets to balance class distributions, ensuring adequate representation of all groups in the training set.
- Explore advanced methods for handling class imbalance, such as Synthetic Minority Oversampling Technique (SMOTE).
- Investigate alternative algorithms or ensemble methods for improved multi-class classification performance.
- Conduct bias audits and fairness metrics analysis to further mitigate algorithmic bias.

# Individual Contributions
- Developed and implemented the Random Forest model for binary and multi-class classification.
- Conducted feature importance analysis and feature selection.
- Tuned hyperparameters using grid search.
- Evaluated and addressed challenges related to data imbalance and bias.
- Documented findings and prepared recommendations for future improvements.

# Installation Instructions

To set up the project locally, follow these steps:

1. Clone the Repository:

`git clone https://github.com/your-username/predict-race-census.git
cd predict-race-census`

2. Install Required Libraries:
   Ensure Python 3.x is installed.

3. Install dependencies:

`pip install -r requirements.txt`

4. Prepare the Dataset:
   Download and preprocess the dataset (instructions provided in the data/README.md).

5. Train the Model:
   Run the training script:

`python train_model.py`

6. Evaluate the Model:
   Evaluate the trained model’s performance:

`python evaluate_model.py`

# Documentation

  User Guide:

Detailed instructions for using the model, including input formats and expected outputs.

  API Documentation:

Information on available functions and classes for extending or integrating the project into other systems.

Comprehensive project documentation is available in the docs/ folder.

# Contact

For questions or collaboration, please reach out:

- [**GitHub**](https://github.com/AnushaAbdulla)
- [**LinkedIn**](https://www.linkedin.com/in/AnushaAbdulla)
