# code-for-calculator-russia.py
numberone = input("Первое число: ")
znak = input("Знак: ")
numbertwo = input("Второе число: ")


if znak == "+" : 
    result = int(numberone) + int(numbertwo)
    print("Решение равно: " + numberone + " Сложить на " + numbertwo + " равенство " + str(result))

elif znak == "-" : 
    result = int(numberone) - int(numbertwo)
    print("Решение равно:" + numberone +" Вычетать на " + numbertwo + " равенство " + str(result))

elif znak == "/" : 
    result = int(numberone) / int(numbertwo)
    print("Решение равно:" + numberone +" Делить на" + numbertwo + " равенство " + str(result)) 

elif znak == "*" : 
    result = int(numberone) * int(numbertwo)
    print("Решение равно:" + numberone +" Умножить на" + numbertwo + " равенство " + str(result))

elif znak == "%" : 
    result = int(numberone) % int(numbertwo)
    print("Решение равно:" + numberone +" Делить остатком " + numbertwo + " равенство " + str(result))

else :
    print("Вы ошиблись в написании откройте программу заново, и напешите правильно числа")
