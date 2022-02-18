# Assignment-2-18-2-2022
Assignment-2 Write a program to print sum of n factorials 
def findFactSum(N):
f=1
Sum = 0
for i in range(1, N + 1):
f=f*i;
Sum +=f
return Sum
if _name_=="_main_":
N=5
print(findFactSum(N))
output
153
