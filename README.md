# Design Patterns

## Description

This repository is intended to demonstrate various Standard Design Patterns used in Object Oriented Systems.
The Language used for the implementation is **JAVA**.

**Note :** The various design patterns are closely related to each other so, in the implementations you can find one design pattern used inside another.<br/>*Eg :* An Abstract Factory is usually implemented as a Singleton Class. However I have tried not to mix the design patterns wherever possible, but in actual systems one may find all these patterns together in use.
## Structure

The design patterns can be broadly categorized into three categories[Design Patterns by gang of four] :
1. *Creational Patterns*
2. *Structural Patterns*
3. *Behavioral Patterns*

#### Creational Patterns
1. **Abstract Factory :**
  <br/> This pattern is used to instantiate objects of related classes through an interface without giving the details of concrete classes to the client.

2. **Singleton :**
  <br/> This pattern ensures that a class has only one instance and provides a global point of access to it.

3. **Builder :**
  <br/> This pattern is used to seperate object representation from its construction process.

4. **Factory Method :**
  <br/> This pattern is used when a particular class(known as Creator) does not know in advance which objects(known as products) it must create. The Creator thus uses an interface(say Product) which must be shared by all the different products that the subclasses of this class can create. The Creator necessarily declares a method(usually something like createProduct, makeProduct etc) which returns an an object of type Product. This Method is known as the *Factory Method* as it is reponsible for creation of the object(product).

  Thus Factory method pattern lets a class defer the Object instantiation to its subclasses.
