# Graph Resilience Analysis  

This project investigates how **edge failures** affect **connectivity** and **node centrality** in weighted, undirected networks.  

We analyze two types of edge failures:  
- **Edge betweenness-based failures**  
- **Edge weight-based failures**  

Both methods apply **min-max** and **sum normalization** to determine failure probabilities.  

### **Analysis Focus**  
The study examines:  
- The **perturbation** in the adjacency matrix.  
- The **deformation** of node centrality vectors, including:  
  - **Degree centrality**  
  - **Katz centrality**  
  - **Eigenvector centrality**  

### **Project Structure**  
- *`networks/`* – Contains the networks examined.  
- Other folders store the generated **plots**.  

### **Implementation**  
Implemented using **[NetworkX](https://networkx.org/)**.
