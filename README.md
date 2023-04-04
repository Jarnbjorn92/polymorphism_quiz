# Polymorphism & Composition Homework - Quiz

# Polymorphism
### What does the word 'polymorphism' mean?
Polymorphism means something has many forms.

### What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Polymorphism in Object-Oriented design refers to the ability of an object to take on multiple forms or behave in different ways depending on the context in which it is used. It allows different objects to be treated in a uniform way, regardless of their specific class or implementation.

### What can we use to implement polymorphism in Java?
We can create interfaces in Java to allow us to implement the defined functions into a class, and allows classes to utilise them.

### How many 'forms' can an object take when using polymorphism?
This is dependent on how many classes that implements or inherates from them.

### Give an example of when you could use polymorphism.
When you have a shape class containing different shapes (such as circle, square, and triangle), the shape could implement a calculateArea() method that all shapes could use but require different method bodies to calculate.


# Composition and Aggregation
### What do we mean by 'composition' in reference to object-oriented programming?
Composition refers to the technique of building complex objects by combining smaller objects.

### When would you use composition? Provide a simple example in Java.
A vehicle takes in an engine and tyre objects, and those objects have their own properties.

### Give a difference between composition and aggregation?
Composition has a 'has a' relationship, while aggregation has a 'like a' relationship.

### What is/are the advantage(s) of using composition/aggregation?
Flexibility as it allows you to create complex objects by using smaller more modular objects.

### When using composition, when an object is destroyed, what happens to all the objects it is composed of?
In composition, when an object is destroyed, all the objects it is composed of are also destroyed.

### When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
In aggregation, when an object is destroyed, the objects it is composed of are not necessarily destroyed. This is because the objects are considered to be independent of the larger object and can exist on their own.
