# Java Questions

-------------------

# Lab1

1. Какой результат работы кода?
```java
int a = true ? null : 0
```

2. Какой результат работы кода?
```java
Integer i1 = 128;
Integer i2 = 128;
System.out.println(i1 == i2);

Integer i3 = 127;
Integer i4 = 127;
System.out.println( i3 == i4);
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
-------------------

# Lab 3

1. Реализовать свой объект для foreach

