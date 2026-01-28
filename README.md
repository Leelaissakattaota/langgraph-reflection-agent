# 🤖 LangGraph Reflection Agent: Self-Improving AI

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-000000?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/IBM%20WatsonX-052FAD?style=for-the-badge&logo=ibm&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Iterative%20AI-FF6F61?style=for-the-badge&logo=ai&logoColor=white" />
</p>

## 🌟 Overview
This project demonstrates the power of **Reflection Agents** built using **LangGraph**. Unlike standard one-shot LLM responses, this agent uses a "System 2" thinking approach: it generates content, critiques it, and iteratively refines it until a high-quality output is achieved.

Specifically, this agent is designed to generate **Optimized LinkedIn Posts** by simulating a feedback loop between a "Creator" and a "Strategist."

---

## 🧠 How it Works (The Graph)
The workflow is structured as a state-based graph:

1.  **Generate Node**: Produces an initial draft.
2.  **Reflect Node**: Acts as a professional strategist, providing structured feedback and actionable critiques.
3.  **Conditional Router**: Decides if the post needs more refinement or if it's ready to be finalized based on message count.


---

## 🛠️ Tech Stack
- **Framework:** [LangGraph](https://python.langchain.com/docs/langgraph)
- **LLM Provider:** [IBM WatsonX](https://www.ibm.com/watsonx) (Granite-3-3-8b)
- **Orchestration:** LangChain
- **Visualization:** PyGraphviz

---

## 🚀 Key Features
- ✅ **Self-Correction:** The agent identifies its own weaknesses in tone, engagement, and structure.
- ✅ **State Management:** Uses `MessageGraph` to maintain conversation history across iterations.
- ✅ **Customizable Logic:** Conditional edges prevent infinite loops by capping iterations.

## 📝 Example Output
> **Initial:** "I got a job at IBM!"
> 
> **Refined:** "🎉 Thrilled to join IBM as a Software Developer! Bringing my Java prowess from [Experience] to collaborate on pioneering projects. Let's connect and share growth stories! #NewJob #IBM #CareerEvolution"

---

## 📁 Repository Structure
- `Building_a_Reflection_Agent.ipynb`: Complete implementation and lab notes.
- `README.md`: Project documentation.

---
*Created as part of the IBM Skills Network Guided Project.*
