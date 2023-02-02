#простой калькулятор на python

#Инструкция сложения

def summa(ch1, ch2):

return ch1 + ch2

#Инструкция вычитания

def minus(ch1, ch2):

return ch1 - ch2

#Инструкция умножения

def umnoz(ch1, ch2):

return ch1 * ch2

#Инструкция деления

def delen(ch1, ch2):

return ch1 / ch2
 
print("Выберите номер желаемой операции -\n" \
        "1. Сложение\n" \
        "2. Вычитание\n" \
        "3. Умножение\n" \
        "4. Деление\n")

select = int(input("Номер вашей операции:"))

chis_1 = int(input("Введите первое значение:"))

chis_2 = int(input("Введите второе значение:"))

if select == 1:
    print(chis_1, "+", chis_2, "=", summa(chis_1, chis_2))

elif select == 2:
    print(chis_1, "-", chis_2, "=", minus(chis_1, chis_2))

elif select == 3:
    print(chis_1, "*", chis_2, "=", umnoz(chis_1, chis_2))

elif select == 4:
    print(chis_1, "/", chis_2, "=", delen(chis_1, chis_2))

else:
    print("Нет операции с таким номером")
