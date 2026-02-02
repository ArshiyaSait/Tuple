# Tuple
tpl = tuple(map(int, input("Enter elements separated by spaces: ").split()))
total = sum(tpl)
mean = total / len(tpl)
print("Given tuple is:", tpl)
print("The mean of given tuple is:", mean)

OUTPUT:
Enter elements separated by spaces: 2 4 5 9
Given tuple is: (2, 4, 5, 9)
The mean of given tuple is: 5.0
