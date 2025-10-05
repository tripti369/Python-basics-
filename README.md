# Python-basics-
# 1. Variables in Python
x = 10
name = "Anaisha"
print("x:", x)
print("name:", name)

# 2. Dynamic Typing
x = 5
print("\nAfter assigning integer, x:", x)
x = "God is great"
print("After assigning string, x:", x)

# 3. Data Types
age = 25                # int
price = 99.99           # float
city = "Delhi"          # str
is_active = True        # bool
fruits = ["apple", "banana"]      # list
point = (10, 20)        # tuple
colors = {"red", "blue"}          # set
user = {"name": "Tripti", "age": 30} # dict

print("\nData Types Examples:")
print("age (int):", age)
print("price (float):", price)
print("city (str):", city)
print("is_active (bool):", is_active)
print("fruits (list):", fruits)
print("point (tuple):", point)
print("colors (set):", colors)
print("user (dict):", user)

# 4. Type Checking
print("\nType Checking:")
print("type(age):", type(age))
print("isinstance(age, int):", isinstance(age, int))

# 5. Type Conversion
print("\nType Conversion:")
num_str = "10"
converted_int = int(num_str)
print(f'int("{num_str}") →', converted_int)

num = 123
converted_str = str(num)
print(f'str({num}) →', converted_str)

letters = list("abc")
print('list("abc") →', letters)

student_age = 10
print("\nDescriptive Variable Name Example: student_age =", student_age)
