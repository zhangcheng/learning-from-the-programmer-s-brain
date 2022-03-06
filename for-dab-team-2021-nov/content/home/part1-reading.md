---
weight: 30
markup: "html"
---
{{< slide bg-color="electric" >}}

## Part 1 - reading code

{{< ul  >}}
{{< li "fragment" >}}Usually we programmer prefer writing code than reading{{< /li >}}
{{< li "fragment" >}}Code reading is not taught or practiced often{{< /li >}}
{{< li "fragment" >}}getting to know code is confusing and often hard work{{< /li >}}
{{< /ul >}}

------

## Three Kinds of Confusion

![cognition context](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH01_F02_Hermans2.png)

* Lack of knowledge (Issue in *LTM*)
* Lack of information (Issue in *STM*)
* Lack of processing power (Issue in *working memory*)

------

#### Lack of knowledge (Issue in LTM)

{{< img src="/images/01 APL.png" >}}

{{< div "fragment" >}}
Knowledge is facts one remember for a long periods of time, such as syntax, algorithm, shortcut, etc.
{{< /div >}}

------

#### Lack of information (Issue in STM)

{{< img src="/images/02 Java.png" >}}

{{< div "fragment" >}}
Information is facts at hand for a brief period of time
{{< /div >}}

------

#### Lack of processing power (Issue in working memory)

{{< img src="/images/03 BASIC.png" >}}

{{< div "fragment" >}}
WM (working memory) is like processor (of brain)
{{< /div >}}

------

### Three little practices

------

{{< img src="/images/04 APL.png" >}}

------

{{< img src="/images/05 Java.png" >}}

------

{{< img src="/images/06 BASIC.png" >}}

------

5 seconds to remember as much as you could (1/3)

{{< div "fragment" >}}
{{< img src="https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH02_F03_UN01_Hermans2.png" height="150" >}}
{{< /div >}}

------

5 seconds to remember as much as you could (2/3)

{{< div "fragment" >}}
{{< img src="https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH02_F03_UN02_Hermans2.png" height="150" >}}
{{< /div >}}

------

5 seconds to remember as much as you could (3/3)

{{< div "fragment" >}}
{{< img src="https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH02_F03_UN03_Hermans2.png" height="150" >}}
{{< /div >}}

------

### If ask you to remember and reproduce this

{{< img src="/images/05 Java.png" >}}

------

### Your brain will be

![brain in code reproduction](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH02_F01_Hermans2.png)

{{< div "fragment" >}}
- STM is limited on both brief storage time and capacity, so need help from LTM
- Chunks, *chunking*, by Dutch mathematician Adrian de Groot
- Iconic memory -> "code at a glance" exercise
{{< /div >}}

------

### Speed up code reading

- Chunkable code
    - Design pattern
    - Comment
    - Beacon
        - Simple and compound
        - Smaller chunk, such as naming
    - Applied "*deliberate practice*" here

- Time spent: understanding code vs. writing code == 6 to 4

------

### How to learn programming syntax quickly

Remembering syntax helps both chunking, and to reduce interruption and possible distraction from looking it up.

{{< div "fragment" >}}
![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH03_F01_Hermans2.png)

Good old flashcard
{{< /div >}}

------

### The forgetting curve

![The forgetting curve](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH03_F02_Hermans2.png)

{{< div "fragment" >}}
- Hermann Ebbinghaus, German philosopher and psychologist, in 1870s
- Spaced repetition
	- more spaced-out intervals, like once a month
{{< /div >}}

------

### Schemata

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH03_F03_Hermans2.png)

- Brain organizes memories as network, instead of hierarchical tree
- Thoughts and its relationship in mind == schemas, or *schemata*

------

### LTM Practices

- 2 different strengths of LTM
	- Storage strength - can only increase over time (never really forget)
	- Retrieval strength - decays over time (years)

- 2 deliberate practices
	- retrieval practice (actively trying to remember something)
		- like index building in DB
	- elaboration (actively connecting new knowledge to existing memories)
		- like FK traversal in DB

------

### How to read complex code

![cognition context](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH01_F02_Hermans2.png)

- Working memory is STM applied to a problem
    - so same capacity limitation applied as well (2 to 6)
- WM's capacity is called "*cognitive load*"

------

- Intrinsic load ![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH04_F03_Hermans2.png)
    - How complex the problem is in itself.

- Extraneous load ![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH04_F04_Hermans2.png)
    - What outside distractions add to the problem.

- Germane load
    - Cognitive load created by having to store your thought to LTM
        - (brain's processing overhead)

------

### Techniques to reduce cognitive load

- Cognitive refactoring
    - Function inlining
    - Reorder code
    - Replace unfamiliar language constructs with familiar ones
        - Good moment to apply previous flashcard method here

------

### Memory aids to offload cognitive load

------

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH04_F06_Hermans2.png)

Dependency graph

------

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH04_F07_Hermans2.png)

State table

---
{{< slide bg-color="electric" >}}

## Part 2 - thinking about code

------

### *Roles of Variables* Framework

![RoV](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH05_F01_Hermans2.png)

------

{{< div "columns" >}}
{{< div "column" >}}![Icons](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH05_F02_Hermans2.png){{< /div >}}
{{< div "column" >}}![Example](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH05_F03_Hermans2.png){{< /div >}}
{{< /div >}}

------

### Model of understand
- text structure knowledge
- plan knowledge
	- what parts of the code relates to other parts, and how

------

### Focal point method
(abstraction of previous dependency graph)
1. Find a *focal point*
2. Expand knowledge from it
3. Understand a concept from a set of related entities (connect)
4. Understand concepts across multiple entities (connect more)

------

### Natural vs. Programming Language
- Better natural language skills strongly relates with better programmer, more than math skills
- Brodmann areas map + fMRI (functional magnetic resonance imaging)

------

### Text comprehension strategies applied to code

- Activating (prior knowledge)
- Monitoring
- Determining importance (of different lines of code)
    - Which parts have the most influence
    - Good moment for team learning, both of code and of people
- Inferring (the meaning of variable names)
    - Identifier names table
    - Divide variable names into 2 categories (domain and programming concept)
- Visualizing
    - All previous techniques
    - Identifier operations table
- Questioning
- Summarizing

------

#### Monitoring example

![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH05_F05_Hermans2.png)

------

### Explicit model, Mental model & Notional machine

![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH06_F02_Hermans2.png)

- Model is a great tool for our brain
- Caution: avoid to apply inappropriate models

------

#### Mental model

- A mental model creates an abstraction in your working memory that you can use to reason about the problem at hand.
- *incomplete* (still be useful if it abstracts the irrelevant details)
- *unstable* (mental nature)
- Multiple inconsistent ones can coexist
	- Competing mental models: snowman riddle
- Can be *weird*, and even *superstitious*
- Brain tends to save mental effort while using mental models

------

#### Mental model in working memory

- A more concrete model strongly supports reasoning
- More detailed, easier to reason about correctly
- Steps to help you form a mental model of complex code
	1. “Begin by creating local models.”
	2. “List all relevant objects in the codebase and the relationships between objects.”
	3. “Answer questions about the system and use the answers to refine your model.”

------

#### Mental model in LTM

- Somewhat similar to schemata
- Flashcard of mental models
	- Good for team exercise

------

#### Notional machine

![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH06_F04_Hermans2.png)

- “A model we use when reasoning about how a computer executes code.”
- “Work well relate programming concepts to everyday concepts that people have already formed strong schemata for.”
	- “A variable is like a bicycle,” is a lot less helpful

------

#### Example within our languages

- variable **holds** value
![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH06_F05_Hermans2.png)
- file is **open** or **closed**
- **pointer** **points** to a memory location
- function **returns** value
![](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH06_F06_Hermans2.png)

------

### Transfer

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH07_F01_Hermans2.png)

- “It happens when information you already know helps you do new things.”
- Two ways: transfer during learning, transfer of learning
	- Relates back to *elaboration* technique
- Influence factors
	- Mastery
	- Critical attributes
	- Similarity
	- Context (how similar the environments are)
	- Association (episodic memory, story)
	- Emotions

------

- Transfer forms
	- Low-road vs. High-road
	- Near vs. Far
	- Positive vs. Negative
- Difficulties
	- “already mastered one programming language will not always help you learn a new one.”
	- “if you set out to learn a new language to expand your way of thinking, it’s important to pick a language that is fundamentally different from the ones already mastered”

------

#### Misconceptions: Bugs in thinking

- Faulty assumption held consistently and with confidence.
    - ```Python
      def foo(bar=[]): pass
      ```
- Debug it with conceptual change
	- “An existing conception is fundamentally changed, replaced, or assimilated by the new knowledge.”
- Inhibition (self-consciousness) helps to suppress
- Ways to diagnose
	- Pair programming or group code review
	- Add test to verify your assumption
	- Documentation in relevant places of likely misconception

---
{{< slide bg-color="electric" >}}

## Part 3 - Writing better code

------

### How to get better at naming things

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH08_F01_Hermans2.png)

- We human naturally names things
- Good naming criteria
	- Syntactic naming conventions
	- Consistency

------

#### When & How

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH08_F02_Hermans2.png)

- When to evaluate the quality of names
	- Not while coding (cognitive load)
	- Good for code review time
- How to choose better names
	- Team agree on conventions:
        - name molds
        - acceptable abbreviations, words, single-letter variables
        - prefixes and suffixes

------

#### Name molds

{{< img src="/images/07 Name molds.png" >}}

- “Name molds are patterns in which elements in a variable name are typically combined.”
- “Project lexicon, in which all important definitions are noted and alternatives for synonyms are registered.”

------

### Avoiding bad code and cognitive load

Antipattern cause lots of cognitive load
- Structural antipatterns
	- Code smells
- Conceptual antipatterns (a.k.a. linguistic antipatterns)
	- Naming is confusing, misleading, or even incorrect
		- `retrieveElements()` returns a single element instead of a list
		- `isValid` is an integer instead of a Boolean

------

### Getting better at solving complex problems

- Research shown problem solving is neither a generic skill nor a cognitive process
- George Pólya “system of thinking” in 1945
	1. Understanding the problem
	2. Devising a plan (need knowledge in LTM)
	3. Carrying out the plan (need more detailed knowledge)

------

#### Types of memory in LTM

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH10_F02_Hermans2.png)
![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH10_F03_Hermans2.png)

------

#### Germane load

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH10_F06_Hermans2.png)

- Two techniques to improve
	- automatization
        - Ideal target of deliberate practice
	- worked examples
		- “to deliberately study how others have solved problems”
		- Code reading club, such as https://code-reading.org/

---
{{< slide bg-color="electric" >}}

## Part 4 - Collaborating on code

------

### The act of writing code

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH11_F01_Hermans2.png)

- Searching
	- offload tip: make notes
- Comprehension
	- offload tip: draw a model of the code, and update it accordingly
- Incrementation
	- Both of above offload tips
	- Split into smaller tasks, and being deliberate about what subtask you are doing
- Exploration
	- Even more heavier load on WM, so watch out

------

#### Interruptions during programming

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH11_F02_Hermans2.png)
![image](https://cdn.shopify.com/s/files/1/0018/5555/3588/products/blynclight-standard-new_large.jpg?v=1536199601)

- A warm-up and cooling down phase around the hardest part of activity
- Affects emotional state (annoyance and anxiety)
- When will be a better time
- Avoid multitasking, esp. during deep cognitive tasks

------

### Designing and improving larger systems

- Cognitive Dimensions of Notation (CDN) Framework
- Cognitive Dimensions of Codebases (CDCB)
- Factors with your brain (mentally), other than with the computer (technically)
- Not all dimensions matter for all codebases, analyze and evaluate once per year is good enough
- Design maneuver, change to a codebase to improve a certain dimension

------

### How to onboard new developers

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH13_F01_Hermans2.png)

Neo-Piagetian levels for programming

------

#### Semantic wave of learning

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH13_F02_Hermans2.png)

------

#### Antipatterns

![image](https://drek4537l1klr.cloudfront.net/hermans2/Figures/CH13_F03_Hermans2.png)

------

#### Activities for a better onboarding process

- “Deliberately manage the cognitive load of the people you are onboarding”
- “Specifically choose step-by-step activities for newcomer”
- Support LTM
	- Document of all important domain concepts
	- Document on external dependencies (library, framework, database, tool, etc)
- Support STM
	- Small, focused tasks
- Support working memory
	- Draw or update diagrams
- Read code together
