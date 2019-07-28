# Clean Code
​
##  Chapter 1:
​
* Leave the compound cleaner than you found it
​
## Chapter 2 : Meaningful Names
​
- Intention revealing names
- Avoid disinformation
- Make meaningful distinctions 
- Use pronounceable names
- Use searchable names
- Follow common conventions
- Class names should be noun phrases
- Method names should be verb phrases
​
## Chapter 3: Functions
​
- Functions should be small.(4-5 lines)
- Functions should do one thing only.
- One level of abstraction per function
- Avoid switch statements
- Use descriptive names
- Arguments - 0, 1, 2 are good enough 
- Never use flag arguments
- If fucntion have more than 2 argument, if possible make them a new class (if possible)!
- Have no side effects. No hidden changes. Clearly do one thing !
- Return value object
- Prefer exception to return error codes. Use try-catch instead of if-else!
- DRY !
​
## Chapter 4: Comments
​
- No comments at all
​
## Chapter 5: Formatting
​
- No blank lines in between function. 
- Blank line should mark a logical separation in methods, classes etc.
- Instace variables at the temp, methods below them
- Caller should be above the callee.
- Foucs on readblity by appropriate vertical density. 
- Indentation
​
## Chapter 6: Objects and Data Structure 
​
- Sometimes you need to use data structure, sometimes you need use objects. 
- Everything is not an object.
- Law of Demeter:  A mehtod *f* of a Class *C* should only call methods of 
  - *C*
  - An object created by *f*
  - An object passed as an argument
  - An object held as an instance variable of *C*
- Failing law of demeter implies a function knows many things. Split that function.
- Active Record is a Data Structure. 
​
## Chpater 7: Error Handling 
​
- Use exceptions rather than error codes
​
## Chapter 9: Unit Test
​
- TDD
- Test must be clean (Readability) - must follow all clean code conventions for test code
- Test code is as important as production code
- Test coverage should be always high
- One assertion per test and try to minimize number of assertions per test
- Single concept per test
- F.I.R.S.T
  - F - Test should run **fast**
  - I - Test shouldn't **depend** on each other
  - R - Test should be **repeatable** in any environment
  - S - **Self Validating** (Test should have a boolean ouput)
  - T - Test should be written **Timely**
​
## Chapter 10: Classes
​
* Never have a public variable - implies **Encapsulation**
* Classes should be small
* One class should have a only responsibility - (**SRP**: *Single Responsibility Principle*)
* Class Name should describe what responsibility it fullfills
* Class should have **High Cohesion**
* **Maximum Cohesion** - It is achieved when each varaible is used by each method
* When classes lose cohesion split them
​
## Chapter 12: Emergence
​
*  Systems that are not testable are not verifiable if not verifiable then not deployable **RUN ALL THE TESTS**
* Refactoring
  * Remove duplication
  * Be Expressive
  * Impose SRP
​
## Chapter 14 & 15 & 16
​
* Read the examples mentioned in the chapter
* Read Appendix A and B
​
## Chapter 17: Brief Points
​
* Building the Project should be one single operation
​
* All test should run with one command
​
* **Avoid** multiple languages in one source file
​
* **Avoid** Surprises 
​
* All write tests for **edge** cases
​
* Never overwrite Safety
​
* Minimum Duplication (**DRY**: *Don't Repeat yourself*)
​
* Don't Mix levels of Abstraction + (**THE LAW OF DEMETER**)
​
* Base class shouldn't depend on the derivative's
​
* Don't put too much Information (function, module, class etc)
​
* Always remove dead code
​
* Always maintain consistency 
​
* Be as expressive as possible
​
* Don't mix responsibility 
​
* Make logical dependencies physical 
​
* Prefer Polymorphism to **if - else, switch cases**
​
* **Encapsulate: Conditionals, Boundary Conditions, Edges Cases** 
