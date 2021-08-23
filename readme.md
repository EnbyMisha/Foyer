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
Python utilises 5 basic **primitive data types**. While you may not immediately notice any difference between `1` as an `str` and `1` as an `int`, aka `"1"` versus `1`- there is a notable difference behind the scenes. This is because data types show machines how to use our data. This means that `"1"` would have different behaviours to `1`.
# L2 | Inputs Outputs and Variables
## Storing input in a variable
```python
name=input("What's your name? ")
```
In the above example, we create a `variable` called `name` and request a user-response to store within it. This is achieved via the `input` method.
## Outputing data from our Variables
```python
print(f"Wow, {name} is such a sweet name!")
```
Here we use the `print` method to display data in the `console`. `{name}` references our `name` variable and will be replaced with `name`s value.
## Challenge
+ Play a madlib game online
+ Create a madlib game
# L3 | Selection
## If Elif Else
```python
if name == "Misha":
  print("Best girl ~ x3")
elif name == "Melody":
  print("Busy playing Leauge of Legends)
else:
  print("A person who exists")
```
Sometimes we may only wish to run code segments under specific conditions. We do this using `selection`. The above example of selection demonstates the usage of `if`, `elif` and `else`.

`if` indicates we wish to check an initial `condition`, as such we must specify our condition to check. Here that is whether `name` is equal(`==`) to `"Misha"`. When ran, the program will assess whether are condition is `True` or `False`. If the `condition` evaluates to `True`, our customised message will be displayed.

In the event you would like to do something else under similar conditions when our initial conditions are not met, we use the else-if(`elif`) statement. `elif` works much like `if`, safe for that it must always be used **after** `if`. Hence the name **else-if**.

If you would like your program to respond differently when **no conditions are met**, you will use the `else` statement. The `else` statement is used after your `if` statement **or** if (if any are used) `elif` statements.

While you may use any number of `elif`s in a code block, you may only use one `if` at the start of the block, and one `else` at the end of the block.
## Multiple conditions
```python
sex = input("Are you male or female? ")
gender = input("What's your gender? ")
age = int(input("How old are you? "))
 
if (age >= 18) and (sex == "male" and gender == "male" or sex == "female" and gender == "male"):
  print("Welcome to the club")
else:
  print("You're not welcome here")
```
## Challenge
+ Attempt to understand the above code
+ Using selection create a basic quiz with 10 questions