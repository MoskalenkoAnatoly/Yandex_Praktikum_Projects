
# Определение температуры для выплавки стали

## Если файл с проектом не грузится


## Задача

Построить модель, которая по данным будет предсказывать температуру

## Данные

Показания с замерами

## Библиотеки

- pandas
- numpy
- matplotlib.pyplot
- sklearn
- catboost 
- lightgbm

## Краткие выводы

Среди всех обученных моделей самый лучший результать показала CatBoostRegressor, с MAE = 5.715. При обучении CatBoostRegressor самым важным для неё признаком была начальная температура стали поступающей на обработку. Следом "идёт" суммарная активная мощность в партии, а затем продолжительность нагрева.





