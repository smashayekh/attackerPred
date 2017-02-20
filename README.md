# Terrorist Group Predictor

This repository contains a Jupyter notebook that answers the challenge "Global Terrorist Attacks" from startup.ml.

Here is the challenge: https://startup.ml/challenge

Global Terrorism Database (GTD) is an open-source database including information on terrorist events around the world from 1970 through 2014. Some portion of the attacks have not been attributed to a particular terrorist group.

Use attack type, weapons used, description of the attack, etc. to build a model that can predict what group may have been responsible for an incident.

To answer this question, after some exploratory data analysis and determining potential features, I use a Random Forest Classifier to predict the terrorist group behind an attack, based on its features. The classifier makes a correct prediction in about 70% of the time. 
