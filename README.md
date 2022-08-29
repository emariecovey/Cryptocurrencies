# Cryptocurrencies

The purpose of this project was to use unsupervised machine learning to group cryptocurrencies. 

1. First, cryptocurrency data was prepared for the machine learning model. I cleaned the data with pandas in python, created numeric variables for text features, and standardized the data with a Standard Scaler. 
2. Then, I applied the Principal Component Analysis (PCA) algorithm to reduce the dimensions to three principal components. 
3. Next, I used a k-means algorithm to create an elbow curve to find the best value for K (which was 4). The data was then run with a k-means algorithm with four clusters. 
4. I then created Visualizations for the project. I used plotly to make a 3D plot of the three PCA dimensions. I also made a dynamic table with hvplot. Lastly, I created a 2D plot of the standardized continous variables from the dataset (total coin supply and total mined coins). 

Elbow curve:
![elbow curve]()

3D plot:
![3D plot]()

Table:
![Table]()

2D_plot:
![Table]()
