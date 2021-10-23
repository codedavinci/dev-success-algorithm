# Developer Success Algorithm 

## "An algorithm that makes a developer succeed 99% of times" 

============================= <br />
*This section is mostly done by the Architect and Manager but it’s a good skill to have as a dev*

### Project Onboarding 

***(User === Client /Business)***

.   **1** - `Listen to new problem`<br />

.   .   **1.1** - `Repeat the problem to the user and validate if you understood it correctly`<br />

.   .   **1.2** - `Identify how many problems there are` <br />

.   .   .   **1.2.1** - `Are there more than one problem to solve` ?<br />

.   .   .   .   `Yes: Create a new Note, Repeat step 1.1`			<br />	 

.   .   .   .   `No: Ask questions until the user says “that’s it !”`<br />

.   .   .   .   .   **1.2.1.1** - `Have you gotten your “that’s it”` ? <br />

.   .   .   .   .   .   `No: Repeat from step 1.2.1`<br />

.   .   .   .   .   .	  `Yes: Move to step 2`<br />

.   **2** -  `Break it down`<br />

.   .   **2.1** - `Identify all the tasks`<br />

.   .   **2.2** - `Identify all the possibilities`<br />

.   .   **2.3** - `Document it all`<br />

.   .   **2.4** - `Create Initial tasks/stories ( Here we use Epics )` <br />

============================= 

### Meetings (Grooming,  Sprint Planning, and etc.) 

 ***(User === Team / Tech Lead / Product Manager)***
 
.   **3** - `Task Onboarding / What to get done (Devs - Analysis )`<br />

.   .   **3.1** - `Repeat the problem to the user and validate if you understood it correctly.`<br />

.   .   .   **3.1.1** - `Is there more than one problem to solve ?`<br />

.   .   .   .   `Yes: Create a new Task, Repeat from step 3.1`<br />

.   .   .   .   `No:  Ask questions until the user  says “that’s it !`”	<br />

.   .   .   .   .   **3.1.1.1** - `Have you gotten your “that’s it !” ?`<br />

.   .   .   .   .   .   `No: Repeat from step 3.1`<br />

.   .   .   .   .   .   `Yes: Move to step 4`<br />

.   **4** - `Adjust all tasks ( usually done in Sprint Planning )`<br />

============================= 

### Execution (Analysis)

***(User === Peers / Tech Lead /Product Manager)***

.   **5** - `Task Execution / How to get it done (Devs - Analysis )`<br />

.   .   **5.1** - `Identify all the micro tasks / create analogies`	

.	.	**5.2** - `Identify all the features`<br />

.   .   **5.3** - `Identify Entities`<br />

.   .   **5.4** - `Prototype your Entities / define your models`<br />

.   .   **5.5** - `Think about Naming Conventions`<br />

.   .   **5.6** - `Iterate with the User`<br />

.   .   .   **5.6.1** - `Have you gotten your “that’s it” ?`<br />

.   .   .   .   `No: Repeat from step 5.1`<br />

.   .   .   .   `Yes: Move to 5.7`<br />

.   .   **5.7** - `Analyze a design containing all features`<br />

.   .   **5.8** - `Design all features ( diagrams, flowcharts and etc.)`<br />

.   .	**5.9** - `Iterate with the User`	<br />

.   .   .   **5.8.1** - `Have you gotten your “that’s it” ?` <br />

.   .   .   .   `No: Repeat from step 5.6`<br />

.   .   .   .   `Yes: Move to step 6`<br />

.   **6** - `Move to Execution (Code) Phase`<br />

============================= 

### Execution (Code)

***(User === Team / Tech Lead)***

.   **7** - `Communicate your solution paths` <br />

.   .   **7.1** -  `Open a WIP (Work in progress) Pull Request` <br />

.   .   **7.2** -  `Create threads` <br />

.   .   **7.3** -  `Code snippets`<br />

.   .   **7.4** -  `Pair Program ( last resort )`<br />

.   .   **7.5** -  `Are you still unsure of your path ?`<br />

.   .   .   `Yes: Repeat from step 7.2`<br />

.   .   .   `No: Move confidently to step 8`<br />

.   **8** - `Implement your code` <br />

.   .   **8.1** - `Analyze each action individually.`<br />

.   .   **8.2** - `Create a list of all Actions / Function definitions`<br />

.   .   **8.3** - `Build all your Actions /Functions`<br />

.   .   .	**8.3.1** - `Is any of your Actions /Functions trying to do more than one thing ?`<br />

.   .   .   .	`Yes: Repeat from step 8.1`<br />

.   .   .   .	`No: Do it, Commit it, Push it!  and move to step 8.3.1.1`<br />

.   .   .   .   .	**8.3.1.1** - `Finished all Actions / Functions?`<br />

.   .   .   .   .   .	`No: Repeat from step 8.3!` <br />

.   .   .   .   .   .	`Yes: Move safely to step 9` <br />

.   **9** - `Move it to “Code Review”`

.   .   **9.1** - `Breakdown everything implemented to enable a better experience for reviewers.`<br />

.   .   **9.2** - `Give the context of the task`<br />

.   .   **9.3** - `Explain how your solved the problem`<br />

.   .   **9.4** - `Explain why you went in this direction`<br />

.   .  	**9.5** - `Respond all the comments`<br />

.   .   .   **9.4.1** - `Have you gotten your “that’s it” from the User ?` <br />

.   .   .   .   `No: Repeat from step 8.1!` <br />

.   .   .   .	`Yes: Move safely to step 10`<br />


============================= 

### QA/ Test

***(User === QA/Testers)***

.   **10** - `Solution sent to QA / Test`<br />

.   .   **10.1** - `Answer all questions` <br />

.   .   .   **10.1.1** - `Have you gotten your “that’s it” from Testers ?`<br />

.   .   .   .   `No: Repeat from step 8.1`<br />

.   .   .   .   `Yes: Finally, move to step 11`<br />

.   **11** - `Deploy / Ship it` <br />
