# Task-12.7.3
per_cent={'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = int(input("Введите требуемую сумму под проценты:"))
ТКБ = int((per_cent['ТКБ'])*(money/100))
СКБ = int((per_cent['СКБ'])*(money/100))
ВТБ = int((per_cent['ВТБ'])*(money/100))
СБЕР = int((per_cent['СБЕР'])*(money/100))
deposit = [ТКБ, СКБ, ВТБ, СБЕР]
print(deposit)
i = max(iter(deposit))
print("Maximal", i)
