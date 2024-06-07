
# Java(1995)


#### Java is a programming language and a platform. Java is a high level, object-oriented and secure programming language.
## Platform: 
##### Any hardware or software environment in which a program runs, is known as a platform. Since Java has a runtime environment (JRE) and API, it is called a platform.

##### Object-oriented programming (OOPs) is a methodology that simplifies software development and maintenance by providing some rules.
## Basic concepts of OOPs are:
#### 1.	Object
#### 2.	Class
#### 3.	Inheritance
#### 4.	Polymorphism
#### 5.	Abstraction
#### 6.	Encapsulation

## Java is architecture neutral because there are no implementation dependent features, for example, the size of primitive types is fixed.
#### In C programming, int data type occupies 2 bytes of memory for 32-bit architecture and 4 bytes of memory for 64-bit architecture. However, it occupies 4 bytes of memory for both 32 and 64-bit architectures in Java.

## Negatives
##### Java is an interpreted language that is why it is slower than compiled languages
##### Java doesn't support multiple inheritance through class. It can be achieved by using interfaces in java.

### Java does not support operator overloading (its diff from method overloading) 
###### In Java, unlike some other programming languages such as C++ or Python, operator overloading is not directly supported for user-defined types.
###### Operator overloading refers to defining the behavior of operators such as +, -, *, /, etc., for user-defined types (objects) in a way that makes sense for those types.
###### For example, in C++, you can overload operators to work with custom types, like defining how the + operator should behave for two objects of a user-defined class.
###### Here's a simplified example of operator overloading in C++:

class Complex {
private:
    int real;
    int imag;
public:
    Complex(int r, int i) : real(r), imag(i) {}
    
    Complex operator+(const Complex& other) {
        Complex result(real + other.real, imag + other.imag);
        return result;
    }
};

##### In this C++ example, the + operator is overloaded for the Complex class so that it can be used to add two Complex objects together.
##### However, in Java, operator overloading is not directly supported. The operators in Java have predefined behaviors for built-in types (e.g., + performs addition for numbers, concatenation for strings). For user-defined types, you can't directly define how operators should behave like you can in C++.
#### In Java, if you want similar functionality to operator overloading, you typically achieve it by defining methods with meaningful names instead of overloading operators. For example, you might define a method like add instead of overloading the + operator. This approach makes the code more readable and understandable.





## Multi-threaded
##### A thread is like a separate program, executing concurrently. We can write Java programs that deal with many tasks at once by defining multiple threads. The main advantage of multi-threading is that it doesn't occupy memory for each thread. It shares a common memory area. Threads are important for multi-media, Web applications, etc.



