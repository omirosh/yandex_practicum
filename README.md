# Проекты курса "Специалист по Data Science" от Яндекс

Данные проекты были выполнены в ходе обучения профессии "Специалист по Data Science" в Яндекс.Практикуме. Проекты расположены в хронологическом порядке, и можно отследить как растет количество навыков, которыми я владею. Оригинальные описания проектов были сокращены и переформулированы. 

|Название проекта  | Описание | Используемые библиотеки |
| :------------- | :------------- |:-------------|
| [Музыка больших городов](yandex_music)  | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени и дня недели. Подготовка, очистка данных, исследовательский анализ данных.  | *pandas* |
| [Исследование надежности заемщиков](credit_scoring) | Исследование как семейное положение, количество детей и доход влияют на возврат кредита в срок. Подготовка, очистка данных, исследовательский анализ данных, категоризация переменных | *pandas*, *pymystem3* |
|[Исследование объявлений о продаже квартир](real_estate_prices)| Определение рыночной цены недвижимости в Санкт-Петербурге и окрестностях, и определение параметров на нее влияющих, чтобы создать систему для отслеживания аномалий и мошеннической деятельности. Подготовка данных, добавление фичей, исследовательский анализ, корреляция между ценой квартир и различными фичами. | *pandas*, *matplotlib.pyplot*,  *plotly.express* |
| [Определение перспективного тарифа для телеком компании](telecom_tariff) | Анализ поведения пользователей двух тарифов телеком компании в целях определения более выгодного для компании тарифа. В процессе работы был проведен статистический анализ, проверены гипотезы об отличии выручки за пользователей двух тарифов и пользователей из Москвы и регионов. Подготовка, очистка данных, добавление фичей. | *pandas*, *matplotlib.pyplot*,  *plotly*, *numpy*, *scipy.stats* |
|[Исследование популярности компьютерных игр](games)| Прогнозирование популярности игры в зависимости от жанра и платформы, основываясь на исторических данных. Исследовательский анализ данных, составление портрета пользователя каждого региона, проверка гипотез о равенстве рейтингов игр на двух платформах и игр двух разных жанров. | *pandas*, *matplotlib.pyplot*,  *plotly*, *numpy*, *scipy.stats* |
| [Рекомендация тарифов](users_classification)| Построение модели машинного обучения для классификации пользователей тарифов мобильного оператора. Обучение проводится на исторических данных с поведением  пользователей, модель будет использоваться для рекомендаций пользователям подходящего тарифа. Подготовка и очистка данных здесь не требовалась. Следующие модели были протестированы: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression. | *pandas*, *sklearn*, *numpy* |
| [Моделирование оттока клиентов банка](bank_customer_churn_modeling) | Построение модели машинного обучения для предсказания ухода клиента из банка, основываясь на исторических данных о поведении клиентов. Подготовка, очистка данных, преобразование категориальных переменных в качественные методом OHE, масштабирование количественных переменных, борьба с дисбалансом классов (взвешивание классов, уменьшение и увеличение выборки). Были простестированы разные модели (DecisionTreeClassifier, RandomForestClassifier, LogisticRegression), оптимальные гиперпараметры были найдены с помощью GridSearchCV, считались F1-мера и AUC-ROC. | *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot* |
| [Выбор локации для скважины](oil_extraction_location) | Построение модели машинного обучения для определения наиболее прибыльного региона для бурения скважины на основе данных о 3ех регионах с 10000 месторождениями в каждом. Имеются описания каждой скважины и количество нефти в ней, бюджет на освоение, стоимость барреля нефти. Прибыль и риски проанализированы техникой Bootstrap. Использовалась LinearRegression. | *pandas*, *sklearn*, *numpy*, *scipy.stats*, *seaborn*, *matplotlib.pyplot* |
| [Коэффициент восстановления золота из золотосодержащей руды](gold_recovery) | Построение модели машинного обучения для предсказания коэффициента восстановления золота из руды. Имеется большое количество параметров сложного технологического процесса, состоящего из 3 этапов: флотация и 2 этапа очистки. Данные нужно подготовить, проверить на наличие аномалий. Использовались модели: LinearRegression, DecisionTreeRegressor, RandomForestRegressor. Оптимальные параметры находились с помощью кросс-валидации. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |










