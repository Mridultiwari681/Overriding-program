# Animal Sound Using Method Overriding in Java

## 📌 Project Overview
This project demonstrates two important Object-Oriented Programming (OOP) concepts in Java: Abstraction and Method Overriding.

An abstract class named `Animal` defines the abstract method `sound()`. The `Dog` class extends `Animal` and implements the `sound()` method to display the sound made by a dog.

## 🛠️ Technologies Used
- Java
- Object-Oriented Programming (OOP)

## 💻 Source Code

```java
abstract class Animal {
    abstract void sound();
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}

class Main {
    public static void main(String[] args) {
        Dog a = new Dog();
        a.sound();
    }
}
``` 
## Output

Dog barks

## Concepts Covered
- Abstract Classes
- Method Overriding
- Inheritance
- Object Creation
- Method Calling

## Author
**Mridul Tiwari**

GitHub: https://github.com/Mridultiwari681
