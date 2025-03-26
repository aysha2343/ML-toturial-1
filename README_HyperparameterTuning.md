# Hyperparameter Tuning with GridSearchCV and Cross-Validation

This tutorial demonstrates how to apply hyperparameter tuning using GridSearchCV in scikit-learn. We compare three classifiers—Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree—using cross-validation and pipeline structures for robust evaluation. The dataset used is the Breast Cancer Wisconsin dataset.

## Files

- hyperparameter_tuning_gridsearchcv_tutorial.ipynb: Main Jupyter notebook with full implementation
- README.md: This file, containing instructions and overview
- requirements.txt: Python packages required to run the notebook

## Dataset

The Breast Cancer dataset used in this tutorial is provided via `sklearn.datasets.load_breast_cancer`. It includes 30 numerical features describing the characteristics of cell nuclei from breast mass images, and a binary target indicating whether the tumor is benign or malignant.

## Objectives

- Understand what hyperparameters are and why tuning is important
- Learn how to use GridSearchCV with cross-validation
- Compare model performance using different parameter settings
- Use pipeline structures to prevent data leakage during preprocessing

## How to Run

1. Install Python (>=3.7)
2. Install dependencies using pip:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   jupyter notebook hyperparameter_tuning_gridsearchcv_tutorial.ipynb
   ```

## License

This project is shared under the MIT License.

## Acknowledgements

- Bergstra, J., & Bengio, Y. (2012). Random search for hyper-parameter optimization. Journal of Machine Learning Research.
- Pedregosa et al. (2011). Scikit-learn: Machine Learning in Python. JMLR.

