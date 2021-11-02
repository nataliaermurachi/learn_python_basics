# learn_python_basics
> **Comments** - important for documentation, providing context, help to understand te code faster, ignore some lines(*not run by the computer*)
Everithing after # is interpreted as a comment:

` # This is a comment in python`

> **print()** - a function that tells a computer to talk, the message needs to be surrounded by quotes

`print("Hello world!")`

> **Variables** - a method of storing data for reuse. We *assign* variables in python by using the equals sign (` = ` )

`message_string = "Hello World"`

> **Errors** - mistakes in code even logical or syntactic, also called *bugs*: 
* `SyntaxError` - something wrong with the way your program is written

```
File "script.py", line 1
    print('This message has mismatched quote marks!")
                ^
```

* `NameError` - occurs when the Python interpreter sees a word he doesn't recognize

```
SyntaxError: EOL while scanning string literal
```

> **Concatenation** - the process of combining two or more strings, resulting with creation of a new string. 

`print("Hello" + " " + "World")  -> #Hello World!` 

To concatenamte a string with a number we must to convert the number to a string using `str()` function :

```
birthday_string = "I am "
age = 29
birthday_string_2 = " years old today!"
 
full_birthday_string = birthday_string + str(age) + birthday_string_2
 
print(full_birthday_string) # Prints "I am 10 years old today!"
```
> **+= operator** - a shortcut for updating variables by adding the curent value with the number specified in the variable:

```
nr_miles = 12
nr_miles += 2
print(nr_miles) #14
```

> **Multi-line strings** - to use strings with multi lines in Python we can use `"""` or `'''`

```
multi_line_var = """
Tis is a multi -
line 
string
"""
```
