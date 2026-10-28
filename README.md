# Hi, I'm Davi! 👋

I'm an engineering student at **Télécom Paris (Institut Polytechnique de Paris)**, pursuing a double degree with the **University of São Paulo (USP)**.

I'm interested in **Artificial Intelligence, Machine Learning, Data Science, and Software Engineering**, particularly at the intersection of mathematical foundations and practical implementations.


## 🚧 Currently building

### [oarp — Observable Agentic RAG Platform](https://github.com/DaviCoelh0/oarp)

**Python · LangGraph · LLM Agents · Docker · Information Retrieval** · *ongoing*

A Python platform for **building, evaluating, and optimizing tool-using LLM agents**. I'm exploring a practical research question: **when is additional retrieval work worth its cost?**

The platform combines bounded agent execution, structured tracing, independent verification, and reproducible, cost-aware experiments.

- **Agent infrastructure:** Built a provider-neutral harness with configurable tool budgets, execution tracing, cost accounting, and **609 passing tests**.
- **Coding environment:** Implemented a Python bug-fixing agent with network-isolated Docker execution, editable-file restrictions, and independent public/hidden-test verification.
- **Retrieval environment:** Developed a **LangGraph search agent** that decides whether and what to search within harness-enforced limits, alongside BM25 and LLM reranking baselines.
- **Harness optimization:** Evaluated **1,089 routing configurations** offline, with the model fixed, to determine when to use BM25, reranking, or agentic search.

**Results on 300 held-out BEIR SciFact queries (nDCG@10):**

| BM25 | LLM reranking | Search agent | Selected routing policy |
|:---:|:---:|:---:|:---:|
| 0.662 | 0.757 | **0.791** | **0.786** |

The development-selected policy **beat LLM reranking by +0.030 nDCG@10** (95% CI [+0.014, +0.048]) on held-out queries, at **49% of the full agent's estimated API cost**.

The policy's pre-specified non-inferiority margin against the full agent was **not established**. Results are from one benchmark and one model (Claude Haiku 5.5); configuration search is bounded and offline, not autonomous self-improvement.

[**Explore the project →**](https://github.com/DaviCoelh0/oarp) · [**Read the held-out evaluation →**](https://github.com/DaviCoelh0/oarp/blob/main/experiments/retrieval_heldout/README.md)

## 🚀 Selected projects

### [PICI — Partially Identifiable Causal Inference](https://github.com/c2d-usp/pici)

**Python · Causal Inference · Optimization**

A Python library for causal inference in structural causal models, capable of identifying causal effects or computing bounds when exact identification is not possible.

The library supports multiple identifiability criteria and optimization-based inference methods. I contributed to its development, documentation, testing, examples, and project website.

### [Interface Solver — Causal Inference Framework](https://github.com/Causal-Inference-Group-C4AI/interface-solver)

**Python · Docker · Causal Inference**

A modular framework for running and benchmarking causal inference algorithms in reproducible environments.

Integrates libraries such as DoWhy, bcause, LCN, and Autobounds. I worked on Docker-based orchestration, solver integration, inter-service communication, and error handling.

### [Rota da Cultura — Entertainment & Urban Mobility](https://github.com/juliamelots/MAC0332-Project)

**TypeScript · React · Kotlin · Docker**

A full-stack application combining movie and cinema discovery with public transportation route planning.

Developed as a team project at USP, using React and TypeScript for the frontend and Kotlin for the backend. My contributions included backend testing and data processing.

### [Totec — Recipe Management Backend](https://github.com/TotecApp/Totec_Backend)

**Kotlin · Ktor · PostgreSQL**

Backend for a recipe-sharing application with user accounts, recipe management, tags, and favorites.

Developed REST API functionality and worked on database integration, user authentication, recipe management, and automated tests.

## 🔬 Open-source contributions

### [scikit-network — UGAP Graph Embedding](https://github.com/sknetwork-team/scikit-network/pull/599)

**Graph Machine Learning · Python · Cython**

Contributed to the research and development of **UGAP**, a graph dimensionality reduction algorithm based on Personalized PageRank similarities.

My work involved algorithmic experimentation, benchmarking against established dimensionality reduction methods, investigating initialization strategies and hyperparameter sensitivity, and exploring alternative approaches to Personalized PageRank computation.

[**View merged Pull Request #599 →**](https://github.com/sknetwork-team/scikit-network/pull/599)

---

## 🛠️ Technologies & Interests

- **Languages:** Python, C++, C, Kotlin, TypeScript, SQL
- **Machine Learning & Data Science:** PyTorch, scikit-learn, NumPy, Pandas, NLTK, spaCy
- **Development & Tools:** Git/GitHub, Docker, Linux, PostgreSQL, Jupyter, React, Ktor
- **Interests:** Deep Learning, Natural Language Processing, Causal Inference, Graph Machine Learning, Information Retrieval & RAG, LLM Agents & Evaluation, AI Observability, and Software Engineering

## 📫 Let's connect!

I'm always interested in opportunities to collaborate on interesting problems in machine learning, data science, and software development.

- **GitHub:** [@DaviCoelh0](https://github.com/DaviCoelh0)
- **LinkedIn:** [Davi Coelho](https://www.linkedin.com/in/davicoelh0/)
