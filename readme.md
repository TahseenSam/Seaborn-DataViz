# Bar Plots
Bar plots are used to display the distribution of a categorical variable. They are often used to compare the values of a variable across different categories. For example, you might use a bar plot to show the number of customers that visited a store each month, with each bar representing a different month.

![bar5](https://user-images.githubusercontent.com/95973635/212457675-4255b5b2-37f3-4ea4-b3e0-c75e0dcdf286.jpg)

# Histograms
Histograms are used to display the distribution of a continuous variable. They show the frequency of different values of the variable, grouped into "bins" of equal size. For example, you might use a histogram to show the distribution of ages of customers in a store, with each bin representing a range of ages (e.g., 20-29, 30-39, etc.).

![histogram](https://user-images.githubusercontent.com/95973635/212458020-95a2694c-7867-4865-bb55-7aa4aa496289.png)


# Box Plot
A box plot, also known as a box-and-whisker plot, is a graphical representation of a dataset that uses quartiles to show the distribution of the data. It consists of a box that spans the interquartile range (the middle 50% of the data) and a vertical line inside the box that represents the median. Whiskers extend from the box to the minimum and maximum values of the dataset, and any data points outside the whiskers are plotted as individual points (outliers).

![box](https://user-images.githubusercontent.com/95973635/212457760-7ad61d6f-a132-431f-86eb-eb1833861a5b.png)

# Violin Plots
Violin plots are a combination of histograms and kernel density estimation, which is a way to estimate the probability density function of a random variable. Violin plots show the distribution of the data, including the spread and the skewness of the data, while also showing the density of the data.It is good to use when you have multiple categories of data and want to compare the distribution of a variable among them. For example you can use it to compare the weight distribution of different species of animals.

![vilin](https://user-images.githubusercontent.com/95973635/212458061-ad08751a-6fca-4791-8f7b-bc54210cdd2b.png)


# Pie Chart
Pie charts are used to display the proportion of different categories of a categorical variable. They are often used to show how a whole is divided into parts. For example, you might use a pie chart to show the percentage of sales that come from different product categories in a store.

![pie chart](https://user-images.githubusercontent.com/95973635/212457873-521a9c48-863c-4f1d-9bf3-d0a420a7420e.png)

# Line Plot
Line Plots: A line plot is used to show the relationship between a continuous variable and a categorical variable. Line plots are particularly useful when you have multiple observations and want to show how they vary over time. For example, you could use a line plot to show the stock price of a company over time, with the date on the x-axis and the stock price on the y-axis.

![line](https://user-images.githubusercontent.com/95973635/212458029-7537a8d3-606a-450c-8384-a85674e56056.png)

# Scatter Plots
Scatter Plots: A scatter plot is used to show the relationship between two continuous variables. Each data point is represented by a dot on the plot, with the value of the first variable on the x-axis and the value of the second variable on the y-axis. Scatter plots are a good way to see whether there is a correlation between two variables. For example, you could use a scatter plot to show the relationship between a customer's age and their annual income.

![scatter](https://user-images.githubusercontent.com/95973635/212458038-474b3d25-14e5-4f15-8aba-d552e956f072.png)

# Count Plots
Count plots: A count plot, also known as a bar plot for frequencies, is similar to a bar plot, but it shows the count of observations for each category of a categorical variable, rather than a summary statistic like mean or median. It is done using seaborn library, and the countplot() function to be precise. The x-axis shows the categories of the variable and the y-axis shows the count of observations in each category. For example, you might use a count plot to show the number of customers of different age groups that visited a store during a given time period.
![count](https://user-images.githubusercontent.com/95973635/212457771-70ded99b-9255-45d5-9c3c-378c7f86984b.png)

# Strip plot
Strip plot: A strip plot, also known as a "one-dimensional scatter plot," is a visualization that shows the distribution of a numerical variable along a categorical variable. It's a scatter plot with one dimension. It is created using seaborn library and its stripplot() function. It can be used to show the distribution of a numerical variable for different categories, for example, you could use a strip plot to show the distribution of customer income for different ages.

![strip](https://user-images.githubusercontent.com/95973635/212457774-17117a09-7643-4075-b71b-9bb2915c2619.png)

# Pair Plot
Pair plot: A pair plot, also known as a "scatter plot matrix," is a visualization that shows the relationship between multiple numerical variables in a dataset. It is created using seaborn library and its pairplot() function. Each variable is plotted against every other variable in a matrix format, with the diagonal being a histogram or a kernel density estimate of the distribution of the variable. It can be a good tool to quickly identify any relationship between the variables, correlation and outliers.

![pair](https://user-images.githubusercontent.com/95973635/212457922-c5297686-688d-4fc1-9a5b-9b1da40e920b.png)

# Cat Plot
Cat plot: A cat plot is a visualization that shows the relationship between a numerical variable and a categorical variable. It's is created using seaborn library and its catplot() function. It allows to see the distribution of a numerical variable for different categories of a categorical variable. It combines aspects of both bar plots and box plots, and can be used for both univariate and bivariate data. It can be a powerful tool to see the relationship of numerical variable with categorical variable, for example, you can use cat plot to show the relationship of income with education

![cat plot](https://user-images.githubusercontent.com/95973635/212457765-2e58bcee-e6cb-4736-82a9-2eab9174584c.png)
