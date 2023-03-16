# Wine_Reviews_Data_Analysis

The goal of the project is to perform data exploration, data cleaning, 
and data visualization to gain insights into the wine industry.

The code first loads the dataset into a pandas dataframe and performs data exploration by getting information about the dataset, 
the shape of the dataset, viewing the first five and last five rows, and getting summary statistics. 
It then performs data cleaning by dropping columns that won't be used in analysis, filling missing values with mean for price and mode for 
variety and winery, and dropping rows with missing country or province.

Next, the code visualizes the data by creating several plots using seaborn and matplotlib libraries. 
It visualizes the distribution of wine scores using a histogram, the relationship between price and points using a scatter plot, 
the top 10 countries with the most wine reviews using a bar chart, the top 10 most expensive wines using a bar chart, 
the most common varieties of wine using a pie chart, and the most common wineries using a word cloud.

From the code, we can make several conclusions about the wine industry:

The distribution of wine scores is roughly normal, with the majority of wines scoring between 85 and 90 points.
There is a positive correlation between price and points, indicating that more expensive wines tend to have higher scores.
The top three countries with the most wine reviews are the United States, France, and Italy, which are traditional wine-producing countries.
The most expensive wines are mostly from France, with several wines costing over $2000 USD.
The most common variety of wine is Chardonnay, followed by Pinot Noir and Cabernet Sauvignon.
The most common wineries are mostly from California, with several wineries having more than 2000 reviews.
Overall, this project provides valuable insights into the wine industry and can help wine producers and retailers make more informed decisions 
based on the data.
