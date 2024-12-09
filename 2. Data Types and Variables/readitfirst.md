# Understanding Objects in Dart

## Introduction to Objects
We are surrounded by objects in our daily lives. Everything we own or interact with can be considered an object.  
For example, a **car** is an object, and it has both **characteristics** and **behaviors**.

### Traits of Objects
1. **Traits (Characteristics)**: Describe the properties of the object (e.g., manufacturer, model, year).
2. **Behaviors**: Define what the object can do or what can be done to it (e.g., accelerate, reverse).

---

## Objects in Dart
In Dart, objects are composed of two main components:
1. **Data**: Represents the properties or attributes of the object.
2. **Methods**: Functions that define the behavior of the object.
   - Methods can receive messages, send messages, and process data.

---

## Key Aspects of an Object
1. **Identity**: A unique identifier for the object.
2. **State**: Represents the properties of the object at a given time.
3. **Behavior**: Defines the possible actions or interactions of the object.

---

## Example: Car Object
- **Identity**: The car's unique serial number.
- **State**: Its properties like manufacturer, model, year, and color.
- **Behavior**: Actions like accelerating, reversing, or stopping.

---

## Summary
Objects can:
- Perform actions (e.g., a car can accelerate).
- Have actions performed on them (e.g., a car can be repainted).  
Objects are fundamental in object-oriented programming, like Dart, as they represent real-world entities and interactions.


# Variables

## What Are Variables?
Variables are used across various disciplines, such as mathematics, programming, and engineering.  
A common example is calculating the **area of a circle** in mathematics.

In programming, **variables** act as containers that store data in memory. This stored data can be retrieved and used whenever needed.

## How Variables Work
- The computer's memory has **registers (bits)** that are used to store data.
- A **variable** represents a piece of data stored in memory, with a specific name for easy reference.
- The **value** assigned to the variable is what is stored in memory.

### Example
Numbers like `5` and `20` can be stored in variables, allowing us to use them later in calculations or operations.

```dart
void main() {
  var number1 = 5; // A variable storing the value 5
  var number2 = 20; // A variable storing the value 20
  
  print(number1); // Output: 5
  print(number2); // Output: 20
}
