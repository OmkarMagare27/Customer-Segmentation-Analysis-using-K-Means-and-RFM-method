# Customer-segmentation

### The customer segmentation based on RFM method and K-Means clustering

## General info
This project explores two methods of customer segmentation by combining the RFM (Recency, Frequency, Monetary Value) method with K-Means clustering. The dataset consists of sample sales data collected from retail transactions over a three-year period. Two distinct approaches are utilized to gain deeper insights into customer behavior::
- **First approach** RFM scoring is computed, and K-means clustering is applied to the assigned RFM scores.;
- **Second approach** K-means clustering is applied directly to the raw RFM variables (Recency, Frequency, Monetary).

### Dataset
The dataset used in this project is based on retail analytics, comprising three years of sales transactions. It can be found on Kaggle here. This dataset provides valuable insights into customer purchasing behavior, offering a foundation for segmentation analysis. [here](https://www.kaggle.com/kyanyoga/sample-sales-data).

## Motivation
Customer segmentation is an essential technique in understanding consumer behavior and tailoring marketing strategies to meet the diverse needs of different customer groups. Companies that store sales and transaction data can leverage this information for customer segmentation, which can then be used to develop targeted marketing campaigns aimed at increasing customer retention and sales. 

**RFM** RFM Analysis is a widely-used technique that segments customers based on their purchasing patterns. The RFM model assesses customer behavior across three dimensions:
- Recency: How recently a customer made a purchase (measured by days since the last transaction);
- Frequency: How often a customer makes purchases (the total number of transactions);
- Monetary Value: How much a customer spends on purchases (the total monetary value of transactions).
By analyzing these three factors, businesses can group customers into segments that are most likely to respond to marketing campaigns and promotions. RFM analysis allows businesses to create highly personalized marketing offers and better manage customer relationships.

## Project contains:
- First approach - **Customer segmentation based on RFM scores – Customer_segmentation.ipynb**
- Second approach - **Customer segmentation based on raw RFM values – Segmentation_Kmeans.ipynb**
- Python script with customer segmentation - **Code for performing customer segmentation and exporting results – customers_segments.py**

## Additional Insights
- K-Means clustering complements the RFM method by further refining customer segments through data-driven algorithms. While RFM scoring provides a structured framework for categorizing customers, K-Means clustering adds the ability to discover patterns and relationships within these categories that might not be evident through RFM alone. Using both methods together allows for more granular segmentation and a deeper understanding of the customer base.

- The second approach, where clustering is applied directly to the raw RFM values, provides flexibility in identifying patterns that may not align with traditional RFM score cut-offs. This method helps identify clusters that represent distinct purchasing behaviors, offering further refinement of marketing strategies.

## Technologies

This project was built using the following technologies:

- Python 3.6
- libraries:
- pandas for data manipulation and analysis
- numpy for numerical computations
- sklearn for machine learning (K-Means)
- scipy for scientific computing
- seaborn and matplotlib for data visualization

**Running the project:**

To run this project, use Jupyter Notebook or Google Colab to execute the .ipynb files, or run the script using any Python environment..
