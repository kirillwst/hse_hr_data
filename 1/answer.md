Проблемы в исследуемом датасете:

1. Некоторые строчки являются пустыми в поле «Age»  – это может исказить статистические данные если мы попытаемся узнать выживаемость по возрасту. Исправить невозможно, но есть альтернатива: 
         1. Выделить в отдельную группу как «Неизвестные» 
         2. Используя инструменты предиктивной аналитики попытаться определить приблизительные значения, 

2. Также, некоторые значения столбца «Age» имеют десятичные значения, а подавляющая часть значений этого столбца не имеет их. Необходимо привести к округлению. 
3. Значения в столбце Fare имеют разное форматирование ячеек: "число" и "текст", необходимо привести к единому формату. 
4. Много пропущенных значений в столбце «Cabin» - исправить в готовом датасете невозможно. Необходимо изучить причина следственные связи возникновения таких пропусков на стадии внесения данных. 

Решение : https://docs.google.com/spreadsheets/d/1KuUzv_9U7i7eEzHQ07goQacQLVN4ybdsP8mXfbGP0aw/edit?usp=sharing

Шансы на выживание: 

Леонардо Ди Каприо - Мужчина, едет в крошечной каюте 3 класса - 13,54%
Кейт Уинслет - Женщина, едет в комфортабельной каюте 1 класса - 96,81%
