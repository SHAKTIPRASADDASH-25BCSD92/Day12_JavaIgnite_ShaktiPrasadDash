# Day12_JavaIgnite
Differentiate between:

Method Overloading

Method Overriding

Provide one example scenario for each.
ans-Method overloading means multiple methods in the same classnwith the same name but differeent parameters eg-calculator class that needs to add numbers
method overriding means a method in the subclass with the same name parameters and return type as one in its superclass eg- an animal base c90lasss and a dog subclass




Question 2

What is the purpose of Wrapper Classes?

Why can't we directly use primitive data types in some Java collections?
The purpose of wrapper classs is to convert primitive data types into objects
it is because the java\ collection frame work is based on only on objects and generics





Question 3

Differentiate between:

FileWriter

FileOutputStream

When would you choose one over the other?
file writer is charcater oriented which is best for writing text files
File outputStream is byte oriented best for binary files us it when you are dealing with  non text data like images


Explain Inheritance using a real-world example.
parent class vehicle inside it has bikes trucks cars rickshaws autos
in cars we can have a specific property that no of wheels

How does inheritance help reduce code duplication?
it helps instead of writing same logic in multiple class we write in parent class only the new ones to be written in the class


Important Interview Question - 

class Animal {
    void sound() {
        System.out.println("Animal Sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Bark");
    }
}

Animal a = new Dog();
a.sound();

What will be the output?
Bark
Explain why.
This is Method Overriding



