# Fraud-Detection-using-PySpark

Download the dataset from Kaggle. Here's the link - https://www.kaggle.com/datasets/ealaxi/paysim1

### **Project Overview:**  
This project focuses on detecting fraudulent transactions using **PySpark**, leveraging big data capabilities to process and analyze large-scale financial transaction data efficiently. The EDA uncovers transaction patterns, fraud trends, and key risk factors.

### **Key Steps & Methodology:**  
1. **Data Preprocessing & Exploration:**  
   - Processed and cleaned a large transaction dataset using **PySpark DataFrames** for efficient computation.  
   - Identified different transaction types (**Payment, Transfer, Cash-Out, Cash-In, Debit**) and their fraud occurrences.  

2. **Feature Analysis & Visualization:**  
   - Analyzed **fraud vs. non-fraud transaction amounts**, revealing fraudulent transactions had significantly **higher mean values (~$1.48M vs. ~$178K)**.  
   - Identified which **transaction types** had the highest fraud risk, with **Transfers and Cash-Outs** being the most fraud-prone.  
   - Examined **fraud frequency by day of the week and hour**, highlighting peak fraud activity trends.  

3. **Insights & Risk Factors:**  
   - **Fraudulent transactions occur at higher amounts** compared to non-fraudulent ones, indicating potential large-scale financial crimes.  
   - **Fraud patterns vary by transaction type**, with **Cash-Outs and Transfers being highly targeted** by fraudsters.  
   - **Fraudulent transactions spike on specific days and hours**, suggesting a need for time-based monitoring and fraud prevention mechanisms.  

### **Outcome & Key Insights:**  
✅ **Data-driven fraud detection** by identifying high-risk transaction types and time periods.  
✅ **Enhanced security measures** by focusing fraud prevention strategies on high-value transactions.  
✅ **Improved fraud monitoring** by understanding when and how fraud is most likely to occur.  
