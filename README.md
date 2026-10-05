# Calculator

Простой калькулятор на Python.

## Установка

```bash
pip install -e .
```

## Запуск тестов

```bash
pytest
```

## Использование

```python
from calculator.core import add, subtract, multiply, divide, power

print(add(2, 3))        # 5
print(subtract(5, 2))   # 3
print(multiply(4, 3))   # 12
print(divide(10, 2))    # 5.0
print(power(2, 3))      # 8
```

## Структура проекта

```
calculator/
├── .gitignore
├── README.md
├── src/
│   └── calculator/
│       ├── __init__.py
│       └── core.py
└── tests/
    └── test_core.py
```
