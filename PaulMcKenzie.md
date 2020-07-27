# Paul McKenzie 

> An experienced Java and Scala developer and team lead. 

 
## April 2009 – Present, Brick Kiln Software

I provide professional services to clients through my limited company *Brick Kiln Software*. 

## October 2019 - Present, Deutsche Bank
_Senior Engineer -- Release and Deployment Automation_

I work in the Release Automation and Deployment team. We have developed an example deployment pipeline using Kubernetes, Jenkins, Openshift, Helm and Jib. We use this to help development teams move their applications to a CI/CD pipeline through workshops, chat-rooms and other materials. Along with supporting this, my role has been to develop a series of integration points with the Service Now SDLC system. This is so that we can get closer to *Ideas to production, safely in a day*, which is the goal of the department. This development work has been Java 8. I am only at the beginning of my exploration of Kubernetes and the cloud-native ecosystem. I have also been active in a new group called the Voice of the Engineer. This has been formed explicitly to provide an engineering perspective on bank-wide issues. 

 
## November 2015 – May 2019, Barclays Wealth

My role was developer/tech-lead, working in a cross-functional agile team. We were responsible for a web application to allow small businesses to open a bank account. We developed an internet-facing site to present a questionnaire to new customers. We also had a small suite of services to integrate with legacy back-end processes. Our software was written in Scala, using the Lift framework and libraries such as Scalaz, Argonaut and HTTP4S. Later work involved extending the integration with Barclays back office functions, so so that we could get closer to straight through processing of account applications. The team won **Best Agile Team** award 2016 across all Barclays, and was commended in 2018. 

We developed the application using Pair Programming, often remotely, which I found to be very effective. We adopted a Test Driven Development approach. I also worked on adding Selenium testing to our web front-end, which proved helpful. I introduced into the team Behaviour Driven Development style testing, using Cucumber, and this was very popular with the Business Analysts. They could see the effect of complex validation rules. 

As the team personnel changed, my role changed to tech-lead. I had always tried to be aware of the bigger-picture of the project, but the role was later formalised. My approach included encouraging the team to explore the long term evolution of the architecture, challenging developers to focus on the quality of their code and facilitating planning and estimation meetings. I  also took an active part in bringing new developers into the team and making sure they were well integrated. A large part of the role was  working with other teams on systems integration tasks.

## May 2012 – October 2015, Bank of America Merrill Lynch 

I worked as a developer on the programme to create the strategic platform for Securities Operations. 
I was part of a highly agile feature team developing an inventory management application. 
The application was written in Scala and we adopted an event–sourced, CQRS style architecture. 
My responsibilities included developing in Scala and Python, "quality control" reviews for my team and other teams and contributing to the analysis and design process with our product owners and other stake–holders. 
The team adopted a Kanban approach and was very focused on test-driven and behaviour–driven development. 
I was also involved in maintaining the code–quality through "clean–code" practices. 

Our approach to making sure we were delivering the feature the Product Owner wanted was to take worked-examples in, for example, Excel and 
turning these into features using the Given-Then-When syntax, and these became executable tests using Cucumber. 
(Specification By Example, 
Gherkin, BDD) 

For a short while I was seconded to the Control Monitor project, a very successful two-month experiment in collating all settlement breaks into one easy to use and attractive gui. 
Working with senior Operations management we used a Kanban process to quickly move through various designs and adding features as the need for them became apparent.
 
## April 2009 – February 2012, HSBC 

##### MTN Repository 
The MTN Repository is a golden source repository for HSBC–issued Medium Term Note trade data, with querying, reporting and reconciliation capabilities. I was 
involved in the overall design of the system and I implemented of one of the main feeds into the system. This involved designing Spring Integration messaging 
architecture, XPath data extraction and error handling. I also designed and implemented the trade search web front–end, I implemented the spread sheet upload 
for the Product Control department. I also lead the implementation of website look and feel. I suggested, and the team adopted, the use of JBehave to implement 
executable acceptance tests that successfully enabled us to run a full regression suite as part of our automated build. 

##### TradeCache
My first assignment at HSBC was on a system called TradeCache, which is a proprietary XML trade document repository. 
The first project was to create a new feed from a Calypso system using Spring Integration. Largely working on my own, I designed, wrote and implemented a JMS consumer/transformation application to pull trade and product messages from a WebSphere MQ queue and populate our TradeCache system. I also implemented a daily and weekly reconciliation process. Messages were split and processed concurrently (multi-threaded) using Spring Integration/Executors. Unit test coverage >90%. 

The second main project was similar, but this time from a Sophis system. Replacing a slow and failure–prone polling–based feed, the new consumer uses Spring Integration again to consume from an MQ queue. I designed this application to use Java Service Loader to allow other team’s code to be executed via a plugin against the incoming messages. I designed and implemented almost the entire system and there is >90% unit test coverage, as well as integration testing using JBehave and ActiveMQ. In order to automate testing I also implemented a custom Maven plugin to start/stop/purge TradeCache. 

## November 2006 – January 2009, Barclays Global Investors 
_Senior Design and Development Engineer_ 

I worked in a small agile team on a Fixed Income Portfolio Management system. The system was designed to take model–driven recommendations and turn them into order lists for traders. The latest phase was to add order list creation for Bond Futures using models and current positions. My role was senior designer and developer, responsible for the architectural design and implementation of key components. I developed a close working relationship with the portfolio managers. The team adopted a broadly XP approach, using test driven development, short iterations and continuous integration. We used a proprietary XML document store and I was heavily involved with the design of the appropriate schemas using XML/XSD/UML. I was also heavily involved in the work flow design and this was implemented using an event driven architecture largely using asynchronous JMS messaging. 
The system was implemented as a series of server side components using Spring MVC for simple “plain old xml” services hosted in a Jetty container using JDBC, XmlBeans and Spring. 
Non–project work included the mentoring of two junior team members. I was also on the corporate Web Services Governance committee, which involved setting policies around project inception and assurance of quality of service. 

## August 2004 – November 2006, BNP Paribas 
_Senior Analyst Programmer_ 

Senior analyst–programmer working on a bank–wide Market Risk system. We were a fully XP team, working to a three week iteration cycle. Mostly project–based work migrating legacy applications to Java and C# system. Project lead on first phase of adoption of enterprise service bus technology (Mule) designing event driven application to track dynamic dependency fulfilment. Appointed as java technical lead for the team, I was responsible for code quality, setting up the continuous integration and encouraging the adoption of test–driven development. Primarily developing middle–tier Java, using the Spring framework, running inside a Tomcat server. 

___

2020.07.08
