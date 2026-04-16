<div align="center">
  
  # 💰 Anti-Money Laundering (AML) Analysis

  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
  [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
  [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
  [![XGBoost](https://img.shields.io/badge/XGBoost-AA0000?style=for-the-badge&logo=python&logoColor=white)](https://xgboost.readthedocs.io/)
  [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

  *A high-scale machine learning project focused on detecting suspicious financial transactions using advanced AML techniques.*
</div>

---

## 📖 Overview  
This project delivers a comprehensive analysis of the **SAML-D dataset**, focusing on strengthening **anti-money laundering (AML)** strategies through **EDA, preprocessing, and predictive modeling**.  

A high-performance **XGBoost Classifier** is implemented to identify suspicious financial behavior.

---

## 🔧 Features  
- 📊 **Exploratory Data Analysis (EDA):** Statistical insights, visualizations, anomaly detection  
- 🧹 **Data Preprocessing:** Feature engineering, encoding, normalization, skewness correction  
- 🤖 **Machine Learning Model:** XGBoost classifier for fraud detection  
- 📏 **Evaluation Metrics:** ROC-AUC, confusion matrix, TPR/FPR analysis  

---

## 📊 Dataset  
- **Name:** SAML-D (Synthetic Anti-Money Laundering Dataset)  
- **Size:** ~9.5 million transactions  
- **Features:**  
  - Transaction details  
  - Payment types  
  - Laundering indicators  
  - Sender/Receiver locations  

---

## 📂 Project Structure
```text
.
├── 📁 data/                # Dataset files
├── 📁 notebooks/           # EDA & model training notebooks
├── 📁 models/              # Saved models (optional)
├── requirements.txt       # Dependencies
└── README.md              # Documentation
```

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

<p align="center"> Built with ❤️ to combat financial fraud using Data Science. </p>
