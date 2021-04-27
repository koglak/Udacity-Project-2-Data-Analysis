# Udacity-Project-2-Data-Analysis
IMDB MOVIE LIST DATA WRANGLING


## Introduction

Imdb dataset included such as movies, directors, genres of moveies, release date and year, budget, production companies etc.
I will try to answer 2 questions.
1. Which genres are most popular from year to year?
2. Does bugdet effect popularity of movie? How?

At this section, I checked dataset information and missing value. I defined my questions accordingly missing value. Budget, release_date, popularity do not have any missing value but genres column has 23 missing value. So I will only drop 23 rows to complete my study.


**My observations:**
 - Drama and romance movies improved popularity a lot later 2010.
 - Drama movies improved popularity between 1970-1980 six times more.
 - Documentary category has lowest popularity
 - Comedy movies was most popular category at beginning of 60s.
 - Horror movies was the most popular category at beginning of 90s.
 
**Notes:**
- CSV data is enough to answer this question for some categories.
- Movies mostly labeled with many genres. I first decided to separate categories. For example, If a movie labeled as Drama and Romance, I thought I can add 2 line for this movie, first one is Drama, second one is Romance. But that seemed to me complicated and I gave up. 
- Later I decided to use genres which has more samples than others. 
- Some categories has 1 sample. 1 sample is not enough to answer this question.
- I faced some difficulties when I tried to plot graphics. It was usually lack of practice. Later I overwhelmed.


**My observations:**
* I tried to observe if budget effects popularity of a movie.
* In this case, I wanted to analysis comedy category because this category had greater sample than others.
* When I plotted budget vs popularity, I could not observe any logical result.
* So I decided to divide popularity to 1,2,3,4,5,6 category and I took mean of budget for each range.
* Latest graphic showed that there is not linear/bounded relationship between this 2 category.
* For example when popularity improved to 2 from 1, mean of budget also increased.
* But when popularity improved to 3 from 2, mean of budget decreased.
* So we can say that mean of budget directly effect to popularity for comedy category

**Notes:**
- I selected comedy category to assess budget effects to popularity.
- When I plotted popularity vs budget with all data, I could not observe a relationship between graphics. 
- Later I decided to categorize popularity to 1,2,3,4,5,6. I calculated mean of budget for each popularity category.
- Finally I drawed line chart graphic for mean of budget vs popularity range. In this case I could not observe direct relationship between these subjects. We can not say budget increasement improves popularity or opposite.
- Accordingly my opinion, csv data is enough to evaluate this question but accordingly my observation there is not linear/nonlinear relationship between budget and popularity.
- When I drawed popularity vs budget graphics I could not observe a relationship. In this case, I felt stuck because I could not find a solution how I can answer this question. Later I thought maybe I can categorize popularity in a range and try to create more clear graphic than first one. And it worked for my observation.
