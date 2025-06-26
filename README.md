MST-Bio-Celegans-Project
CSAI335 Mini-Project: MST Algorithms on Biological Networks
New Giza University – Spring 2025

 Project Summary
In this project, we tested and compared five different Minimum Spanning Tree (MST) algorithms using real biological networks. We used datasets based on the neural structure of a worm called C. elegans, along with larger networks like gene interactions in humans.

The goal was to see how each algorithm performs, how fast they are, and how they build the MST step by step.

 Datasets Used
We used five datasets of different sizes and complexities:

bio-CE-GT – original C. elegans neural graph

bio-CE-GN – another version of the C. elegans dataset

bio-WormNet-v3 – worm gene interaction network

bio-Human-Gene1 – human gene interaction network

bio-celegans.mtx – matrix format of the C. elegans network

These networks are real-world and are great for testing how algorithms perform at different scales.

 Algorithms We Used
1. Kruskal’s Algorithm
Sorts all edges by weight and adds the smallest ones that don’t form a cycle. Works well for sparse graphs.

2. Prim’s Algorithm
Starts from one node and always connects to the nearest unvisited neighbor.

3. Borůvka’s Algorithm
Each component picks the cheapest edge to connect to another one. Repeats until everything is connected.

4. Reverse-Delete Algorithm
Starts with all edges and removes the heaviest ones, only if the graph stays connected. Simple but slower.

5. Karger’s Algorithm
Does not build an MST. Instead, it contracts random edges and finds the minimum cut that splits the graph into two parts.

 MST Videos and Code Links
We created videos that show how each MST builds up step-by-step. A frame is saved every 50 or 100 edges to make the visual clear.

Dataset 1: bio-celegans.mtx

Dataset 2: bio-CE-GT

Dataset 3: bio-CE-GN

Dataset 4: bio-WormNet-v3

Dataset 5: bio-Human-Gene1

 What We Found
We tested each algorithm on every dataset and recorded the runtime.

Prim’s and kruskals algorithm were the best in practice .

Borůvka performed well on small datasets but slowed down on larger ones.

Karger’s Algorithm worked differently — it gave a minimum cut, not an MST.

Reeverse delete Algorithm was the worst as it was the slowest.

We also created line plots showing how the execution time increased as dataset size grew.

 Tools We Used
Python (Google Colab)

NetworkX (for graph structures)

SciPy and NumPy (for handling matrices and numbers)

Matplotlib (for charts and MST video animations)

 Team Members
This project was completed by:

Abeya Mahmoud

Zeina Helali

Jodie Ehab

Amira Farag

Noura El Haywan
