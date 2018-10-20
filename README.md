# CSharp-Questions-1
Repository holding the questions and answers for the same assignment
***

1. Q: What is a **namespace**?
- A namespace essentially seems like a container for programs. It holds all the variables, methods, etc. within it, and doesn't allow another namespace to use the variables defined within it. From tutorialspoint, "The class names declared in one namespace does not conflict with the same class names declared in another." However, it's possible to call a method/use a variable from one namespace in a different namespace.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_namespaces.htm "Namespaces")

2. Q: What are **value types**?
- Value types are basically variables that are created which when utilized/called will provide an actual value rather than output a location in memory. For instance, an integer (int) type variable is a value type because when it's called it will output the value it currently holds. When it's intially created the system will set aside memory intended for the value that's going to be stored.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_data_types.htm "C# Data Types")

3. Q: What are **reference types**?
- Reference types are different from value types in that they store the location of something in memory. If a variable or method causes the value at that location to change, then when the reference variable is called it will display the change as well since it's basically "pointing" to that spot in memory.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_data_types.htm "C# Data Types")

4. Q: What is an **automatic property** and how is it useful?
- When initializing a new object, automatic (auto-implemented?) properties will set the initial values for that object - but with simpler code.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/auto-implemented-properties "Auto-Implemented Properties")

5. Q: What is the purpose of **using** statement?
- It predefines what the resource being used can do, and once the resource reaches the end of its range it is automatically released. This is helpful as it will help avoid memory leaks from forgetting to free memory.
- [Stack Overflow](https://stackoverflow.com/questions/75401/what-are-the-uses-of-using-in-c-sharp "Uses of 'Using' in C#")

6. Q: What are **dynamic type** variables?
- Dynamic variables can store any data type, and the computer checks what type is being used after the program has compiled.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_data_types.htm "C# Data Types")

7. Q: What is the purpose of the **is** operator?
- This is used to determine if a variable is a certain type. Seems like it would only be used when following an if statement to determine if the varible or object is within that method or class.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_operators.htm "C# Operators")

8. Q: What are **generics** and how is using them useful?
- With generics you can basically create a dynamic class, one that can use any data type - until it's first used. Once it becomes a data type it turns into that data type, and can't constantly change around.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_generics.htm "C# Generics")

9. Q: What is the **scope** of a public member of a class?
- If something is declared as "public" can be used throughout the entire project. Public opens it up to be used by anything capable of calling it/using it's value/location.
- [Msdn.Microsoft](https://msdn.microsoft.com/en-us/library/ms973875.aspx "Scopes")

10. Q: Can you create a function that can accept a **varying number of arguments**?
- Yes, by using the "params" keyword, which allows you to pre-designate the number of arguments that it's able to use. "Params" can only be used once per method, and once run it can't be changed until the program is run again. It's declared the same as a single dimensional array.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/params "Params Keyword")

11. Q: How do you **sort an array**?
- There's a method within C# that sorts arrays basically by pre-specifying the way you wish to sort the array, and then it sets a base value for that array, after doing that it compares future values to that and if a new one is preferable to the current held value, then it replaces the held value with the new value until another is even more preferable.
- [CSharp Examples](http://www.csharp-examples.net/sort-array/ "Sort-Array")

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
- The break statement completely ends the loop and tells the program to move to the next line in the program. 
- The continue statement, on the other hand, tells the program to finish that specific loop, but then it forces it to go to the next increment of the loop skipping anything else that may have been leftover in the previous one.
- [Tutorialspoint](https://www.tutorialspoint.com/What-is-the-difference-between-break-and-continue-statements-in-Chash "Break Vs. Continue Statements")

20. Q: What is **this** and how is it used?
- The "this" keyword is used when trying to use something in the current instance of the class you're using. For instance if you're creating an object that's intended to be a car you would assign it's color with this.color and that would assign a color to the current car you're creating/using.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/this "This")

21. Q: What is **try** and **catch** and when are they used?
- The "try" keyword is implemented at a spot in your code where you expect to have an error. It's typically followed by at least one "catch" block of code.
- The "catch" keyword is placed at the spot where the exception is expected to occur, and then outputs a message indicating that the exeception was actually caught. 
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm "Exception Handling")

22. Q: How is **exception handling** done?
- Exception handling is done through the use of the "try," "catch," "finally," and "throw" blocks. When there's an error that occurs in a block of code a try/catch is put there to catch it. Whether or not an exception is caught a finally block carries out it's code. I assume this is intended to help find the exact location and identify what kind of exception occurs in order to fix it.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm "Exception Handling")

23. Q: What is **finally** and what is its purpose?
- A "finally" block of code is one that will always execute no matter if an exception occurs or not. This keyword follows both the "try" and "catch" blocks. For instance if a file was opened, occurred somewhere while it was opened, the finally block would close the file either way in order to avoid memory leak.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm "Exception Handling")

24. Q: List the differences between **Array** and **ArrayList**.
- An array is a strong-typed collection in which you would use a specific data type. An array list on the other hand is more flexible and a weaker-typed collection, and ArrayList can store values of any type inside it. Furthermore, an array is/can be multi-dimensional, whereas an ArrayList is single dimension. You would use an ArrayList when you aren't sure about how large the array will get, or in the event you're using multiple types of data.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_arraylist.htm "C# ArrayList Class")
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_arrays.htm "C# Arrays")

25. Q: What is an **object**?
- An object is something that is created when a class is implemented. Basically, the class lays out what is supposed to be made and what it can do, then it creates an object using that information which follows those parameters.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/objects "Objects")

26. Q: Define **constructor**.
- Whenever an instance/object is first created, it calls a constructor that initializes types for that object. Basically it builds the base model of that object that can then be altered later in the program. A constructor is also called the same thing as the class, and each class can only have one. I believe the constructor is used every time a new object is created using that class.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_classes.htm "C# Classes")

27. Q: When can **var** be used to declare a variable and how is the type for the variable determined?
- Var is a strongly typed variable like others, but isn't really specific until after the program is compiled. For instance if you declare a variable called age as var and set it to five, after the program is compiled the var will basically be as if an integer was declared (because it was). Var is more useful, from what it seems, when being used in a varible that might handle several types of data. However, if it's only passed an array containing strings, then there's no point using var as you might as well use the "char" data type.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/var "Var")

28. Q: What is an **abstract class**?
- An abstract class is a special class that is designed to force a certain level of organization in the project. It can only be inherited from, so it has to be the first class, and then sub-classes branch from it. Unlike an interface, an abstract class can have constructors. Abstract classes can also extend, and content in an abstract class can contain abstract or concrete information. Other classes can inherit a base class, and then also use the interfaces within that base class I believe.
- [Docs.Microsoft](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/abstract "Abstract")

29. Q: What is an **interface**?
- Unlike with inheritance, a class can utilize multiple interfaces. Interfaces remain the same size after being created. Anything that runs an interface must also run everything within that interface. I think this is how interfaces don't actually implement anything themselves.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_interfaces.htm "C# Interfaces")

30. Q: What is a **method**?
- These are the blocks of code that "do" things. Main is the primary method that's used in every program. Methods are where the program is carried out.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_methods.htm "C# Methods")

31. Q: What is a **property**?
- This is basically a named "field" within a class, struct, or interface that use accessors which are contained in private fields that gather and assign the information for that property.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_properties.htm "C# Properties")

32. Q: What is an **access specifier**?
- Basically it controls what the variable or class can be seen/used by. For instance, a public specifier can be used by anything within the program.
- [Tutorialspoint](https://www.tutorialspoint.com/Access-Modifiers-in-Chash "Access Modifiers")

33. Q: What access specifiers are supported and what do they mean?
- Public, protected, internal, protected internal, and private are the specifiers supported
- Public has no restrictions on what can see it or use it
- Protected can only be used by classes that inherit the protected class
- Internal can only be used by the method/class that created it - I'm not too clear on this specifier
- Protected internal is basically a combination of both the protected and internal specifiers, seems redundant
- Private can only be used by that class it was declared in
- [Tutorialspoint](https://www.tutorialspoint.com/Access-Modifiers-in-Chash "Access Modifiers")

34. Q: What is a **collection**?
- These are special indexed classes that are capable of storing dynamic sizes of data and utilizing them at later points in the program. They are used in things such as stacks, queues, and hash tables. Collections seems to be the foundation for object classes as it can store several separate objects within it which then creates an object class.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_collections.htm "C# Collections")

35. Q: What is a **Hash Table**?
- A list, or collection, of stored and paired values. For instance you may store names in a class - in this case each name would be assigned to a different "key" specifying that specific name. From what I can tell, the table can then be referenced using either the names or the keys since they're paired together.
- [Tutorialspoint](https://www.tutorialspoint.com/csharp/csharp_hashtable.htm "C# Hashtable Class")
