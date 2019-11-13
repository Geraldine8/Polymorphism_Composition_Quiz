# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
A:Polymorphism means 'many forms'

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A: In Java it means that a single object can be many different types, for instance:
We could have object of type building and car - both of which have a holds people function.

3. What can we use to implement polymorphism in Java?
We can use interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?
A: An object can have take infinite number of forms using Polymorphism, so long as it implements the specific methods defined in the interfaces.


5. Give an example of when you could use polymorphism.
A: An example of this could be a superclass Animal that has a method called animalSound() - Subclasses of Animals could be Pigs, Cats, Dogs, Birds - And they also have their own implementation of an animal sound (the pig oinks, and the cat meows, etc.):

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
A: Composition means an object contains other objects  and their relationship is described as 'Has-a' relationship.

7. When would you use composition? Provide a simple example in Java.
A: I can use composition in a library that have a no. of books on the same or different subjects. If the library gets destroyed then all books will be destroyed as well, because book can not exits without library.  

8. What is/are the advantage(s) of using composition?
A: Benefit of using composition in Java is we can reuse code rather than to use inheritance, we can also control the visibility of the other object to client classes and reuse only what we need.

9. When an object is destroyed, what happens to all the objects it is composed of?
A: When an object is deleted all objects that it owns is also deleted,, so if you delete a person then its job is also deleted.
