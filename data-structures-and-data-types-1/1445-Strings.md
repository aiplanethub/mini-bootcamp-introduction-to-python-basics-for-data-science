# Strings

## Sequence Types

* Sequences allow you to store multiple values in an **organized and efficient way**.
* There are seven sequence types: strings, Unicode strings, lists, tuples, bytearrays, buffers, and xrange objects.
* _Nothing to worry about looking at this long list; you will get to know it gradually._

## Python Strings

* Strings are a sequence of characters.
* Let us see some examples of strings: "My name is Rahul", "Rahul", "Go home". All these are examples of strings.
* In Python, strings are called str.
* There is a specific way of defining a string in Python – it is defined within single quotes (') or double quotes ("), or even triple quotes (''' or """).

### Accessing String Elements

* Square brackets can be used to access elements of the string.
* **Remember that the first character has index 0.**
* Index refers to the position of a character in a string. In python index number starts from 0.
* Example: \
  **`a = "Hello, World!"`**\
  **`print(a[1])`**
* **Will give an output e. Can you understand why?**

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e25fba17090d4b7fa3568c1fa7ac5773.png)

* Hope you got the answer to the previous question now!

### String Slicing

* We can also call out a range of characters from the string using string slicing.
* Specify the start and end indexes separated by a colon to return a part of the string. Note that the character of the end index is not included.
* Suppose we want to print World from the "Hello World" string. We can do so as below:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d87f6a4428d7403c898454d5b5130844.png)

### Negative Indexing

* If we have a long string and want to pinpoint an item towards the end, we can also count backward from the end of the string, starting at the index number -1.
*   Printing 'r' from the string :\
    **'a = "Hello, World!"`**

    **`print(a[-4])`**
* Get the characters from position -5 to position -3, starting the count from the end of the string: \
  **`print(a[-5:-2])`**
* **Output**: orl

### String Concatenation

* String concatenation means adding strings together.
* Use the + character to add a variable to another variable:
*   Example:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f99e3cec855e4e0ca673520d682ec3d8.png)
* Another example:\
  **`x = "Python is "`**\
  **`y = "awesome"`**\
  **`z =  x + y`**\
  **`print(z)`**
* **Output**: Python is awesome

### String Concatenation: Add Space

* We can also add spaces between two strings

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_8d557ac674d54f3daff8c4324c7e1719.png)

### String Length

* To get the length of a string, use the len( ) function.
*   Getting the length of the string a :

    **'a = "Hello, World!"`**

    **`print(len(a))`**
* **Output: 13**

### String Methods

* Python has a set of built-in methods you can use on strings.
* Must learn: Learn about important string methods from the below cheatsheet: [Python String Methods Cheatsheet](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-strings/cheatsheet)
* Tip: If you are unable to follow, run the code and make out the difference.