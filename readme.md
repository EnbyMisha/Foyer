# L1 | Data types
## Data and their types
```python
# string / str
word = "one"

# integer / int
number = 1

# float
decimal = 1.2

# boolean / bool
answer = True

# character / char
letter = 'o'
```
Python utilises 5 basic `primitive data types`. While you may not immediately notice any difference between `1` as an `str` and `1` as an `int`, aka `"1"` versus `1`- there is a notable difference behind the scenes. This is because data types show machines how to treat our data. This means that `"1"` would have different behaviours compared to `1`.
# L2 | Inputs Outputs and Variables
## Storing input in a variable
```python
name=input("What's your name? ")
```
In the above example, we create a variable called `name` and request a user-response to store within it. This is achieved via the `input` method.
## Outputing data from our Variables
```python
print(f"Wow, {name} is such a sweet name!")
```
Here we use the `print` method to display data in the `console`. `{name}` references our `name` variable and will be replaced with `name`s value.
## Challenge
Attempt to create a basic madlib game using what you have learned.