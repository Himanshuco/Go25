# Variable 

    These variable types are essential in Go and are used to store different kinds of data.

Here are the basic variable types in Go:

- **bool**: A boolean value, either `true` or `false`.
- **string**: A sequence of characters (e.g., `"Hello, World!"`).
- **int**: A signed integer, which can store both positive and negative whole numbers (e.g., `42`).
- **float64**: A floating-point number, typically used for decimal numbers (e.g., `3.14159`).
- **byte**: Exactly what it sounds like: 8 bits of data, often used to represent a single character in a string (e.g., `'A'`).

# Declaring a Variable in Go

In Go, variables can be declared in two ways: using the `var` keyword or using the shorthand `:=` syntax.

## a) Using the `var` Keyword

The `var` keyword is used to declare a variable with a specified type. The general syntax is:

```go
var variableName type = value
```

    **NOTE** :- 
        1. We always need to specify either type or value or both.
        2. Can be used inside or outside function.

## b) Using the ` := `

The `:=` syntax is shorthand for declaring and initializing a variable. 

```go
variableName := value
```

    **NOTE** :- 
        1. Here Assignment is must.
        2. Can be used only inside function.
        3. When variables are declared but they are not been assigned initial values so they have default calues of their respective type.
        4. Type of varibale is inferred from the value.





