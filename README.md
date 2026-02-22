# Determinants of Video Game Success: A Data-Driven Market Analysis
This is the first project that I have created during the process of education on the Yandex Practicum platform.
In this project I am working as an analyst at the online store “Strymchik,” which sells computer games worldwide.
Historical data on game sales, user and expert ratings, genres, and platforms (for example, Xbox or PlayStation) are available from open sources.
It is necessary to identify patterns that determine a game’s success. This will allow us to bet on a potentially popular product and plan advertising campaigns.
We have data up to 2016. Let’s assume it is now December 2016, and we are planning a campaign for 2017.

## Technical Project Description

This project focused on identifying the key factors influencing video game sales using Python-based data analysis. The objective was to analyze market trends, platform and genre performance, regional differences, and the impact of ratings on sales.

The analysis was conducted using Python, primarily with:
- pandas for data cleaning, transformation, and aggregation
- matplotlib and seaborn for data visualization
- scipy.stats for hypothesis testing

First, I cleaned and prepared the dataset: renamed columns, handled missing values, converted data types, and filtered the data for games released from 2012 onward. I also created additional variables, including total global sales.

Using groupby(), sum(), mean(), and median(), I analyzed sales trends by year, platform, genre, and region (North America, Europe, Japan). Visualizations such as bar charts and boxplots helped identify top-performing platforms and genres.

I then calculated Pearson correlations to examine the relationship between sales and both user and critic ratings. The results showed that critic scores have a stronger correlation with sales than user scores.

Finally, I tested hypotheses using independent two-sample t-tests. 

## Key Technical Skills Applied
- Data cleaning and transformation with pandas
- Aggregation and grouping operations
- Correlation analysis
- Visualization using matplotlib and seaborn
- Statistical hypothesis testing with scipy
- Interpretation of p-values and significance levels
