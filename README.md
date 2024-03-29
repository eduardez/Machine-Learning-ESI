# Deng AI | Machine-Learning-ESI
## Predicting the spread of Dengue from climate data

<img align='right' src='img/Mosquito.png' width='350"'>

### Objetive 
Dengue has emerged as one of the major epidemics in current times. There is some evidence available about the correlation of this disease with climate. If we are able to model the number of cases reported historically in a place using the climate data for that place over the same period, It shall increase our accuracy in predicting the spread of this disease. Which in turn shall help not only in being better prepared in our efforts at the individual level but also at the government level for prevention as well as treatment measures.

### Data
The data has been obtained from [drivenData.org](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/), it was released as a part of their competition DengAI. In their own words, driven data hosts "data science competitions to save the world"..

### Modelling Approaches
A quick walk-through of different modeling techniques used:

1. Decision Tree
2. K-Neighbors Regression
3. Random Forest
4. Ada Boost
5. Stochastic gradient descent
6. Facebook's Prophet
7. Voting Ensemble
8. LSTM
  
>In our case, the best model is Random Forest. The importance of Random Forest for us is not whether it was good or bad predicting cases of dengue in Iquitos or San Juan, but because it showed the importance of each feature we could be able to use those same features to train other models and get better results.

### Results from Experiments

#### Feature Engineering

For the selection of characteristics we have had to make a temporary shift between the different characteristics and the total cases since, for example, the rain that fell 1 month ago is what causes the birth of dengue mosquitoes now.

#### Feature Selection
<p align='center'><img  src='img/modelo.png' width='650"'></p>


------------------------------------
For more information on the development of this project, do not hesitate to consult the [attached PDF](https://github.com/eduardez/Machine-Learning-ESI/blob/master/img/Second_Milestone___Machine_Learning.pdf) in this repository.

### Next Steps
- Better exploit feature shifting.
- Use one model to predict just the seasonality and other one to predict the error of the previous model.
- Correct the LSTM, as we believe it can give better results than we have.

### Contributing Members

|Name     |  Github User   | Contact |
|---------|-----------------|---------|
|[Lucía Alfonso García](https://github.com/luciaagarcia)| @luciaagarcia       | Lucia.Alfonso@alu.uclm.es|
|[Eduardo García Aparicio](https://github.com/eduardez) |     @eduardez    | Eduardo.Garcia14@alu.uclm.es
|[Manuel Villalba Montalbán](https://github.com/manuvillalba-uclm) |     @manuvillalba-uclm    | Manuel.Villalba@alu.uclm.es |

### References
- [DrivenData competition](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/)
- [Introduction to Time Series Forecasting with Python](https://www.studocu.com/row/document/tsinghua-university/econometrics-2/other/introduction-to-time-series-forecasting-with-python-how-to-prepare-data-and-develop-models-to-predict-the-future-by-jason-brownlee-z-lib/8650098/view)
- [How to Backtest Machine Learning Models for Time Series Forecasting](https://machinelearningmastery.com/backtest-machine-learning-models-time-series-forecasting/)
