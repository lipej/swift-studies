# swift-studies

## doing your first hello world

```swift
print("Hello World")
```

## Variables & constants

### declare a variable

- to declare a variable in swift use:  ```var```
  + variables is useful when you need to manipulate a value

#### example:
```swift 
var amount = 1
amount += 1

print(amount) //output 2
```

### declare a constant

- to declare a constant in swift use:  ```let```
  + constants is useful when you don't want a value can be mutable

#### example:
```swift 
let pi: Double = 3.14
```

---

## Basic types

- Int: integers
- Double: floating-point numbers
- String: a sequence of characters
- Bool: true/false

#### examples:

```swift 
var age: Int = 27
 
var price: Double = 1.99
 
var message: String = "this is good"
 
var lateToWork: Bool = true
```

--- 

## Arithmetic Operators

- ```+``` addition
- ```-``` subtraction
- ```*``` multiplication
- ```/``` division
- ```%``` remainder

#### you can use with compound assignment operators too:

```swift
var age: Int = 30

age += 1 //31
age -= 1 //30
age *= 2 //60
age /= 2 //30
age %= 2 //0
```

---

## String Interpolation

- string interpolation is very easy in swift:

```swift 
var price: Double = 299.99

print("this xbox one series s costs \(price) dollars")

//output: this xbox one series s costs 299.99 dollars
```