# Fraud_Detection

![4](https://github.com/user-attachments/assets/66ca1ee8-3d6e-4555-8919-421312939b51)

### Tools used🛠: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

## 🎯 Objective
The goal is to build a machine learning model to detect fraudulent transactions based on various payment-related features. The model classifies each transaction as either Fraudulent (1) or Legitimate (0), helping businesses identify suspicious activities in real time.

## 💡 Why We Use It
Fraud detection is critical for the e-commerce, banking, and fintech industries to minimize financial losses and protect customers. It is used in:

-Online payment security systems
-Credit card transaction monitoring
-E-commerce fraud prevention
-Banking and insurance claim verification

By analyzing patterns like payment methods, transaction amounts, and customer behavior, the model can spot anomalies that indicate potential fraud.

# ✅ Step-by-step Approach
## 📥 Data Loading & Setup
-Imported essential libraries: NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn.
-Loaded the dataset payment_fraud.csv and checked for missing values.

## 🔍 Exploratory Data Analysis (EDA)
-Visualized the distribution of payment methods using sns.barplot.
-Checked the class distribution of label (fraud vs. legitimate transactions).
-Created a correlation heatmap to identify relationships between features.

### Key Insights from EDA:
-Some payment methods were more prone to fraudulent activities.
-Certain numerical features had a strong correlation with the fraud label.

## 🧠 Feature Engineering
-Label Encoding was applied to convert the categorical column paymentMethod into numeric values.
-Feature Scaling was done using StandardScaler to normalize the dataset for better model performance.

## 📊 Model Training
-Split the dataset into training (75%) and testing (25%) sets using train_test_split.
-Used Logistic Regression as the classification model to predict fraudulent transactions.

## 🧪 Model Testing & Evaluation
-Generated predictions using the test set.
-Evaluated the model using Accuracy Score, Classification Report, and Confusion Matrix.

## Output
<img width="1140" height="60" alt="1" src="https://github.com/user-attachments/assets/612b38d4-02ea-4196-a66e-c0b97447010a" />

<img width="623" height="233" alt="2" src="https://github.com/user-attachments/assets/c3773bb6-4051-42fd-910a-374061b45632" />

## -------------------------------------------------Confustion Metrics----------------------------------------------------

<img width="779" height="811" alt="3" src="https://github.com/user-attachments/assets/479e93a5-aeab-4dc9-b6ae-41de7f527389" />
