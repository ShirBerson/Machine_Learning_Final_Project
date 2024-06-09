# Machine Learning Final Project
## **Is a file malicious?**
**By: Shir Berson and Michal Gogol**

This project was completed as a final project for a Machine Learning course at Tel Aviv University. The goal was to develop a model to predict whether executable files (.exe) are malicious based on static analysis.

### Overview
We were provided with a dataset containing features of executable files, some known and some anonymous, and tasked with building a binary classification model to determine if a file is malicious (1) or benign (0). The dataset comprised 60,000 observations labeled as malicious or non-malicious.

### Methodology
- **Exploratory Data Analysis**: Analyzed the dataset to understand feature distributions and relationships.
- **Preprocessing**: Normalized features, handled missing values, and removed outliers using techniques like Z-Score and Local Outlier Factor (LOF).
- **Feature Engineering**: Created new features, such as size-to-virtual size ratios, to enhance model performance.
- **Modeling**: Implemented and compared various models, including Logistic Regression, KNN, SVM, and AdaBoost, with hyperparameter tuning.
- **Model Selection**: Selected AdaBoost as the final model due to its high AUC score and strong predictive capabilities.

### Key Achievements
- **Grade**: Received a score of 94 for the project.

### Conclusion
This project showcases the application of machine learning techniques to malware classification, resulting in a robust model capable of accurately distinguishing between malicious and benign files. Our work highlights the importance of data preprocessing, feature engineering, and model optimization in developing effective machine learning solutions.
