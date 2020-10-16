# loan-calculator
loan_principal = int(input("Enter the loan principal: "))
que_1 = input("What do you want to calculate? ")
#que_2 = input("Enter the monthly payment: ")
#que_3 = input("Enter the number of months")

if que_1 == "m":
    from math import *
    a = (ceil(loan_principal / int(input("Enter the monthly payment: "))))
    if a == 1:
        print("It will take " + str(a) + " month to repay the loan")
    else:
        print("It will take " + str(a) + " months to repay the loan")

elif que_1 == "p":
    from math import *
    c = int(input("Enter the number of months: "))
    if c % 2 == 1:
        from math import *
        b = (ceil(loan_principal / c))

        print(b)
