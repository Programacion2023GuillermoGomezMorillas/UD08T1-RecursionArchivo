## UD08T1-Recursion

#### 2. ¿Qué imprime el siguiente código si llamamos al método con la expresión mystery(0);?

Imprime los numeros del 0 al 6.

#### ¿Y con mystery(100);?

Imprime 100, pues es mayor que 5.

#### 3. ¿Qué imprime el siguiente código si llamamos al método con mystery(5);?

Va restando 1 desde la posición 5 hasta que salta el error de StackOverflow porque colapsa la memoria.

#### 4. ¿Qué hace el siguiente algoritmo? Realiza una traza cualquiera.

Lo que hace es multiplicar los dos números que tu le pongas.

#### 5. Escribe una función recursiva para realizar el cálculo del exponente: x^e, sabiendo que todo número elevado a 0 = 1.
```
public static int exponente(int x, int y) {
if (y == 0) {
return 1;
}
return (x * exponente(x, y-1));}
```
#### 6. Dado el ejercicio anterior, escribe la versión iterativa del método del cálculo del exponente.
```
public static int exponente(int x, int exp) {
int resultado = 1;
for (int i=0; i < exp; i++){
resultado = resultado * x;
}
return resultado;
}
```
#### 7. Crea una función recursiva que calcule la sucesión de Fibonacci hasta un número dado y la muestre por pantalla
```
    public static int fibonacci(int num){
        if(num == 0 || num==1)
            return num;
        else
            return fibonacci(num-1) + fibonacci(num-2);
    }
}
```

