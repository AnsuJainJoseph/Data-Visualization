PYTHON DATA VISUALIZATION 

Introduction
In this assignment, I explored how Python can be used to clean, analyse, and visualize data. I worked with the Taxis dataset available in the Seaborn library.
First, I explored the dataset and checked for missing values. I then applied suitable methods to handle the missing data. After cleaning the dataset, I created different types of charts using Matplotlib, Pandas, and Seaborn.

Objectives
•	To import and explore the Seaborn Taxis dataset.
•	To identify missing values in different columns.
•	To practise filling or removing missing values using appropriate methods.
•	To understand basic data cleaning techniques.
•	To create different charts using Matplotlib and Pandas.
•	To explore data visualization using Seaborn.
•	To analyse relationships, patterns, and trends in the dataset.
•	To improve my understanding of data interpretation through charts.

Dataset Information

The dataset contains information about taxi trips, including pickup and drop-off details, fare amounts, trip distance, tips, payment methods, and pickup locations.
I loaded the dataset into a Pandas Data Frame named df for further analysis.
Data Cleaning and Missing Value Treatment
Before creating visualizations, I checked the dataset to understand its structure and data quality.
•	Checked the dataset for null or missing values.
•	Identified the columns containing missing data.
•	Used suitable statistical methods such as mean or median to fill missing numerical values.
•	Used mode to replace missing categorical values wherever appropriate.
•	Removed rows where missing information could not be handled reliably.
•	Rechecked the dataset to verify the missing value treatment.

Data Visualization Using Matplotlib and Pandas
I created the following visualizations to explore different aspects of the taxi dataset.

Line Chart – Fare Over Time
Created a line chart to understand how taxi fares changed over time. The pickup date column was converted into datetime format and used on the X-axis, while fare was displayed on the Y-axis.

Bar Chart – Total Fare by Pickup Borough
Created a bar chart to compare the total fare collected from different pickup boroughs. I grouped the data by pickup borough and calculated the total fare for each category.

Pie Chart – Payment Method Distribution
Used a pie chart to display the distribution of taxi trips based on payment methods. This helped compare the number of trips made using different payment options, such as cash and credit card.

Histogram – Trip Distance Distribution
Created a histogram to understand how trip distances were distributed. Different bins were used to observe the frequency of trips across distance ranges.

Box Plot – Tip Amount by Pickup Borough
Used a box plot to compare tip amounts across different pickup boroughs. This visualization helped examine the distribution and variation in tips for each borough.

Data Visualization Using Seaborn
I also used Seaborn to create additional visualizations and explore the dataset in more detail.

Count Plot – Trips by Pickup Borough
Created a count plot to compare the number of taxi trips recorded in each pickup borough.

Scatter Plot – Distance vs Fare
Used a scatter plot to study the relationship between trip distance and fare amount. Different colours were assigned to pickup boroughs to make comparisons easier.

Heatmap – Correlation Between Numerical Variables
Created a correlation matrix using numerical columns such as distance, fare, tip, tolls, and total. A heatmap was used to identify positive and negative relationships between these variables.

Pair Plot – Relationship Between Variables
Created a pair plot to examine the relationships between distance, fare, tip, and total. Pickup zones were used to distinguish different groups in the visualization.

Violin Plot – Fare Distribution by Payment Method
Used a violin plot to compare fare distributions across different payment methods. This helped me understand how fare amounts varied between payment categories.

Conclusion

This assignment gave me an opportunity to practise data cleaning and visualization using Python. By working with the Taxis dataset, I understood how to prepare data and represent it through different types of charts.
I also improved my practical knowledge of Pandas, Matplotlib, and Seaborn. Overall, this exercise helped me build a better foundation in Python-based data analysis and understand how visualizations can support meaningful insights from data.

