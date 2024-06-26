### Введение
Для добывающей компании нужно решить, где бурить новую скважину.
Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Необходимо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль и проанализировать возможную прибыль и риски.
Шаги для выбора локации:
1. В избранном регионе ищут месторождения, для каждого определяют значения признаков;
2. Строят модель и оценивают объём запасов;
3. Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
4. Прибыль равна суммарной прибыли отобранных месторождений.

### Выводы
С помощью техники Bootstrap из 500 скважин мы выбрали 200 лучших. Среди регионов оказался лучшим регион 1:
- Средняя прибыль скважен Топ-200 = 467 млн. рублей.
- Доверительный интервал лежит между 77 - 859 млн. рублей.
- Риск убытков составляет = 1.10%,  что меньше 2,5%, заявленных в ТЗ.
