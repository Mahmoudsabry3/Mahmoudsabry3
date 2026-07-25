<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0B1220,45:172554,100:22C55E&text=Mahmoud%20Sabry&fontColor=FFFFFF&fontSize=46&fontAlignY=36&desc=Senior%20AI%20Engineer&descAlignY=56&descSize=20&animation=fadeIn)

**Agent systems · ML services · Eval-driven delivery**

I design and build **AI systems that move beyond the notebook** — from multi-agent orchestration and evaluation to model serving, observability, and user-facing delivery.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoudsabrygamal/)
[![Email](https://img.shields.io/badge/Email-Let's_talk-172554?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:mahmoudsabryfayed@outlook.com)
![Location](https://img.shields.io/badge/Giza%2C%20Egypt%20%C2%B7%20Open%20to%20remote-22C55E?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

## Flagship — [ai-research-assistant](https://github.com/Mahmoudsabry3/ai-research-assistant)

> **LangGraph supervisor routing web search and insight research into three delivery surfaces.**

Multi-agent research pipeline with tool calling, local persistence, optional LangSmith tracing, and HTML / Gradio / terminal interfaces.

```text
Research question → LangGraph supervisor → Web Searcher | Insight Researcher
                  → synthesized answer → HTML report · Gradio chat · terminal export
```

| System | Detail |
| --- | --- |
| Orchestration | Supervisor state graph with explicit `FINISH` routing and specialist hand-offs |
| Agent roles | `Web_Searcher` and `Insight_Researcher` with distinct prompts and shared tools |
| Tools | DuckDuckGo search, HTTP retrieval, Beautiful Soup extraction |
| Interfaces | `./research.sh "question"` · `./research.sh chat` · `./research.sh simple-chat` |
| Observability | Optional LangSmith tracing via `LANGCHAIN_TRACING_V2` |
| Run locally | `python -m venv .venv && pip install -r requirements.txt && cp .env.example .env` |

[**View architecture & quickstart →**](https://github.com/Mahmoudsabry3/ai-research-assistant#architecture)

## Other production-style work

| Project | What it proves | Proof |
| --- | --- | --- |
| [**market-intelligence-system**](https://github.com/Mahmoudsabry3/market-intelligence-system) | Four-stage agent pipeline: query understanding → data collection → analysis → report generation | Hybrid live/demo fallbacks, Markdown + PDF/HTML export |
| [**customer_churn**](https://github.com/Mahmoudsabry3/customer_churn) | End-to-end ML service: feature engineering → XGBoost → MLflow → FastAPI | **ROC AUC 0.91** · Accuracy 0.89 · F1 0.74 (5-fold OOF eval) |

![Market intelligence report preview](https://github.com/user-attachments/assets/2fe21405-deb7-40f1-87ad-63612585ca27)

## How I build AI systems

- **Architecture before complexity** — clear agent boundaries and contracts before adding more tools.
- **Evaluation before confidence** — generated output needs measurable checks and visible limits.
- **Reliability before demos** — validated inputs, designed fallbacks, understandable failures.
- **Delivery completes the model** — value ships through APIs, containers, and interfaces people can use.

## Stack

**Agents & LLM**  
![Python](https://img.shields.io/badge/Python-0B1220?style=flat-square&logo=python&logoColor=FACC15)
![LangGraph](https://img.shields.io/badge/LangGraph-0B1220?style=flat-square&logo=langchain&logoColor=22C55E)
![LangChain](https://img.shields.io/badge/LangChain-0B1220?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-0B1220?style=flat-square&logo=openai&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-0B1220?style=flat-square&logo=gradio&logoColor=F97316)
![LangSmith](https://img.shields.io/badge/LangSmith-0B1220?style=flat-square&logo=langchain&logoColor=38BDF8)

**ML & MLOps**  
![FastAPI](https://img.shields.io/badge/FastAPI-0B1220?style=flat-square&logo=fastapi&logoColor=22C55E)
![XGBoost](https://img.shields.io/badge/XGBoost-0B1220?style=flat-square&logo=xgboost&logoColor=22C55E)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0B1220?style=flat-square&logo=scikitlearn&logoColor=F97316)
![MLflow](https://img.shields.io/badge/MLflow-0B1220?style=flat-square&logo=mlflow&logoColor=38BDF8)
![Pydantic](https://img.shields.io/badge/Pydantic-0B1220?style=flat-square&logo=pydantic&logoColor=E92063)

**Delivery & quality**  
![Docker](https://img.shields.io/badge/Docker-0B1220?style=flat-square&logo=docker&logoColor=2496ED)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0B1220?style=flat-square&logo=githubactions&logoColor=2088FF)
![pytest](https://img.shields.io/badge/pytest-0B1220?style=flat-square&logo=pytest&logoColor=FACC15)

---

### Building AI systems that are useful, inspectable, and ready to evolve.

[![Start a conversation](https://img.shields.io/badge/Start_a_conversation-22C55E?style=for-the-badge&logo=linkedin&logoColor=0B1220)](https://www.linkedin.com/in/mahmoudsabrygamal/)
