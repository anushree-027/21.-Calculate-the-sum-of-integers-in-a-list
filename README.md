# 21.-Calculate-the-sum-of-integers-in-a-list
L = [1, 2, "Two", 3, 4, "four", 5]

s = 0

for x in L:
    if type(x) == int:
        s = s + x

print("The sum of integers is:", s)
