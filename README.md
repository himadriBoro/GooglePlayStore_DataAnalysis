<h1 align='center'>Exploratory Data Analysis On Google Play Store Apps Reviews.<h1>
## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of the Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.


### Data Source:
- [Dataset](https://www.kaggle.com/datasets/lava18/google-play-store-apps) 


## Features

**App Category:** Category of the app. This could be beauty, business, entertainment, education...etc.

**Rating:** How users rate the app out of 5, with 1 being the lowest rating and 5 being the highest.

**Reviews:** The number of user reviews each app has received.

**Size:** The memory size needed to install the application.

**Installs:** The number of times each application has been installed by users.

**Type:** Whether the app is free or a paid app.

**Price:** The price of the app.

**Content Rating:** This column specifies the intended audience for the app. Can be for teens, mature audience, or everyone.

**Genres:** The sub-category for each app. Example: for the Education category, this could be Education: Pretend Play, for example.

**Last Updated:** Release date of the most recent update for the app.

**Current Ver:** The app's current version.

**Android Ver:** The oldest version of Android OS supported by the app.

## Tools used

![Python]

![NumPy]

![Pandas]

![Matplotlib]

![Seaborn]

![GoogleColab]

![Power BI]



## Summary and Conclusion

Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

To ensure data integrity, we began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. However, due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected our final results. Therefore, we used another method to deal that particular null values.

After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs.

Furthermore, we merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

Key insights and conclusions drawn from our analysis include:
There is a strong positive correlation (0.64) between the number of reviews and installs.

Rating and installs show weak correlation (0.05), implying high ratings don’t always mean high downloads.

"FAMILY" is the category with the most apps.

"GAME" and "COMMUNICATION" are among the top categories by number of installs.

Free apps dominate the Play Store, comprising 92.12% of the dataset, while paid apps make up only 7.81%.

Top-rated free apps often belong to "Productivity", "Education", and "Tools" categories.---------

Top-paid apps with high ratings are often in "Game" and "Lifestyle".

The majority of content (81.80%) is rated "Everyone", making it broadly accessible.

Apps with high installs generally have more sizes, indicating users prefer more smooth and graphics apps.

Apps with more reviews are more likely to be downloaded frequently.

Sentiment analysis shows 63.6% of user reviews are positive, while 23.9% are negative, and the rest are neutral.

Free apps receive more feedback, both positive and negative, due to their wider accessibility.

Paid apps, though fewer in reviews, tend to receive more positive sentiments, reflecting buyer satisfaction.

Developing apps within the "Family","Game" and "Lifestyle" categories may result in higher revenue.

Genres with the highest number of apps include: "Tools", "Entertainment", "Education", "Business", and "Medical".

Apps with frequent updates and optimal sizes are more likely to maintain higher ratings.

Designing apps for everyone with positive sentiment focus (good UX, performance) is a strategic advantage.

The dataset offers valuable insights for monetization strategy, category targeting, and user satisfaction. 

#


