Контрольная работа (Сложный уровень) Зебницкого Андрея МФ-72
#Задание №1
print("Введите длину, ширину и высоту для 3 прямоугольных параллелепипедов")
length = int(input())
width = int(input())
height = int(input())
length2 = int(input())
width2 = int(input())
height2 = int(input())
length3 = int(input())
width3 = int(input())
height3 = int(input())
volume1 = length*width*height
volume2 = length2*width2*height2
volume3 = length3*width3*height3
Volume_o = volume1+volume2+volume3
print(Volume_o) #Общий объем 3 прямоугольников


#Задание №2
num = int(input("Введите число,которое будет умножаться на таблицу умножения "))
for i in range(1,11):
    print(num*i)


#Задание №3
import math
n =int(input("Введите число"))
k = int(input("Введите 2 число"))
result = math.factorial(n)
result2 = math.factorial(k)
result3 = math.factorial(n-k)
result4 = result2*result3
C = result/result4
if n > k:
    print(C)
else:
    print('Ошибка')

