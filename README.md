# 🧠 AI & ML Internship – Task 7: Support Vector Machines (SVM)

## 📌 Objective
Use Support Vector Machines (SVMs) for **linear and non-linear classification** on a binary dataset.

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib

---

## 📂 Dataset
- **Dataset used**: Breast Cancer Wisconsin Dataset (from scikit-learn)
- **Type**: Binary Classification (Malignant vs Benign)

---

## ✅ Task Flow

1. **Load & preprocess data**  
   - Standardized features using `StandardScaler`
   - Split into training and test sets

2. **Train SVM Classifiers**  
   - **Linear Kernel**
   - **RBF (Radial Basis Function) Kernel**

3. **Evaluate Model Performance**  
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)
   - Accuracy Score

4. **Hyperparameter Tuning**  
   - Used `GridSearchCV` to tune:
     - `C`: [0.1, 1, 10]
     - `gamma`: [1, 0.1, 0.01]
     - `kernel`: 'rbf'

5. **Cross-Validation**  
   - 5-Fold cross-validation for model validation
   - Reported average CV score

6. **(Optional)**: PCA + 2D Decision Boundary Visualization

---

## 📈 Results

- **Best Parameters**:  
  `{'C': 10, 'gamma': 0.01, 'kernel': 'rbf'}`

- **Best Estimator Accuracy**:  
  `98.25%`

- **Cross-Validation Scores**:  
  `[0.9737, 0.9825, 0.9737, 0.9911]`

- **Average CV Score**:  
  `97.89%`

---

## 💡 What I Learned

- Concept of **margin maximization** in SVM  
- Importance of **kernel trick** for non-linear classification  
- How to **tune hyperparameters** like C and gamma  
- Using **cross-validation** for robust model evaluation

---

## 📌 Conclusion

SVM performed excellently on this dataset. Hyperparameter tuning and kernel selection played a crucial role in achieving high accuracy and generalization.

---

### 👩‍💻 Submitted by:
**Reeta Kambar**  
AI & ML Internship – Elevate Labs + MSME
