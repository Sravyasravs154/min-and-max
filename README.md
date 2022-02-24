# l = []
n = int(input("Enter n value : "))
for i in range(1, n + 1):
    value = int(input())
    l.append(value)
print("The Smallest Element in this List is : ", min(l))
print("The Largest Element in this List is : ", max(l)) 
