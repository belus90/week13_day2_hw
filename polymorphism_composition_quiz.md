# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
The complexity of human cognition. 
2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Polymorphism in OO design allows us to perform a single action in different ways. 
Exp.:
"public class Animal{
    public void sound(){
        System.out.printIn("Animal is making a sound");
    }
}

public class Cat extends Animal{
    @Override
    public void sound(){
        System.out.printIn("Miaw");
    }
} "

3. What can we use to implement polymorphism in Java?
We can perform polymorphism in java by method: overloading,overriding.

4. How many 'forms' can an object take when using polymorphism?

An object can have multiple forms when using polymorphism.

5. Give an example of when you could use polymorphism.
We would use polymorphism when the class has a "IS A" relationship whit the super class. Exp.: Create a class "Animal", let's create subclasses: "Cat","Dog". Both are animals, but they make different sounds. 



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
A class which references one or more objects of other classes in instance variables. We refer for this as an "HAS A" relationship between the objects.

7. When would you use composition? Provide a simple example in Java. 
When an object contains a composed object, but the composed object cannot exist without another entity. For example: A university been closed, all the details of the employees should be deleted. 

8. Give a difference between composition and aggregation?
Aggreagation is one type of association between two objects which "HAVE A" relationship. On the other hand the composition is a type of aggregation which implies ownership. 

9. What is/are the advantage(s) of using composition/aggregation?
Allowes to reuse codes, better test-abality of a class. 

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
All the objects it is composed will be deleted. . 
11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
All the objects will be kept. 