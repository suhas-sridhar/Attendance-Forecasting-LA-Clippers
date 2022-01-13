# Attendance-Forecasting-LA-Clippers
- Watch Powerpoint presentation to get a summary of the project. The presentation covers key aspects such as the reason for choosing a random forest model, reasoning behind the features used, and a brief summary of the results.
- Formulated and answered some interesting questions before proceeding with EDA and Model development.
- These questions also give me an opportunity to showcase my proficiency in Pandas, SQL, Algorithmic thinking, etc.

### Do weekend games (Friday, Saturday, Sunday), on average, have a higher attendance than weekday games (Monday through Thursday)?
- Used SQL to answer this question.
- Weekend games do have higher attendance on average.
### Identify and rank the top 4 opponents with the highest average number of attendances.
- Used SQL to answer this question.

![image](https://user-images.githubusercontent.com/96037819/149369284-74b30bb2-af26-4055-877f-2601d1f73d7a.png)
### Identify and rank the top 10 sections that are, on average, the most filled to their capacity.
- Used pandas to manipulate dataframes to answer this question.

![image](https://user-images.githubusercontent.com/96037819/149369619-4ad3dd34-b175-4a0d-97a2-44accd4fa800.png)
### Is there a correlation between the opponent team having a higher Vegas Odds Score (indicating higher probability of winning a championship) and higher attendance?
- Used seaborne, statsmodels, pandas to answer this question.
- There does not seem to be a correlation between the Vegas Odds score and attendance.
- The p-value of attendance is 0.316, and the R-squared value os 0.0206. (Check jupyter notebook for OLS regression results)
- Hence, we cannot conclude that there is a correlation between attendance and Vegas odds score.
### On average, which 15-minute period before or after the start of a game has the highest numberof people scanning.(Example 30 – 16 minutes prior to the start of a game)
- Used pandas and algorithmic thinking to answer this question.
- On average, the 15-0 minute window prior to the start of the game has the highest number of people scanning. (Check jupyter notebook for code)

## Model Development
- Used Random forest to predict attendance for upcoming season
- Compared random forest model with linear regression model. Accuracy of random forest model is much higher.
- Plotted graph of important features identified by the model
- Developed 2 models using random forest.
- According to me, model 2 is a better model for predicting attendance. Reasoning is mentioned in the powerpoint presentation.
- Model 2 has an accuracy of 87.88%
