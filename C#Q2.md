###1. **What are the differences between a Class and a Struct?**###

    The difference between a class and a struct is that a *class* is a reference type stored on the heap and supports inheritance, while a *struct* is a value stored on the stack and doesn't support inheritance.

###2. **When and where is the finally keyword used?**###

    The *finally* keyword is used in exception handling to execute code after a try-catch block regardless of whether an exception was thrown.

###3. **Name some properties of an array.**###

    Some properties of arrays are *Length* and *Rank* and *IsFixedSize*.

###4. **What is an escape sequence? Name some String escape sequences.**###

    An *escape* sequence is a special character combination used to represent characters like newline (*\n*), tab (*\t*), or backslash (*\\*).

###5. **What are the basic String Operations? Explain.**###

    The basic String Operations are *concatenation*, *comparison*, *searching* (such as *IndexOf*), slicing (such as *Substring*), and *formatting*.

###6. **What is the difference between continue and break statements?**###

    The difference between continue and break is that the *continue* statement skips the current iteration and moves to the next, while the *break* exits the nearest loop entirely.

###7. **Explain get and set accessor properties.**###

    *get* returns the value of a property, while *set* assigns a value to a property.

###8. **What is an object?**###

    An *object* is a specific instance of a class that holds real values and can perform actions.

###9. **What is a class?**###

    A *class* is a bluprint or template for creating objects.

###10. **Can we use "this" command within a static method?**###

    No, "*this*" can't be used within a static method because static methods belong to the class, not an instance.

###11. **What is the difference between "method overriding" and "method overloading?"**###

    Method *overriding* replaces a bases class method in a derived class, while *overloading* defines multiple methods with the same name but different parameters.

###12. **What are the differences between static, public and void?**###

    The differences between statiic, public, and void is that *static* means the member belongs to the class, *public* defines acessibility, and *void* means the method returns no value.

###13. **What are value types?**###

    *Value types* store data directly and include types which hold their value in memory directly.

###14. **What are reference types?**###

    *Reference types* store a reference to the memory location where the data is held.

###15. **If a return is provided in a try block, does the finally block execute?**###

    Yes, the *finally* block executes even if there is a return in the *try* block.

###16. **How do you sort array elements in descending order?**###

    To sort array elments in descending order use *Array.Sort()* and then *Array.Reverse()* or use LINQ's *OrderByDescending()*.

###17. **What is the difference between the "as" and "is" operators?**###

    The difference between “as” and “is” operators is that the "*as*" operator attempts to cast the object and returns null if the cast fails, while the 
   "*is*" operator checks if an object is a certain type and returns a bool.

###18. **What is enum?**###

    An *enum* is a special value type that defines a set of named constants, used when a variable should only hold a predefined set of values.

###19. **What is the difference between an interface and an abstract class ?**###

    The difference between interface and an abstract class is that an *interface* defines a contract with no implementation, while an *abstract* class can provide both abstract and concrete members.

###20. **What are partial classes?.**###

    *Partial classes* allow a class's definition to be split across multiple files for better organization and collaboration.