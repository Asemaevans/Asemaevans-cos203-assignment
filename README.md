# Asemaevans-cos203-assignment

# Program to print the first 100 numbers of the Fibonacci sequence

a = 0
b = 1

print("The first 100 Fibonacci numbers are:")

for i in range(100):
    print(a, end=" ")
    a, b = b, a + b
