# Developer Success Algorithm

## "An algorithm that makes a developer succeed 99% of times"

=============================
_This section is mostly done by an Architect and Manager but it’s a good skill to have as a dev_

### Project Onboarding

**(User === Client /Business)**

. 1 - New Problem What to
. . 1.1 - Repeat the problem to the user and validate if you even understood
. . 1.2 - Identify how many problems there are
. . . 1.2.1 - Is there more than one problem to solve ?
. . . . Yes: Create a new Note, Repeat step 1.1
. . . . No: Ask questions until the user says “that’s it !”
. . . . . 1.2.1.1 - Have you gotten your “that’s it” ?
. . . . . . No: Repeat from 1.2.1.1”
. . . . . . Yes: Move to step 2
. 2 - Break it down
. . 2.1 - Identify all the tasks
. . 2.2 - Identify all the possibilities
. . 2.3 - Document it all
. . 2.4 - Create Initial tasks/stories ( Here we use Epics )

=============================

### Meetings (Grooming, Sprint Planning, and etc.)

**(User === Team / Tech Lead / Product Manager)**
. 3 - Task Onboarding / What to get it done (Devs - Analysis )
. . 3.1 - Repeat the problem to the user and validate if you understood it correctly.
. . . 3.1.1 - Is there more than one problem to solve ?
. . . . Yes: Create a new Task, Repeat from step 3.1
. . . . No: Ask questions until the user says “that’s it !”
. . . . . 3.1.1.1 - Have you gotten your “that’s it !” ?
. . . . . . No: Repeat from step 3.1
. . . . . . Yes: Move to step 4
. 4 - Adjust all tasks ( usually done in Sprint Planning )
=============================

### Execution (Analysis)

**(User === Peers / Tech Lead /Product Manager)**
. 5 - Task Execution / How to get it done (Devs - Analysis )
. . 5.1 - Identify all the micro tasks / create analogies
. . 5.2 - Identify all the features
. . 5.3 - Identify Entities
. . 5.4 - Prototype your Entities / Model Definitions
. . 5.5 - Create Naming Conventions
. . 5.6 - Iterate with the User
. . . 5.6.1 - Have you gotten your “that’s it” ?
. . . . No: Repeat from step 5.1
. . . . Yes: Move to 5.6
. . 5.7 - Analyze a design containing all features
. . 5.8 - Design all features ( diagrams, flowcharts and etc.)
. . 5.9 - Iterate with the User
. . . 5.8.1 - Have you gotten your “that’s it” ?
. . . . No: Repeat from step 5.6
. . . . Yes: Move to step 6
. 6 - Move to Execution (Code) Phase
=============================

### Execution (Code)

**(User === Team / Tech Lead)**
. 7 - Communicate your solution paths
. . 7.1 - Open a WIP (Work in progress) Pull Request
. . 7.2 - Create threads
. . 7.3 - Code snippets
. . 7.4 - Pair Program ( last resort )
. . 7.5 - Are you still unsure of your path ?
. . . Yes: Repeat from step 7.2
. . . No: Move confidently to step 8
. 8 - Implement your code:
. . 8.1 - Analyze each action individually.
. . 8.2 - Create a list of all Actions / Function definitions
. . 8.3 - Build all your Actions /Functions
. . 8.3.1 - Is any of your Actions /Functions trying to do more than one thing ?
. . . Yes: Repeat from step 8.1
. . . No: Do it, Commit it, Push it! and move to step 8.3.1.1
. . . . 8.3.1.1 - Finished all Actions / Functions?
. . . . . No: Repeat from step 8.3!
. . . . . Yes: Move safely to step 9
. 9 - Move it to “Code Review”
. . 9.1 - Breakdown everything implemented to enable a better experience for reviewers.
. . 9.2 - Give the context of the task
. . 9.3 - Explain how your solved the problem
. . 9.4 - Explain why you went in this direction
. . 9.5 - Respond all the comments
. . . 9.4.1 - Have you gotten your “that’s it” from the User ?
. . . . No: Repeat from step 8.1!
. . . . Yes: Move safely to step 10
=============================

### QA/ Test

**(User === QA/Testers)**
. 10 - Solution sent to QA / Test
. . 10.1 - Answer all questions
. . . 10.1.1 - Have you gotten your “that’s it” from Testers ?
. . . . No: Repeat from step 8.1
. . . . Yes: Finally, move to step 11
. 11 - Deploy / Ship it
