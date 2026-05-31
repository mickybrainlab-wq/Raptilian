# Raptilian Programming Syllabus


```
┌─────────────────────────────┐
│  Layer 5 : Production       │
├─────────────────────────────┤
│  Layer 4 : LLD             │
├─────────────────────────────┤
│  Layer 3 : HLD             │
├─────────────────────────────┤
│  Layer 2 : DSA             │
├─────────────────────────────┤
│  Layer 1 : Action Language │
└─────────────────────────────┘
````
We will learn it in 5 parts

## 1. PROGRAMMING LANGUAGE (to communicate with the action system)

Programming languages communicate with computers.

### 1.1 Action system 

The action system tawlks in 

1. signals
2. Targets
3. constraints
4. Rewards
5. Threats
6. Patterns

It does not understand the laguge like

```
Become successful
Become rich
Become disciplined
Become confident
```

### 1.2 Primitive Data Types



1. Target --> read 10 pages
2. TIme --> Before 6 PM
3. Quantity --> 20 pushups
4. Constraint --> no phone until completed
5. Reward --> watch movie after completion
6. Identity --> I am a person who finishes tasks



### 1.3 Built-in Functions --> that directly calls the action system, and demand energy and controlover system.



1. focus() --> purpose of this method is **Direct attention**

```
focus("Chapter 3")
```

2. deadline() --> purpuse of this method is to **Create Scarecity.**

```
deadline("6 PM")
```

3. chunk() --> purpose is to reduce the **complexity**.

```
chunk("Build Startup", 10 steps) // target + no of steps
```

4. repeat() --> purpose is to create cache , patterns. that will not need much resource.

```
repeat("7 PM Daily")
```

5. reward() --> purpose is to create **reinforcement**

```
reward("Tea")
```

6. compare() --> creates meaning through constrast (like if all fail and you got 40% acc to this method you will be happy)

```
compare(Stack, Queue)
```

7. gap() --> purpose is to create **curiosity** --> to triger search action

8. mystery() --> purpose is to create attention loop --> ask multiple questions 

```
mystery("How did Airbnb survive?")
```

## 2. DSA of Raptilian --> How should knowledge and goals be stored?


1. Array --> for check list

```
Task1
Task2
Task3
```

2. Stack --> immediate priorities.

```
Top = Current Mission
```

3. Queue --> backlogs storage

```
Learn React
Learn Node
Learn System Design
```
4. Tree --> used for knowledge


```
React
│
├── Components
├── Hooks
├── Routing
└── State
```

5. Graph --> used for Mental Models

```
Psychology ↔ Marketing
Psychology ↔ Leadership
Psychology ↔ Sales
```

6. HashMap --> Fast retrival (very important, a problem and list of solutions in array)

```
Problem -> Solution


like

Procrastination -> Clear Target
```

7. Priority queue --> used for **Decision making** (what should i do now to move myu gole matrix)

```
Impact
Urgency
Importance
```


## HLD --> What system creates the desired outcome?


Like goal is to launch a **Startup**


#### System Design 

```
Vision
│
├── Product
├── Marketing
├── Sales
├── Operations
├── Finance
└── Team
```


#### Inputs 

1. Time
2. Energy
3. Money
4. SKills

#### Output 

1. Customers
2. Revenue
3. Growth

#### Constraints 

1. Budget
2. Competition
3. deadlines

#### Metrics 

1. Users
2. Revenue
3. Retention

## LLD ---> How do components communicate?

1. Marketing module

Components:


```
Research
↓
Content
↓
Distribution
↓
Lead Capture
↓
Sales
```


Note :- mamalian takes action , raptilian creates emotion to support that action, neocortex handles the design and clearity task that will be used by raptilian.


#### Human GOF Patterns


1. Observer Pattern --> leader watches metrics

```
Metric Changed
↓
Leader Responds
```
2. Strategy Pattern --> different plan (different options acc to condition)

```
Exam Strategy
Startup Strategy
Fitness Strategy
```

3. Command Pattern --> Action triggers.

```
Alarm
↓
Workout
```

4. State Pattern --> Behaviour depends on state

```
Energy High
Energy Low
```

5. Feedback Pattern

```
Action
↓
Result
↓
Adjustment
```


## Production system


Software fails without production systems.

Humans fail for the same reason.

1. Logging --> recors behavior.

```
Date
Task
Completed
Reason
```

2. Monitoring --> Track metrics

```
Study Hours
Workout Hours
Revenue
Sleep
```

3. Authentication --> Who is allowed to influence decisions?

```
Random Opinions = Rejected
Trusted Mentors = Accepted
```


4. Authorization --> What can influence behavior?

```
Social Media
Restricted

Learning Material
Allowed
```

5. Database --> Knowledge Repository

```
Books
Notes
Experiences
Failures
Insights
```

6. Cache --> Frequently used knowledge

```
Core Principles
Daily Rules
Mission
```
But it must be also stored in database for longer retrival

7. Backup System --> When motivation disappears.

```
Minimum Daily Action.


Read 1 page
Do 1 pushup
Write 1 line

```

## DIFFERENT USER ROLES

#### Leader 

Design system for

```

Matrix


People
Performance
Direction
```

#### Coach 

Create Learning Loops

```
Growth
Skill Acquisition
Retention
```

#### Communicator

Transfer knowledge.

```
Stories
Mysteries
Analogies
Knowledge Gaps
```


#### Founder

Create value systems.

```
Vision
Execution
Feedback
Iteration
```
#### Actor / Performer --> control attention

```
Emotion
Timing
Presence
Story
```





#### =======================================================================================
    There is a system a programming language given to human to design acc to them , else it will react not act.--> the action system is to react only. Its your work is to make it act.

    Core truth :- use the system else system will use you. (its a nature law)
#### =======================================================================================























