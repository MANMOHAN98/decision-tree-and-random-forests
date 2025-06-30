Objective
Learn and implement Decision Tree and Random Forest models for classification using Scikit-learn. Analyze model performance, overfitting, and feature importance.

 Dataset
*Heart Disease Dataset*  
Source: [Kaggle - Heart Disease](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
Filename used: heart.csv

Tools & Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Graphviz (optional for tree visualization)

 Tasks Performed

1. *Data Loading & Preprocessing*
   - Loaded heart disease dataset
   - Split data into features and labels
   - Performed train-test split

2. *Decision Tree Classifier*
   - Trained default decision tree
   - Evaluated accuracy and classification report
   - Visualized tree structure
   - Limited tree depth to control overfitting

3. *Random Forest Classifier*
   - Trained Random Forest with 100 trees
   - Compared performance with Decision Tree
   - Plotted feature importances

4. *Cross-Validation*
   - Evaluated model with 5-fold cross-validation
   - Reported mean accuracy

Results

| Model              | Accuracy |
|-------------------|----------|
| Decision Tree      | ~81%     |
| Decision Tree (Depth=3) | ~78%     |
| Random Forest      | ~85%     |
| Cross-Validation (RF) | ~83-86% |

Visuals Included
- Decision tree plot
- Feature importance bar graph

 Concepts Covered
- Decision trees and splitting rules
- Overfitting and controlling depth
- Ensemble learning and bagging
- Feature importance interpretation
- Cross-validation for reliable evaluation


