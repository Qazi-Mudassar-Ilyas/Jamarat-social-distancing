WHAT IS IT?
===========
We propose a pedestrian simulation model to analyze the impact of social distancing on the stoning ritual of the Islamic pilgrimage. The simulation model analyzes the impact of inter-queue and intra-queue spacing between adjacent pilgrims on the throughput and congestion during the stoning ritual. 
The NetLogo simulation environment is required to run the simulation model (https://ccl.northwestern.edu/netlogo/).

HOW IT WORKS
=============
A reader may refer to the following research paper for model assumptions, locomotion, social distancing, and the stoning components of the proposed model.
 
Q. M. Ilyas, M. Ahmad, N. Z. Jhanjhi and M. B. Ahmad, "Analyzing the Impact of Social Distancing on the Stoning Ritual of the Islamic Pilgrimage," KSII Transactions on Internet and Information Systems, vol. 16, no. 6, pp. 1953-1972, 2022. DOI: 10.3837/tiis.2022.06.010. http://itiis.org/journals/tiis/digital-library/25763

HOW TO USE IT
=============
Please make sure that you have copied the "jamarah.png" file in the same folder as that of the model file. 
Use interface controls to set the simulation parameters (desired number of pilgrims for the simulation, inter-queue and intra-queue spacing, and time to perform the stoning ritual). 
Remember to enable the "Write-output-To-File" if you want to use the simulation results. If enabled, an "output.csv" file will be created in the model folder with the values required to calculate congestion and throughput after every ten ticks. Keep the setting disabled for improved performance if you do not intend to use the results of the simulation. 

EXTENDING THE MODEL
====================
The proposed model uses simple heuristics for movement and collision avoidance of pilgrims. The other researchers may improve these heuristics to propose advanced locomotion and stoning models. We also need to consider the emotions of pilgrims (such as fear, anxiety, confusion, and directional focus), groups, diverse cultures of pilgrims, wheelchairs, and special characteristics of pilgrims (such as demography, education level, the experience of performing pilgrimage, gender, and age). Finally, we have modeled only one level of the Jamarat bridge. A more comprehensive model is required to simulate all six levels of the bridge. 

KNOWN ISSUES
=============
A small number of pilgrims (<0.001%) may get stuck with the walls during the simulation. We could not locate the bug and ignored the issue because of an insignificant impact on the results. Please keep an eye on the "total pilgrims" monitor and stop the simulation run manually if you observe this issue. 

CREDITS AND REFERENCES
======================
Q. M. Ilyas, M. Ahmad, N. Z. Jhanjhi and M. B. Ahmad, "Analyzing the Impact of Social Distancing on the Stoning Ritual of the Islamic Pilgrimage," KSII Transactions on Internet and Information Systems, vol. 16, no. 6, pp. 1953-1972, 2022. DOI: 10.3837/tiis.2022.06.010. http://itiis.org/journals/tiis/digital-library/25763
