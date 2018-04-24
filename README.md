# IDS6145(SimTech 2018) - Research Plan

> * Group Name: *2 ∞ & Beyond!*
> * Group participants names: Lauren Doocy, Jihye Song, Jonathan Valderrama
> * Project Title: *If You Build It, They Will <s>Come</s> Do What?*

## Abstract
Helbing's Social Force Model<sup>[[1]](#references)</sup> proposes that the list of influences on pedestrian movement extends past a desired goal. We seek to model pedestrian movements within various spaces and discuss how individual personality differences affect movements within a system. Additionally, we seek to model how manipulating the environment (e.g., by designing buildings in a certain way) can lead to varying changes in collective behavior as a function of individual differences and social interactions. 
The Social Force Model includes influences of a desired goal, other pedestrians within the system, as well as boarders and walls. In addition to this, individual personality traits will affect individual behaviors within a crowd. We seek to understand these individual traits and their influence on behavior within the system.

Recently, we have become more conscious in designing spaces with an explicit intent (e.g., environmentally friendly, cost effective heating and cooling), and we intend to explore how physical spaces alter human behavior to motivate a desired behavior. Once we understand human behavior at the individual level, potential applications can include:
* Safe evacuation/stampede prevention
* Sustainable behavior (e.g., recycling)
* Healthy behavior (e.g., being more physically active, preventing spread of disease)
* Improving quality of life through design features like elements from nature<sup>[[3]](#references)[[4]](#references)</sup>
* Collaboration<sup>[[5]](#references)</sup>

![https://www.officelovin.com/2015/08/16/a-tour-of-ubers-new-san-francisco-office-expansion/](images/uber-office.jpg)


## General Introduction

Decades ago, people believed human behavior is unpredictable due to the unreliable behavior or humans. However, it has been shown by numerous scientists that, in fact, the movements of pedestrians can be modeled by already studied substances such as gases and fluids. Helbing took the approach that pedestrians will move with the influence of social forces. He defines such forces as the ultimate goal of the pedestrian in combination with the idea that humans will keep a certain distance from walls and boarders as well as strange people, and will be formally attracted to other pedestrians which the consider a friend<sup>[[1]](#references)</sup>. This causes pedestians to travel and pair and keep a predictable distance from strange groups of people.

Humans perform tasks differently based on individual differences, such as personality type. Personality influences, along with the social force model, must determine the choice path of pedestrians within a system. With a better understanding how individuals react to their environment, we can build an environment that encourages a group of people to perform desired actions. This desired action can include preffered evacuation methods, encouragement of collaboration, or optimal "good vibes" within a space. By taking an interdisciplinary approach and integrating social science and computational methods, we seek to create a model of social behavior that can be used to inform the design of spaces.

This project makes the following contributions:

1. Scientific Implications
    * Improving our understanding of social behavior using computational methods
    * Integrating interdisciplinary research approaches to form a novel model of social behavior as a function of physical spaces and human characteristics
2. Societal Implications
    * Improved public safety through design of spaces
    * Application of findings to real-world settings to enhance social interaction and collaboration among people

## The Model
### Social Force Model

The Social Force Model<sup>[[1]](#references)</sup>, describes pedestrian behavior by four actions:

1. Desired direction of movement
2. Repulsive social forces
3. Repulsive forces from walls or any obstacles
4. Attractive social forces

This is described by the equation:

![Social Force](images/socialforceeq.png)

### Desired Direction:
![Social Force](images/desired.png)

The first term in the social force equation takes into account the pedestrians desired movement. Each entity will have a defined goal to reach in the shortest distance possible. This term depends on the entities desired velocity and the entities actual velocity.

### Repulsive Social Forces:
![Social Force](images/repulsive.png)

The second term is a summation of repulsive forces given from other pedestrians in the system. This is known as a repulsive social force. This term depends on the pedestrian's desired direction and the distance from the other pedestrian. Pedestrians desire to keep a distance from strange people and will change directions and velocity to account for this.

### Desired distance from walls/borders:
![Social Force](images/boarders.png)

The third term stands as a summation of the effects of all boarders and obsticals present. Each pedeistrian will desire to keep a certain distance from walls, furnature, decorations, and other boarders. This term takes into account each pedestrian's desired direction and his or her distance from the boarder. Since boarders and walls are typically larger than a single point, the point used to calculate distance from boarder will change dymamically as the closest point to the pedestrian.

###Social Attraction Forces:
![Social Force](images/friends.png)

The fourth and final defined term in the social force model is the attractive forces. This takes into account that given a shared goal, pedestrians will travel with friends. This term takes into account desired direction, distance from a friendly pedestrian, and time.

The social force model takes into account random behaviors with a fluctuation term. This could be desired velocities, movements, or personal space preferences based on ones personality or random behaviors based on individual decisions to avoid obstacles. 
We predict that personality differences influence pedestrian behaviors. In the present study, we draw from the OCEAN model, focusing on the effect of introversion and extroversion on agent behaviors within a simulation. While influences like personality are broadly covered by the fluctuation term, we seek to enhance the Social Force Model by identifying and integrating individual variables that influence real human behavior.

### Our Model
The below diagrams demonstrate potential applications of our work.

![Proposal Object Diagram](images/ProposalObjectDiagram.png)


![Proposal Behavior Diagram](images/ProposalBehaviorDiagram.png)

##### Requirements

* The model shall produce agent behavior that replicates real observed behavior (assessed looking at past/historical events)
* The model shall include individual characteristics that each agent will have (e.g., personality type)
* Agents in the model shall behave according to both individual characteristics, as well as social factors
* The model shall simulate collective behavior in different physical environments

## Fundamental Questions

* **Research Question 1**: What theory or theories best explain and predict human behavior?
    * 1a. What individual parameters (e.g., OCEAN personality type, emotion, etc.) need to be included in an agent-based model to represent varying social behaviors dependent on physical structures?
    * 1b. What *combination* of parameters is optimal for replicating and predicting real behavior patterns?

* **Research Question 2**: How can physical structures be designed to facilitate desired group behavior?
    * 2a. What features promote/hinder actions like collaboration?
    * 2b. How do physical structures alter collective behavior?

* **Research Question 3**: To what extent and how do individual differences in people affect how physical structures influence their actions?
    * 3a. Which individual differences are likely to result in varying reactions to physical structures designed to elicit certain behaviors?
    * 3b. How can we optimize building design to account for individual differences in people?


## Expected Results

We expect that given input from different theories and varying combinations of individual agent parameters, we will see patterns of collective behavior emerge<sup>[[6]](#references)</sup>. 

We also expect that design to nudge human behavior will have varying results based on individual differences.

![https://www.smithsonianmag.com/science-nature/crowds-are-much-smarter-we-suspected-180954868/](images/crowd.jpg)

Below are examples of the type of data we expect to analyze.

![Proposal Histogram](images/ProposalHistogram.png)

![Proposal Bargraph](images/ProposalBargraph.png)


## Research Methods

To explore our research questions, we utilized agent based modeling and AnyLogic.

(Cellular Automata, Agent-Based Model, Discrete Event Continuous Modeling...)(Python or Anylogic)  (Steps in the process)

## (Other)
(change the title and amount of headers as needed) (mention datasets you are going to use) (mention base code or examples you)

## Discussion
(final only - remove whole section for proposal Readme) 
(What would you have done differently) 
What are the contributions summarize)
(what is the big take away)
(what did you learn)

## Future Work
(final only - remove whole section for proposal Readme) (if you had 6 more months what would be the next steps in this project.) (What are a few questions you have now)

While relatively simple models can replicate human social behavior with significant accuracy, future work should seek to add additional parameters to account for the complexity of human motivations, personality, and other factors influencing actions.

## References

<sup>[[1]](#abstract)</sup> Helbing, D., & Molnar, P. (1995). Social force model for pedestrian dynamics. *Physical Review E, 51*(5), 4282. [Link](https://arxiv.org/pdf/cond-mat/9805244.pdf)

<sup>[[2]](#abstract)</sup> Durupinar, F., Pelechano, N., Allbeck, J., Gudukbay, U., & Badler, N. I. (2011). How the ocean personality model affects the perception of crowds. *IEEE Computer Graphics and Applications, 31*(3), 22-31. [Link](https://doi.org/10.1109/MCG.2009.105)

<sup>[[3]](#abstract)</sup> Kaplan, S. (1995). The restorative benefits of nature: Toward an integrative framework. *Journal of Environmental Psychology, 15*(3), 169-182. [Link](https://pdfs.semanticscholar.org/a506/f60e29b6aa386a381f6aa213b89c30ecdda9.pdf)

<sup>[[4]](#abstract)</sup> Ulrich, R. S. (1979). Visual landscapes and psychological well‐being. *Landscape Research, 4*(1), 17-23. [Link](http://rsos.royalsocietypublishing.org/content/2/3/140437)

<sup>[[5]](#abstract)</sup> Pinter-Wollman, N., Fiore, S. M., & Theraulaz, G. (2017). The impact of architecture on collective behaviour. *Nature Ecology & Evolution, 1*(5), s41. [Link](https://pinterwollmanlab.eeb.ucla.edu/wp-content/uploads/sites/86/2016/05/Pinter-Wollman-et-al-2017-NEE.pdf)

<sup>[[6]](#expected-results)</sup> Smaldino, P. E., & Epstein, J. M. (2015). Social conformity despite individual preferences for distinctiveness. *Royal Society Open Science, 2*(3), 140437. [Link](http://rsos.royalsocietypublishing.org/content/2/3/140437)

<sup>[[3]](#abstract)</sup> Kaplan, S. (1995). The restorative benefits of nature: Toward an integrative framework. *Journal of Environmental Psychology, 15*(3), 169-182. [Link](https://pdfs.semanticscholar.org/a506/f60e29b6aa386a381f6aa213b89c30ecdda9.pdf)

<sup>[[4]](#abstract)</sup> Ulrich, R. S. (1979). Visual landscapes and psychological well‐being. *Landscape Research, 4*(1), 17-23. [Link](http://rsos.royalsocietypublishing.org/content/2/3/140437)

<sup>[[5]](#abstract)</sup> Pinter-Wollman, N., Fiore, S. M., & Theraulaz, G. (2017). The impact of architecture on collective behaviour. *Nature Ecology & Evolution, 1*(5), s41. [Link](https://pinterwollmanlab.eeb.ucla.edu/wp-content/uploads/sites/86/2016/05/Pinter-Wollman-et-al-2017-NEE.pdf)

<sup>[[6]](#expected-results)</sup> Smaldino, P. E., & Epstein, J. M. (2015). Social conformity despite individual preferences for distinctiveness. *Royal Society Open Science, 2*(3), 140437. [Link](http://rsos.royalsocietypublishing.org/content/2/3/140437)
