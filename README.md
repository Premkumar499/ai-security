# 🛡️ AI Security Masterclass

A hands-on learning repository exploring the security, reliability, observability, and evaluation of Large Language Model (LLM) applications.

This project demonstrates practical techniques for building more secure, reliable, and production-ready AI systems using tools and frameworks such as Portkey, Guardrails AI, LangSmith, RAGAS, and DeepEval.

## 📌 Overview

As LLM applications become more widely used, developers must address challenges such as unreliable outputs, hallucinations, prompt injection, insufficient monitoring, and inconsistent evaluation.

The **AI Security Masterclass** explores practical approaches to identifying and managing these challenges through hands-on Jupyter notebooks.

## 🎯 Objectives

- Understand the security risks associated with LLM applications.
- Explore LLM gateways and request management.
- Validate and constrain LLM outputs using guardrails.
- Monitor and debug LLM application workflows.
- Evaluate Retrieval-Augmented Generation (RAG) systems.
- Measure LLM quality using automated evaluation frameworks.
- Learn practices that support reliable AI application development.

## ✨ Key Topics

### 1. LLM Gateway

**Notebook:** `gateway.ipynb`

Explore LLM gateway concepts and request management using Portkey.

Topics include:
- LLM request handling
- Request tracing and monitoring
- Retries and fallback strategies
- Caching and reliability considerations

### 2. Guardrails for LLM Applications

**Notebook:** `guard_rail.ipynb`

Learn how to validate and control LLM outputs.

Topics include:
- Output validation
- Custom validators
- Structured response constraints
- Handling invalid or unexpected outputs

### 3. LLM Observability

**Notebook:** `observability.ipynb`

Understand how to monitor and debug LLM application workflows using LangSmith.

Topics include:
- Request tracing
- Execution monitoring
- Debugging LLM chains
- Understanding application behavior

### 4. RAG Evaluation

**Notebook:** `ragas_evaluation.ipynb`

Explore evaluation techniques for Retrieval-Augmented Generation systems using RAGAS.

Evaluation concepts include:
- Faithfulness
- Answer relevancy
- Context precision
- Context recall

### 5. LLM Evaluation with DeepEval

**Notebook:** `deep_eval.ipynb`

Explore systematic evaluation of LLM responses using DeepEval.

Topics include:
- Test cases for LLM applications
- Evaluation metrics
- Custom evaluation criteria
- Assessing response quality and reliability

## 🧰 Technology Stack

- **Language:** Python
- **Development Environment:** Jupyter Notebook
- **LLM Gateway:** Portkey
- **Guardrails:** Guardrails AI
- **Observability:** LangSmith
- **RAG Evaluation:** RAGAS
- **LLM Evaluation:** DeepEval

## 📂 Project Structure

```text
AI-Security-Masterclass/
├── gateway.ipynb
├── guard_rail.ipynb
├── observability.ipynb
├── ragas_evaluation.ipynb
├── deep_eval.ipynb
├── requirements.txt
└── README.md
```

*The structure above represents the main project files; adjust it if your repository contains additional folders or files.*

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.10 or later
- Git
- Jupyter Notebook or JupyterLab
- API keys for external services used by the notebooks

### 1. Clone the repository

```bash
git clone https://github.com/Premkumar499/ai-security.git
cd ai-security
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Linux or macOS:

```bash
source .venv/bin/activate
```

On Windows:

```powershell
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

If a dependency is missing, install it according to the relevant notebook's requirements.

### 4. Configure API keys

Some notebooks may require API keys for external LLM providers or monitoring services.

Set the required environment variables according to the services used in each notebook.

Example for Linux or macOS:

```bash
export OPENAI_API_KEY="your-api-key"
export LANGCHAIN_API_KEY="your-api-key"
```

Use the actual variable names required by each notebook. Never commit real API keys, passwords, or other secrets to GitHub.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook you want to explore and execute its cells in order.

## 🚀 Getting Started

Recommended learning order:

1. `gateway.ipynb` — Learn about LLM gateway concepts.
2. `guard_rail.ipynb` — Explore output validation and guardrails.
3. `observability.ipynb` — Understand tracing and monitoring.
4. `ragas_evaluation.ipynb` — Evaluate RAG pipelines.
5. `deep_eval.ipynb` — Explore systematic LLM evaluation.

Review the configuration and dependencies of each notebook before running it.

## 🔐 Security Best Practices

- Store API keys in environment variables or a secrets manager.
- Never expose credentials in source code or notebook outputs.
- Validate LLM inputs and outputs where appropriate.
- Treat retrieved documents and external content as untrusted input.
- Test applications against prompt injection and other LLM-specific risks.
- Monitor failures, unexpected responses, and evaluation results.
- Avoid treating automated evaluation scores as a guarantee of safety or correctness.

## 📚 Learning Outcomes

After working through this repository, you should have a practical introduction to:

- LLM application security concepts
- Gateway-based request management
- Output validation and guardrails
- LLM tracing and observability
- RAG evaluation methodologies
- Automated LLM testing and quality assessment

## 🛣️ Future Improvements

Potential areas for further development include:

- Prompt injection detection and mitigation experiments
- Automated security test suites for LLM applications
- Evaluation dashboards for RAG systems
- Improved error handling and logging
- Reproducible experiments and benchmark datasets
- Integration of additional LLM security evaluation tools

## 👨‍💻 Author

**Prem Kumar**

B.Tech — Artificial Intelligence and Data Science

GitHub: [@Premkumar499](https://github.com/Premkumar499)

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request describing your improvements.

## 📄 License

No license is specified in this README. Add an appropriate license file if you intend to permit others to reuse, modify, or distribute this project.

---

⭐ If you find this repository useful for learning AI security and LLM engineering, consider starring the repository.

