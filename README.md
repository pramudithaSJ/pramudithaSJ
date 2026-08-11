# Pramuditha Jayawardhana

MSc student in Information Systems at **Uppsala University**, specialising in AI and machine learning.
Previously BSc (Hons) in Software Engineering at SLIIT, Sri Lanka.

I build production systems for medical device and healthcare companies, and I publish on computer vision for assistive technology.

Open to internships and part-time work in Sweden — **software, data and AI engineering**.

📍 Uppsala, Sweden · ✉️ pramuditha.sj@gmail.com · [LinkedIn](https://www.linkedin.com/in/pramuditha-jayawardhana/)

---

## Published research

Two IEEE papers on a smart glass that helps visually impaired students take part in STEM classes. I trained the detection models and built the edge inference pipeline.

- **Enhancing Learning Experiences for Visually Impaired Students with AI and Machine Learning on Smart Device** — HORA 2024 · [10.1109/HORA61326.2024.10550610](https://doi.org/10.1109/HORA61326.2024.10550610)
- **Enhancing STEM Education Accessibility for Blind and Low Vision Students** — ICCCNT 2024 · [10.1109/ICCCNT61001.2024.10725667](https://doi.org/10.1109/ICCCNT61001.2024.10725667)

Code: [VE-Server](https://github.com/pramudithaSJ/VE-Server) (Python, YOLOv8, ncnn) · [VE-Mobile-App](https://github.com/pramudithaSJ/VE-Mobile-App) (Flutter)

---

## What I work on

Most of my recent work sits in private client repositories, so here is what it actually is.

### ProtoMed — order management for patient-specific medical implants
`TypeScript` `Node.js` `Express` `MongoDB` `Next.js` `Azure`

Around 45,000 lines across a Next.js front end and an Express API built as 27 domain modules — CT imaging, implant design, quality control, printing, inventory, quotations, payments. JWT auth with role-based access control, patient-privacy middleware, and a full audit trail. CT scans and design files in Azure Blob Storage. Order documents generated server-side as PDFs with barcodes and QR codes. Database backups run on a scheduled GitHub Actions job with a command-line restore path.

Runs in production for teams in Sri Lanka, Singapore and Malaysia, with each country's patient data kept isolated.

### InkLessQ — AI-assisted quality management for ISO 9001 and ISO 13485
`Python` `FastAPI` `SQLAlchemy` `Celery` `Redis` `PostgreSQL` `Claude API` `Next.js`

A multi-tenant compliance platform. The interesting part is a dynamic forms engine: form templates are stored as JSONB and act as the schema for the records filled against them, so new document types need no migration. Signed records freeze to PDF as audit evidence. Document analysis runs asynchronously in a separate internal FastAPI service on Celery and Redis.

Built with two medical device manufacturers as design partners.

### Voizon — AI agent for WhatsApp, voice notes and live calls
`Node.js` `Claude API` `MongoDB Atlas Vector Search` `Voyage AI` `Deepgram` `Azure Speech` `WebRTC` `Redis`

Retrieval-augmented generation over a client knowledge base: Voyage AI embeddings stored in MongoDB Atlas, searched by vector similarity, then passed to Claude. One reasoning layer serves all three channels, so text, voice notes and live calls share the same knowledge base. Speech-to-text through Deepgram, text-to-speech through Azure Speech, streamed over WebRTC for live calls.

### GalleExpress — revenue forecasting for a bus operator
`Python` `FastAPI` `scikit-learn` `pandas` `Next.js` `MongoDB`

31 engineered features from raw daily takings — lags at 1, 7 and 14 days, rolling means over 7, 14 and 30 days, sine and cosine encoding of month and weekday, per-vehicle encoding, maintenance flags. Random Forest regressors for revenue, expenses and net income, at company and per-vehicle level, evaluated on held-out data and served through FastAPI to a management dashboard.

---

## Tools

**ML and AI** — Python · PyTorch · TensorFlow/Keras · YOLOv8 · scikit-learn · OpenCV · pandas · NumPy · ncnn · RAG and vector search · Claude API

**Data and backend** — FastAPI · Flask · Node.js · Express · TypeScript · PostgreSQL · MongoDB · Redis · Celery · BullMQ · WebSocket · WebRTC

**Cloud** — Azure (Blob Storage, App Service, Speech) · Supabase · Firebase · Vercel · GitHub Actions

**Frontend** — Next.js · React · Tailwind CSS · shadcn/ui · Flutter

---

## Also here

Teaching: I lectured Data Structures and Algorithms, Probability and Statistics, Database Systems and mobile and web development at SLIIT Kandy for a year and a half.

Languages: English (professional), Sinhala (native), Swedish (learning).
