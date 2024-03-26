# Calculator

A simple calculator package providing basic arithmetic operations. This project was created to gain experience in publishing Python packages to the PyPI repository.

## Installation

Install the package using pip:

pip install -i https://test.pypi.org/simple/ my_calculator1

python
Copy code

## Usage

```python
from my_calculator1 import Calculator

# Create a new calculator
calc = Calculator()

# Add two numbers
result = calc.add(2, 3)
print(result)  # Output: 5

# Add a single number to the calculator's memory
result = calc.add(2)
print(result)  # Output: 7

# Other available operations: subtract, multiply, divide, nth_root

# Reset the calculator
calc.reset()

```

# Methods
- Calculator(): Initializes the calculator with a memory of 0.
- add(num1: Optional[float], num2: Optional[float] = None) -> float: Adds two numbers or a single number to memory.

- subtract(num1: Optional[float], num2: Optional[float] = None) -> float: Subtracts two numbers or a single number from memory.

- multiply(num1: Optional[float], num2: Optional[float] = None) -> float: Multiplies two numbers or a single number with memory.

- divide(num1: Optional[float], num2: Optional[float] = None) -> float: Divides memory by a number or divides two numbers.

- nth_root(root: int, num1: Optional[float] = None, num2: Optional[float] = None) -> float: Takes the nth root of a number (stores in memory) or takes the nth root of two numbers.

- reset() -> float: Resets memory to 0.

Project Notes
This package was developed as an exercise in understanding the process of creating and publishing Python packages on the Python Package Index (PyPI).
