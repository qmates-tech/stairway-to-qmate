# QMates' learning path

This is the learning path every new developer has to follow when joining our team.

This path reflects our team's culture and values, which have their roots in the [agile values and principles](http://agilemanifesto.org/), as well as in those of XP, and in the [software craftsmanship manifesto](http://manifesto.softwarecraftsmanship.org/).

Please feel free to fork and contribute, add materials, fix the existing ones and propose new stuff.

How to use: the resources or kata are divided by macro-topics and in order of complexity. You can compose your study iterations taking resources from the topics (even different) you're interested.

## Main learning path

### # Methodology
* Read [The Agile Manifesto](https://agilemanifesto.org/) and the [Twelve Principles](https://agilemanifesto.org/principles.html) behind it ```#onboarding```
  * Read also about its [History](https://agilemanifesto.org/history.html) if you want to know more
* Read _Iterative and Incremental Development_ paper by Robert C. Martin:
  * why [Waterfall](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDI.pdf) fails
  * why [Agile Method](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDII.pdf) can be the alternative ```#onboarding```
  * Watch [7 minutes, 26 seconds, and the Fundamental Theorem of Agile Software Development](https://www.youtube.com/watch?v=WSes_PexXcA) by J.B. Rainsberger
  * how to [Transit](https://condor.depaul.edu/dmumaugh/readings/handouts/IS375/IIDIII.pdf) from first to second one
* Read preface and chapters 1, 4, 5, 7 of [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416) by Kent Beck ```#onboarding```
* Watch ["The Agile Mindset - And Beyond"](https://www.youtube.com/watch?v=C13JC_YP2Q8) by Linda Rising (~ 50 minutes)
* Read ["What is Extreme Programming?"](https://ronjeffries.com/xprog/what-is-extreme-programming/) post - definition of the 13 XP practices by Ron Jeffries ```#onboarding```
* For __italian speakers__, watch ["Perché è così difficile fare Extreme Programming"](https://vimeo.com/113090009) by Matteo Vaccari (~ 40 minutes) ```#onboarding```
* For __italian speakers__, watch ["Vivere per raccontarla: l’importanza del daily journal in un team agile"](https://vimeo.com/195952480) by Pietro Di Bello (~ 15 minutes) ```#onboarding```
* Read [Scrum Guide (LeSS Version)](https://less.works/less/scrum-guide) by Craig Larman and Bas Vodde

### # Pair Programming
* Read first two sections of Martin Fowler's [Pair Programming blogpost](https://martinfowler.com/articles/on-pair-programming.html) (_How to pair_ + _Benefits_) ```#onboarding```
* Read [Pairing Session Template](https://tuple.app/pair-programming-guide/template) on how setting up a pairing session by Tuple
* Focusing on pair programming antipatterns:
  - Read [Pair programming antipatterns](https://tuple.app/pair-programming-guide/antipatterns)
  - Watch [Pair programming antipatterns](https://www.youtube.com/watch?v=ReuFZYtGeCc) (~ 5 minutes)
  - Watch [Killing me softly - with this Pair](https://www.infoq.com/presentations/pair-programming-play/) (~ 20 minutes)

### # Testing and TDD
* Read chapter 2 of [Working Effectively with Legacy Code](https://www.amazon.com/Working-Effectively-Legacy-Code-EFFECT-ebook/dp/B005OYHF0A?qid=1698919236&sr=8-1) up to _"What is Unit Testing?"_ section ```#onboarding```
* Read chapter 9 of [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) up to _"The Three Laws of TDD"_ section ```#onboarding```
* Read preface and chapters 1, 2, 3 of [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530) ```#onboarding```
* Try the [String Calculator Kata](https://github.com/qmates-tech/string-calculator-kata) in TDD ```#onboarding```
* For __italian speakers__, watch [Piergiuliano Bossi's screencasts](https://www.youtube.com/channel/UCKu3XCVh7pe06khn4N1uCiQ) on TDD basics and emergent design (~ 40 minutes x5 videos)
* Watch the Google Clean Code Talks series by Miško Hevery:
  - [Unit Testing](http://www.youtube.com/watch?v=wEhu57pih5w) (~ 30 minutes) - [[slides](https://docs.google.com/presentation/d/1mZsq0WljEfgIR9Df_IcW0VQfNl-Pk_cEBR3i9id-eR4/present#slide=id.i0)] [[blogpost](http://misko.hevery.com/2008/11/04/clean-code-talks-unit-testing/)] ```#onboarding```
  - [Inheritance, Polymorphism, & Testing](https://www.youtube.com/watch?v=4F72VULWFvc) (~ 40 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/12/08/clean-code-talks-inheritance-polymorphism-testing/)] ```#onboarding```
  - [Don't Look For Things!](https://www.youtube.com/watch?v=RlfLCWKxHJ0): includes Dependency Injection pattern (~ 35 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/11/11/clean-code-talks-dependency-injection/)]
  - [Global State and Singletons](https://www.youtube.com/watch?v=-FRm3VPhseI) (~ 55 minutes) - [[blogpost and slides](http://misko.hevery.com/2008/11/21/clean-code-talks-global-state-and-singletons/)]
* Read Miško Hevery's guide on ["Writing Testable Code"](https://web.archive.org/web/20230531093323/http://misko.hevery.com/code-reviewers-guide/)
* Try the [Sales Kata](https://github.com/xpeppers/sales-taxes-problem) in TDD

### # Clean Code
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

### # Refactoring
* Read preface and first three chapters of [Refactoring: Improving the design of existing code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) by Martin Fowler ```#onboarding```
* Watch ["Workflows of Refactoring"](https://www.youtube.com/watch?v=vqEg37e4Mkw) talk by Martin Fowler (~ 25 minutes)
* Try the [Tennis-Refactoring-Kata](https://github.com/emilybache/Tennis-Refactoring-Kata) and spot the code smells (chapter 3 of [Refactoring](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) book) ```#onboarding```
* Read part I - Tydings of [Tidy First?](https://www.amazon.it/Tidy-First-Personal-Exercise-Empirical/dp/1098151240) by Kent Beck
* Try [Tennis-Refactoring-Kata](https://github.com/emilybache/Tennis-Refactoring-Kata) again spotting the tydings you used 
* Watch [Testing and Refactoring Legacy Code](https://www.youtube.com/watch?v=_NnElPO5BU0) screencast by Sandro Mancuso (~ 75 minutes) - [[example code](https://github.com/sandromancuso/trip-service-kata)]
  * take also a look into his [trip-service-kata code](https://github.com/sandromancuso/trip-service-kata)
* Read [Parallel change (aka: expand and contract)](https://martinfowler.com/bliki/ParallelChange.html) by Martin Fowler
* Try the [GildedRose-Refactoring-Kata](https://github.com/qmates-tech/GildedRose-Refactoring-Kata) following this steps: ```#onboarding```
  1. Code Coverage
  2. Code Refactoring
  3. Add the new feature

### # Simple and Testable design
* Read [Kent Beck's 4 Rules of Simple Design](https://martinfowler.com/bliki/BeckDesignRules.html) Martin Fowler's article ```#onboarding```
* Watch [How to Write Clean, Testable Code](https://www.youtube.com/watch?v=XcT4yYu_TTs) by Miško Hevery (~ 75 minutes)
* Read [Good Design is Easily-Learned](http://blog.scottbellware.com/2009/01/good-design-is-easily-learned.html) Scott Bellware's post
* Encapsulation and Information Hiding
  * Read [Nat Pryce's article](http://www.natpryce.com/articles/000498.html)
  * Read [C2 Wiki article](http://c2.com/cgi/wiki?EncapsulationIsNotInformationHiding)
* Try these Katas and compare your solution with related videos:
  * [The Bowling Game Kata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata) - [[related video](https://www.youtube.com/watch?v=OPGTPQ4kURU)]
  * [The Roman Numerals Kata](https://web.archive.org/web/20180602202843/http://www.codekatas.org/casts/roman-numerals-kata-with-audio-commentary) - [[related video](https://www.youtube.com/watch?v=vX-Yym7166Y)]

### # Test driven & friends
* Read the first eight chapters of [Growing Object Oriented Software, Guided by Tests](http://www.growing-object-oriented-software.com/)
* Read introduction and chapters 1-6 of [xUnit Test Patterns: Refactoring Test Code](https://www.amazon.com/xUnit-Test-Patterns-Refactoring-Code/dp/0131495054)
* Read [Mocks Aren't Stubs](http://martinfowler.com/articles/mocksArentStubs.html) Martin Fowler's article
* Read [The Little Mocker](https://blog.cleancoder.com/uncle-bob/2014/05/14/TheLittleMocker.html) Robert Martin's article
* Read [How I learned to love mocks](https://medium.com/@xpmatteo/how-i-learned-to-love-mocks-1-fb341b71328) - Matteo Vaccari
* Read [Overcoming the one weakness of OOP](http://blogs.ugidotnet.org/luKa/archive/2015/01/20/overcoming-the-one-weakness-of-oop.aspx)
* Read about the [Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
* Watch [Ian Cooper - TDD, where did it all go wrong](http://vimeo.com/68375232)
* Watch [J.B. Rainsberger - Integrated Tests Are A Scam](http://vimeo.com/80533536)
* Watch [Sandro Mancuso - Crafted Design](https://www.youtube.com/watch?v=dYvSaajboEs)
* Watch [Mock Roles Not Object States](http://www.infoq.com/news/2008/08/Mock-Roles-Pryce-and-Freeman) - [Paper](http://jmock.org/oopsla2004.pdf)
* Try to do a known kata applying some [Object Calisthenics](http://williamdurand.fr/2013/06/03/object-calisthenics/) rule and discuss effects with some collegues
* Read Part II, Test Smells, chapters 15-17 of [xUnit Test Patterns: Refactoring Test Code](https://www.amazon.com/xUnit-Test-Patterns-Refactoring-Code/dp/0131495054)

### # Architecture
* Read chapter 1, introcuction [Lean Architecture: for Agile Software Development](https://a.co/d/0ndvAtw)
* Read [Alistair Cockburn - Hexagonal architecture](https://web.archive.org/web/20170916120520/http://alistair.cockburn.us/Hexagonal+architecture) ```#onboarding```
* Read [Matteo Vaccari - Hexagonal architecture](http://matteo.vaccari.name/blog/the-hexagonal-architecture)
* Read [Matteo Vaccari - Birthday Greetings kata](http://matteo.vaccari.name/blog/archives/154)
* Read [The Forgotten Layer of the Test Automation Pyramid](http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid)
* Read [Hexagonal architecture - wiki-c2](http://c2.com/cgi/wiki?HexagonalArchitecture)
* Watch Uncle Bob lessons on [Clean code/architecture](https://www.youtube.com/playlist?list=PLauZ2TQIEOHbV_PlLQEr2OtuW9B8HaoCQ) (~ 10 hours)

### # Infrastructure Operations
* Read chapters about Stability 3, 4, 5 and Capacity 8, 9, 10 of [Release It!](https://a.co/d/9aQ719u) ```#onboarding```
* Read the definition of continuous delivery [What is continuous delivery?](https://continuousdelivery.com/)
* Read the principles of continuous delivery [Principles - Continuous Delivery](https://continuousdelivery.com/principles/)
* Read [Continuous Delivery](https://a.co/d/cMpvaFw) book to go deeper

## (going deeper with) Advanced learning path

### # Methodology
* Complete [XP Explained](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416) by Kent Beck: starts from chapters 2 and 6
* Complete Martin Fowler's [Pair Programming blogpost](https://martinfowler.com/articles/on-pair-programming.html)
* Read [The Pomodoro Technique paper](http://friend.ucsd.edu/reasonableexpectations/downloads/Cirillo%20--%20Pomodoro%20Technique.pdf)
* Flat Organizations:
   * [The Flat Way](https://link.medium.com/E4kjMXajO3)
   * [Teal Is The New Black: Self-management and the future of work](https://management30.com/blog/teal-organization-self-management-future-of-work/)
   * [Decision-making methods: a comparison](https://www.sociocracyforall.org/decision-making-methods-comparison/) by Sociocracy 3.0
   * [Consent Decision Making Demonstration](https://www.youtube.com/watch?v=uJG5f4EBGGQ) by Sociocracy 3.0
* Read [Introduction to LeSS - Large Scale Scrum](https://less.works/less/framework/introduction) by Craig Larman and Bas Vodde
* Read [The Principles of product development flow](https://a.co/d/fEoXtZb) by Don Reinertsen

### # Testing and TDD
* Complete [Test Driven Development: By Example](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
* [Lets Play on TDD](http://www.jamesshore.com/Blog/Lets-Play) series by James Shore
* [The World's Best Intro to TDD](http://online-training.jbrains.ca/p/wbitdd-01) by J. B. Rainsberger

### # Clean Code
* Complete [Clean Code](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) book by Robert C. Martin
* Complete [The Pragmatic Programmer](https://www.amazon.it/Pragmatic-Programmer-Journeyman-Master/dp/020161622X/) book
* Tell Don't Ask principle
  * read the article [Tell, Don't Ask](http://archive.is/Bk10R/)
  * read the article [The Art of Enbugging](http://media.pragprog.com/articles/jan_03_enbug.pdf)
* Watch [Is SOLID A Good Idea](http://vimeo.com/20388419) (~ 55 minutes)
* Watch [Responsive Design](http://www.infoq.com/presentations/responsive-design) (~ 70 minutes)
* Follow the ["Clean coders"](http://cleancoders.com/) series by Robert C. Martin

### # Test driven & friends
* Read part III, The Patterns of [xUnit Test Patterns: Refactoring Test Code](https://www.amazon.com/xUnit-Test-Patterns-Refactoring-Code/dp/0131495054)

### # Software development economics
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
