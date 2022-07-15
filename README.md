# Kotlin Style Guide

[Naming Convention](#naming)
+ [Classes & Objects](#classes-objects)
+ [Interfaces & Implementation Classes](#interfaces-Implementation)


# Naming
## Classes & Objects
```
Class names should be written in PascalCase and are typically nouns and noun phrases.
e.g. Number or Character.

On the other hand, Interface names may also be nouns or noun phrases e.g. Map, but sometime they can be adjectives or adjective phrases 
e.g. Closeable

Test classes are named starting with the class name of the class they are testing and ended by with Test.
e.g. : LoginActivityTest or LoginPresenterTest
```

## Interfaces & Implementation Classes
```
- Interfaces should follow same naming conventions like Classes and should not use prefixes. 

e.g IMap

- Avoid prefixes and suffixes use in implementation classes, they should be semantic to describe the implementation specifics.

e.g HashMap or LinkedList etc.

- If you have a case-use where you can't add implementation specifications to a class and there is a one-on-one mapping with an interface, then use suffix Impl. 
```
