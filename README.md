# Mariem Aissa — AI Engineer

[Portfolio](https://myraissa.github.io/aissa-mariem-portfolio/) • [LinkedIn](https://linkedin.com/in/mariem-aissa-b16244222) • [Email](mailto:mariem.aissa@ensi-uma.tn)

---

I build AI systems that ship to production — not notebooks, not demos. My work spans LLM pipelines, real-time computer vision, and full-stack AI applications. Every project in my pinned repos has a reference letter behind it.

Currently: building a privacy-preserving on-premise LLM system for Saudi enterprise project analytics.  
Previously: built Tunisia's first real-time sign language translation API (30 FPS, text/audio/video → animated avatar), and an AI regulatory compliance copilot for a German MedTech company (60% documentation time reduction, in production).

---

## What I've shipped

### Beem 360 — On-Premise LLM System
*AI Engineer · DAL Digital, Saudi Arabia · March 2026 – Present*

Privacy-preserving LLM system for enterprise project data — sensitive data never leaves the client's infrastructure.

- Docker-based deployment; multi-level pipeline: task summarisation and translation through to sub-company historical performance aggregation
- Automated PDF report generation for investor and stakeholder reporting (budget breakdowns, employee directories, project status)

`Python` `Docker` `Ollama/Llama` `PDF Generation` `LLM Systems` 

---

### BridgSign — Real-Time Sign Language AI
*AI Engineer · Tradrly, Tunisia · May 2025 – Feb 2026*

End-to-end pipeline: text, audio, or video input → animated sign language avatar at 30 FPS.  
Built the entire AI stack from scratch — no existing dataset, no prior work to reference.

- Recorded and processed 1,000+ expert sign units: MediaPipe pose extraction, torso normalization, forward kinematics finger rotations, facial blendshapes for lip-sync
- Engineered NLP grammar layer (spaCy + Gemini API) for text → gloss conversion, supporting Tunisian, French, and English Sign Language
- Smoothed concatenated motion sequences using Savitzky–Golay filtering and cubic spline interpolation
- Integrated ASR for Arabic/French audio input; defined JSON motion schema with Unity developer for WebGL playback
- Shipped as a Flask API; mentored 2 interns on pipeline extensions

`Python` `MediaPipe` `OpenCV` `Flask` `spaCy` `Gemini API` `Signal Processing`

---

### meddevo AI Copilot — Regulatory Compliance (MedTech)
*AI Software Engineer Intern · dytab GmbH, Germany · May 2024 – Nov 2024*

AI copilot for EU MDR medical device documentation — built and deployed to real customers.

- RAG system with GPT-4 and EU MDR knowledge bases for context-aware generation
- Streaming infrastructure via Server-Sent Events for real-time AI feedback
- Full workflow engine: TypeScript + Angular + NestJS + MongoDB
- 85% test coverage; worked directly with regulatory affairs consultants and early customers
- Reduced documentation time by 60%; improved response precision through iterative prompt optimization

`GPT-4` `RAG` `TypeScript` `Angular` `NestJS` `MongoDB` `Docker` `GitHub Actions`

---


### MindSync AI — Mental Health Companion
*Personal project · [Live Demo](https://mindsync-ai-akywxsuhxjkwb6onu4c6ts.streamlit.app/) · [GitHub](https://github.com/myraissa/MindSync-AI)*

Production-deployed mental health chatbot with crisis detection, emotion tracking across 6 emotion classes, and trilingual support (English, French, Arabic).

`Llama 3.1` `DistilBERT` `HuggingFace` `Streamlit` `PyTorch`

---

## Technical skills

**LLM & AI systems:** RAG pipelines, prompt engineering, agent workflows, LangChain, LangGraph, GPT-4, Gemini, Llama/Ollama, on-premise LLM deployment  
**Computer vision:** MediaPipe, OpenCV, pose estimation, motion capture, signal processing (Savitzky–Golay, cubic spline interpolation)  
**NLP:** spaCy, DistilBERT, HuggingFace Transformers, ASR integration, text → gloss grammar transformation  
**Backend & APIs:** Python, FastAPI, Flask, NestJS, TypeScript, REST, Server-Sent Events  
**Infrastructure:** Docker, GitHub Actions, CI/CD, Linux  
**Databases:** MongoDB, MySQL, FAISS, SentenceTransformers  
**Testing:** Pytest, unit/integration testing (85% coverage in production systems)

---

## Education

**National School of Computer Science (ENSI)** — Computer Science Engineering Degree, 2021–2024  
Top-ranked Tunisian engineering school; admitted via national competitive exam (top 5% of science graduates)

---

## References

Reference letters available from:
- **Michael Kania, CEO — dytab GmbH (Germany)** · *"Extremely motivated. Always found sensible and practicable solutions. Went above and beyond the call of duty."*
- **Salah Sammari, CEO — Tradrly (Tunisia)** · *"Strong technical skills, professionalism, and a high level of commitment. I strongly recommend Ms. Mariem Aissa for any opportunity in Data Science."*

Full letters available on request 

---

*Engineering degree from Tunisia. Shipping production AI. Looking for the next hard problem*
