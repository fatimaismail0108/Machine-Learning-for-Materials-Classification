# Machine-Learning-for-Material-Classification
Developed an end-to-end machine learning pipeline to classify materials properties using Python and scikit-learn. The project includes modular preprocessing, modelling, and evaluation components, with robust data cleaning, feature engineering (median imputation, standardisation), and stratified train–test splitting to handle missing values and class imbalance.

Implemented and benchmarked multiple classifiers (Logistic Regression, Random Forest, SVM, KNN) using 5-fold cross-validation and key metrics (accuracy, precision, recall, F1-score, confusion matrices). Conducted feature importance analysis and feature-subset experiments, revealing that band gap alone predicts electrical conductivity, enabling potential measurement cost reductions.

Generated learning curves to quantify performance versus dataset size, ensuring reproducible ML practices via pipelines and ColumnTransformers to prevent data leakage. Results were communicated through technical visualisations, linking model behaviour to physically meaningful insights in materials science.
