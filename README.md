# pedestriancrossing-sumo
# Introduction
An example for building a pedestrian-actuated traffic light via Sumo's TraCI
The project contains pedestrians trips.
The scenario consists of a single road which is crossed by a footpath. The crossing is controlled by a traffic light and should switch when triggered by the pedestrians via push-button. To model the button-pushing behavior, it is assumed that a pedestrian which arrives at a red light activates the button if it is not yet activated. To prevent undue interference with vehicular traffic, there is a minimum green duration of 15 seconds for the vehicular green phase.
