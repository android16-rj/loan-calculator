# loan-calculator
loan calc stage 3/4
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
    b = (ceil( loan_principal / int(input("Enter the number of months: ")))
 #        if b % 2 == 0:
          #  print("Your monthly payment = " + str(b))
       # elif b % 2 == 1:
       # from math import *
      #  print("Your monthly payment = " + (ceil(b))  + " and the last payment =  " + (loan_principal - )
#It will take 1 month to repay the loan
