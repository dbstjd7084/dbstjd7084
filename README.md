# Hi, I'm YunSeong! 👋

> **"Building reliable AI that solves real-world problems."**

Hi there! I'm **YunSeong**, a problem-solving AI developer working across the full lifecycle—from domain-specific data curation and lightweight fine-tuning (PEFT) to multi-agent systems.

Rather than stopping at model training, I focus on building trustworthy projects through **inference latency optimization under constrained resources**, **LLM hallucination control**, and **custom benchmark dataset construction and evaluation**.

---

## 🎯 Core Focus
- **Agentic AI & Hybrid RAG:** Designing LangGraph-based self-correction workflows and hybrid retrieval architectures combining VectorDB (FAISS) and GraphDB (Neo4j).
- **Domain-Specific Fine-Tuning:** Applying parameter-efficient fine-tuning (LoRA/DoRA) and inference acceleration tailored to domain data across Whisper, KLUE-RoBERTa, and BGE-M3.
- **End-to-End Implementation:** Delivering complete solutions spanning data crawling and preprocessing pipelines to FastAPI, Streamlit, and Android (Kotlin) applications.

---

## 🛠 Tech Stack

**Applied AI & LLM**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2B5B84?style=flat-square&logo=python&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-00A67E?style=flat-square&logo=openai&logoColor=white)

**Search & Database**  
![FAISS](https://img.shields.io/badge/VectorDB%20(FAISS)-0467DF?style=flat-square&logo=meta&logoColor=white)
![Neo4j](https://img.shields.io/badge/GraphDB%20(Neo4j)-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Backend, App & Infra**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 🚀 Featured Projects

### 1. [Beauty-Schema-Agent | Automated E-Commerce JSON-LD Schema Markup Agent](https://github.com/dbstjd7084/Beauty-Schema-Agent)
> **Automated over 90% of manual SEO workload using a LangGraph-based self-correction multi-agent architecture**
- **Problem:** High manual overhead of applying Schema.org markups across thousands of e-commerce pages, alongside severe token waste and URL hallucinations when using raw LLMs.
- **Tech Stack:** `Python`, `LangGraph`, `Pydantic v2`, `FastAPI`, `BeautifulSoup4`, `LangSmith`
- **Key Contributions:**
  - Reduced token consumption by **over 60%** and eliminated URL hallucinations via a media key mapping/remapping preprocessing algorithm (`[IMG_001]`).
  - Separated `Classifier`, `Extractor`, and `Validator` nodes with a Pydantic-driven **backtracking self-correction loop**, generating valid schemas in **1.46 seconds** per page.

### 2. [119-Emergency-STT-Whisper | Real-Time 119 Emergency Call STT System](https://github.com/dbstjd7084/119-Emergency-STT-Whisper-)
> **Overcame background noise in urgent emergency calls and achieved a 10x inference speedup (81.41s → 8.17s)**
- **Problem:** Degraded recognition accuracy caused by low-frequency (8kHz) telephony audio, background noise, and urgent speech, coupled with high inference latency on long calls.
- **Tech Stack:** `Python`, `PyTorch`, `Whisper / Faster-Whisper`, `PEFT (LoRA/DoRA)`, `Streamlit`, `Librosa`
- **Key Contributions:**
  - Built an audio signal preprocessing pipeline featuring 16kHz mono normalization and sub-500ms silence/noise filtering.
  - Applied **DoRA fine-tuning** and **30-second chunking** to `Whisper Large-v3-turbo`, reducing **CER (Character Error Rate) by ~60%** and cutting inference time by 10x.

### 3. [K-PopularOpinionDataSet | Multi-Task Political Comment Analysis Model (Target, Sentiment & Toxicity)](https://github.com/dbstjd7084/K-PopularOpinionDataSet)
> **Constructed a Korean political opinion benchmark dataset and achieved 99% target candidate recognition accuracy**
- **Problem:** Lack of standardized datasets and models capable of simultaneously identifying target candidates, sentiment, and toxicity amidst slang, nicknames, and sarcasm in political comments.
- **Tech Stack:** `Python`, `KLUE-RoBERTa`, `PyTorch`, `AdamW`, `YouTube Data API v3`
- **Key Contributions:**
  - Collected and curated 30,647 YouTube comments from major presidential debates to build a multi-dimensional annotated dataset (**Presented at KDBC 2025**).
  - Introduced a candidate nickname dictionary and `[ENT]` entity marking preprocessing, achieving **99% candidate recognition accuracy** and **0.795 toxicity F1-score**.

---

## 📦 More Repositories on GitHub
- **[Ko-Pixel (Pixel-ART)](https://github.com/kgty0707/Pixel-ART)** — Korean culture-specialized pixel art generation platform powered by Stable Diffusion v1.5 and Multi-Adapter LoRA (LCM, Style, Context) *(2025 SeSAC Hackathon)*
- **[DogCatgorithm (멍냥고리즘)](https://github.com/dbstjd7084/dogcatgorithm)** — Android app offering GPT-4o-mini personalized pet video curation and pet-friendly facility search via Google Maps & Public Data APIs
- **[Dating App](https://github.com/dbstjd7084/dating)** — Android social matching and real-time chat app integrating TensorFlow Lite on-device image inference and Firebase

---

## 📫 Contact
- **Email:** `dbstjd7084@naver.com`
