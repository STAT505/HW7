# HW7

### 1.  
Using the candy dataset ([https://www.kaggle.com/fivethirtyeight/the-ultimate-halloween-candy-power-ranking/](https://www.kaggle.com/fivethirtyeight/the-ultimate-halloween-candy-power-ranking/) below
```
 candy <- read_csv("https://math.montana.edu/ahoegh/teaching/stat446/candy-data.csv") 
```
fit a linear regression model to predict win percent. Specifically for this model explore a model with 

- `chocolate`
- `peanutalmondy`
- `pricepercent`

#### a. (3 points) EDA

Create a few figures to explore the relationship between the three identified variables and `winpercent`. These figures should contain informative captions, titles, and labels.

#### b. (3 points) Model Formulation

Propose and write out a statistical model using complete notation. Note you may revise this after the following questions.

#### c. (3 points) Model Fitting

Fit a model using these three predictors. Focus on the functional form of the model: is an additive appropriate or do interactions need to be considered.

#### d. (3 points) Model Interpretation

Give (interval) estimates of all model parameters and describe them in the way a [candy maker](https://en.wikipedia.org/wiki/Willy_Wonka) can understand.

#### e. (3 points) Model Interpretation

Using your model, make (interval) predictions for the winning percentage for _new_ candy bar with the following ingredients:

- `chocolate` = 1, `peanutalmondy` = 1, - `pricepercent` = .5
- `chocolate` = 0, `peanutalmondy` = 1, - `pricepercent` = .5
- `chocolate` = 0, `peanutalmondy` = 1, - `pricepercent` = .9

