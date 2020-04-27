## This is a repository for learning mesa
#### Ref: https://mesa.readthedocs.io/en/master/tutorials/intro_tutorial.html


### Installation
- first need to intall pipenv: python3 -m pipenv (*ref: https://stackoverflow.com/questions/46391721/pipenv-command-not-found)
- then type: pipenv install mesa
- run: pipenv shell (* to activate the virtual environment)

### Link with Github
- create a repo on Github
- in terminal, mkdir mesa , cd mesa, touch readme.md
- within mesa wd, type: jupyter notebook 
- when jupyter notebook webpage pop up, on the top right-hand side click new, then choose python3 to open up a new notebook
- rename of the notebook first


### Model setting up
- set two core classes: one for the overall model, the other for agents
  - **model class**: 
        1. holds model-level attributes, manages the agents and generally handels the global level of model;
        2. each instantiation of the model class will be a specific model run
  - **agent class**: each model will contain multiple agents, all of which are instantiations of the agent class. 
        1. each agent has only one variable -- the amount of wealth it currently has;
        2. each agent also has a unique identifier (a name) stored in 'unique_id' variable. 
        
        
        
        
- both the model and agent classes are child classes of Mesa's generic 'Model' and 'Agent' classes. 


- 
