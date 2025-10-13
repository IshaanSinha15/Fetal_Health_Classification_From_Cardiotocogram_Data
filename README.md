Classify fetal health status (normal, suspect, pathological) from
cardiotocographic (CTG) measurements. This helps obstetricians assess fetal
well-being during pregnancy and delivery, enabling timely interventions when
necessary.

1.Features: baseline fetal heart rate, accelerations, fetal movement, uterine
contractions, variability measures, histogram features
Classes: Normal (1), Suspect (2), Pathological (3)

2.Model/Methods That Can Be Used
Logistic Regression (multi-class)  Random Forest, XGBoost for handling non-linear relationships
Support Vector Machines with RBF kernel  Neural Networks with dropout for regularization

2.Evaluation Metrics & Reporting
Multi-class Accuracy
Per-class Precision, Recall, F1-Score
Confusion Matrix
