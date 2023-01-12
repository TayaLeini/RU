# Свод по проектам

Ссылка | Направление | Цель | Отработанные навыки | Используемые библиотеки
------------- |------------- |---------------- | ---------------- | -----------------------
[Прогнозирование стоимости б/у автомобилей (регрессия)](https://github.com/TayaLeini/RU/blob/main/сar_price_predict/сar_price_predict_regression.ipynb) | Machine learning (градиентный бустинг, регрессия) | Обучить модель для определения рыночной стоимости автомобиля. | Выполнена предобработка (удалены дубликаты, замены пропуски, аномалии), проведен анализ. Проведено обучение и предсказание моделей: LightGBM, Linear Regression, Random Forrest  с параметрами по умолчанию и  с использованием гиперпараметров, подобранных через кросс-вадицаию GridSearch,optuna. Выбрана лучшая модель по результатам метрики RMSE и времени обучения. | `Pandas`, `NumPy`, `Sklearn`, `CatBoost`, `GridSearchCV`, '`LightGBM`, `CatBoost`, `Seaborn`, `OrdinalEncoder`, `OHE`, `optuna`, `Random Forrest`
[Предсказание цены на недвижимость в Мадриде (регрессия)](https://github.com/TayaLeini/RU/blob/main/Madrid_estate_regression/Madrid_estate.ipynb) | Machine learning (градиентный бустинг, регрессия) | Определить лучшую модель для предсказания стоимости рыночной недвижимости в Мадриде | На валидационной выборке модель CatBoostRegressor показаала резульата MAE 4335 евро, на тестовой выборке 4053 евро. При выполнении выполнена предобработка (пропуски, аномалии, выбросы, дубликаты), проведен анализ, через кросс-валидацию проверены 10 моделей, для лучшей подобраны гиперпараметры с помощью optuna  | `Linear Regression`, `Bayesian Ridge Regression`, `LightGBM`, `SVR`, `Decision Tree Regression`, `Random Forest`, `XGB Regression`, `Grad Boost`, `Cat Boost`, `matplotlib`, `seaborn`, `pandas`, `sklearn`, `plotly`, `ОrdinalEncoder`, `RepeatedKFold`, `optuna`
[Предсказание увольнений сотрудников (классификация)](https://github.com/TayaLeini/RU/blob/main/Madrid_estate_regression/Madrid_estate.ipynb) | Machine learning (градиентный бустинг, регрессия) | Определить лучшую модель для предсказания стоимости рыночной недвижимости в Мадриде | На валидационной выборке модель CatBoostRegressor показаала резульата MAE 4335 евро, на тестовой выборке 4053 евро. При выполнении выполнена предобработка (пропуски, аномалии, выбросы, дубликаты), проведен анализ, через кросс-валидацию проверены 10 моделей, для лучшей подобраны гиперпараметры с помощью optuna  | `Linear Regression`, `Bayesian Ridge Regression`, `LightGBM`, `SVR`, `Decision Tree Regression`, `Random Forest`, `XGB Regression`, `Grad Boost`, `Cat Boost`, `matplotlib`, `seaborn`, `pandas`, `sklearn`, `plotly`, `ОrdinalEncoder`, `RepeatedKFold`, `optuna`
