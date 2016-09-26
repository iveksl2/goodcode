This repository contains Universal principles to improve code quality.  Although our 
strongly held opinions are never wrong, we will include principles that are emprically supported.
We do not intend on endorsing the software industries trendy new acronym or management theory. 
Much of the content draws upon principles & philosophy within [Making Software](http://shop.oreilly.com/product/9780596808303.do) book.
  * ["Notes on 'Making Software'"](http://peterhurford.tumblr.com/post/143408649351/notes-on-making-software-what-really-works-and)


Few Words of Caution:
No one principle is likely to be earth shattering in improving your code quality. However, similar to a trading strategy,
the accumulation of many small principles independently verified can in 
aggregate make a significant positive difference. 

Finally, we believe by far the single best way to improve you coding ability is to be in the trenches 
reading and writing code. This repository can serve serve as a post-mortem to allow
you to 'sharpen the saw' when attacking your next project.

Each Principle will Provide Empirical Support (i) and Reference / Documentation (ii) on learning & implementing the principle. 
# Principles:
  
- **Readability**
  1. ["What is good code?: A scientific definition](http://engineering.intenthq.com/2015/03/what-is-good-code-a-scientific-definition/) 
  2. ["How Do You Write Readable Code?: 11 Principles](https://gist.github.com/peterhurford/3ad9f48071bd2665a8af) 


- **Design Patterns**
 1. i.  Some edvidence exists merely documenting presence of design patterns may reduce implementation time & improve program specification correctness.[1]   
     ii. Weak but significant evidence exists certain patterns reduce errors in pattern relavant maintenance tasks[2][3]     
     iii. Design Patterns allow for better / more distributed communication among the team when members share pattern knowledge. [4]     
     *Note*: Per Vokac et al. "design patterns are not universally good or bad, but must be used in a way that
                               matches the problem and the people". The factory pattern within an API was shown to degrade quality.[5] Visitor pattern has also been found hard to comprehend. [3]
 2. The following are implementations of design patterns found to improve solution quality or maintenance speed: 
       * [Decorator](https://github.com/faif/python-patterns/blob/master/decorator.py)
       * [Observer](https://github.com/faif/python-patterns/blob/master/observer.py) 

Study References:
   *Design Patterns*:
   1. [Prechelt et al. 2002: Two Controlled Experiemnts Assessing the Usefulness of Design Pattern Documentation in Program Maintenance](http://dl.acm.org/citation.cfm?id=570532)  
   2. [Lutz Prechlet & Barbara Unger et al. 2001: A Controlled Experiment in Maintenance Comparing Design Patterns to Simpler Solutions](http://www.ptidej.net/courses/log6306/fall12/readingnotes/2/Prechelt%20-%20A%20controlled%20experiment%20in%20maintenance.%20comparing%20design%20patterns%20to%20simpler%20solutio.pdf)
   3. [Vokac et al. 2004: A Controlled Experiment Comparing the Maintainability of Programs Designed with and Wwihout Design Patterns](https://www.nr.no/~aldrin/artikler/DesignPatternsEmpiricalSoftwareEngineering.pdf)
   4. [Unger et al. 2000: Do Design Patterns Improve Communication? An Experiment with Pair Design. Workshop on Empirical Studies of Software Maintenance](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=6BCE30334106F3C5CD15BC8E033EE7DF?doi=10.1.1.258.7373&rep=rep1&type=pdf)
   5. [Ellis et al. 2007: The Factory Pattern API Deisgn: A Usability Evaluation](https://www.cs.cmu.edu/~NatProg/papers/Ellis2007FactoryUsability.pdf)
