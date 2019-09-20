---
layout: post
title: Square vs Rectangle 
---

##  Why is a rectangle and a square a bad example of an inheritance?  

Inheritance in Java is a mechanism in which one object acquires **all** the properties and **behaviors** of a parent object. 
  
![_config.yml]({{ site.baseurl }}/images/liskov.png)
  
According to the __Liskov Substitution Principle__, any class that is the child of a parent class should be usable in place of its parent __without any unexpected behaviour__.
  
Although a square is considered a rectangle, a square has different behaviors than a rectangle. 
If you were to change the height of Rectangle, width would not be affected.  
With square, on the other hand, you would have to change both length and width.
  
![_config.yml]({{ site.baseurl }}/images/duck.png) 
  
Since square does not have **all** the behaviors from the "parent" rectangle ,  
we can conclude that rectangle.... 
   
![_config.yml]({{ site.baseurl }}/images/notfather.png)  

....." You are NOT the father!". 



