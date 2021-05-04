# Проекты курса "Специалист по Data Science" от Яндекс

Данные проекты были выполнены в ходе обучения профессии "Специалист по Data Science" в Яндекс.Практикуме. Проекты расположены в хронологическом порядке, и можно отследить как растет количество навыков, которыми я владею. Оригинальные описания проектов были сокращены и переформулированы. 

|Название проекта  | Описание | Используемые библиотеки |
| :------------- | :------------- |:-------------|
| [1. Музыка больших городов](01_yandex_music)  | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени и дня недели. Подготовка, очистка данных, исследовательский анализ данных.  | *pandas* |
| [2. Исследование надежности заемщиков](02_credit_scoring) | Исследование как семейное положение, количество детей и доход влияют на возврат кредита в срок. Подготовка, очистка данных, исследовательский анализ данных, категоризация переменных | *pandas*, *pymystem3* |
|[3. Исследование объявлений о продаже квартир](03_real_estate_prices)| Определение рыночной цены недвижимости в Санкт-Петербурге и окрестностях, и определение параметров на нее влияющих, чтобы создать систему для отслеживания аномалий и мошеннической деятельности. Подготовка данных, добавление фичей, исследовательский анализ, корреляция между ценой квартир и различными фичами. | *pandas*, *matplotlib.pyplot*,  *plotly.express* |
| [4. Определение перспективного тарифа для телеком компании](04_telecom_tariff) | Анализ поведения пользователей двух тарифов телеком компании в целях определения более выгодного для компании тарифа. В процессе работы был проведен статистический анализ, проверены гипотезы об отличии выручки за пользователей двух тарифов и пользователей из Москвы и регионов. Подготовка, очистка данных, добавление фичей. | *pandas*, *matplotlib.pyplot*,  *plotly*, *numpy*, *scipy.stats* |
|[5. Исследование популярности компьютерных игр](05_games)| Прогнозирование популярности игры в зависимости от жанра и платформы, основываясь на исторических данных. Исследовательский анализ данных, составление портрета пользователя каждого региона, проверка гипотез о равенстве рейтингов игр на двух платформах и игр двух разных жанров. | *pandas*, *matplotlib.pyplot*,  *plotly*, *numpy*, *scipy.stats* |
| [6. Рекомендация тарифов](06_users_classification)| Построение модели машинного обучения для классификации пользователей тарифов мобильного оператора. Обучение проводится на исторических данных с поведением  пользователей, модель будет использоваться для рекомендаций пользователям подходящего тарифа. Подготовка и очистка данных здесь не требовалась. Следующие модели были протестированы: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression. | *pandas*, *sklearn*, *numpy* |
| [7. Моделирование оттока клиентов банка](07_bank_customer_churn_modeling) | Построение модели машинного обучения для предсказания ухода клиента из банка, основываясь на исторических данных о поведении клиентов. Подготовка, очистка данных, преобразование категориальных переменных в качественные методом OHE, масштабирование количественных переменных, борьба с дисбалансом классов (взвешивание классов, уменьшение и увеличение выборки). Были простестированы разные модели (DecisionTreeClassifier, RandomForestClassifier, LogisticRegression), оптимальные гиперпараметры были найдены с помощью GridSearchCV, считались F1-мера и AUC-ROC. | *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot* |
| [8. Выбор локации для скважины](08_oil_extraction_location) | Построение модели машинного обучения для определения наиболее прибыльного региона для бурения скважины на основе данных о 3ех регионах с 10000 месторождениями в каждом. Имеются описания каждой скважины и количество нефти в ней, бюджет на освоение, стоимость барреля нефти. Прибыль и риски проанализированы техникой Bootstrap. Использовалась LinearRegression. | *pandas*, *sklearn*, *numpy*, *scipy.stats*, *seaborn*, *matplotlib.pyplot* |
| [9. Коэффициент восстановления золота из золотосодержащей руды](09_gold_recovery) | Построение модели машинного обучения для предсказания коэффициента восстановления золота из руды. Имеется большое количество параметров сложного технологического процесса, состоящего из 3 этапов: флотация и 2 этапа очистки. Данные нужно подготовить, проверить на наличие аномалий. Использовались модели: LinearRegression, DecisionTreeRegressor, RandomForestRegressor. Оптимальные параметры находились с помощью кросс-валидации. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |
| [10. Защита персональных данных клиентов](10_customer_data_encryption) | Разработка метода шифрования данных посредством умножения признаков на обратимую матрицу. Корректность метода математически обоснована. Показано, что качество линейной регрессии на преобразованных данных не меняется. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |
| [11. Определение стоимости автомобилей](11_car_prices_boosting) | Построение модели машинного обучения для предсказания рыночной цены автомобиля на основе исторических данных. Данные были подготовлены, категориальные данные закодированы с помощью OrdinalEncoder. Использовались модели: Gradient Boosting, Random Forest. Оптимальные параметры были найдены с помощью GridSearchCV. Были построены графики важности факторов. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot*, *plotly*, *lightgbm* |
| [12. Прогнозирование количества заказов такси](12_time_series) | Построение модели машинного обучения для временных рядов, а именно для прогнозирования количества заказов такси на следующий час. Был проведен ресемплинг данных по 1 часу, были изучены тренды и сезонность. Добавлены новые фичи: календарные признаки, отстающие значения и скользящее среднее. Использовались следующие модели: Gradient Boosting (CatBoost), Linear Regression. Оптимальные параметры были найдены с помощью GridSearchCV. | *statsmodels.tsa.seasonal*, *catboost*, *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot* |
| [13. Анализ тональности текста](13_nlp) | Разработка модели машинного обучения для обработки текстов, а именно анализ их тональности. Тексты были очищены от лишних символов и лемматизированы с помощью Spacy. Были использованы следующие модели: CatBoost, TF-IDF + Logistic Regression | *catboost*, *pandas*, *sklearn*, *re*, *nltk* |
| [14. Аналитика предпочтений клиентов авиакомпании](14_sql) | Анализ полетов клиентов в разные города в сентябре 2018 года. Изучение базы данных и выгрузка необходимой информации.| *pandas*, *PostgreSQL* |


                                                          
















