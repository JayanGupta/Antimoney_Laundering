# Anti-Money Laundering (AML) Analysis 🚀

## Overview  
This project provides a comprehensive analysis of the **SAML-D dataset**, aimed at enhancing **anti-money laundering (AML) strategies**. It explores **exploratory data analysis (EDA), data preprocessing, and predictive modeling** using **XGBoost Classifier** to detect suspicious financial transactions.

## Features  
✔️ **Exploratory Data Analysis (EDA):** Statistical insights, data visualization, and anomaly detection.  
✔️ **Data Preprocessing:** Feature engineering, encoding, normalization, and skewness correction.  
✔️ **Machine Learning Model:** **XGBoost Classifier** trained for high-performance fraud detection.  
✔️ **Evaluation Metrics:** ROC-AUC, confusion matrix, and true positive rate (TPR) analysis.  

## Dataset  
- **Name:** SAML-D (Synthetic Anti-Money Laundering Dataset)  
- **Size:** ~9.5 million transactions  
- **Features:** Transaction details, payment types, laundering indicators, sender/receiver locations.  

## Installation  
Clone the repository and install the required dependencies:  
```bash
git clone https://github.com/your-username/AML-Detection.git
cd AML-Detection
pip install -r requirements.txt
```

## Usage  
1. **Load the dataset:**  
   ```python
   import pandas as pd
   df = pd.read_csv("SAML-D.csv")
   ```
2. **Run the Jupyter Notebook** for analysis and training:  
   ```bash
   jupyter notebook AML_Analysis.ipynb
   ```
3. **Train the XGBoost model:**  
   ```python
   from xgboost import XGBClassifier
   model = XGBClassifier()
   model.fit(X_train, y_train)
   ```

## Results  
✅ **Validation AUC:** 0.827  
✅ **Test AUC:** 0.812  
✅ **TPR (90% threshold):** 0.900  
✅ **FPR:** 0.580  

## Visualizations  
- **Transaction Distributions** 📊  
- **Fraud Patterns by Payment Type** 🔍  
- **Suspicious Transaction Heatmaps** 🔥  

## Contributing  
Contributions are welcome! Feel free to submit pull requests or report issues.  
