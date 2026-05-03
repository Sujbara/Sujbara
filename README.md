<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Suhaib+Jbara+%F0%9F%91%8B;Software+Engineer;AI+Enthusiast;Building+Smart+Solutions" alt="Typing SVG" />

</div>

---

## 🙋 About Me

I'm a **AI-first Software Engineer** with experience in AI, full-stack, and cloud. Skilled in Python, TypeScript, NextJS, React Native, SQL, REST APIs, Gen AI, RAG, AI Agents, Docker, AWS, Cloudflare, Infrastructure as Code (IaC), and Continuous Integration and Continuous Delivery (CI/CD). Strong foundation in computer science with hands-on industry experience and translating problems into software solutions.

- 🔭 **Currently working on:** Notion Notes Chatbot, a AI bot to retrieve and summarize my notes from Notion.
- 🌱 **Currently learning:** Building AI systems and deployment.
- 👯 **Looking to collaborate on:** Open-source projects in AI systems and full-stack web development.
- 💬 **Ask me about:** AI applications, TypeScript/Python development, REST APIs, and Cloud deployment.
- ⚡ **Fun fact:** Tagushi website is running zero cost

---

## 🛠️ Tech Stack

### Languages
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
</p>

### Frameworks & Libraries
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white" alt="NextJS"/>
  <img src="https://img.shields.io/badge/FastAPI-009485.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
</p>

### AI
<p>
  <img src="https://img.shields.io/badge/Ollama-fff?style=for-the-badge&logo=ollama&logoColor=000" alt="Ollama"/>
  <img src="https://img.shields.io/badge/LangChain-1c3c3c.svg?style=for-the-badge&logo=langchain&logoColor=white" alt="Langchain"/>
</p>

### Cloud
<p>
  <img src="https://custom-icon-badges.demolab.com/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white" alt="Cloudflare"/>
  <img src="https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white" alt="Firebase"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="Github Actions"/>
</p>

### Tools & Platforms
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code"/>
</p>

---

## 🚀 Featured Projects

### 🧠 [Notion RAG chatbot](http://github.com/Sujbara/Notion-RAG-chatbot)
> A private, agentic RAG pipeline that transforms personal Notion workspaces into searchable, interactive knowledge bases — built with a local-first privacy architecture.

| Feature | Detail |
|---|---|
| **Frontend** | Next.js (App Router) |
| **Backend**	| FastAPI / Python |
| **RAG Engine** | LlamaIndex / ChromaDB |
| **Intelligence** | Local (Ollama) & Cloud (Gemini) |
| **Goal** | An intelligent system to help me retrieve information intelligently from a 2000+ min of information |

**Key capabilities:**
- Hybrid Inference Engine: Implements a provider-agnostic LLM interface that toggles between local-first privacy (Ollama/Gemma) and high-reasoning cloud models (Gemini 2.0 Flash) based on query complexity.
- Dual-Mode Response Pipeline: Features an autonomous "Thinking Mode" using LlamaIndex AgentWorkflow for multi-step reasoning, alongside a "Fast Mode" optimized for millisecond-latency direct vector retrieval.
- Deep-Link Document Ingestion: Custom Python parsers that navigate Notion's nested block structure and extract data from attached .ipynb notebooks, converting unstructured research into high-density embeddings.
- Optimized Vector Persistence: ChromaDB integration with MD5-based file hashing, ensuring the local knowledge base only re-indexes when source content actually changes—drastically reducing compute overhead for large workspaces.
- Real-time Agentic Streaming: Stateful Next.js frontend connected via WebSockets to visualize the agent's internal "event stream," showing exactly what the AI is thinking or searching before it delivers the final answer.

[![Notion RAG chatbot Repo](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sujbara/Notion-RAG-chatbot)

### 🍣 Tagushi

> A sushi menu website built around a realistic local-business use case — treated as a live product with a full deployment pipeline.

| Feature | Detail |
|---|---|
| **Frontend** | Angular JS |
| **CI/CD** | GitHub Actions |
| **Deployment** | Cloudflare |
| **Goal** | Help a local business increase its reach |

**Key capabilities:**
- Production Angular SPA with lazy-loaded routes, OnPush change detection, and trackBy-optimized renders — eliminating layout shift and scroll lag across all menu categories.
- Real-time cart engine with a single reactive subscription propagated via inputs, replacing 9 redundant per-card subscriptions and cutting re-render overhead by 90%.
- Asset pipeline split across two independent CI/CD workflows: app code deploys to Cloudflare Workers on every push, while images and menu data upload to R2 only when those files actually change.
- Infrastructure defined entirely in code — Wrangler config, GitHub Actions, and environment-aware Angular builds that swap between local assets and R2 CDN automatically at build time.
- Served from Cloudflare's 330+ edge locations globally with zero origin server, zero database, and zero monthly cost — not a free tier that expires, permanently free by architecture.

### 🚦 [QTPS — Qatar Traffic Prediction System](https://github.com/Sujbara/QTPS-Qatar-Traffic-Prediction-System)

> Revolutionizing travel planning in Qatar through ML-powered traffic forecasting.

| Feature | Detail |
|---|---|
| **Model** | Random Forest Classifier (~90% accuracy) |
| **Data Source** | TomTom Traffic History API (Oct 2022) |
| **Frontend** | JavaScript web dashboard with interactive map |
| **Backend** | Python ML inference server |
| **Goal** | Predict traffic volume & recommend fastest routes |

**Key capabilities:**
- 🗺️ Visualize live street-level traffic conditions on an interactive map
- 📊 Query historical traffic data by road, time, and functional class
- 🤖 Serve ML predictions in real-time via a REST API backend
- 🏁 Recommend the fastest route between two points in Qatar

[![QTPS Repo](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sujbara/QTPS-Qatar-Traffic-Prediction-System)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sujbara&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sujbara&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top Languages" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sujbara&theme=github-dark-blue&hide_border=true" alt="GitHub Streak"/>
</div>

---

## 📫 Get in Touch

<p align="center">
  <a href="https://suhaibjbara.online">
    <img src="https://img.shields.io/badge/ReadMe-018EF5?style=for-the-badge&logo=readme&logoColor=fff" alt="Suhaib Jbara"/>
  </a>
  <a href="https://www.linkedin.com/in/suhaib-jbara/">
    <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin-white&logoColor=fff" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Sujbara">
    <img src="https://img.shields.io/badge/GitHub-Sujbara-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:suhaib.jebara@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Sujbara&color=58A6FF&style=flat-square&label=Profile+Views" alt="Profile Views"/>
</div>
