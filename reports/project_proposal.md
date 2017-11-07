# Optimization by Cooperating Agents *a la* Ant

Duncan Hall


##### Abstract:

This project will involve implementation of an agent-based model of path discovery in which agents preferentially choose edges which have been more heavily traveled. These agents replicate ants leaving pheromones for other ants to sense, establishing a path to a target destination from a home, and once again back to the home. The model will then be adapted as done in Dorigo, Maniezzo, and Colorni (1996) to generate solutions for the traveling salesman problem. This will involve changes in the way the pheromone trail is established and in the agents themselves (adding a small amount of memory and foresight). In this way I will have began with a simple model of an organism and adapted it to the specific needs of path finding problems.

The experiments run will be presented initially in a text output with relative pheromone levels of all edges displayed once the path has been established. I would like to do some basic animation of the time steps to supplement this however by creating animations with edges changing thickness and/or color as pheromone is produced/decays. This animation will be immediately applicable to the second phase of the project where I adapt the agent behavior for traveling salesman path finding. I will also examine how quickly the shortest path is established and how that depends on specific parameters (pheromone decay rate, pheromone bias, random noise in choosing paths etc.).

My greatest concern is that figuring out how to create an animated graph will take too much time.

To get this project underway, I will begin with a basic network generation function, agent class, and a script to run the initial simple simulation of path finding between two points.