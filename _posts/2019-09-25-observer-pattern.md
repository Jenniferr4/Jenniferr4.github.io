---
layout: post
title: Observer Pattern 
---
## What is the observer pattern?
* A one-to-many dependency between objects
  -- so that when one object changes state, all its dependents are notified and updated automatically.
  
* Whenever the Subject changes, it broadcasts to all registered Observers that it has changed, 
and each Observer queries the Subject for that __subset of the Subject's state__ that it is responsible for monitoring.
    
## What are the Java language features?

![_config.yml]({{ site.baseurl }}/images/java-features.png)
     
## Which Java language feature supports the use of the Observer pattern?
**Object Oriented**
In Java, everything is an Object. Java can be easily extended since it is based on the Object model.

**Architecture-neutral**
Java compiler generates an architecture-neutral object file format, which makes the compiled code executable on many processors, with the presence of Java runtime system.
  
[source](https://sourcemaking.com/design_patterns/observer)
