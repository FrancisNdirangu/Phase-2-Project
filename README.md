# Movie Studio Launch Analysis - Final Project
Team: Group 5
Members: Francis Ndirangu, Hanifa Chepchirchir, Brian Kipyegon, Ian Riua, Denis Kibor
Pace: Full Time
Instructor: Nikita Njoroge
Review Date: May 2, 2025  

# Project Overview
As a new entrant in the movie production industry, our goal is to uncover data-driven insights that inform what types of movies will most likely achieve commercial success.

### This analysis uses comprehensive data from IMDb, The Movies, and The Numbers to explore:

Genre trends
Director performance
Language and profitability
Popularity vs. profitability
Budget efficiency

# Objectives
Identify profitable movie genres and languages
Determine if top-rated directors yield better ROI
Analyze if popular or highly-rated movies generate more profit

# Methodology
Combined multiple datasets using SQL joins to unify:
Titles, genres, and release years
Ratings, popularity, financials
Key contributors (directors, cast)
Used Python libraries: pandas, numpy, sqlite3, seaborn, matplotlib, scipy, statsmodels
Applied:
Descriptive and inferential statistics
Visualization (boxplots, bubble plots)
T-tests and effect size calculations

# Visual Findings
Boxplot of Net Income by Genre: Genres like Adventure, Animation, Sci-Fi, Musical, and Fantasy showed both higher medians and wider profit ranges, indicating strong commercial potential but some variability.

![Boxplot of Net Income by Genre](./README_images/boxplot%20net%20income%20by%20genre.png)



Language Insight: English dominates in count, but Thai, Telugu, and Russian films show the highest profits.

![Language by Profit](./README_images/language%20by%20profit.png)



Bubble Plot: Budget vs. Net Income: A visible positive correlation exists between production budget and net income, especially when focusing on unique films to avoid overrepresentation from cast/crew multiplicity.

![Bubble Plot](./README_images/bubble%20plot.png)


Animated vs. Real Movies: Animated films demonstrated higher average profits compared to non-animated ones, suggesting the studio should prioritize animation-heavy projects.

![Animated vs Non-Animated Comparison](./README_images/animated%20vs%20non-animated.png)




# Conclusions
Popularity drives profits: A movie's popularity is the strongest predictor of its commercial success. The studio should invest in marketing, promotions, and casting actors with large social followings.

Quality matters: Higher-rated movies significantly outperform lower-rated ones. Invest in:
High-rated directors
Award-winning actors
Strong scripts or adaptations from high-quality source material

Top directors yield modest gains: Hiring highly-rated directors improves profitability, but the effect size is small (0.31). Focus on a balanced team.

Timing of release: Summer months — May, June, July — tend to see higher average profits. Plan releases accordingly.

Profitable genres: Stick to genres with the highest mean profits: Adventure, Animation, Sci-Fi, Musical, Fantasy, Sport, Action.

Go animated: Animated movies had consistently higher profits. Prioritize projects in this category.

Stick with English: Due to dataset limitations and target market considerations, produce films in English.

# Next Steps
Investigate strategies to boost movie popularity, including:
Advertising budget analysis
Influence of actor fame via social media metrics
Explore ways to enhance movie quality:
Hire top-rated actors and directors
Consider adaptation from acclaimed source material
Conduct A/B tests and hypothesis testing on creative decisions
### trello link= https://app.clickup.com/9012915717/chat/r/8ckcbg5-312
### github link= https://github.com/FrancisNdirangu/Phase-2-Project