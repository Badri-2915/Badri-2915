<div align="center">

# Badri Narayana Pamisetty

### Backend Software Engineer

Python · Go · Distributed Systems · Event-Driven Microservices

<a href="https://www.linkedin.com/in/badri-narayana-pamisetty"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjk0OCAxLjYzNy0xLjk1IDMuMzctMS45NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMSAxIDAtNC4xMjUgMi4wNjIgMi4wNjIgMCAwIDEgMCA0LjEyNXpNNy4xMTkgMjAuNDUySDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:badripamisetty13@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/Badri-2915"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<a href="https://eventhub-swart-xi.vercel.app"><img src="https://img.shields.io/badge/EventHub-Live-111827?style=flat-square&logo=vercel&logoColor=white" alt="EventHub live"></a>
<a href="https://2goi.in"><img src="https://img.shields.io/badge/2GOI-Live-0F766E?style=flat-square&logo=fastapi&logoColor=white" alt="2GOI live"></a>
<a href="https://badri.online"><img src="https://img.shields.io/badge/Ghost_Chat-Live-6D28D9?style=flat-square&logo=socketdotio&logoColor=white" alt="Ghost Chat live"></a>

</div>

---

## About me

I build backend systems that stay correct under load.

- **1.5+ years** building production Python microservices at **Enphase Energy**, serving **1M+ solar and battery sites**
- Comfortable with **Kafka, AWS SQS/S3, Redis, MongoDB, PostgreSQL** and async processing
- Resolved **20+ production incidents**, from root cause to permanent fix
- On my own time I build in **Go** and **React**, with a focus on concurrency, idempotency and testing

---

## Experience

| Role | Company | Years | Highlights |
|---|---|---|---|
| **Software Engineer I** | [Enphase Energy](https://enphase.com) | 2025 – 2026 | Python microservices for **1M+ sites** · Kafka · SQS · Redis · **20+ incidents** resolved |
| **Software Engineer Intern** | [Continental](https://www.continental.com) | 2023 – 2024 | Python release automation · **4 h 20 min → 40 min** |

---

## Education

| Degree | Institute | Years | CGPA |
|---|---|---|---|
| **Integrated M.Tech, Computer Science and Engineering (Data Science)** | [Vellore Institute of Technology](https://vit.ac.in) | 2019 – 2024 | **8.15 / 10** |

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [EventHub](https://github.com/Badri-2915/eventhub)
**Event ticketing where a seat can never be sold twice**

Go · Gin · PostgreSQL · Redis · React · TypeScript

- Atomic conditional updates, ordered row locks and `CHECK` constraints
- **1,000** concurrent buyers for one seat → exactly **1** winner, **0** deadlocks
- **70 automated tests** in CI · k6: **~350 bookings/s**, 0% errors
- Live seat maps over Redis + SSE, QR tickets, door check-in

[Live demo](https://eventhub-swart-xi.vercel.app) · [Code](https://github.com/Badri-2915/eventhub)

</td>
<td width="50%" valign="top">

### [CodeLens AI](https://github.com/Badri-2915/ai-dev-platform)
**Ask questions about any GitHub codebase in plain English**

Next.js · TypeScript · PostgreSQL (pgvector) · Docker · LLMs

- End-to-end **RAG** pipeline: ~60-line code chunks → embeddings → pgvector
- Top-10 cosine-similarity retrieval within a ~4K-token budget
- Answers grounded in real code, with file and line citations
- One interface for OpenAI or a local Ollama model

[Code](https://github.com/Badri-2915/ai-dev-platform)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [2GOI](https://github.com/Badri-2915/2goi)
**Production URL shortener**

FastAPI · React · PostgreSQL · Redis

- Base62 short codes from sequential IDs, so no collision checks
- Redis hot-link cache with PostgreSQL fallback
- Pre-aggregated click analytics, QR codes, custom aliases

[Live](https://2goi.in) · [Code](https://github.com/Badri-2915/2goi)

</td>
<td width="50%" valign="top">

### [Ghost Chat](https://github.com/Badri-2915/ghost-chat)
**Privacy-first ephemeral messaging**

Node.js · Express · Socket.IO · React · Redis

- End-to-end encrypted (AES-GCM); the server never sees plain text
- Self-destructing messages with Redis TTLs, no database
- Typing indicators, read receipts and instant panic delete

[Live](https://badri.online) · [Code](https://github.com/Badri-2915/ghost-chat)

</td>
</tr>
</table>

---

## Tech stack

**Languages**

<img src="https://skillicons.dev/icons?i=py,go,cpp,js,ts&theme=light" alt="Languages">

**Backend and data**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,kafka,postgres,mysql,mongodb,redis&theme=light" alt="Backend and data">

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=light" alt="Frontend">

**Cloud and DevOps**

<img src="https://skillicons.dev/icons?i=aws,docker,githubactions,jenkins,linux,git&theme=light" alt="Cloud and DevOps">

---

## A bit more about me

I graduated from **Vellore Institute of Technology (VIT)** in 2024 with an Integrated M.Tech in Computer Science and Engineering, specialising in Data Science.

Since then, I've worked across the backend lifecycle: designing services and APIs, building event-driven pipelines, owning them in production, and debugging issues that cross several services. I enjoy taking ownership of a messy problem and driving it to a clean, reliable solution.

I'm curious by nature and like to understand not just how something works, but why. Along the way I've explored backend development, distributed systems, concurrency and applied AI (RAG and vector search), and each one has shaped how I think about building systems.

I value strong fundamentals, clear communication and honest engineering: measuring before claiming, and writing down the trade-offs. I enjoy working with a team and being someone others can rely on when production gets stressful.

Outside work, I enjoy playing badminton, chess and cricket.

---

<div align="center">

<a href="https://www.linkedin.com/in/badri-narayana-pamisetty"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjk0OCAxLjYzNy0xLjk1IDMuMzctMS45NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMSAxIDAtNC4xMjUgMi4wNjIgMi4wNjIgMCAwIDEgMCA0LjEyNXpNNy4xMTkgMjAuNDUySDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:badripamisetty13@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/Badri-2915"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

</div>
