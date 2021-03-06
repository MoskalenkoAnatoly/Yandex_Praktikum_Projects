# Прогнозирование оттока клиентов

## Если не грузится файл с проектом
https://nbviewer.jupyter.org/github/MoskalenkoAnatoly/Yandex_Praktikum_Projects/blob/main/6.%20Прогнозирование%20оттока%20клиентов/Project_6_classifier.ipynb

## Задача

На основе исторических данных спрогнозировать, уйдёт клиент из банка в ближайшее время или нет

## Данные

- уникальный идентификатор клиента
- фамилия
- кредитный рейтинг
- страна проживания
- пол
- возраст
- количество недвижимости у клиента
- баланс на счёте
- количество продуктов банка, используемых клиентом
- наличие кредитной карты
- активность клиента
- предполагаемая зарплата
- факт ухода клиента

## Библиотеки
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- sklearn

## Краткие выводы

- Чтобы провести исследование, нам было необходимо подготовить данные(разобраться с пропусками, удалить ненужные столбцы и "привести" категориальные признаки к нужному виду), проверить модели с различными параметрами и выявить, какая покажет лучший результат. Также мы рассмотрели различные методы борьбы с дисбалансом классов.
- Мы выяснили, что модель дерева случайного леса справилась лучше всех, а метод для борьбы с дисбалансом уменьшение выборки.
- И получили конечные результаты модели: F1 = 0.603 и ROC-AUC = 0.851. Результаты конечно не идеальные и есть куда стремиться.
