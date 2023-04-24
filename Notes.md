# Learning-Python
My first study in learning Python

A string is just a bunch of letters and words that we want to use in our program. We can use strings to say hello or write a message. Sometimes we want to put two messages on different lines. To do that, we use a special code that tells the computer to start a new line. It looks like this: "\n". It's like hitting the "enter" key on a keyboard. We can use this code inside our strings to make them look better. 

Here's an example of a string in Python:

```
my_string = "Hello, world!"
print(my_string)

```

This code would output:

```
Hello, world!

```

The variable `my_string` is assigned the value of `"Hello, world!"`, which is a string. The `print()` function is then used to display the contents of the variable `my_string` in the console.

To create a new line within a single string in Python, you can use the escape sequence `\n`. Here's an example:

```

print("Hello, world!\nHello, world!")

or

my_string = "Hello,\nworld!"
print(my_string)

```

This code would output:

```
Hello,
world!

```

The `\n` tells Python to start a new line within the string.

### ******************************************STRING CONCANTENATION******************************************

String concatenation is the process of combining two or more strings together into a single string. In Python, you can use the `+` operator to concatenate strings. Here's an example:

```
first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name
print(full_name)
```

This code would output:

```
John Doe

```

In this example, we first define two strings `first_name` and `last_name`. We then use the `+` operator to concatenate them together with a space in between. The resulting string is assigned to the variable `full_name`, which is then printed to the console.

You can also use the `+=` operator to concatenate strings. Here's an example:

```
greeting = "Hello, "
name = "John"
greeting += name
print(greeting)

```

This code would output:

```
Hello, John

```

In this example, we first define two strings `greeting` and `name`. We then use the `+=` operator to concatenate `name` onto the end of `greeting`. The resulting string is assigned back to the variable `greeting`, which is then printed to the console.

### ****************************INPUT FUNCTION****************************

The input function in Python is like asking a question to the computer and getting an answer. For example, if you want to ask the user for their name, you can use the input function like this:

```
name = input("What is your name? ")

```

The computer will then print the question "What is your name?" and wait for the user to type in their answer. Whatever the user types in will be stored in the variable `name`. You can then use the variable `name` in your program to refer to the user's name.

It's like when your teacher asks you a question in class and you raise your hand to answer. The teacher writes down your answer (stores it in a variable) and then uses it to teach the rest of the class.

Another code to know the length function:

The code `print(len(input("What is your name? ")))` asks the user to input their name using the `input()` function. The `len()` function then returns the length of the string that the user inputted (i.e., the number of characters in their name). Finally, the `print()` function is used to display the length of the user's input in the console.

```
print(len(input("What is your name? ")))

#Notes
#If input was "Jack
#1st: print(len("Jack")
#2nd: print(4)

```

*note: to put comments on python, it can add ‘ # ‘ at the first line. So the computer won’t read the code. Or highlight the code and type “ Ctrl + / ”*

### ********************************PYTHON VARIABLES********************************

In Python,  a variable is like a container that holds information, while a string is just a bunch of letters and words that we want to use in our program. Variables can be used to store different types of information, such as numbers or strings, while a string can only store text. **Variable** is like a box that has a name and you can put things in it. You can put different kinds of things in a variable, like numbers or words, and you can change what's inside the box whenever you want.

For example, you could have a variable called `my_age` that holds the number `5`. Later on, you could change the value of `my_age` to `6` if you had a birthday.

Variables are really useful because they let us store information and use it later on in our program. We can also give variables names that make it easy for us to remember what's inside them.

For example, if you want to store the number 7 in a variable called `my_variable`, you can do so like this:

```
my_variable = 7

```

Now whenever you use the name `my_variable` in your program, it will be replaced with the value `7`. You can also change the value of `my_variable` later on in your program:

```
my_variable = 10

```

Now whenever you use the name `my_variable` in your program, it will be replaced with the value `10`.

Variables can be used to store different types of information, such as numbers or strings. For example, if you want to store the string "hello" in a variable called `my_string`, you can do so like this:

```
my_string = "hello"

```

Now whenever you use the name `my_string` in your program, it will be replaced with the string "hello". You can also change the value of `my_string` later on in your program:

```
my_string = "goodbye"

```

Now whenever you use the name `my_string` in your program, it will be replaced with the string "goodbye".
