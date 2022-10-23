
# Pharmaceutical Reviews NLP

A new pharmaceutical startup is recently acquired by one of the world's largest MNCs. For the
acquisition process, the startup is required to tabulate all drugs that they have sold and account
for each drug's effectiveness. A dedicated team has been assigned the task to analyze all the
data. This data has been collected over the years and it contains data points such as the drug's
name, reviews by customers, popularity and use cases of the drug, and so on. Members of
this team are by the noise present in the data.

Task is to make a sophisticated NLP-based Machine Learning model that has the mentioned
features as the input. Also, use the input to predict the base score of a certain drug in a provided
case

### Tech Stack
NLTK : To build NLP model
XGBOOST : XGboostRegressor to predecit continous variables.
SKlearn : For ML libraries, such as RandomForestRegressor, DecesionTreeRegressor effectiveness
Pandas, Seaborn : Visualisation libraries


### Outcome 

As data is not linear, the regression models such as LinearRegressor, RidgeRegressor failed to produce good results.
Linear Regressor : 0.1667906924412197 
  1. Ridge Regressor :  0.16679072363988756
  2. GradientBoostingRegressor : 0.8804187450879799
  3. DecisionTreeRegressor : 0.9578741413365196
  4. RandomForestRegressor : 0.97429
  5. KNeighborsRegressor : 0.1034
  6. XGBRegressor : 0.9951950956840576


Out of all the models XGRegressor predecited the best
