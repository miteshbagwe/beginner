# beginner
# Find sum of first n numbers
n = input("Input number:")
n = int(n)
sum = 0
for num in range(0,n+1):
    sum = sum + num
print("Sum of first",n,"numbers is",sum,".")
