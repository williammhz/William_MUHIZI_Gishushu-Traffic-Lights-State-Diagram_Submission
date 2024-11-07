# William_MUHIZI_State_Diagram_Submission

This UML state diagram represents a traffic control system for Gishushu Traffic Lights with two vehicle flow directions. North-South (NS) and West-East (WE), it also includes pedestrian (PE) crossings in both directions. The system operates in a cycle to ensure the safe flow of vehicles and pedestrians.

The routes and intersections of these roads are: KG 17 Avenue (The road coming from Downtown - Kimihurura - Kacyiru), I used it as West Road.
						KN 5 Road (The road that continues to Kigali International Airport, passing through Remera), I used it as East Road.
                                                KG 7 Avenue (The road that heads to Nyarutarama - Gacuriro), I used it as North Road 
						KG 9 Avenue (The road that continues to some neighborhoods of Gikondo and Kicukiro), I used it as South Road

States and their descriptions:
NS Green, WE Red, Pedestrian WE Walk:

Vehicles traveling in the NS direction have a green light, allowing them to proceed.
Vehicles in the WE direction have a red light, requiring them to stop.
Pedestrians crossing in the WE direction have a “Walk” signal to cross safely.


NS Yellow, WE Red, Pedestrian WE Don’t Walk:

NS traffic light turns yellow, signaling vehicles in the NS direction to prepare to stop.
WE remains red, continuing to stop WE traffic.
WE pedestrian light changes to “Don’t Walk,” giving pedestrians time to clear the crosswalk before vehicles resume movement.


All Red, Pedestrian WE Don’t Walk:

All vehicle lights turn red briefly to ensure the intersection is cleared before allowing WE traffic to proceed.
WE pedestrian signal remains on “Don’t Walk.”


NS Red, WE Green, Pedestrian NS Walk:

Vehicles traveling in the WE direction receive a green light, allowing them to proceed.
Vehicles in the NS direction remain stopped with a red light.
Pedestrians crossing in the NS direction have a “Walk” signal to cross safely.


NS Red, WE Yellow, Pedestrian NS Don’t Walk:

WE light changes to yellow, signaling WE vehicles to prepare to stop.
NS remains red, keeping NS traffic stopped.
NS pedestrian light changes to “Don’t Walk,” allowing pedestrians time to clear the crosswalk.


All Red, Pedestrian NS Don’t Walk:

All vehicle lights turn red briefly to ensure the intersection is clear before the cycle resets.
NS pedestrian signal remains on “Don’t Walk.”

After, it loops back to the first/initial state NS Green, WE Red, Pedestrian WE Walk, keeping the system in a loop
