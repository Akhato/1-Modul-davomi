# 1-Modul-davomi
# 1. Напишите код, который создает переменную `name` и присваивает ей строковое значение. Затем выведите значение переменной на экран.
name = "Shaxzod'
print(name)
# 2. Создайте список из трех элементов и измените второй элемент на новое значение. Напечатайте измененный список.
moshinalar = ['kobalt','BYD Song','matiz']
moshinalar[1] = 'damas'
print(moshinalar)
# 3. Напишите код, который вычисляет сумму двух чисел и выводит результат на экран.
a = int(input('birinchi sonni kiriting  '))
b = int(input('ikkinchi sonni kiriting  '))
c = a+b
print('sonlar yigindisi', c)
#4. Создайте строку и используйте метод `.replace()` для замены определенного слова на другое.
matn = 'Python dasturlash tilini ozlashtirish korsatkichi'
matn_new = matn.replace('ozlashtirish','ozlashtiraolmaslik')
print(matn_new)
#5. Напишите функцию, которая принимает два числа и возвращает их произведение.
def multiply(a, b):
    return a * b

result = multiply(4, 5)
print(result)
#6. Используя цикл `for`, создайте код, который выводит числа от 1 до 10 на одной строке, разделенные пробелом.
sonlar = list(range(1,11))
for son in sonlar:
    print(son, end=' ')
#7. Напишите код, который создает словарь с тремя ключами и значениями, и затем изменяет значение одного из ключей.
car_0 = {'model':'malibu','matori':1.5}
car_0['matori'] = 1.8
print(car_0)
#8. Создайте кортеж с 4 элементами и напечатайте его длину.
car_0 = ['matiz','damas','tiko','malibu']
uzunlik = len(car_0)
print(uzunlik)
#9. Используя цикл `while`, напишите код, который выводит числа от 10 до 1 в обратном порядке.
son = 10
while son >= 1:
    print(son, end= ' ')
    son = son - 1
#10. Напишите функцию, которая принимает список чисел и возвращает список, содержащий только четные числа.

son = list(range(2,100,2))
print(son)

#11. Используя метод `.split()`, разделите строку на слова и напечатайте каждое слово на новой строке.
manzil = 'Samarqand viloyati Narpay tumani Oqtosh shaxarchasi'
ruyxat = manzil.split(" ")
for i in ruyxat:
    print(i)
#12. Напишите код, который создает пустое множество и добавляет в него три элемента.
odam = []
odam.append('Bekzod')
odam.append('Sherzod')
odam.append('Ozod')

print(odam)

#13. Создайте строку и используйте метод `.find()` для поиска индекса первого вхождения подстроки.

text = 'Samarqand viloyati Narpay tumani Oqtosh shaxarchasi'
index = text.find('tumani')
print(index)

#15. Напишите функцию, которая принимает строку и возвращает строку, перевернутую задом наперед.

numbers = [25,65,85,25,13,62,15,89,94,75]
numbers.sort()
print(numbers)

#16. Используя функцию `range()`, напишите код, который создает список из первых 5 квадратов чисел (1, 4, 9, 16, 25).

sonlar = list(range(1,6))
kvadrati = []
for i in sonlar:
    i = i*i
    kvadrati.append(i)
print(kvadrati)

#17. Напишите код, который проверяет, является ли число положительным, отрицательным или нулем, и выводит соответствующее сообщение.


son = float(input('sonni kiring = '))
if son > 0:
    print('kiritilgan son musbat')
elif son == 0:
    print('bu son nolga teng')
elif son < 0:
    print('bu son manfiy son')
