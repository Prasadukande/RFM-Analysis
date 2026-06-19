# 📊 RFM Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project performs **RFM (Recency, Frequency, Monetary) Analysis** on customer transaction data and applies **K-Means Clustering** to segment customers into meaningful groups. The objective is to identify high-value customers, understand customer behavior, and support data-driven marketing strategies.

Customer segmentation helps businesses improve customer retention, personalize marketing campaigns, and increase overall profitability.

---

## 🎯 Objectives

* Analyze customer purchasing behavior.
* Calculate RFM metrics:

  * **Recency** – How recently a customer made a purchase.
  * **Frequency** – How often a customer makes purchases.
  * **Monetary** – How much money a customer spends.
* Perform customer segmentation using K-Means Clustering.
* Visualize customer groups and business insights.

---

## 📂 Dataset

The project uses the **Online Retail Dataset**, which contains transaction records from an online retail store.

### Dataset Features

* Invoice Number
* Stock Code
* Product Description
* Quantity
* Invoice Date
* Unit Price
* Customer ID
* Country

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Plotly

---

## ⚙️ Project Workflow

### 1. Data Collection

* Load Online Retail dataset.
* Explore dataset structure and statistics.

### 2. Data Preprocessing

* Handle missing values.
* Remove negative quantities and prices.
* Filter invalid transactions.
* Convert date columns to datetime format.

### 3. Feature Engineering

Generate RFM metrics:

#### Recency

Number of days since the customer's last purchase.

#### Frequency

Total number of purchases made by a customer.

#### Monetary

Total amount spent by a customer.

### 4. Data Scaling

* Standardize RFM values using StandardScaler.

### 5. K-Means Clustering

* Determine optimal number of clusters.
* Train K-Means clustering model.
* Assign customers to segments.

### 6. Visualization

* Customer distribution analysis.
* Cluster visualization.
* RFM score comparison.
* Business insights extraction.

---

## 📊 Customer Segments

The clustering process identifies customer groups such as:

### ⭐ Champions

* Recent purchasers
* High purchase frequency
* High spending customers

### 💎 Loyal Customers

* Frequent buyers
* Consistent purchasing behavior

### 🛍️ Potential Customers

* Moderate purchase activity
* Opportunity for retention campaigns

### ⚠️ At-Risk Customers

* Haven't purchased recently
* Require re-engagement strategies

### ❌ Lost Customers

* Low activity
* Long time since last purchase

---

## 📈 Results

The project successfully:

* Segmented customers based on purchasing behavior.
* Identified high-value customer groups.
* Generated actionable marketing insights.
* Improved understanding of customer retention opportunities.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/rfm-analysis.git
```

Navigate to the project folder:

```bash
cd rfm-analysis
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy plotly
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
RFM_K_Means1.ipynb
```

---

## 📁 Project Structure

```text
RFM-Analysis/
│
├── RFM_K_Means1.ipynb
├── OnlineRetail.csv
├── README.md
│
├── images/
│   ├── recency_analysis.png
│   ├── frequency_analysis.png
│   ├── monetary_analysis.png
│   └── customer_segments.png
│
└── requirements.txt
```

---

## 📚 Key Concepts

### RFM Analysis

RFM is a marketing technique used to evaluate customer value.

| Metric    | Description                       |
| --------- | --------------------------------- |
| Recency   | How recently a customer purchased |
| Frequency | How often a customer purchases    |
| Monetary  | How much a customer spends        |

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that groups similar customers into clusters based on their purchasing behavior.

---

## 🎓 Learning Outcomes

Through this project, I gained experience in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Customer Segmentation
* Feature Engineering
* K-Means Clustering
* Data Visualization
* Business Analytics
* Machine Learning Applications

---

## 👨‍💻 Author

**Prasad Ukande**

MCA Graduate | Python Developer | Data Analytics Enthusiast

### Skills

* Python
* Machine Learning
* Data Analysis
* Pandas
* NumPy
* Scikit-Learn
* Data Visualization

---

## ⭐ Future Enhancements

* DBSCAN Clustering
* Hierarchical Clustering
* Interactive Dashboard using Streamlit
* Customer Churn Prediction
* Recommendation System

---

### If you found this project useful, please give it a ⭐ on GitHub.
