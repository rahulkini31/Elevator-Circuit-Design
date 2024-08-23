# elevator_design
Elevator Simulink and Arduino Design

# Features

Requests can be made from the inside lift, or from floors (with options to request for going up and going down). The requests are handled in the most optimized way, i.e. 
If the elevator is on floor 0, and floor 2 makes the request, and while going to floor 2, if a request comes from floor 1 to go up, or from inside the lift, then the lift makes a stop at floor 1, if the request comes from floor 1 to go down, then first it goes to floor 2, and if there is no more request for going up, then it comes to floor 1.
