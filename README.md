# Java Terminologies

* [List](#List)
* [Set](#Set)
* [Map](#Map)
* [Vector](#Vector)
* [Queue](#Queue)
* [Stack](#Stack)
* [Any experience in using the subclasses of Map besides HashMap](#Any experience in using the subclasses of Map besides HashMap)
* [How does Jquery know it already get the response from servers](#How does Jquery know it already get the response from servers)
* [OOD Software Design Principles](#Software Design Principles)


List
------






























Any experience in using the subclasses of Map besides HashMap
------------







####Software Design Principles
1. Single Responsibility Principle(SRP)
* Open-Close Principle(OCP)
* Liskov's Substituition Principle（LSP)
* Dependence Inversion Principle（DIP）
* Interface Segregation Principle（ISP）
* Composition/Aggregation Reuse Principle（CARP）
* Law of Demeter or Least Knowlegde Principle（LoD or LKP）

####Software Development Model [http://www.itinfo.am/eng/software-development-methodologies/](http://www.itinfo.am/eng/software-development-methodologies/)
1. Agile Software Development
* Crystal Methods
* Dynamic Systems Development Model (DSDM)
* Extreme Programming (XP)
* Feature Driven Development (FDD)
* Joint Application Development (JAD)
* Lean Development (LD)
* Rapid Application Development (RAD)
* Rational Unified Process (RUP)
* Scrum
* Spiral
* Systems Development Life Cycle (SDLC)
* Waterfall (a.k.a. Traditional)

####OOP's 3 basic concepts features [http://beginnersbook.com/2013/03/oops-in-java-encapsulation-inheritance-polymorphism-abstraction/](http://beginnersbook.com/2013/03/oops-in-java-encapsulation-inheritance-polymorphism-abstraction/)
1. Encapsulation
* inheritance
* polymorphism


How does Jquery know it already get the response from servers
------



##Design Principles
>**Single Responsibility Principle**  
A responsibility is considered to be one reason to change. This principle states that if we have 2 reasons to change for a class, we have to split the functionality in two classes. Each class will handle only one responsibility and on future if we need to make one change we are going to make it in the class which handle it. When we need to make a change in a class having more responsibilities the change might affect the other functionality of the classes.

>**Open Close Principle**  
You can consider it when writing your classes to make sure that when you need to extend their behavior you don't have to change the class but to extend it. The same principle can be applied for modules, packages, libraries. If you have a library containing a set of classes there are many reasons for which you'll prefer to extend it without changing the code that was already written (backward compatibility, regression testing). This is why we have to make sure our modules follow Open Closed Principle.

>**Liskov's Substituition Principle**  
This principle is just an extension of the Open Close Principle in terms of behavior meaning that we must make sure that new derived classes are extending the base classes without changing their behavior. The new derived classes should be able to replace the base classes without any change in the code.

>**Dependence Inversion Principle**  

>**Interface Segregation Principle**  
When we write our interfaces we should take care to add only methods that should be there. If we add methods that should not be there the classes implementing the interface will have to implement those methods as well. For example if we create an interface called Worker and add a method lunch break, all the workers will have to implement it. What if the worker is a robot?

>**Composition/Aggregation Reuse Principle**  

>**Law of Demeter or Least Knowlegde Principle**  


Design patterns
---------------
>**creational patterns**  
* Factory Pattern
* Abstract Factory Pattern
* Singleton Pattern
* Prototype Pattern
* Builder Pattern


>**structural patterns**  
* Adapter Pattern
* Bridge Pattern
* Composite Pattern

>**behavioral patterns**
