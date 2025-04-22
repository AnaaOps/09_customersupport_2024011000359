# 09_customersupport_2024011000359
# Customer Support Case Classification

This project focuses on classifying customer support cases into different categories such as *Billing*, *Technical Issue*, etc., using machine learning. The goal is to automate the ticket routing process to enhance customer service efficiency.

## 📁 Dataset

The dataset includes the following features:
- `message_length`: Length of the customer's message
- `response_time`: Time taken to respond to the customer
- `case_type`: Target variable indicating the category of support (e.g., Billing, Technical Issue)

## 🧰 Technologies Used

- Python 🐍
- pandas
- scikit-learn
- matplotlib
- seaborn

## 📊 Problem Statement

Predict the type of customer support case using attributes like message length and response time. This helps in routing tickets to the correct department automatically.

## 🎯 Objectives

- Preprocess the data and encode categorical variables
- Train a Logistic Regression model for classification
- Evaluate model performance using standard metrics
- Visualize the results with a confusion matrix

## 🔍 Methodology

1. **Data Preprocessing**
   - Label encoding of `case_type`
   - Selection of numerical features (`message_length`, `response_time`)
   
2. **Model Building**
   - Data split using `train_test_split`
   - Model trained using `LogisticRegression`

3. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion matrix visualization

## ✅ Results

- The Logistic Regression model performed well on the test dataset.
- The confusion matrix revealed class-level performance.
- The model shows promise for automating support ticket categorization.

## 🧪 How to Run

1. Clone the repo or download the `.ipynb` file.
2. Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn
