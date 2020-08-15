Dataset : Ford GoBike System data (2017)

Main Findings : 
 - This dataset consisted of 519700 rows with 13 columns. Data types are mixed including object, integer, float, and datetime. There are 272 Stations with 3673 bikes. On the 'user_type' column, there are two unique values which are 'Customer' and 'Subscriber'
 - There are outliers within the dataset. These are removed
 - There are rows where distances is 0 meter. These are removed
 - 8.91% of total rows removed
 - Logarithmic Transformation is done to view the Amount of Customer Rental Distribution in 2017. In linear scale, it was right skewed, while in logarithmic scale, it was in normal distribution
 - There are relationship between Duration and Distance variables
 - Confidence Interval of June pointplot estimator between Distance, Month, and User Type is very much larger than the other months. This is because the amount of rows is much lower in this month

 Key Findings :
 - In average, customers ride in 15 minutes
 - October is the highest amount of rentals
 - Customer Type rows is around 1/4 of Subscriber Type rows
 - Duration and Distance has high and positive relationship
 - Customer Type Duration seems more distributed
 - Customer rides further and longer than Subscriber
 - People travelled further in Autumn

Finding in exploration aboout Top 5 station was abandoned because I don't think I'm going to
find something interesting anymore