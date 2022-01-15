# HW1
![image](https://user-images.githubusercontent.com/83466117/148700613-ca53fb6e-5e52-4b2e-b0e8-d9bbfb649b1f.png)

     
OOP's expression is object oriented programming.First programming languages like C are based on procedural programming. Procedural programming is writing functions then perfors on data. Then, OOP programming comes with differences. OOP programming is about creating object contain data and functions. 
The most popular OOP languages are C++,Python, C# and Java.


![image](https://user-images.githubusercontent.com/83466117/148700661-a5d6c512-6c47-4c58-881e-3b7d6ad60c49.png)




| |  Abstract class|Interface|
| :--- | :---: | :---: |
| 1 | Abstract class can have abstract and non-abstract methods. | Interface can have only abstract methods. Since Java 8, it can have default and static methods also. |
| 2| Abstract class doesn't support multiple inheritance.	 | Interface supports multiple inheritance. |
| 3|  Abstract class can have final, non-final, static and non-static variables.	 |Interface has only static and final variables. |
|4|Abstract class can provide the implementation of interface.|Interface can't provide the implementation of abstract class.|

![image](https://user-images.githubusercontent.com/83466117/149574479-cb8550f3-fa13-4295-913b-f4bc9daa8e31.png)

The default implementation of equals() in the class Object says that equality is the same as object identity. And income and expenses are two distinct instances.hashCode() returns an integer representing the current instance of the class. We should calculate this value consistent with the definition of equality for the class. Thus if we override the equals() method, we also have to override hashCode().

![image](https://user-images.githubusercontent.com/83466117/149574687-db68f92e-80b6-41c3-bec6-f46f105d5530.png)
 
 In Java, the diamond problem is related to multiple inheritance. Sometimes it is also known as the deadly diamond problem or deadly diamond of death. We can support the functionality of multiple inheritance( Diamond Problem Solution) with interface.

![image](https://user-images.githubusercontent.com/83466117/149575765-b64a02be-6a64-47a7-993f-c7d26770a032.png)


It is a recycling operation handled by JVM for the memory that not being used by a JAVA application. It is triggered by dead object which is the unreachable since it is not reference from anywhere

![image](https://user-images.githubusercontent.com/83466117/149575670-5c3b5688-2017-4908-95f7-77f0358d6b65.png)

The static keyword is a non-access modifier used for methods and attributes. Static methods/attributes can be accessed without creating an object of a class.

![image](https://user-images.githubusercontent.com/83466117/149575826-efed6259-97f9-4937-9685-bf995184c2df.png)

An object is considered immutable if its state cannot change after it is constructed. Maximum reliance on immutable objects is widely accepted as a sound strategy for creating simple, reliable code.

Immutable objects are particularly useful in concurrent applications. Since they cannot change state, they cannot be corrupted by thread interference or observed in an inconsistent state.

![image](https://user-images.githubusercontent.com/83466117/149576531-e500b10a-cc7a-4d81-84a0-15109418d652.png)

Aggregation is a special case of association when an object ‘has-a’ another object, which you can have an aggregation between them. The composition is a special case of Aggregation that helps you to specify a whole-part relationship between the composition class and a subordinate (part) class.Aggregation is indicated using a straight line with an empty arrowhead at one end. On the other hand, the composition is indicated using a straight line with a filled arrowhead at any one of the ends.
In an aggregation relationship, objects that are associated with each other can remain in the scope of a system without each other. But in a composition relationship, objects that are associated with each other cannot remain in the scope without each other.
In Aggregation, linked objects are not dependent upon the other object whereas in composition, objects are highly dependent upon each other.


![image](https://user-images.githubusercontent.com/83466117/149576736-cb967a6a-2428-4216-8137-fc4c0a7a4531.png)

Cohesion is defined as the degree to which the elements of a particular module are functionally related. Basically, cohesion is used to measure the functional strength of a module.

Coupling is defined as the degree to which the two modules are dependent on each other. It measures the strength of relationships between modules.

The major difference between cohesion and coupling is that cohesion deals with the interconnection between the elements of the same module.

![image](https://user-images.githubusercontent.com/83466117/149577340-e2b88a6c-e461-4f29-b692-8c377fdc1dfa.png)

A stack is a special area of computer’s memory which stores temporary variables created by a function. In stack, variables are declared, stored and initialized during runtime.

It is a temporary storage memory. When the computing task is complete, the memory of the variable will be automatically erased. The stack section mostly contains methods, local variable, and reference variables.

The heap is a memory used by programming languages to store global variables. By default, all global variable are stored in heap memory space. It supports Dynamic memory allocation.

The heap is not managed automatically for you and is not as tightly managed by the CPU. It is more like a free-floating region of memory.

**Differences**

1)Stack is a linear data structure whereas Heap is a hierarchical data structure.
2)Stack memory will never become fragmented whereas Heap memory can become fragmented as blocks of memory are first allocated and then freed.
3)Stack accesses local variables only while Heap allows you to access variables globally.
4)Stack variables can’t be resized whereas Heap variables can be resized.
5)Stack memory is allocated in a contiguous block whereas Heap memory is allocated in any random order.
6)Stack doesn’t require to de-allocate variables whereas in Heap de-allocation is needed.
7)Stack allocation and deallocation are done by compiler instructions whereas Heap allocation and deallocation is done by the programmer.

![image](https://user-images.githubusercontent.com/83466117/149577806-f9684fa9-ed09-4be1-bb01-574cf27950d5.png)

When a program violates the semantic constraints of the Java programming language, the Java Virtual Machine signals this error to the program as an exception.

Built-in exceptions are the exceptions which are available in Java libraries. These exceptions are suitable to explain certain error situations. Besides, there are user-defined exceptions, too

![image](https://user-images.githubusercontent.com/83466117/149578590-78ae0cbe-3173-439e-9eed-df40c5b277b6.png)

Clean code can be read and enhanced by a developer other than its original author with understandability comes readability, changeability, extensibility and maintainability

![image](https://user-images.githubusercontent.com/83466117/149578677-4c542e8d-b6d0-4e68-a6f5-bbc03da953f2.png)

Method hiding means subclass has defined a class method with the same signature as a class method in the superclass.

![image](https://user-images.githubusercontent.com/83466117/149578743-0d845217-5cde-4080-af60-82a0d72a2a52.png)

Data abstraction means information hiding. Usually what is hidden is the representation of a data structure. Example: I implement sets, but I don't tell you whether a set is represented as a list, a balanced binary tree, or an unbalanced binary tree. Done right, I can change representation without breaking your code.

Polymorphism means reuse with different types. So with my set example you could create sets of Social Security numbers, sets of full names, or sets of fruitbats, all using the same code.
