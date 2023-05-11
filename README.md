# Пример программы на Python для вычисления факториала числа

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5)) # выводит 120
