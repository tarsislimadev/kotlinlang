# String Templates

A string value is a sequence of characters in double quotes `"`.

To print the contents of variables to standard output, you can use string templates.

You can use template expressions to convert data stored in variables to strings.

Template expressions always start with a dollar sign `$`.

```kotlin
fun main() {
    val customers = 10
    println("There are $customers customers") // There are 10 customers
    println("There are ${customers + 1} customers") // There are 11 customers
}
```

## links

[previous](#) - [next](#)
