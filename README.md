# 👋 Snehith Kumar

AI Engineering • Generative AI • Agentic AI • Full-Stack • Computer Vision

[GitHub](https://github.com/snehithkumar18) • [LinkedIn](https://www.linkedin.com/in/snehith-kumar-4266071b8/) • snehithkumarbarkam@gmail.com

---

## About Me

I'm **Snehith Kumar**, a Computer Science Engineer focused on building practical systems at the intersection of **Artificial Intelligence and Software Engineering**.

I enjoy taking a problem from an idea to a working product — understanding the workflow, designing the architecture, building APIs and AI pipelines, integrating models and tools, testing failure cases, and deploying the system.

My strongest areas are **Python, Generative AI, Agentic AI, LLM applications, RAG, Computer Vision, backend engineering, and full-stack development**.

- 🤖 LLMs, Agentic AI, RAG and Multimodal AI
- 🧠 LangGraph, LangChain, Gemini, LLaMA, Groq, Hugging Face and PyTorch
- 🔧 Python, FastAPI, Flask, Node.js and Express
- 🌐 React, TypeScript and JavaScript
- 🗄️ PostgreSQL, MySQL, Supabase, Redis and ChromaDB
- 🧪 Pytest, Vitest, automated validation and CI/CD
- 🐳 Docker, Git, GitHub Actions and Linux

---

## 🚀 What I Build

I don't focus on adding AI to an application just because an LLM is available.

I focus on building systems where AI actually performs useful work:

```text
Real Problem
     ↓
Workflow Analysis
     ↓
System Architecture
     ↓
AI / LLM / Agent Layer
     ↓
Tools + APIs + Data
     ↓
Backend Services
     ↓
Testing + Reliability
     ↓
Deployment
     ↓
Production Product
```

My projects cover:

- Agentic AI
- Generative AI
- LLM applications
- Retrieval-Augmented Generation
- Multi-agent systems
- Computer Vision
- Multimodal AI
- AI automation
- Backend engineering
- Full-stack applications
- Real-time systems
- Data pipelines
- Developer tools

---

# 🧠 Featured Projects

## 🤖 SnehithGPT — Stateful Agentic AI Assistant

A production-oriented personal AI assistant built around **stateful agent orchestration**, tool calling, memory and retrieval.

### What I built

- Stateful workflows using **LangGraph**
- Persistent conversation state and memory
- Tool calling and conditional agent routing
- Retrieval-Augmented Generation
- Document ingestion and semantic retrieval
- SSE response streaming
- PostgreSQL persistence
- ChromaDB vector retrieval
- Gemini-powered reasoning
- Dockerized backend architecture
- Thread-isolated conversation state

### Architecture

```text
User
 ↓
FastAPI
 ↓
LangGraph Agent
 ↓
 ├── Memory
 ├── RAG
 ├── Web Search
 ├── Calculator
 ├── Document Retrieval
 └── Other Tools
 ↓
LLM
 ↓
SSE Streaming
 ↓
User
```

**Tech:** `Python` `FastAPI` `LangGraph` `LangChain` `Gemini` `RAG` `ChromaDB` `PostgreSQL` `SSE` `Docker`

---

## ✈️ TripMate AI — Multi-Agent Travel Planner

An agentic travel planning system coordinating specialized AI agents to create complete travel plans.

### What I built

- Multi-agent architecture using **LangGraph**
- Flight, hotel and itinerary agents
- Final response synthesis agent
- Shared agent state
- External API and tool integration
- PostgreSQL checkpoints
- Memory and fallback mechanisms
- Structured outputs
- Graceful failure handling

```text
User Request
     ↓
Orchestrator
     ↓
 ┌──────────────┬──────────────┐
 ↓              ↓              ↓
Flight Agent  Hotel Agent  Itinerary Agent
 └──────────────┬──────────────┘
                ↓
        Final Response Agent
                ↓
           Travel Plan
```

**Tech:** `Python` `LangGraph` `LangChain` `FastAPI` `Groq` `LLaMA 3.3` `PostgreSQL` `Docker`

---

## 🔎 EverydayJobs — Autonomous AI Job Intelligence Engine

An autonomous job intelligence and screening system that filters thousands of live jobs and identifies roles that genuinely match a candidate's skills.

**Repository:** https://github.com/snehithkumar18/Everydayjobs

### What I built

- Greenhouse, Lever and Ashby integrations
- Parallel job extraction
- Deterministic filtering
- LLM semantic screening
- Automated application-kit generation
- Email delivery
- SHA-256 deduplication
- Retry and rate-limit handling
- Persistent state
- Automated regression testing
- GitHub Actions deployment

### Pipeline

```text
9,000+ Jobs
     ↓
Deterministic Filtering
     ↓
Location / Seniority Filtering
     ↓
SHA-256 Deduplication
     ↓
LLM Batch Screening
     ↓
High-Fit Jobs
     ↓
Resume + Cover Note + Interview Prep
     ↓
Email Digest
```

### Engineering Highlights

- Designed a two-stage LLM architecture to reduce unnecessary model usage.
- Combined deterministic Python filtering with semantic LLM evaluation.
- Implemented exponential backoff for API rate limits.
- Added partial JSON recovery for interrupted LLM responses.
- Built persistent state using `seen.json`.
- Created **70 automated tests** covering parsers, providers, retries and edge cases.
- Automated execution using GitHub Actions.

**Tech:** `Python` `Gemini` `Claude` `Groq` `LLaMA` `REST APIs` `Pytest` `GitHub Actions` `Jinja2` `SMTP` `JSON` `SHA-256`

---

## 🎨 ThumbAI — AI-Powered Thumbnail Intelligence & Editing Platform

An AI-powered design platform combining **computer vision, multimodal AI, image processing and full-stack engineering**.

### What I built

- AI-assisted thumbnail generation
- YOLOv8 object/person segmentation
- Meta Segment Anything Model
- EasyOCR text detection
- InsightFace face processing
- GFPGAN facial restoration
- OpenCV image processing
- Gemini multimodal visual analysis
- LLaMA-based script analysis
- BullMQ + Redis asynchronous processing
- React-Konva WYSIWYG editor
- Dockerized ML services
- Supabase and PostgreSQL backend

### Pipeline

```text
Uploaded Thumbnail
        ↓
Image Hash / Cache
        ↓
YOLOv8 + SAM
        ↓
Object / Person / Text Detection
        ↓
EasyOCR
        ↓
Layer Extraction
        ↓
AI Editing / Inpainting
        ↓
InsightFace / GFPGAN
        ↓
Gemini Multimodal Analysis
        ↓
Thumbnail Optimization
```

**Tech:** `React` `TypeScript` `FastAPI` `Python` `PyTorch` `YOLOv8` `SAM` `OpenCV` `EasyOCR` `InsightFace` `GFPGAN` `Gemini` `LLaMA` `Redis` `BullMQ` `PostgreSQL` `Supabase` `Docker`

**Live:** https://thumb-ly.vercel.app/

---

## 🌱 AI Crop Doctor — Multimodal Agricultural AI

A multimodal agricultural AI platform that diagnoses crop diseases from images and generates localized treatment recommendations.

### What I built

- Crop disease classification
- YOLOv8 plant detection
- PyTorch disease classification
- OpenCV image preprocessing
- LLaMA reasoning through Groq
- Real-time weather integration
- Multilingual recommendations
- Text-to-speech assistance
- Browser geolocation
- Web Speech API
- Multi-level fallback handling

```text
Leaf Image
    ↓
YOLOv8 Plant Detection
    ↓
Image Preprocessing
    ↓
PyTorch Classifier
    ↓
Disease Prediction
    ↓
Weather + Soil Context
    ↓
LLaMA Reasoning
    ↓
Treatment Recommendation
    ↓
Translation
    ↓
Text-to-Speech
```

**ML:** `PyTorch` `MobileNetV2` `ResNet50` `YOLOv8` `OpenCV` `Pillow` `Torchvision`

**GenAI:** `Groq` `LLaMA 3.2 Vision` `LLaMA 3.3 70B` `Prompt Engineering`

**Tech:** `Python` `Flask` `Pandas` `NumPy` `gTTS` `FFmpeg`

---

## 🍽️ QRAVE — Smart Contactless Ordering & POS Platform

A production-oriented restaurant ordering platform connecting customers, restaurant staff and kitchen operations through a real-time ordering system.

### What I built

- QR-based digital menus
- Customer ordering workflows
- Restaurant and kitchen management
- Digital order display
- Razorpay payment integration
- JWT authentication
- HMAC-SHA256 webhook verification
- Supabase real-time synchronization
- API rate limiting
- `p-queue` concurrency control
- PostgreSQL relational architecture
- REST APIs

```text
Customer
   ↓
React Application
   ↓
Node.js / Express API
   ↓
PostgreSQL / Supabase
   ↓
 ┌───────────────┬────────────────┐
 ↓               ↓                ↓
Payments      Kitchen          Display
Razorpay      Dashboard        Board
 └───────────────┴────────────────┘
           Real-Time Sync
```

**Tech:** `React` `JavaScript` `Node.js` `Express.js` `PostgreSQL` `Supabase` `REST APIs` `Razorpay` `JWT` `Tailwind CSS` `WebSockets`

**Live:** https://qravee.me/

---

## 🛕 BhaktiPatham — AI Telugu Temple Assistant

An AI-powered multilingual platform designed to provide information and assistance related to Telugu temples.

### What I built

- AI chatbot
- Multilingual support
- Temple information database
- Intelligent information retrieval
- LLM integration
- Structured temple knowledge
- Conversational interface

**Tech:** `Python` `Streamlit` `LLMs` `GPT-4` `Gemini` `RAG` `Googletrans`

---

# 💼 Experience

## AI & Data Engineering Intern — Viswam.AI / IIIT Hyderabad

Worked on AI application development and multilingual data engineering for Telugu Large Language Model development.

- Built AI applications and backend services using **Python and FastAPI**.
- Developed AI applications using **Streamlit and Hugging Face**.
- Worked with **LLM-based applications and RAG workflows**.
- Contributed to multilingual text, audio and video data workflows.
- Performed data validation and quality assurance.
- Worked on debugging, testing and deployment.
- Collaborated in an AI-focused engineering environment.

---

# 🛠️ Technical Skills

### 👨‍💻 Programming Languages

`Python` `Java` `JavaScript` `TypeScript` `SQL` `C++` `Bash`

### 🤖 Generative AI

`Generative AI` `LLMs` `Agentic AI` `AI Agents` `Prompt Engineering` `RAG`

`Tool Calling` `Multi-Agent Systems` `Multimodal AI` `Structured Outputs`

### 🔗 Agentic AI

`LangGraph` `LangChain` `Stateful Workflows` `Conditional Routing`

`Agent Memory` `Tool Integration` `Multi-Agent Orchestration`

### 🧠 AI / Machine Learning

`PyTorch` `Deep Learning` `Model Inference` `Model Evaluation`

`Hugging Face` `Computer Vision` `Image Processing`

### 👁️ Computer Vision

`OpenCV` `YOLOv8` `MobileNetV2` `ResNet50`

`Segment Anything` `EasyOCR` `InsightFace` `GFPGAN` `Pillow`

### ⚙️ Backend Engineering

`FastAPI` `Flask` `Node.js` `Express.js`

`REST APIs` `WebSockets` `SSE` `Async Processing`

### 🎨 Frontend Engineering

`React` `TypeScript` `JavaScript`

`HTML5` `CSS3` `Tailwind CSS` `React-Konva` `Vite`

### 🗄️ Databases & Data

`PostgreSQL` `MySQL` `Supabase` `Redis`

`ChromaDB` `Pandas` `NumPy` `SQL`

### ☁️ DevOps & Infrastructure

`Docker` `Git` `GitHub` `GitHub Actions`

`Linux` `CI/CD` `BullMQ` `Pytest` `Vitest`

---

# 🏗️ Engineering Principles

I try to approach AI engineering as a software engineering problem first.

```text
                    ┌──────────────────┐
                    │   Real Problem   │
                    └────────┬─────────┘
                             ↓
                    ┌──────────────────┐
                    │ Workflow Analysis│
                    └────────┬─────────┘
                             ↓
              ┌─────────────────────────────┐
              │   Simplest Useful System   │
              └──────────────┬──────────────┘
                             ↓
          ┌────────────────────────────────────┐
          │ AI / LLM / Agent / ML Model        │
          └────────────────┬───────────────────┘
                           ↓
              ┌─────────────────────────┐
              │ APIs + Tools + Data     │
              └────────────┬────────────┘
                           ↓
              ┌─────────────────────────┐
              │ Backend + Infrastructure│
              └────────────┬────────────┘
                           ↓
              ┌─────────────────────────┐
              │ Testing + Reliability   │
              └────────────┬────────────┘
                           ↓
              ┌─────────────────────────┐
              │ Production Deployment   │
              └─────────────────────────┘
```

---

# 🔬 Areas I'm Exploring

- Agentic AI
- Stateful AI systems
- LLM orchestration
- Retrieval-Augmented Generation
- Multimodal AI
- AI-powered automation
- AI evaluation
- Computer Vision
- AI developer tools
- Intelligent enterprise workflows
- Production AI infrastructure
- Distributed backend systems

---

# 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=snehithkumar18&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" height="180"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=snehithkumar18&layout=compact&theme=github_dark&hide_border=true" height="180"/>

</div>

---

# 📫 Let's Connect

I'm interested in collaborating on:

- AI-powered products
- Agentic AI systems
- LLM applications
- Computer Vision
- AI automation
- Backend systems
- Developer tools
- Open-source projects

<div align="center">

<a href="https://github.com/snehithkumar18">
<img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/snehith-kumar-4266071b8/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:snehithkumarbarkam@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

<div align="center">

### Building useful systems, not just AI demos.

</div>
