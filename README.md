



# **MSCS 634 Project – Online Retail Data Analytics**

## **Project Overview**

This project focuses on analyzing an online retail dataset to extract meaningful insights using data analytics and machine learning techniques. The goal is to understand customer purchasing behavior, identify sales trends, and provide data-driven recommendations for business decision-making. The project demonstrates the application of preprocessing, exploratory data analysis (EDA), feature engineering, and multiple modeling techniques, including regression, classification, clustering, and association rule mining.



## **Dataset Description**

The dataset consists of transactional records from an online retail store. It includes the following key attributes:

* CustomerID
* InvoiceDate
* Quantity
* UnitPrice
* Country
* TotalPrice (derived)

Additional features were engineered to enhance analysis:

* **Recency** – Time since last purchase
* **Frequency** – Number of transactions
* **Monetary Value** – Total spending
* **Average Basket Value**
* **Total Items Purchased**

The dataset is dominated by transactions from the United Kingdom, making it useful for geographic and customer segmentation analysis.


## **Project Workflow**

### **1. Data Preprocessing**

* Handled missing values (especially CustomerID)
* Removed duplicate and inconsistent records
* Treated outliers in UnitPrice
* Cleaned and structured the dataset

### **2. Exploratory Data Analysis (EDA)**

* Analyzed monthly sales trends
* Identified top-performing products
* Examined geographic distribution of sales
* Evaluated price distribution
* Conducted correlation analysis

### **3. Feature Engineering**

* Created RFM (Recency, Frequency, Monetary) features
* Generated customer behavior metrics
* Prepared dataset for modeling

### **4. Modeling Techniques**

* **Regression:** Predicted customer spending behavior
* **Classification:** Identified high-value vs. low-value customers
* **Clustering (K-Means):** Segmented customers into groups
* **Association Rule Mining:** Discovered product relationships



## **Key Findings**

* A small percentage of customers contribute most of the revenue
* Sales show seasonal trends with higher activity in later months
* Product demand is concentrated among a few top-selling items
* Strong correlation exists between purchase frequency and spending
* The UK dominates sales, indicating geographic dependency



## **Recommendations**

* Implement customer segmentation for targeted marketing
* Focus on retaining high-value customers through loyalty programs
* Optimize inventory by prioritizing top-selling products
* Use association rules for cross-selling strategies
* Expand into new geographic markets
* Apply dynamic pricing based on demand patterns



## **Ethical Considerations**

* Ensured no personally identifiable information (PII) was used
* Acknowledged potential dataset bias (UK dominance)
* Maintained transparency in data processing and modeling
* Emphasized responsible use of data insights

## **Repository Structure**

```
MSCS_634_Project/

```


## **Tools and Technologies**

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* Jupyter Notebook
* Machine Learning Algorithms (Regression, K-Means, Classification)
* Association Rule Mining (Apriori / FP-Growth)


## **How to Run the Project**

1. Clone this repository:

   ```
   git clone https://github.com/your-username/MSCS_634_Project.git
   ```
2. Open the Jupyter Notebook:

   ```
   Deliverable4_Full_Version_Online_Retail.ipynb
   ```
3. Run all cells to reproduce the analysis and results.


## **Future Improvements**

* Apply advanced machine learning models (e.g., XGBoost, Neural Networks)
* Implement real-time analytics
* Build a recommendation system
* Expand dataset to include more diverse geographic regions



## **References**

Chen, H., Chiang, R. H. L., & Storey, V. C. (2022). Business intelligence and analytics: From big data to big impact. *MIS Quarterly, 46*(2), 1165–1188.

Han, J., Pei, J., & Kamber, M. (2022). *Data mining: Concepts and techniques* (4th ed.). Morgan Kaufmann.

Provost, F., & Fawcett, T. (2023). *Data science for business* (2nd ed.). O’Reilly Media.

Shmueli, G., Bruce, P. C., Yahav, I., Patel, N. R., & Lichtendahl, K. C. (2022). *Data mining for business analytics* (3rd ed.). Wiley.

Witten, I. H., Frank, E., Hall, M. A., & Pal, C. J. (2023). *Data mining: Practical machine learning tools and techniques* (5th ed.). Morgan Kaufmann.


