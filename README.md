# AndreSilvaGusmaoStudy-C-Sharp
This document was strcutured by André Silva Gusmão.Check my socials, follow me and leave a message, if you will.
Socials:
https://linktr.ee/AndreSilvaGusmao

This document aims to guide the study of anyone about C#. Flash cards and flash cards for Brazilian exams were created as well.

# Index

1. [Introduction to C#](#Introduction_to_C#)
2. [Basic Concepts](#Basic_Concepts)
   1. [Data Types](#Data_Types)
      1. [Value Types](#Value_Types)
         1. [Integral Types](#Integral_Types)
         2. [Floating-Point Types](#Floating-Point_Types)
         3. [Decimal Type](#Decimal_Type)
         4. [Boolean Type](#Boolean_Type)
         5. [Character Type](#Character_Type)
      2. [Reference Types](#Reference_Types)
         1. [Object Type](#Object_Type)
         2. [Dynamic Type](#Dynamic_Type)
         3. [String Type](#String_Type)
   2. [Variables](#Variables)
      1. [Declaring Variables](#Declaring_Variables)
      2. [Assigning Values](#Assigning_Values)
      3. [Variable Scope](#Variable_Scope)
      4. [Constants](#Constants)
   3. [Operators](#Operators)
      1. [Arithmetic Operators](#Arithmetic_Operators)
      2. [Relational Operators](#Relational_Operators)
      3. [Logical Operators](#Logical_Operators)
      4. [Bitwise Operators](#Bitwise_Operators)
      5. [Assignment Operators](#Assignment_Operators)
      6. [Other Operators](#Other_Operators)
   4. [Control Structures](#Control_Structures)
      1. [If Statement](#If_Statement)
      2. [Switch Statement](#Switch_Statement)
   5. [Loops](#Loops)
      1. [For Loop](#For_Loop)
      2. [While Loop](#While_Loop)
      3. [Do-While Loop](#Do-While_Loop)
      4. [Foreach Loop](#Foreach_Loop)
   6. [Arrays](#Arrays)
      1. [Single-Dimensional Arrays](#Single-Dimensional_Arrays)
      2. [Multidimensional Arrays](#Multidimensional_Arrays)
      3. [Jagged Arrays](#Jagged_Arrays)
3. [Intermediate Concepts](#Intermediate_Concepts)
   1. [Classes and Objects](#Classes_and_Objects)
      1. [Class Definition](#Class_Definition)
      2. [Creating Objects](#Creating_Objects)
      3. [Constructors](#Constructors)
      4. [Destructors](#Destructors)
      5. [Properties](#Properties)
      6. [Methods](#Methods)
   2. [Inheritance](#Inheritance)
      1. [Base Classes](#Base_Classes)
      2. [Derived Classes](#Derived_Classes)
      3. [Abstract Classes](#Abstract_Classes)
      4. [Sealed Classes](#Sealed_Classes)
   3. [Polymorphism](#Polymorphism)
      1. [Method Overloading](#Method_Overloading)
      2. [Method Overriding](#Method_Overriding)
      3. [Virtual Methods](#Virtual_Methods)
   4. [Interfaces](#Interfaces)
      1. [Interface Definition](#Interface_Definition)
      2. [Implementing Interfaces](#Implementing_Interfaces)
   5. [Namespaces](#Namespaces)
      1. [Namespace Declaration](#Namespace_Declaration)
      2. [Using Directives](#Using_Directives)
      3. [Namespace Aliases](#Namespace_Aliases)
   6. [Delegates](#Delegates)
      1. [Delegate Declaration](#Delegate_Declaration)
      2. [Multicast Delegates](#Multicast_Delegates)
   7. [Events](#Events)
      1. [Event Declaration](#Event_Declaration)
      2. [Event Handlers](#Event_Handlers)
   8. [Exceptions](#Exceptions)
      1. [Exception Handling](#Exception_Handling)
      2. [Custom Exceptions](#Custom_Exceptions)
      3. [Using and Disposing Resources](#Using_and_Disposing_Resources)
   9. [File I/O](#File_I/O)
      1. [Reading and Writing Files](#Reading_and_Writing_Files)
      2. [Serialization](#Serialization)
   10. [Collections](#Collections)
      1. [Lists](#Lists)
      2. [Dictionaries](#Dictionaries)
      3. [Sets](#Sets)
      4. [Queues](#Queues)
      5. [Stacks](#Stacks)
   11. [Generics](#Generics)
      1. [Generic Classes](#Generic_Classes)
      2. [Generic Methods](#Generic_Methods)
      3. [Constraints](#Constraints)
4. [Advanced Concepts](#Advanced_Concepts)
   1. [LINQ](#LINQ)
      1. [LINQ Syntax](#LINQ_Syntax)
      2. [Deferred Execution](#Deferred_Execution)
      3. [Query Operators](#Query_Operators)
   2. [Asynchronous Programming](#Asynchronous_Programming)
      1. [Async and Await](#Async_and_Await)
      2. [Task Parallel Library](#Task_Parallel_Library)
   3. [Reflection](#Reflection)
      1. [Accessing Type Information](#Accessing_Type_Information)
      2. [Creating Instances Dynamically](#Creating_Instances_Dynamically)
         3. [Reflection](#Reflection) (continued)
      4. [Invoking Methods and Accessing Properties](#Invoking_Methods_and_Accessing_Properties)
      5. [Attributes](#Attributes)
   4. [Memory Management](#Memory_Management)
      1. [Garbage Collection](#Garbage_Collection)
      2. [Finalizers](#Finalizers)
      3. [Weak References](#Weak_References)
   5. [Regular Expressions](#Regular_Expressions)
      1. [Pattern Matching](#Pattern_Matching)
      2. [Groups and Captures](#Groups_and_Captures)
      3. [Lookaheads and Lookbehinds](#Lookaheads_and_Lookbehinds)
   6. [Networking](#Networking)
      1. [Sockets](#Sockets)
      2. [HTTP Requests](#HTTP_Requests)
      3. [Web Services](#Web_Services)
   7. [Multithreading](#Multithreading)
      1. [Threads](#Threads)
      2. [Thread Synchronization](#Thread_Synchronization)
      3. [Thread Pools](#Thread_Pools)
5. [Expert Concepts](#Expert_Concepts)
   1. [C# Language Design](#C#_Language_Design)
      1. [Language Evolution](#Language_Evolution)
      2. [Language Features](#Language_Features)
   2. [Compiler and Runtime](#Compiler_and_Runtime)
      1. [Compilation Process](#Compilation_Process)
      2. [Just-In-Time Compilation](#Just-In-Time_Compilation)
   3. [Code Optimization](#Code_Optimization)
      1. [Performance Profiling](#Performance_Profiling)
      2. [Code Analysis](#Code_Analysis)
   4. [Advanced Diagnostics](#Advanced_Diagnostics)
      1. [Debugging Techniques](#Debugging_Techniques)
      2. [Tracing and Logging](#Tracing_and_Logging)
   5. [C# and the .NET Ecosystem](#C#_and_the_.NET_Ecosystem)
      1. [C# and Other .NET Languages](#C#_and_Other_.NET_Languages)
      2. [Interoperability with Native Code](#Interoperability_with_Native_Code)
6. [Practice Projects](#Practice_Projects)
   1. [Console Applications](#Console_Applications)
   2. [Desktop Applications](#Desktop_Applications)
   3. [Web Applications](#Web_Applications)
   4. [Mobile Applications](#Mobile_Applications)
7. [Additional Resources](#Additional_Resources)
   1. [Books](#Books)
   2. [Online Courses](#Online_Courses)
   3. [Blogs](#Blogs)
   4. [Forums](#Forums)




==================================================================================================



<a name="Introduction_to_C#"></a>
## Introduction to C#

### Important points 📌
1. C# is a modern, object-oriented programming language.
2. Designed by Microsoft for the .NET Framework.
3. Provides a balance between simplicity and power.
4. Supports advanced features like garbage collection, type safety, and exception handling.
5. Widely used for web, desktop, mobile, and gaming development.

### Content table 📜

| Concept | Description |
| ------- | ----------- |
| Object-oriented programming | A programming paradigm focused on objects and their interactions. |
| .NET Framework | A software framework developed by Microsoft for building and running applications. |
| Garbage collection | Automatic memory management technique for deallocating unused memory. |
| Type safety | A language feature that helps prevent type errors in the code. |
| Exception handling | A mechanism for dealing with runtime errors gracefully. |

### References 📚
1. [C# Programming Yellow Book by Rob Miles](http://www.csharpcourse.com/)
2. [C# in Depth by Jon Skeet](https://www.manning.com/books/c-sharp-in-depth-third-edition)
3. [Microsoft C# Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)

### Diagram 📊
[An overview of the C# programming language](https://www.conceptdraw.com/How-To-Guide/picture/CSharp.png)

### 10 years old definition 👶
C# is a language that helps people tell computers what to do. It's like learning how to speak a secret code that computers understand.

### Definition 🧑
C# is a programming language developed by Microsoft that enables developers to create a wide range of applications, including web, desktop, and mobile applications. It's an object-oriented language, which means it focuses on working with objects and their interactions.

### PHD definition 🎓
C# is a statically typed, multi-paradigm programming language developed by Microsoft as part of the .NET initiative. It incorporates elements from both imperative and functional programming styles and supports features such as strong typing, automatic memory management, and exception handling. Its design principles emphasize simplicity, modernity, and expressiveness, allowing for the development of robust, maintainable software systems.

### Practical exercises🏋️
1. Install Visual Studio and create a new C# console application.
2. Write a program that calculates the area of a rectangle.
3. Create a simple calculator application that supports addition, subtraction, multiplication, and division.
4. Design a class hierarchy for a zoo, including various animal types and their characteristics.
5. Implement a basic file I/O operation to read and write data to a text file.
6. Develop a simple application that uses LINQ to filter and sort data.
7. Create a basic web application using ASP.NET Core and C#.
8. Design a mobile application using Xamarin and C#.

### Answers 👍
1. Download Visual Studio from the [official website](https://visualstudio.microsoft.com/downloads/), install it, and create a new C# console application by selecting "Create a new project" and choosing "Console App (.NET)".
```csharp
int width = 10;
int height = 5;
int area = width * height;
Console.WriteLine($"The area of the rectangle is {area}");
```

3. Calculator application:
```csharp
double num1, num2;
string operation;
double result = 0;

Console.WriteLine("Enter the first number:");
num1 = Convert.ToDouble(Console.ReadLine());

Console.WriteLine("Enter the second number:");
num2 = Convert.ToDouble(Console.ReadLine());

Console.WriteLine("Enter the operation = Console.ReadLine();

switch (operation)
{
    case "+":
        result = num1 + num2;
        break;
    case "-":
        result = num1 - num2;
        break;
    case "*":
        result = num1 * num2;
        break;
    case "/":
        if (num2 != 0)
            result = num1 / num2;
        else
        {
            Console.WriteLine("Cannot divide by zero.");
            return;
        }
        break;
    default:
        Console.WriteLine("Invalid operation.");
        return;
}

Console.WriteLine($"The result is {result}");
```

4. Zoo class hierarchy:
```csharp
public abstract class Animal
{
    public string Name { get; set; }
    public int Age { get; set; }

    public abstract void MakeSound();
}

public class Mammal : Animal
{
    public int NumberOfLegs { get; set; }
}

public class Bird : Animal
{
    public int WingSpan { get; set; }
}

public class Reptile : Animal
{
    public bool IsVenomous { get; set; }
}
```

5. Basic file I/O operation:
```csharp
string filePath = "example.txt";
string textToWrite = "Hello, World!";

File.WriteAllText(filePath, textToWrite);

string readText = File.ReadAllText(filePath);
Console.WriteLine(readText);
```

6. LINQ example:
```csharp
var numbers = new List<int> { 1, 5, 2, 8, 3, 7 };

var evenNumbers = from number in numbers
                  where number % 2 == 0
                  orderby number
                  select number;

foreach (var evenNumber in evenNumbers)
{
    Console.WriteLine(evenNumber);
}
```

7. For creating an ASP.NET Core web application, follow the [official tutorial](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-5.0&tabs=visual-studio).

8. For designing a mobile application using Xamarin and C#, follow the [official Xamarin.Forms tutorial](https://docs.microsoft.com/en-us/xamarin/get-started/first-app/?pivots=windows).

### Basic examples 🔰

1. Hello World:
```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```

2. Variables and data types:
```csharp
int age = 30;
string name = "John";
double height = 1.85;
bool isStudent = true;
```

3. If statement:
```csharp
int number = 10;

if (number > 5)
{
    Console.WriteLine("The number is greater than 5.");
}
else
{
    Console.WriteLine("The number is less than or equal to 5.");
}
```

4. Loops:
```csharp
for (int i = 0; i < 10; i++)
{
    Console.WriteLine($"The value of i is {i}");
}

int j = 0;
while (j < 10)
{
    Console.WriteLine($"The value of j is {j}");
    j++;
}
```

5. Arrays:
```csharp
int[] numbers = new int[] { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };

foreach (int number in numbers)
{
    Console.WriteLine(number);
}
```

6. Lists:
```csharp
List<string> names = new List<string> { "Alice", "Bob", "Charlie", "David" };

names.Add("Eva");
names.Remove("Bob");

foreach (string name in names)
{
    Console.WriteLine(name);
}
```

7. Methods:
```csharp
static int Add(int a, int b)
{
    return a + b;
}

int sum = Add(5, 10);
Console.WriteLine($"The sum is {sum}");
```

8. Classes:
```csharp
public class Person
{
    public string Name { get; set; }
    public int Age { get; set; }

    public void Introduce()
    {
        Console.WriteLine($"Hello, my name is {Name} and I am {Age} years old.");
    }
}

Person person = new Person { Name = "John", Age = 30 };
person.Introduce();
```

### Middle-ground examples ⚖️

1. Inheritance:
```csharp
public class Employee : Person
{
    public string Position { get; set; }

    public void Work()
    {
        Console.WriteLine($"{Name} is working as a {Position}.");
    }
}

Employee employee = new Employee { Name = "Alice", Age = 28, Position = "Software Engineer" };
employee.Introduce();
employee.Work();
```

2. Interfaces:
```csharp
public interface IDriveable
{
    void Drive();
}

public class Car : IDriveable
{
    public void Drive()
    {
        Console.WriteLine("Driving a car...");
    }
}

Car car = new Car();
car.Drive();
```

3. Delegates and events:
```csharp
public delegate void NumberChangedEventHandler(int oldValue, int newValue);

public class NumberChanger
{
    private int _number;
    public event NumberChangedEventHandler NumberChanged;

    public int Number
    {
        get => _number;
        set
        {
            int oldValue = _number;
            _number = value;
            NumberChanged?.Invoke(oldValue, _number);
        }
    }
}

NumberChanger numberChanger = new NumberChanger();
numberChanger.NumberChanged += (oldValue, newValue) =>
{
    Console.WriteLine($"Number changed from {oldValue} to {newValue}");
};

numberChanger.Number = 5;
```

4. Nullable value types:
```csharp
int? nullableInt = null;

if (nullableInt.HasValue)
{
    Console.WriteLine($"The value is {nullableInt.Value}");
}
else
{
    Console.WriteLine("The value is null.");
}
```

5. Extension methods:
```csharp
public static class StringExtensions
{
    public static string Reverse(this string input)
    {
        char[] charArray = input.ToCharArray();
        Array.Reverse(charArray);
        return new string(charArray);
    }
}

string originalText = "Hello, World!";
string reversedText = originalText.Reverse();
Console.WriteLine(reversedText);
```

6. Exception handling:
```csharp
try
{
    int result = 10 / 0;
}
catch (DivideByZeroException ex)
{
    Console.WriteLine("Cannot divide by zero.");
}
finally
{
    Console.WriteLine("Finished.");
}
```

7. Asynchronous programming:
```csharp
public async Task DoSomethingAsync()
{
    await Task.Delay(1000);
    Console.WriteLine("Finished waiting.");
}

await DoSomethingAsync();
```

8. LINQ:
```csharp
List<int> numbers = new List<int> { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };

var evenNumbers = numbers.Where(n => n % 2 == 0);

foreach (int evenNumber in evenNumbers)
{
    Console.WriteLine(evenNumber);
}
```

### Advanced examples 🚀

1. Attributes and reflection:
```csharp
public class MyAttribute : Attribute
{
    public string Description { get; set; }

    public MyAttribute(string description)
    {
        Description = description;
    }
}

[My("This is a sample class with an attribute.")]
public class SampleClass
{
}

Type type = typeof(SampleClass);
object[] attributes = type.GetCustomAttributes(typeof(MyAttribute), false);

if (attributes.Length > 0 && attributes[0] is MyAttribute attribute)
{
    Console.WriteLine(attribute.Description);
}
```

2. Dynamic and ExpandoObject:
```csharp
dynamic person = new ExpandoObject();
person.FirstName = "John";
person.LastName = "Doe";
person.Age = 30;

Console.WriteLine($"{person.FirstName} {person.LastName} is {person.Age} years old.");
```

3. Tuples and pattern matching:
```csharp
(string Name, int Age) GetPerson()
{
    return ("Alice", 28);
}

var person = GetPerson();
Console.WriteLine($"{person.Name} is {person.Age} years old.");

switch (person)
{
    case var (name, age) when age < 18:
        Console.WriteLine($"{name} is a child.");
        break;
    case var (name, age) when age >= 18 && age < 65:
        Console.WriteLine($"{name} is an adult.");
        break;
    case var (name, _):
        Console.WriteLine($"{name} is a senior.");
        break;
}
```

4. Custom exception handling:
```csharp
public class CustomException : ApplicationException
{
    public CustomException(string message) : base(message)
    {
    }
}

try
{
    throw new CustomException("This is a custom exception.");
}
catch (CustomException ex)
{
    Console.WriteLine(ex.Message);
}
```

5. Operator overloading:
```csharp
public class Complex
{
    public double Real { get; set; }
    public double Imaginary { get; set; }

    public Complex(double real, double imaginary)
    {
        Real = real;
        Imaginary = imaginary;
    }

    public static Complex operator +(Complex c1, Complex c2)
    {
        return new Complex(c1.Real + c2.Real, c1.Imaginary + c2.Imaginary);
    }

    public override string ToString()
    {
        return $"{Real} + {Imaginary}i";
    }
}

Complex c1 = new Complex(2, 3);
Complex c2 = new Complex(4, 5);
Complex result = c1 + c2;
Console.WriteLine(result);
```

6. Custom indexers:
```csharp
public class CustomList<T>
{
    private List<T> _list = new List<T>();

    public void Add(T item)
    {
        _list.Add(item);
    }

    public T this[int index]
    {
        get { return _list[index]; }
        set { _list[index] = value; }
    }
}

CustomList<int> numbers = new CustomList<int>();
numbers.Add(1);
numbers.Add(2);
numbers.Add(3);

Console.WriteLine(numbers[1]); // Output: 2
numbers[1] = 4;
Console.WriteLine(numbers[1]); // Output: 4
```

7. Extension methods:
```csharp
public static class StringExtensions
{
    public static string Reverse(this string str)
    {
        char[] charArray = str.ToCharArray();
        Array.Reverse(charArray);
        return new string(charArray);
    }
}

string original = "Hello, World!";
string reversed = original.Reverse();
Console.WriteLine(reversed); // Output: "!dlroW ,olleH"
```

8. Parallel programming with the Task Parallel Library (TPL):
```csharp
using System.Threading.Tasks;

int[] numbers = new int[] { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };

Parallel.ForEach(numbers, (number) =>
{
    Console.WriteLine($"Processing number {number} on thread {Thread.CurrentThread.ManagedThreadId}");
});
```










