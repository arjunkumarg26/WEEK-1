```python
rows = 5

print("Lower Triangular Pattern:")
for i in range(1, rows + 1):
    print("* " * i)

print("\nUpper Triangular Pattern:")
for i in range(rows, 0, -1):
    print(" " * (rows - i) + "* " * i)

print("\nPyramid Pattern:")
for i in range(1, rows + 1):
    print(" " * (rows - i) + "* " * (2 * i - 1))
```
```markdown
This Python program prints three different star patterns using loops:
- Lower Triangular Pattern
- Upper Triangular Pattern
- Centered Pyramid Pattern


