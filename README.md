# Sms_Spam_classifier
# 📱 SMS Spam Detection

This project classifies SMS messages as **Spam** or **Ham** (not spam) using machine learning. The notebook covers data processing, model training, and evaluation.

## 🔍 Key Steps

- **Data Loading and Preprocessing**: 
  - Cleaned and prepared the data for model training.
  
- **Text Vectorization**:
  - Converted SMS text into numerical features using **TF-IDF**.

- **Model Training**:
  - Trained and evaluated models, including **Logistic Regression** and **Naive Bayes**.

- **Evaluation**:
  - Assessed model performance with metrics like **accuracy** and **precision**.

## 📊 Visualizations

- **Spam vs. Ham Distribution**: Visualized the class balance.
- **Confusion Matrix**: Displayed the performance of both models on test data.

## 📈 Results

| Model                 | Accuracy | Precision |
|-----------------------|----------|-----------|
| Naive Bayes           | 0.95     | 1.00      |
| Logistic Regression   | 0.95     | 0.94      |

The **Naive Bayes** model achieved the highest precision, making it very effective for spam classification, while **Logistic Regression** also provided robust accuracy.

--- 

