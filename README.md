Short-answer questions:

1.Problem Addressed by Generics:
Generics solve the issue of code duplication and type safety. They allow you to create a class or method that operates on any data type, preventing the need to write multiple versions for different types. Generics also enforce type safety by performing compile-time checks, reducing runtime errors due to type mismatches.

2.Creating a List of Strings Using the Generic List Class:
List<string> myStrings = new List<string>();

3.Number of Generic Type Parameters in Dictionary Class:
The Dictionary class in C# has two generic type parameters, TKey and TValue.

4.True/False: All Type Parameters Must Match in a Generic Class:
False. Generic classes with multiple type parameters do not require the parameters to be of the same type.

5.Method Used to Add Items to a List Object:
The Add() method is used to append items to a List.

6.Two Methods That Remove Items From a List:

7.Remove(T item): Removes the first occurrence of a specified object from the List.
RemoveAt(int index): Removes the element at the specified index.
Indicating a Generic Type Parameter in a Class:
You indicate a generic type parameter by placing the type parameter names within angle brackets after the class name, e.g., ClassName<T>.

8.True/False: Generic Classes Can Only Have One Generic Type Parameter:
False. Generic classes can have multiple generic type parameters.

9.True/False: Generic Type Constraints Limit What Can Be Used for the Generic Type:
True. Type constraints specify the requirements that must be met by the types used as arguments for a generic type parameter, limiting which types can be used.

10.True/False: Constraints Let You Use the Methods of the Thing You Are Constraining To:
True. By applying constraints, you can call methods and access properties on the generic types as if they were instances of the constrained type.
