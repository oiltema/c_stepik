## Числовые типы данных
Имеются разные типы данных для чисел:
int - простое число
doubel - более точное число с плавующей точкой
float - точное число с плавующей точкой
long - число более 3000000000

## Каст
есть явный каст или не явный каст
то есть ты можем из int сделать double без потери информации, но наоборот - нам нужно указывать каст(наше потверждение того что мы делаем специальную потерю информации)


каст - это не округление, для округления нужно использовать метод Math.Round()
Этот метод не делает каст он после своей работы выдаёт нам тот же самый тип данных что и на входе

## e
число с е - это число со сдвигом запятой, этот сдвиг показывается числом после запятой
то есть 123,45е-2 = 1,2345
12,45е00 = 12,45 

## Строка
ввод с консоли это всегда строка
sting - строка обозначается ""
char - символ обозначается  ''
для того что бы преобразовать число в строку нужно воспользоваться:
```c
int.Parse(); // fit to double

str.ToString(); // из числа в строку
Console.ReedLine(); //input string
```
