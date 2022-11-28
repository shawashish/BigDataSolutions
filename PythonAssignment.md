## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language? 
A1. Python is called as a general purpose and high level programming language because it is easy to write and understand. Moreover it can be used to create a variety of different programs and isn't specialized for any specific problems.

Q2. Why is Python called a dynamically typed language? 
A2. It is called as dynamically typed language because type of variable declaration is not needed in python. It identifies the type of variable by itself during runtime.

Q3. List some pros and cons of Python programming language? 
A3. Pros: Python is high level programming language easy to read and write. Python is dynamically capable of identifying all sorts of variables. Python is general purpose and can be used for a variety of problem statements. Cons: Python is weak in mobile computing and browsers. It is more suitable in the server side not in the client side.

Q4. In what all domains can we use Python? 
A4. Data Science, Machine Learning, Deep Learning, Artificial Intelligence, Scientific Computing Scripting, Networking, Game Development to Web Development.

Q5. What are variable and how can we declare them? 
A5. Variables are symbolic reference to an object. We can simply type the name of the variable and assign the value to it. There is no need to explicitly define the data type of the variable.

Q6. How can we take an input from the user in Python? 
A6. Using input function.

Q7. What is the default datatype of the value that has been taken as an input using input() function? 
A7. string.

Q8. What is type casting? 
A8. Type casting is converting a set of data type to one of our required data types.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why? 
A9. Yes we can, by using split function.

Q10. What are keywords? 
A10. Keywords in python are inbuilt standard functions of python which are meant to perform specfic task.

Q11. Can we use keywords as a variable? Support your answer with reason. 
A11. Keywords are some predefined and reserved words in python that have special meanings. Keywords are used to define the syntax of the coding. The keyword cannot be used as an identifier, function, and variable name.

Q12. What is indentation? What's the use of indentation in Python? 
A12. Indentation refers to the spaces at the beginning of a code line. In python indentation is used to segregate specific block of code.

Q13. How can we throw some output in Python? 
A13. Using print function.

Q14. What are operators in Python? 
A14. In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands. A sequence of operands and operators, like a + b - 5 , is called an expression. Python supports many operators for combining data objects into expressions.

Q15. What is difference between / and // operators? 
A15. / stands for normal division whereas // stands for float division.

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron
A16. 
str_value = 'iNeuron' 
str_value = str_value*4 
print(str_value)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even. A17.

Input Function
int_value = int(input('Enter a number')) 
if int_value % 2 == 0: 
    print('Even Number') 
else: print('Odd Number')

Q18. What are boolean operator? 
A18. Boolean operators are Python's built-in data types. It's used to represent the truth value of an expression.

Q19. What will the output of the following?

1 or 0
A19. Output: 1

0 and 0
Output: 0

True and False and True
Output: False

1 or 0 or 0
Output:  1

Q20. What are conditional statements in Python? 
A20. A conditional statement is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Q21. What is use of 'if', 'elif' and 'else' keywords? 
A21. The if / elif / else structure is a common way to control the flow of a program, allowing you to execute specific blocks of code depending on the value of some data.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote". A22. 
age = int(input('Enter the age')) 
if age >=18: 
    print('I can vote') 
else: print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]
A23. 
numbers = [12, 75, 150, 180, 145, 525, 50] 
sum = 0 
for item in numbers: 
    if item %2==0: 
    sum = sum + item

print("The sum of all even numbers is: ", sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output. A24.
A24.
Greatest number as output
x = list(map(int, input("Enter multiple values: ").split())) print(max(x))

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
A25. 
numbers = [12, 75, 150, 180, 145, 525, 50] 
my_list = [] 
for item in numbers: 
    if item %5 ==0 and item <= 150: 
    my_list.append(item) 
    elif item > 500: 
    break 
    elif item > 150: 
    continue

print(my_list)
```

Q26. What is a string? How can we declare string in Python?
A26. String is one of the data types in python which can store variables. String can be declared using single quotes or double quotes.

Q27. How can we access the string using its index?
A27. String can be accessed using [] by providing the index number in the brackets.

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
A45. Sets are used to store multiple items in a single variable. Set is one of 4 built-in data types in Python used to store collections of data, the other 3 are List, Tuple, and Dictionary, all with different qualities and usage. A set is a collection which is unordered, unchangeable*, and unindexed.

Q46. How can you create a set?
A46.
my_set = {1,2,3,4,5}

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
A49. We use add() method to add single value to a set. We use update() method to add sequence values to a set.

Q50. What is clear() in sets?
A50. Python Set clear() method removes all elements from the set.

Q51. What is frozen set?
A51. Frozen set is just an immutable version of a Python set object. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation. 

Q52. How is frozen set different from set?
A52. Frozen set is immutable whereas normal set can be changed.

Q53. What is union() in sets? Explain via code.
A53.
my_set1 = {1,2,3}
my_set2 = {2,5,6}
print(my_set1.union(my_set2))

Q54. What is intersection() in sets? Explain via code.
A54.
my_set1 = {1,2,3}
my_set2 = {2,5,6}
print(my_set1.intersection(my_set2))

Q55. What is dictionary ibn Python?
A55. Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered, changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.
A56. In dictionary data is stored in the form of key value pairs unlike other data structures.

Q57. How can we delare a dictionary in Python?
A57. 
my_dict = {1:'Rahul',2:'Nikita',3:'Suresh',4:'Yash',5:'Rahul',6:'Nikita',7:'Raj',8:'Jyoti',9:'Ashish'}

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
A58. <class 'dict'>

Q59. How can we add an element in a dictionary?
A59. 
my_dict = {1:'Rahul',2:'Nikita',3:'Suresh',4:'Yash',5:'Rahul',6:'Nikita',7:'Raj',8:'Jyoti',9:'Ashish'}
my_dict[17]='Golu'
print(my_dict)

Q60. Create a dictionary and access all the values in that dictionary.
A60. 
my_dict = {1:'Rahul',2:'Nikita',3:'Suresh',4:'Yash',5:'Rahul',6:'Nikita',7:'Raj',8:'Jyoti',9:'Ashish'}
print(my_dict.values())

Q61. Create a nested dictionary and access all the element in the inner dictionary.
A61.
my_nested_dict = {1:'Rahul',2:'Nikita',10:{1:'Rahul',2:'Nikita',3:'Suresh'},3:'Suresh',4:'Yash',
                 5:'Rahul',6:'Nikita',7:'Raj',8:'Jyoti',9:'Ashish'}

print(my_nested_dict[10].values())

Q62. What is the use of get() function?
A62. get() function is used to retrieve value from the dictionary by providing the key in the get() function.

Q63. What is the use of items() function?
A63. items() function is used to fetch all the key value pair of a dictionary.

Q64. What is the use of pop() function?
A64. pop() function is used to remove element from the list.

Q65. What is the use of popitems() function?
A65. popitem() is used to remove the last key pair value inserted in the dictionary.

Q66. What is the use of keys() function?
A66. keys() function is used to fetch all the keys of the dictionary.

Q67. What is the use of values() function?
A67. values() function is used to fetch all the values of the dictionary.

Q68. What are loops in Python?
A68. Loops are control flow statements in python which are used to repeatedly execute a group of statements based on some condition.

Q69. How many type of loop are there in Python?
A69. Three types of loops are there in python. While, For and Nested loops.

Q70. What is the difference between for and while loops?
A70. for loops are iterating through a given list whereas while loop is executed based on a condition, the moment the condition is false the while loop ends.

Q71. What is the use of continue statement?
A71. continue statement is used to iterate over the next item in the loop.

Q72. What is the use of break statement?
A72. break statement is used to come out of a loop at any given point.

Q73. What is the use of pass statement?
A73. Inside a custom function if you wish to add some logic in future then you can use pass statement using which python interpreter won't throw any sytax error even if no code is written inside the custom function.

Q74. What is the use of range() function?
A74. The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

Q75. How can you loop over a dictionary?
A75. You can loop through a dictionary using .items() inside for loops.

### Coding problems
Q76. Write a Python program to find the factorial of a given number.
A76.
# Find factorial of a given number

my_num = int(input('Enter a number: '))
result = 1
while my_num != 0:
    result = result * my_num
    my_num = my_num - 1

print(result)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
A77.
# Calculate S.I
p,r,t = map(int, (input('Enter the values of Principal, Interest and Time period').split()))
result = (p*r*t)/100
print('Simple Interest is : ', result)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
A78.
# Calculate C.I
p,r,t = map(int, (input('Enter the values of Principal, Interest and Time period').split()))
result = p*((1 + r/100)**t)
print('Compound Interest is : ', result)

Q79. Write a Python program to check if a number is prime or not.
A79.
# Prime Number Check
my_number = int(input('Enter a number: '))
not_prime = False
for num in range(2,10):
    if my_number % num == 0 and my_number !=num:
        not_prime = True
        break
    else:
        continue
if not not_prime and my_number > 1:
    print(f'The number {my_number} is a Prime number')
else:
    print(f'The number {my_number} is not a Prime number')

Q80. Write a Python program to check Armstrong Number.
A80.
# Armstrong Number

my_number = input('Enter a number: ')
my_list = list(my_number)
num_len = len(my_list)
result = 0
for item in my_list:
    result = (int(item) ** num_len) + result

if result == int(my_number):
    print(f'The number {my_number} is an Armstrong number')
else:
    print(f'The number {my_number} is not an Armstrong number')

Q81. Write a Python program to find the n-th Fibonacci Number.
A81.
# Print nth Fibonacci number

def fibo(num):
    if num<=0:
        print('Incorrect number')
    elif num == 1:
        return 0
    elif num ==2:
        return 1
    else:
        return fibo(num-1) + fibo(num-2)

print(fibo(5))

Q82. Write a Python program to interchange the first and last element in a list.
A82.
# Interchange first and last element of a list

my_list = [1,5,6,8,9,12]
last = my_list.pop()
first = my_list.pop(0)
my_list.insert(0, last)
my_list.append(first)
print(my_list)

Q83. Write a Python program to swap two elements in a list.
A83.
# Swap two elements in a list
my_list = [1,3,4,56,7,8]
pos1 = 3
pos2 = 4

def swap_list(my_list,pos1,pos2):
    my_list[pos1],my_list[pos2] =my_list[pos2],my_list[pos1]
    return my_list

print(swap_list(my_list, pos1-1, pos2-1))

Q84. Write a Python program to find N largest element from a list.
A84.
# Find nth largest element in a list

my_list = [12,76,54,78,96,34,55,44,77,9]
position = int(input('Enter the position'))
def check_largest(my_list,num):
    max = 0
    my_list.sort()
    for item in my_list:
        if item >= max:
            max = item
            if my_list.index(item) == num:
                return item
            else:
                continue
print(check_largest(my_list,position-1))

Q85. Write a Python program to find cumulative sum of a list.
A85.
# Cumulative sum of a list

my_list = [12,109,97,84,24,5,52]
print('The sum of the list is: ',sum(my_list))

Q86. Write a Python program to check if a string is palindrome or not.
A86.
# Palindrome string
my_string = input('Enter a string: ').upper()
if my_string == my_string[::-1]:
    print(f'{my_string} is a Palindrome')
else:
    print(f'{my_string} is not a Palindrome')

Q87. Write a Python program to remove i'th element from a string.
A87.
# Remove ith element from a string

my_string,position = input('Enter a string and the position element to be removed').split()
my_list = []
my_list = list(my_string)
my_list.pop(int(position)-1)
result = ''.join(my_list)
print(result)

Q88. Write a Python program to check if a substring is present in a given string.
A88.
# Check substring is present in a given string

main_string, sub_string = input('Enter the main string and the substring ').split()
if sub_string in main_string:
    print('Sub string is inside Main string')
else:
    print('Try again please')

Q89. Write a Python program to find words which are greater than given length k.
A89.
# Find words greater than a specified length

my_list =['Jyoti','Ashish','Abhishek', 'Julie','Palindrome','Armstrong', 'Cruciferous']
result = []
def find_word(my_list,word_length):
    for item in my_list:
        if len(item) > word_length:
            result.append(item)
    return result

print(find_word(my_list, 9))

Q90. Write a Python program to extract unquire dictionary values.
A90.
# Extract unique dictionary values

my_dict = {1:'Rahul',2:'Nikita',3:'Suresh',4:'Yash',5:'Rahul',6:'Nikita',7:'Raj',8:'Jyoti',9:'Ashish'}
my_set = set(my_dict.values())
print(my_set)

Q91. Write a Python program to merge two dictionary.
A91.
# Merge two dictionaries

my_dict1 = {1:'Rahul',2:'Nikita',3:'Suresh',4:'Yash',5:'Ashish'}
my_dict2 = {6:'Navin',7:'Swastik',8:'Jyoti',9:'Julie'}

result = my_dict1.copy()
result.update(my_dict2)
print(result)

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
A92.
# Convert tuple into dictionary

my_list = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
print(dict(my_list))

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
A93.
# Convert list into tuple

my_list = [9, 5, 6]
result = [(val,pow(val,3)) for val in my_list]
print(result)


Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
A94.
# Join two tuples

test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
my_list = []
for item in test_tuple1:
    for value in test_tuple2:
        result = (item,value)
        my_list.append(result)
for item in test_tuple2:
    for value in test_tuple1:
        result = (item,value)
        my_list.append(result)
print(my_list)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```
A95.
# Sort a list of tuples by 2nd item

my_list = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
my_list.sort(key=lambda x:x[1])
print(my_list)

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
A96.
# Pattern print 

my_constant = '* '
for val in range(1,6):
    print(my_constant * val)

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
A97.
# Pattern print 

my_constant = '*'
my_space = ' '
counter = 1
for val in range(5,0,-1):
    print((my_space * val) + (my_constant*counter))
    counter+=1

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
A98.
# # Pattern print 

my_constant = ' *'
my_space = ' '
counter = 0
for val in range(5,0,-1):
     result = (my_constant + (my_constant*counter))
     print((my_space * val + result))
     counter+=1


Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
A99.
# Number Pattern 

for i in range(1,6):
    for j in range(1,i+1):
        print(j, end=' ')
    print('')


Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
A100.
# Alphabet pattern

my_list = ['A','B ','C ','D ','E ']

counter = 1
for val in my_list:
    print(val * counter + ' ')
    counter+=1