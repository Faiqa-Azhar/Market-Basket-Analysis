# 🛒 Market Basket Analysis using Apriori Algorithm

## 📌 Project Overview

This project performs **Market Basket Analysis (MBA)** using the **Apriori Algorithm** to discover hidden purchasing patterns and associations between products. The analysis helps identify which items are frequently bought together by customers.

The project uses transactional shopping data and applies **Association Rule Mining** to generate meaningful product recommendations based on customer buying behavior.


## 🎯 Project Objectives

- Analyze customer purchase transactions
- Identify frequently purchased item combinations
- Generate association rules between products
- Measure rule strength using Support, Confidence, and Lift
- Visualize purchasing patterns through graphs


## 🗂 Dataset Information

The dataset contains transactional purchase records with the following structure:

| Column Name | Description |
|-------------|-------------|
| Transaction_ID | Unique transaction identifier |
| Item | Purchased item/product |

Example:

| Transaction_ID | Item |
|----------------|------|
| 1 | Bread |
| 1 | Milk |
| 2 | Butter |


## ⚙️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Mlxtend**
- **Google Colab**


## 🔄 Project Workflow

The following steps were performed in this project:

### 1. Data Loading
- Imported transaction dataset
- Checked dataset structure and information

### 2. Data Cleaning & Preprocessing
- Checked missing values
- Removed duplicate records
- Cleaned item names
- Removed unwanted characters and noise

### 3. One-Hot Encoding
Transactional data was converted into binary format (**0 and 1**) where:
- **1 = Item Purchased**
- **0 = Item Not Purchased**

This step was necessary because the **Apriori Algorithm requires binary transactional data**.

### 4. Frequent Itemset Generation
The **Apriori Algorithm** was applied to identify frequent product combinations based on minimum support.

### 5. Association Rule Mining
Association rules were generated using:

- **Support**
- **Confidence**
- **Lift**

### 6. Data Visualization
Graphs were used to better understand customer purchasing patterns:
- Top Selling Items
- Support vs Confidence
- Support vs Lift
- Association Rule Heatmap


## 📊 Evaluation Metrics

### Support
Measures how frequently items appear together in transactions.

### Confidence
Measures the probability of purchasing one product after another product is purchased.

### Lift
Measures the strength of association between products.

- **Lift > 1** → Positive relationship
- **Lift = 1** → No relationship
- **Lift < 1** → Negative relationship


## 📈 Project Results

### Generated Results

- **Total Rules Generated:** 14,141
- **Strong Rules Generated:** 1,881
- **Average Support:** 3.26%
- **Average Confidence:** 55.13%
- **Average Lift:** 1.35

These results indicate meaningful product associations and successful implementation of the **Apriori Algorithm**.


## 🚀 Applications of Market Basket Analysis

Market Basket Analysis is widely used in:

- Product Recommendation Systems
- Supermarket Layout Optimization
- Cross-Selling Strategies
- Combo Offers
- Customer Purchase Analysis
- E-Commerce Recommendations

Examples:
- Amazon
- Walmart
- Netflix


## ▶️ How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/your-username/market-basket-analysis.git
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Notebook

Open Jupyter Notebook and run:

```text
Market_Basket_Analysis.ipynb
```


## ✅ Conclusion

The **Apriori Algorithm** was successfully implemented to analyze customer purchasing behavior and discover meaningful relationships between products. The generated association rules can be useful for recommendation systems, marketing strategies, and business decision-making.


## 👨‍💻 Author

**Faiqa Azhar**  
AI & Data Science Student  
