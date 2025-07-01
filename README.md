pin=int(input("enter your 4 digit pin number:"))
spin=1234
balance=10000
if pin==spin:
    print("access granted")
    print("savings account")
    amount=int(input("enter the withdrawl amount"))
    if amount>balance:
        print("insuuficient balance")
    elif amount<balance:
        print("amount withdrawl",amount)
        print("remaining balance",balance-amount)
else:
    print("error")
