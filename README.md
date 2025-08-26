# Marvel Social Network

This project explores the Marvel Universe as a social network.  
**Nodes** represent characters, and **edges** represent co-appearances in the same comic issue.

This project is part of my data science portfolio and demonstrates how network analysis can uncover insights from relational data.

The goal is to use network analysis to answer questions such as:
- Which characters are the most central or well-connected?  
- Who acts as a bridge between otherwise separate teams?  
- Do detected communities align with groups like the Avengers or X-Men?  
- What does the overall structure of the Marvel universe look like when visualized?  

---

## Project Structure
- `data/` → dataset (heroes, comics, edges)  
- `notebooks/` → Jupyter notebooks for exploration + analysis  
- `src/` → planned reusable functions/scripts  
- `outputs/` → results, metrics, and visualizations  
- `README.md` → project documentation  

---

## Tools
- **pandas** – data handling  
- **networkx** – graph construction + centrality metrics  
- **community-louvain** – community detection  
- **pyvis** – interactive visualization  
- **matplotlib** – plots and charts  

---

## Next Steps 
- Build bipartite and projected graphs  
- Run centrality metrics (degree, betweenness, eigenvector)  
- Detect communities with Louvain clustering  
- Create an interactive visualization (PyVis)  
- Document early findings and insights