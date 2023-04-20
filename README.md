# [IN-DEVELOPMENT] Transiting-Exoplanet-Debris-Cloud
In-development model simulating the changes of lightcurves when a debris cloud is present around a transiting exoplanet.

Other files in this repository contain common error resolutions, required modules, and more extensive research notes / assumptions / and equations. 
This project was developed by New Mexico Institute of Mining and Technology students, find below our summation of research. 

This project developed an exoplanet transit and lightcurve model with large data format versatility for the analytical purpose of testing if satellite debris clouds around transiting exoplanets could be detected from Earth, or near-Earth. Previously, all known models of similar capability focused on direct data analysis from inputs such as TESS (Transiting Exoplanet Survey Satellite) – prohibiting data synthesis, and thus extrapolatory analysis. Python via JupyterLab was used to develop an initial basic transit model and light curve simulation. Further implementation of limb-darkening, tangential atmospheric gradients, direct source input from TESS for planetary system parameters (radii, orbital periods, temperature, distances), and system blurring (to account for finite resolutions) refined the precision of the program. This model was then calibrated against known TESS light-curves and models and shown to be accurate. Data was then synthesized to mimic the appearance of an exoplanet with a reflective debris cloud (possessing artificial alloys and silicates), and a new light curve was generated – with infinite resolution, a minute difference to the known TESS curve was detectable. However because of maximum current telescopic resolution abilities, the differences are indistinguishable.
