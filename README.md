This project was carried out as an assignment of the UCA DSAI course "Introduction to Machine Learning" class.

The evaluation overview is as follows:
Goal: predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

Code: 
* All the code (features cleaning, features generation, features selection, features extraction, prediction, model selection) must be executed within a sklearn or imblearn pipeline.
* All the code, included in a jupyter notebook, must be commented and possibly illustrated with images or bibliographic references. You may reuse images available on the Internet.
Metric: Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. 

## Project Overview : House Price Prediction

Ask a buyer to describe their dream home and they probably won't start with basement ceiling height or proximity to an east-west rail line. But the data set from this playground contest proves that price negotiations are influenced by much more than the number of bedrooms or a white picket fence.

![](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

This dataset contains 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa. 

**Goal:** It is your job to predict the sales price for each house using everything you have learned so far. If **you use a model not presented in class, you must justify it, explain how it works and describe precisely the role of each of the hyper-parameters**. For each Id in the test set, you must predict the value of the SalePrice variable. 

**Metric:** Predictions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

**Homework submission**: You must upload a zip archive containing 3 files to``lms.univ-cotedazur.fr`:

* A `pdf` report describing for each of the selected features the treatment performed
* A `jupyter notebook` performing the preprocessing, each step of which is inserted into a sklearn or imblearn pipeline (you must leave traces of notebook executions. The first cell should have the number 1, the second the number 2, etc.)
* A `result.csv` should contain your prediction for each of the properties in tthe test set in the the following format:
<pre>
        Id,SalePrice
        1461,169000.9876
        1462,187724.1233
        1463,175221.1928
        etc.
</pre>

The scale will be as follows:
* 8 points on the quality of the preprocessing and its description from the report 
* 8 points on the quality and correctness of the code contained in the notebook
* 4 points on the quality of the model produced