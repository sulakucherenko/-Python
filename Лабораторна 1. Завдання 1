def calculate_x(a, b):
    if a > b:
        return a / b - 1
    elif a == b:
        return -25
    elif a < b:
        return (a**3 - 5) / a

try:
    a = float(input("Введіть значення a (додатнє число): "))
    b = float(input("Введіть значення b (додатнє число): "))

    if a <= 0 or b <= 0:
        print("Помилка: a та b повинні бути додатніми числами.")
    else:
        x = calculate_x(a, b)
        print(f"Результат X: {x}")
except ValueError:
    print("Помилка: введіть числові значення для a та b.")

input("\nНатисніть Enter, щоб завершити програму...")
