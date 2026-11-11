<div align="center">

  <a href="mailto:keshm@uw.edu">
    <img src="https://img.shields.io/badge/Email-keshm%40uw.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/ukeshwaran">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/keshm2">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>

  <br />

  <img src="https://img.shields.io/badge/Open%20to-2026%2F2027%20Internships%20%26%202027%20New%20Grad-2f6fed?style=for-the-badge" alt="Open to 2026/2027 internships and 2027 new grad roles" />

</div>

---

## About me

Hi, I'm Ukeshwaran Muthukumaran Radha (Kesh Muthu). I'm a senior at UW studying Informatics, with a minor in Data Science, and I graduate in December 2027.

This year I'm interning at KredosAI, building the backend for a voice AI agent. It's FastAPI and vLLM services taking about 100 calls a day, and a lot of my time goes to keeping latency under 500ms. Before that I fine-tuned LLMs there and built vector search at Apexiel. I also got a CCNA along the way, so I still like networking and security more than I probably should.

Most of what's below exists because something annoyed me. I was pasting the same resume into every application, so I built Aplyx. My chapter's dues lived in a spreadsheet, so I built a member platform.

---

## Projects

### [Ripprz](https://ripprz.com)

A Pokemon card trading app. I led a team of five (standups three times a week, code review) and owned payments. Stripe payouts had three race conditions that were causing double refunds, and the fix was consistent lock ordering plus idempotency keys. Inventory allocation took 10 seconds until I switched it to prefix sums, which got it down to 13ms.

TypeScript, Next.js, PostgreSQL, Redis, Stripe

### Kappa Theta Pi member platform

The site and member portal for our chapter at UW, live at [ktpuw.org](https://ktpuw.org). Dues used to be tracked by hand. Now about 50 members pay through Stripe, event turnout went up 50%, and webhooks for four payment types cut reconciliation errors by 90%. I was most careful about the Postgres row-level security, so a member can't quietly promote themselves to an officer.

Next.js, TypeScript, Supabase, Stripe, Resend

### Aplyx

A job application agent that runs on top of a coding agent you already have (opencode or Claude Code). It searches Ashby, Lever, Greenhouse, and Workday, tailors a resume and cover letter for each posting, applies, and pings me on Discord. Python helpers own all the state and the LLM only orchestrates. If anything looks off at submit time it refuses to send. I later added a read-only MCP server so other agents can query job data, and Redis caching took searches from 7 seconds to under 500ms. [Repo](https://github.com/keshm2/aplyx)

Python, TypeScript, React, Rust, MCP, Redis, PostgreSQL

### Cisco school network deployment

I led a team of five putting Cisco routers and switches into 8 schools, with OSPF routing and DHCP. Each school got its own VLANs so devices stay isolated, and I diagnosed TCP/IP faults across three or more segments per school.

Cisco IOS, OSPF, VLANs, DHCP

### Smaller stuff

[kyper](https://github.com/keshm2/kyper) answers questions about my own PDFs, fully offline with Llama 3 and Ollama. [HusKey Manager](https://github.com/keshm2/passwordmanager) is a password vault for UW's INFO 310 with bugs planted on purpose for students to find. [bots](https://github.com/keshm2/bots) has a few Discord bots, including one that nags about 50 students about chores.

---

## Tech I use

- Languages: Python, TypeScript, JavaScript, Java, SQL, C++, Rust, PHP, R, and Go (learning)
- AI: vLLM, LoRA/QLoRA, RAG, embeddings, MCP, Qdrant, Ollama
- Backend: FastAPI, Node.js, Next.js, React, PostgreSQL, Redis, Supabase, Docker, AWS, Linux
- Security and networking: OWASP Top 10, Metasploit, Nmap, CCNA, TCP/IP, OSPF, VLANs
- Tools: Git, GitHub Actions, Playwright, Claude Code, Codex

---

## Right now

I'm looking for internships and 2027 new grad roles, mostly backend and AI infrastructure, though cloud, networking, and security work interests me too. If you're hiring or just want to talk shop, email me at [keshm@uw.edu](mailto:keshm@uw.edu) or find me on [LinkedIn](https://linkedin.com/in/ukeshwaran).
