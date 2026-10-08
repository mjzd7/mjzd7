<!-- REHeader banner: generate at https://github.com/khalby786/REHeader and replace this comment with <img> -->
<div align="center">

# Mohit Dagar

### **Software Development Engineer (SDE)**
**Systems Tooling (Rust) • Distributed Backend & APIs (Node.js, TypeScript) • Production Web (Next.js, React)**

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Software+Development+Engineer;Rust+%C2%B7+Node.js+%C2%B7+Next.js+%C2%B7+Systems+%26+Proxies;Building+production+web+at+Volume)

Delhi, India • [Portfolio](https://mohitworks-mjzd7s-projects.vercel.app) • [LinkedIn](https://linkedin.com/in/mohitdagar) • [work.mohitdagar@gmail.com](mailto:work.mohitdagar@gmail.com)

</div>

## 👨‍💻 About Me

Software engineer with a hybrid background spanning **low-level systems tooling**, **fault-tolerant backend APIs**, and **high-traffic production web platforms**:

- **Systems & DevTools:** Creator of **[DAGR](https://github.com/mjzd7/dagr)**, a native Rust hypervisor for AI coding agents featuring symbolic AST slicing, Copy-on-Write shadow sandboxes with zero dirty bytes on failure, and Blake3 cryptographic audit receipts (<1ms policy enforcement, MCP JSON-RPC 2.0).
- **Backend & Network Resilience:** Built **[FreeLLM-Api-with-Proxy](https://github.com/mjzd7/FreeLLM-Api-with-Proxy)**, an OpenAI-compatible reverse proxy on GCP aggregating 28 free upstream inference providers with dynamic failover, rate-limiting, and zero-token leak guarantees.
- **Production Web Operations Lead:** Led end-to-end web engineering and deployment operations at **[Volume](https://www.volume.in/)**, shipping and maintaining commercial web platforms, Next.js streaming applications, and high-converting e-commerce storefronts.
- **Algorithmic Fundamentals:** Active problem solver with 150+ LeetCode problems documented with strict Big-O time/space complexity analysis and automated test assertions.

---

## 🚀 Production & Commercial Systems

Commercial web applications, platforms, and e-commerce architectures engineered, deployed, and maintained for global consumer and enterprise brands:

| Platform / Client | Architecture & Stack | Role & Engineering Scope |
| :--- | :--- | :--- |
| **[Volume Flagship](https://www.volume.in/)** | Next.js, React, Vercel | **Lead Web Engineer:** Architected agency digital flagship; implemented React Server Components (RSC), optimized asset streaming, and achieved sub-second FCP. |
| **[Kanpeki Care](https://kanpekicare.com/)** | E-Commerce, Fastrr, Shiprocket | **Web Operations & Integration:** Engineered custom storefront architecture, integrated 1-click Fastrr checkout, and automated end-to-end 3rd-party logistics (Shiprocket) sync. |
| **[Hottest Ex](https://hottestex.com/)** | D2C Storefront, Cloudflare CDN | **Lead Developer:** Built high-impact mobile-first storefront, configured Cloudflare edge caching, and optimized Core Web Vitals for high-volume marketing drops. |
| **[Sipgel](https://sipgel.com/)** | Brand Web Platform, Cloudflare | **Deployment & Maintenance:** Engineered responsive digital platform with automated continuous delivery and asset optimization pipelines. |
| **[Project 5 Name](https://...)** | Next.js / Node.js / React | *Reserved Slot:* Custom full-stack web application, webhook event pipelines, and REST API integration. |
| **[Project 6 Name](https://...)** | Headless E-Commerce / Custom APIs | *Reserved Slot:* Automated inventory synchronization, payment gateway webhooks, and sub-second load times. |
| **[Project 7 Name](https://...)** | Full-Stack Web Portal | *Reserved Slot:* Multi-service brand platform, zero-downtime maintenance, and performance tuning. |

---

## 🛠 Core Technical Competencies

[![Skills](https://skillicons.dev/icons?i=rust,ts,js,nodejs,nextjs,react,postgres,docker,gcp,cloudflare,vercel&perline=11)](https://github.com/tandpfun/skill-icons)

- **Languages:** Rust, TypeScript, JavaScript (ES6+), SQL, Bash/Shell, HTML5/CSS3
- **Backend & Systems:** Node.js, Express, REST APIs, JSON-RPC (Model Context Protocol), Reverse Proxies (Caddy/Nginx), Redis, PostgreSQL
- **Frontend & Web Platforms:** React, Next.js, Tailwind CSS, Webpack/Vite, Liquid (Shopify Storefronts), Core Web Vitals Optimization
- **DevOps, Cloud & Infra:** Docker, Git/GitHub, GitHub Actions (CI/CD pipelines), Google Cloud Platform (GCP), Cloudflare DNS/CDN, Vercel, Linux
- **Architecture & Practices:** AST parsing/symbolic analysis, Copy-on-Write sandboxing, API rate limiting, webhook idempotency, test-driven development (TDD)

---

## 📌 Featured Engineering & Open Source Projects

### ⚡ [DAGR (`dagr`)](https://github.com/mjzd7/dagr)
*The DAG-Native Symbolic AST Slicing Hypervisor & Safety Sandbox for AI Coding Agents*
- **Stack:** Rust 2021, Tree-sitter, Blake3, MCP (Model Context Protocol) JSON-RPC 2.0
- **Key Engineering:**
  - Enforces architecture boundary policies (`.dagr/rules.yaml`) via AST parsing in <1ms.
  - Safe Copy-on-Write execution sandbox that rolls back atomically on agent failure.
  - Generates deterministic, Blake3-hashed audit receipts for every agent diff.

### 🌐 [FreeLLM-Api-with-Proxy](https://github.com/mjzd7/FreeLLM-Api-with-Proxy)
*Self-Hosted API Reverse Proxy & Aggregator with Dynamic Provider Failover*
- **Stack:** Node.js, Caddy, Google Cloud Platform (e2-micro Always Free), REST
- **Key Engineering:**
  - Reverse proxies 28 free inference providers behind a unified, OpenAI-compatible endpoint.
  - Built-in provider health checking, automated failover routing, and upstream quota handling.
  - In-depth architectural documentation, threat modeling, and terms-of-service compliance review.

### 🧩 [LeetCode Top Interview 150 (JavaScript)](https://github.com/mjzd7/leetcode-top-interview-150-javascript)
*Algorithmic Problem-Solving Manual & Test Suite*
- **Stack:** JavaScript, Node.js test runner, GitHub Pages portal
- **Key Engineering:**
  - 150 top interview questions solved with 3 progression tiers (Brute Force → Optimized → Idiomatic).
  - Explicit Big-O time and space complexity breakdown for every solution with executable test suites.

### 🤖 [Hermes Agent GCP](https://github.com/mjzd7/hermes-agent-gcp) & [Automate-Instagram-Posts](https://github.com/mjzd7/Automate-Instagram-Posts)
*Autonomous Agent Runtime & Headless Publishing Automation*
- **Stack:** Python/Node.js, GCP Compute Engine, Headless Automation
- **Key Engineering:**
  - Automated scheduling, task queues, idempotent webhook triggers, and error recovery pipelines.

---

## 📈 Activity & Engineering Standards

- **Commit Hygiene:** Atomic, descriptive conventional commits (`feat:`, `fix:`, `refactor:`, `perf:`).
- **Code Reliability:** Automated test suites, linting, and strict compiler checks in CI workflows.
- **Production Focus:** Every project includes clear architecture documentation, environment configuration, and quickstart commands (`docker compose up` or `cargo build --release`).

### 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mjzd7&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mjzd7&layout=compact&theme=tokyonight&hide_border=true)

</div>

![Profile Summary](https://github-readme-stats.vercel.app/api/pin/?username=mjzd7&repo=dagr&theme=tokyonight&hide_border=true)

### 🕒 Recent Activity

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
<!-- github-activity-readme (jamesgeorge007) Action will auto-fill this block -->

---

<div align="center">

*Open to Software Development Engineer (SDE-1 / SDE-2) roles across Backend, Systems, and Full-Stack teams.*  
**Connect:** [Portfolio](https://mohitworks-mjzd7s-projects.vercel.app) • [LinkedIn](https://linkedin.com/in/mohitdagar) • [work.mohitdagar@gmail.com](mailto:work.mohitdagar@gmail.com)

</div>
