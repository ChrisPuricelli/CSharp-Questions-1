# CSharp-Questions-1
Repository holding the questions and answers for the same assignment
***

1. Q: What is a namespace?
- A namespace essentially seems like a container for programs. It holds all the variables, methods, etc. within it, and doesn't allow another namespace to use the variables defined within it. From tutorialspoint, "The class names declared in one namespace does not conflict with the same class names declared in another." However, it's possible to call a method/use a variable from one namespace in a different namespace.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_namespaces.htm "Namespaces")

2. Q: What are value types?
- Value types are basically variables that are created which when utilized/called will provide an actual value rather than output a location in memory. For instance, an integer (int) type variable is a value type because when it's called it will output the value it currently holds. When it's intially created the system will set aside memory intended for the value that's going to be stored.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_data_types.htm "C# Data Types")

3. Q: What are reference types?
- Reference types are different from value types in that they store the location of something in memory. If a variable or method causes the value at that location to change, then when the reference variable is called it will display the change as well since it's basically "pointing" to that spot in memory.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_data_types.htm "C# Data Types")

4. Q: What is an automatic property and how is it useful?
- When initializing a new object, automatic (auto-implemented?) properties will set the initial values for that object - but with simpler code.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/auto-implemented-properties "Auto-Implemented Properties")

5. Q: What is the purpose of **using** statement?
- It predefines what the resource being used can do, and once the resource reaches the end of its range it is automatically released. This is helpful as it will help avoid memory leaks from forgetting to free memory.
- [Stack Overflow](https://stackoverflow.com/questions/75401/what-are-the-uses-of-using-in-c-sharp "Uses of 'Using' in C#")

6. Q: What are dynamic type variables?
- Dynamic variables can store any data type, and the computer checks what type is being used after the program has compiled.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_data_types.htm "C# Data Types")

7. Q: What is the purpose of the **is** operator?
- This is used to determine if a variable is a certain type. Seems like it would only be used when following an if statement to determine if the varible or object is within that method or class.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_operators.htm "C# Operators")

8. Q: What are **generics** and how is using them useful?
... - With generics you can basically create a dynamic class, one that can use any data type - until it's first used. Once it becomes a data type it turns into that data type, and can't constantly change around.
  - [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_generics.htm "C# Generics")

9. Q: What is the **scope** of a public member of a class?
- If something is declared as "public" can be used throughout the entire project. Public opens it up to be used by anything capable of calling it/using it's value/location.
- [Msdn.Microsoft](https://msdn.microsoft.com/en-us/library/ms973875.aspx "Scopes")

10. Q: Can you create a function that can accept a **varying number of arguments**?
- Yes, by using the "params" keyword, which allows you to pre-designate the number of arguments that it's able to use. "Params" can only be used once per method, and once run it can't be changed until the program is run again. It's declared the same as a single dimensional array.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/params "Params Keyword")

11. Q: How do you **sort an array**?
12. Q: What is a **nullable type** and what purpose does it serve?
- A nullable type is any that is capable of storing the standard set of values along with the null value. This is important as it also allows the use of "true" and "false" values as well, which broadens the uses for the variable.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_nullables.htm "C# Nullables")

13. Q: What is an **enumeration**?
- An enumeration, or enum as it's declared, refers to a list of constant, integer typed words. For instance it could be a list of the days of the week. Each day would contain a value according to what day of the week it was, but those values couldn't be changed after being set.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_enums.htm "C# Enums")

14. Q: What is **inheritance**?
- Inheritance is basically a very efficient way of creating separate classes that use the same variables and declarations. The purpose of this is to eliminate the need to have to keep re-entering all of the same values several times within a large program. If a class is inherited, then it uses whatever variables/statments were declared in the class that it's within.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_inheritance.htm "C# Inheritance")

15. Q: Is **multiple inheritance** supported?
- Multiple inheritance isn't supported in this language, but there are ways to use it such as interfaces.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_inheritance.htm "C# Inheritance")

16. Q: What is the purpose of **as** operator?
- The as operator is useful in that it can allow a data type to be changed within the program, but only between compatible types. The "is" operator is more useful because it automatically checks to see if the two are compatible whereas with the "as" operator it will just store a null value if the types weren't compatible.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/as "As")

17. Q: What is an **object**?
- An object is something that is created when a class is implemented. Basically, the class lays out what is supposed to be made and what it can do, then it creates an object using that information which follows those parameters.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/objects "Objects")

18. Q: What is the difference between a **struct** and a **class**?
- Classes support inheritance, and are reference types. When you use a class you're creating an object that uses the data within. Classes require the new operator in order to initialize a new object as well.
- A struct doesn't allow for any inheritance and merely holds varying datatypes that relate to that specific struct. For instance, if you create a struct called car, you might contain variables such as color, make, model, etc. which will be different types of data, but all pertaining to the car.
- [Tutorialspoint](https://www.tutorialspoint.com/Classes-vs-Structures-in-Chash "Classes Vs. Structures")

19. Q: What is the difference between **continue** and **break** statements?
20. Q: What is **this** and how is it used?
21. Q: What is **try** and **catch** and when are they used?
22. Q: How is **exception handling** done?
23. Q: What is **finally** and what is its purpose?
24. Q: List the differences between **Array** and **ArrayList**.
25. Q: What is an **object**?
26. Q: Define **constructor**.
27. Q: When can **var** be used to declare a variable and how is the type for the variable determined?
28. Q: What is an **abstract class**?
29. Q: What is an **interface**?
30. Q: What is a **method**?
31. Q: What is a **property**?
32. Q: What is an **access specifier**?
33. Q: What access specifiers are supported and what do they mean?
34. Q: What is a **collection**?
35. Q: What is a **Hash Table**?
