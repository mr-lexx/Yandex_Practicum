# Классификация комментариев
<a href='https://github.com/mr-lexx/Yandex_Practicum/blob/main/Toxic_words/wikishop.html'>HTML</a> | 
<a href='https://github.com/mr-lexx/Yandex_Practicum/blob/main/Toxic_words/wikishop.ipynb'>ipynb</a>
## Описание проекта
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Необходимо обучить модель классифицировать комментарии на позитивные и негативные. В распоряжении набор данных с разметкой о токсичности правок.<br>
Нужно постройте модель со значением метрики качества F1 не меньше 0.75. 

## Навыки и инструменты
- **os**
- **pandas**
- **numpy**
- **matplotlib**
- **wordcloud**
- **spacy**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.feature_extraction.text.**CountVectorizer**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**GridSearchCV**
- imblearn.over_sampling.**SMOTE**
- sklearn.linear_model.**LogisticRegression**
- sklearn.linear_model.**PassiveAggressiveClassifier**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- lightgbm.**LGBMClassifier**
- sklearn.dummy.**DummyClassifier**

## Общий вывод
На начальном этапе была проведена чистка строк и выделены самые важные слова, по которым можно строить прогнозы. Построена 2 облака слов для токсичных и нормальных комментариев, чтобы визуально выделить те слова, которые чаще всего используются в обеих категориях. Среди общего количества токсичных комментариев было чуть более 10%. Было рассмотрено несколько моделей машинного обучения, из которых лучше всего справились модель линейной регрессии и градиентного бустинга. Было принято решение обе протекстировать на тестовой выборке и сравнить с константной. Обе прошли испытания на тестовой выборке и на "адекватность". 

## Статус проекта
Завершён
