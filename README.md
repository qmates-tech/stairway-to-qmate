# QMates' learning path

This is the learning path every new developer has to follow when joining our team.

This path reflects our team's culture and values, which have their roots in the [agile values and principles](http://agilemanifesto.org/), as well as in those of XP, and in the [software craftsmanship manifesto](http://manifesto.softwarecraftsmanship.org/).

Please feel free to fork and contribute, add materials, fix the existing ones and propose new stuff.

## Main learning path

### 1) Methodology
* Read preface and chapters 1, 4, 5, 7 of [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416) by Kent Beck ```#onboarding```
* "[What Exactly is the Agile Mindset?](https://www.infoq.com/articles/what-agile-mindset/)" InfoQ article  ```#onboarding```
* For __italian speakers__, Watch ["Perché è così difficile fare Extreme Programming"](https://vimeo.com/113090009) by Matteo Vaccari ```#onboarding```
* Martin Fowler's [Pair Programming blogpost](https://martinfowler.com/articles/on-pair-programming.html): choose some interesting parts ```#onboarding```
* Iterative and Incremental Development paper by Robert C. Martin:
  * why [Waterfall](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDI.pdf) fails ```#onboarding```
  * why [Agile Method](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDII.pdf) can be the alternative ```#onboarding```
  * how to [Transition](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDIII.pdf) from first to second one

### 2) Testing and TDD
* Read chapter 9 of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) up to _"The Three Laws of TDD"_ section ```#onboarding```
* Read preface and chapters 1, 2, 3 of [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
* For __italian speakers__, [Piergiuliano Bossi's screencasts](https://www.youtube.com/channel/UCKu3XCVh7pe06khn4N1uCiQ) on TDD basics and emergent design
* Google Clean Code Talks series by Miško Hevery:
  - [Unit Testing](http://www.youtube.com/watch?v=wEhu57pih5w) (~ 30 minutes) - [[slides](https://docs.google.com/presentation/d/1mZsq0WljEfgIR9Df_IcW0VQfNl-Pk_cEBR3i9id-eR4/present#slide=id.i0)] [[blogpost](http://misko.hevery.com/2008/11/04/clean-code-talks-unit-testing/)] ```#onboarding```
  - [Inheritance, Polymorphism, & Testing](https://www.youtube.com/watch?v=4F72VULWFvc) (~ 40 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/12/08/clean-code-talks-inheritance-polymorphism-testing/)] ```#onboarding```
  - [Don't Look For Things!](https://www.youtube.com/watch?v=RlfLCWKxHJ0): includes Dependency Injection pattern (~ 35 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/11/11/clean-code-talks-dependency-injection/)]
  - [Global State and Singletons](https://www.youtube.com/watch?v=-FRm3VPhseI) (~ 55 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/11/21/clean-code-talks-global-state-and-singletons/)]
* Miško Hevery's guide on ["Writing Testable Code"](https://web.archive.org/web/20230531093323/http://misko.hevery.com/code-reviewers-guide/)
* Do the [Sales Kata](https://github.com/xpeppers/sales-taxes-problem) in TDD ```#onboarding```

### 3) Clean code
* Read the article [Keep It DRY, Shy, and Tell the Other Guy](http://media.pragprog.com/articles/may_04_oo1.pdf) ```#onboarding```
* Read the article [You Aren't Gonna Need It](http://wiki.c2.com/?YouArentGonnaNeedIt)
* Tell Don't Ask principle
  * read the article [Tell, Don't Ask](http://archive.is/Bk10R/)
  * read the article [The Art of Enbugging](http://media.pragprog.com/articles/jan_03_enbug.pdf)
* Do the [Kata String Calculator](https://github.com/xpeppers/string-calculator-kata)
* Read first chapter of ["Applying UML and Patterns"](http://www.amazon.com/Applying-UML-Patterns-Introduction-Object-Oriented/dp/0131489062)
* Read first ten chapters of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
* [SOLID principles](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod) ```#onboarding```
  * [SRP: Single Responsibility Principle](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
  * [OCP: Open-Closed Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
  * [LSP: Liskov Substitution Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
  * [ISP: Interface Segregation Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
  * [DIP: Dependency Inversion Principle](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)
* Start the [Racing Car Katas](https://github.com/emilybache/Racing-Car-Katas) ```#onboarding```
  * find SOLID violations
* Read [Names objects after things, not actions!](http://matteo.vaccari.name/blog/archives/743) by Matteo Vaccari
* Watch Venkat Subramaniam's talk about ["Core Design Principles for Software Developers"](https://www.youtube.com/watch?v=llGgO74uXMI) ```#onboarding```
* Read [The Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer)
* Watch [Is SOLID A Good Idea](http://vimeo.com/20388419)
* Watch [Responsive Design](http://www.infoq.com/presentations/responsive-design)
* Extra: Follow the [__"Clean coders"__](http://cleancoders.com/) screencasts by Robert C. Martin

### 4) Refactoring

* Watch [Martin Fowler @ OOP2014 "Workflows of Refactoring"](https://www.youtube.com/watch?v=vqEg37e4Mkw)
* Read first three chapters of [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) ```#onboarding```
* Watch [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
  * [Example Code](https://github.com/sandromancuso/trip-service-kata)
* Try the [GildedRoseKata](https://github.com/joebew42/GildedRose) ```#onboarding```
  * Code Coverage
  * Code Refactoring
  * Add the new feature
* Try the [TennisRefactoringKata](https://github.com/emilybache/Tennis-Refactoring-Kata) (find code smells)

### 5) TDD and "Friends"

* Read [The Four Elements of Simple Design](http://www.jbrains.ca/permalink/the-four-elements-of-simple-design) ```#onboarding```
* [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs)
* [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html)
* Try to learn and repeat these Katas autonomously
  * [TheBowlingGameKata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
  * [TheRomanNumeralsKata](https://web.archive.org/web/20180602202843/http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary) ([video](https://www.youtube.com/watch?v=vX-Yym7166Y))
* Read the first eight chapters of [Growing Object Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)
* [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html)
* Encapsulation e Information Hiding:
  * http://www.natpryce.com/articles/000498.html
  * http://c2.com/cgi/wiki?EncapsulationIsNotInformationHiding
* Read [Overcoming the one weakness of OOP](http://blogs.ugidotnet.org/luKa/archive/2015/01/20/overcoming-the-one-weakness-of-oop.aspx)
* Read [Object Calisthenics](http://williamdurand.fr/2013/06/03/object-calisthenics/)
* Read about the [Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
* Watch [Ian Cooper - TDD, where did it all go wrong](http://vimeo.com/68375232)
* Watch [J.B. Rainsberger - Integrated Tests Are A Scam](http://vimeo.com/80533536)
* Watch [Sandro Mancuso - Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0)
* Watch [Sandro Mancuso - Crafted Design](http://vimeo.com/101106002)
* Watch [Mock Roles Not Object States](http://www.infoq.com/news/2008/08/Mock-Roles-Pryce-and-Freeman) - [Paper](http://jmock.org/oopsla2004.pdf)

### 6) Hexagonal architecture

* Read https://web.archive.org/web/20170916120520/http://alistair.cockburn.us/Hexagonal+architecture ```#onboarding```
* Read http://matteo.vaccari.name/blog/the-hexagonal-architecture
* Read http://matteo.vaccari.name/blog/archives/154
* Read http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid
* Read http://c2.com/cgi/wiki?HexagonalArchitecture

### 7) Systems architecture

* Read chapters about Stability 3, 4, 5 and Capacity 8, 9, 10 of [Release It!](https://pragprog.com/book/mnee/release-it) ```#onboarding```

## Beyond Software Development

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
