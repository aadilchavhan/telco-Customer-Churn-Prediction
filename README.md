# **Customer Churn Prediction Using Neural Networks**
![Project Status](https://img.shields.io/badge/status-Active-brightgreen) ![Python Version](https://img.shields.io/badge/python-12.7%2B-blue) ![License](https://img.shields.io/badge/license-MIT-lightgrey)

## **Overview**
This project aims to predict customer churn for a telecom company using historical usage patterns. We first implement a **Single-Layer Perceptron (SLP)** to classify customers and identify its limitations. To enhance prediction accuracy, we upgrade to a **Multi-Layer Perceptron (MLP)**. The model can help businesses retain customers by identifying high-risk churn profiles.

## **Features**
- **Machine Learning Models:** SLP & MLP
- **Data Processing:** Handling missing values, scaling features, encoding categorical variables
- **Model Training:** Stochastic Gradient Descent (SGD), Adam optimizer, accuracy tracking
- **Evaluation Metrics:** Precision, Recall, F1-score, AUC-ROC
- **Visualization:** Confusion matrix, loss curves, accuracy plots

## **Installation & Setup**
```bash
git clone https://github.com/your-repo/customer-churn.git
cd customer-churn
pip install -r requirements.txt
```
Ensure Python 3.8+ and relevant libraries such as TensorFlow/PyTorch are installed.

## **Dataset Information**
- **Source:** [Telecom Customer Churn Dataset](https://www.kaggle.com/datasets) (or proprietary dataset)
- **Format:** CSV with columns: `customer_id`, `usage_minutes`, `data_gb`, `billing_amount`, `contract_type`, etc.
- **Preprocessing:** Normalization, categorical encoding, feature engineering

## **Model Architecture**
| Layer | Description |
|-------|------------|
| Input | Customer features (usage patterns, contract details, billing history) |
| Hidden | Multiple layers with ReLU activation |
| Output | Binary classification (1: churn, 0: retain) |

## **Training & Evaluation**
Run training with:
```bash
python train.py --model mlp --epochs 50 --optimizer adam
```
Validation accuracy and loss metrics are tracked per epoch.

## **Performance Comparison**
| Model | Optimizer | Accuracy | F1-score |
|-------|-----------|---------|---------|
| SLP   | SGD      | 72%     | 0.65    |
| MLP   | Adam     | 85%     | 0.78    |

## **Visualization & Results**
Confusion matrices, accuracy curves, and insights are saved in the `/results` folder.

## **Contributing**
Feel free to contribute! Follow these steps:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with detailed updates

## **License**
This project is licensed under the **MIT License**.

## **Connect with Me**
[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/aadilchavhan)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://linkedin.com/in/aadilchavhan)  

---

This README provides clear guidance and professional documentation while incorporating helpful badges and structured tables. Let me know if you'd like to customize it further! 🚀
