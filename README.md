<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
  <img alt="Prakash Pa, Agentic AI Architect. Let the model interpret. Let the code decide." src="assets/banner-light.png">
</picture>

<p align="center">
  <a href="https://prakashpa-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-prakashpa--portfolio.vercel.app-e07a2e?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/prakash-pa/"><img src="https://img.shields.io/badge/LinkedIn-prakash--pa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://prakashpa-portfolio.vercel.app/downloads/Prakash_PA_Agentic_AI_Architect_Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-1f1d1a?style=for-the-badge" alt="Resume"></a>
</p>

## Hi, I'm Prakash

I'm an AI architect who still builds what I design, with 15+ years of building software products behind me.

Since 2020 I've been technical lead on **InsideArbitrage**, a fintech research platform with 50K+ registered users. There I take Generative AI features from idea to production:

- AI-written portfolio reports that are **fact-checked against SEC and market data** before they reach subscribers
- One LLM layer across four providers, with database-managed prompts, caching and per-request cost tracking
- LLM pipelines that turn SEC filings and press releases into validated, structured data

That code is private. What you'll find here is the work I do on my own time.

## Nobody asked me to build these

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/prakashpa-codes/autogen-ai-customer-support-desk"><img src="assets/resolvedesk.jpg" alt="ResolveDesk"></a>
      <h3><a href="https://github.com/prakashpa-codes/autogen-ai-customer-support-desk">ResolveDesk</a></h3>
      Four AutoGen agents read each complaint, check company policy, and resolve it or hand it to a person with a reason. Confidence is calculated in code from the evidence, never self-reported by the model.
      <br><br><sub>AutoGen · MCP · FastAPI · FAISS + BM25 · Docker</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/prakashpa-codes/spotifychat-hybrid-rag"><img src="assets/spotifychat.jpg" alt="SpotifyChat"></a>
      <h3><a href="https://github.com/prakashpa-codes/spotifychat-hybrid-rag">SpotifyChat</a></h3>
      Vector search fused with a Neo4j concept graph. Falls back to vector-only search if the graph is down, and searches the web only after the user says yes.
      <br><br><sub>LangChain · FAISS · Neo4j · LangSmith · Docker</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/prakashpa-codes/uzhavar-gpt"><img src="assets/uzhavar-gpt.jpg" alt="Uzhavar GPT"></a>
      <h3><a href="https://github.com/prakashpa-codes/uzhavar-gpt">Uzhavar GPT</a></h3>
      Helps Tamil Nadu farmers find government schemes by text or voice, in Tamil or English. On a 20-question bilingual test set, the right source was in the top 8 every time.
      <br><br><sub>LangChain · FAISS + BM25 · FastAPI · OpenAI speech</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/prakashpa-codes/hybrid-graph-vector-rag-demo"><img src="assets/graphvector.jpg" alt="Graph vs Vector"></a>
      <h3><a href="https://github.com/prakashpa-codes/hybrid-graph-vector-rag-demo">Graph vs Vector</a></h3>
      Vector, graph and hybrid retrieval side by side on Neo4j, graded against ground truth on multi-hop and numeric questions.
      <br><br><sub>LangChain · Neo4j · OpenAI</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/prakashpa-codes/autogen-multiagent-docker-agentdesk"><img src="assets/agentdesk.jpg" alt="AgentDesk"></a>
      <h3><a href="https://github.com/prakashpa-codes/autogen-multiagent-docker-agentdesk">AgentDesk</a></h3>
      A main agent decides which specialists a request needs, delegates to them as tools and combines their answers. The UI shows each agent working in real time.
      <br><br><sub>AutoGen · FastAPI · Docker · Traefik</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/prakashpa-codes/multipdf-rag-assistant"><img src="assets/multipdf.jpg" alt="Multi-PDF RAG"></a>
      <h3><a href="https://github.com/prakashpa-codes/multipdf-rag-assistant">Multi-PDF RAG</a></h3>
      Q&A across many PDFs with switchable retrieval: vector, BM25, hybrid fusion, multi-query and cross-encoder re-ranking. Every answer cites its sources.
      <br><br><sub>LangChain · FAISS · BM25 · sentence-transformers</sub>
    </td>
  </tr>
</table>

## How I build

- **Start simple.** A plain workflow first; an agent only where a step needs judgment.
- **The model reads and drafts. Code validates, scores and acts.**
- **Measure before choosing.** Retrieval and orchestration choices are tested on labelled questions, not picked by habit.
- **Safe by default.** Least-privilege tools, PII masking, and a person in the loop where a mistake would cost something.

## Tools I work with

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![AutoGen](https://img.shields.io/badge/AutoGen-5C2D91)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50)
![MCP](https://img.shields.io/badge/MCP-000000)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?logo=neo4j&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL%20%2F%20MariaDB-4479A1?logo=mysql&logoColor=white)

<sub>Before AI, I spent a decade building PHP and full-stack products for US clients in finance, healthcare and education. That's why I treat data, integrations and security as part of the AI system, not an afterthought.</sub>
