# SmartCart Customer Segmentation using Clustering

## 📌 Project Overview

SmartCart is a growing e-commerce platform serving customers across multiple countries.
The company currently uses generic marketing strategies for all customers, which leads to:

* Inefficient marketing campaigns
* Missed high-value customer retention opportunities
* Difficulty identifying churn-prone users

This project builds an **Intelligent Customer Segmentation System** using **Unsupervised Machine Learning (Clustering)** to discover hidden behavioral patterns and enable data-driven marketing decisions.

---

## 🎯 Objective

The goal of this project is to group customers into meaningful clusters based on:

* Purchasing behaviour
* Engagement levels
* Spending patterns
* Loyalty indicators

These segments help SmartCart perform personalized marketing and improve customer retention.

---

## 📊 Dataset Description

The dataset contains **2240 customer records** and **22 features**.

### 1️⃣ Customer Demographics

* ID — Customer identifier
* Year_Birth — Year of birth
* Education — Education level
* Marital_Status — Marital status
* Income — Household income
* Kidhome — Number of children
* Teenhome — Number of teenagers
* Dt_Customer — Enrollment date

### 2️⃣ Purchase Behaviour (Amount Spent)

* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds

### 3️⃣ Purchase Behaviour (Frequency)

* NumDealsPurchases
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth

### 4️⃣ Customer Feedback

* Recency — Days since last purchase
* Complain — Complaint indicator

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## 🤖 Machine Learning Approach

This project uses **clustering algorithms** to segment customers:

* Data Cleaning & Preprocessing
* Feature Engineering
* Scaling
* KMeans Clustering
* Elbow Method (optimal clusters)
* Cluster Analysis & Interpretation

---

## 📈 Project Workflow

1. Data understanding
2. Data preprocessing
3. Exploratory Data Analysis
4. Feature scaling
5. Model building (Clustering)
6. Cluster visualization
7. Business insights

---

## 💡 Business Impact

The segmentation system helps SmartCart:

* Identify high-value customers
* Detect churn-risk users
* Enable personalized marketing
* Improve campaign ROI
* Support data-driven decision making

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/SmartCart-Customer-Clustering-ML.git
cd SmartCart-Customer-Clustering-ML
pip install -r requirements.txt
python main.py
```

---

## 📂 Project Structure

```
├── data/
├── notebooks/
├── src/
├── main.py
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

* Try DBSCAN / Hierarchical clustering
* Build dashboard (Streamlit / Power BI)
* Deploy segmentation API
* Real-time segmentation
* Recommendation engine integration

---

## 👩‍💻 Author

Shaik Kareena
AI / ML Engineer (Aspiring)
