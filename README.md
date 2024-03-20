# Breast Cancer Classification Project

## Dataset
For this project, the Breast Cancer Wisconsin (Diagnostic) dataset from scikit-learn was utilized. The dataset contains features extracted from digitized images of breast mass fine needle aspirates (FNA). These features describe various characteristics of cell nuclei present in the images, such as radius, texture, perimeter, area, smoothness, compactness, concavity, and more.

## Goals
1. **Data Exploration and Preprocessing**: Explore and preprocess the dataset to ensure its suitability for training machine learning models.
2. **Model Implementation and Comparison**: Implement and compare the performance of Decision Trees, Random Forest, and AdaBoost classifiers for breast cancer classification.
3. **Model Evaluation**: Evaluate the models using appropriate performance metrics and visualization techniques.

## Code Overview
### Data Importing and Preprocessing
The dataset was loaded using scikit-learn's `load_breast_cancer` function. Features and target labels were extracted from the dataset. The features were then converted into a Pandas DataFrame for ease of manipulation. Initial checks were performed to ensure there were no missing values and to examine the class distribution.

### Model Training and Evaluation
Three classifiers were initialized: Decision Tree, Random Forest, and AdaBoost. The models were trained on the training data and then used to make predictions on the test data. The accuracy scores were calculated for each classifier. Additionally, confusion matrices were generated to visualize the performance of each classifier.

### Results
- Accuracy score for Decision Tree Classifier: 94.74%
- Accuracy score for Random Forest Classifier: 96.49%
- Accuracy score for Ada Boost Classifier: 97.37%

## Conclusion
The results indicate that AdaBoost Classifier outperformed the other classifiers in terms of accuracy. However, the difference between Random Forest and AdaBoost is not significant. Decision Tree algorithm performed slightly poorer compared to ensemble approaches like Random Forest and AdaBoost, as reflected in the accuracy and confusion matrices.
