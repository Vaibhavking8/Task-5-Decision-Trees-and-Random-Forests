# Task-5-Decision-Trees-and-Random-Forests

This project analyzes a heart disease dataset using machine learning models: Decision Tree and Random Forest. It aims to evaluate model performance, interpret feature importance, and avoid overfitting.

## Tasks Performed

1. **Train a Decision Tree Classifier**
   - Visualized the decision tree.
   - Observed that unrestricted depth can lead to overfitting.

2. **Control Tree Depth**
   - Tested different `max_depth` values.
   - Identified optimal depth range (~4–6) to balance bias and variance.

3. **Train a Random Forest Classifier**
   - Compared its accuracy to the best Decision Tree.
   - Achieved better generalization and stability.

4. **Interpret Feature Importances**
   - Extracted and visualized top contributing features using Random Forest.

5. **Evaluate with Cross-Validation**
   - Applied 5-fold cross-validation to both models.
   - Random Forest showed higher mean accuracy with lower variance.
