# ❤️ Heart Disease Prediction using Decision Trees & Random Forest

This project demonstrates how to predict the presence of heart disease using Decision Trees and Random Forest classifiers. It also shows how to visualize trees, analyze overfitting, and evaluate models.

---

## 📌 Steps Performed

1. **Decision Tree Classifier**
   - Trained on the heart disease dataset.
   - Visualized the tree using `plot_tree`.

2. **Overfitting Control**
   - Experimented with different `max_depth` values.
   - Compared train vs test accuracy.

3. **Random Forest Classifier**
   - Trained with multiple trees.
   - Compared accuracy with Decision Tree.

4. **Feature Importance**
   - Identified most important features (e.g., age, cholesterol, chest pain type).

5. **Cross-Validation**
   - Used `cross_val_score` to validate model performance.

---

## 📊 Results

- **Decision Tree**: High training accuracy but prone to overfitting.  
- **Random Forest**: More stable and better generalization.  
- **Important Features**: Age, cholesterol, and exercise-induced angina showed higher importance.  
- **Cross-validation**: Ensures reliable accuracy estimation.  

---

## 🛠️ Tech Stack
- Python  
- Scikit-learn  
- Matplotlib / Seaborn  
- Pandas, NumPy  

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
python heart_disease_prediction.py
