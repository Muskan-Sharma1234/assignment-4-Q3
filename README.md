# assignment-4-Q3

Write a Python program to square the elements of a list using map() function.
Sample List: [4, 5, 2, 9]
Square the elements of the list:
[16, 25, 4, 81]




def square(x):
    return x * x

nums = [4, 5, 2, 9]
squares = map(str, map(square, nums))

print(','.join(squares))



