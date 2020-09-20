#  Civil Violence Model (Modified)

To run the model please open RunEpsteinCivilViolence.ipynb and run the code. 
The code is based on EpsteinCivilViolence modified to include additional parameters. 
The model expects three new parameters: 
initial_unemployment_rate = 0.2,
corruption_level = 0.1,
susceptible_level = 0.6,

Each citizen can have one of four states {Susceptible, Honest, Jailed, Corrupted}.  Citizens can be employed/unemployed based on the given initial_unemployment_rate. 

The corrupted agents can influence other susceptible agents with a certain probability to become corrupted. 
The corrupted agents also alter the employment rate. They can assign a job to a newly corrupted agent and take a job from other non corrupted agents with a certain probability. 


## Files

* ``EpsteinCivilViolence.py``: Core model and agent code.
* ``EpsteinCivilViolenceServer.py``: Sets up the interactive visualization.
* ``Epstein Civil Violence.ipynb``: Jupyter notebook conducting some preliminary analysis of the model.


This model is based adapted from:

[Epstein, J. “Modeling civil violence: An agent-based computational approach”, Proceedings of the National Academy of Sciences, Vol. 99, Suppl. 3, May 14, 2002](http://www.pnas.org/content/99/suppl.3/7243.short)

