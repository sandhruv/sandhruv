# Sankalp Nigam | AI Engineer & Full-Stack Developer

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=23&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Building+AI-powered+products;RAG+%7C+LLM+Applications+%7C+Backend+Systems;From+prototype+to+production;Full-Stack+Development+%2B+Applied+AI" alt="Animated introduction" />
</p>

<p align="center">
  <a href="https://github.com/sandhruv">
    <img src="https://img.shields.io/badge/GitHub-sandhruv-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/sankalpnigam">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="mailto:sankalpnigamofficial@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sandhruv&style=flat-square&color=58A6FF&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## About Me

I'm a Computer Science and Engineering student at **Lovely Professional University**, interested in building practical AI applications, intelligent backend systems, and full-stack products.

My focus is on connecting AI capabilities with real software engineering: retrieving relevant information, orchestrating language models, designing APIs, building usable interfaces, and deploying applications.

- **Currently building:** Placement Prep Buddy — an AI-powered interview preparation platform.
- **AI interests:** Retrieval-Augmented Generation (RAG), LLM applications, semantic search, and AI agents.
- **Engineering interests:** API design, backend architecture, databases, testing, and cloud deployment.
- **Core stack:** Python, Java, TypeScript, React, FastAPI, Node.js, and MongoDB.
- **Education:** B.Tech in Computer Science and Engineering, Lovely Professional University.

I'm particularly interested in building AI systems that are useful, measurable, maintainable, and accessible through well-designed software.

---

## What I Build

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 Applied AI & RAG</h3>
      <p>Document retrieval, semantic search, vector databases, LLM-powered question answering, and retrieval pipelines.</p>
      <p><code>Python</code> <code>FAISS</code> <code>Sentence Transformers</code> <code>LLMs</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ Backend Engineering</h3>
      <p>REST APIs, authentication, data modeling, asynchronous workflows, integrations, and application architecture.</p>
      <p><code>FastAPI</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🖥️ Full-Stack Development</h3>
      <p>Responsive interfaces connected to backend services, databases, and AI-powered application features.</p>
      <p><code>React</code> <code>Next.js</code> <code>TypeScript</code> <code>Tailwind CSS</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🚀 Deployment & Quality</h3>
      <p>Containerization, deployment workflows, automated browser testing, and performance-conscious development.</p>
      <p><code>Docker</code> <code>Google Cloud</code> <code>Render</code> <code>Selenium</code></p>
    </td>
  </tr>
</table>

---

## Featured Projects

### 01 · Placement Prep Buddy

**AI-powered interview preparation and skill-gap analysis**

An interview preparation platform designed to help candidates practice for specific roles, identify skill gaps, and receive structured feedback.

**Key capabilities**
- Resume-based preparation and role selection.
- Skill-gap analysis to guide preparation.
- Dynamic AI interviewer with follow-up questions.
- Scored interview reports and feedback.

**Technology:** React · FastAPI · Groq LLM · Tavily · MongoDB · Render

<p>
  <a href="https://placement-preparation-buddy-1.onrender.com/login">
    <img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=for-the-badge&logo=render&logoColor=white" alt="Live demo" />
  </a>
  <a href="https://github.com/sandhruv/placement-preparation-buddy">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github" alt="Source code" />
  </a>
</p>

**Application preview**

<!-- Add a real screenshot at assets/placement-prep-buddy.png -->
<p align="center">
  <img src="assets/placement-prep-buddy.png" alt="Placement Prep Buddy application screenshot" width="90%" />
</p>

**High-level architecture**

```mermaid
flowchart TD
    A[Candidate] --> B[React Frontend]
    B --> C[FastAPI Backend]
    C --> D[Resume and Skill Analysis]
    C --> E[LLM Interview Workflow]
    E --> F[Groq LLM]
    C --> G[Tavily Search]
    C --> H[(MongoDB)]
    D --> I[Interview Report]
    E --> I
    I --> B
```

*Conceptual architecture based on the project's described components; not a runtime trace.*

---

### 02 · Vettora

**AI-assisted recruitment and assessment platform**

A full-stack recruitment system designed to bring candidate screening, interview workflows, assessment features, and role-based access into one application.

**Key capabilities**
- Role-based experiences for recruitment and candidate workflows.
- Resume processing and ATS-oriented functionality.
- AI-assisted interview question generation and audio analysis.
- Real-time application features using Socket.IO and WebRTC.
- Assessment and anti-cheat functionality.

**Technology:** React · Redux Toolkit · Express · MongoDB · Socket.IO · WebRTC · Docker

<p>
  <a href="https://cv-shortlisting-system-2.onrender.com/">
    <img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=for-the-badge&logo=render&logoColor=white" alt="Live demo" />
  </a>
  <a href="https://github.com/sandhruv/cv-shortlisting-system">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github" alt="Source code" />
  </a>
</p>

**Application preview**

<!-- Add a real screenshot at assets/vettora-dashboard.png -->
<p align="center">
  <img src="assets/vettora-dashboard.png" alt="Vettora recruitment dashboard screenshot" width="90%" />
</p>

**High-level architecture**

```mermaid
flowchart TD
    U[Recruiters and Candidates] --> F[React Frontend]
    F --> A[Express API]
    A --> DB[(MongoDB)]
    A --> AI[AI Processing Services]
    A --> RT[Socket.IO]
    F <--> RTC[WebRTC Sessions]
    RT --> F
    AI --> A
```

*Conceptual overview; actual service boundaries may differ.*

---

### 03 · SangamRAG

**Conflict-aware Retrieval-Augmented Generation**

An experimental RAG system designed to retrieve relevant text and identify potentially contradictory claims before generating an answer.

**Key capabilities**
- Document chunking and semantic retrieval.
- Vector search using FAISS and MiniLM embeddings.
- Conflict-aware processing before answer generation.
- SHA-256-based caching for repeated requests.

**Technology:** Python · FastAPI · FAISS · Groq · Ollama · Docker · Google Cloud Run

<p>
  <a href="https://sangam-rag-frontend-524229321053.asia-south1.run.app">
    <img src="https://img.shields.io/badge/Live_Demo-2EA44F?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Live demo" />
  </a>
  <a href="https://github.com/sandhruv/sanagam-rag">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github" alt="Source code" />
  </a>
</p>

**Pipeline architecture**

```mermaid
flowchart TD
    A[User Question] --> B[Query Processing]
    B --> C[Embedding Model]
    C --> D[FAISS Vector Search]
    D --> E[Relevant Chunks]
    E --> F[Conflict Detection]
    F --> G[LLM Generation]
    G --> H[Answer]
    B -. Repeated request .-> I[SHA-256 Cache]
    I -. Cache hit .-> H
```

*Conceptual pipeline; confirm the precise cache and retrieval flow against the implementation.*

---

### 04 · Batuni Chat App

**Real-time Android messaging application**

An Android chat application built around Firebase authentication and real-time data synchronization.

**Key capabilities**
- Firebase Authentication.
- Realtime Database integration.
- Modular Android components using Fragments and Adapters.
- Responsive messaging interface.

**Technology:** Java · Firebase · Android SDK

<p>
  <a href="https://github.com/sandhruv/batuni-chat-aap">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github" alt="Source code" />
  </a>
</p>

<!-- Optional: add a real screenshot at assets/batuni-chat.png -->

---

### 05 · Document AI RAG

**Question answering over personal documents**

A document-focused question-answering application that combines retrieval with language-model generation to help users query their own content.

**Technology:** Python · FastAPI · React · FAISS · Sentence Transformers · Groq

<p>
  <a href="https://github.com/sandhruv/document-ai-rag">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github" alt="Source code" />
  </a>
</p>

---

### 06 · Portfolio Website

**Personal developer portfolio**

A portfolio website built with the Next.js App Router and TypeScript, styled using Tailwind CSS.

**Technology:** Next.js · TypeScript · Tailwind CSS

<p>
  <a href="https://github.com/sandhruv/sankalpnigam">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github" alt="Source code" />
  </a>
</p>

---

## More Projects

| Project | Description | Repository |
|---|---|---|
| WhatsApp Automation Suite | Desktop messaging automation using Selenium and Tkinter | [View repository](https://github.com/sandhruv/WhatsApp-Automation-Suite) |
| Screenshot to Code | UI screenshot-to-code experimentation | [View repository](https://github.com/sandhruv/screenshot-to-code) |
| Personal Budget Assistant | Python-based personal finance assistant | [View repository](https://github.com/sandhruv/-Personal-Budget-Assistant) |
| Student Performance Prediction | Machine learning and predictive analysis | [View repository](https://github.com/sandhruv/predictive-analysis) |
| LPU Portal | Document processing portal | [View repository](https://github.com/sandhruv/lpu-portal) |
| Hand Gesture Control | Computer vision and gesture interaction | [View repository](https://github.com/sandhruv/hand-gesture-) |
| LeetCode Solutions | DSA practice and problem-solving archive | [View repository](https://github.com/sandhruv/leetcode_solution-summer-pep) |

---

## Technology Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL" />
</p>

### Frontend & Backend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

### AI / ML

<p>
  <img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/FAISS-111111?style=flat-square" alt="FAISS" />
  <img src="https://img.shields.io/badge/LLMs-8A2BE2?style=flat-square" alt="LLMs" />
  <img src="https://img.shields.io/badge/NLP-0F9D58?style=flat-square" alt="NLP" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
</p>

### Databases, Cloud & Tools

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Render-121212?style=flat-square" alt="Render" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" alt="Selenium" />
</p>

---

## GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=sandhruv&show_icons=true&include_all_commits=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub statistics" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sandhruv&layout=compact&theme=github_dark&hide_border=true" alt="Most-used languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sandhruv&theme=github-dark&hide_border=true" alt="GitHub contribution streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sandhruv&theme=github-compact&hide_border=true" alt="GitHub contribution activity graph" width="100%" />
</p>

---

## Certifications & Learning

- NPTEL — Cloud Computing
- Coursera — Google AI Essentials
- McKinsey.org — Forward Program
- Activeloop — GenAI 360°
- Lovely Professional University — Logic Building and Data Structures

---

## Current Learning Roadmap

- [ ] Build more reliable RAG pipelines with evaluation and retrieval-quality testing.
- [ ] Explore agent workflows, tool calling, and LLM orchestration.
- [ ] Improve API security, automated testing, and backend reliability.
- [ ] Deepen cloud deployment and containerization skills.
- [ ] Continue practicing data structures and algorithms.

---

## Let's Connect

I'm interested in AI engineering, full-stack development, and projects that solve practical problems.

<p align="center">
  <a href="mailto:sankalpnigamofficial@gmail.com">
    <img src="https://img.shields.io/badge/Email-Let's_Talk-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/sankalpnigam">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/sandhruv">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
</p>

<p align="center">
  <i>Building, learning, and shipping — one project at a time.</i>
</p>
