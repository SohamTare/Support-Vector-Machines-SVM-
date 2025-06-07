# Task-7-Support-Vector-Machines-SVM-
Support Vector Machines (SVM)

## 🧠 Objective
Use SVMs for binary classification on the Breast Cancer dataset using both Linear and RBF kernels. Visualize decision boundaries using PCA and evaluate performance using multiple metrics.

## 📁 Dataset
- **Source:** sklearn.datasets `load_breast_cancer()`
- **Target:** `Malignant` vs `Benign`

## 🔨 Steps Performed

1. Loaded dataset from sklearn
2. Scaled features using `StandardScaler`
3. Trained SVM with Linear and RBF kernels
4. Evaluated using Accuracy, Confusion Matrix, and Classification Report
5. Performed 5-fold Cross Validation
6. Reduced data to 2D using PCA for visualization
7. Plotted SVM decision boundary

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision, Recall, F1**
- **Cross-validation Accuracy**
- **Decision Boundary in 2D (PCA)**

## 🔧 Libraries Used
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- NumPy


