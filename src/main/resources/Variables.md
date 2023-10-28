[Regresar al menú principal](../../../README.md)

# Variables
Para declarar variables, usar la palabra clave “val” (Crea 
variables inmutables) y “var” (Crea variables mutables).

***Implementación:***
```kotlin
val popcorn = 5
val hotdog = 7
var customers = 10
customers = 8
fun main() {
    println(customers)
}
```

***Salida:***
```output
8
```

* La declaración de una variable inicia con “val” o “var”, seguido del nombre de la variable, luego el operador de asignación “=” y finalmente un valor a asignar.
* La palabra clave “val” permite declarar una variable de sólo lectura (Inmutable).
* La palabra clave “var” permite declarar una variable a la cual podemos modificar su valor (Mutable).  
* El tipado de Kotlin es estático, la primera vez que declaramos la variable se infiere su tipo automáticamente y este será el único tipo para dicha variable.
* Las variables pueden declararse de forma global o local (Dentro o fuera del contexto de la función “main”).
* Se recomienda usar “val” para la declaración de variables. Y se usará “var”, sólo si es estrictamente necesario.