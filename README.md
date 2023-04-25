x = int(input())
y = int(input())
r = str(input())
if r == "*":
	print(x,r,y,"=")
	print(x*y)
elif r == "-":
	print(x,r,y,"=")
	print(x-y)
elif r == "+":
	print(x,r,y,"=")
	print(x+y)
else:
	print(x,r,y,"=") 
	print(x/y)