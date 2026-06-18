# Assignment 3: Multiplication Table Generator

**Objective:** Practice loops and control flow.

## Task:
Write a program that takes a number as input and prints its multiplication table from 1 to 10.

## Example Output (for number 5):
```
5 × 1 = 5
5 × 2 = 10
5 × 3 = 15
5 × 4 = 20
5 × 5 = 25
5 × 6 = 30
5 × 7 = 35
5 × 8 = 40
5 × 9 = 45
5 × 10 = 50
```

## Solution Example:
```python
number = 5

for i in range(1, 11):
    result = number * i
    print(f"{number} × {i} = {result}")
```

## Hints:
- Use a for loop with range(1, 11)
- Multiply the number by the loop variable
- Use f-strings to format the output nicely
- The × symbol can be typed as part of the string