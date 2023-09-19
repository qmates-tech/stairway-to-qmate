# QMates' learning path

This is the learning path every new developer has to follow when joining our team.

This path reflects our team's culture and values, which have their roots in the [agile values and principles](http://agilemanifesto.org/), as well as in those of XP, and in the [software craftsmanship manifesto](http://manifesto.softwarecraftsmanship.org/).

Please feel free to fork and contribute, add materials, fix the existing ones and propose new stuff.

## Main learning path

### 1) Methodology
* Read [The Agile Manifesto](https://agilemanifesto.org/) and the [Twelve Principles](https://agilemanifesto.org/principles.html) behind it ```#onboarding```
  * Read also about its [History](https://agilemanifesto.org/history.html) if you want to know more
* Read preface and chapters 1, 4, 5, 7 of [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416) by Kent Beck ```#onboarding``
* Watch ["The Agile Mindset - And Beyond"](https://www.youtube.com/watch?v=C13JC_YP2Q8) by Linda Rising (~ 50 minutes) ```#onboarding```
* For __italian speakers__, watch ["Perché è così difficile fare Extreme Programming"](https://vimeo.com/113090009) by Matteo Vaccari (~ 40 minutes) ```#onboarding```
* Read ["What is Extreme Programming?"](https://ronjeffries.com/xprog/what-is-extreme-programming/) post - definition of the 13 XP practices by Ron Jeffries
* Read first two sections of Martin Fowler's [Pair Programming blogpost](https://martinfowler.com/articles/on-pair-programming.html) (_How to pair_ + _Benefits_) ```#onboarding```
* Read _Iterative and Incremental Development_ paper by Robert C. Martin:
  * why [Waterfall](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDI.pdf) fails ```#onboarding```
  * why [Agile Method](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDII.pdf) can be the alternative ```#onboarding```
  * how to [Transit](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDIII.pdf) from first to second one

### 2) Testing and TDD
* Read chapter 9 of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) up to _"The Three Laws of TDD"_ section ```#onboarding```
* Read preface and chapters 1, 2, 3 of [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
* Try the [String Calculator Kata](https://github.com/qmates-tech/string-calculator-kata) in TDD ```#onboarding```
* For __italian speakers__, watch [Piergiuliano Bossi's screencasts](https://www.youtube.com/channel/UCKu3XCVh7pe06khn4N1uCiQ) on TDD basics and emergent design (~ 40 minutes x5 videos)
* Watch the Google Clean Code Talks series by Miško Hevery:
  - [Unit Testing](http://www.youtube.com/watch?v=wEhu57pih5w) (~ 30 minutes) - [[slides](https://docs.google.com/presentation/d/1mZsq0WljEfgIR9Df_IcW0VQfNl-Pk_cEBR3i9id-eR4/present#slide=id.i0)] [[blogpost](http://misko.hevery.com/2008/11/04/clean-code-talks-unit-testing/)] ```#onboarding```
  - [Inheritance, Polymorphism, & Testing](https://www.youtube.com/watch?v=4F72VULWFvc) (~ 40 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/12/08/clean-code-talks-inheritance-polymorphism-testing/)] ```#onboarding```
  - [Don't Look For Things!](https://www.youtube.com/watch?v=RlfLCWKxHJ0): includes Dependency Injection pattern (~ 35 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/11/11/clean-code-talks-dependency-injection/)]
  - [Global State and Singletons](https://www.youtube.com/watch?v=-FRm3VPhseI) (~ 55 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/11/21/clean-code-talks-global-state-and-singletons/)]
* Read Miško Hevery's guide on ["Writing Testable Code"](https://web.archive.org/web/20230531093323/http://misko.hevery.com/code-reviewers-guide/)
* Try the [Sales Kata](https://github.com/xpeppers/sales-taxes-problem) in TDD

### 3) Clean Code
* Read introduction and first six chapters of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) book by Robert C. Martin ```#onboarding```
* Read preface and first chapter of [The Pragmatic Programmer](https://www.amazon.it/Pragmatic-Programmer-Journeyman-Master/dp/020161622X/) book ```#onboarding```
* Watch Venkat Subramaniam's talk about ["Core Design Principles for Software Developers"](https://www.youtube.com/watch?v=llGgO74uXMI) (~ 150 minutes) ```#onboarding```
* Read first chapter of ["Applying UML and Patterns"](http://www.amazon.com/Applying-UML-Patterns-Introduction-Object-Oriented/dp/0131489062)
* Study the [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
  * [SRP: Single Responsibility Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
  * [OCP: Open-Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
  * [LSP: Liskov Substitution Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
  * [ISP: Interface Segregation Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
  * [DIP: Dependency Inversion Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)
* Try the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas):
  * find SOLID violations and discuss them with some collegues ```#onboarding```
  * try to write unit tests for analyzed classes
* Read [Names objects after things, not actions!](http://matteo.vaccari.name/blog/archives/743) by Matteo Vaccari
* Read the article [Keep It DRY, Shy, and Tell the Other Guy](http://media.pragprog.com/articles/may_04_oo1.pdf) ```#onboarding```
* Read the article [You Aren't Gonna Need It](http://wiki.c2.com/?YouArentGonnaNeedIt)

### 4) Refactoring
* Read preface and first three chapters of [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) by Martin Fowler ```#onboarding```
* Watch ["Workflows of Refactoring"](https://www.youtube.com/watch?v=vqEg37e4Mkw) talk by Martin Fowler (~ 25 minutes)
* Try the [Tennis-Refactoring-Kata](https://github.com/emilybache/Tennis-Refactoring-Kata) and spot the code smells (chapter 3 of [Refactoring](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) book) ```#onboarding```
* Watch [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0) screencast by Sandro Mancuso (~ 75 minutes) - [[example code](https://github.com/sandromancuso/trip-service-kata)]
* Try the [GildedRose-Refactoring-Kata](https://github.com/qmates-tech/GildedRose-Refactoring-Kata) following this steps: ```#onboarding```
  1. Code Coverage
  2. Code Refactoring
  3. Add the new feature

### 5) Simple and Testable design
* Read [Kent Beck's 4 Rules of Simple Design](https://martinfowler.com/bliki/BeckDesignRules.html) Martin Fowler's article ```#onboarding```
* Watch [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs) by Miško Hevery (~ 75 minutes)
* Read [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html) Scott Bellware's post
* Encapsulation and Information Hiding
  * Read [Nat Pryce's article](http://www.natpryce.com/articles/000498.html)
  * Read [C2 Wiki article](http://c2.com/cgi/wiki?EncapsulationIsNotInformationHiding)
* Try these Katas and compare your solution with related videos:
  * [The Bowling Game Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata) - [[related video](https://www.youtube.com/watch?v=OPGTPQ4kURU)]
  * [The Roman Numerals Kata](https://web.archive.org/web/20180602202843/http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary) - [[related video](https://www.youtube.com/watch?v=vX-Yym7166Y)]

### 6) Test driven & friends
* Read the first eight chapters of [Growing Object Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)
* Read [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html) Martin Fowler's article
* Read [The Little Mocker](https://blog.cleancoder.com/uncle-bob/2014/05/14/TheLittleMocker.html) Robert Martin's article
* Read [Overcoming the one weakness of OOP](http://blogs.ugidotnet.org/luKa/archive/2015/01/20/overcoming-the-one-weakness-of-oop.aspx)
* Read about the [Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
* Watch [Ian Cooper - TDD, where did it all go wrong](http://vimeo.com/68375232)
* Watch [J.B. Rainsberger - Integrated Tests Are A Scam](http://vimeo.com/80533536)
* Watch [Sandro Mancuso - Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
* Watch [Sandro Mancuso - Crafted Design](http://vimeo.com/101106002)
* Watch [Mock Roles Not Object States](http://www.infoq.com/news/2008/08/Mock-Roles-Pryce-and-Freeman) - [Paper](http://jmock.org/oopsla2004.pdf)
* Try to do a known kata applying some [Object Calisthenics](http://williamdurand.fr/2013/06/03/object-calisthenics/) rule and discuss effects with some collegues

### 7) Hexagonal architecture

* Read https://web.archive.org/web/20170916120520/http://alistair.cockburn.us/Hexagonal+architecture ```#onboarding```
* Read http://matteo.vaccari.name/blog/the-hexagonal-architecture
* Read http://matteo.vaccari.name/blog/archives/154
* Read http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid
* Read http://c2.com/cgi/wiki?HexagonalArchitecture

### 8) Systems architecture

* Read chapters about Stability 3, 4, 5 and Capacity 8, 9, 10 of [Release It!](https://pragprog.com/book/mnee/release-it) ```#onboarding```

## Complete the main learning path

### More on Methodology
* Complete [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416) by Kent Beck: starts from chapters 2 and 6
* Complete Martin Fowler's [Pair Programming blogpost](https://martinfowler.com/articles/on-pair-programming.html)
* Read [The Pomodoro Technique paper](http://friend.ucsd.edu/reasonableexpectations/downloads/Cirillo%20--%20Pomodoro%20Technique.pdf)
* Flat Organizations:
   * [The Flat Way](https://link.medium.com/E4kjMXajO3) ```#onboarding```
   * [Teal Is The New Black: Self-management and the future of work](https://management30.com/blog/teal-organization-self-management-future-of-work/)
   * [Collaborative decision making in self-organizing teams](https://www.agilebusinessday.com/2019/09/26/collaborative-decision-making-in-self-organizing-teams-abd19-lorenzo-massacci/)
 
### More on Testing and TDD
* Complete [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
* [Lets Play on TDD](http://www.jamesshore.com/Blog/Lets-Play) series by James Shore
* [The World's Best Intro to TDD](http://online-training.jbrains.ca/p/wbitdd-01) by J. B. Rainsberger

### More on Clean Code
* Complete [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) book by Robert C. Martin
* Complete [The Pragmatic Programmer](https://www.amazon.it/Pragmatic-Programmer-Journeyman-Master/dp/020161622X/) book
* Tell Don't Ask principle
  * read the article [Tell, Don't Ask](http://archive.is/Bk10R/)
  * read the article [The Art of Enbugging](http://media.pragprog.com/articles/jan_03_enbug.pdf)
* Watch [Is SOLID A Good Idea](http://vimeo.com/20388419) (~ 55 minutes)
* Watch [Responsive Design](http://www.infoq.com/presentations/responsive-design) (~ 70 minutes)
* Follow the ["Clean coders"](http://cleancoders.com/) series by Robert C. Martin

## Beyond Software Development

### Becoming a "full-stack" Agile Developer
* Watch [7 minutes, 26 seconds, and the Fundamental Theorem of Agile Software Development](https://www.youtube.com/watch?v=WSes_PexXcA) by J.B. Rainsberger

### Software development economics
* Read chapter 3 ```"Economics of Software Development"``` of [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416)
* Read chapter 7, section with title ```"Tools 22": Contracts``` of [Lean Software Development: An Agile Toolkit](https://www.amazon.com/Lean-Software-Development-Agile-Toolkit/dp/0321150783)

## Side learning paths
* [Languages](study-path/languages)
* [Tools](study-path/tools)
* [On Microservices](study-path/microservices)
* [An Agile Study Path](study-path/agile)

### Additional Bibliography
* [__"Patterns of Enterprise Application Architecture"__](http://www.amazon.it/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420) by Martin Fowler
* [__"Working Effectively with Legacy Code"__](http://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052) by Micheal Feathers
* [__"Understanding the Four Rules of Simple Design"__](https://leanpub.com/4rulesofsimpledesign) by C.Haines

### Other honorable learning paths
* [JoeBew's Study Path](https://github.com/joebew42/study-path)!
