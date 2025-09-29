# Task 5: Decision Trees and Random Forests (AI & ML Internship)

## 🎯 Objective
Learn tree-based models for classification and regression using Decision Trees and Random Forests.

## 📂 Dataset
- **Heart Disease Dataset** ([Kaggle link](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset))
- Target variable: `target` (1 = Disease, 0 = No Disease)

## 🛠️ Steps Performed
1. **Loaded and explored dataset**
   - Checked structure, data types, and missing values.

2. **Prepared features and target variable**
   - `X = df.drop('target', axis=1)`
   - `y = df['target']`

3. **Train/test split**
   - Divided dataset into 80% training and 20% testing sets.

4. **Trained a Decision Tree Classifier**
   - Built baseline tree model.
   - Visualized the tree using `plot_tree`.

5. **Analyzed overfitting and controlled depth**
   - Restricted `max_depth` to prevent overfitting.
   - Compared accuracy of full-depth vs limited-depth tree.

6. **Trained a Random Forest Classifier**
   - Built an ensemble of decision trees.
   - Compared accuracy with single decision tree.

7. **Interpreted feature importances**
   - Visualized most important features contributing to classification.

8. **Cross-validation**
   - Applied 5-fold cross-validation to check model stability.

## 📊 Evaluation
- **Decision Tree Accuracy** (baseline and controlled depth)
- **Random Forest Accuracy** (usually higher due to ensemble learning)
- **Cross-Validation Scores** (model generalization check)
- **Feature Importances** (understanding which features impact predictions)

## 🧰 Tools Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 📦 Deliverables
- Jupyter Notebook: `task5.ipynb`
- README documentation (this file)

