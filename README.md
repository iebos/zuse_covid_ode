# zuse_covid_ode
 
This repository contains the script for the challenge in covid_zuse_code_ib.ipynb as a jupyter notebook, which is accompanied with explanations and sources. The data that I used for comparison is in the file fallzahlen.csv. The source of the data is https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Daten/Fallzahlen_Kum_Tab.html.

In the script, I create simple SIR models to model the delta wave in autumn 2021, and attempt to include the first omicron wave for one region. After that, I showcase how a model can include two regions with a dependency while still being observed in isolation. The models manage to somewhat predict the peak of the waves, but are bad in predicting absolute cases and generally seem "polished" compared to the real world data. This is expected given that this is the simplest type of model with only three variables. Finally, I add ideas for improvement.
