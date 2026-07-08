# Pablo Rejón Camacho

### Final-Year Computer Engineering Student | Full-Stack Developer & Systems Engineer

Final-year Computer Engineering student combining a rigorous academic background with hands-on corporate IT experience. I run my own production infrastructure — a hardened Linux VPS hosting every project below — and build with a strict *Secure by Design* mentality. Currently **IT Infrastructure Lead** at a biotechnology company.

**Erasmus Alumnus** at *Università degli Studi Roma Tre* (Rome, Italy) · **Cyber Málaga Bootcamp** (UMA, funded by Google).

---

## Featured Engineering Projects

### [Vessel](https://github.com/Pol3105/vessel-paas) — Self-Managed Micro-PaaS Engine (Open Source)
*A private Render/Fly.io running on a single VPS, written in Go.*
* **Orchestration:** Provisions containers via the Docker Engine API and hot-routes traffic with zero downtime through Caddy's admin HTTP API. Multi-tenant isolation with dynamic bridge networks; databases never expose public ports.
* **Security:** Loopback-bound API managed over SSH tunneling, constant-time token comparison (timing-attack mitigation), request body limits, high-entropy credentials via `crypto/rand`.
* **Stack:** Go, Docker Engine API, Caddy, PostgreSQL, Bash CLI.

### TriajIA — Multi-Tenant Hospital Triage Platform *(Closed Beta)*
* **Architecture & Security:** Multi-hospital architecture with middleware-enforced RBAC and an immutable clinical audit log (`EditLog`).
* **AI Integration:** Anthropic Claude SDK with adaptive prompting for patient autotriage kiosks; clinical algorithms (NEWS2, PEWS, pediatric dosing, allergy cross-checking).
* **Stack:** Next.js 14 (App Router), TypeScript, Prisma, PostgreSQL, Docker.

### [SkyFlow-Insights](https://github.com/Pol3105/SkyFlow-Insights) — Distributed Big Data Pipeline
* **Scale:** ~7M flight records (1.3 GB) processed on **AWS EMR** with S3, plus a full local cluster (HDFS, YARN, Hive + PostgreSQL metastore, Spark) via Docker Compose.
* **Rigor:** The same business logic implemented in **Hadoop MapReduce, Hive and Spark — identical row-for-row results across all three engines**. Every AWS failure documented with its fix (OOM sizing, schema drift, S3 path pitfalls).
* **Stack:** PySpark, HiveQL, Hadoop Streaming (Python), AWS EMR/S3, Docker.

### CampoSync — Agricultural Compliance SaaS + Big Data Layer
* **Compliance:** Digital Field Notebook (CUE) under Spanish FEGA/SIEX regulations — XML export validated against the ministry's official XSD schema.
* **Performance Engineering:** Benchmarked 4 retrieval methods (TF-IDF, BM25, pgvector embeddings) over the official catalogue, and the Hibernate N+1 problem with 100,000 records — **JOIN FETCH: 3.6× throughput, −72% P95 latency**, findings shipped to production search. Custom SQL indexing cut retrieval latency by 35%.
* **Stack:** Spring Boot (Java), React + Vite, PostgreSQL + pgvector, Python, Docker.

### Organizator — Self-Hosted Productivity Hub *(Cloud → VPS Migration)*
* **The Case Study:** Full migration off managed cloud (Vercel, Railway, Supabase) to a single self-hosted VPS — custom JWT + bcrypt auth replacing Supabase Auth, native `pg` parameterized queries, CI/CD via GitHub Actions over SSH.
* **Hardening:** DB bound to localhost only, cloud firewall (22/80/443), Fail2Ban, key-only SSH. In production with real daily use.
* **Stack:** React, Node.js/Express, PostgreSQL, Docker Compose, Caddy.

### [Samurai Defense](https://github.com/Pol3105/Samurai-Defense) — Complete 2D Game (Unity/C#)
* Shipped v1.0: 5-level campaign, auto-battler combat with multi-target AI, persistent upgrade shop, final boss, Android touch controls. From tutorial to credits.

---

## Stack & Systems Taxonomy

<table>
  <tr>
    <td valign="top" width="33%">
      <strong>Languages & Core</strong><br />
      • Java (Spring Boot)<br />
      • Python (data pipelines / scripting)<br />
      • JavaScript / TypeScript<br />
      • Go<br />
      • C# (Unity) / C++ / PHP / SQL
    </td>
    <td valign="top" width="33%">
      <strong>Web & Data</strong><br />
      • Next.js 14 / React / Vite<br />
      • Node.js / Express<br />
      • PostgreSQL (+ pgvector) / MySQL / Prisma<br />
      • Spark / Hadoop / Hive<br />
      • Tailwind CSS
    </td>
    <td valign="top" width="34%">
      <strong>Infrastructure & Security</strong><br />
      • Docker / Docker Compose<br />
      • AWS (EMR / S3)<br />
      • Linux VPS admin (Caddy, Nginx, Fail2Ban)<br />
      • CI/CD — GitHub Actions<br />
      • Nmap / Wireshark
    </td>
  </tr>
</table>

---

## Corporate Experience

### IT Infrastructure Lead & Support — Rekom Biotech S.L.
*2024 – Present | Granada, Spain*
* **Business Continuity:** Administered Active Directory and secure backup protocols, reducing weekly backup validation and incident resolution times to an average of **<15 minutes** with a 100% data durability record.
* **Disaster Recovery:** Designed backup policies and failover recovery testing for highly sensitive scientific datasets and clinical assay records.
* **Access Management:** Governed organizational access and network permissions with a zero-breach security record.

---

## Academic Background & Languages

* **B.Sc. in Computer Engineering** — *Universidad de Granada (UGR)* | 2022 – 2027 (expected)
* **Erasmus Mobility** — *Università degli Studi Roma Tre (Italy)* | 2025 – 2026 — *Cybersecurity (26/30), Mobile Computing, Big Data*
* **Cyber Málaga Bootcamp** — *University of Málaga, funded by Google* | 2026
* **Languages:** Spanish (Native) · English (B2, C1 in progress)

---

## Connect with me

* **Portfolio:** [pol3105.github.io](https://pol3105.github.io/)
* **LinkedIn:** [in/pablo-rejon-camacho](https://www.linkedin.com/in/pablo-rejon-camacho)
* **Email:** [pablorejoncamacho@gmail.com](mailto:pablorejoncamacho@gmail.com)

---
*Secure by Design, Efficient by Default.*
