# Determining the Effect of Wind on a CA-based Fire Propagation Model
by Elias Gabriel and Erika Lu

# Abstract
While cellular automata have often been used to simulate wildfires, a devastating fire that hit the forests of Southern Portugal in 2012 exhibited an explosive behavior that was not well captured by existing models. Models for fire spread are valuable to disaster relief organizations and volunteers, as they can help identify where relief resources can be allocated. In these cases, it is important for models to reasonably accurately predict spread patterns and disaster zones.

We attempted to answer whether or not the inclusion of wind data in a fire-modeling cellular automata has a substantial impact on the overall behavior of a system. We replicated a model proposed by Freire et al. and make use of NumPy to perform iterative probability-based array operations. We visualized the results using Seaborn and matplotlib and conclude, in agreement with the original authors, that the inclusion of wind data has a very substantial impact on the spread of fire under numerous environmental conditions.

The code behind our data parsing and aggregation is avalibale on [Binder](https://mybinder.org/v2/gh/thearchitector/wind-and-fire/e30c753b886af94fa0e0a8c2e71178739dcb3bb1).
You can follow along and run the code behind our CA and analysis on [Google Colab](https://colab.research.google.com/drive/1oxDOWZ2jLf-vwF6y1FeO4pElzdakRbbm).
