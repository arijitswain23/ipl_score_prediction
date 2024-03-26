# IPL Score Predictor

This Sports Analysis Model enables user to predict total runs between teams using current runs and wickets.

**Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn**

**Algorithms used:**

* Linear Regression
* K-Nearest Neighbor Regressor 
* XGBoost Regressor
* RandomForest Regressor
* SVR
* Decision Tree Regressor

 **Dataset:**

The dataset comprises of over by over details of matches and runs from 2008 to 2017.

Dataset Used: ipl_data.csv

* mid - match id
* date - when matches are played
* venue - place where matches aew played
* bat_team - batting team
* bowl_team - bowling team
* batsman - batsman
* bowler - bowler
* runs - runs scored
* wickets - wickets
* overs - overs - next 3 are based on this
* run_last_5 - runs scored in last 5 overs
* wicket_last_5 - wickets in last 5 overs
* stricker - batsman playing as main 1
* non-striker - batsman playing as runner up - not main 0
* total - total score (target variable)

**Functionality:**

**Data Collection:** The system collects historical match data including team performance, player statistics, venue details, and other relevant factors.

**Data Preprocessing:** The collected data is preprocessed to clean, transform, and prepare it for training machine learning models.

**Machine Learning Models:** Various machine learning models such as regression, ensemble methods, or neural networks are trained on the preprocessed data to learn patterns and relationships.

**Prediction:** Once trained, the models are used to predict the scores of upcoming IPL matches based on input parameters such as teams playing, venue, weather conditions, etc.

**Evaluation:** The performance of the prediction models is evaluated using metrics such as accuracy, mean squared error, or root mean squared error to assess their effectiveness.
