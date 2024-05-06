# Thesis
This repository provides a short description of my thesis, the model that I adapted and extended, and the Jupyter notebooks in which I simulated the model and analysed the results.

## Problem statement
Neodymium-Iron-Boron permanent magnets (NdFeB) are critical for the energy transition. Currently the strongest permanent magnets on the market, NdFeB magnets are also essential in today’s high–tech industry. They are used in various digital appliances like consumer electronics, electric cars and wind turbines. NdFeB magnets outperform other magnets, because of the use of rare earth elements (REEs). Generally, REEs are divided into two groups, light and heavy rare earth elements (LREE and HREE, respectively), with HREEs generally being more scarce and also more expensive. NdFeB permanent magnets contain Neodymium and Praseodymium (both LREEs), as well as Dysprosium and/or Terbium (both HREEs). 

China’s dominance in the NdFeB supply chain increases at every downstream stage of production of NdFeB magnets, resulting in a 92% share of annual global magnet production. A key question for decision makers on the energy transition is whether supply of NdFeB magnets can meet the demand of clean energy technologies. The demand of NdFeB permanent magnets will likely grow tremendously due to an expected growth in demand for clean energy technologies and further digitisation. Substitution might be a viable mechanism to reduce the dependency on REEs in both the short and long term. For decision makers in the energy transition, it is valuable to understand how substitution of REEs can contribute to the supply of electric cars and wind energy. This will therefore be the focus of this research. 

## Project description
In order to tackle this problem, I adapted and extended a supply chain model in order to assess the substitution potential of REEs in NdFeB magnets in electric cars and wind turbines. A combination of system dynamics (SD) and exploratory modelling and analysis (EMA) is chosen as the modelling methodology. Assessing long-term availability of supply and demand of material supply chains is a deeply complex and uncertain issue. SD is tailored to model complex systems with time delays, accumulation, internal feedback loops and non-linear behaviour. In order to cope with the deeply uncertain nature of the system, EMA will be used to offer decision-making support under deep uncertainty. A combination of SD and EMA has been used in recent years in modelling material supply chains. 

This research evaluates the effect substitution of REEs might have on the long-term implementation of wind energy and electric cars under a wide range of scenarios. The material supply chain model used in this study was originally developed for the Copper supply system by Auping (2011) and was further adapted and expanded by Van der Linden (2020) to explore the Cobalt supply system. The model by Van der Linden (2020) will be adapted to fit the REE supply system and will then be extended to include various substitution mechanisms. The chosen time period is until 2050, seeing as many sustainability policies share this time span. The model is built in Vensim, a software designed for system dynamics modelling, and simulated in python using Jupyter notebooks, primarily using the EMA workbench, a python library that is specialized in modelling and simulating problems of deep uncertainty.

## Folder structure
This repository contains three folders:
1. Model:

   This folder contains two models:
   - _model_ndfeb_subst.mdl_: This model can be used to open and to play around by yourself.
   - _model_ndfeb_subst.vpmx_: This model has the right extension, so that it can be used to simulate in the jupyter notebooks.
3. Simulation

   This folder contains two Jupyter notebooks:
   - _Generate results.ipynb_: In this notebook, model is simulated, the uncertain variables are introduced and the uncertainty range of these variables is given.
   - _Clustering.ipynb_: In this notebook runs are clustered, both on the amount of electric cars in use and on the amount of wind energy in use.  
5. Analysis

   This folder contain three Jupyter notebooks:
   - _Chapter 3.4.3 - replicative validation.ipynb_: In this notebook the figure for replicative validation in chapter 3.4.3 is generated. The model outcomes regarding demand of Neodymium is compared to projections from related research.
   - _Chapter 4.1 - Development of the system.ipynb_: In this notebook the figures pertaining to the development of REEs, electric cars and wind turbines, discussed in chapter 4.1, are generated.
   - _Chapter 4.2 - Substitution mechanisms.ipynb_: In this notebook the figures pertaining to the effect of substitution mechanisms, discussed in chapter 4.2 are generated. 


References:

Auping, W. (2011). The uncertain future of copper: An exploratory system dynamics model and 	analysis of the global copper system in the next 40 years (Master’s thesis, Delft University of 	Technology). Retrieved from 	https://repository.tudelft.nl/islandora/object/uuid%3A4998f817-848d-4879-9d5f-2c0bd9ee4c81

Van der Linden, E. (2020). Exploration of the cobalt system: Scenarios for a critical material for the 	energy system (Master’s thesis, Delft University of Technology). Retrieved from 	https://repository.tudelft.nl/islandora/object/uuid%3Ae51dbb87-09f7-4c33-a956-226874a



