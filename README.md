# Учебные проекты Data Science (Анна Тахтай, г. Донецк)
*машинное обучение*
|№|Наименование проекта|Описание|Стек|
|---|----|-----|-----|
|1| [Выбор наиболее выгодного региона нефтедобычи](/geo_petrol_bootstrap) | Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Нужно построить модель для определения региона, где добыча принесёт наибольшую прибыль. | Python Pandas Scikit-learn бутстреп |
|2| [Прогноз количества вызовов такси на следующий час с использованием временных рядов](/taxi_time) | Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания. | Python Pandas Scikit-learn statmodels |
|3| [Обучение модели классификации комментариев](/toxic_comments_tfidf) | Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. | Python Pandas nltk tf-idf |
|4| [Определение возраста по фотографии](/photo_age) | Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. Есть набор фотографий людей с указанием возраста. | Python Keras PIL |
|5| [Линейные модели в машинном обучении для прогноза удоя и вкуса молока](/cow_milk) | Для фермера надо построить 2 модели: для прогнозирования удоя коров и для прогнозирования вкуса молока (вкусное или нет). | Python Pandas Scikit-learn Matplotlib |

<!--
|1| [Прогноз снижения покупательской активности клиента интернет-магазина](/market_models) | Отчёт интернет-магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Нужно построить модель, которая предскажет вероятность снижения покупательской активности клиента в следующие три месяца. Имеются данные о поведении покупателя на сайте, о коммуникациях с покупателем и его продуктовом поведении, принесённой магазину выручке и времени, проведённом покупателем на сайте магазина. | Python Pandas Scikit-learn Matplotlib |
|2| [Прогноз удовлетворённости сотрудников работой / риска ухода сотрудника](/job_satisfaction) | Компания предоставила данные с характеристиками сотрудников компании. Среди них — уровень удовлетворённости сотрудника работой в компании, которая напрямую влияет на отток сотрудников. Внезапные увольнения несут в себе риски для компании, особенно если уходит важный сотрудник. Нужно построить модель 1, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика, и модель 2, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании. | Python Pandas Scikit-learn Matplotlib NumPy |
-->
