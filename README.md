# Python-Assignment

This repository contains Python exercises focused on variables, data types, operators, expressions, and list manipulations.

## Tasks

### Task 1: Variables and Data Types

- **Create variables**:
  - `age`: an integer
  - `name`: a string
  - `is_student`: a boolean
  
  ```python
  age = 23
  name = "Osama"
  is_student = False
  
  print("Age:", age)
  print("Name:", name)
  print("Is Student:", is_student)
  print(name, "is Student:", is_student)
  ```

- **Perform operations**:
  - Add 25 to `age`
  - Concatenate `name` with `"Smith"`
  - Negate `is_student`

  ```python
  new_age = age + 25
  full_name = name + "Smith"
  negated_student_status = not is_student
  
  print("New Age:", new_age)
  print("Full Name:", full_name)
  print("Negated Student Status:", negated_student_status)
  ```

### Task 2: Expressions and Operators

- **Calculate area of a rectangle** (width = 5.5, height = 3.25):

  ```python
  width = 5.5
  height = 3.25
  area = width * height
  print("Area of rectangle:", area)
  ```

- **Convert Celsius to Fahrenheit**:

  ```python
  celsius = float(input("Enter temperature in Celsius:"))
  fahrenheit = (celsius * 9/5) + 32
  print("Temperature in Celsius:", celsius, "C")
  print("Temperature in Fahrenheit:", fahrenheit, "F")
  ```

- **Calculate the area of a circle** (using `π * radius^2`):

  ```python
  radius = float(input("Enter radius of the circle:"))
  area = 3.14159 * radius ** 2
  print("Area of circle:", area)
  ```

### Task 3: List Manipulation

- **Create a list of fruits**:

  ```python
  fruits = ["apple", "banana", "cherry", "date", "strawberry", "fig", "grape"]
  print("List of fruits:", fruits)
  ```

- **Remove first and last elements**:

  ```python
  fruits = fruits[1:-1]
  print("Updated fruits list:", fruits)
  ```

- **Replace second to fourth items**:

  ```python
  fruits[1:4] = ["kiwi", "lemon", "mango"]
  print("Updated fruits list:", fruits)
  ```

- **Find the length of the list**:

  ```python
  print("Number of fruits in the list:", len(fruits))
  ```

## How to Run

1. Clone this repository.
2. Open the Python files in any Python IDE or code editor.
3. Run each task's code to see the output.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
