a = float(input("Введите 1  число:"))
b = float(input("Введите 2  число:"))

oper = input('Что сделать ? (+, -, *, /):')
result = int()

if oper == "-":
    result = a - b
elif oper == "+":
    result = a + b
elif oper == "*":
    result = a * b
elif oper == '/':
    result = a / b

print(f'Результат: {result}')

