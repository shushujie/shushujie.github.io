---
<<<<<<< HEAD
title: *
=======
title:
>>>>>>> 8805b4fd7aec2f53f1cfc5adddd775d56f35f940
layout: page
---











## Inspiration

----------------------
A kinetic Model was developed based on Stefan model coupled to diffusion ki- netics. The diffusion parameters for WO2 for which the diffusion proper has little related literatures, was obtained with DFT calculations. Finally We carried out a Machine Learning model to reproduce the Oxidation kinetic model so the growth curve, with a selected temperature, for the oxidation process of pure tungsten can be predicted.

## What it does
The kinetics model of tungsten’s oxidation basically takes the database built on various examples of oxidation process from literatures to fit the diffusion parameters for oxide layer W O2.9 and W O2.72 in the model, thus it is enabled to locate valid values for each related parameter .Though the values acquired can be semi-determined(different combinations of fitting parameters can finally produce similar oxidation growth curves that fit a same previous experiment), we can use them to produce a more powerful database which will boost the machine learning model to mimic a complete simulation model for tungsten’s oxidation.


## How we built it
• Built a package with Object Oriented Design for: PDE solver, interface tracker, curve fitter, etc., and wrote 1000+ lines Java code.
• Created 100+ lines of shell scripts for the model and provided 100+ data points, mitigated the lack of references in the research field.


## Challenge we ran into
In the most general case the oxidation of metallic tungsten will evolve into a structure characterized by five distinct layers. These layers represent different tungsten-oxygen structures ranging from WO3 on the environment side (where O radicals are produced) to the W-O metallic solid solutions (where the metal is reduced). In between, three more oxide phases are expected to form, namely, WO2.9, WO2.72, and WO2.


