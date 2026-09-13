# Overriding-program
abstract class Animal {     abstract void sound(); }  class Dog extends Animal {     void sound() {         System.out.println("Dog barks");     } }  class Main {     public static void main() {         Dog  a = new Dog();         a.sound();     } }
