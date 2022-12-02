## Assignment Part-1
## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
-> we call python general purpose language beacuse with python we can build any thing or we can use
python for any kind of computational task like web development, App development, machine learning, NLP
Data Engineering/Sciance, Games etc. and it is High level beacuse with simple english we can write/read python code it is easy to human to read and write it. and we can write it by using simple human understable english language that why it is high level programming language 

Q2. Why is Python called a dynamically typed language?
-> we called python is dynamically type beacuse while defining any object we dont have to tell which type of data it going to hold or we cant mention how much element is going to hold by list like we do in c and c++ for array. in c/c++/java we define what kind of data that is going hold by variable before assigning any data into it. same we dont do in python we simply assign data to variable. Also in python we can add any no of elements in list and type of data in list without predefining any thing thats why we call python as dynamically type

Q3. List some pros and cons of Python programming language?
pros-> It is easy to ready/write, dynamic typed, have/support many frameworkd/librarys, can use with multiple teach like(ML,data sciance,data engineer,NLP,web/app development)
cons-> comparatively SLOW than c++/java

Q4. In what all domains can we use Python?
->yes like (data sciance/data engineer,ML,NLP,web development,block chain)

Q5. What are variable and how can we declare them?
->variable is name to memory location where our data is hold. to declare it we give name to varibale with assignment oprator and then data that we need to store in varibale.
ex number=100,name="ineuron"

Q6. How can we take an input from the user in Python?
-> we can take input from user by using python inbulid function input() or input("enter your data")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
-> default data type taken by input() is string

Q8. What is type casting?
->type casting is converting data type from one form to another.like int("21"),list((1,2,3,4))

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
-> yes you can take it in single input. like if you want 3 int number from user you can do it like below

num1,num2,num3=[int(i) for i in input("enter number ").split()]


Q10. What are keywords?
-> keywords are reserved words in python which have some predefine meaning
like class,def,pass,continue,break,for,in,not in

Q11. Can we use keywords as a variable? Support your answer with reason.
->NO Keyword is reserved words in language which have some work or predefine meaning so you cannot use them as variables

Q12. What is indentation? What's the use of indentaion in Python?
->indentation is bydefault 4 spaces in python it is used to define block in if else or loops part. with help of indentation you can define which is part of what block or code.

Q13. How can we throw some output in Python?
-> by using build in function print()

Q14. What are operators in Python?
->arathmatic oprator:-  +,-,//,/,*,%
->assignment oprator:- +=,-+,/+,*=,=
->comparator:- ==,!=,<,>,<=,>=
->logical:- and,or,not

Q15. What is difference between / and // operators?
-> / is use to devide ans is always in float
->// is use to floor devide ans is in integer 

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

```
-> print("iNeuron"*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
->code is

number=int(input("Enter your number: "))

if number%2 == 0:
    print(number,"is Even")
else:
    print(number,"is Odd")

Q18. What are boolean operator?
-> and,or,not
Q19. What will the output of the following?
```
1 or 0 -> True

0 and 0 -> False

True and False and True -> False

1 or 0 or 0 -> True
```

Q20. What are conditional statements in Python?
-> if,elif,else are conditional statements by using we and change flow of our code

Q21. What is use of 'if', 'elif' and 'else' keywords?
->to control flow of code. IF satisfy condition then that block execute outerwise it will go to elif part if both didnt satisfy the it will execute else part. so we clontrolling flow of our code 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
->code is

age=int(input("Enter your age: "))

if age >= 18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
->code is
n_sum=0

for i in numbers:
    if i%2 == 0:
        n_sum+=i
print("sum of even numbers is",n_sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
->code is

num1,num2,num3=[int(i) for i in input("enter number ").split()]

if num1>num2 and num1>num3:
    print(num1,"is greater")
elif num2>num3:
    print(num2,"is greater")
else:
    print(num3,"is greater")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
->code is

for i in  numbers:
    if i<=500:
        if i>150:
            continue
        elif i%5==0:
            print(i)
    else:
        break

Q26. What is a string? How can we declare string in Python?
-> In a python string is collection/group of character enclosed in ' '," ",""" """
example: "my name is Bhujang"
Q27. How can we access the string using its index?
-> we can access the single character from string by calling its index number in []
in python index starts from 0(left to right) and from -1(right to left)
like example 
var="Ineuron"
print(var[1]) -> output will be n

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
->code is 
print(string[9:])

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
->code is 
print(string[-1:8:-1])

Q30. Resverse the string given in the above question.
->code is

print(string[len(string)::-1])
or
print(string[15::-1])
Q31. How can you delete entire string at once?
->
if you ant to delete the whole string with variable as wel you can use del() inbuild function in python
del(string)
or you can apply empty sctring to variable
string=""
Q32. What is escape sequence?
-> escape sequence is shifting a string to new line we call it line break
we use \n for break line
or if we want to escap any character then as well we use \ as an escape character
\n for line breal
\t for horozontal tab
\b for backspace
\v for vertical tab

also in string we could use as 
print("who's this")

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
->
print("iNeuron's Big Data Course")

Q34. What is a list in Python?
-> List in python is group of elements where elements can be heterogeneous data. it is sequential datatype iterable and mutable as well
alike array we can store data in list but dynamically and any kine of data we can store like heterogeneous data
Q35. How can you create a list in Python?
-> we can create it by multiple options as.
var=[]
var=list()
var=[1,2,3,4,5]
var=["hi",2,2.40]

Q36. How can we access the elements in a list?
-> you can access list elements by using python indixing slicing over list or you can apply for loop as well on list to access elements.
data=[1,2,3,4]
```
data[0]
````
````
data[1:4]
`````
````
for i in data:
    print(i)
`````

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
-> print(lst[4][2])

Q38. Take a list as an input from the user and find the length of the list.
->
var=[i for i in input("enter data to generate list: \n").split(" ")]
print(len(var))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
->
list.insert(3,'Big')

Q40. What is a tuple? How is it different from list?
-> Tuple is group of elements and can hold heterogeneous data. only diffrenece between tuple and list is tuple is immutable we cannot update tuple data like list.

Q41. How can you create a tuple in Python?
->
tup=tuple()
tup=(1,2,3,)
tup=()

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
-> NO we cannnot add elements in tuple. as Tuple is Immutable datatype so it does not allow to add elements in typle.
BUT by some logic you can do it like 
tup=()
tup+=("Bhujang",)
print(tup)

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
-> You cannot append two tuples beacuse there is no any method called append as we know tuple is immutable datatype but yes you can add
two tuples like
tup1=(1,2,3)
tup2=(11,12,13)
tup=tup1+tup2
print(tup)

Q44. Take a tuple as an input and print the count of elements in it.
->
tup1=tuple([i for i in input("enter data in tuple: \n").split(" ")])
print(len(tup1))

Q45. What are sets in Python?
-> Set is group of unique elements it in unordered and you can store heterogeneous data but it just hold unique elements.

Q46. How can you create a set?
->
data=set()
data={1,2,3,4,5}

Q47. Create a set and add "iNeuron" in your set.
->
data=set()
data.add("iNeuron")
print(data)

Q48. Try to add multiple values using add() function.
->
multiple_values=[11,12,13,14,15]
set_data={1,2,3}
for i in multiple_values:
    set_data.add(i)

Q49. How is update() different from add()?
-> for add() it only add or insert one element at a time in existing set
but update() can add group of set() selements in existing set like
set_data=set()
set_data.update({1,2,3,4})

Q50. What is clear() in sets?
-> It clear out your set data and makes your set empty

Q51. What is frozen set?
-> frozen set is another type of set which is immutable 

Q52. How is frozen set different from set?
-> difference is only set is mutable and frozen set is immutable

Q53. What is union() in sets? Explain via code.
-> union() is creates another set which contains all elements from two sets and overlapping/duplicate elements only considers onces
set1={1,2,3}
set2={3,4,5}
print(set1.union(set2))
ans is: {1,2,3,4,5}

Q54. What is intersection() in sets? Explain via code.
-> It gives you anothe set which contains the common elements from both sets
set1={1,2,3}
set2={3,4,5}
print(set1.intersection(set2))
ans is: {3}

Q55. What is dictionary in Python?
-> dictionary stores the data in KEY=value pair like hashing in java
{"key":"value"}

Q56. How is dictionary different from all other data structures.
-> other data structures store data like container buy in dict we can store data in form of key:value pair 

Q57. How can we delare a dictionary in Python?
->
var=dict()
var={}
var={'key':'value'}

Q58. What will the output of the following?
```
var = {}
print(type(var))
````
-> <class:'dict'>

Q59. How can we add an element in a dictionary?
->please refer the code how to add data in dict
data={}
data['name']='Bhujang'

Q60. Create a dictionary and access all the values in that dictionary.
data={1:"value1",1:"value1",2:"value2",3:"value3",4:"value4",5:"value5"}
for k,v in data.items():
    print("value is:",v)

or

var=data.values() -> get list of all values

Q61. Create a nested dictionary and access all the element in the inner dictionary.
-> data={"dict1":{1:"value1",1:"value1",2:"value2",3:"value3",4:"value4",5:"value5"},"dict2":{1:1,2:2,3:3}}
->data["dict"].items()
for k,v in data['dict1'].items():
    print(k,v)

Q62. What is the use of get() function?
-> get() function takes 2 argunment 1 is KEY for which value you want and 2 one is default value like if KEY didnt found in dict then it will return that default value and if that KEY found it will return value of that KEY
if you didnt set any default value and KEY didnt found then it will print None.

Q63. What is the use of items() function?
-> items() function will givens you list of tuple where in each tuple you found key,value
actuall it will give you all key,values from dict

Q64. What is the use of pop() function?
->pop() function takes 1 argunment which is KEY when we pass KEY in pop() function it will remove and return value of that KEY
if KEY didnt found in dict then pop() raise Keyerror 

Q65. What is the use of popitems() function?
-> there is no popitems() function in dict
yes but there is piopitem() function which takes no argunment and remove and show last (hey:value) pair from dict on output window
if dict is empty then this function raise dictempty error.

Q66. What is the use of keys() function?
-> it will retrun list of all keys from given dict.

Q67. What is the use of values() function?
-> it will return list of all values from given dict
Q68. What are loops in Python?
-> there are 2 loops in python 
1 is for loop mainly used to iterate over some data or if you have finite sequential type of opration you can use for loop
2 is while loop if you want to check perticuilar condition and want to performan an operation again and agian unless condition gets failed then we can use while loop.

Q69. How many type of loop are there in Python?
->
there are 2 types of loops in python  for and while.

Q70. What is the difference between for and while loops?
-> for loop mainly used to iterate over some data or if you have finite sequential type of opration you can use for loop
->while loop if you want to check perticuilar condition and want to performan an operation again and agian unless condition gets

Q71. What is the use of continue statement?
-> when even any loop gets continue statement it will exclude all operation after the statment and goes to next iteration or next cycle loop.

Q72. What is the use of break statement?
-> when ever we use break statment in loop and it gets break statment the loop gets break and get out of thet cycle.
Q73. What is the use of pass statement?
-> Pass will do nothing it just pass to next statment. mainly it is used in blank class and functions.

Q74. What is the use of range() function?
->it given you number from 1 range to second one(excluded) in sequential manar
range(1,10) given sequential data from 1 to 10 default step is +1.

Q75. How can you loop over a dictionary?
->
for k,v for dict.items():
    print(k,v)

### Coding problems
Q76. Write a Python program to find the factorial of a given number.
->
number=int(input("eneter a number:\n"))
count=1
for i in range(1,n+1):
    count*=i
print(f"factorial of {number} is {count}")
->
def factorial(n):
    if n==0 or n==1:
        return 1
    else:
        return n*factorial(n-1)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100
->
principal_amount=int(input("enter your principal:\n"))
rate=int(input("enetr your rate:\n"))
time=int(input("enetr your time\n"))
print((principal_amount*rate*time)/100,"Rs only")

or 

def simple_interest(p,r,t):
    return (P*R*T)/100

print(simple_interest(principal_amount*rate*time))

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
->
principal_amount=int(input("enter your principal:\n"))
rate=int(input("enetr your rate:\n"))
time=int(input("enetr your time\n"))
print(principal_amount(1+rate)**time)

or 
def compound_interest(p,r,t):
    return P(1+ R/100)**t
print(compound_interest(principal_amount*rate*time))

Q79. Write a Python program to check if a number is prime or not.
->
number=int(input("enter your number:\n"))
if number==1 or number==2:
    print(f"{number} is a prime number")
else:
    for i in range(2,number):
        if number%i == 0:
            print(f"{number} is not a prime number")
            break
    else:
        print(f"{number} is a prime number"

Q80. Write a Python program to check Armstrong Number.
->
number=548834
power=len(str(number))
count=0
for i in str(number):
    count+=int(i)**power
if number==count:
    print(f"{number} is Armstrong number")
else:
    print(f"{number} is not an Armstrong number")

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