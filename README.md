<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&ColorList=0f0f0f,1c1c1c,d4af37,8b8000,f5f5f5&height=250&section=header&text=Social%20Graph%20Engine&fontSize=40&fontColor=0f2027&animation=fadeIn&fontAlignY=35&desc=GraphBased%20Recommendation%20Backend%20%7C%20Triadic%20Closure%20Algorithms&descAlignY=60&descAlign=50" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=25&pause=1000&color=00f2ea&center=true&vCenter=true&width=600&lines=Mapping+User+Topology...;Calculating+Edge+Weights...;Identifying+Triadic+Closures...;RECOMMENDATION+GENERATED."/>
</div>

<br/>

<div align="center">
  <a href="https://github.com/Abu-Sameer-66">
    <img src="https://img.shields.io/badge/Algorithm-Graph_Theory-00f2ea?style=for-the-badge&logo=googleanalytics&logoColor=black"/>
  </a>
  <a href="https://github.com/Abu-Sameer-66">
    <img src="https://img.shields.io/badge/Python-3.9+-ff0050?style=for-the-badge&logo=python&logoColor=white"/>
  </a>
  <a href="https://github.com/Abu-Sameer-66">
    <img src="https://img.shields.io/badge/ETL_Pipeline-Optimized-success?style=for-the-badge"/>
  </a>
</div>

---

## 🕸️ System Overview
> **A high-performance Graph Recommendation Engine designed to analyze user connection topology and predict meaningful interactions.**

Social networks rely on hidden patterns. This project moves beyond simple SQL queries to use **Graph Theory** concepts (like *Triadic Closure* and *Jaccard Similarity*) to answer the question: **"Who should you know?"**

It ingests raw, unstructured JSON logs and transforms them into a structured **Edge-List Matrix** for algorithmic processing.

---

## 🧬 Algorithmic Logic
*Visualizing the Recommendation Pipeline:*

```mermaid
graph LR
    A[📂 Raw JSON Logs] -->|ETL Parsing| B(Node & Edge Extraction)
    B -->|Matrix Construction| C{Graph Topology}
    C -->|Algo 1| D[Triadic Closure]
    C -->|Algo 2| E[Common Neighbors]
    D & E -->|Weighting| F[Similarity Score]
    F --> G[🚀 Recommendation Output]
    style C fill:#00f2ea,stroke:#ff0050,stroke-width:2px,color:#000
    style G fill:#ff0050,stroke:#00f2ea,stroke-width:2px,color:#fff
