# Accelerated-testing-plan-for-autonomous-vehicles

Homework description

You are tasked of developing a test plan for a L4 autonomous driving system. 
Let’s assume we want to deploy our product in an urban area where the self-driving system is intended to operate safely. 
This area of operation is usually described by the Operational Design Domain, which is defined like this:
“The specific conditions under which a given driving automation system or feature thereof is designed to function. 
An ODD may include geographic, roadway, environmental, traffic, speed, actor and/or temporal conditions.” 
The ODD for this exercise is a loop around our office building in Munich. 
The start and end point is in front of the main entrance at Ungererstr. 69 in Munich. 
The self-driving vehicle (SV) is intended to conduct all necessary driving behaviors in the dedicated ODD. 
To limit the scope of this exercise we simplify the OOD and work with some operational constraints: 
- The SV is only intended to make right-turns to do the loop. 
- There are no passengers on-board, only a safety driver. 
- The SV is not intended to operate in inclement weather. 
- We assume that the speed limit is 30 kmh per hour the entire loop. 
- We assume that there are no traffic lights and construction zones present. 
- We assume that there are only Pedestrians, Bicyclists and normal mid-sized cars present. 

1. Task 1: In order to deploy the SV in an above (artificial) constrained environment we need to define test scenarios which cover the above ODD. In the first part of the homework please define a minimum of 10 scenarios which are specific to the ODD. Please use a similar standardized format as in the below example. For each scenario specify which self-driving functionality is tested. Example:  2 “The SV is approaching a X-intersection on a two-lane road where it must yield for traffic. The intersection is controlled by a yield sign. The SV intends to make a left turn. An oncoming car is approaching the intersection and intends to go straight ahead. The SV must enter the intersection and wait for the oncoming car to pass and clear the way for the SV to continue its path to conduct the left-turn.” 

2. Task 2: Develop a system level verification plan proposal to evaluate if our self-driving vehicle can be deployed in the above described ODD, given the operational constraints. a. Please think of 3 alternative approaches and lay down the advantages, disadvantages and feasibility of each of those approaches. Based on your assessment decide on one of these approaches. b. For the selected approach outline a suitable product verification plan. Please include concepts like product requirements, definition of done, quality metrics, testing etc. 
