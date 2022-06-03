# Java Questions

-------------------

# Lab1

## Типы данных, типизация

1. Какой результат работы кода?
```java
int a = true ? null : 0
```

2. Найти ошибки компиляции и исполнения, назвать значения каждой переменной.
```java
int a = 0,
 b = 10,
 c = 6,
 d = 4,
 e = 11.1,
 f = b / a,
 g = c / d,
 h = 10 / 0,
 i = 6.0 / 4;
double j = 0,
 k = 6,
 l = 5,
 m = k / j,
 n = k / l,
 o = b / a,
 p = 10 / 0;
```

3. Написать калькулятор для больших чисел

4. Какой результат работы кода?
```java
System.out.print(null);
```

5. Какой результат работы кода?
```java
 String abc = "abc";
 String ab = "ab";
 String c = "c";
 String abc1 = "ab"+"c";
 String abc2 = ab + c;
 System.out.print(abc == abc1);
 System.out.print(abc == abc2);
```
6. Какой результат работы кода? Напишите программу, которая выведет такой же результат.
```java
System.out.println(2.0 % 0);
``` 

## Операторы и приоритеты
1. 
```java
int a = 4;
a > 3 ? System.out.println(1) : System.out.println(2)
```
Для чего нужен тернарный оператор?

2. Как изменится результат выполнения при замене `||` на `|` 
```java
int a = 0;
if (a == 0 || 10 / a > 1) {
 System.out.println(1);
}
```


## Управляющие конструкции

1. Для чего нужен оператор switch.
Исправить ошибки компиляции в коде и сказать результат его выполнения.
```java
int a = 10;
int b = 11;
++b;
switch (a) {
 case 9: System.out.println(1);
 case 10: System.out.println(2);
 case 11: System.out.println(3);
 case b: System.out.println(4);
 default: System.out.println(5);
}
```

## JDK, JRE, JVM
1. 
```bash
javac Main.java
java Main
```
Какие действия будут происходить при выполнении этих команд (какие файлы будут искаться, какие будут созданы, с чего начнётся исполнение программы...)

2. Поставить точку останова при помощи утилиты jdb и проверить значения переменных

3. Что такое стек и куча?

4. Утилита javap, чем отличается
```java
int a = 1 + 1;
int b = 1;
int c = 1;
int a1 = b + c;
```

-------------------

# Lab2

1. 
```java
String[] strings = new String[1];
Object[] objects = strings;
objects[1] = new Object()
```

2. Можно ли вызывать метод на null?
```java
public class Test{

public static void show(){
       System.out.println("Static method");
}

public static void main(String[] args){
 A a = null;
   a.show();
  }
}
```

3. Какой результат работы кода?
```java
Integer i1 = 128;
Integer i2 = 128;
System.out.println(i1 == i2);

Integer i3 = 127;
Integer i4 = 127;
System.out.println( i3 == i4);
-------------------
```

# Lab 3

1. Реализовать свой объект для foreach
2. Когда стоит использовать интерфейс, а когда абстрактный класс?
3. Написать класс который можно передать в foreach и он возвращает значение последовательности фибоначи

# Lab 6

1. Обеспечить передачу объектов произвольного размера (больше размера буффера)
2. Написать http клиент (с использованием tcp )
3. Написать http сервер ( с импользованием tcp )

# Lab 7

1. Вернуть значение первого закончившего свою работу потока без использования anyOf()

# Lab 8

1. Добавить задержку на сервере, без зависания интерфейса
