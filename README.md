# Прогноз числа Вульфа (число пятен на Солнце)

***
Постановка задачи
1. Найти и скачать данные по числам Вульфа https://en.wikipedia.org/wiki/Wolf_number .
2. Построить модель, предсказывающую число Вульфа через полгода.
3. Прислать ноутбук, который можно запустить сверху вниз, чтобы считать данные по числам Вульфа с диска, провести с ними нужные манипуляции, обучить модель, получить ее предсказания, вывести график, где предсказания модели будут наложены на фактические наблюдения из отложенной выборки.

Относительное число солнечных пятен $R$ вычисляется по формуле

$R=k(10g+s)$

*где:*
$s$ - количество отдельных пятен,
$g$ - число групп солнечных пятен, и
$k$ - коэффициент, зависящий от обсерватории или персональным коэффициентом уменьшения.

С 1 июля 2015 года применяется пересмотренная и обновленная международная серия чисел солнечных пятен.


Этапы решения

1. [Импорт библиотек подготовка данных](#1)
2. [Преобразование данных](#2)
3. [Модель ARIMA](#3)
