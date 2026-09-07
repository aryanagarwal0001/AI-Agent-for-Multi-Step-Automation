# AI-Agent-for-Multi-Step-Automation

##  Overview
This project demonstrates an AI agent built with LangChain that can orchestrate multiple tools to perform complex workflows. The agent integrates web search and calculation functions, enabling it to handle tasks like retrieving information, analyzing results, and performing computations in a single pipeline.

---

##  Tech Stack
- LangChain → Agent orchestration & tool integration  
- DuckDuckGoSearchAPIWrapper → Real‑time web search  
- Custom Calculator Function → Mathematical operations on retrieved data  

---

## Features
- Multi‑tool orchestration (search + compute)  
- Example workflow: “Find UK population and compute its square”  

---

-------------------IMPORTANT NOTE------------------------
- 1- Insert you own Google Api Key while creation of llm model.
- 2- You can remove the verbose = True field while crration of agent, if you just want to know the answer and not the reasoning behind it. 
