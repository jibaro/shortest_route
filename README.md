# shortest_route

This is a solution to the shortest route problem, using network routing algorithms in transport networks.

## Description
With the development of technology and the evolution of societies, more and more people are using a passenger car, which, combined with the urbanization of the modern times, results in traffic congestion and long delay in passenger movement, especially in large urban centers. Thus, in the context of Intelligent Transport Systems (ITS) and aiming at traffic decongestion, in this project a Java and JavaScript application has been developed, that implement network routing algorithms in transport networks to find the shortest route. More specifically, the communication technologies used in ITS, network routing algorithms and protocols were studied and the Dijkstra and Bellman-Ford algorithms were used to develop the application. The algorithms are applied to a graph representing a part of the road network, that is roads are considered as the links and lanterns as the nodes of the graph and the weight of the links indicates the traffic factor that has a road at that moment. The user can select the initial node in which is located, and the system calculates and displays the shortest path to certain specific destinations (e.g. airport, bus station, central points, etc.) defined by the administrator. Βoth projects were implemented for the area of the center of Thessaloniki.

## Desktop Application

This implementation is more useful to the system administrator. In this case the map is static and shows a specific area, which has been pre-selected by the program. Τhe nodes are inserted by the administrator in the constellation and coordinate files. The advantage of this application is that the administrator can very easily edit the graph and perform tests.

### How to run

* To run Bellman-Ford you will need JavaFX. You can find it [here](https://gluonhq.com/products/javafx/ "JavaFX").
  For Eclipse IDE you can just 1)Go to Help, 2)Go to Eclipse MarketPlace, 3)Search e(fx)clipse and 4)Install it. Then, to add it on the project just follow: Java Build Path > Libraries > Add Libraries > JavaFx SDK
* Download a project and import as an existing project into your IDE.
* Run Main class.


