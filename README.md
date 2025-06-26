MST-Bio-Celegans-Project
CSAI335 Mini-Project: MST Algorithms on Biological Networks

Project Summary
In this project, we tested and compared five different Minimum Spanning Tree (MST) algorithms using real biological networks. We used datasets based on the neural structure of a worm called C. elegans, along with some larger networks like gene interactions in humans.

The goal was to see how each algorithm performs, how fast they are, and how they build the MST step-by-step.

Datasets Used
We used five datasets that vary in size and complexity:

bio-CE-GT – original C. elegans neural graph

bio-CE-GN – another version of the C. elegans dataset

bio-WormNet-v3 – worm gene interaction network

bio-Human-Gene1 – human gene interaction network

bio-celegans.mtx – matrix file for the C. elegans graph

These networks are useful because they are real-world and test how the algorithms scale on different sizes.

Algorithms We Used
Here’s a quick explanation of each algorithm we tested:

Kruskal’s Algorithm
Sorts all the edges by weight and adds the smallest ones that don’t form a cycle. Good for sparse graphs.

Prim’s Algorithm
Starts from one node and always connects to the nearest neighbor that’s not in the tree yet.

Borůvka’s Algorithm
Each node (or part) picks the cheapest edge to connect with another part. Repeats until everything is connected.

Reverse-Delete Algorithm
Starts with all edges and removes the biggest ones if the graph stays connected. Slower but simple.

Karger’s Algorithm
This one doesn’t give an MST. It randomly merges nodes and gives a minimum cut — the smallest set of edges that split the graph into two parts.

Videos and Code Links
We created videos that show how each algorithm builds the MST step-by-step. We saved a frame every 50 or 100 edges so it’s easier to follow the process visually.

DATASET 1 
https://drive.google.com/drive/folders/1YAAQqn3oZ0bmL7RGd_RA_tiSGUGrPbMs?usp=drive_link

DATASET 2
https://drive.google.com/drive/folders/1AJoxipjR-vKs3dH0UDNftoL3IfYiz2pk?usp=drive_link

DATASET 3
https://drive.google.com/drive/folders/1hKSmMBib6jEOU12XW09Yh5PkMUM-jgsW?usp=drive_link

DATASET4
https://drive.google.com/drive/folders/1JIN-1KjaPgIm3n9fM3XDUd-Q2g01rZt0?usp=drive_link

DATASET5
https://drive.google.com/drive/folders/1-3891Np55ZPpvU9GUYMTJcajBzRmKpsC?usp=drive_link

What We Found
We ran all algorithms on each dataset and measured how long they took.

Prim’s Algorithm was usually the fastest.

Borůvka was okay on small graphs but got slower on big ones.

Karger’s Algorithm worked differently — it gave the minimum cut, not a tree.

We also made line plots to show how the time increased as the dataset size got bigger.

Tools We Used
Python in Google Colab

NetworkX (for graph stuff)

SciPy and NumPy

Matplotlib (for charts and video animations)

Team Members
This project was done by:

Abeya Mahmoud

Zeina Helali

Jodie Ehab

Amira Farag

Noura El Haywan

Course: CSAI335 — Spring 2025 — New giza University

