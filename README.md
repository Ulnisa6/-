5-Вариант
1.a = [3, 8, 15, 2, 7, 6, 1, 12, 11, 4]

odd_numbers = [x for x in a if x % 2 != 0]

if odd_numbers:
    max_odd = max(odd_numbers)
    print("Максимум среди нечетных чисел:", max_odd)
else:
    print("В массиве нет нечетных чисел.")

2.A = [
    [1, 2, 3, 4],
    [5, 6, 7, 8],
    [9, 10, 11, 12],
    [13, 14, 15, 16]
]

secondary_diagonal = [A[i][3 - i] for i in range(4)]

max_secondary = max(secondary_diagonal)

print("Максимум по дополнительной диагонали:", max_secondary)
