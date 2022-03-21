# Cryptocurrencies

## Overview/Background
Martha a friend and senior manager for the Advisory Services Team at Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
The data Martha and I will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, we have decided to use unsupervised learning. To group the cryptocurrencies, Martha and I decided on a clustering algorithm. We will use data visualizations to share our findings with the board. 

Tools used
  SCIkit-learn  runs statistically functions and computations
  Plotly graphing library 
  Hvplot high level plotting library that uses holovViews and bokeh
  Pandas : read data into dataframes and much much more 

## Analysis
Preprocessing the Data for PCA
  • Review the steps to prepare data
  •	Preprocessing data with Pandas
  • Data selection
  •	Preprocessing data
  •	Use the StandardScaler library to standardize features


Reducing Data Dimensions Using PCA
![reducingdatadimentsionspca](https://user-images.githubusercontent.com/94208810/159311490-c2ce5de9-6b4a-4442-bc10-d62a9f84512e.png)


Clustering Cryptocurrencies using K-Means
  * Finding the best valuse for k using the Elbow Curve
![elbow](https://user-images.githubusercontent.com/94208810/159310483-cea2b28a-827e-49aa-ad9d-a6aeefd62062.png)

  
Visualize Cryptocurrencies Results
  *  3D Scatter Plot 

![3D scatter with PCA Data and clusters](https://user-images.githubusercontent.com/94208810/159307442-eaa4f21a-2cf1-42cc-ae16-532830e757d2.png)


  * Table with tradable crypotocurrencies using the hvplot.table() function.
  ![TradableCurrenciesTable](https://user-images.githubusercontent.com/94208810/159306256-0359f637-d58b-4a9e-95f1-39f83edcc3db.png)
 
 * Total Number of  traable Cryptocurrencies

![Screenshot (219)](https://user-images.githubusercontent.com/94208810/159307575-5c8eb25b-a505-4bc4-bbd7-b642c6f58a26.png)
  
  * Plot_df (New Dataframe created with scaled data)
  * 
 ![Screenshot (229)](https://user-images.githubusercontent.com/94208810/159311704-b9342b4d-75be-44e0-8929-3e7228551220.png)

  
  * hvplot scatter plot with X="TotalCoinsMInes" and y="TotalCoinsSupply"
  
![hvscatterplot4](https://user-images.githubusercontent.com/94208810/159312181-f81da349-ce34-4371-a464-350b7a8f64b2.png)

