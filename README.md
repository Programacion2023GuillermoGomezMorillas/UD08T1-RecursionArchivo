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
public static int fun(int x, int y) {
if (y == 0) {
return 1;
}
return (x * fun(x, y-1)); }
```
