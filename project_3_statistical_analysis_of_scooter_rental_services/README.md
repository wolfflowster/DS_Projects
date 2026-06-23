# Research of the GoFast Scooter Rental Service

## Description: 
I have data on users of the GoFast scooter rental service from several cities, as well as detailed information about their trips. 
The task is to perform a comprehensive analysis of the data, test key business hypotheses, calculate revenue, 
and provide marketing recommendations to increase the number of profitable subscribers.
## Tools: 
Pandas, Matplotlib, Seaborn, Plotly, NumPy, SciPy (ttest_ind, ttest_rel, binom, norm), Datetime. 
Exploratory data analysis, data preprocessing, data merging, visualization, statistical hypothesis testing, binomial and normal distribution approximations.
## Goal: Analyze user behavior, compare subscribers and non-subscribers, test hypotheses about trip duration, 
distance, revenue, and evaluate the effectiveness of marketing promotions (promo codes and push notifications).
## Conclusions:
Users with a subscription are more profitable for the company: they make longer trips on average and generate higher monthly revenue.
The average trip distance for subscribers is optimal (does not exceed 3130 meters) from the point of view of scooter wear.
To achieve at least 100 subscription renewals with ~95% probability, a minimum of 1161 promo codes should be distributed.
The probability that no more than 399.5 thousand users will open 1 million push notifications is approximately 15.37%.
Short trips (< 500 m and < 5 min) require additional analysis as they may indicate cancellations.

## Project Status: Completed.


# Исследование сервиса аренды самокатов GoFast

## Описание: В распоряжении имеются данные о пользователях сервиса аренды самокатов GoFast из нескольких городов, 
а также подробная информация об их поездках. Необходимо провести всесторонний анализ данных, проверить ключевые бизнес-гипотезы, 
рассчитать выручку и дать маркетинговые рекомендации для увеличения количества выгодных подписчиков.
## Инструменты: 
Pandas, Matplotlib, Seaborn, Plotly, NumPy, SciPy (ttest_ind, ttest_rel, binom, norm), Datetime. 
Исследовательский анализ данных, предобработка данных, объединение таблиц, визуализация, 
статистическая проверка гипотез, аппроксимация биномиального и нормального распределений.
## Цель: 
Проанализировать поведение пользователей, сравнить подписчиков и пользователей без подписки, 
проверить гипотезы о продолжительности поездок, расстоянии, выручке и оценить эффективность маркетинговых акций (промокоды и push-уведомления).
## Выводы:
Пользователи с подпиской более выгодны для компании: они совершают более продолжительные поездки в среднем и приносят большую помесячную выручку.
Среднее расстояние поездки у подписчиков оптимально (не превышает 3130 метров) с точки зрения износа самокатов.
Для достижения минимум 100 продлений подписки с вероятностью ~95% необходимо разослать минимум 1161 промокод.
Вероятность того, что из 1 млн push-уведомлений откроют не более 399,5 тыс. пользователей — примерно 15,37%.
Короткие поездки (< 500 м и < 5 мин) требуют дополнительного анализа, так как могут указывать на отмены.

## Статус проекта: Завершен.
