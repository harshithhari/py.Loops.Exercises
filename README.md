# py.Loops.Exercises
''Exercise 1: Calculate the multiplication and sum of two numbers
Given two integer numbers return their product only if the product is equal to or lower than 1000, 
else return their sum.'''

'''x=int(input("Please enter a numner: "))
y=int(input("Please enter a numner: "))

if x*y<=1000:
    print('product is:',x*y)
else:
    print('sum is :',x+y)'''
'''Exercise 2: Print the sum of the current number and the previous number
Write a program to iterate the first 10 numbers and in each iteration, 
print the sum of the current and previous number.'''

x = 0
for i in range(0,10):
    y = x+i
    print(f'current number :{i},previous number is : {x},sum is : {y}')
    x = i

*******'''Exercise 3: Print characters from a string that are present at an even index number
Write a program to accept a string from the user and display characters that are present at an even index number.

For example, str = "pynative" so you should display ‘p’, ‘n’, ‘t’, ‘v’.'''

'''x= 'pynative'

print(x[0::2])'''

'''x = input('enter your word :')

print("original string:",x)

for i in range(0,len(x),2):
    print('index number is :',i, x[i])'''

'''Exercise 4: Remove first n characters from a string
Write a program to remove characters from a string starting from zero up to n and return a new string.

For example:

remove_chars("pynative", 4) so output must be tive. Here we need to remove first four characters from a string.
remove_chars("pynative", 2) so output must be native. Here we need to remove first two characters from a string.
Note: n must be less than the length of the string.'''

def remove_charaters(word,n):
    x = word
    print('removing charecters')
    print('original characters',x)
    print(f'after removing:{x[n:]}')

x = remove_charaters('pynative',4)
print(x)
