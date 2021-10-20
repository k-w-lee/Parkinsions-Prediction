# Parkinsions-Prediction
The aim of this paper is to build a predictive model
that can accurately predict the total UPDRS scores with at
least 0.9 R Squared based on the voice measures. We utilized
a dataset that recorded voice measures from 42 subjects with
Parkinson Diseases, which consist of 5874 observations and
22 attributes. After performing data exploration, we noticed
voice measures have a nonlinear relationship with UPDRS
scores. Therefore, 3 nonlinear models are deployed, which
are Support Vector Machine, Decision Tree Regressor, and
Random Forest Regressor. After running all the models, the
random forest regression model can best predict UPDRS
based on voice measures (RQ2). This is because it has the
highest R Squared (0.912), and has the lowest RMSE (3.39)
and MAE (2.38) on the testing set. Besides, age is the highest
feature importance in the prediction of UPDRS, which
means that it is the most important predictor in the UPDRS
score.

# Team Presentation
You can view the presentation via this [link](https://spark.adobe.com/page/gf0qnybSmQvfc/)

# 2MP Competition
You can view the competition via this [link](https://padlet.com/nlee95/posterC202)
