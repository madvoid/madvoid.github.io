---
layout: page
title: PhD Projects
permalink: /projects/phd/
---

# PhD Projects

My PhD was split into three main tasks. Each task is outlined below, along with the skills and lessons it taught me.

## Low Cost Weather Stations

In boundary layer meteorology, the standard experimental practice is to deploy a small amount of large, expensive towers. However, the advent of wireless sensor networks and open-source microelectronics means that many, small, inexpensive sensor stations can be deployed instead. However, these low-cost microelectronics and open-source tools were not evaluated in the literature, so I designed and built a sensor station system and evaluated it as my first task. 

Called the Low-cost Energy-budget Measurement Stations (LEMS), I designed these sensor stations to measure various environmental variables at a fraction of the cost of existing equipment. The stations have been deployed for several field experiments, across multiple terrains, climates, and countries. The data from the stations have been used for multiple scientific publications.

 This process involved part selection, microcontroller programming, circuit design, PCB design, and manufacturing. I learned many things during this process, the most important being project management and documentation. Since I was in charge of the entire design process, but other researchers had to use the stations I designed, it was important to make sure everything was organized and that people could understand my work. The hardware and software for this project are open source, and can be found on my Github page [here](https://github.com/madvoid/LEMSv2). The article itself can be found [here](http://iopscience.iop.org/article/10.1088/1361-6501/aa97fb/meta).

![LEMS_PCB](/images/LEMS_PCB.png)

## Nowcasting Environmental Variables in Complex Terrain

 When conducting boundary layer meteorology field experiments, it is often common to deploy many temporary sensors amongst permanent sensors. After the field experiment is over, the temporary sensors are removed, leaving only the permanent sensors. If a researcher wants to continue to monitor the area after a field experiment, it is useful for them to be able to predict the environmental variables at the locations that the temporary sensors inhabited, even though they are not there anymore. Using the permanent sensors and the technique of [nowcasting](https://en.wikipedia.org/wiki/Nowcasting), researchers can predict the environmental variables at any given weather station using the data from other weather stations. This technique can also be used for data cleaning or gap filling.

For my second task, I show that this is possible in highly complex terrain on small spatial scales (< ~1km). I performed all nowcasting with artificial neural networks and standard linear regression models. This process involved data cleaning, statistics and machine learning, Matlab programming, and data visualization. Much of what I know about neural networks was learned during this project. The paper is in preparation right now, and a link will be posted once it is available.

## Contaminant Source Term Estimation

My third task involves source term estimation. In the event of a contaminant release into the atmosphere (chemical spill, terrorist attack, etc.), it is vital for emergency responders to find the source and strength of the contaminant source. Doing this automatically is called [source term estimation](https://narac.llnl.gov/research-and-development/source-term-estimation). Source term estimation has been successfully completed in a simple environment with steady-state meteorological conditions. However, it is much harder in a non-steady-state complex environment. My research serves to develop an algorithm that will work in such an environment. This algorithm will depend on autonomous drones with concentration sensors on it to do the "finding". This research is still in progress and a link to the paper will be posted once it is available.

![PSO_Hestia_Run3](/images/PSO_Hestia_Run3.gif)





