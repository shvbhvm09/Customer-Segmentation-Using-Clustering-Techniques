# Customer Segmentation Using Clustering Techniques

This project demonstrates customer segmentation using clustering techniques, specifically K-Means, to identify distinct customer groups for targeted marketing. The segmentation is based on customer purchase behavior, analyzed using RFM (Recency, Frequency, and Monetary) analysis.

## Project Description

Customer segmentation is crucial for businesses to tailor marketing strategies and improve customer retention. In this project, we perform a detailed analysis of an online retail dataset containing over 500,000 transactions, leveraging clustering algorithms to group customers based on their purchasing habits.

### Objectives:
- **Segment customers** into different groups based on their purchasing behavior.
- **Optimize marketing strategies** by identifying key customer segments.
- **Visualize customer behavior** through data analysis and clustering.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Database**: SQL (for cleaning and processing transactional data)
- **Clustering Algorithm**: K-Means

## Data Description

The dataset used in this project is an online retail dataset, with the following key features:
- `InvoiceNo`: Unique identifier for each transaction
- `StockCode`: Unique identifier for each product
- `Description`: Product description
- `Quantity`: Number of items purchased
- `InvoiceDate`: Date and time of purchase
- `UnitPrice`: Price per item
- `CustomerID`: Unique identifier for customers
- `Country`: Customer's country of residence

## Steps Performed

1. **Data Preprocessing**: 
    - Cleaned and filtered data to ensure only valid customer transactions were used.
    - Replaced missing descriptions with "Unknown" and removed rows with missing `CustomerID`.
    
2. **Feature Engineering**: 
    - Performed RFM analysis (Recency, Frequency, Monetary Value) to create customer features.
    
3. **Clustering**: 
    - Applied K-Means clustering algorithm to segment customers into different groups based on their RFM scores.
    
4. **Visualization**: 
    - Created visualizations such as scatter plots, heatmaps, and customer segmentation charts to provide insights into the customer segments.
    - 
## **Data Source**:  
The dataset used for training and customer segmentation was downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail).

## Note:
See the .ipynb file to understand better.
