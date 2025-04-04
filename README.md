# Market Basket Analysis using Apriori and FP-Growth

This project implements **Market Basket Analysis** using the **Apriori** and **FP-Growth** algorithms.
 The goal is to identify frequent itemsets and generate association rules from a transactional dataset. 
 These insights can be used for applications such as product bundling, recommendation systems, and inventory optimization.


---

## 📂 Project Structure

- **`Apriori-FPGrowth for Market Basket Analysis.ipynb`**: Jupyter Notebook containing the implementation of Apriori and FP-Growth algorithms for Market Basket Analysis.
- **`Sales1998_normalized.csv`**: The transactional dataset used for analysis.
- 

---

## 📊 Dataset

The dataset (`Sales1998_normalized.csv`) contains transactional data in a normalized format. 
Each row represents a transaction, and each column represents an item.
 The dataset is loaded using `pandas` for preprocessing and analysis.

---

## 🚀 Features

1. **Frequent Itemset Mining**:
   - Uses the **FP-Growth** algorithm to identify frequent itemsets based on a minimum support threshold.

2. **Association Rule Generation**:
   - Generates association rules from the frequent itemsets using metrics such as:
     - **Support**
     - **Confidence**
     - **Lift**

3.

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YoHa2024NKU/Market-Basket-analysis-Apriori.git
   cd Market-Basket-analysis-Apriori
