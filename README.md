# \#RIP24and2

The dataset was provided by [Kaggle](https://www.kaggle.com/c/kobe-bryant-shot-selection/data?select=sample_submission.csv.zip).

## Task
In this data, we were given every single shot taken by Kobe throughout his 20 years in the NBA. 

I used a Random Forest, a Logistic Regression, and ADA Boosting as models.

We use these models to classify whether or not Kobe sinks a shot or makes enough bricks to make a house.

## EDA
Here are some insights and trends to look at.

![](https://github.com/laternader/RIP24and2/blob/main/imgs/topshot.png)

![](https://github.com/laternader/RIP24and2/blob/main/imgs/shotsaroundthecourt.png)

![](https://github.com/laternader/RIP24and2/blob/main/imgs/whoaretheknickslol.png)

![](https://github.com/laternader/RIP24and2/blob/main/imgs/playoffkobe.png)

![](https://github.com/laternader/RIP24and2/blob/main/imgs/4thqtrcounts.png)


## Results
The best model I select was the ADA model on these paramters:
```python
{'base_estimator__max_depth': 1, 'base_estimator__min_samples_leaf': 2, 'learning_rate': 0.95, 'n_estimators': 100}
Train Score 0.6847699814126395
Val Score 0.6770428015564203

f1_score = 0.5584394647751089
accuracy_score = 0.6770428015564203
```

There was not much overfit and it had a good metrics.

Regardless of the data, we have one of the best all time shot takers ever. And he was gone too soon. #RIPKOBE

![](https://github.com/laternader/RIP24and2/blob/main/imgs/ripkobe.jpg)