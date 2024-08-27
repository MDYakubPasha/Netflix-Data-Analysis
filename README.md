# Netflix Data Analysis Case Study

## Project Overview
This project involves analyzing Netflix's dataset to extract valuable insights and provide actionable recommendations. The analysis focuses on understanding content trends, viewer engagement, and optimizing Netflix's content strategy.

## Problem Statement
**From the Company’s Perspective:**
- Netflix is one of the leading media streaming platforms with over 200 million subscribers globally.
- With over 8,000 movies and TV shows available, it is crucial to analyze the data to understand what content resonates with different audiences.
- This analysis will help Netflix decide on content production strategies and improve business growth.

**From the Learner’s Perspective:**
- This case study provides hands-on experience for aspiring data analysts and scientists.
- It enhances practical skills in data analysis using Python, helping to communicate insights to stakeholders effectively.

## Dataset
The dataset includes details about all movies and TV shows available on Netflix, such as cast, directors, ratings, release year, duration, and more.

- **Link to Dataset:** [Kaggle Netflix Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows)
- **Key Columns:**
  - `Show ID`: Unique identifier for each show.
  - `Type`: Indicates whether it's a Movie or TV Show.
  - `Title`: Name of the Movie/TV Show.
  - `Director`: Director of the Movie/Show.
  - `Cast`: Actors involved in the Movie/Show.
  - `Country`: Country where the Movie/Show was produced.
  - `Date_added`: Date the Movie/Show was added to Netflix.
  - `Release_year`: Year the Movie/Show was released.
  - `Rating`: TV rating of the Movie/Show.
  - `Duration`: Total duration (in minutes or number of seasons).
  - `Listed_in`: Genre of the Movie/Show.
  - `Description`: Brief description of the Movie/Show.

## Analysis Approach
### 1. Basic Analysis
- **Un-nesting Columns:** Un-nested columns with multiple comma-separated values by creating multiple rows.
- **Handling Null Values:**
  - For categorical variables, missing values were replaced with `Unknown`.
  - For continuous variables, missing values were replaced with `0`.

### 2. Categorical Variable Analysis
- Conducted both graphical and non-graphical analysis to find the counts of each category.

### 3. TV Shows vs. Movies Comparison
- Analyzed the number of Movies and TV Shows produced in each country, focusing on the top 10 countries.

### 4. Best Time to Launch Content
- Identified the best week and month to release TV Shows and Movies based on historical data.

### 5. Director/Actor Analysis
- Identified the top 10 directors and actors who have appeared in the most Movies or TV Shows.

### 6. Genre Popularity
- Used a word cloud to visualize which genres are produced more frequently.

### 7. Time to Add to Netflix
- Analyzed the time difference between a Movie's release date and its addition to Netflix.

## Tools and Technologies
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab
- Word Cloud for genre analysis

## Insights and Recommendations
- Content Type : Our analysis showed that Netflix had added more movies than TV shows
- Content Addition: July emerged as the month when Netflix adds the most content, closely followed by December, indicating a strategic approach to content release.
- Movie Lengths: The analysis of movie durations indicated a peak around the 1960s, followed by a stabilization around 100 minutes, highlighting a trend in movie lengths over time.
- TV Show Episodes: Most TV shows on Netflix have one season, suggesting a preference for shorter series among viewers.
- Common Themes: Words like love, life, family, and adventure were frequently found in titles and descriptions, capturing recurring themes in Netflix content.
- Rating Distribution: The distribution of ratings over the years offers insights into the evolving content landscape and audience reception.


RECOMMENDATIONS :

1.Netflix needs to produce more number of TV shows which will increase the duration of viewership.
2.Adding further, more engaging content needs to be roped in as most of the TV shows have less than 2 seasons.
3.Recommend that netflix can engage the top directors and actors for producing movies/tv shows that will have a good audience reach.
4.We can also notice that top 10 countries producing content is almost equal to 90% of total content, recommend that we can target more diverse regions and countries to increase the subscription base.
5.Ratings are also mostly 'TV-MA' which is limiting our viewership, so recommend to have more wider audience approach content. 

## How to Run the Project
1. Download the dataset from the provided Kaggle link.
2. Open the `Netflix_case_study.ipynb` file in Jupyter Notebook or Google Colab.
3. Follow the analysis steps and run the cells to reproduce the insights.

## Conclusion
This analysis provides Netflix with actionable insights that can be leveraged to enhance content strategy and viewer engagement across different regions.

## Contact
- **LinkedIn:** [Yakub Pasha](https://www.linkedin.com/in/yakub-pasha-01434855/)
- **GitHub:** [@MDYakubPasha](https://github.com/MDYakubPasha)
