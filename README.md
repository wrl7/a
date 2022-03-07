Z = '\033[1;31m'
N1 =  float(input("Enter the first number  :"))
OP = input("Enter one of the four arithmetic operations  :")
N2 = float(input("Enter the second number  :"))
if OP == '+' :
	print(N1 + N2)
elif OP == '-' :
		print(N1 - N2)
elif OP == '*' : 
		print(N1 * N2)
elif OP == '/' :
			print(N1 / N2)
else :
	print("\n---\n" +Z+ "Error")
