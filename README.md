# Agents in Artificial Intelligence
An AI system can be defined as the study of the `rational agent` and its `environment`. The agents sense the environment through `sensors` and act on their environment through `actuators`. An AI agent can have mental properties such as knowledge, belief, intention, etc.

- `Human-Agent`: A human agent has eyes, ears, and other organs which work for sensors and hand, legs, vocal tract work for actuators.

- `Robotic Agent`: A robotic agent can have cameras, infrared range finder, NLP for sensors and various motors for actuators.

- `Software Agent`: Software agent can have keystrokes, file contents as sensory input and act on those inputs and display output on the screen.

####  ***the world around us is full of agents such as thermostat, cellphone, camera, and even we are also agents***

- `Sensor`: Sensor is a device which detects the change in the environment and sends the information to other electronic devices. An agent observes its environment through sensors.

- `Actuators`: Actuators are the component of machines that converts energy into motion. The actuators are only responsible for moving and controlling a system. An actuator can be an electric motor, gears, rails, etc.

- `Effectors`: Effectors are the devices which affect the environment. Effectors can be legs, wheels, arms, fingers, wings, fins, and display screen.

<br>
<div align="center">
    <img src="https://www.doc.ic.ac.uk/project/examples/2005/163/g0516334/images/sensorseniv.png" alt="Actions Of Rational Agents ">
</div>
<br>

### Rules Of Intelligent Agents In AI
+ ***Rule 1***: An AI agent must have the ability to perceive the environment.
+ ***Rule 2***: The observation must be used to make decisions.
+ ***Rule 3***: Decision should result in an action.
+ ***Rule 4***: The action taken by an AI agent must be a rational action.

### Rational Agent:
- A rational agent is an agent which has clear preference, models uncertainty, and acts in a way to maximize its performance measure with all possible actions.

- A rational agent is said to perform the right things. `AI is about creating rational agents` to use for game theory and decision theory for various real-world scenarios.

### Structure of an AI Agent
The task of AI is to design an `agent program` which implements the `agent function`. The structure of an intelligent agent is a combination of `architecture` and `agent program`. 

```
Agent = Architecture + Agent program
```

- `Architecture`: Architecture is machinery that an AI agent executes on.
- `Agent Function`: Agent function is used to map a percept to an action.  
- `Agent program`: Agent program is an implementation of agent function. An agent program executes on the physical architecture to produce function f. f:P* → A 

## PEAS Representation
PEAS is a type of model on which an AI agent works upon. When we define an AI agent or rational agent, then we can group its properties under PEAS representation model. It is made up of four words:
- `P`: Performance measure
- `E`: Environment
- `A`: Actuators
- `S`: Sensors
  
***Here performance measure is the objective for the success of an agent's behavior.***

## Types of AI Agents
Agents can be grouped into five classes based on their degree of perceived intelligence and capability.
- [Simple Reflex Agent](https://www.geeksforgeeks.org/agents-artificial-intelligence/)
- [Model-based reflex agent](https://www.geeksforgeeks.org/agents-artificial-intelligence/)
- [Goal-based agents](https://www.geeksforgeeks.org/agents-artificial-intelligence/)
- [Utility-based agent](https://www.geeksforgeeks.org/agents-artificial-intelligence/)
- [Learning agent](https://www.geeksforgeeks.org/agents-artificial-intelligence/)

## `Simple Reflex agent` :
- The Simple reflex agents are the simplest agents. These agents take decisions on the basis of the current percepts and ignore the rest of the percept history.
- These agents only succeed in the fully observable environment.
- The Simple reflex agent works on Condition-action rule, which means it maps the current state to action. Such as a Room Cleaner agent, it works only if there is dirt in the room.
- Problems for the simple reflex agent design approach:
   - They have very limited intelligence
   - They do not have knowledge of non-perceptual parts of the current state
   - Mostly too big to generate and to store.
   - Not adaptive to changes in the environment.

<br>
<div align="center">
    <img src="https://static.javatpoint.com/tutorial/ai/images/simple-reflex-agent.png" alt="Simple Reflux Agent">
</div>
<br>

## `Model-based reflex agent` :
- The Model-based agent can work in a partially observable environment, and track the situation.
- A model-based agent has two important factors:
    - Model: It is knowledge about "how things happen in the world," so it is called a Model-based agent.
    - Internal State: It is a representation of the current state based on percept history.

<br>
<div align="center">
    <img src="https://static.javatpoint.com/tutorial/ai/images/model-based-reflex-agent.png" alt="Model Based Reflux Agent">
</div>
<br>

## `Goal-based agents` :
- The knowledge of the current state environment is not always sufficient to decide for an agent to what to do.
- The agent needs to know its goal which describes desirable situations.
- Goal-based agents expand the capabilities of the model-based agent by having the "goal" information.
- They choose an action, so that they can achieve the goal.
- These agents may have to consider a long sequence of possible actions before deciding whether the goal is achieved or not. Such considerations of different scenario are called searching and planning, which makes an agent proactive.

<br>
<div align="center">
    <img src="https://static.javatpoint.com/tutorial/ai/images/goal-based-agent.png" alt="Goal Based Agent">
</div>
<br>

## `Utility-based agent` :
- These agents are similar to the goal-based agent but provide an extra component of utility measurement which makes them different by providing a measure of success at a given state.
- Utility-based agent act based not only goals but also the best way to achieve the goal.
- The Utility-based agent is useful when there are multiple possible alternatives, and an agent has to choose in order to perform the best action.
- The utility function maps each state to a real number to check how efficiently each action achieves the goals.

<br>
<div align="center">
    <img src="https://static.javatpoint.com/tutorial/ai/images/utility-based-agent.png" alt="Utility Based Agent">
</div>
<br>

## `Learning agent` :
- A learning agent in AI is the type of agent which can learn from its past experiences, or it has learning capabilities.
- It starts to act with basic knowledge and then able to act and adapt automatically through learning.
- A learning agent has mainly four conceptual components, which are:
    - `Learning element`: It is responsible for making improvements by learning from environment
    - `Critic`: Learning element takes feedback from critic which describes that how well the agent is doing with respect to a fixed performance standard.
    - `Performance element`: It is responsible for selecting external action
    - `Problem generator`: This component is responsible for suggesting actions that will lead to new and informative experiences.

<br>
<div align="center">
    <img src="https://static.javatpoint.com/tutorial/ai/images/learning-agent.png" alt="Learning Agent">
</div>
<br>




## Turing Test in AI
In 1950, `Alan Turing` introduced a test to check whether a machine can think like a human or not, this test is known as the `Turing Test`. In this test, Turing proposed that the computer can be said to be an intelligent if it can `mimic human response` under specific conditions.

Turing Test was introduced by Turing in his 1950 paper, `Computing Machinery and Intelligence`, which considered the question, `"Can Machine think?"`

<br>
<div align="center">
    <img src="https://static.javatpoint.com/tutorial/ai/images/turing-test-in-ai.png" alt="Actions Of Rational Agents ">
</div>
<br>

 This game involves `three players` in which one player is `Computer`, another player is `human responder`, and the third player is a` human Interrogator`, who is isolated from other two players and his job is to find that which player is machine among two of them.

Consider, Player A is a computer , Player B is human, and Player C is an interrogator. Interrogator is aware that one of them is machine, but he needs to identify this on the basis of questions and their responses.
The conversation between all players is via keyboard and screen so the result would not depend on the machine's ability to convert words as speech.

The test result does not depend on each correct answer, but only how closely its responses like a human answer. The computer is permitted to do everything possible to force a wrong identification by the interrogator.

The questions and answers can be like:

Interrogator: Are you a computer?

PlayerA (Computer): No

Interrogator: Multiply two large numbers such as (256896489*456725896)

Player A: Long pause and give the wrong answer.

In this game, if an interrogator would not be able to identify which is a machine and which is human, then the computer passes the test successfully, and the machine is said to be intelligent and can think like a human.


### Features required for a machine to pass the Turing test:
- `Natural language processing`: NLP is required to communicate with Interrogator in general human language like English.
- `Knowledge representation`: To store and retrieve information during the test.
- `Automated reasoning`: To use the previously stored information for answering the questions.
- `Machine learning`: To adapt new changes and can detect generalized patterns.
- `Vision` (For total Turing test): To recognize the interrogator actions and other objects during a test.
- `Motor Control` (For total Turing test): To act upon objects if requested.

-----

### Previous Topics : 
- [Artificial Intelligence.]()
### Next Topics : 
- [Search Algorithms in AI.]()

### Created By:
<a href = "https://github.com/hacker-404-error">Pritam Das</a>

<a href="https://github.com/hacker-404-error"><img src="https://avatars.githubusercontent.com/u/93383417?s=400&u=f4a9586e9618a27227ff3723ed6e282fc5be78fd&v=4" alt="Avatar" style="border-radius: 50%; width:70px"></a>



-------------------------------------------------------------------------------------------------------------