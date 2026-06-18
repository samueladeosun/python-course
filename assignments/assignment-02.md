# Assignment 2: Temperature Converter

**Objective:** Practice arithmetic operations and if/else statements.

## Task:
Write a program that converts temperature from Celsius to Fahrenheit using the formula:
```
F = (C × 9/5) + 32
```

Then classify the temperature:
- Below 0°C: "Freezing"
- 0-15°C: "Cold"
- 16-25°C: "Moderate"
- Above 25°C: "Warm"

## Example Input/Output:
```
Celsius: 20
Fahrenheit: 68.0
Classification: Moderate
```

## Solution Example:
```python
celsius = 20
fahrenheit = (celsius * 9/5) + 32

if celsius < 0:
    classification = "Freezing"
elif celsius <= 15:
    classification = "Cold"
elif celsius <= 25:
    classification = "Moderate"
else:
    classification = "Warm"

print(f"Celsius: {celsius}")
print(f"Fahrenheit: {fahrenheit}")
print(f"Classification: {classification}")
```

## Hints:
- Use variables for celsius and fahrenheit
- Remember the formula: F = (C × 9/5) + 32
- Use if/elif/else for classification