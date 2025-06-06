# Task 7: Elevate Labs AI/ML Internship Support Vector Machines (SVM) – Breast Cancer Classification

---

## Dataset
- Breast Cancer Diagnostic Dataset (`breast-cancer.csv`)
- 30 features extracted from cell nuclei (e.g., texture, radius, smoothness)
- Target: `diagnosis` → Benign (0), Malignant (1)

## Tools
- Python, scikit-learn, pandas, seaborn, matplotlib

## Steps Performed
1. **Data Cleaning & Encoding**
   - Removed ID column
   - Encoded `diagnosis` as binary (M → 1, B → 0)

2. **Feature Scaling**
   - Normalized with `StandardScaler`

3. **Model Training**
   - Linear SVM and RBF SVM
   - Evaluated test set accuracy

4. **Hyperparameter Tuning**
   - GridSearchCV with parameters C and gamma
   - Best model tested on test set

5. **PCA + 2D Visualization**
   - Reduced features to 2D using PCA
   - Visualized SVM decision boundary

---

## Results
- **Linear SVM Accuracy**: ~97–98%
- **RBF SVM Accuracy**: ~98–99%
- PCA boundary clearly separates benign and malignant cases

---

## Interview Concepts
- **Support Vector**: The boundary-defining data points
- **C Parameter**: Controls tradeoff between margin width and misclassification
- **Kernel**: Maps data into higher dimensions for separation
- **Linear vs RBF**: Linear → linearly separable; RBF → nonlinear flexibility

---
