# Свод по проектам

Ссылка | Направление | Цель | Отработанные навыки | Используемые библиотеки
------------- |------------- |---------------- | ---------------- | -----------------------
[Прогнозирование стоимости б/у автомобилей (регрессия)](https://github.com/TayaLeini/RU/blob/main/сar_price_predict/сar_price_predict-3.ipynb) | Machine learning (градиентный бустинг, регрессия) | Обучить модель для определения рыночной стоимости автомобиля. | Выполнена предобработка (удалены дубликаты, замены пропуски, аномалии), проведен анализ. Проведено обучение и предсказание моделей: LightGBM, Linear Regression, Random Forrest  с параметрами по умолчанию и  с использованием гиперпараметров, подобранных через кросс-вадицаию GridSearch,optuna. Выбрана лучшая модель по результатам метрики RMSE и времени обучения. | `Pandas`, `NumPy`, `Sklearn`, `CatBoost`, `GridSearchCV`, '`LightGBM`, `CatBoost`, `Seaborn`, `OrdinalEncoder`, `OHE`, `optuna`, `Random Forrest`
[Предсказание цены на недвижимость в Мадриде (регрессия)](https://github.com/TayaLeini/RU/blob/main/Madrid_estate_regression/Madrid_estate-3.ipynb) | Machine learning (градиентный бустинг, регрессия) | Определить лучшую модель для предсказания стоимости рыночной недвижимости в Мадриде | На валидационной выборке модель CatBoostRegressor показаала резульата MAE 4335 евро, на тестовой выборке 3775 евро. При выполнении сделана предобработка (пропуски, аномалии, выбросы, дубликаты), проведен анализ, через кросс-валидацию проверены 10 моделей, для лучшей подобраны гиперпараметры с помощью optuna  | `Linear Regression`, `Bayesian Ridge Regression`, `LightGBM`, `SVR`, `Decision Tree Regression`, `Random Forest`, `XGB Regression`, `Grad Boost`, `Cat Boost`, `matplotlib`, `seaborn`, `pandas`, `sklearn`, `plotly`, `ОrdinalEncoder`, `RepeatedKFold`, `optuna`
[Предсказание оттока клиентов (классификация)](https://github.com/TayaLeini/RU/blob/main/Churn%20Modelling/Churn_Modelling-3.ipynb) | Machine learning (градиентный бустинг, классификация) | Определить лучшую модель для предсказания оттока клиентов банка | На тестовой выборке модель RandomForrest показаала резульата F1 0,9. При выполнении проведен анализ, через кросс-валидацию проверены 3 модели, подобраны гиперпараметры с помощью optuna и GridSearch | `Logistic Regression`, `LightGBM`,  `Random Forest`,  `matplotlib`, `seaborn`, `pandas`, `sklearn`, `plotly`, `ОrdinalEncoder`, `RepeatedKFold`, `optuna`
