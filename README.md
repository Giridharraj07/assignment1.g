## Assignment Part-1
Q1- Why do we call Python as a general purpose and high-level programming language?
A1- python is not limited to one domain,it is use as multiple domains like as machine learning,data science,web devlopment,data analysis,scripting,artificial intellegence,software devlopment and to make system application that's why we called python as a general purpose programming language.before Understanding high level programming language, we have to understand that there were 2 languages which we know as low level programming language which came first from high level programming language. the first of which was machine learning language which was difficult to understand and which was in binary form(example-0101-hello)it is also known as first generation programming language, the second was assembly language which was easier than this, it has numeric symbols(example-(add-+)and(sub-)) was used , it was known as second generation programming language and then came the third generation  programming language(python),which we know from the high level programming language,it is very easy to did the code(example-print("hello world"))and remember it.it is human friendly programming language, that's why python is called high level programming language.
Q2-Why is Python called a dynamically typed language?
A2-There is no need to declare the data type in python,but in c,c++ and java the data type has to be declared. Example-Q-add two numbers and print,A-in python Dynamic typed language-a,b=10,20 print(a+b).AA-in static(java,c++,c) typed language-int_a=10,int_b=20,system.out.printll etc. so that python called a dynamically typed language.
Q3- List some pros and cons of Python programming language?
A3-Pros-python is support all functions and perform easily,python code run is line by line,python syntax is very simple,python GUI provide better functionality as compare to other language and python is support POP and OOP.                                                                                                                Cons-Not the fastest language,lessor libraries,not strong on type-binding, not easily convertible and  lack of web devlopment capabilities.
Q4-In what all domains can we use Python?
A4-Since python is the go-to programming language for domains such as artificial intelligence, machine learning and deep learning.
Q5- What are variable and how can we declare them?
A5-Variable is a name given to a specific memory location.                                                                                                                  Example-  a=5--right -simple variable declaration and assignment ,12abc=10--wrong                                                                                        Any variable name should start with alphabet.                                                                                                                            We cannot use any special symbol in variable.                                                                                                                            example-post ? _ 123--wrong                                                                                                                                              We can only use underscore( _ )  as a part of variable names                                                                                                              Example-abc _ 123, our variable name can start from underscore _ 123
Q6- How can we take an input from the user in Python?
A6-Input()                                                                                                                                                                        Python provides us the facility to take input from user using input() function.this function prompts the user to input a value.                                          for example:                                                                                                                                                                          Name=input("enter your name");                                                                                                                                            print(Name);                                                                                                                                                   Output will be the name as entered by the user.                                                                                                                           Example 2:                                                                                                                                                                          Name=input("Giridhar raj");                                                                                                                                            print('welcome mr.",Name);                                                                                                                               Output         welcome mr. Giridhar raj        
Q7- What is the default datatype of the value that has been taken as an input using input() function?   
A7-In Python, we implement the input() function to get user input. The input function translates whatever you give it as input into a string. Even if an integer value is entered, the input() method accepts it as a string.                                                                                                                       Syntax: input(prompt)                                                                                                                                                   Parameter:                                                                                                                                                             Prompt: (optional) The string to write to standard output (typically the screen) without a newline                                                                     By default, it returns a string object                                                                                                                                 By default, it returns a string object. Hence, the input () function by default returns the value as string data type 
Q8-  What is type casting?
A8- Trying to change datatype                                                                                                                                                       Ex- Int->float
Q9- Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A9- Yes, we can take more than one input from the user using a single input() function by asking the user to enter multiple values separated by a delimiter (e.g., a comma, space, or semicolon). Then, we can use the string method split() to split the input string into individual values.                                           Here's an example of how to do this:                                                                                                                                   # Ask the user to enter multiple values separated by a comma                                                                                                      user_input = input("Enter multiple values separated by a comma:")                                                                                                       # Split the input string into individual values                                                                                                                          values = user_input.split(",")                                                                                                                                         # Print the individual values                                                                                                                                            for value in values:                                                                                                                                                  print(value.strip())                                                                                                                                                    # strip() is used to remove any leading/trailing whitespaces                                                                                                           When the user enters multiple values separated by a comma (e.g., "apple,banana,orange"), the split() method will create a list of individual values (["apple", "banana", "orange"]) that we can loop through or process in other ways.
Q10-What are keywords?                                                                                                                                                  A10-Keywords are the reserved words whose meaning already defined in the python interpretor.                                                                              Note:a- we can't use a keyword as a variable name, method name or any other identifier.                                                                                     b-python keywords are the case sensetive.                                                                                                                       # how to know how many keywords in python-                                                                                                                              help('keywords')                                                                                                                                                       # 2nd way                                                                                                                                                                 import keyword                                                                                                                                          print("keywords are:")                                                                                                                                          print(keyword.kwlist) 
