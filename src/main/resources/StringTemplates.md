[Regresar al menú principal](../../../README.md)

# String templates
Para incluir el valor de una “variable” o “bloque de código” como parte de una cadena a imprimirse con “println()”, podemos usar “Template expressions”.

***Implementación:***
```kotlin
fun main() {
    val customers = 10

    //template expression for variable ($customers)
    println("There are $customers customers")

    //template expression for piece of code (${customers + 1})
    println("There are ${customers + 1} customers")
}
```

***Salida:***
```output
There are 10 customers
There are 11 customers
```

* Los template expressions siempre comienzan con el símbolo “$”.
* Para imprimir el valor de una variable, se define del siguiente modo: $customers.
* Para imprimir el resultado de un bloque de código, se define del siguiente modo: ${customers + 1}.
* Los template expressions convierten el valor o resultado de la variable o bloque de código en un string. Este string se integra con el texto a imprimir de forma natural, no deberíamos concatenar usando el símbolo “+”.
