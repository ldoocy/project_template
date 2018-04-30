# IDS6145(SimTech 2018) - Research Plan

> * Group Name: *2 ∞ & Beyond!*
> * Group participants names: Lauren Doocy, Jihye Song, Jonathan Valderrama
> * Project Title: *If You Build It, They Will <s>Come</s> Do What?*

## Abstract

Our topic involves the impact of architecture on collective behavior. By integrating different approaches (e.g., social force model<sup>[[1]](#references)</sup>, OCEAN/Big Five personality model<sup>[[2]](#references)</sup>), we seek to model not just crowd behavior, but behavior of different individuals within crowds, and how individual differences affect the degree to which environment influences behavior. Additionally, we seek to model how manipulating the environment (e.g., by designing buildings in a certain way) can lead to varying changes in collective behavior as a function of individual differences and social interactions. This topic is important because by exploring how physical spaces alter human behavior at the individual and crowd level, this work can inform the design of spaces as a means of motivating desired behaviors. Potential applications include:
* Safe evacuation/stampede prevention
* Sustainable behavior (e.g., recycling)
* Healthy behavior (e.g., being more physically active, preventing spread of disease)
* Improving quality of life through design features like elements from nature<sup>[[3]](#references)[[4]](#references)</sup>
* Collaboration<sup>[[5]](#references)</sup>

![https://www.officelovin.com/2015/08/16/a-tour-of-ubers-new-san-francisco-office-expansion/](../images/fig1_uber-office.jpg)


## General Introduction

It is understood that humans' feelings are affected by their environment, both the built environment and the people they interact with. It is also understood that humans perform tasks differently based on individual differences, such as personality type. 
The OCEAN model provides a layout for particular personality types given five degrees of freedom. We aim to show the propogation of a feeling throughout a crowd. 
With a better understanding how individuals react to their environment, we can build an environment that encourages a group of people to perform desired actions. 
People with personalities that better react to the built environment will begin to influence those who are more affected by human to human interactions and so on. Here we apply self organization theories to understand the best method to promote a "good" feeling within a space.

This type of propogation of feelings can also be applied to a space where safety is concerned. If we implement an initial condition of a dangerous event that sparks panic, such as a fire, bomb, or active shooter, we can understand how to build an environment to encourage the least amount of panic. 
This can help usher the most amount of people to safety as possible. Reactions to extreme events will rely heavily on the personalities of the individuals involved, and we seek to understand the best scenario for all involved.

By taking an interdisciplinary approach and integrating social science and computational methods, we seek to create a model of social behavior that can be used to inform the design of spaces.

This project makes the following contributions:

1. Scientific Implications
    * Improving our understanding of social behavior using computational methods
    * Integrating interdisciplinary research approaches to form a novel model of social behavior as a function of physical spaces and human characteristics
2. Societal Implications
    * Improved public safety through design of spaces
    * Application of findings to real-world settings to enhance social interaction and collaboration among people

## The Model

The below diagrams demonstrate potential applications of our work.

![Proposal Object Diagram](../images/ProposalObjectDiagram.png)


![Proposal Behavior Diagram](../images/ProposalBehaviorDiagram.png)

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

![https://www.smithsonianmag.com/science-nature/crowds-are-much-smarter-we-suspected-180954868/](../images/crowd.jpg)

Below are examples of the type of data we expect to analyze.

![Proposal Histogram](../images/ProposalHistogram.png)

![Proposal Bargraph](../images/ProposalBargraph.png)


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
