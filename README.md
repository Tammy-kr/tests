**Some ways to calculate LTV**

Different forecast models are used to calculate predictive LTV.
First of all, you should understand what kind of data history we have
(week, month or other period).
Suppose for data for a year and for a week one forecast model may not be effective or applicable.

Linear models and catboost can be used in sufficient quantities data, but the coefficient model and
extrapolation model can be applied to small datasets and the data should be as update as possible.

The classic approach in forecasting (but not the most accurate), for example - Pareto/NBD.

In addition, you need to decide on a cohort (let's say all users,
who made the first payment on date, for a more accurate prediction by cohort.

It is also useful to evaluate the error on the cohort, which will show the accuracy of the prediction.




