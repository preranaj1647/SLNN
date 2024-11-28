
Input Code : 
print("Practical 1(A) performed by Prerana Jadhav")
x=int(input("Enter the value of x "))
b=int(input("Enter the value for bias "))
w=int(input("Enter the value for weight "))

ynet=w*x+b

print("Net Input =",ynet)

print("Apply Activation Function over ne input , Ramp Function")

if ynet<0:
    output=0
elif ynet>=0 and ynet<=1:
    output=ynet
else:
    output=1

print("output =", output
