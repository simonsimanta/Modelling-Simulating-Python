# Modelling-Simulating-Python
Modelling, Simulating and Optimisating train plans for the HS2 line from London to Birmingham

Problem Statement
Simulating and optimising the London-Birmingham section of the high-speed line to decide on number of signalling blocks and trains running per hour.

The Context
Train information
The HS2 line connecting London and Birmingham has planned to operate high-speed train with the following features:

Acceleration: 0.72m/s**2 (approx same as commuter train)
Emmergency deceleration: 2.5m/s**2
Optimal deceleration: 0.36m/s**2
Max. travelling speed: 83.3m/s
Time taken to accelerate to maximum speed is 115.7s travelling 4,820m.
At optimal decelaration it takes 231.4s to travel 9,640m.
Signaling blocks
The railway line consists of sequential signaling blocks.A train enters a block only if there is no other train. The entry singal is green when there is no train in the block and turns red with entry of a train. The signal switches to green post 5 sec exit of the train end.
