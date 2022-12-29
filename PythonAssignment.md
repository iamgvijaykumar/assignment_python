Q1. Why do we call Python as a general purpose and high-level programming language?
	
	Python is an interpreted, interactive, object-oriented programming language. It incorporates modules, exceptions, dynamic typing,
	very high level dynamic data types, and classes
	
Q2. Why is Python called a dynamically typed language?

	In Python language we do not need to declare the type of the variables, it will automatically states the variable in runtime. 
	It will take care of the Memory Mangement as well.  
	
Q3. List some pros and cons of Python programming language?

	PROS: 
		Easy to learn and understand
		Open Source
		Large community support
		Various Libraries
		Interpreter
		
	Cons:
		 Since Python is interpreted, it often results in slow execution.
		 Python is much rarely seen on the client-side.		

Q4. In what all domains can we use Python?

	Web Development
	Gaming
	Data Science, AI, ML
	OS development	

Q5. What are variable and how can we declare them?

	Variables are containers for storing data
		foo = "Hello World"
		bar = 43

Q6. How can we take an input from the user in Python?

	name = input('What is your name: ')

Q7. What is the default datatype of the value that has been taken as an input using input() function?

	string

Q8. What is type casting?

	type casting is to change the data type of a variable(for eg: int to float)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

	yes, We can use looping statements(recursive and non resursive) fon n-number of times or until the condition is satisfy
	
Q10. What are keywords?

	Keywords are special resevred words for the programming language, which we cannot use

Q11. Can we use keywords as a variable? Support your answer with reason.

	No, The keywords are already avaliable to program to perform specific tasks(eg: if, class, elif)

Q12. What is indentation? What's the use of indentaion in Python?

	Indentatiion is nothing but spaces, where in Python it's used indicate the block of code

Q13. How can we throw some output in Python?

	1. using print statement: print()
	2. using raise keyword, raise TypeError('Only integers are allowed')	

Q14. What are operators in Python?

	operators perform specific task on variables and values
		Arithmetic operators
		Assignment operators
		Comparison operators
		Logical operators
		Identity operators
		Membership operators
		Bitwise operators

Q15. What is difference between / and // operators?

	/ - float division
	// - integer division

Q16. Write a code that gives following as an output.


	iNeuroniNeuroniNeuroniNeuron
	
			value = 'iNeuron'
			opvalue = value*4
			print(opvalue)
			
			or
			
			print('iNeuron'*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

	userInput = input('Enter a number: ')
	if (userInput % 2 == 0):
		print('your entered number ->',userInput,'is EVEN number'  )
	else:
		print('your entered number ->',userInput,'is ODD number'  )

Q18. What are boolean operator?

	and, or and not are referred to as boolean operators with give true or false

Q19. What will the output of the following?

	```
	1 or 0 - 1
	 
	0 and 0 - 	0

	True and False and True - false

	1 or 0 or 0 - 1
	```

Q20. What are conditional statements in Python?

	if, if elif, nested if elif are the conditional statements to perform operations on true or false(decision making)
	

Q21. What is use of 'if', 'elif' and 'else' keywords?

	if, if elif, nested if elif are the conditional statements to perform operations on true or false
	else will be the last of the conditional statement

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

	userAge = input('Enter your Age')
	if(userAge >= 18):
		print(I can vote)
	else:
		print(I can't vote)
		

Q23. Write a code that displays the sum of all the even numbers from the given list.

	```
	numbers = [12, 75, 150, 180, 145, 525, 50]
	sum = 0
	for num in numbers:
		sum += num
	print(sum)

	```

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

	num1 = input('Enter first number')
	num2 = input('Enter second number')
	num3 = input('Enter third number')
	
	max = num1

	if(num2 > max):
		max = num2
	if(num3 > max):
		max = num3
		
	print('max number is', max)
	
	

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

	- The number must be divisible by five

	- If the number is greater than 150, then skip it and move to the next number

	- If the number is greater than 500, then stop the loop
	```
	numbers = [12, 75, 150, 180, 145, 525, 50]

	for num in numbers:
		if(num >= 500):
			break
		if(num >= 150):
			continue
		if((num % 5) == 0):
			print(num)
	```

Q26. What is a string? How can we declare string in Python?

	String is a sequence of chars, nameStr = 'iNeuron'

Q27. How can we access the string using its index?

	nameStr = 'iNeuron'
	print(nameStr[0]) # i
	print(nameStr[1]) # N
		

Q28. Write a code to get the desired output of the following

	string = "Big Data iNeuron"
	lst = list(string.split(" "))
	desired_output = lst[-1]
	print(desired_output)

	# desired_output = "iNeuron"

Q29. Write a code to get the desired output of the following

	string = "Big Data iNeuron"
	desired_output = "norueNi"

	print(string[len(string):8:-1])

Q30. Resverse the string given in the above question.

	string = "Big Data iNeuron"
	print(string[len(string): :-1])

Q31. How can you delete entire string at once?

	string = "Big Data iNeuron"
	del string

Q32. What is escape sequence?

	Character combinations consisting of a backslash (\) followed by a letter or by a combination of digits are called "escape sequences."
	

Q33. How can you print the below string?

	'iNeuron's Big Data Course'

	str ='iNeuron\'s Big Data Course'
	print(str)

Q34. What is a list in Python?

	Lists are used to store multiple items in a single variable. 
	Lists are one of 4 built-in data types in Python used to store collections of data	

Q35. How can you create a list in Python?

	lst = [2,4,6,'foo', True, 'bar', 4.5]
	print(lst)

Q36. How can we access the elements in a list?

	using index
	lst = [2,4,6,'foo', True, 'bar', 4.5]
	print(lst[3])

Q37. Write a code to access the word "iNeuron" from the given list.

	lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
	print(lst[4][2])
	
Q38. Take a list as an input from the user and find the length of the list.

	input_user = input('Enter any values with spaces')
	lst = list(input_user.split(" "))
	print(len(lst))

Q39. Add the word "Big" in the 3rd index of the given list.

	lst = ["Welcome", "to", "Data", "course"]
	lst.insert(3, "Big")
	print(lst)

Q40. What is a tuple? How is it different from list?

	Lists are mutable						Tuples are immutable
	Lists have several built-in methods		Tuple does not have many built-in methods.

Q41. How can you create a tuple in Python?

	tup = ("Welcome", "to", "Data", "course")

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

	Tuples are immutable, we cannot modify the Tuple

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

	There's no append() or extend() method for tuples, You can't remove elements from a tuple, also because of their immutability.
	
Q44. Take a tuple as an input and print the count of elements in it.

	input_user = input('Enter any values with spaces')
	tup = tuple(input_user.split(" "))
	print(len(tup))

Q45. What are sets in Python?

	Set hold unique elements

Q46. How can you create a set?

	set_ =  {"Welcome", "to", "Data", "course"}

Q47. Create a set and add "iNeuron" in your set.

	set_ =  {"Welcome", "to", "Data", "course"}
	set_.add("iNeuron")
	print(set_)

Q48. Try to add multiple values using add() function.

	set_ =  {"Welcome", "to", "Data", "course"}
	set_.add("iNeuron")
	set_.add("iNeuron")
	set_.add("iNeuron1")
	set_.add("iNeuron2")
	set_.add(2234)
	set_.add(True)
	print(set_)

Q49. How is update() different from add()?

	The object in the update() method does not have to be a set, it can be any iterable object (tuples, lists, dictionaries etc.).
	To add one item to a set use the add() method.

Q50. What is clear() in sets?

	The clear() method removes all the elements from a list, tuple, set

Q51. What is frozen set?

	Python frozenset() Method creates an immutable Set object from an iterable. It is a built-in Python function. 
	As it is a set object therefore we cannot have duplicate values in the frozenset.

Q52. How is frozen set different from set?

	set is mutable	frozenset is immutable

Q53. What is union() in sets? Explain via code.

	union is contains all items from both sets, duplicates are excluded:

	set1 = {'apple', 'banana', 'orange'}
	set2 = {'apple', 'milk', 'doctor'}
	print(set1.union(set2))
	
Q54. What is intersection() in sets? Explain via code.

	Intersection is common items for from both the sets
	set1 = {'apple', 'banana', 'orange'}
	set2 = {'apple', 'milk', 'doctor'}
	print(set1.intersection(set2))

Q55. What is dictionary ibn Python?

	Dictionaries are used to store data values in key:value pairs
	A dictionary is a collection which is ordered*, changeable and do not allow duplicates keys
	As of Python version 3.7, dictionaries are ordered. In Python 3.6 and earlier, dictionaries are unordered.

Q56. How is dictionary different from all other data structures.

	Dictionaries stores items in key and value pairs. set, tuple and list does not store in key:value pairs
	
Q57. How can we delare a dictionary in Python?

	dict_ = {'fdj':'dsfsdf', 343:434, 'feee':'dsfsdf'}
	del dict_

Q58. What will the output of the following?

	var = {}
	print(type(var))
	
	output: class dict
	
Q59. How can we add an element in a dictionary?

	dict_ = {'fdj':'dsfsdf', 343:434, 'feee':'dsfsdf'}
	dict_['color'] = 'red'
	print(dict_)	

Q60. Create a dictionary and access all the values in that dictionary.

	dict_ = {'fdj': 'dsfsdf', 343: 'next', 'feee': 434, 'color': 'red'}
	print(dict_.values())
	print(list(dict_.values()))

Q61. Create a nested dictionary and access all the element in the inner dictionary.

	dict_ = {'fdj': 'dsfsdf', 343: 'next','car': { "brand": "Ford", "model": "Mustang", "year": 1964 },'feee': 434, 'color': 'red'}
	for key, val in dict_.items():
		if key == 'car':
			for k,v in val.items():
				print('Key is:',k,'value is:',v )

Q62. What is the use of get() function?

	The get() method returns the value of the item with the specified key from a dictionary.
		if key exists -> returns value
		if key does not exists -> returns None
		if optional val is passed -> retuns the same value	

Q63. What is the use of items() function?

	The items() method returns a view object. The view object contains the key-value pairs of the dictionary

Q64. What is the use of pop() function?

	The pop() method removes the element at the specified position for dict. index in sets and random in sets
	car = { "brand": "Ford", "model": "Mustang", "year": 1964 }

	print(car.pop('year'))
	print(car)

Q65. What is the use of popitems() function?

	 popitem() can only remove and return the value of the last element in the dictionary.

Q66. What is the use of keys() function?

	The keys() method in Python Dictionary, returns a view object that displays a list of all the keys in the dictionary in order of insertion using Python

Q67. What is the use of values() function?

	Python dictionary method values() returns a list of all the values available in a given dictionary.

Q68. What are loops in Python?

	loops are used to do repetative tasks
	for and while

Q69. How many type of loop are there in Python?

	Major -> for and while - (Nested loop)

Q70. What is the difference between for and while loops?

	we use for when we know the fixed number of iterations
	we use while when we do not know the fixed number of iterations, works with boolean

Q71. What is the use of continue statement?

	it's will skip the iteration

Q72. What is the use of break statement?

	it'll break the loop - come out of the loop

Q73. What is the use of pass statement?

	The pass statement is used as a placeholder for future code. will not throw error

Q74. What is the use of range() function?

	The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.
	range(start, stop, step)
	

Q75. How can you loop over a dictionary?

	dict_ = {'fdj': 'dsfsdf', 343: 'next','car': { "brand": "Ford", "model": "Mustang", "year": 1964 },'feee': 434, 'color': 'red'}
	for key, val in dict_.items():
		if key == 'car':
			for k,v in val.items():
				print('Key is:',k,'value is:',v )

Coding problems
Q76. Write a Python program to find the factorial of a given number.

	def fact(num):
    counter = 1
    if (num == 0 or num == 1):
        return 'fact is 1'
    for i in range(1,num+1):
        counter *= i
    return counter

	print(fact(6)
	

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

	def simpleIntrest(p,t,r):
    return (p*t*r)/100

	print(simpleIntrest(100000, 1, 3))

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
	
	def compoundIntrest(p,t,r):
    return (pow(1+r/100, t))*p

	print(compoundIntrest(10000, 2, 3))

Q79. Write a Python program to check if a number is prime or not.

	num = int(input("Enter a number: "))

	if num > 1:
	   for i in range(2,num):
		   if (num % i) == 0:
			   print(num,"is not a prime number")
			   break
	   else:
		   print(num,"is a prime number")
	else:
	   print(num,"is not a prime number")

Q80. Write a Python program to check Armstrong Number.
	
	num = int(input("Enter a number: "))

	sum = 0
	temp = num
	while temp > 0:
	   digit = temp % 10
	   sum += digit ** 3
	   temp //= 10
	if num == sum:
	   print(num,"is an Armstrong number")
	else:
	   print(num,"is not an Armstrong number")

Q81. Write a Python program to find the n-th Fibonacci Number.
	
	FibArray = [0, 1]
 
	def fibonacci(n):
		if n<0:
			print("Incorrect input")
		elif n<= len(FibArray):
			return FibArray[n-1]
		else:
			temp_fib = fibonacci(n-1)+fibonacci(n-2)
			FibArray.append(temp_fib)
			return temp_fib
	 
	print(fibonacci(9))

Q82. Write a Python program to interchange the first and last element in a list.

	mylist = ["apple", "banana", "cherry", "google", "microsoft"]

	first_element = mylist[0]
	mylist[0]=mylist[len(mylist)-1]
	mylist[len(mylist)-1] = first_element

	print(mylist) 

Q83. Write a Python program to swap two elements in a list.
	
	def swaplist(lst, pos1, pos2):
    temp = lst[pos1]
    lst[pos1] = lst[pos2]
    lst[pos2] = temp
    return lst

	mylst = ["apple", "banana", "cherry", "google", "microsoft"]
	pos1, pos2 = 1, 3
	print(swaplist(mylst, pos1, pos2))

Q84. Write a Python program to find N largest element from a list.
	
	mylst = [4, 5, 1, 2, 9]

	def nMaxNums(lst, n):
		lst.sort()
		lst.reverse()
		return lst[0:n]

	print(nMaxNums(mylst, 2))

Q85. Write a Python program to find cumulative sum of a list.

	mylst = [10, 20, 30, 40, 50]
	final_list = []
	for i in range(0, len(mylst)):
		if i == 0:
			final_list.append(mylst[i])
		else:
			final_list.append(mylst[i]+final_list[i-1])
	print(final_list)

Q86. Write a Python program to check if a string is palindrome or not.
	
	Num = int(input("Enter a value:"))  
	Temp = num  
	Rev = 0  
	while(num > 0):  
		dig = num % 10  
		revrev = rev * 10 + dig  
		numnum = num // 10  
	if(temp == rev):  
		print("This value is a palindrome number!")  
	else:  
		print("This value is not a palindrome number!") 


Q87. Write a Python program to remove i'th element from a string.

	str = 'big data science'
	print(str[0:3]+str[4:])	

Q88. Write a Python program to check if a substring is present in a given string.

	str = 'big data science iNeuron'
	print('iNeuron' in str)

Q89. Write a Python program to find words which are greater than given length k.

	str = "hello all this is computer science portal"
	def greater_than_k(str, k):
		txt = ''
		lst = str.split(" ")
		for i in lst:
			if len(i) >=k:
				txt += i + ' '
		return txt

	print(greater_than_k(str, 5))

Q90. Write a Python program to extract unquire dictionary values.

	dict_ = {'gfg': 1, 'is': 2, 'best': 1, 'for': 3, 'CS': 2}
	print(set(dict_.values()))

Q91. Write a Python program to merge two dictionary.

	dict1 = {'gfg': 1, 'is': 2, 'best': 1, 'for': 3, 'CS': 2}
	dict2 = {'abc': 1, 'def': 2, 'ghij': 1, 'gfg': 3}
	newdict = {**dict1,**dict2}
	print(newdict)

	or

	dict1.update(dict2)
	print(dict1)

Q92. Write a Python program to convert a list of tuples into dictionary.

	Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
	Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}

	lst = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
	print(dict((lst)))
	
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

	Input: list = [9, 5, 6]
	Output: [(9, 729), (5, 125), (6, 216)]

	lst = [9, 5, 6]
	dict1 = {}

	for i in lst:
		dict1[i] = pow(i, 3)

	print(list(dict1.items()))


Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]

Q95. Write a Python program to sort a list of tuples by second item.

	Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
	Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]

	lst = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
	lst.insert(0, lst.pop(1))
	print(lst)
	
Q96. Write a python program to print below pattern.

	* 
	* * 
	* * * 
	* * * * 
	* * * * * 

	for row in range(1,6):
		for col in range(1,row+1):
			print('*', end =" ")
		print()

Q97. Write a python program to print below pattern.

		*
	   **
	  ***
	 ****
	*****

	n = 5

	k = 2*n - 2

	for i in range(0, n):
		for j in range(0, k):
			print(end=" ")
		k = k - 2
		for j in range(0, i+1):
			print("* ", end="")
		print("\r")

Q98. Write a python program to print below pattern.

	    * 
	   * * 
	  * * * 
	 * * * * 
	* * * * *

	n = 5

	k = 2*n - 1

	for i in range(0, n):
		for j in range(0, k):
			print(end=" ")
		k = k - 1
		for j in range(0, i+1):
			print("* ", end="")
		print("\r")
	
	
Q99. Write a python program to print below pattern.

	1 
	1 2 
	1 2 3 
	1 2 3 4 
	1 2 3 4 5

	for row in range(1,6):
			for col in range(1,row+1):
				print(col, end =" ")
			print()
		
Q100. Write a python program to print below pattern.

	A 
	B B 
	C C C 
	D D D D 
	E E E E E 

	ascii_ = 65
	for i in range (1,6):
		# inner loop
		for j in range(1,i+1):
			print(chr(ascii_),end="")
		ascii_ += 1
		print()
