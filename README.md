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
