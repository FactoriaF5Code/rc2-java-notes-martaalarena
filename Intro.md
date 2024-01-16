# Introducción 
**Crear una clase es imprescindible**
1. (En un documento que se llama main.java)
1. llamaré a mi clase main
```
public static void main (String[] args) {
    System.out.println("Hola mundo!")
}
```
1. lo que vaya dentro del println tiene que ir entre comillas "" si es texto y sin nada si son números
1. para comentar se utiliza // una línea y /* */ para multiples líneas.

## Variables 
**Diferentes tipos de variables**

+ String : solo para texto "hola"
+ int : numeros enteros 10, 50, 64
+ float: numeros decimales 19.99 o -19.99
+ char: caracteres solos como 'a' o 'B'
+ boolean: cuando devuelvem true o false.

### Ejemplo de uso de variables 

+ String name = "John"
+ int myNum = 15
+ float myDecimal = 19.99
+ char myLetter = 'a'
+ boolean myBool = true

### Para imprimir varias variables 
```
int x = 5;
int y = 6;
int z = 50;
System.out.println(x + y + z);
```
**o**
```
int x = 5, y = 6, z = 50;
System.out.println(x + y + z);
```

