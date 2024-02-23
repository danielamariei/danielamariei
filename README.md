* [Good thoughts 🖖](#good-thoughts-)
* [Contact me ✍](#contact-me-)
* [Projects 📋](#projects-)
* [Talks 👨‍🏫](#talks-)

### Good thoughts 🖖
Hi there! My name is Daniel.

## Contact me ✍
Drop me a note or get in touch with me: [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSdidsTCj9zd0gAEh-BcfCatbCa-2fmFDFItFnDSj57JjAcTDA/viewform). 

## Projects 📋
Here are some projects I've been working on. You can also [play TeTwix, a nice game developed by me and a colleague 🎮](https://danielamariei.github.io/tetwix/serverless/).

* [TeTwix](#tetwix)
* [Company Classification](#company-classification)
* [Points Distance](#points-distance)
* [Product Ratings](#product-ratings)
* [Clothing Ontology](#clothing-ontology)
* [Semantic Clothing](#semantic-clothing)
* [Databases Ontology](#databases-ontology)
* [Databases Ontology Demo App](#databases-ontology-demo-app)
* [Movie Recommendation](#movie-recommendation)


### TeTwix
**Tetris GamR (Game Resurrection)**
* [Play the game](https://danielamariei.github.io/tetwix/serverless/)
* **GitHub repo**: https://github.com/danielamariei/tetwix
* **You can see a demo of the game here**: [TeTwix](https://vimeo.com/98003746) 

The game proposes a modern version of Tetris, it supports multiplayer game modes, while user(s) are able to use natural I/O devices and interaction methods such as: gestural ([Leap Motion](https://www.ultraleap.com/product/leap-motion-controller/)), locomotion ([Makey Makey](https://makeymakey.com/)), etc. The game is attractive for various population segments and can be used as a means for having fun or to carry out cardio exercises, a serious game, and many others.

**Tech: JavaScript, HTML, CSS, Leap Motion Controller, Makey Makey**

### Company Classification 
**GitHub repo**: https://github.com/danielamariei/company-classification

* Exploratory Java application for indexing a corpus of articles and searching companies in the corpus of articles using different strategies
* Exploring the use of Lucene for indexing text and searching the index using various Query techniques
* Fine-tuning for optimal results is required and is context-dependent
* Please take into consideration that this is a specific use-case and the same technique/approach can be used in other contexts (e.g., DNA sequencing, finding specific faults in sets of wafers to be inspected, etc.)

**Tech: Java, Spring, Spring Boot, Lucene, Gradle**

### Points Distance 
**GitHub repo**: https://github.com/danielamariei/points-distance

Point Distance calculation on a large corpus of input points using different approaches. Determines the optimal set of points according to predefined metrics (i.e., closest, farthest to the reference point). Provides different proximity calculator possibilities (e.g., Priority Queues, Sorting, etc.); abstracts different strategies. Ability to read the points from different sources: binary file, JSON, etc. Provides support for reading the input in a lazy fashion through iterators.

**Tech: Java, Spring, Spring Boot, Gradle**

### Product Ratings
**GitHub repo**: https://github.com/danielamariei/product-ratings

- Java Application that reads a large corpus of product ratings, processes them, and computes relevant metrics. 
- Uses the Java API for Bean Validation (JSR 380) to ensure that fields meet specific criteria in a declarative format.
- Ability to read the points from different sources: binary file, JSON, etc. 
- Provides support for reading the input in a lazy fashion through iterators. 
- Optimally determines the top k best rated and worst rated products by using a Priority Queue. 


**Tech: Java, Spring, Spring Boot, Gradle, Java API for Bean Validation (JSR 380)**

### Clothing Ontology
**GitHub repo**: https://github.com/danielamariei/clothing-ontology

The purpose of this ontology is to create the common conceptual framework for 'talking' about clothing and/or related concepts. This should provide a common vocabulary for this domain.

**Tech: OWL 2 Web Ontology Language, SPARQL Query Language for RDF**

### Semantic Clothing
**GitHub repo**: https://github.com/danielamariei/semantic-clothing

Semantic Clothing Web Application that enables the selection of different clothing items based on the existing wardrobe. Some people have difficulties when choosing the right vestment for a certain type of event (_i.e._, interview, dinner party, show, etc.). The purpose of the project is to create an Web Application that enables the selection of different clothing items based on the existing wardrobe; the information of interest can be obtained from [DBpedia](http://wiki.dbpedia.org/About) or
 [Freebase](https://developers.google.com/freebase/). The application will offer suggestions that take into account the fashion proclivity, the season, or different preferences that the user has. Moreover, the user will be able to receive information regarding the purchasing of different items of interest, taking into account its geographic localization.
 
 **Tech: REST, RAML, OWL 2, SPARQL, Stardog, Scala, PHP, JavaScrip, HTML, CSS**

### Databases Ontology 
**GitHub repo**: https://github.com/danielamariei/databases-ontology

The purpose of this ontology is to create the common conceptual framework for 'talking' about databases and/or related concepts. This should provide a common vocabulary for the domain. The results are captured in the following paper: [S. C. Buraga, D. Amariei and O. Dospinescu, "An owl-based specification of database management systems," Computers, Materials & Continua, vol. 70, no.3, pp. 5537–5550, 2022.](https://www.techscience.com/cmc/v70n3/45029)


**Tech: OWL 2 Web Ontology Language, SPARQL Query Language for RDF**

### Databases Ontology Demo App 
**GitHub repo**: https://github.com/danielamariei/databases-ontology-demo-app

The purpose of this application is to provide a demo for the usage of the Database Management Systems Ontology (DBMSs Ontology) ontology. It provides an interactive comparison of different characteristics of interest for several databases.

For more details regarding the DBMSs Ontology please consult the dedicated repository: https://github.com/danielamariei/databases-ontology/.

**Tech: Node.js, Stardog, OWL 2, SPARQL**

### Movie Recommendation
**GitHub repo**: https://github.com/danielamariei/movie-recommendations

The implementation of a movie recommendation system on top of the Hadoop platform using Apache Pig and Apache Hive. 

The purpose of this project is to provide movie recommendations based on the ratings made be multiple users. It uses a collaborative filtering algorithm in order to construct user profiles, detect the closest users and construct a set of movies that the users will most likey appreciate. The algorithm is based on the work presented in the following book (chapter 9): Title: Minning of Massive Datasets, Authors: Jure Leskovec, Anand Rajaraman and Jeffrey D, Ullman.
 
 Input:
 - a CSV file with user ratings that has the following columns at least:userId, movieId and rating,
 - a CSV file with movie data that has the following columns at least: movieId and movieTitle,
 - the id of the user for which we want to make the recommendations, 
 - the size of the sample from the ratings file on which we should base our algorithm.
  
 Output:
 - a list of recommended movie titles.

**Tech: Hadoop, Apache Pig, Apache Hive, Python**

## Talks 👨‍🏫

* [Monologue for the Cloud](#monologue-for-the-cloud)
* [Natural/unconventional interfaces and game resurrection](#naturalunconventional-interfaces-and-game-resurrection)
* [RESTing on MVC using Node.js and Express](#resting-on-mvc-using-nodejs-and-express)
* [AOP Case Studies](#aop-case-studies)
* [Erlang](#erlang)
* [Cppcheck Your Code](#cppcheck-your-code)
* [Insufficient Process Validation](#insufficient-process-validation)
* [SQL Injection Tools: Pangoling and sqlmap](#sql-injection-tools-pangoling-and-sqlmap)
* [w3af: Web Application Attack and Audit Framework](#w3af-web-application-attack-and-audit-framework)



### Monologue for the Cloud

**Presentation**: [Monologue for the Cloud](https://github.com/danielamariei/talks/tree/master/monologue-for-the-cloud)

The purpose of this presentation is to introduce the concept of Cloud computing. In order to accomplish this, we structured the presentation as follows:

* **Main characteristics**: In this section, we describe the main characteristics that Cloud computing exhibits.
* **Architecture and service models**: This section provides details regarding the architecture of the Cloud, together with the stack of service models.
* **Advantages. Disadvantages**: In this section, we present the duality between the advantages and disadvantages of Cloud computing.
* **Cloud providers**: We enumerate some of the most popular Cloud computing platforms. We conclude with a description of OpenStack, an open-source Cloud computing platform.
* **Do we use the Cloud?**: In the final part of the presentation, we conclude with a description of several popular freely available web applications that are empowered by the Cloud.

**#cloud-computing, #IaaS, #PaaS, #SaaS, #CloudComputing**

### Natural/unconventional interfaces and game resurrection

**Presentation**: [Natural/unconventional interfaces and game resurrection](https://github.com/danielamariei/talks/tree/master/natural-unconventional-interfaces-and-game-resurrection)

The purpose of this presentation is twofold. Firstly, we explore unconventional user interfaces (e.g. haptic, speech, olfactory, etc.) which become an increasingly prevalent mode of interaction. Secondly, we describe an open-source game (i.e. TeTwix, Website: https://github.com/danielamariei/tetwix) which proposes a modern version of the classical electronic game Tetris by adopting these new user interaction techniques.

* **Nontraditional interfaces**: In this section of the presentation, we expose the main characteristics for each interaction method, as well as the general context which enables them to be used as a day-to-day technology. Several examples are also included.
* **Tetris GamR (Game Resurrection)**: We describe the main aspects of our developed game. As the game proposes a modern version of Tetris, it supports multiplayer game modes, while user(s) are able to use natural I/O devices and interaction methods such as: gestural (Leap Motion), locomotion (Makey Makey), etc. The game is attractive for various population segments and can be used as a means for having fun or to carry out cardio exercises, a serious game, and many others.

**#HCI**

### RESTing on MVC using Node.js and Express

**Presentation**: [RESTing on MVC using Node.js and Express](https://github.com/danielamariei/talks/tree/master/rest-mvc-express)

In this talk we review some of the basics aspects that we deal with when developing software for the World Wide Web (WWW). Some of the topics that are discussed include:
* **What a Pattern is and the different types;**
* **The MVC Architectural Pattern;**
* **The REST Architectural style;**
* **The Node.js framwork;**
* **Creating a basic application using Express.**

**#REST, #HTTP, #MVC, #Node.js, ##DesignPatterns**

### AOP Case Studies

**Presentation**: [AOP Case Studies](https://github.com/danielamariei/talks/tree/master/aop-case-studies)

In this talk with go over some Aspect Oriented Programming (AOP) case studies, together with some practical examples.

* Using AOP with class hierarchies
* Runtime measurement: 
  * AOP 
  * The classical approach

**#AOP, #AspectOrientedProgramming**

### Erlang

**Presentation**: [Erlang](https://github.com/danielamariei/talks/tree/master/erlang)

The purpose of this presentation is to describe the Erlang programming language together with a few concepts that entail a better understanding of the context. The presentation will cover the following aspects:
* consistency models and examples
* concurrency and parallelism and the difference between them
* concurrency models 
* the Actor mode
* the Erlang programming language
* programming examples


**#Erlang, #ConsistencyModels, #Concurrency, #Parallelism, #ActorModel**

### Cppcheck Your Code

**Presentation**: [Cppcheck Your Code](https://github.com/danielamariei/talks/tree/master/cpp-check-your-code)

The purpose of this talk is to offer a concise view of program analysis, especially static program analysis, using **Cppcheck** as a tool. The presentation covers topic as follows: 
* the levels at which a program analysis can be performed; 
* program analysis and possible approaches in performing it; 
* Cppcheck presentation, both from an architectural and practical standpoints

Practical examples for the including, but not limited to:
* out of bonds errors
* unitialized variable error
* unused function errors 
* unused variable errors
* buffer overflow errros
* using initialized memory only
* must free the buffer after using it
* detection of redundant conditional expressions
* configuration possibilities

#program-analysis, #ProgramAnalysis, #Cppcheck, #cpp-check


### Insufficient Process Validation

**Presentation**: [Insufficent Process Validation](https://github.com/danielamariei/talks/tree/master/insufficient-process-validation)


The purpose of this talk is to cover how `Insufficient Process Validation` occurs when a Web Application fails to prevent an attacker from circumventing the intended flow or business logic of the application [1]. For example, if the user state through a process is not sufficiently well verified, the Web Site is vulnerable to exploitation or fraud.

We cover practical examples that depict `Insuficient Process Validation` situations:
* `best-buy`: Entering negative values on donation forms.
* `list`: Listing directories without beeing authenticated.
* `youtube`: Accessing restricted content.


**#OWASP, #InsuficientProcessValidation**


### SQL Injection Tools: Pangoling and sqlmap

**Presentation**: [SQL Injection Tools: Pangoling and sqlmap](https://github.com/danielamariei/talks/tree/master/pangoling-and-sqlmap)

The presentation introduce the following SQL Injection Tools: Pangolin and sqlmap. These are penetration testing tools that automate the process of detecting and exploiting SQL Injection vulnerabilities. Pangolin is a penetration testing, SQL Injection test tool for database security. Its main purpose is to detect and exploit SQL Injection vulnerabilities. Following the detection of SQL Injection vulnerabilities, the users have available a plethora of options to choose their further exploration, including: 
* perform a DBMS fingerprint; 
* retrieve DBMS session user and database;
* enumerate users, password hashes, privileges, databases, etc.;
* run specific SQL statements;
* etc.

**#OWASP, #SQLInjectin, #PenetrationTesting**


### w3af: Web Application Attack and Audit Framework

**Presentation**: [w3af: Web Application Attack and Audit Framework](https://github.com/danielamariei/talks/tree/master/w3af)

The presentation introduce the w3af Web Application Attack and Audit Framework. The project helps reduce a site's overall exposure by helping project developers detect more than 200 application vulnerabilities.


<!--
**danielamariei/danielamariei** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
