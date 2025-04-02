---
title: Swift Day 2
date: 2025-04-01
draft: false
description: Description of the page used for link previews. Delete this if not wanted
tags:
---
---

```swift

// Booleans
var isMultiple = 120.isMultiple(of: 3)
// false, true, flip it with !
isMultiple.toggled()
// isMultiple is now flipped, so it's false.

// Join Strings
// Concat, "Hello " + "World" works
// Concats are slow though... imagine "A" + "B" + "C"... so on...
// This means you add each string individual, so "AB" + C... "ABC" + D...
// This is where String interpolation comes in.

let number = 11
let message = "Hey! My favorite number is \(number)"

// If you didnt do this and concat, you will have to do String(number)

// You can also do calculations like \(number * 5) in the string.

//Summary:
// let for const, var for variables (Different than JS)
// Other types: Int, Double, String, Boolean, and their functionality like properities like count instead of length and methods like uppercased()
```


```swift

let tempInCelsius = Double(20)
let tempInFahrenheit = (tempInCelsius * Double(9))/Double(5) + Double(32)
print("Celsius is \(tempInCelsius)")

// My code after, main thing is swift autoconverts, so if you use a double it will stay a double.
let tempInCelsius = 21.0

let tempInFahrenheit = (tempInCelsius * 9)/5 + 32

print("Celsius is \(tempInCelsius)")

print("Fahrenheit is \(tempInFahrenheit)")
```

See ya, 
--Brody
