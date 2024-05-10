# Прогнозирования оттока клиентов оператора
<a href='https://github.com/mr-lexx/Yandex_Practicum/blob/main/Outflow_forecasting/Final_YP.html'>HTML</a> | 
<a href='https://github.com/mr-lexx/Yandex_Practicum/blob/main/Outflow_forecasting/Final_YP.ipynb'>ipynb</a>
# Постановка задачи
Необходимо научиться выделять тех клиентов компании, которые могут покинуть компанию. Найти возможные причины уходы, чтобы иметь возможноть удержать их.

# Навыки и инструменты
- **python**
- **os**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **phik**
- **shap**
- imblearn.over_sampling.**SMOTE**
- sklearn.compose.**make_column_transformer**
- sklearn.model_selection.**GridSearchCV**
- sklearn.**pipeline**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- lightgbm.**LGBMClassifier**
- catboost.**CatBoostClassifier**
- sklearn.dummy.**DummyClassifier**

# Общий вывод
После предварительной обработки и анализа полученных данных были выявленые некоторые закономерности у тех клиентов, которые перестали пользоваться услугами компании. Из 4 обученных моделей была выбрана самая эффективная, а также были выделены 5 самых важных признаков.
