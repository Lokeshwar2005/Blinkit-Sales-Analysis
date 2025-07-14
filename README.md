# The Blinkit Sales and Customer Feedback Analysis

📊 **Machine Learning Project | CSM355**  
📅 **Submitted on:** April 16, 2025  
👨‍🎓 **Student:** Sudam Lokeshwar  
🎓 **University:** Lovely Professional University  
🔗 [Project Repository](https://github.com/Lokeshwar2005/Blinkit-Sales-Analysis)

---

## 📌 Project Overview

**Blinkit**, a leading Indian online grocery platform, operates under fast-paced delivery models. This project dives deep into analyzing Blinkit’s operational datasets using **machine learning** techniques to optimize:

- 📦 **Delivery performance**
- 💬 **Customer feedback sentiment**
- 🛒 **Sales performance**

A total of **13 datasets** were used, covering customer orders, product details, inventory, delivery performance, and feedback data.

---

## 🎯 Objectives

- **Predict** whether orders will be delivered on time or delayed.
- **Analyze** customer satisfaction using sentiment classification.
- **Understand** product sales performance for inventory optimization.
- **Build** machine learning models for delivery time, customer behavior, and feedback prediction.

---

## 🧠 Methodology

### 🔍 Data Preprocessing

- Missing values imputed (mean/median/mode)
- Categorical features encoded (Label Encoding, One-Hot)
- Extracted features from timestamps (hour, weekday)
- Outlier detection using IQR/Z-score

### 🤖 Machine Learning Models

| Task                          | Model Used               |
|-------------------------------|---------------------------|
| Delivery Prediction           | Logistic Regression       |
| Feedback Sentiment Analysis   | Random Forest Classifier  |
| Payment Method Classification | K-Nearest Neighbors (KNN) |
| Delivery Time Prediction      | Random Forest Regressor   |
| Feedback Sentiment (Alt)      | Naive Bayes               |


---

## 📈 Model Performance

### ✅ **Classification Models**

| Model                    | Accuracy | Precision | Recall | F1-Score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression      | 81.2%    | 79.5%     | 84.3%  | 81.9%    |
| Random Forest Classifier | 87.6%    | 86.5%     | 89.1%  | 87.8%    |
| KNN Classifier           | 75.4%    | 72.8%     | 78.5%  | 75.3%    |

### 📉 **Regression Model**

- **Random Forest Regressor (Delivery Time):**
  - RMSE: `14.5 minutes`

---

## 📊 Key Insights

- **50.8%** of orders are delivered within 10–20 minutes; only **8.6%** within 10 minutes.
- **Dairy & Breakfast** category generates the highest product amount.
- **Tier 2 cities** outperform in average sales.
- **High-value customers** should be prioritized for loyalty strategies.
- **Customer Service & Late Delivery** are major sources of negative feedback.

---

## 🔧 Future Improvements

- Integrate **real-time data** like traffic/weather for delivery prediction.
- Use **deep NLP models (e.g., BERT)** for nuanced sentiment analysis.
- Address class imbalance using **SMOTE**.
- Include **external sales trends** for forecasting.
- Employ **Bayesian Optimization** for hyperparameter tuning.

---

## 📊 Screenshots of Analysis

<img width="547" height="741" alt="Screenshot 2025-07-14 at 9 37 40 AM" src="https://github.com/user-attachments/assets/738ea172-e4b9-426c-a9c8-caf415b21599" />
<img width="534" height="738" alt="Screenshot 2025-07-14 at 9 37 59 AM" src="https://github.com/user-attachments/assets/7f39712a-deda-4271-a001-dd62706d1793" />
<img width="545" height="725" alt="Screenshot 2025-07-14 at 9 38 18 AM" src="https://github.com/user-attachments/assets/c8f5de08-04e8-45c7-a803-34f14fe98c7b" />
<img width="548" height="749" alt="Screenshot 2025-07-14 at 9 38 30 AM" src="https://github.com/user-attachments/assets/730dfc04-bc8e-43d2-af53-45a99f93060c" />
<img width="530" height="730" alt="Screenshot 2025-07-14 at 9 38 43 AM" src="https://github.com/user-attachments/assets/ed808186-4b52-48dd-8dce-c87f6e8614e9" />
<img width="528" height="716" alt="Screenshot 2025-07-14 at 9 38 52 AM" src="https://github.com/user-attachments/assets/a7fc8af2-c17f-4a7b-bf58-ef1bbf33d7f6" />
<img width="554" height="742" alt="Screenshot 2025-07-14 at 9 39 00 AM" src="https://github.com/user-attachments/assets/fae22383-fb18-4a33-a8f9-86afecb3ccfe" />
<img width="545" height="729" alt="Screenshot 2025-07-14 at 9 39 12 AM" src="https://github.com/user-attachments/assets/54ed804a-9a7e-4a82-bd83-231b72c0dc33" />
<img width="544" height="748" alt="Screenshot 2025-07-14 at 9 40 10 AM" src="https://github.com/user-attachments/assets/f3c07ac1-2ac6-4656-9d43-e3fab9ab11c5" />

---


## 📂 Dataset Highlights

- 📦 Orders: order_total, delivery_time, payment_method
- 👥 Customers: profiles, segments, order history
- 💬 Feedback: ratings, review text, sentiment
- 🚚 Deliveries: partner ID, delay status, delivery time
- 🛍️ Products: price, stock level, shelf life

---

## 📧 Contact

- 📬 **Email:** lokeshwarsudam@gmail.com  
- 💻 **GitHub:** [Lokeshwar2005](https://github.com/Lokeshwar2005)

---

## 📜 License

This project is for academic use under the guidelines of Lovely Professional University.


