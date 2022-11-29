# PragmaticProgrammer
Chapter 1 -------------------------------
Another key to their success is that they take responsibility for everything they
do. Being responsible, Pragmatic Programmers won't sit idly by and watch their
projects fall apart through neglect.
One of the benefits of understanding the context in which you work is that it becomes easier to know just how good your software has to be. Sometimes near-perfection is the only option, but often there are trade-offs involved

Finally, none of us works in a vacuum. We all spend a large amount of time interacting with others. Communicate! lists ways we can do this better.
1.1----

One of the cornerstones of the pragmatic philosophy is the idea of taking responsibility 
for yourself and your actions in terms of your career advancement, your project, and your 
day-to-day work. A Pragmatic Programmer takes charge of his or her own career, and isn't 
afraid to admit ignorance or error.

You have the right not to take on a responsibility for an impossible situation, or one in 
which the risks are too great. You'll have to make the call based on your own ethics and 
judgment.

Before you approach anyone to tell them why you cant do, ask yourself questions.
Instead of excuses, provide options. Dont say it cant be done, explain what can be done 
to salvage the situation.
There are many factors that can contribute to software rot. The most important one seems 
to be the psychology, or culture, at work on a project

Broken Window theory : 
This story is important to me because it gives the main idea of this theory;

The "Broken Window Theory" has inspired police departments in New York and other major 
cities to crack down on the small stuff in order to keep out the big stuff. It works: 
keeping on top of broken windows, graffiti, and other small infractions has reduced the 
serious crime level.

Don't leave "broken windows" (bad designs, wrong decisions, or poor code) unrepaired. Fix 
each one as soon as it is discovered.  If there is insufficient time to fix it properly, 
then board it up. 
Putting out Fires :
If you find yourself working on a project with quite a few broken windows, it's all too 
easy to slip into the mindset of "All the rest of this code is crap, I'll just follow 
suit." It doesn't matter if the project has been fine up to this point. In the original 
experiment leading to the "Broken Window Theory," an abandoned car sat for a week 
untouched. But once a single window was broken, the car was stripped and turned upside 
down within hours.
----Be a Catalyst for Change
It's often the accumulation of small things that breaks morale and teams.
----Remember the Big Picture
It is unprofessional to ignore these users' requirements simply to add new features to the program, or to polsih up the ode just one more time. Also it is unprofessional to promise impossible time scales and the cut basic engineering corners to meet a deadline.
So that, the scope and quailty of the system you produce should be specified as part ıf that systems requirements.
----Make Quality a Requirements Issue
We need to give our users something to play with early, their feedback will often lead us to 
better eventual solution. In today's world, great software of today is often preferable to 
perfect software tomorrow.
----Know when to stop
all the hard work is ruined if we don't know when to stop. If we add layer upon layer, detail 
over detail, the painting becomes lost in the paint.
Building Porfolio Guidelines ;
Invest Regularly,
Diversify,
Manage Risk,
Buy low, Sell high
Review and rebalance
----Oppurtunities for learning : 
If you dont know the answer, find a guru in office. If you do not have guru in your office
then find it on internet.
----Critical Thinking:
The last important point is to think critically about what you read and hear. You need to
ensure that the knowledge in your portfolio is accurate and unswayed by either vendor or
media hype.
Never underestimate the power of commercialism.
Always need to critically analyze what you read and hear.  
----Choose your Moment : 
Ask yourself "Is this a good time to talk about"

----Choose A Style :
When it comes to written documents, some like to receive large bound reports, while
others expect a simple memo or e-mail. If in doubt, ask.
Communication is the key for learn people style.
----Make It Look Good
It is important to forward your ideas to audience properly also good loking.
Also it is important to create content with good style.
----Involve Your Auidience: 

We often find that the documents we produce end up being less important than the process
we go through to produce them. If possible, involve your readers with early drafts of
your document. Get their feedback.

----Be A Listener: 
If you do not listen to people, they won't listen to you either.
----Get Back To People:
It is important to get back to people's email or message even if you say "I will get back 
to you later". Its key of being polite person.
!!It's both what you say and the way you say it.

Summary of Chapter 1: 
✅Know what you want to say.
✅Know your audience.
✅Choose your moment.
✅Choose a style.
✅Make it look good.
✅Involve your audience.
✅Be a listener.
✅Get back to people.

Chapter 2 : PRAGMATIC APPROACH 
DRY (Don't Repeat Yourself)
The alternative is to have the same thing expressed in two or more places. If you change 
one, you have to remember to change the others, or, like the alien computers, your 
program will be brought to its knees by a contradiction. It isn't a question of whether 
you'll remember: it's a question of when you'll forget.

How Does Duplication Arise ? 
-Imposed duplication
-Inadvertent duplication
-Impatient duplication.
-Interdeveloper duplication.

----Imposed duplication:
Sometimes, duplication seems to be forced on us. Project standards may require
documents that contain duplicated information, or documents that duplicate information in 
the code.
Some techniques that our life eaiser; 
-Multiple representations of information:
With a bit of ingenuity you can normally remove the need for duplication. Often the 
answer is to write a simple filter or code generator.
-Documentation in code
--Good code always has lots of comments is not true in all case. On the other hand,
bad code requires lots of comments.
The DRY principle tells us to keep the low-level knowledge in the code, where it 
belongs, and reserve the comments for other, high-level explanations.
-Language issues.
Use the header files to document interface issues, and the implementation files to 
document the nitty-gritty details that users of your code don't need to know.

----Inadvertent Duplication

Sometimes, duplication comes about as the result of mistakes in the design.
----Impatient Duplication
If you feel this temptation, remember the hackneyed aphorism "shortcuts make for 
long delays." You may well save some seconds now, but at the potential loss of hours 
later.Impatient duplication is an easy form to detect and handle, but it takes 
discipline and a willingness to spend time up front to save pain later.
----Interdeveloper Duplication
We feel that the best way to deal with this is to encourage active and frequent 
communication between developers.
----Impatient Duplication
Impatient duplication is an easy form to detect and handle, but it takes discipline and a willingness to spend time up front to save pain later.
----Interdeveloper Duplication

We feel that the best way to deal with this is to encourage active and frequent communication between developers. Set up forums to discuss common problems. . This provides a nonintrusive way of communicating—even across multiple sites—while retaining a permanent history of everything said.) Appoint a team member as the project librarian, whose job is to facilitate the exchange of knowledge.
----Orthogonality
In computing, the term has come to signify a kind of independence or decoupling. Two or more things are orthogonal if changes in one do not affect any of the others.
When components of any system are highly interdependent, there is no such thing as a local fix.
When components are isolated from one another, you know that you can change one without having to worry about the rest.
You get two major benefits if you write orthogonal systems: increased productivity and reduced risk.: Gain Productivty - Reduce Risk.
----Reversebilty:
suppose the project begins as a client-server model, but then, late in the game, marketing decides that servers are too expensive for some clients, and they want a stand-alone version. How hard would that be for you? Since it's just a deployment issue, it shouldn't take more than a few days. If it would take longer, then you haven't thought about reversibility. The other direction is even more interesting. What if the stand-alone product you are making needs to be deployed in a client-server or n-tier fashion? That shouldn't be hard either

Chapter 3: 

----Drawbacks
There are two major drawbacks to using plain text: (1) It may take more space to store than a compressed binary format, and (2) it may be computationally more expensive to interpret and process a plain text file.
Depending on your application, either or both of these situations may be unacceptable—for example, when storing satellite telemetry data, or as the internal format of a relational database.
The Power of Text
----Insurance against obsolescence: you will always have a chance to be able to use text.
----Leverage: Virtually every tool in the computing can operate on plain text.
Easier testing
----Shell Games:
Use the Power of Command Shells
----Power Editing:
-Use asingle Editor well.
----Editor Features: 
Configurable
Extensible
Programmable
----Source Code Control
Always Use Source Code Control
----A Debugging Mindset
Don't waste a single neuron on the train of thought that begins "but that can't happen" because
quite clearly it can, and has. Try to discover the root cause of a problem, not just this
particular appearance of it.
Before you start to look at the bug, make sure that you are working on code that compiled cleanly—without warnings. We routinely set compiler warning levels as high as possible. It doesn't make sense to waste time trying to find a problem that the compiler could find for you! We need to concentrate on the harder problems at hand.

When trying to solve any problem, you need to gather all the relevant data. Unfortunately, bug reporting isn't an exact science. It's easy to be misled by coincidences, and you can't afford to waste time debugging coincidences. You first need to be accurate in your observations.
You may need to interview the user who reported the bug in order to gather more data than you were initially given.
Artifical test.
Bug Reproduction
The best way to start fixing a bug is to make it reproducible.
The second best way is to make it reproducible with a single command.
Visualize Your Data
Use the tools that the debugger offers you. Pen and paper can also help.
Tracing
Know what happens before and after.
Rubber Ducking
Explain the bug to someone else.
Process of Elimination
It is possible that a bug exists in the OS, the compiler, or a third-party product—but this should not be your first thought.
 "select" Isn't Broken
The Element of Surprise
Don't Assume It—Prove It
Debugging Checklist
Is the problem being reported a direct result of the underlying bug, or merely asymptom?
Is the bug really in the compiler? Is it in the OS? Or is it in your code?
If you explained this problem in detail to a coworker, what would you say?
If the suspect code passes its unit tests, are the tests complete enough? What happens if you
run the unit test with this data?
Do the conditions that caused this bug exist anywhere else in the system?
----Text Manipulation
Tip 28: Learn a Text Manipulation Language

----Code Generators
Tip 29: Write Code That Writes Code Two main types of code generators:
Passive code generators are run once to produce a result. They are basically parameterized 
templates, generating a given output from a set of inputs.
Active code generators are used each time their results are required. Take a single 
representation of some piece of knowledge and convert it into all the forms your application 
needs.
Code Generators Needn't Be Complex
Keep the input format simple, and the code generator becomes simple.
----Chapter 4:
 
You can't write Perfect Software
No one in the brief history of computing has ever written a piece of perfect software.
Pragmatic Programmers don't trust themselves, either.
Design by Contract
A correct program is one that does no more and no less than it claims to do.

-Preconditions
-Postconditions
-Invariants
 Design with Contracts
Write "lazy" code: be strict in what you will accept before you begin, and promise as little as possible in return.
Implementing DBC
Simply enumerating at design time:
what the input domain range is
what the boundary conditions are
what the routine promises to deliver (and what it doesn't)
Assertions
You can use assertions to apply DBC in some range. (Assertions are not propagated in subclasses)
DBC enforce Crashing Early
Invariants
Loop Invariants: Is true before and during the loop therefore also when the loop finishes
Semantic Invariants: ie the error should be on the side of not processing a transaction rather
than processing a duplicate transaction.
Dead Programs Tell No Lies
All errors give you information. Pragmatic Programmers tell themselves that if there is an
error, something very, very bad has happened.

Tip 32: Crash Early
A dead program normally does a lot less damage than a crippled one.
When your code discovers that something that was supposed to be impossible just happened, your
program is no longer viable.
Assertive Programming
If It Can't Happen, Use Assertions to Ensure That It Won't
Assertions are also useful checks on an algorithm's operation.
Don't use assertions in place of real error handling.
Leave Assertions Turned On, unless you have critical performance issues.
When to Use Exceptions
Use Exceptions for Exceptional Problems
What Is Exceptional?
The program must run if all the exception handlers are removed If your code tries to open a 
file for reading and that file does not exist, should an exception be raised
Yes: If the file should have been there
No: If you have no idea whether the file should exist or not
How to Balance Resources
When managing resources: memory, transactions, threads, flies, timers—all kinds of things with 
limited availability, we have to close, finish, delete, deallocate them when we are done.
Finish What You Start
Nest Allocations
-Deallocate resources in the opposite order to that in which you allocate them
-When allocating the same set of resources in different places in your code, always allocate them in the same order (prevent deadlocks)
Chapter 5:
----Don't Write Dodo-Code
Without metadata, your code is not as adaptable or flexible as it could be. Is this a bad
thing? Well, out here in the real world, species that don't adapt die.
The dodo didn't adapt to the presence of humans and their livestock on the island of Mauritius,
and quickly became extinct. It was the first documented extinction of a species at the hand of
man.
-Design Using Services
-Always Design for Concurrency
-Separate Views from Models
-Use Blackboards to Coordinate Workflow
Chapter 6: 
-Don't Program by Coincidence
How to Program Deliberately: 
-Always be aware of what you are doing.
-Don't code blindfolded.
-Proceed from a plan.
-Rely only on reliable things.
-Document your assumptions. Design by Contract.
-Don't just test your code, but test your assumptions as well. Don't guess Assertive Programming
-Prioritize your effort.
-Don't be a slave to history. Don't let existing code dictate future code. Refactoring
Common Sense Estimation:

-Simple loops
-Nested loops
-Binary chop
-Divide and conquer
Algorithms that partition their input, work on the two halves independently, and then combine
the result.
Combinatoric
-Estimate the Order of Your Algorithms
-Test your estimates
Refactoring: 
Code may need to change or edit.
When do you need to refactor ? 
-Duplication
-nonortahangonal design
-outdated knowledge
-performance
-How Do You Refactor: 
Don't try to refactor and add functionality at the same time.
Make sure you have good tests before you begin refactoring.
Take short, deliberate steps.
Unit Testing:
Testing done on each module, in isolation, to verify its behavior. A software unit test is code
that exercises a module
Writing Unit Test:
The unit tests for a module shouldn't be shoved in some far-away corner of the source tree.
They need to be conveniently located. For small projects, you can embed the unit test for 
module in the module itself. For larger projects, we suggest moving each test into a
subdirectory. Either way, remember that if it isn't easy to find, it won't be used.
1. Examples of how to use all the functionality of your module
2. A means to build regression tests to validate any future changes to the code
Using Test Harnesses: 
Because we usually write a lot of test code, and do a lot of testing, we'll make life easier on
ourselves and develop a standard testing harness for the project. The main shown in the
previous section is a very simple test harness, but usually we'll need more functionality than 
that.
Regardless of the technology you decide to use, test harnesses should include the following capabilities:
-A standard way to specify setup and cleanup
-A method for selecting individual tests or all available tests
-A means of analyzing output for expected (or unexpected) results
-A standardized form of failure reporting

Chapter 7:
Digging for Requirements
Policy may end up as metadata in the application.
Gathering requirements in this way naturally leads you to a system that is well factored to
support metadata.

-Work with a User to Think Like a User
Documenting Requirements
Use "use cases"
Overspecifying
Requirements are not architecture. Requirements are not design, nor are they the user
interface. Requirements are need.

Seeing Further
-Abstractions Live Longer than Details

Maintain a Glossary
It's very hard to succeed on a project where the users and developers refer to the same thing
by different names or, even worse, refer to different things by the same name.
-Use a Project Glossary

Get the Word Out
Publishing project documents to internal Web sites for easy access by all participants.

Solving Impossible Puzzles
Degrees of Freedom
The key to solving puzzles is both to recognize the constraints placed on you and to recognize
the degrees of freedom you do have, for in those you'll find your solution.
Chapter 8: Pragmatic Projects:
Pragmatic Teams:
-No Broken Windows:
Teams as a whole should not tolerate broken windows—those small imperfections that no one fixes. The team must take responsibility for the quality of the product, supporting developers who understand the no broken windows philosophy we describe in Software Entropy, and encouraging those who haven't yet discovered it.
-Boiled Frogs:
Make sure everyone actively monitors the environment for changes. Maybe appoint a chief water
tester.
-Communicate:
It's obvious that developers in a team must talk to each other.
Great project teams have a distinct personality. People look forward to meetings with them, because they know that they'll see a well-prepared performance that makes everyone feel good. 
-Dont Repeat Yourself:
Some teams appoint a member as the project librarian, responsible for coordinating
documentation and code repositories. Other team members can use this person as the first port
of call when they're looking for something. A good librarian will also be able to spot
impending duplication by reading the material that they're handling.
----Orthogonality:
It is a mistake to think that the activities of a project—analysis, design, coding, and
testing—can happen in isolation. They can't. These are different views of the same problem, and
artificially separating them can cause a boatload of trouble.
----Automation:
A great way to ensure both consistency and accuracy is to automate everything the team does. 
Know When to Stop Adding Paint:
 Give them just enough structure to support them and to ensure that the project delivers against its requirements. 
 -Ruthless testing
Pragmatic Programmers are driven to find our bugs now, so we don't have to endure the shame of others finding our bugs later.
-Test Early. Test Often. Test Automatically.
Tests that run with every build are the most effective.
The earlier a bug is found, the cheaper it is to remedy. "Code a little, test a little".

-Coding Ain't Done til All the Tests Run
3 Main aspects:
-What to Test
Unit testing: code that exercises a module.
Integration testing: the major subsystems that make up the project work and play well with each other.
Validation and verification: test if you are delivering what users needs.
Resource exhaustion, errors, and recovery: discover how it will behave under real-world conditions. (Memory, Disk, CPU, Screen...)
Performance testing: meets the performance requirements under real-world conditions.
Usability testing: performed with real users, under real environmental conditions.
-How to Test
Regression testing: compares the output of the current test with previous (or known) values.
Test data: there are only two kinds of data: real-world data and synthetic data.
Exercising GUI systems: requires specialized testing tools, based on a simple even
capture/playback model.
Use Saboteurs to Test Your Testing
Testing thoroughly:
Test State Coverage, Not Code Coverage
-When to Test
As soon as any production code exists, it needs to be tested. Most testing should be done
automatically.
-It's All Writing
If there's a discrepancy, the code is what matters—for better or worse.

Comments in Code
In general, comments should discuss why something is done, its purpose and its goal.

Remember that you (and others after you) will be reading the code many hundreds of times, but
only writing it a few times.
Even worse than meaningless names are misleading names.
One of the most important pieces of information that should appear in the source file is the author's name—not necessarily who edited the file last, but the owner.

Executable Documents
Create documents that create schemas. The only way to change the schema is to change the document.
Technical Writers
We want the writers to embrace the same basic principles that a Pragmatic Programmer does—especially honoring the DRY principle, orthogonality, the model-view concept, and the use of automation and scripting.
-Great Expectations
The success of a project is measured by how well it meets the expectations of its users.
Gently Exceed Your Users' Expectations

Communicating Expectations
Users initially come to you with some vision of what they want. You cannot just ignore it.
Everyone should understand what's expected and how it will be built.





