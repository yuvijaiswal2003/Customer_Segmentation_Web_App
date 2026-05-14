# Customer Segmentation using K-Means Clustering

## Project Overview
This project performs customer segmentation using Machine Learning techniques such as **K-Means Clustering** and **PCA (Principal Component Analysis)** to identify meaningful customer groups based on purchasing behavior and demographic patterns.

An interactive **Streamlit web application** was developed and deployed to visualize customer segments and predict the segment for new customer inputs.

---

## Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature scaling using StandardScaler
- Dimensionality reduction using PCA
- Customer segmentation using K-Means Clustering
- Optimal cluster selection using:
  - Elbow Method
  - Silhouette Score
- Interactive Streamlit dashboard
- Cluster prediction for new customer data
- Data visualization and business insights

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit

---

## Project Structure

```text
customer-segmentation/
│
├── app.py
├── requirements.txt
├── README.md
├── kmeans_model.pkl
├── scaler.pkl
│
├── data/
│   └── customer_segmentation.csv
│
└── notebooks/
    └── analysis_model.ipynb
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yuvijaiswal2003/Customer_Segmentation_Web_App
```

Move into project directory:

```bash
cd customer-segmentation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Streamlit app:

```bash
streamlit run app.py
```

---

## Machine Learning Workflow
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Scaling
4. PCA for dimensionality reduction
5. K-Means clustering
6. Cluster evaluation using:
   - WCSS (Elbow Method)
   - Silhouette Score
7. Cluster visualization and interpretation
8. Deployment using Streamlit

---

## Cluster Labels
- Moderate Customers
- Inactive Customers
- Low-Spending Customers
- Active High Spenders
- Premium Customers
- Loyal Customers
- Senior Customers

---

## Deployment
The project is deployed using **Streamlit Community Cloud**.

---

## Author
Yuvraj
