__Обозначение и Объяснения__
===========================
## Программа которая из имеющегося массива строк формируют массив из строк , длина которого < либо = 3 символам . Изначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.При решение не рекомендуется пользоваться коллекциями , лучше обойтись исключительно массивами.
Пример ("hello;2:world;^^;top)  вывод -> [2;^^;top]

# Алгоритм и решение 
===================
+ начало алгоритма 
+ пользователю дается информация на ввод 
+ обьяснения принципа ввода
+ программа производит действия 
+ разделение на два вывода информации 
  + если есть соответствия 
  + если нет соответствия
+ конец работы программы 
  ___Принцип решения___:
## Пользователю дается информация на ввод данных и так же какие методы разделения доступны 
+ сам ввод осуществляется за счет оператора string  и переменной maf
+ обозначается метод формирования массива через Split и указавыется методы разделения для символов(текста и чисел)
## Программа производит отборку по своим параметрам отсеивания а именно < или = 3  , так же если  > 3  и по указаным символам пользователем
+ работа с оператором var и с его помощью назначаем переменную Array
+ добавляем работу с оператом Select и его возможностями 
+ From  берёт символы в переменной maf
+ Where уточняет метод проверки и выборки

## Делает вывод массива или текста   в соответсвиями с условиями и совпадениями
 + за счет операторов If % Else для уточнения метода вывода текста по параметру соответсвия 
 + заключительное обрамление и вывод соответствующего текста 
-->> ___Есть момент пояснения для пользователя___ 
 
 Итоговый проект выполнил Мухамеджанов А.Ф.