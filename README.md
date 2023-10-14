# Depression-Detection

Detect Depression  from  [b-depression Dataset](https://www.kaggle.com/datasets/francispython/b-depression) using 4 models. 


## Technologies Used
- Jupyter Notebook
- Numpy
- Pandas
- Scikit Learn
- Matplotlib
- Seaborn
- xgboost

  
## Implemented Models: 
1. **Logistic Model**
2. **Decision Tree**
3. **Random Forest**
4. **XGBoost Model**

Evaluated using *K-Fold Cross Validation*


## Outcome
There are two expected outcomes: Depressed(1) and Not Depressed(0).


### Models and Accuracy Scores

{'Logistic Regression': 0.5260205337365071,
 'Decision Tree':0.8891600154706234,
 'Random Forest': 0.9580165957596428,
 'xgboost': 0.9395292008016597}

**Random Forest performed the best and Logistic Regression performed the worst!** 


## Conclusion
I randomly chose one of the test samples and predicted, using all four models by the **voting method**, if the person has depression or not!




