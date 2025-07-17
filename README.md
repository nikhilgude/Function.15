# Function.15
It prints alternating lines of "Nikhil" and "Gude" along with the current number, counting down from the input number to 1.
def A(n):
    if n<=0:
        return
    print("Nikhil", n)
    B(n-1)
def B(n):
    if n<=0:
        return
    print("Gude", n)
    A(n-1)
num = int(input("enter a number:"))
A(num)
