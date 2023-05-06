# Ford-Fulkerson Algorithm

## What is Ford-Fulkerson Algorithm ?

> Well, this algorithm is a greedy approach for calculating the maximum possible flow in a network or a graph and it is used to find the max flow problem in flow network.

### 😳  What the hell does Flow in Network (Flow Network) and Maximum Flow mean ?

- It is term used to describe e network of vertices ( tamoqning uchlari ) and the edges with a source of (S) and sink (T). To make it simple, **Maximum Flow** is maximum amount of something that you can move from starting node to ending node.

## Flow Network Example Graph :

![](../Data%20/Flow-Network.png)

> Here, the **S** will be our Source and the **T** will be our Sink. When we start to calculate the maximum flow in the graph, we set the Sink (T) to 0 ( as a default ).

### Number on the Left and Right :

![](../Data%20/Left%20and%20Right.png)

- Below picture is the last iteration of the searching for the path. As we can see form the graph, there is bottleneck capacity from C to D ( which is 3 ) and the flow is augmented by applying the possible capacity to the in and out nodes as **equilibrium**

**🤔 What the hell nodes as equilibrium mean ?**

> Well, each node after augmenting the flow, the node must be **equilibrium** meaning that the flow into the node must be equal to the flow out of the node.

![](../Data%20/Equilibrium.png)

### Final Wrap-ups of the Ford-Fulkerson Algorithm:

> ✈️ This Algorithm follows the below rules to find the maximum flow of the Sink in the flow network or graph. Clearly, in each iteration, we have to do a **Depth-First Search (DFS)** which has time complexity of **Big O e.**

Let’s you want to find the maximum number of the flow iterations in the graph and by just counting the total flow value, will gives us the end result 😄.

![](../Data%20/Wrap-up.png)

📎 **Reference:**

| Article or Blog Title                 | Link Url                                               |
| ------------------------------------- | ------------------------------------------------------ |
| Ford-Fulkerson in 5 minutes - Youtube | https://www.youtube.com/watch?v=Tl90tNtKvxs            |
| Ford-Fulkerson Algorithm - Programiz  | https://www.programiz.com/dsa/ford-fulkerson-algorithm |
