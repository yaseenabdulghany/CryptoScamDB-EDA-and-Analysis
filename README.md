# **CryptoScamDB Dataset Analysis**  

This project contains an exploratory data analysis (EDA) of the **CryptoScamDB Dataset**, which focuses on fraudulent activities within the cryptocurrency space. The goal is to uncover trends, visualize data, and provide insights into common scams targeting cryptocurrency users.  

---

## **Dataset Description**  

The dataset includes verified scam URLs and metadata related to phishing, trust-trading scams, and social media impersonations. Each entry provides:  

- **Name**: The name or identifier of the scam.  
- **URL**: The web address associated with the scam.  
- **Category**: The primary type of scam (e.g., phishing, impersonation).  
- **Subcategory**: A more specific classification of the scam.  
- **Description**: A detailed explanation of the scam's operation.  
- **Addresses**: Cryptocurrency addresses tied to the scam.  
- **Reporter**: The source that flagged the scam.  

---

## **Repository Contents**  

- **`dataset/`**:  
  Contains the CryptoScamDB dataset file.  

- **`notebook/`**:  
  A Jupyter Notebook that performs EDA using Python libraries such as **pandas**, **Seaborn**, and **Matplotlib**.  

- **`visualizations/`**:  
  Saved visualizations created during the analysis.  

---

## **Features of the Analysis**  

The notebook explores:  
1. **Scam Category Distribution**:  
   Visualizes the count of scams by category to understand the most common scam types.  
2. **Subcategory Trends**:  
   Breaks down subcategories for deeper insights.  
3. **Word Cloud from Descriptions**:  
   Highlights common terms in scam descriptions.  
4. **Address Analysis**:  
   Analyzes the number of cryptocurrency addresses associated with scams.  
5. **Reporter Insights**:  
   Identifies sources actively flagging scams.  

