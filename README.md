<div align="center">

<img src="https://user-images.githubusercontent.com/36594527/117921831-c3d32c80-b334-11eb-8bab-a423ac34272a.png" alt="MasterHead" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&pause=1000&color=7C3AED&center=true&vCenter=true&width=720&lines=Hi+there%2C+I'm+Shubham+Pandey;AI+%2F+ML+Engineer+%40+Gartner;Generative+AI+%C2%B7+LLMs+%C2%B7+Agentic+Systems;Production+RAG+%C2%B7+Guardrails+%C2%B7+Fine-tuning" alt="Typing SVG" />
</a>

Hi 👋, I'm Shubham Pandey

AI / Machine Learning Engineer building Generative AI systems that survive production

<a href="https://github.com/shubham-309">
  <img src="https://img.shields.io/badge/GitHub-shubham--309-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/sp309/">
  <img src="https://img.shields.io/badge/LinkedIn-Shubham%20Pandey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:shubham.py309@gmail.com">
  <img src="https://img.shields.io/badge/Email-shubham.py309-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://drive.google.com/file/d/1SokGydqSTSIbCUwiBzBxotuTb9xXewfY/view?usp=sharing">
  <img src="https://img.shields.io/badge/Resume-View%20PDF-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=shubham-309&label=Profile%20Views&color=7C3AED&style=flat-square" alt="Profile views"/>

</div>

🧠 About Me

🔭 Currently: Software Engineer (ML / NLP) at Gartner, building a unified agentic framework that turns conventional workflows into orchestrated agent flows, cutting new-workflow integration time by ~50%.

🛡️ AI Safety: Own an LLM guardrails pipeline covering all 10 categories of the OWASP Top 10 for LLM Applications, including prompt injection, system-prompt leakage, excessive agency, and unsafe output handling.

🏢 Previously: 2 years at Impressico Business Solutions, delivering GenAI systems for a US-based LegalTech client, including production RAG over 5,000+ legal documents.

🧪 Fine-tuning: Built domain-specific models including Culinary BERT and QLoRA/PEFT classifiers, reaching 91–92% F1 on relevant tasks.

📈 Production mindset: 100% of production LLM calls traced with Langfuse, RAGAS + DeepEval regression suites, and ~35% token-spend reduction through semantic and response caching.

🚀 Internal AI tooling: Built hiring intelligence and meeting-summarization systems, including tooling that reduced per-candidate screening time by ~60%.

💬 Ask me about: Agentic RAG, Graph RAG, MCP, LoRA/QLoRA fine-tuning, LLM evaluation, guardrails, and production AI optimization.

🏗️ How I Structure a Production LLM System
```
                    ┌──────────────────────┐
                    │      USER QUERY      │
                    └──────────┬───────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│  01 · PROTECT                                                        │
│  Input Guardrails                                                    │
│  Prompt injection · PII · jailbreaks · input validation              │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│  02 · REASON                                                         │
│  Agent Orchestration                                                 │
│  Router → RAG → Tools / MCP → LLM                                    │
│  BM25 + vector retrieval · function calling · grounded generation   │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│  03 · VALIDATE                                                        │
│  Output Guardrails                                                    │
│  Faithfulness · relevance · safety · structured output validation    │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────────────────────────────┐
│  04 · OBSERVE & OPTIMIZE                                             │
│  Langfuse · RAGAS · DeepEval · semantic / response caching           │
│  Trace every hop → evaluate quality → control latency & token cost   │
└──────────────────────────────┬───────────────────────────────────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   PRODUCTION ANSWER  │
                    └──────────────────────┘
```
My principle: production GenAI is not just about getting a good answer — it is about making every step safe, observable, evaluable, and cost-efficient.

🛠️ Tech Arsenal

Core Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,flask,js,nextjs,tailwind,mysql,postgres" alt="Core engineering stack"/>
</p>

ML / Deep Learning / Search

<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,graphql,elasticsearch" alt="ML and search stack"/>
</p>

Cloud / DevOps

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,docker,git,gitlab,github" alt="Cloud and DevOps stack"/>
</p>

GenAI Stack

<p align="center">
  <img src="https://img.shields.io/badge/Hugging%20Face-Transformers%20%26%20Hub-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000000" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/LangChain-RAG%20%26%20Agents-1C3C3C?style=for-the-badge&logo=langchain&logoColor=F6EDE3" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-Stateful%20Orchestration-0B7285?style=for-the-badge" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/OpenAI-GPT%20API-000000?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Pinecone-Vector%20Retrieval-212121?style=for-the-badge&logo=pinecone&logoColor=white" alt="Pinecone"/>
  <img src="https://img.shields.io/badge/FAISS-Vector%20Search-10B981?style=for-the-badge" alt="FAISS"/>
</p>

What I Build

<p align="center">
  <img src="https://img.shields.io/badge/RAG-Agentic%20%7C%20Graph%20%7C%20Multimodal-7C3AED?style=for-the-badge" alt="RAG"/>
  <img src="https://img.shields.io/badge/Agents-LangGraph%20%7C%20MCP%20%7C%20Tools-7C3AED?style=for-the-badge" alt="Agents"/>
  <img src="https://img.shields.io/badge/Fine--tuning-PEFT%20%7C%20LoRA%20%7C%20QLoRA-F59E0B?style=for-the-badge" alt="Fine tuning"/>
  <img src="https://img.shields.io/badge/Evals-RAGAS%20%7C%20DeepEval%20%7C%20Langfuse-10B981?style=for-the-badge" alt="Evals"/>
  <img src="https://img.shields.io/badge/Guardrails-OWASP%20Top%2010%20for%20LLMs-EF4444?style=for-the-badge" alt="Guardrails"/>
  <img src="https://img.shields.io/badge/Retrieval-Pinecone%20%7C%20FAISS%20%7C%20OpenSearch-06B6D4?style=for-the-badge" alt="Retrieval"/>
  <img src="https://img.shields.io/badge/Serving-FastAPI%20%7C%20AWS%20Lambda%20%7C%20Docker-06B6D4?style=for-the-badge" alt="Serving"/>
  <img src="https://img.shields.io/badge/Optimization-Semantic%20Cache%20%7C%20%7E35%25%20Tokens-F59E0B?style=for-the-badge" alt="Optimization"/>
</p>

<details>
<summary><b>📋 Full Skills Matrix</b></summary>

<br/>

Area

Toolkit

Languages & APIs

Python, SQL, JavaScript · FastAPI, Flask, REST & GraphQL APIs, OOP

Generative AI

LLM applications, RAG, agentic/graph/multimodal RAG, AI agents, multi-agent orchestration, MCP, tool/function calling, prompting

Fine-tuning

Hugging Face Transformers, PyTorch, PEFT, LoRA, QLoRA, MLM/NSP pre-training, text classification, summarization

Evaluation & Observability

RAGAS, DeepEval, Langfuse, LLM-as-a-Judge, faithfulness, relevancy, hallucination detection, regression testing

AI Safety

OWASP Top 10 for LLM Applications, prompt-injection/jailbreak defense, sensitive-information disclosure prevention, excessive-agency controls, input/output validation

Vector Search

Pinecone, FAISS, Elasticsearch, OpenSearch, embeddings, semantic search, document chunking

Cloud & DevOps

AWS Lambda, Microsoft Azure AI Foundry, Azure Cognitive Services, Document Intelligence, Docker, model serving

Data Engineering

PostgreSQL, MySQL, Apache Airflow, ETL and data pipelines

Performance

Token-cost optimization, semantic/response caching, latency and inference optimization

</details>

⭐ Featured Work

<p align="center">
  <a href="https://github.com/shubham-309/cullinary-bert">
    <img width="49%" src="https://github-readme-stats-ten-green.vercel.app/api/pin/?username=shubham-309&repo=cullinary-bert&theme=tokyonight&hide_border=true&bg_color=161b22&title_color=a78bfa&icon_color=22d3ee" alt="Culinary BERT"/>
  </a>
  <a href="https://github.com/shubham-309/MultiPDF_Chatbot">
    <img width="49%" src="https://github-readme-stats-ten-green.vercel.app/api/pin/?username=shubham-309&repo=MultiPDF_Chatbot&theme=tokyonight&hide_border=true&bg_color=161b22&title_color=a78bfa&icon_color=22d3ee" alt="MultiPDF Chatbot"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/shubham-309/AI_RESUME_SCREENING_SYSTEM">
    <img width="49%" src="https://github-readme-stats-ten-green.vercel.app/api/pin/?username=shubham-309&repo=AI_RESUME_SCREENING_SYSTEM&theme=tokyonight&hide_border=true&bg_color=161b22&title_color=a78bfa&icon_color=22d3ee" alt="AI Resume Screening"/>
  </a>
  <a href="https://github.com/shubham-309/meeting_summarization">
    <img width="49%" src="https://github-readme-stats-ten-green.vercel.app/api/pin/?username=shubham-309&repo=meeting_summarization&theme=tokyonight&hide_border=true&bg_color=161b22&title_color=a78bfa&icon_color=22d3ee" alt="Meeting Summarization"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/shubham-309/developer_profile_analysis">
    <img width="49%" src="https://github-readme-stats-ten-green.vercel.app/api/pin/?username=shubham-309&repo=developer_profile_analysis&theme=tokyonight&hide_border=true&bg_color=161b22&title_color=a78bfa&icon_color=22d3ee" alt="Developer Profile Analysis"/>
  </a>
  <a href="https://github.com/shubham-309/Finetuning">
    <img width="49%" src="https://github-readme-stats-ten-green.vercel.app/api/pin/?username=shubham-309&repo=Finetuning&theme=tokyonight&hide_border=true&bg_color=161b22&title_color=a78bfa&icon_color=22d3ee" alt="Fine-tuning"/>
  </a>
</p>

🔒 Enterprise work: agentic-workflow framework and OWASP-10 guardrails pipeline at Gartner; production RAG for a US LegalTech client over 5,000+ documents; and an SEO content engine that improved keyword rankings by ~8 positions.

💼 Experience

🟣 Gartner

Software Engineer — Machine Learning / NLP · Nov 2025 – Present

Building production AI systems for enterprise research workflows.

Focus

Impact

🤖 Agentic AI

Built a unified agentic framework that reduced new-workflow integration time by ~50%

🛡️ AI Safety

Built LLM guardrails covering the OWASP Top 10 for LLM Applications

📊 Observability

Traced 100% of production LLM calls with Langfuse

💰 Optimization

Reduced token spend by ~35% through semantic and response caching

🔎 Research Automation

Automated Magic Quadrant research workflows and reduced analyst effort

🔵 Impressico Business Solutions

Associate Applied AI Engineer · Oct 2023 – Nov 2025

Delivered production GenAI systems for a US-based LegalTech client.

Focus

Impact

📚 RAG

Production RAG across 5,000+ legal documents

🧠 Fine-tuning

QLoRA / PEFT classifiers reaching 92% F1

🔗 Agentic Workflows

LangGraph automation across 6 business workflows

👥 Hiring Intelligence

Reduced per-candidate screening time by ~60%

⚪ Isoftra Digital

Software Developer Intern · Mar 2022 – May 2022

Delivered production web features across the full software-development lifecycle using Laravel, PHP, HTML/CSS and JavaScript.

📊 GitHub Pulse

<div align="center">

<a href="https://github.com/shubham-309">
  <img height="180" src="https://github-readme-stats-ten-green.vercel.app/api?username=shubham-309&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=161b22" alt="Shubham's GitHub stats"/>
</a>
<a href="https://github.com/shubham-309?tab=repositories">
  <img height="180" src="https://github-readme-stats-ten-green.vercel.app/api/top-langs/?username=shubham-309&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=161b22" alt="Top languages"/>
</a>

<br/>

<a href="https://github.com/shubham-309">
  <img src="https://streak-stats.demolab.com?user=shubham-309&theme=tokyonight&hide_border=true&background=161b22" alt="GitHub streak"/>
</a>

</div>

🌏 Beyond the Terminal

🎓 B.Tech, Electronics & Communication — Birla Institute of Applied Sciences, Bhimtal (2019–2023)

🗣️ Trilingual: English (professional) · Hindi (native) · French (DELF A2)

🏅 Certifications: DELF A2 · continuous learning in LLM evaluation and agent safety

☕ Fueled by chai, READMEs nobody reads, and the eternal quest for lower p95 latency at lower $/token

📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/sp309/">
    <img src="https://img.shields.io/badge/LinkedIn-Shubham%20Pandey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:shubham.py309@gmail.com">
    <img src="https://img.shields.io/badge/Email-shubham.py309-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/shubham-309">
    <img src="https://img.shields.io/badge/GitHub-@shubham--309-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://drive.google.com/file/d/1SokGydqSTSIbCUwiBzBxotuTb9xXewfY/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-Full%20PDF-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"/>
  </a>
</p>

<div align="center">

"Any sufficiently advanced RAG pipeline is indistinguishable from good engineering."

Built with 💜 & determinism.

</div>
