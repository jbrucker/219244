---

### Week 11
* Quiz on using JUnit
* Authentication and intercepters in Play.  Intercepters let you easily and consistently secure all your non-public resources.  The Play tutorial section on [Adding Authentication](https://www.playframework.com/documentation/2.2.x/JavaGuide4) describes how.

### Week 10
* Quiz on Play Framework
* Demo EL2 work products.
* Create plan and start work on construction iteration 1 (CO1).

#### Week 10 Assignment
* Create iteration plan according to template and add it to your project repository.
* Your iteration goals should include (if you haven't already done these in previous iteration):
** Users are authenticated before they can access voting pages
** Users can vote and their votes are recorded
** Application permits both "voting" (choose one contestant) and "ranking" (rank each contestant according to criteria)
** There is an admin interface that shows who and logged in and who has voted
** Admin can specify the voting time period (start - end) and change it, so as to start/stop voting.
** System computes and displays results of voting.  While voting is open, only admin users can see results. After voting period has ended, everyone can see results.



### Roadmap for Next Four Weeks
We are starting Elaboration Iteration 1.  Your team will identify the main features in implement and select which to implement in EL1. To keep all teams on track, TAs and I will choose a common set of features we want all projects to implement.

By the end of EL1 you must have a running, deployable application.  You must also have good documentation, including refined, nearly complete set of requirements (as UC and Supplemental Requirements), and some design documentation, which you will bundle into a _Software Architecture Document_.  The SAD is for developers, so it isn't as rigorous as the SRS, but it should be accurate and complete.  Record important _design decisions_ in the SAD.  Your Web Frameworks review is a design decision.

During EL1, we'll study some useful technology.  I hope to cover Unit Testing, Logging, Persistence, and a few design patterns.  We will introduce and require teams to use _Issue Tracking_ using Github and Waffle.io, and Git _branches_ for development. 

---

### Week 5 Lab
1. Review and discussion of teams' **Domain Models**. I will choose a few teams to present, so be prepared.
  * You should be able to relate your Domain Model to your Use Cases and Mock-up.  They should be consistent.
2. (postponed) Introduction to Play! framework. 
3. Practice drawing System Sequence Diagrams.
4. Introduction to Design Patterns.
5. Overview of Elaboration Iteration 1 (EL1), its goals, and writing an Iteration Plan for EL1.
6. Intro to issue tracking for recording tasks and progress.

#### Week 5 Assignment
* Meet with team to choose goals, tasks, and milestone(s) for this iteration.
* Create Iteration Plan for EL1 using template. Put it on your Wiki and link to your project README file.
* Record backlog and milestones in Github issue tracker.
* Work on your tasks!

---

### Week 4 Lab
UML Sequence Diagram practice (reschedule from week3)<br>
Review of Requirements and Use Cases<br>
Domain Modeling

#### Week 4 Assignment
1. Revise and improve your Use Cases, Vision, and Mock-up.
2. Create a domain model.  You should have at least one domain class diagram and one or more sequence diagrams.  These may be sketches (don't have to be beautiful).
3. Add terms to your Glossary that explain important concept classes in domain model. For example, if you have a class named "Registrar" then explain what it is! 
4. Be prepared to explain your Domain Model in lab next week!  2-3 teams will be selected to present.

---

### Week 3 Lab
Quiz on git<br>
Meet the customer!

#### Week 3 Assignment
Each team should create a project on Github. On this site create:

1. _Vision Statement_ including Mock-up of the UI.  _Mock-up_ is not just some wishful sketch: it must show how the application will be used (screen-by-screen) and how it fulfills the customer's primary use case requirements.
2. _Glossary_ file containing terms you learned from the customer, plus any significant terms you learn from your own research.
3. _Informal Use Cases_ short descriptions of customer's requirements.  Number them UC1, UC2, etc.
4. _Supplementary Requirements_ document containing non-functional requirements, or any requirements not expressed as Use Cases.
5 _Comparison of Java Web Frameworks_: Select some frameworks, use them to create a project, and write a summary of your findings.  See: http://goo.gl/9erztx  
__Due__: Tuesday, 10 Feb, on Github.

---

### Week 2 Lab
UML Practice  
Git practice (game)

#### Week 2 Assignment
Form a team of 3-5 people for the class term project, which will begin next week.

---

### Week 1
A "mini-project" as overview of what you will do during your own software project for this course.

For today you will work in teams of 5.  You may choose a _different_ team later for the course project, so don't spend a lot of time selecting a team now.

The activities to perform are:

* Find out [[Requirements|what the customer wants]].
* Jointly develop a [[Vision Statement|Vision]] of the solution. Ask questions, draw mock-ups of what the solution will look like, investigate existing or similar projects.
* Write a [[Vision Statement]] (usually 2 pages) to guide your work.  The Vision helps keep your team on track and avoid feature creep.
* Discover requirements. In this case we will only write "user stories" or "informal use cases" that describe major features. (There are many other kinds of requirements.)
* Plan the first iteration.  What can you implement '''today'''?
* Design software for the first iteration. -- Use the whiteboards.
* Quickly write tasks you need to do.  Don't try to be complete -- you'll discover tasks as you start coding.
* Do the tasks (write the software).  Test your work!  Update your tasks, too.
* Integrate & test the result.
* Demo and review it.

#### Work Products

* Create a Github project for your team.
* In the project, write a README.md listing your team members.
* Write a short _Vision Statement_.  Vision should include:
  * Background - what is the context? what is the problem?
  * Who are the customer and stakeholders?  How does the problem affect them?
  * Why is this project worth undertaking?  (Aside from the fact that its required for this course.)
  * Your VISION of the solution.  And make it visual.  
  * How is your solution different from existing products? 
  * Write the Vision in Github or Google Docs. Put a '''link''' to it in your README.md.
  * If you use Google Docs be sure to ''share'' it.
