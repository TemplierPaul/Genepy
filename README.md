# Genepy
by Paul TEMPLIER

Artificial Life in a 2D environment

Run : Génépy_Main.ipynb

Implemented:
- Environment: map with grass (food) and water (useless for now)
- Memory: Group class to iterate more efficiently on the population and the environment
- Moving randomly
- Eating Grass
- Reproducing
- Seasons: grass growing and dying in cycles (toggled)
- UI: animated view

WIP:
- Data viz
Visualization of various data from the simulation, eg: population size in time, distribution of animal characteristics across population
- Brain
Based on NEAT (NeuroEvolution of Augmenting Topologies), brains are Artificial Neural Networks acting as decision functions to define the behavior of an animal. They are specific to each individual,  

TO DO:
- Agressive behavior: Fighting, eating meat
- Balance: make the simulation run with a stable population size
- Species representation: clustering to show groups of similar animals
- Specific environments: custom maps to study how populations evolve under specific constraints
