# Документація API
## Модуль Calculator

### Функція add()
```python
def add(a, b):
    """Додавання двох чисел"""
    return a + b
```

**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число

**Повертає:**
- `float`: Сума двох чисел

**Приклад:**
```python
result = add(5, 3)
print(result)  # Виведе: 8
```

### Функція subtract()
```python
def subtract(a, b):
    """Віднімання двох чисел"""
    return a - b
```

**Параметри:**
- `a` (float): Зменшуване
- `b` (float): Від’ємник

**Повертає:**
- `float`: Різниця двох чисел

**Приклад:**
```python
result = subtract(10, 4)
print(result)  # Виведе: 6
```

### Функція multiply()
```python
def multiply(a, b):
    """Множення двох чисел"""
    return a * b
```

**Параметри:**
- `a` (float): Множник
- `b` (float): Множник

**Повертає:**
- `float`: Добуток чисел

**Приклад:**
```python
result = multiply(6, 7)
print(result)  # Виведе: 42
```

### Функція divide()
```python
def divide(a, b):
    """Ділення двох чисел"""
    if b != 0:
        return a / b
    else:
        return "Помилка: ділення на нуль!"
```

**Параметри:**
- `a` (float): Ділене
- `b` (float): Дільник

**Повертає:**
- `float`: Результат ділення
- `str`: Повідомлення про помилку, якщо b = 0

**Приклад:**
```python
result = divide(10, 2)
print(result)  # Виведе: 5.0
```

### Функція power()
```python
def power(a, b):
    """Піднесення числа a до степеня b"""
    return a ** b
```

**Параметри:**
- `a` (float): Основа
- `b` (float): Степінь

**Повертає:**
- `float`: a піднесене до степеня b

**Приклад:**
```python
result = power(2, 3)
print(result)  # Виведе: 8
```

### Функція modulo()
```python
def modulo(a, b):
    """Остача від ділення"""
    if b != 0:
        return a % b
    else:
        return "Помилка: ділення на нуль!"
```

**Параметри:**
- `a` (float): Ділене
- `b` (float): Дільник

**Повертає:**
- `float`: Остача від ділення
- `str`: Помилка, якщо b = 0

**Приклад:**
```python
result = modulo(10, 3)
print(result)  # Виведе: 1
```
