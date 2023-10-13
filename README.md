# Breast Cancer Prediction Project

This project aims to predict whether a tumor is malignant or benign using machine learning techniques. It utilizes the Support Vector Machine (SVM) and Random Forest classifiers for prediction. Additionally, it explores the impact of feature selection on model performance.



## Dependencies
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- PrettyTable

### Predicting Tumor Classification

The project provides a function named `tumorClassification()` which allows you to predict tumor classification for a given set of features. Here's an example of how to use it:

```python
data_for_malignent_tumor = (20.57, 17.77, 132.9, 1326, ...)  # Provide actual values
result = tumorClassification(data_for_malignent_tumor)
print(result)
```


