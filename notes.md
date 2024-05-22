1) For a height of 1km, 
Time taken for echo = 1000 / 343 * 2
Which is more than 4 seconds
So horizontal displacement in this time is too big to ignore

Assumptions:
1) The radius of view of the ultrasound sensor is short, so we don't get interference from the sides of the buildings
2) The simulator need not consider the horizontal displacement, as data is random data anyway

graph the data that you see

Intentionally ignoring the specifics of setups and reads for electronics sensors. We can rather learn it while working with actual electronics

Data generated at 1m/s

Maybe make the drone land at the end?

Tasks to complete:
1) Lattitude-Longitude data to follow actual coordinate system (check NavIC and GPS accuracies too) - how is location actually measured in drones? CV?
2) Add longitude to the location. Accordingly generate 3D data by fusing two 2D paths (side plane and top plane). Interpolate this appropriately
3) Multiple test cases to be present - draw images accordingly - multiple topologies - mix and match paths and topologies - different topologies like slanted roof tops
4) OS commands for file handling multiples
5) Hosting? Since there is an artificial delay, we have to self host. Appropriate method to swap test cases (data files)?
6) Result validation - implement for all of the objectives
7) Document this - YouTube video? website post?
8) Publish it - Others learning Arduino should also be able to use
