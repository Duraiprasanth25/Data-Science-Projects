# Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, with fraud cases accounting for only **0.172%** of all transactions. To tackle this challenge, **undersampling** was applied to balance the data, and multiple models were evaluated.

## 📂 Dataset
- The dataset contains **284,807 transactions** with **492 fraud cases**.
- Features include **V1 to V28** (PCA-transformed), **Time**, **Amount**, and **Class** (0 = legitimate, 1 = fraud).
- Due to confidentiality, original feature descriptions are not available.

## 🚀 Approach
1. **Data Preprocessing**
   - Handled missing values and checked for inconsistencies.
   - Standardized the **Amount** feature.
   - Applied **undersampling** to address class imbalance.
2. **Model Training**
   - Implemented and evaluated the following models:
     - **Logistic Regression**
     - **Random Forest**
     - **ADA Boost**
   - Tuned hyperparameters for optimal performance.
3. **Performance Evaluation**
   - Given the class imbalance, used **AUPRC (0.80)** as the primary metric.
   - Achieved **0.68 recall** and **64% precision**, ensuring effective fraud detection.

## 📊 Results
| Metric          | Score  |
|----------------|--------|
| AUPRC          | 0.80   |
| Recall         | 0.68   |
| Precision      | 64%    |

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn)
- **Machine Learning Models** (Logistic Regression, Random Forest, ADA Boost)
- **Jupyter Notebook** for experimentation

## 📌 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook
   ```

## 📜 License
This project is open-source and available under the **MIT License**.

## 🤝 Contributing
Feel free to submit issues or pull requests to improve the project!

