## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language? A1. Python is called as a general purpose and high level programming language because it is easy to write and understand. Moreover it can be used to create a variety of different programs and isn't specialized for any specific problems.

Q2. Why is Python called a dynamically typed language? A2. It is called as dynamically typed language because type of variable declaration is not needed in python. It identifies the type of variable by itself during runtime.

Q3. List some pros and cons of Python programming language? A3. Pros: Python is high level programming language easy to read and write. Python is dynamically capable of identifying all sorts of variables. Python is general purpose and can be used for a variety of problem statements. Cons: Python is weak in mobile computing and browsers. It is more suitable in the server side not in the client side.

Q4. In what all domains can we use Python? A4. Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting, Networking, Game Development to Web Development.

Q5. What are variable and how can we declare them? A5. Variables are symbolic reference to an object. We can simply type the name of the variable and assign the value to it. There is no need to explicitly define the data type of the variable.

Q6. How can we take an input from the user in Python? A6. Using input function.

Q7. What is the default datatype of the value that has been taken as an input using input() function? A7. string.

Q8. What is type casting? A8. Type casting is converting a set of data type to one of our required data types.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why? A9. Yes we can, by using split function.

Q10. What are keywords? A10. Keywords in python are inbuilt standard functions of python which are meant to perform specfic task.

Q11. Can we use keywords as a variable? Support your answer with reason. A11. Keywords are some predefined and reserved words in python that have special meanings. Keywords are used to define the syntax of the coding. The keyword cannot be used as an identifier, function, and variable name.

Q12. What is indentation? What's the use of indentation in Python? A12. Indentation refers to the spaces at the beginning of a code line. In python indentation is used to segregate specific block of code.

Q13. How can we throw some output in Python? A13. Using print function.

Q14. What are operators in Python? A14. In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands. A sequence of operands and operators, like a + b - 5 , is called an expression. Python supports many operators for combining data objects into expressions.

Q15. What is difference between / and // operators? A15. / stands for normal division whereas // stands for float division.

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron
A16. str_value = 'iNeuron' str_value = str_value*4 print(str_value)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even. A17.

Input Function
int_value = int(input('Enter a number')) if int_value % 2 == 0: print('Even Number') else: print('Odd Number')

Q18. What are boolean operator? A18. Boolean operators are Python's built-in data types. It's used to represent the truth value of an expression.

Q19. What will the output of the following?

1 or 0
A19. Output: 1

0 and 0
Output: 0

True and False and True
Output: False

1 or 0 or 0
Output:  1
Q20. What are conditional statements in Python? A20. A conditional statement is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Q21. What is use of 'if', 'elif' and 'else' keywords? A21. The if / elif / else structure is a common way to control the flow of a program, allowing you to execute specific blocks of code depending on the value of some data.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote". A22. age = int(input('Enter the age')) if age >=18: print('I can vote') else: print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]
A23. numbers = [12, 75, 150, 180, 145, 525, 50] sum = 0 for item in numbers: if item %2==0: sum = sum + item

print("The sum of all even numbers is: ", sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output. A24.

Greatest number as output
x = list(map(int, input("Enter multiple values: ").split())) print(max(x))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
A25. numbers = [12, 75, 150, 180, 145, 525, 50] my_list = [] for item in numbers: if item %5 ==0 and item <= 150: my_list.append(item) elif item > 500: break elif item > 150: continue

print(my_list)
```

Q26. What is a string? How can we declare string in Python?

Q27. How can we access the string using its index?

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
A28.
# String Index problem
string = "Big Data iNeuron"
print(string[9:])

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
A29.
string = "Big Data iNeuron"
print(string[-1:-8:-1])

Q30. Resverse the string given in the above question.
A30.
string = "Big Data iNeuron"
print(string[::-1])

Q31. How can you delete entire string at once?
A31. You can delete the entire string using replace method with the new string as space ('').

Q32. What is escape sequence?
A32. An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters.

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
A33.
print("iNeuron's Big Data Course")

Q34. What is a list in Python?
A34.
Lists are used to store multiple items in a single variable. Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are Tuple, Set, and Dictionary, all with different qualities and usage.

Q35. How can you create a list in Python?
A35.
my_list = [1,2,6,8,9]

Q36. How can we access the elements in a list?
A36.
List elements can be accessed using indexes.
my_list[0] would be able to access the first element of the list.

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
A37.
my_list = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(my_list[4][2])

Q38. Take a list as an input from the user and find the length of the list.
A38.
# Find Lenth of the list
my_list = [1,2,6,8,9]
print(len(my_list))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
A39.
# Add elements to the list
my_list = ["Welcome", "to", "Data", "course"]
my_list.insert(2,"Big")
print(my_list)

Q40. What is a tuple? How is it different from list?
A40. Tuples are used to store multiple items in a single variable. Tuple is one of 4 built-in data types in Python used to store collections of data. Tuples are immutable while lists are mutable.

Q41. How can you create a tuple in Python?
A41. my_tuple = (1,2,3,5,7)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
A42. 
my_tuple = (1,2,3,5,7)
My name cannot be added to the above tuple as tuples are immutable.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
A43. Two tuples cannot be appended since tuples are immutable.

Q44. Take a tuple as an input and print the count of elements in it.
A44.
# Count number of entries in tuple
result = tuple(map(int,input("Enter values for a tuple").split()))
print(len(result))

Q45. What are sets in Python?

Q46. How can you create a set?

Q47. Create a set and add "iNeuron" in your set.
A47.
# Set problem
my_set = {2,4,7,'Ashish'}
my_set.add('iNeuron')
print(my_set)

Q48. Try to add multiple values using add() function.
A48.
# Set problem to add multiple values using add function
my_set = {2,4,7,'Ashish'}
print('My initial set is :', my_set)
new_set = {4,8,9,'Shaw'}
for item in new_set:
    my_set.add(item)
print('My New set is : ',my_set)


Q49. How is update() different from add()?

Q50. What is clear() in sets?

Q51. What is frozen set?

Q52. How is frozen set different from set?

Q53. What is union() in sets? Explain via code.

Q54. What is intersection() in sets? Explain via code.

Q55. What is dictionary ibn Python?

Q56. How is dictionary different from all other data structures.

Q57. How can we delare a dictionary in Python?

Q58. What will the output of the following?
```
var = {}
print(type(var))
```

Q59. How can we add an element in a dictionary?

Q60. Create a dictionary and access all the values in that dictionary.

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Q62. What is the use of get() function?

Q63. What is the use of items() function?

Q64. What is the use of pop() function?

Q65. What is the use of popitems() function?

Q66. What is the use of keys() function?

Q67. What is the use of values() function?

Q68. What are loops in Python?

Q69. How many type of loop are there in Python?

Q70. What is the difference between for and while loops?

Q71. What is the use of continue statement?

Q72. What is the use of break statement?

Q73. What is the use of pass statement?

Q74. What is the use of range() function?

Q75. How can you loop over a dictionary?


### Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```