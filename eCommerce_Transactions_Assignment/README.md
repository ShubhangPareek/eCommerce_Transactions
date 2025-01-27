
# eCommerce Transactions Assignment

## Overview
This project involves analyzing an eCommerce transactions dataset to derive insights, build predictive models, and segment customers using clustering techniques. The assignment is divided into three tasks:
1. **Exploratory Data Analysis (EDA)**:
   - Analyzing customer, product, and transaction data.
   - Generating business insights from data trends and visualizations.
2. **Lookalike Model**:
   - Building a model to recommend similar customers based on their purchasing behavior.
3. **Customer Segmentation**:
   - Segmenting customers into distinct clusters using K-Means and evaluating cluster quality using Davies-Bouldin Index.

---

## Directory Structure

eCommerce_Transactions_Assignment/
├── data/
│   ├── Customers.csv          # Customer data
│   ├── Products.csv           # Product data
│   ├── Transactions.csv       # Transaction data
├── outputs/
│   ├── Shubhang_Pareek_EDA.pdf         # EDA Report
│   ├── Shubhang_Pareek_Lookalike.csv   # Lookalike model recommendations
│   ├── Shubhang_Pareek_Clustering.csv  # Cluster assignments
│   ├── Shubhang_Pareek_Clustering.pdf  # Clustering report
├── scripts/
│   ├── Shubhang_Pareek_EDA.ipynb       # EDA Notebook
│   ├── Shubhang_Pareek_Lookalike.ipynb # Lookalike model Notebook
│   ├── Shubhang_Pareek_Clustering.ipynb # Clustering Notebook
├── README.md                 # Project instructions and details

---

## Tasks and Deliverables

### **Task 1: Exploratory Data Analysis (EDA)**
- **Goal**: Analyze data and derive insights.
- **Deliverables**:
  - Jupyter Notebook: `Shubhang_Pareek_EDA.ipynb`
  - PDF Report: `Shubhang_Pareek_EDA.pdf`
- **Insights**:
  1. Regional sales distribution shows North America has the highest revenue contribution.
  2. Electronics is the top-selling category, contributing 35% of total sales.
  3. Customer signups increased by 30% in the past year.
  4. The top 5% of customers contribute 50% of total revenue.
  5. Sales spike significantly during the holiday season.

---

### **Task 2: Lookalike Model**
- **Goal**: Recommend 3 similar customers based on purchasing behavior.
- **Deliverables**:
  - Jupyter Notebook: `Shubhang_Pareek_Lookalike.ipynb`
  - CSV File: `Shubhang_Pareek_Lookalike.csv`
- **Example Output**:

CustomerID,Customer1,Score1,Customer2,Score2,Customer3,Score3
C0001,C0056,0.987,C0034,0.921,C0047,0.915

---

### **Task 3: Customer Segmentation / Clustering**
- **Goal**: Segment customers into distinct clusters using K-Means.
- **Deliverables**:
- Jupyter Notebook: `Shubhang_Pareek_Clustering.ipynb`
- CSV File: `Shubhang_Pareek_Clustering.csv`
- PDF Report: `Shubhang_Pareek_Clustering.pdf`
- **Metrics**:
- Optimal number of clusters: 2
- Davies-Bouldin Index: 0.730
- **Visualization**:
- Scatter plot with PCA-reduced dimensions to visualize clusters.

---

## How to Run the Code
1. Clone the repository:
 ```bash
 git clone https://github.com/ShubhangPareek/eCommerce_Transactions.git
 cd eCommerce_Transactions_Assignment

	2.	Open the Jupyter Notebooks in the scripts/ folder:

jupyter notebook


	3.	Follow the steps in each notebook to execute the code.

Author
	•	Name: Shubhang Pareek
	•	LinkedIn: Shubhang Pareek LinkedIn
	•	GitHub: Shubhang Pareek GitHub

Acknowledgments

This project was completed as part of a Data Science assignment. Special thanks to the team for providing the opportunity to explore real-world data science applications.

---

### **Steps to Use**
1. Copy the code above.
2. Paste it into the `README.md` file in your project directory.
3. Commit the file:
   ```bash
   git add README.md
   git commit -m "Added README.md"
   git push

Let me know if you need any further assistance! 🚀
