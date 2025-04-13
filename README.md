# Proyecto de Soluciones a Problemas de Java

Este repositorio contiene soluciones a varios problemas de programación en Java. Cada uno de estos problemas se encuentra en una clase independiente y puede ser ejecutado de manera individual.

## Problemas Resueltos

### 1) **Mínimo de Operaciones**

#### Descripción:
Se te da una cadena binaria representando cajas. Cada caja puede estar vacía ('0') o contener una bola ('1'). En una operación, puedes mover una bola de una caja a una caja adyacente. El objetivo es calcular el número mínimo de operaciones necesarias para mover todas las bolas a cada caja.

#### Entrada:
- `cajas = "110"`

#### Salida:
- `Resultado: [1, 1, 3]`

### 2) **Agrupar Personas**

#### Descripción:
Dado un arreglo `groupSizes` donde cada elemento indica el tamaño del grupo de una persona, se debe agrupar a las personas en grupos del tamaño correspondiente. El objetivo es devolver una lista de grupos donde cada persona está en su grupo adecuado.

#### Entrada:
- `groupSizes = [3, 3, 3, 3, 3, 1, 3]`

#### Salida:
- `Resultado: [[5], [0, 1, 2], [3, 4, 6]]`

### 3) **Convertir un Arreglo en Matriz**

#### Descripción:
Dado un arreglo de números enteros, el objetivo es convertirlo en una matriz 2D de manera que cada fila contenga números únicos y el número total de filas sea el mínimo posible.

#### Entrada:
- `nums = [1, 3, 4, 1, 2, 3, 1]`

#### Salida:
- `Resultado: [[1, 3, 4, 2], [1, 3], [1]]`

### 4) **Ordenar los Elementos por Frecuencia**

#### Descripción:
Se te da un arreglo de números enteros. El objetivo es ordenar los números por su frecuencia de aparición, de manera que los números más frecuentes aparezcan primero. En caso de empate, se debe mantener el orden relativo de los números.

#### Entrada:
- `nums = [4, 3, 1, 6, 3, 4, 4, 6]`

#### Salida:
- `Resultado: [4, 4, 4, 3, 3, 6, 6, 1]`

## Estructura del Proyecto

Este proyecto contiene cuatro clases, cada una con una solución independiente a uno de los problemas:

- **MinimoOperaciones.java**: Resuelve el problema de mover bolas entre cajas con el mínimo de operaciones.
- **AgruparPersonas.java**: Resuelve el problema de agrupar personas según el tamaño de su grupo.
- **ConvertirArreglo.java**: Resuelve el problema de convertir un arreglo en una matriz 2D.
- **OrdenarPorFrecuencia.java**: Resuelve el problema de ordenar un arreglo según la frecuencia de sus elementos.

Cada clase tiene un método principal (`main`) que puede ser ejecutado individualmente para probar las soluciones.
