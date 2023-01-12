# Variables

Declare variables like local variables in Ruby

`name = "Alina"`

console.log in Python is `print(something)`
​

# Data Types

## String

Ex. 1
`string = "my string"`
Ex. 2
`string = 'my single string'`
**String interpolation**
`print(f"This string is {string}")`
**Length of a string**
`len(string)`
**Absolutely worthless, but cool**
`"Hello " "world!"`
​

## Integer

Ex. 1
`score = 100`
​

## Boolean

In Python they start with capital letter

`facts = True`

`not_facts = False`
​

## None

This is null/nil
​

## List

They work like array data type in other languages

`fruits = ['apple', 'pear', 'tomato']`

`fruits.append('banana')`
​

```python
big_fruits = map(uppercase, fruits)
# big_fruits is currently a map object and not ready to be sent back to client
list(big_fruits)
```

The Multiple Assignment Trick

```python
cat = ['fat', 'gray', 'loud']
size, color, disposition = cat
```

​

## Tuples

Work like arrays but they are immutable. You define tuples with parenthesis

`frozen_fruits = ('apple', 'pear', 'tomato')`
​

You cannot change anything in the above tuple. These are more memory efficient, but you cannot change them later!
​

## Dictionaries

This is the Ruby Hash. The JavaScript Object.

```python
user = {'email': 'michael@example.com', 'password': '11111111'}
```

​
​

# Functions

`def` keyword followed by the function name, parenthesis and a colon. Functions require `()` to be invoked, as in JavaScript and languages designed by sane people.
​

```python
def uppercase(s):
    return s.upper()
```

### View an object's type

```python
# 1st method
type(user)
​
# 2nd method
user.__class__.__name__
```

​
​

### Typecasting

You can typecast objects and data by calling the method of that data type

```
str()
int()
list()
bool()
float()
dict()
```

​

### Operating in Python

Python uses the following keywords when operating on data:

```python
is # checks for is-ness
and
or
not
in
!=
== # checks for equality
```
