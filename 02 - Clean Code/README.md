
# Chapter 01 - Clean Code


> You are reading this book for two reasons. First, you are a programmer. Second, you want
to be a better programmer. Good. We need better programmers.

> Had you sometime wade through code? Well, this is a bad code.

> LeBlanc’s law: Later equals never

>  Attittude: Most managers want good code, even when they are obsessing about the schedule. They may defend the schedule and requirements with passion; but that’s their job. ** It’s your job to defend the code with equal passion. **

> "The logic should be straightforward to make it hard for bugs to hide, the dependencies minimal to ease  maintenance, error handling complete according to an articulated strategy, and performance close to optimal so as not to tempt people to make the code messy with unprincipled optimizations" - Bjarne Stroustrup -  inventor of C++

> "...Clean code reads like well-written prose." - Grady Booch - author of  Object Oriented Analysis and Design with Applications  

> "Clean code always looks like it was written by someone who cares." - Michael Feathers, author of Working Effectively with Legacy Code  

> if you want your code to be easy to write, make it easy to read.

> Rule of The Boy Scouts of America: Leave the campground cleaner than you found it.

> Other book: Agile Software Development: Principles, Patterns, and Practices (PPP).

Bibliography:
[Beck07]: Implementation Patterns, Kent Beck, Addison-Wesley, 2007.  
[Knuth92]: Literate Programming, Donald E. Knuth, Center for the Study of Language and Information, Leland Stanford   Junior University, 1992.  


# Chapter 02 - Meaningful Names

> Use Intention-Revealing Names

> Stop using comments.

> Avoid Disinformation
avoid leaving false clues  

> Make Meaninful Distinctions
Use Pronounceable Names  

> Use Pronounceable Names

> Use Searchable Names

> Avoid Encodings
Stop using hungarian notation  
Member prefixes  
Interfaces and Implementations  

> Avoid Mental Mapping
Readers shouldn’t have to mentally translate your names into other names they already know.  

> Class Names
Prefer nouns or noun phrase.
Do not use verbs, please.  

> Method Names
Prefer verb or verb phrase.

> Do not be cute
That is do not use slang words.

> Pick One Word per Concept
Pick one word for one abstract concept and stick with it.  

> Don't Pun

> Use Solution Domain Names
JobQueue, AccountVisitor

> Use Problem Domain Names

> Add Meaningful Context
Maybe you should break a method to a class?

> Don't Add Gratuitous Context


# Chapter 03 - Functions


> Always write small functions and methods!

> Blocks, Ifs and Identating
Keep not greater than one or two.  

> Do One Thing.
FUNCTIONS SHOULD DO ONE THING. THEY SHOULD DO IT WELL. THEY SHOULD DO IT ONLY.  

> One Level of Abstraction per Function

> Reading Code from Top to Bottom: The Stepdown Rule
We want the code to read like a top-down narrative.  

Try write code like this:

```
   To include the setups and teardowns, we include setups, then we include the test page content, and then we include the teardowns.
   To include the setups, we include the suite setup if this is a suite, then we include the regular setup.
   To include the suite setup, we search the parent hierarchy for the “SuiteSetUp” page and add an include statement with the path of that page.
   To search the parent...
```

> Switch Statements
Try to use abstract factory or factory pattern.

> Use Descriptive Names

> Function Arguments
Ideal number of arguments: 1 or 2.  
Try not to use void functions.   

> Flag Arguments
Avoid boolean arguments.  

> Dyadic Functions
Avoid functions with two arguments.  
Monadic is your best guest.  

> Triads Functions
Try never write then.  

> Argument Objects
More then 2 arguments, use objects.  

> Verbs and Keywords

> Have no side effect
Side effects are lies.
Never write functions that does one more thing than this function name.

> Output Arguments
Cognitive break should be avoided.  
So, output arguments should be avoided.  

> Command Query Separation
Functions should either do something or answer something, but not both.  

> Prefer Exceptions to Returning Error Codes

> Extract Try/Catch Blocks

> Error Handling is One Thing

> The Error.java Dependency Magnet

> Don't Repeat Yourself (DRY)

> Structured Programming

> Conclusion
Functions are the verbs of the language.  
Classes are the nouns.  
Master programmers think of systems as stories to be told rather than programs to be written.  


Bibliography:
[KP78]: Kernighan and Plaugher, The Elements of Programming Style, 2d. ed., McGrawHill, 1978.
[PPP02]: Robert C. Martin, Agile Software Development: Principles, Patterns, and Practices, Prentice Hall, 2002.
[GOF]: Design Patterns: Elements of Reusable Object Oriented Software, Gamma et al., Addison-Wesley, 1996.
[PRAG]: The Pragmatic Programmer, Andrew Hunt, Dave Thomas, Addison-Wesley, 2000.
[SP72]: Structured Programming, O.-J. Dahl, E. W. Dijkstra, C. A. R. Hoare, Academic Press, London, 1972.


# Chapter 04 - Comments

> "Don’t comment bad code—rewrite it." —Brian W. Kernighan and P. J. Plaugher1

> Programmers can’t realistically maintain comments. Get ride of them.

> Keep in mind, however, that the only truly good comment is the comment you found a way not to write

> TODOs are jobs that the programmer thinks should be done, but for some reason can’t do at the moment


Bibliography:

[KP78]: Kernighan and Plaugher, The Elements of Programming Style, 2d. ed., McGrawHill, 1978.



# Chapter 05 - Formatting


> You should take care that your code is nicely formatted.

> You should choose a set of simple rules that govern the format of your code, and then you should consistently apply those rules.  

> Vertical Formatting
Small files, talking about number of lines, are usually easier to understand than large files are.

> The Newspaper Metaphor
Write source fileto be like a newspaper article.

> Vertical Openness Between Concepts
One line before each method.

> Vertical Density
Methods that are tightly related should appear vertically dense, or near.

> Variable Declarations
Should appear a the top of each function.

> Instance Variables
Should be declared at the top of the class.

> Dependent Functions
The caller should be above the callee.

> Conceptual Affinity.
Certain bits of code want to be near other bits.

> Vertical Ordering
In general we want function call dependencies to point in the downward direction.  
That is, a function that is called should be below a function that does the calling.  

> Horizontal Formatting
Programmers clearly prefer short lines.
140 characters that's OK.

> Horizontal Openness and Density
We use horizontal white space to associate things that are strongly related and disassociate things that are more weakly related.  

> Horizontal Alignment
Please don't do this.

> Indentation
Any doubts?
3 spaces or 1 tab, it's nice.

> Team Rules Rulez!



Stopped at page 124

