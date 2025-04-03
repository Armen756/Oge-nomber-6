# Oge-nomber-6

def a():
    global yes_count, no_count  # Используем глобальные переменные для подсчёта
    try:
        x = int(input("Введите число x: "))
        y = int(input("Введите число y: "))

        if 17 >= x > y:
            print("Yes")
            yes_count += 1
        else:
            print("No")
            no_count += 1
    except ValueError:
        print("Ошибка: введите целые числа.")

# Счётчики Yes и No
yes_count = 0
no_count = 0

n = 9
for _ in range(n):
    a()

print(f"Количество 'Yes': {yes_count}")
print(f"Количество 'No': {no_count}")
print("Finish Process💩💀🙈🙉")

