What are constructors
-> What are constructor's how do they differ from other methods of the class,
can we invoke one constructor
from another constructor and can we invoke the super class constructor from
the child class constructor?
Let's take a look.
-> A constructor is a method that is used to initialize the properties of an
object when it is created.
It has the same name as the class name, unlike the other methods in this
case, Class Accord , the constructor
is also Accord.
-> But other methods start and stop, have different names of their own, but the
constructor name is the
same name as the class name.
-> The constructor is only invoked when instance or the object of that class is
created, whereas the other
methods can be invoked as many number of times as we want.
-> To invoke other constructor's in the same class, we used the this method and
we can pass in the parameters
just like any other method.
-> And if the class accord extends Class Honda to invoke the super classes
constructor the hondas constructor
from within the class constructor, we use the super method and pass in any
parameters.
