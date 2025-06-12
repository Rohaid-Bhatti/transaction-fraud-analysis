# Credit Card Fraud Detection - EDA & Anomaly Detection

This project explores a dataset of credit card transactions to identify fraudulent activities using exploratory data analysis (EDA) and basic anomaly detection techniques. The analysis includes visualization, outlier detection using IQR and Z-score, and feature-based anomaly tagging.

## 📁 Dataset

- **Source**: `kaggle/card_transdata`
- **Size**: ~1 million transactions
- **Target Variable**: `fraud` (1 = fraud, 0 = non-fraud)

## 🔍 Objectives

- Understand the distribution of fraud vs non-fraud transactions.
- Explore key features such as:
  - `distance_from_home`
  - `distance_from_last_transaction`
  - `ratio_to_median_purchase_price`
- Apply statistical methods to detect outliers:
  - Interquartile Range (IQR)
  - Z-score

## 📊 Techniques Used

- **Data Cleaning**: Missing value checks
- **Visualization**: Scatter plots, box plots, distribution analysis
- **Anomaly Detection**:
  - IQR method
  - Z-score thresholding
- **EDA**: Trend identification and feature-wise behavior analysis

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scipy.stats`

## 📌 Key Findings

- Fraud cases account for a small percentage (~X%) of the total transactions.
- Significant anomalies observed in features like:
  - Distance metrics (`distance_from_home`, `distance_from_last_transaction`)
  - Purchase price behavior

## 📂 Project Structure

├── TransactionFraud.ipynb # Jupyter notebook with full analysis
├── card_transdata.csv # Dataset (not included in repo)
└── README.md # Project overview

yaml
Copy
Edit

> ⚠️ Note: The dataset is not included due to size or privacy constraints. Please download it separately if needed.

## 🚀 Future Improvements

- Apply machine learning models (e.g., Logistic Regression, Random Forest) for fraud classification
- Time-based analysis of fraud patterns
- Feature engineering for improved detection

---

## 📬 Contact

For questions or suggestions, feel free to reach out via GitHub issues or pull requests.
