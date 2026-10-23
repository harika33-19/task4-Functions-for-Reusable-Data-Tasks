# task4-Functions-for-Reusable-Data-Tasks

## Overview
Create reusable Python functions for calculations, data transformation, and simple statistical operations.

## Objectives
- Learn how to define and call Python functions.
- Use parameters and return values.
- Calculate mean, maximum, minimum, and percentage.
- Improve code reusability and organization.

## Tools
- Python
- Jupyter Notebook / Google Colab

## Functions Implemented

### 1. Calculate Mean
```python
def calculate_mean(values):
    if len(values) == 0:
        return 0
    return sum(values) / len(values)
```

### 2. Find Maximum
```python
def find_maximum(values):
    if len(values) == 0:
        return None
    return max(values)
```

### 3. Find Minimum
```python
def find_minimum(values):
    if len(values) == 0:
        return None
    return min(values)
```

### 4. Calculate Percentage
```python
def calculate_percentage(part, total):
    if total == 0:
        return 0
    return (part / total) * 100
```

### 5. Convert Celsius to Fahrenheit
```python
def celsius_to_fahrenheit(celsius):
    return (celsius * 9 / 5) + 32
```

### 6. Apply Discount
```python
def apply_discount(price, discount_percent):
    return price - (price * discount_percent / 100)
```

### 7. Function Parameters and Return Values
```python
def add_numbers(a, b):
    return a + b

print(add_numbers(10, 20))
```

## Sample Usage
```python
marks = [85, 90, 78, 92, 88]

print("Mean:", calculate_mean(marks))
print("Maximum:", find_maximum(marks))
print("Minimum:", find_minimum(marks))
print("Percentage:", calculate_percentage(450, 500))
print("Temperature:", celsius_to_fahrenheit(25))
print("Discounted Price:", apply_discount(2000, 10))
```

## Key Learnings
- Functions help avoid repeated code.
- Parameters accept input values.
- Return statements provide results for reuse.
- Functions make programs easier to read, test, and maintain.

## Conclusion
This task demonstrates how Python functions can simplify calculations and support reusable data science workflows.
