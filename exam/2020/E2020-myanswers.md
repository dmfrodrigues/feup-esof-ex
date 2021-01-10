### Exam 2019/20

#### Question 1

What was the first (recorded) software bug and how was it identified? Please justify your answer.
- a) On the 50s, using NATO's advanced bug identification systems
- b) On the 80s, using critical service analysis
- c) On the 40s, manually
- d) On the 90s, using automated testing.

**Answer:** c). The first recorded software bug was found by Grace Hopper in September 1945. It was a literal bug (a moth) that was attracted by the warmth of the internal components of the Harvard Mark II computer, causing a short-circuit that led the computer to malfunction. It is not a software bug in the strict sense, as the issue was actually on the hardware instead of the running software; however it is usually regarded as the first recorded "bug".

#### Question 2
Which one of the following is most adequate to have a software prototype (please justify your answer):
- a) A customer-driven app for ordering food;
- b) A business-to-business software for supporting a supply chain;
- c) A healthcare software to handle critical data;
- d) All of the above

**Answer:** d). All products are adequate to have a software prototype, as it is a fundamental step for requirements engineering. It allows the development team to better understand the requirements, as well as confirm, reject and add requirements. It consists of creating a user interface prototype that the client can explore, and as such it helps elicit new requirements in an intuitive way for the client so the final product matches the client's expectations.

#### Question 3
With RUP, the construction phase is when the actual software is most actively developed. Identify the disciplines that are most active during this phase and briefly explain why.
- a) All disciplines are equally active;
- b) The only active discipline is the implementation;
- c) Implementation and testing;
- d) Design, implementation and testing.

**Answer:** d). Implementation is obviously the most active discipline during construction phase, as this is when the bulk of the project is implemented. Design was already quite intense before construction, but some design challenges are only made clearer once the implementation reaches a certain degree of maturity and the development team is actually faced with having to implement it instead of trying to design it in advance. Testing goes hand-in-hand with implementation, as testing should either drive or validate the project implementation; it becomes more intense towards the end of the construction phase as there is an increased focus on proper feature testing instead of implementing new features.

#### Question 4
XP actively prevent software regressions by motivating a test first approach. Who should participate in this process? Justify your choice.
- a) The client should provide the development team with tests for his requirements;
- b) The client and the project manager should write tests before tackling new features;
- c) The development team, with input from the client, should write tests before tackling new features;
- d) The development team, with input from the project manager, should write tests before tackling new features;

**Answer:** c). The client's concern is the product, as he/she is not required to have technical expertise. The project manager is also not required to have technical expertise as he/she is only concerned with managing the project execution and not exactly execute it. The project manager does not have any input over the tests as he/she is not the one making the requirements. As such, it should be the development team to write tests, with input from the client to make sure the tests verify the client requirements are met.

#### Question 5
Missing project deadlines is possibly the most recurring failure in software development. How does Scrum try to address it? Justify your answer.
- a) Scrum will only ensure that a product increment exists in the end of each sprint, but not the quantity of features that are part of it. Traditional methodologies are more strict hence, more capable of meeting deadlines;
- b) The Scrum Master is responsible for ensuring that the team is efficient and delivers the software at the right time;
- c) Effort estimations and velocity can be used to forecast when the backlog will be complete;
- d) A well defined process will ensure development efficiency, which will guarantee the project deadline.

**Answer:** c). The backlog being complete is equivalent to having accomplished all tasks, should they be the work the team had to perform during a sprint or during the whole product development. It is an attempt to address missing deadlines as it gives a more specific idea on how much is left to be done, and as such the team can addapt their working rate to comply with deadlines. It does not completely address deadline missing, as the tasks allocated to each sprint added up across all available sprints might not add up to the total work that had to be done by the deadline due to poor deadline estimations or strict deadlines imposed by the client.

#### Question 6
Brainstorming is a common requirement elicitation technique in which (justify your answer):
- a) the ideas only come from the system end users
- b) all the ideas are welcome
- c) there is no facilitator
- d) 15 people is the limit of people in the room.

**Answer:** b). Everyone should contribute when brainstorming. The point of brainstorming is to elicit new requirements by first collecting a large number of ideas from the stakeholders (dev team and client) and only then discuss them based on their merit. More specifically, the client can add requirements and guide the brainstorming meeting to meet his/her expectations, and the development team can suggest features that often come together with some requirements in most projects. The dev team has a saying as some requirements almost always come together with others. There is a facilitator, called a moderator, which is usually a requirements engineer. There is no hard limit to the number of people, but up to 8 people is recomended to avoid the meeting going chaotic.


#### Question 7
Regarding use case modelling, include relationships aim to (justify your answer):
- a) Represent optional behavior
- b) Represent critical behavior
- c) Represent mandatory behavior
- d) Represent behavior imported from other system

**Answer:** c). An include relationship represents mandatory behavior because it means that, for a use case to work and be useful for the agents, it requires another use case to be implemented and work properly. Besides, a use case that is included by other use cases could otherwise be represented as part of each of the use cases it is included by, as include is only a strategy to avoid repeating common tasks, but which are still essential for accomplishing the use cases they are included by.

#### Question 8
Software Engineering has been a research subject for the past decades. Focusing on software architectures, engineers have learned much about how to build good software. What technique/approach is typically adopted to share such knowledge between engineers? Describe why is it a good technique/approach.
- a) Object Oriented Programming.
- b) Reusable Open Source libraries.
- c) Design Patterns.
- d) Sequence Diagrams.

**Answer:** Design patterns. Object-Oriented Programming is a common technique but it is so commonly used it is not exactly a thing software engineers learned to contribute to building good software, it is pretty much indispensable. Reusable Open Source libraries are used to share code publicly, not knowledge between engineers. Sequence diagrams are part of managing the development process and only represents the path taken to solve a certain instance of a large problem. Design patterns are code patterns that are commonly found in software development and can be mostly solved using well-established operations; these patterns help engineers develop better software as solutions for certain issues have been applied many times already. Besides, patterns help engineers understand each others' code as patterns usually take on names that reveal the roles of certain classes and functions in doing a particular action that solves the issue.

#### Question 9
The Project Management Body of Knowledge states that the project management processes are divided into process groups. How may process groups are there and what are their names and main objective:
- a) 6
- b) 12
- c) 5
- d) 3

**Answer:** c).

1. Initiating Process Group: where the new project or new project phase are launched
2. Planning Process Group: planning the extent and execution of the project
3. Executing Process Group: processes where the project is actually executed
4. Monitoring & Controlling Process Group: processes that track, monitor, report and control the project performance and progress
5. Closing Process Group: processes required to finalize and close a project/phase

#### Question 10
Reverse engineering (please justify your answer):
- a) Is a reengineering process activity
- b) Means converting code to a new language
- c) Is to clean-up and restructure system data
- d) Is to reorganise the program structure.

**Answer:** a). Reverse engineering consists of taking a code set and study it to try to understand what it does, how it is designed (find its architecture), and fundamentally understand it better. It usually consists of running the application and analyse what happens, what are the interfaces, that comes out when a certain input is given; or otherwise by reading the source code to understand what is happening so software can be reimplemented or better documented.
