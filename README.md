# Feature Transformation: Binarization & Binning (Titanic Dataset)

This project focuses on feature engineering techniques—specifically Binarization and Binning/Discretization—and evaluates their impact on model performance using the Titanic dataset.

What’s Covered
1. Binarization

Created a new family feature from SibSp + Parch

Applied Binarizer to convert the feature into binary form

Used ColumnTransformer to apply transformations cleanly

Compared model performance before vs after binarization

Evaluated using DecisionTreeClassifier with cross-validation

2. Binning / Discretization

Applied KBinsDiscretizer on Age and Fare

Used different strategies:

Quantile binning

KMeans binning

Visualized feature distribution before and after discretization

Compared accuracy with and without binning

Built a reusable function to test different bin sizes and strategies

Tools & Libraries

Python, Pandas, NumPy

Scikit-learn

Matplotlib

ColumnTransformer, KBinsDiscretizer, Binarizer

Key Takeaway

Feature transformation can significantly affect model behavior.
This project shows when discretization or binarization helps, when it doesn’t, and why blindly applying transformations is a bad idea.

Next.
Day 9: Feature Engineering — Handling Mixed Variables (Numerical + Categorical)
