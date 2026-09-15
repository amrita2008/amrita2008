<div align="center">

# Hi, I'm Amrita Vaish 👋

### Software Engineer

**Building intelligent systems, agentic workflows, and real-world AI products.**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amrita2008)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](YOUR_LEETCODE_URL)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](YOUR_CODECHEF_URL)
[![Resume](https://img.shields.io/badge/Resume-Download-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](YOUR_RESUME_URL)

</div>

---

## 👩‍💻 About Me

B.Tech student at **IIIT Bhopal** focused on building production-oriented software and AI systems.

My work spans:

- 🤖 Generative AI & Agentic AI
- 🧠 Machine Learning & Deep Learning
- 🔎 RAG, Embeddings & Semantic Search
- 🕸️ Multi-Agent Systems
- ⚙️ Backend & API Engineering
- 💻 Full-Stack Development

I enjoy turning AI capabilities into **reliable, deployable software systems** with proper APIs, databases, validation, testing, and user workflows.

---

# 🚀 Featured Projects

## 🛡️ KAVACH AI
### Sovereign Industrial AI Workbench

**PROJECT**  
Local-first AI workbench for sensitive industrial workflows, combining **agent orchestration, multimodal document analysis, OCR, RAG, local LLMs, code execution, and human approval**.

**STACK**  
`Python` · `Ollama` · `Qwen2.5` · `Qwen2.5-VL` · `ChromaDB` · `RAG` · `OCR`

**IMPACT**  
Enables AI-assisted analysis and automation while keeping sensitive data inside a controlled environment.

### Architecture

```mermaid
flowchart LR

    U[User] --> K[KAVACH AI]

    K --> A[Agent Orchestrator]
    A --> P[Planning]

    P --> D[Document Intelligence]
    P --> V[Vision + OCR]
    P --> R[RAG]
    P --> C[Code Execution]

    D --> M[Local AI Models]
    V --> M
    R --> M

    C --> S[Sandbox]

    M --> X[Self Verification]
    S --> X

    X --> H{Human Approval}

    H -->|Approve| O[Deliverable]
    H -->|Revise| A
