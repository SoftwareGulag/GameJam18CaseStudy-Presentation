- title : How to create a legacy project in less than two days?
- description : What is legacy code and How it is made? How to stop code decay and when it's acceptable. Game Jam 18 case study.
- author : Pawel Jelinski
- theme : night
- transition : default

***

## How to create a legacy project in less than two days?


### GameJam 2018 case study

Pawel Jelinski

***
### Befor we start

---
### If you read those books, You can leave.

* Kent Beck, Test Driven Development: By Example
* Joshua Kerievsky, Refactoring to Patterns
* Robert C. Martin, The Clean Coder: A Code of Conduct for Professional Programmers
* Robert C. Martin, Clean Code: A Handbook of Agile Software Craftsmanship
* Michael Feathers, Working Effectively with Legacy Code

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
_Legacy code. The phrase strikes disgust in the hearts of programmers. It conjures images of slogging through a murky swamp of tangled undergrowth with leaches beneath and stinging flies above. It conjures odors of murk, slime, stagnancy, and offal. Although our first joy of programming may have been intense, the misery of dealing with legacy code is often sufficient to extinguish that flame._

___Feathers, Michael. Working Effectively with Legacy Code.___

---
### Code without tests rots like a piece of bad meat.


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
* easy to improve
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
* SOLID principles are not a golden hammer. 
* They are guidelines created to reduce coupling and increase cohesion.

---
### Principles of package cohesion & Principles of package coupling

***
### Automated tests
---
_Code without tests is bad code. It doesn't matter how well written it is; it doesn't matter how pretty or object-oriented or well-encapsulated it is. With tests, we can change the behavior of our code quickly and verifiably. Without them, we really don't know if our code is getting better or worse._

___Feathers, Michael. Working Effectively with Legacy Code.___
---
### TDD
Invented by Smalltalkers, in order to write type-safe code. Later rediscovered by Kent Beck.

---
### Red, green, refactor

* write failing test
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
### Office Parkour

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
### Primary value of software vs Secondary value of software

***
## Why we broke rules and what were consequences?

### Sources

***
### Thank you!
