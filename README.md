
<div align="center">

# Hey, I'm Arnav Deep 👋

### Systems Programming • Rust Engineering • AI & Backend Development

**Building reliable software. Understanding systems. Engineering beyond abstractions.**

Computer Science Undergraduate | Rust Developer | SIH 2025 Finalist

[![GitHub](https://img.shields.io/badge/GitHub-DeepArnav1102-181717?style=for-the-badge&logo=github)](https://github.com/DeepArnav1102)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arnav_Deep-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/arnav-deep-6b5950381)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deeparnav777@gmail.com)


</div>

---

## 🧠 About Me

I'm **Arnav Deep**, a Computer Science and Engineering undergraduate at **Dr. B. C. Roy College of Engineering, Durgapur**, passionate about systems programming, backend engineering, and building reliable software infrastructure.

I enjoy working close to the fundamentals of computing — understanding how systems work internally, designing efficient algorithms, and building tools rather than simply relying on existing abstractions.

My primary interests lie at the intersection of **Systems Programming, Developer Infrastructure, and AI Engineering**.

- 🦀 Building systems software and developer tools with **Rust**.
- ⚙️ Exploring version control internals, parsers, and software architecture.
- 🤖 Developing AI-powered applications and Retrieval-Augmented Generation systems.
- 🌐 Designing scalable backend systems and efficient REST APIs.
- 🧪 Interested in performance engineering, testing, and software reliability.
- 🏆 **Smart India Hackathon 2025 Finalist**.
- 📦 Published an independent Rust crate on **crates.io**.

> "Don't just use the tools. Understand them. Build them. Improve them."

---

## 🚀 Featured Projects

### 🦀 Rusty — A Version Control System

A Git-inspired version control system engineered from scratch in Rust, focusing on content-addressed storage, repository integrity, efficient object synchronization, and merge operations.

**Key Engineering Highlights:**

- Designed a chunked batch object-synchronization protocol supporting 100 objects per request.
- Reduced synchronization round-trips by 99% (approximately 1,000 to 5).
- Improved synchronization latency from 50 seconds to 0.25 seconds — approximately 200× faster.
- Implemented `rusty fsck`, a repository integrity engine with 17 error codes across 5 severity levels.
- Built parallel SHA-256 DAG traversal using Rayon and memory-mapped I/O.
- Developed a three-way merge engine supporting four conflict types.
- Validated merge functionality with 29 unit tests.

**Tech Stack:**

`Rust` `Ratatui` `Rayon` `Reqwest` `SHA-256` `Serde`

🔗 [Explore Rusty](https://github.com/DeepArnav1102/rusty)

---

### 📚 RAG Matrix — Multi-Tenant RAG Platform

An intelligent document retrieval platform that enables users to interact with PDF documents through natural language using Retrieval-Augmented Generation.

**Key Engineering Highlights:**

- Built a document ingestion pipeline using FastAPI and PyMuPDF.
- Implemented 800-character chunking with 100-character overlap.
- Integrated local 384-dimensional ONNX embeddings, reducing vectorization latency by approximately 40%.
- Implemented pgvector cosine-similarity search, retrieving the top 5 relevant chunks in under 150ms.
- Integrated Gemini for context-grounded answer generation.
- Achieved sub-1.5-second end-to-end response times.
- Implemented multi-tenant isolation across document and chat endpoints using JWT, Google OAuth 2.0, and ownership checks.

**Tech Stack:**

`Python` `FastAPI` `React` `Express.js` `PostgreSQL` `pgvector` `ONNX` `PyMuPDF` `Gemini`

🔗 [Explore RAG Matrix](https://github.com/DeepArnav1102/rag-matrix)

---

### 🔍 NC-Parser — ANSI/ECMA-48 Terminal Parser

An independent, zero-dependency Rust crate designed to parse ANSI/ECMA-48 escape sequences through an incremental parsing architecture.

Built as reusable parsing infrastructure for terminal emulators, terminal applications, and developer tools.

**Key Engineering Highlights:**

- Developed a zero-dependency incremental parser with 7 event types and 10 modules.
- Implemented `no_std` support for resource-constrained environments.
- Published the crate on **crates.io**.
- Achieved parsing throughput of 76 MB/s on plain text and 44 MB/s on dense ANSI input.
- Built a headless 80×24 virtual terminal with `Screen` and `ScreenDiff` abstractions.
- Implemented ANSI diff generation at 52 MB/s.
- Enabled snapshot testing and ANSI-to-HTML/SVG rendering without requiring a PTY.
- Validated with 68 integration tests, 5 libFuzzer targets, and 2 proptest suites.

**Tech Stack:**

`Rust` `no_std` `ANSI/ECMA-48` `libFuzzer` `proptest`

🔗 [Explore NC-Parser](https://github.com/DeepArnav1102/nc-parser)

---

## 💻 Technical Skills

### Programming Languages

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Frontend Development

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend Development

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### Databases & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Core Concepts

- Data Structures and Algorithms
- Systems Programming
- REST API Design
- Database Management
- Unit Testing and Software Reliability
- Version Control Internals
- Performance Optimization

---

## 🏆 Achievements

- 🥇 **Smart India Hackathon Finalist — 2025**
- 📦 Published **NC-Parser**, an independent Rust crate on crates.io.
- 💡 Solved **150+ LeetCode problems**.
- ⚡ Engineered a version-control synchronization protocol achieving approximately 200× faster synchronization.

---

## 🎯 Engineering Philosophy

I am particularly interested in the intersection of:

**Systems Programming × Developer Infrastructure × Artificial Intelligence**

My goal is to become an engineer who can design, understand, and build reliable software systems from the ground up.

I believe in:

- **Building over just consuming** — understanding the internals of the tools I use.
- **Performance with correctness** — optimizing without compromising reliability.
- **Engineering fundamentals** — strong foundations in algorithms, systems, and architecture.
- **Continuous experimentation** — exploring ideas beyond conventional application development.
- **Open source** — building reusable tools and contributing to the developer ecosystem.

---

## 🤝 Let's Connect

I'm always interested in discussing systems programming, Rust, backend engineering, AI infrastructure, open source, and interesting engineering challenges.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-DeepArnav1102-181717?style=for-the-badge&logo=github)](https://github.com/DeepArnav1102)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arnav_Deep-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/arnav-deep-6b5950381)

[![Email](https://img.shields.io/badge/Email-deeparnav777%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deeparnav777@gmail.com)

</div>

---
