# Titanic: Machine Learning from Disaster

> My entry for the [Titanic Kaggle competition](https://www.kaggle.com/c/titanic) which received a public score of 0.78229 (*Top 21%* out of 17,079 entries) and was submitted in November 2020. Competition participants create a machine learning model to predict which passengers survived the shipwreck. 



## General info

A variety of models and features were created and tested for this competition. In the end, after a lengthy feature engineering process, I settled on 9 features. This included creating a feature for the title of each passenger (‘Mr’, ‘Miss’, ‘Master’, etc.) using regular expressions and age groups via pandas’ built-in functions. 

A Random Forest Classifier was trained using a random part of the train dataset. The model was initially evaluated using its accuracy and AUC (Area under the ROC Curve) scores. It was then hypertuned with the help of matplotlib and sklearn. Seaborn was also used throughout the analysis to visualise the data.

Please note that due to the high randomness of the Titanic incident, this code was run many times to find the best parameters. This is why the displayed parameter suggestions in the uploaded code do not reflect what was eventually selected for the final model.

The following files are included in this repo:

* `kaggle-titanic.ipynb`: the code
* `titanic-submission.csv`: survival rate predictions
* `train.csv`: train dataset; includes survival information
* `test.csv`: test dataset; excludes survival information



## Technologies

Python 3.7.6



## Contact

Created by [@katrinaalaimo](https://www.katrinaalaimo.com/) — feel free to contact me!
