# Python Help Sheet

## Basic Python

### Basic Operators

Arithmetic Operators

- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division

Others
- Use round brackets `()` to specify order of operations.
- You may add spaces before and after operators to make expressions more readable, e.g. `(1 + 2) * 5` is the same as `(1+2)*5`.
- Anything that comes after the `#` is considered a comment and is ignored by IDLE.

### Strings

- Strings are enclosed by quote marks `''`.
- `+` joins two strings, e.g. `'python' + ' ' + 'cool'` evaluates to `'python cool'`.
- `*` repeats a string, e.g. `'gee' * 3` gives `'geegeegee'`
- You can mix and match them, e.g. `'b'+'a'*5` gives `'baaaaa'`

### Data Types

You should recognize different data types in python, which are treated differently by IDLE.

- Numbers
- Strings
- True/False values

Example of True/False values
- `5 < 5` gives the boolean `False`
- `5 == 5` gives the boolean `True`


### Variable

You can use variables to ask Python to remember values by using the `=` operator. 
You can also use `=` to update the value of existing variables.
For example, 
```python
greeting = 'howdy'  # greeting is assigned a value
new_greeting = greeting * 4  # IDLE recalls the stored value here
print(new_greeting)  # this will print 'howdyhowdyhowdyhowdy'
new_greeting = greeting + ' do?'  # the variable new_greeting is updated
print(new_greeting)  # this will print 'howdy do?'
```

Do not use variable names that start with a number.
