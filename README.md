# Web-Scraping-Price-Prediction-and-Category-Clustering

In this project, I started by performing web scraping to extract book prices and details from a website. I used the BeautifulSoup library to parse the HTML content of the web pages and extract the desired information such as title, price, availability, rating, product type, number of reviews, and category.

After scraping the data, I performed data transformation and feature engineering to prepare it for machine learning. I cleaned the data by removing any unnecessary characters and converted the price and quantity columns to numeric values. I also created a unique ID for each book and encoded the categorical variable "Category" using label encoding.

For the supervised learning task, I chose to use the Linear Regression algorithm to predict book prices, just for simplicity. I also split the data into training and testing sets, fitted the model on the training data, and evaluated its performance on the testing data. I also compared the predicted prices with the actual prices using a scatter plot to visualize the model's performance.

For the unsupervised learning task, I employed the K-Means clustering algorithm to classify books into different categories based on their features. I used the encoded category ID column and other relevant features for clustering. I determined the optimal number of clusters using the elbow method and silhouette analysis. Finally, I visualized the clusters and the data points in a scatter plot to gain insights into the clustering results.

Overall, this project involved web scraping, data transformation, feature engineering, and the application of both supervised (Linear Regression) and unsupervised (K-Means) machine learning algorithms. It allowed me to extract book prices and details, predict prices using regression, and classify books into categories using clustering. The combination of web scraping and machine learning techniques provided valuable insights and potential applications in the domain of book analysis and recommendation systems.
