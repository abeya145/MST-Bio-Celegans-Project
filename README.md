# MST-Bio-Celegans-Project
# 🧠 CSAI335 Mini-Project: MST Algorithms on a Biological Network

## 📘 Project Summary

This project is about using five different **Minimum Spanning Tree (MST)** algorithms to analyze a real biological network. We used the **bio-CE-GT** dataset, which is based on the neural connections of a roundworm called **C. elegans**.

MSTs help us find the shortest way to connect all points (nodes) in a network without making any loops, and with the least total weight.

---

## 🧬 About the Dataset

The **C. elegans** network shows how neurons are connected in a small worm. It's popular in science because it's one of the most complete neural maps we have.

### 🔍 Why It’s Useful:

- 🧠 Helps understand how brains and networks pass information  
- 🧬 Can be used in biology and bioinformatics  
- 🤖 Inspires AI and neural network designs  
- ⚙️ Good for testing algorithms on real-world systems  

---

## 🌲 MST Algorithms Used

Here’s a quick summary of the five algorithms I tested:

### 1. **Kruskal’s Algorithm**
- Sorts all edges by weight  
- Keeps adding the smallest edges that don’t make loops  
- Works well on sparse graphs

### 2. **Prim’s Algorithm**
- Starts from a node and grows the tree  
- Always connects to the nearest neighbor  
- Fast with heaps/priority queues

### 3. **Borůvka’s Algorithm**
- Every part of the graph picks its cheapest edge  
- All parts merge until one MST is left  
- Great for parallel computing

### 4. **Reverse-Delete Algorithm**
- Starts with all edges  
- Keeps removing the biggest ones if the graph stays connected  
- Simple but slower

### 5. **Karger’s Algorithm**
- Contracts edges randomly until only two nodes are left  
- Finds a **minimum cut**, not an MST  
- Good for estimating network partitions

---

## CODE AND VIDEOS OF DATASET 1 
https://drive.google.com/drive/folders/1YAAQqn3oZ0bmL7RGd_RA_tiSGUGrPbMs?usp=drive_link
## CODE AND VIDEOS OF DATASET 2
https://drive.google.com/drive/folders/1AJoxipjR-vKs3dH0UDNftoL3IfYiz2pk?usp=drive_link
## CODE AND VIDEOS OF DATASET 3
https://drive.google.com/drive/folders/1hKSmMBib6jEOU12XW09Yh5PkMUM-jgsW?usp=drive_link
## CODE AND VIDEOS OF DATASET 4

## CODE AND VIDEOS OF DATASET 5


## 📊 Performance Testing

I created graphs of different sizes and timed how long each algorithm took.

### ✅ Result:
**Prim’s Algorithm** was the fastest for the types of graphs we worked with (sparse and real-world-like).

---

## 🎥 MST Visual Videos

I made videos that show how each MST builds up step-by-step:
- One edge is added every 50 steps
- It’s easier to see how the tree forms visually

---

## 🛠️ Tools I Used

- Python (Google Colab)
- NetworkX
- NumPy & SciPy
- Matplotlib for charts and animations

---

## 👤 About Me

This project was done by **[ABEYA MAHMOUD]**, a student in **CSAI335 at NGU, Spring 2025**.

