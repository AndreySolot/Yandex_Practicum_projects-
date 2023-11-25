## Проверка гипотез по увеличению выручки в интернет-магазине. Оценка результатов A/B теста
### Задачи проекта 
- Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами.
### Описание 
- Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провеа анализ результатов A/B-теста, построила графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитала статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.
### Выводы
- Исходя из анализа стабильности кумулятивных метрик можем говорить о том, что в течении всего теста выручка стабильно увеличивается. За исключением выброса в группе В в августе. Такой же выброс мы наблюдаем и в графике о среднем чеке, так же в группе В. Скорее всего появились люди, которые заказывали несколько раз и люди заказывающие дорогие вещи.
- Из графика относительного изменения кумулятивного среднего количества заказов на посетителя группы B к группе A мы узнали, что в начале нашего теста группа B значительно проигрывала группе A, затем вырвалась вперёд. Потом группа В переживала небольшую стагнацию и затем снова постепенно росла.
- Проанализировав перцентили (95 и 99) опредилили грацицы допустимых значений. И подтвердили свои догадки об аномалиях.
- Статистически значимые различия по среднему кол-ву заказов между группами в «сырых» и в «очищенных» данных присутствуют.
- А вот статистически значимого различия по среднему чеку между группами в «сырых» и в «очищенных» данных нет.
- Было принято решение остановить тест и признать его успешным, так как целью проекта было - увеличение выручки, что мы и получили в группе В.
### Используемые библиотеки 
- Pandas, 
- Matplotlib, 
- SciPy,
- Numpy,