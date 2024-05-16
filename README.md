# solid-principles
This repository demonstrates the solid principles of object oriented design
### solid principles history
The solid principles were introduced by Robert C. Martin in his 2000 paper “Design Principles and Design Patterns.” These concepts were later built upon by Michael Feathers, who introduced us to the SOLID acronym. And in the last 20 years, these five principles have revolutionized the world of object-oriented programming, changing the way that we write software
### solid principles goal
The solid principles encourage us to create more maintainable, understandable, and flexible software
### SOLID acronym
SOLID is an acronym that represents five essential principles of object-oriented design: 
Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion
### Single Responsibility 
<em>Focusing on one task</em><br/>

This principle states that a class should only have one responsibility. Furthermore, it should only have one reason to change.<br/>

The benefits that we can get applying this principle are the following:<br/>
<ul>
<li>Testing: A class with one responsibility will have far fewer test cases.</li>

<li>Lower coupling: Less functionality in a single class will have fewer dependencies.</li>

<li>Organization: Smaller, well-organized classes are easier to search than monolithic ones</li>
</ul>

### Open Closed Principle
<em>Embracing Extension</em><br/>
Classes should be open for extension but closed for modification. 
In doing so, we stop ourselves from modifying existing code and causing potential new bugs.
The only exception to the rule is when fixing bugs in existing code.
### Liskov Substitution Principle
<em>Ensuring Substitutability</em><br/>
if class A is a subtype of class B, we should be able to replace B with A without disrupting the behavior of our program.
### Interface Segregation Principle
<em>Granular Interfaces</em><br/>
Larger interfaces should be split into smaller ones. By doing so, we can ensure that implementing classes only need to be concerned about the methods that are of interest to them.
### Dependency Inversion Principle
<em>Inverting Dependency Flow</em><br/>
Depend on abstraccions, not on concretions.




