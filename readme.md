# 📊 Telecom Customer Churn Prediction

### 🧾 Project Reference: PM-PR-0017

---

## 🏢 Business Case

**No-Churn Telecom** is an established telecom operator in Europe with more than a decade in business.  
Due to increased competition in the telecom industry, retaining customers has become a major challenge.  
Despite initiatives such as reducing tariffs and offering special deals, the company continues to face customer churn.

---

## 🎯 Objective

To identify key factors influencing customer churn and build a **predictive model** that helps the company  
proactively retain customers who are likely to leave.

---

## 🔍 Domain Analysis

The dataset consists of **21 columns** and **4617 rows**.  

**Key attributes include:**
- **State:** Customer’s geographical region.  
- **Account Length:** Number of days the customer has been associated with the company.  
- **Area Code:** Represents the customer’s regional code.  
- **Phone:** Customer’s phone number (identifier).  
- **International Plan / Voice Mail Plan:** Subscription details.  
- **Call Durations (Day, Evening, Night, International):** Usage metrics.  
- **Customer Service Calls:** Number of service calls made.  
- **Churn:** Target variable indicating whether the customer left.

---

## 🧠 Project Workflow

1. **Database Connection** – Connected to a MySQL server to retrieve the dataset.  
2. **Data Loading & Exploration** – Examined structure, data types, and null values.  
3. **Data Cleaning** – Processed categorical and numerical columns, handled missing data.  
4. **Feature Engineering** – Encoded categorical variables and scaled features.  
5. **Model Building** – Applied ML algorithms to predict churn.  
6. **Model Evaluation** – Evaluated performance using accuracy, precision, recall, and F1-score.

---

## ⚙️ Technologies Used

- **Python**  
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **Scikit-learn**  
- **MySQL Connector**  
- **Jupyter Notebook**

---

## 🚀 How to Run

1. Clone or download the project notebook.  
2. Install required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn mysql-connector-python
