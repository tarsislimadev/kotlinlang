# Variables

Variables help you to store data in programs.

In Kotlin, you can declare:

- Read-only variables with `val`

- Mutable variables with `var`

Use the assignment operator `=` to assign a value.

```kotlin
fun main () {
    val popcorn = 5
    println("There are " + popcorn + " boxes of popcorn")
    
    val hotdog = 7
    println("There are " + hotdog + " hotdogs")

    var customers = 10
    println("There are " + customers + " customers in the queue")

    customers = 8
    println("Now, there are " + customers + " customers in the queue")
}
```
