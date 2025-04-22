# README

## Python Code Explanation

This repository contains three Python programs demonstrating recursion, list comprehensions, and the use of `defaultdict` from the `collections` module.

### 1. Recursive Power Function
**File: `power_function.py`**
This script calculates the power of a number using recursion.
- The function `power(a, b)` recursively calculates `a^b`.
- The base condition is when `b == 0`, returning `1`.
- The user inputs values for `a` and `b`, and the result is displayed.

**Example Input & Output:**
```
Enter base (a): 6
Enter exponent (b): 5
6 to the power of 5 is 7776
```

---

### 2. List of Squares
**File: `squares_list.py`**
This script generates and prints the squares of numbers from `1` to `30` using list comprehension.
- The function `squares_list()` generates the list `[x**2 for x in range(1, 31)]`.
- The list is then printed to the console.

**Example Output:**
```
[1, 4, 9, 16, 25, 36, 49, ..., 841, 900]
```

---

### 3. Dictionary with Sets (defaultdict)
**File: `defaultdict_example.py`**
This script demonstrates the use of `defaultdict` to group values under specific keys.
- The function `create_dict(keys, values)` creates a dictionary where each key maps to a set of values.
- `defaultdict(set)` is used to automatically initialize missing keys with empty sets.

**Example Input & Output:**
```python
keys = ['Class-V', 'Class-VI', 'Class-VII', 'Class-VIII']
values = [1, 2, 2, 3]
output_dict = create_dict(keys, values)
print(output_dict)
```
Output:
```
defaultdict(<class 'set'>, {'Class-V': {1}, 'Class-VI': {2}, 'Class-VII': {2}, 'Class-VIII': {3}})
```

---

## How to Run
1. Ensure you have Python installed (>= 3.x).
2. Run each script using:
   ```sh
   python filename.py
   ```
3. Follow the prompts or review the printed output.

---

## Dependencies
No external dependencies are required; these scripts use Python's built-in functionalities.

---

## License
This project is licensed under the MIT License.

---

## Author
Singampalli Yuva Chandrakanth
Happy Coding! 🚀
