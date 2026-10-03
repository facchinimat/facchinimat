# Matteo Facchini

**Computer Science @ Stony Brook University | Backend, Infrastructure & AI Systems**

I'm a junior Computer Science student at **Stony Brook University**, graduating in **May 2028**, interested in building reliable backend, infrastructure, distributed, and AI systems.

I'm currently conducting **GPU systems research at Stony Brook's PACE Lab** and building **ForgeCI**, a CI/CD infrastructure platform inspired by the systems behind tools like GitHub Actions and CircleCI.

I'm seeking **Summer 2027 Software Engineering internships**, particularly in backend engineering, infrastructure/platform engineering, systems, and AI infrastructure.

[![Portfolio](https://img.shields.io/badge/Portfolio-Website-111111?style=flat-square)](https://matteo-portfolio-sage.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Matteo%20Facchini-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matteo-facchini-b14667352/)
[![Email](https://img.shields.io/badge/Email-matteofac12%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:matteofac12@gmail.com)

---

## Research

### Undergraduate Researcher — PACE Lab
**Stony Brook University | Advisor: Prof. Anshul Gandhi**

Working on GPU systems research focused on **resource sharing, workload co-location, performance isolation, and resource partitioning**.

- Investigating GPU resource sharing using **NVIDIA MPS** and **CUDA Green Contexts**
- Benchmarking Transformer workloads on remote **Linux GPU nodes**
- Evaluating workloads under varying GPU compute allocations
- Measuring **latency and throughput** to characterize interference between concurrent workloads
- Comparing GPU-sharing mechanisms and workload characteristics to study resource-allocation tradeoffs

**Focus:** GPU Systems · ML Infrastructure · Performance Benchmarking · Linux · CUDA

---

## Featured Projects

### [ForgeCI](https://github.com/facchinimat/ForgeCI) — CI/CD Infrastructure Platform

A backend and infrastructure project exploring how modern CI/CD systems authenticate events, persist build state, schedule work, execute jobs, and recover from failures.

**Implemented**
- Built a **FastAPI** backend with health-check and GitHub webhook endpoints
- Integrated real GitHub `push` event processing
- Authenticated webhook requests using **HMAC-SHA256**
- Extracted repository, branch, and commit metadata from incoming events
- Implemented **PostgreSQL-backed build-state persistence** using SQLAlchemy
- Created persistent `Build` records for authenticated GitHub pushes
- Added automated API, webhook-security, malformed-payload, and persistence tests with **pytest**
- Isolated automated tests from development data using a temporary **SQLite** test database
- Configured **GitHub Actions** to run the test suite on pushes and pull requests
- Managed secrets and database configuration through environment variables

**Next**
- Redis-backed job queue
- CI worker processes
- Repository cloning and commit checkout
- Docker-isolated test execution
- Concurrent workers
- Job leases, heartbeats, retries, and failure recovery
- GitHub Checks API integration
- Deployment, observability, and performance benchmarking

**Tech:** Python · FastAPI · PostgreSQL · SQLAlchemy · psycopg · pytest · GitHub Actions · GitHub Webhooks

---

### [CourseLens AI](https://github.com/facchinimat/CourseLens_AI) — RAG Course Document Assistant

An AI-powered study assistant that lets students upload course PDFs and ask natural-language questions grounded in their own course material.

- Built a complete **Retrieval-Augmented Generation (RAG)** pipeline
- Extracted page-level text from uploaded PDFs using **PyMuPDF**
- Chunked documents while preserving source and page metadata
- Generated vector embeddings with the **OpenAI API**
- Indexed and retrieved document chunks using **ChromaDB**
- Generated source-grounded LLM answers with filename and page citations
- Developed **10+ FastAPI REST endpoints** for course management, PDF ingestion, chunking, indexing, search, and question answering
- Added persistent course and document metadata
- Built a **Streamlit** chat interface for document upload and course Q&A

**Tech:** Python · FastAPI · OpenAI API · ChromaDB · PyMuPDF · Pydantic · Streamlit

---

## Technical Skills

**Languages**  
Python · Java · C · TypeScript · SQL

**Backend & Data**  
FastAPI · REST APIs · PostgreSQL · SQLAlchemy · ChromaDB

**Frontend**  
React · Next.js

**Systems & Infrastructure**  
Linux · Docker · Git · GitHub · GitHub Actions · CI/CD · pytest

**AI**  
RAG · Embeddings · Vector Search · OpenAI API

---

## Involvement

### AI Community — Agentic AI Competition
**Stony Brook University**

Collaborating on an **LLM-based agent** designed around planning, tool use, and multi-step task execution as part of an internal agentic AI competition.

---

## Current Focus

I'm currently deepening my experience in:

**Distributed Systems · Backend Infrastructure · Concurrency · Job Queues · Fault Tolerance · Containerized Execution · Systems Performance · AI Infrastructure**

---

## Contribution Activity

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/facchinimat/facchinimat/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/facchinimat/facchinimat/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="GitHub contribution activity"
    src="https://raw.githubusercontent.com/facchinimat/facchinimat/output/github-contribution-grid-snake.svg"
  />
</picture>

---

## Contact

- **Portfolio:** [matteo-portfolio-sage.vercel.app](https://matteo-portfolio-sage.vercel.app/)
- **LinkedIn:** [linkedin.com/in/matteo-facchini-b14667352](https://www.linkedin.com/in/matteo-facchini-b14667352/)
- **Email:** [matteofac12@gmail.com](mailto:matteofac12@gmail.com)
