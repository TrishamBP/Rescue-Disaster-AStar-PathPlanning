<div align="center">
  <h3 align="center">A* Path Planning for Disaster Rescue Operations</h3>
</div>
<!-- Problem Statement -->
## Problem Statement
In disaster response scenarios, efficient allocation and distribution of essential supplies such as food, water, and medicines to flood-affected areas are crucial for mitigating human suffering and facilitating recovery efforts. Given a map of flooded areas within the city of Chennai, marked as vertices in a graph, and equipped with an autonomous battery-operated micro aquatic boat capable of detecting flooded regions and responding to distress signals, the challenge is to devise an optimal path that covers all affected areas while minimizing energy consumption and travel time.

The primary objective of this research is to develop a path planning algorithm tailored for autonomous relief operations in flood-stricken regions. The algorithm must ensure that the autonomous boat traverses each road (edge in the graph) exactly once, covering all flooded areas to fulfill the supply needs of the affected population. Additionally, the algorithm should optimize the path to minimize the total distance traveled and maximize resource delivery efficiency, considering the limited battery capacity of the autonomous boat.

This research addresses the critical need for efficient and effective resource allocation in disaster response efforts by providing a novel approach to path planning in flooded areas. By optimizing the route taken by the autonomous boat, the proposed algorithm aims to enhance the speed and efficacy of relief operations, ultimately aiding in the timely delivery of essential supplies to those in need and minimizing the impact of natural disasters on affected communities.

### Map of Chennai
![image](https://github.com/TrishamBP/Rescue-Disaster-AStar-PathPlanning/assets/91331117/9e763c59-b2f1-455c-8a1c-bce044ebf559)

<!-- PEAS -->
## PEAS (Performance Measure, Environment, Actuators and Sensors)
### Performance Measure
This specifies the criteria for evaluating the PSA's success in addressing the needs of flooded areas while considering the constraint that all nodes can be traversed multiple times but edges are covered only once. It could include metrics such as the number of people assisted, the time taken to reach affected areas while adhering to this constraint, and the effectiveness of resource distribution in optimizing battery usage and minimizing redundancy in path traversal i.e. traveserinsg the edges only once but can cover many nodes/cities.
### Environment
* City of Chennai - The environment in which the autonomous battery-operated micro aquatic boat operates is centered around the city of Chennai during a period of flooding.
* Map Representation: In this scenario, certain areas of the city have been affected by flooding due to natural disasters like heavy rainfall or cyclones. These flooded areas are depicted as vertices on a graph, with each vertex representing a specific location within the city where assistance may be required, such as residential neighborhoods, streets, or landmarks.
* Graph Structure: The flooded areas are connected by edges, representing the roads or pathways between them. The graph is undirected since the roads can be traversed in both directions.
* Agent's Abilities: The agent is an autonomous battery-operated micro aquatic boat capable of navigating through flooded areas. It operates on battery power and is equipped with sensors to detect flooded regions and people waving for help.
* Battery Constraint: Since the agent operates on battery power, it needs to plan its route efficiently to cover all the flooded areas while conserving battery life. The shortest route that covers all roads only once is desired to optimize energy consumption.
* Sensing and Response: The agent's sensors detect flooded areas and people waving for help. It responds to signals from people in distress by approaching them to provide aid or assistance.
* Path Planning: The agent's objective is to find the shortest path that covers all the flooded areas (vertices) while traversing each road (edge) only once.
* Communication: The agent communicates with the central control or human operators to report its current location, the path it has taken, and locations where people are requesting help.
### Actuators
The actuators of the PSA are the mechanisms through which it interacts with its environment. In this case, they include the boat's navigation system for traversing flooded areas and its communication system for responding to distress signals.
### Sensors
Sensors enable the PSA to perceive and gather information about its environment. This includes sensors for detecting flooded areas, identifying distressed individuals waving for help, and monitoring battery levels.
