# ArtificialCrature

The main idea of this project is to develop a robot that looks like an artificial creature. 
That is to say, an object that looks artificial to everyone but at the same time that looks
intelligent to any observer.

We think that to achieve this state the robot should exhibit the three following properties:
- Reactive: the robot should react immediatly to changes happening in its environment
- Autonomous: the robot should sustain its autonomy and well being by itself
- Self-adaptive: the robot should adapt to the environment and learn to navigate in it

For the moment the following papers look like good inspiration to develop an architecture that
achieve the three goals:
- Hemminghaus, Jacqueline, and Stefan Kopp. “Towards Adaptive Social Behavior Generation for Assistive Robots Using Reinforcement Learning,” 332–40. ACM Press, 2017. https://doi.org/10.1145/2909824.3020217.
- Malfaz, María, Álvaro Castro-González, Ramón Barber, and Miguel A Salichs. “A Biologically Inspired Architecture for an Autonomous and Social Robot” 6, no. 1 (2007): 15.
- Michaud, François, François Ferland, Dominic Létourneau, Marc-Antoine Legault, and Michel Lauria. “Toward Autonomous, Compliant, Omnidirectional Humanoid Robots for Natural Interaction in Real-Life Settings.” Paladyn, Journal of Behavioral Robotics 1, no. 1 (January 1, 2010). https://doi.org/10.2478/s13230-010-0003-3.

The current goals of the project are not hardware dependent. Therefore we would like the architecture
to be easily transferable from one robot to another. This could pass by a division between two
levels:
- shell: low level behaviours grounded in the physic of the robot (i.e. ostacle avoidance)
- core: high level behaviours relying on symbol reasoning (i.e. plannificaiton of tasks)

# License
Please see LICENCE.txt in this directory.
