import math
while True:
    s=input("Выбери действие(+,-,*,/,%,sq(square)):")
    if s==0:
        break

    if s in ("+","-","*","/","%",'sq'):
        x=float(input('Выбери первое число:'))
        y=float(input('Выбери второе число:'))
        if s=='+':
            print("%.2f" %(x+y))
        elif s=='-':
            print("%.2f" %(x-y))
        elif s=='*':
            print("%.2f" %(x*y))
        elif s=='/':
            if y!=0:
                print("%.2f" %(x/y))
            else:
                print("Ошибка, нельзя делить на 0!")
                break
        elif s=='%':
            print("%.2f" %(x*y/100))
        elif s=='sq':
            print("%.2f" %(x**y))

    else:
        print("Ошибка, неверный знак операции!")
        break
