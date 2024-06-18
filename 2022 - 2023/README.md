# Years 2022 to 2023

## Center For Sustainable Software Engineering

### [TRACCC](https://github.com/CSC-HudUniv/traccc) and [ACTS (ACTS Common Tracking Software) ](https://github.com/CSC-HudUniv/acts)

I helped find block size issues in CUDA code of the project using Nvidia Nsight profiling tools with various block sizes to test performance.

A presentation showing these findings in an ACTS Parellization Meeting was done by Minsi Chen as shown [here](https://indico.cern.ch/event/1219021/contributions/5127841/attachments/2554195/4401080/MChen-profiling-traccc-cuda-code.pdf).

### [TRACCC Visualise](https://github.com/Yusuf-Manjra/GeomPlot)

I created a Command Line Python Application using the Visualisation ToolKit to render the data from the ATLAS particle collider.

The data had to be trimmed slightly to remove sections of events that occured in parts of the collider that were not on the model being used.
This data and trimming program can be found [here](https://github.com/Yusuf-Manjra/Placement-Work).

This visulisation used the data files from the collision event and a model file of the collider to create a visual representation of where the particles were detected, this was used to help understand the movements and velocities of each particle from the event.

### [SonarCloud](https://sonarcloud.io/organizations/yusuf-manjra/projects)

For both projects I created an automation system that built the projects with SonarCloud's scanner service on top.
This was done due to the large number of people working on it over its development leading to quite a few potential inefficiencies and potential inconsistencies.
The system gave us the ability to quickly find sections of code that were being repeated or common errors in the code that were created over time.