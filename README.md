# Object Oriented Programming in Python
## Essential concepts
### Class
A class is a blueprint for creating objects (a specific data structure), providing initial values for its attributes and methods to interact with these attributes.
A class defines how an object will look and behave when created from that class. It includes:
1. Attributes – these define what properties an object of this class has. For example, if
we have a Car class, its attribute might include color, make, model etc.
2. Behaviours/Methods - they define how an object interacts with the outside world
(either user input, other objects, or itself). For example, a method for a Car
class might allow you to start(), stop() or honk().

### Object
An instance of a class is called an object. In other words, objects are instances of classes.
An object consists of:
- A set of attributes/state (data) associated with it. These can be simple data like strings or
integers, complex data structures such as lists and dictionaries, or even methods that can perform actions
on the object's attributes.
- A collection of behaviors (methods), which are functions that belong to the object and can access
and modify the object’s attributes. Methods interact with the attributes of an object to carry out
specific tasks. They can also contain code that performs calculations, displays messages, or initiates
other processes.
- An identity that gives a unique name to an object and enables one object to interact with other objects.

### The python self
The `self` parameter represents the instance of the class. When we call a method on an object using dot notation (`object.method()`), Python implicitly passes the object as the first argument to the method. This argument becomes known as `self`. Inside the method definition, `self` refers to the current instance of the class.
When we call a method of this object as myobject.method(arg1, arg2), this is automatically converted by Python into MyClass.method(myobject, arg1, arg2).