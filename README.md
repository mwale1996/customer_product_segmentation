# customer_product_segmentation
Using Market Basket Analysis and simple KMeans Clustering to group products and customers.

The notebook is split into three sections.

The first section loads the Online Retail data from Kaggle (https://www.kaggle.com/datasets/vijayuv/onlineretail). Then I perform exploratory data analysis (EDA) to extract some preliminary insights which should affect the direction of ongoing analysis.

The second section demonstrates how to use Market Basket analysis to identify product-bundling opportunities to be able to upsell to Customers. It does this using mlxtend library and its apriori algorithm and association_rules class to identify instances where a statistical relationship exists between two products.

The third section uses Recency, Frequency, Monetary Value (RFM) Clustering to group customers into different groupings based on the RFM features. KMeans Clustering is used from scikit-learn. Altair is then used to visualize the distribution of customers and their different clusters.
