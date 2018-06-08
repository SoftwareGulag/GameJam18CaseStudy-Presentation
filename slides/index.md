- title : How to create a legacy project in less than two days?
- description : Real life example of what happens when programmers do not care about clean code.
- author : Pawel Jelinski
- theme : night
- transition : default

***

## How to create a legacy project in less than two days?

<br />
<br />

### GameJam 2018 case study

<br />
<br />
Pawel Jelinski

***
### Befor we start

---
### Read those books!

* Clean Code: A Handbook of Agile Software Craftsmanship, by Rober C. Martin
* Test Driven Development: By Example, by Kent Beck
* Refactoring to Patterns, by Joshua Kerievsky
* The Clean Coder: A Code of Conduct for Professional Programmers, by Rober C. Martin
* The Art of Unit Testing: with examples in C#, by Roy Osherove

***
### Agenda

---
1. What is legacy software?
2. What is clean code?
3. How to write clean code?
4. Case study
5. Summary

***
### What is legacy code?
---
_Legacy code is simply code without tests._

___Feathers, Michael. Working Effectively with Legacy Code.___


***
### What is clean code?

---
_I like my code to be elegant and efficient. The logic should be straightforward and make it hard for bugs to hide, the dependencies minimal to ease maintenance, error handling complete according to an articulated strategy, and performance close to optimal so as not to tempt people to make the code messy with unprincipled optimizations. Clean code does one thing well._

___Bjarne Stroustrup, inventor of C++___

---
_Clean code is simple and direct. Clean code reads like well-written prose. Clean code never obscures the designers’ intent but rather is full of crisp abstractions and straightforward lines of control._

___Grady Booch, author of Object-Oriented Analysis and Design with Applications___

---
_I could list all of the qualities that I notice in clean code, but there is one overarching quality that leads to all of them. Clean code always looks like it was written by someone who cares. There is nothing obvious that you can do to make it better. All of those things were thought about by the code’s author, and if you try to imagine improvements, you are led back to where you are, sitting in appreciation of the code someone left for you—code written by someone who cared deeply about the craft._

___Michael Feathers, author of Working Effectively with Legacy Code___

---
_You know you are working with clean code when each routine you read turns out to be pretty much what you expected. You can call it beautiful code when the code also makes it look like the language was made for the problem._

___Ward Cunningham, inventor of Wiki and Fit, co-inventor of Extreme Programming___

---
* hard to create nasty bugs
* simple and direct
* easy to read
* easy to imporve
* works as you

***
### How to wirght clean code?

***
### SOLID

---

* Single responsibility principle
* Open/closed principle
* Liskov substitution principle
* Interface segregation principle
* Dependency inversion principle

---
* SOLID princpiles are not gloden hammer. 
* They are guidlines created to reduce coupling and increase cohesion.

---
### Principles of package cohesion & Principles of package coupling

***
### TDD
Invented by Smalltalkers, in order to write type safe code. Later rediscoverd by Kent Beck.

---
### Red, green, refactor

* write red test
* make test pass
* refactor

---

_As the tests get more specific, the production code gets more generic._

___Rober C. Martin___ 

---
### Pros

* comprehensive unit test suite
* documentation
* simple design
* give confidence

---
### Cons

***
### Design patterns

---
_Design pattern is a general, reusable solution to a commonly occurring problem within a given context_

___Design patterns, Gang of four___

***
### DDD, BDD, DRY...

***
### Case study

---
### Game Jam 2018

---
### Offive Parkour

---
### Technology choice
## Unity vs Phaser

---
### If driven architecture

---
### Manual testing

---
### Last hours
## Bugs,rigidity and fear

---
### Code

***
### Spike, POC, MVP

***
### Pirmary value of svtware vs Secondary value of software

***
## Why we broke rule and what were consequntions?

### Sources

***
### Thank you!
