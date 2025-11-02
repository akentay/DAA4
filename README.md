# 🌿 Minimum Spanning Tree — Prim & Kruskal

**Student:** Аида Кентай  
**Group:** SE - 2428 
**Language:** Java (Maven)  


---

## Project Goal
This project implements two classic algorithms to find the **Minimum Spanning Tree (MST)** in a weighted undirected graph:

- **Prim’s Algorithm** — grows a tree from one starting node using a **priority queue (heap)**.  
- **Kruskal’s Algorithm** — sorts all edges by weight and connects components using **Union-Find**.

Both algorithms are compared by **total cost**, **execution time**, and **operation counters**.

---


---

## Functionality Overview

- `Graph` & `Edge` — data structures for graph representation.  
- `PrimAlgorithm` — MST using a **heap (priority queue)**.  
- `KruskalAlgorithm` — MST using **Union-Find (Disjoint Set)**.  
- `MetricsCollector` — tracks execution time and operation counts.  
- `MSTResult` — stores MST edges, total cost, and metrics.  
- `Main.java` — runs both algorithms, compares results, and exports them as JSON and CSV.

---

## How to Run the Project

### Requirements
- **Java 17 or higher**  
- **Maven** installed (`mvn -v` to check)

### Commands

**Build the project:**
```bash
mvn clean install

