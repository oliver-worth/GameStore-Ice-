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
2. Identifying potential blockbuster games for planning future marketing campaigns.

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
## Future Work
- Model Improvement: Further refinement of the predictive model using advanced techniques.
- Feature Engineering: Creation of additional features to improve model accuracy.
- Broader Dataset: Expanding the dataset to include more recent data and additional regions.
