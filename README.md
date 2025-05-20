# 📈 Task 3 – Build A ChatBot for Customer Support

I made a Custom Chatbot for Customer Support using FAQ Data available in Kaggle for my Machine Learning Internship at **Future Interns**

---

## 📊 Dataset
- **Source**: [Stock Market Dataset](https://www.kaggle.com/datasets/waseemalastal/customer-support-ticket-dataset)

---

## 🎯 Objective
A Pretrained ChatBot that can resolve Customer Queries using available FAQ Data and generate help and relevent answers at real time for quick help.

---

## 🧠 What I Did

1. **Data Preprocessing**
   - Cleaned and visualized AMZN price trends
   - Added SMA20 and SMA50 moving averages

2. **Model Implementation**
   - Created lag features (previous 7 days of prices)
   - Trained a **Linear Regression** model
   - Predicted the next 7 days of stock prices

3. **Evaluation**
   - Metrics used:  
     - MAE: `44.92`  
     - RMSE: `47.48`  
     - MAPE: `2.33%`


---

## 📸 Visuals

### Closing Price  
![Close](Visualization/AMZN_Close_Price.png)

---

## 💡 Business Insight

- SMA crossovers help traders identify **entry and exit** points
- Short-term predictions assist in **portfolio timing**
- Combined ML + rule-based logic for real-world use