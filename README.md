# Context: 

Our client is an online retailer based in the UK. They sell 'all- occasion' gifts and many of their customers are wholesalers. Most of their customers are based in the UK, however, they do have a small percentage of customers from abroad. 

They would like to **segment these customers based on their previous purchase patterns**. Their goal is to provide more tailored services and enhance their marketing efforts towards international customers.

Currently, customers are grouped by **country of purchase** and this is not an optimal segmentation pattern because:

1) There are many countries, and hence, **many groups**

2) Some countries have a **negligible** number of customers in comparison to others 

3) 'Large' and 'Small' customers are treated the same way **regardless** of their purchase patterns 

The client would like us to help them by creating **3 clusters of customers** (a.k.a customer segments). To aid us in our task, we have past purchase data at the transaction level.


# Objective: 

Our task is to build a **clustering model** that factors in **aggregate sales patterns and specific items purchased by each customer**.

# Document Structure

There are **4 key steps** in the overarching Machine Learning framework that we will follow:

**Section 1** - Data Wrangling: This first step will involve us restructuring and manipulating our dataset in order to generate the features required for our clustering model

**Section 2** - Dimensionality Reduction: We will understand how to reduce the dimensionality of our dataset with multiple input features through feature elimination 

**Section 3** - Principal Component Analysis (PCA): We will explore how to reduce the dimensionality of our dataset with multiple input features through feature extraction  

**Section 4** - Cluster Analysis: We will develop clusters based on the analyses from the preceding section 
