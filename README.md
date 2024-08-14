# Ice Video Game Sales Analysis
## Project Overview
This project is part of the Ice online store's initiative to analyze video game sales data. The goal is to identify patterns that predict whether a game will succeed or fail. By understanding these patterns, the company can make informed decisions about future advertising campaigns.

## Data Source
The dataset contains information on video game sales, user and expert reviews, game genres, platforms (e.g., Xbox, PlayStation), and other relevant features. The data is collected from open sources and goes back to the year 2016. The dataset includes:

- Name: Name of the game
- Platform: Platform on which the game was released
- Year_of_Release: Year the game was released
- Genre: Genre of the game
- NA_sales: Sales in North America (in USD millions)
- EU_sales: Sales in Europe (in USD millions)
- JP_sales: Sales in Japan (in USD millions)
- Other_sales: Sales in other regions (in USD millions)
- Critic_Score: Aggregate score from critics (maximum of 100)
- User_Score: Aggregate score from users (maximum of 10)
- Rating: ESRB rating of the game

## Objective
The primary objective is to forecast game sales for the year 2017, using data from previous years, with a focus on:

1. Understanding the key factors that drive video game sales across different regions.
2. To forecast potential trends in the gaming market for 2017, focusing on game genres, platforms, and ratings.

## Tools and Libraries
The following libraries were used in this project:

- Pandas: For data manipulation and analysis
- NumPy: For numerical computations
- Plotly: For interactive visualizations
- Matplotlib: For static visualizations
- Scipy: For statistical analysis

## Methodology
1. Data Preprocessing: Initial data cleaning, including handling missing values, and data type conversions.
2. Exploratory Data Analysis (EDA): Detailed analysis of various factors such as sales by region, genre, platform, and user/critic scores.
3. Statistical Testing: Hypothesis testing to determine significant differences in sales across different categories.
4. Modeling: Predictive modeling to forecast sales for the upcoming year based on historical trends.

## Results and Insights
- The analysis revealed key insights into the influence of platform, genre, and ratings on sales.
- Statistical tests helped identify significant factors that can be leveraged for future game releases and marketing strategies.
- The predictive model provided a reasonable forecast for 2017 sales, though there is room for improvement.

# Analyzed Data and Key Findings 
## Number of Games Released Over the Years
- The peak year for game releases was 2008, with 1,427 games produced.
- The lowest number of releases was in 1980, with only 9 games produced.
## Sales Analysis by Platform
- Platform Popularity Over Time: Analyzed the lifecycle of various platforms, showing that platforms typically remain relevant for about 7.6 years before sales drop to zero.
- Top Platforms: DS and PS4 showed significant trends, with DS peaking in 2005 but declining post-2007, while PS4 continued to grow in sales through 2015.
## Platform Lifecycle Distribution
- Most platforms have a lifecycle of 10-11 years.
- The market began to stabilize in 2012 after a significant drop in sales, making data from 2012-2016 most relevant for analysis.
## Global Sales Trends (2012-2016)
- PS4 and Xbox One are the only platforms with increasing sales as of 2015, while all other platforms show a decline.
- A boxplot analysis revealed that median sales are relatively low across platforms, with significant outliers indicating that a few games achieve exceptionally high sales.
## Correlation Between Reviews and Sales
- User Scores: A weak correlation between user scores and sales (e.g., PS4 correlation of -0.03) suggests that user reviews do not strongly influence sales.
- Critic Scores: A moderately positive correlation for PS4 and Xbox One (0.4) suggests critic reviews might have some impact on sales, although it is not definitive.
## Genre Sales Analysis
- Total Sales: Action games generated the most revenue, but this was skewed by the high number of releases.
- Average Sales: Shooter games had the highest average sales per game, outperforming other genres.
- Median Sales: Shooter games also had the highest median sales, reinforcing their profitability.
## Regional Market Shares (2012-2016)
- North America: Xbox platforms dominate with a 44.7% combined market share.
- Europe: PlayStation platforms lead with a 49% combined market share.
- Japan: The 3DS controls 45% of the market, with minimal presence of Xbox platforms.
## ESRB Ratings and Regional Sales
- North America and Europe: Rated M games have the highest sales, indicating a preference for mature content in these regions.
- Japan: Rated E games perform better, with a much lower overall average sales compared to North America and Europe.
## Hypothesis Testing
- Xbox One vs PS4 User Ratings: No significant difference in average user ratings between the platforms.
- Action vs Sports Genre Ratings: A statistically significant difference was found in user ratings, with Action games rated higher on average.
## Conclusion and Recommendations
- Platform Strategy: Focus on emerging platforms like PS4 and Xbox One for future marketing, as they show growing sales trends.
- Genre Focus: Shooter games should be prioritized due to their higher average and median sales.
- Regional Marketing: Tailor marketing strategies to regional preferences, emphasizing Rated M games in North America and Europe, and Rated E games in Japan.
