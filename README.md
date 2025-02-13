# Smart-Suggest-Recommendation-Engine
SmartSuggest is an AI-driven recommendation system that personalizes e-commerce shopping by analyzing user behavior and purchase history, offering tailored product suggestions to enhance the shopping experience.

### Recommendation System Primary Columns

In the recommendation system, the primary columns used from the dataset to make recommendations are:

1): CustomerID: This column uniquely identifies each customer. It is used as the index in the user-item matrix to represent different users.

2): StockCode: This column uniquely identifies each product. It is used as the columns in the user-item matrix to represent different products.

3): Quantity: This column represents the quantity of each product purchased by a customer. It is used as the values in the user-item matrix to indicate the strength of interaction between a user and a product.

### Why These Columns?

CustomerID and StockCode: These columns are essential for creating a user-item interaction matrix, which is a fundamental structure in collaborative filtering. The matrix captures the relationship between users and products, enabling the system to identify patterns and similarities in purchasing behavior.

Quantity: The quantity of products purchased is used as a proxy for user preference or interest. A higher quantity purchased might indicate a stronger preference for that product. This information helps in identifying which products are likely to be of interest to similar users.

Kaggle Dataset: https://www.kaggle.com/datasets/carrie1/ecommerce-data
