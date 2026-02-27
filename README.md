# RSRP-Cellular-Networks
RSRP Cellular Network Signal Strength PredictionMachine learning and deep learning models for predicting Reference Signal Received Power (RSRP) from a private telecom dataset, built during an internship at the University of Glasgow, James Watt School of Engineering.
Results:
* 98% reduction in RMSE (73.74 → 1.31) through iterative feature selection, L1/L2 regularization, and hyperparameter tuning
* 94.2% classification accuracy on a 4-class DNN signal strength classifier validated via confusion matrix

Models Built
* Linear Regression (baseline, polynomial features, and revised with regularization)
* Dense Neural Network (DNN) classifier with funnel architecture (64→32 neurons)
* Experimental comparisons: ReLU vs Leaky ReLU activation, Standard vs Robust scaling

Tech Stack
Python, TensorFlow/Keras, scikit-learn, Pandas, NumPy, Matplotlib, SeabornReport
Full technical report available in the repository: RSRP_Regression_Model_Report.pdf

## 📊 Report
Full technical report available in the repository: RSRP_Regression_Model_Report.pdf
[Click here to view the full report](RSRP_Regression_Model_Report.pdf)

