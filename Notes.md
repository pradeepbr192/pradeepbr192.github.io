<h1> Java notes </h1>
<p>Abstract Class:

Abstract should have atleast one Abstract method.
Abstract method will have only declaration. No Body.
Abstract class can also have Non Abstract method.
Public abstract class Bank{ Public Abstract void new(); }

If an Abstract Class is inherited, then the inheriting class (child class) should defind the body for the abstract method.

Abstraction means hiding the implementation logic.

Interface:

Interface can have only Abstract methods i.e no method body. only method declaration.

Keyword abstract is also not required.

In a interface, if the abstract methods are inherited, then it has to be started with @overheard annotation.

public interface new(){ }

ex: @Override public abstract car();

Cannot create the object of Interface/ Abstract class.
Final Keyword:

Final keyword is used to avoid Inheritance. 2.Final Keyword prevents Method overriding. 3.Final keyword is used to declare constant values.
final int i =3;

Finally block is executed always when declared irrespective of the status

finally { SOP("New");

}

Method overloading:

When in the same class, functions having same name but different parameters.

Method Overriding: When same method is present in Parent class and child class, with same name and same number of arguments, it's called Method overriding.

LinkedList ll = new LinkedList(); </p>
