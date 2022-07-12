# Data Structures and Data Types

* If you're learning Python from multiple sources, you might encounter the terms data structures and data types being used interchangeably.
* **Definition**: The term "Data structure" is a general computer science concept. Its definition reads as follows on Wikipedia:

> **Data structure is a data organization, management, and storage format that enables efficient access and modification.** More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.

* On the other hand, Data type is a concept specific to a programming language. In a way, it is a concrete implementation of a data structure in a particular programming language (be it Python or any other language).
* **The definition of a "type" varies among programming languages.** Talking about Python, there are basic data types like int, float, string, etc. You can use the built-in types like list, set, etc., which we will cover in this session.
* Calling these data types as data structures won't be wrong because there is no significant difference between the two in Python.

### Data Types in Python

*   Before we proceed to discuss what data types in Python are, there are some basic questions that we would discuss. **What is data?** 
* Let's say you are going to meet a friend at her office. When you visit her office, the security guard asks you to fill in the following information in the register before you enter:

| **Visitor's name** | **Visitor's phone number** | **Visitor's address** | **Entry time** |
| ------------------ | ---------------------- | --------------------- | ------------------- |
| **Karen** | **32 000 000** | **Leuven** | **8:30 AM** |

* The above information that you just provided is data.
* We see that the data entered in the previous slide has different varieties:
  * Some are English letters,
  * Some are numerical digits, and
  * There are some special characters, dash (-) and colon ( : ).
  * In this example, we divide the data into four categories – name, phone number, address, and time.
  *   This **categorization of data, based on its characteristics & our needs, is called data types.**

*   Some of the data types in Python include:

    * Integer: whole numbers, positive or negative numbers. E.g., 100.
    * Float: Floating-point numbers are real numbers, rational or irrational. In most cases, this means numbers with decimal parts. Example: 123.45.
    * String: Strings are sequences of characters, or text, enclosed in quotes. Example: "any text", "Karen".

* For further reading **about operators and data types**, visit: [https://www.dummies.com/programming/python/python-all-in-one-for-dummies-cheat-sheet/](https://www.dummies.com/programming/python/python-all-in-one-for-dummies-cheat-sheet/)
* For practice and different data type examples, visit: [https://www.w3schools.com/python/python\_datatypes.asp](https://www.w3schools.com/python/python\_datatypes.asp)

### **Getting the Data Type**

You can get the data type of any object by using the type( ) function:

* **Numerical Types**: int (integer), float (decimal)
* **Text Type**: str (string)
* **Boolean Type**: bool (True or False)

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3d533f4f681f408ca628cd0594978900.png)