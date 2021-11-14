# Gift_Faulty_Calculator_to_cheater_friend
My friend give me a order to build a calculator for my maths exam using python. I make the calculator but with twist adding some function with fault.
print("Prasad Coding")
print("Hello welcome to my calculator")
Num1 = int(input("Enter a Num1:"))
Num2 = int(input("Enter a Num2:"))
print("Please enter a oprator to proceed further")
print('what you want?''+','-','*','/')
Num3 = input("Enter a oprator :")

if Num1 == 45 and Num2 == 3 and Num3 == '*':
    print("555")
elif Num1 == 56 and Num2 == 9 and Num3 == '+':
    print("77")
elif Num1 == 56 and Num2 == 6 and Num3 == '/':
    print("4")
elif Num1 == 10 and Num2 == 6 and Num3 == '-':
    print("3")
elif Num3 == '+':
    addi = Num1+Num2
    print(addi)
elif Num3 == '-':
    minus = Num1 - Num2
    print(minus)

elif Num3 == '*':
    multi = Num1 * Num2
    print(multi)
elif Num3 == '/':
    Divi = Num1 / Num2
    print(Divi)

else:
    print("Thank you for using me")

print("Thank For using me")
