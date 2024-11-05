# Ensemble Classifiers Diabetes Risk Prediction

## Project Overview
This project provides a detailed analysis of a diabetes risk prediction dataset, implementing various ensemble learning techniques to classify risk levels effectively. Using a blend of visualization, preprocessing, and multiple ensemble classifiers, the project aims to improve classification accuracy and provide insights into the dataset's structure.

## Dataset Overview
- **Entries**: 520
- **Features**: 17 (mixed numerical and categorical)
- Initial exploration highlighted data distributions and prevalence across features, laying the groundwork for further analysis of diabetes-related symptoms and risk factors.

## Analysis and Methodology
1. **Exploratory Data Analysis (EDA)**:
   - **Univariate Analysis**: Analyzed feature distributions with histograms, count plots, and frequency tables.
   - **Bivariate Analysis**: Explored relationships between features using scatter plots, pair plots, and box plots.
   - **Correlation Analysis**: Computed correlation coefficients for numerical features to assess relationships.

2. **Data Preprocessing**:
   - Dropped irrelevant columns, performed one-hot encoding for categorical variables, and standardized numerical features.

3. **Ensemble Learning Models**:
   - Implemented and evaluated **Random Forest**, **AdaBoost**, **Logistic Regression**, and **Decision Tree** classifiers.
   - Developed **voting classifiers** (hard and soft) and applied **bagging (Random Forest)** and **boosting (AdaBoost)** techniques.
   - Model performance assessed using accuracy, classification reports, and confusion matrices.

## Key Findings
- The **Random Forest (Bagging Classifier)** achieved the highest accuracy at **99%**, followed by AdaBoost with 97% accuracy.
- Ensemble techniques such as **voting, bagging, and boosting** enhanced classification performance compared to individual models for diabetes risk prediction.
- Different methods can be chosen based on project-specific needs like interpretability, speed, or performance.

## Conclusion
Ensemble learning proved highly effective in diabetes risk prediction, with Bagging and Boosting methods providing significant accuracy improvements. This project highlights the versatility of ensemble classifiers for healthcare-related classification tasks.

---

## Future Work
- Experiment with other ensemble methods such as stacking.
- Explore feature engineering for potential performance improvements.

---
