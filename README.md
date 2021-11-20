# pedestriancrossing-sumo
# Introduction
An example for building a pedestrian-actuated traffic light via Sumo's TraCI
The project contains pedestrians trips.
The scenario consists of a single road which is crossed by a footpath. The crossing is controlled by a traffic light and should switch when triggered by the pedestrians via push-button. To model the button-pushing behavior, it is assumed that a pedestrian which arrives at a red light activates the button if it is not yet activated. To prevent undue interference with vehicular traffic, there is a minimum green duration of 15 seconds for the vehicular green phase.
# RUNNING IT
You'd need to execute the python script runner.py
This would open your sumo simulator.
![sumo](https://user-images.githubusercontent.com/42734825/142742740-17d62d81-670f-48ab-baaa-4b8f30d41153.png)

## Press Start to start the run the simulation.

![sumo3](https://user-images.githubusercontent.com/42734825/142742829-8b5c0577-7438-4217-93af-8c8138fdf27d.png)

If you the python script returns the error "please declare environment variable 'SUMO_HOME'",
Run the code SUMO_HOME=/thepathofyour sumo, example export SUMO_HOME=/usr/share/sumo/. Please note that the code above is for linux environment. Declaring environment variable for window swould be different.
