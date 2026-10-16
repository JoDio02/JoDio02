# Oğuzhan Altuntaş

**Backend Software Developer · Java / Spring Boot · Python · PostgreSQL · AI integration**  
Ankara, Türkiye · Open to relocating to Canada (Ottawa preferred)

I'm the only engineer at a legal-tech startup, where I keep a production AI legal-research platform running (Python microservices, React, PostgreSQL, Google Cloud). Before that I interned at **HAVELSAN** (PostgreSQL high availability, Ansible) and **ASELSAN** (fine-tuning LLMs). I like backend systems that are tested, observable and boring to operate.

[LinkedIn](https://www.linkedin.com/in/oguzhan-altuntas) · [Email](mailto:oguzhanaltuntas2002@gmail.com)

---

## Featured projects

### Travel Mail AI: email automation for travel agencies (private repo, code available on request)
`Python` `FastAPI` `Celery` `Redis` `PostgreSQL` `Ollama` `React` `TypeScript` `Docker`
- Reads partner reservation emails over IMAP, extracts booking data with a **local LLM constrained by JSON Schema**, and writes approved bookings to a master Excel file.
- Celery + Redis queues with retries and scheduled jobs, plus SPF/DKIM/DMARC sender checks. Per-field confidence scores send doubtful results to an operator for review.
- **900+ pytest tests**, AES-256-GCM encryption for personal data, an offline data network, and one-command installers for Windows and Linux.

### [AI Face Verification](https://github.com/JoDio02/AI-face-verification): identity check with liveness detection
`Python` `ONNX Runtime` `RetinaFace` `ArcFace` `MiniFASNet` `OpenCV`
- Face matching plus passive anti-spoofing, built as the verification service for a dating app backend.

### White Collar Dating App: backend developer, team of 4
`Java` `Spring Boot` `PostgreSQL` `pgvector` `PostGIS` `RabbitMQ` `Firebase` `MinIO`
- Spring Boot backend for auth, profiles, matching and messaging. Semantic recommendations with pgvector embeddings, location filtering with PostGIS, and async RabbitMQ jobs that call the Python AI services.

### [PlateIn](https://github.com/JoDio02/platein-back-end): diet-tracking web app (graduation project, team of 3)
`Java` `Spring Boot` `MySQL` `Vision Transformer`
- I owned the backend, database, REST APIs and AI parts. A ViT model sorts food photos into 101 dishes (Food-101) and the app returns their nutrition data.

---

## Experience
- **Software Developer, İçtiHub**: Aug 2026 – present. Shipped 30+ production fixes and features to a RAG legal assistant; rebuilt an MCP connector with OAuth so Claude and ChatGPT users can search court decisions.
- **Database & DevOps Intern, HAVELSAN**: 2025. Ran a 4-node PostgreSQL HA cluster (Patroni, etcd, HAProxy) and automated it with Ansible.
- **AI Intern, ASELSAN**: 2024. Fine-tuned GPT-2 with Hugging Face Transformers for a Turkish dictionary prototype.

## Tech
- **Languages:** Java, Python, TypeScript, JavaScript, SQL, C
- **Backend:** Spring Boot, FastAPI, REST, RabbitMQ, Celery, microservices
- **Data:** PostgreSQL (Patroni, pgvector, PostGIS), MySQL, Redis, MongoDB
- **AI:** RAG, embeddings, local LLMs (Ollama), Hugging Face, ONNX, OpenCV
- **Ops:** Docker, Google Cloud, Linux, Ansible, Git

🎓 B.Sc. Software Engineering, Çankaya University (English-medium), 2026 · English C1
