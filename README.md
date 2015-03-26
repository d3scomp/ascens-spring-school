### EMobility Student Project Starter 
---
It consists of a sample projects which features a Vehicle component and their communication. A vehicle component 
has a given destination to go to. When it gets close to a destination, it chooses a place close-by where it can park. 
To know where it can park, it (a) monitors free parking spaces – as it passes by them, and (b) exchanges the information 
about free parking spaces with vehicles close-by.

The project has two launch configurations - one for running a simulation, the other for visualizing the results of the simulation.

To run them, simply import the project to Eclipse (for Java developers - http://www.eclipse.org/downloads/).  
The launch configurations are part of the project, thus corresponding run targets automatically appear in the Run configurations. Simply run the project by executing the run configuration.

To launch the visualization, follow these steps:
- Run the simulation to produce run logs
- Unpack the file <project>/matsim/ITERS/it.0/0.events.xml.gz (the file should become <project>/matsim/ITERS/it.0/0.events.xml)
- Run visualization via the launch target
- In the visualization, click File->Import Scene; select the file <project>/visualisation/config.txt in "Specify Configuration File" and click on "Load!", then click on OK.

A quick start to DEECo with explanation of its concepts can be found in the file "DEECo - Quick Start.pdf" in the root of the GIT repository.

More information about DEECo and jDEECo can be found at:

http://d3s.mff.cuni.cz/projects/components_and_services/deeco/
and
https://github.com/d3scomp/JDEECo
