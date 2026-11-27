<img src="https://capsule-render.vercel.app/api?type=waving&color=1e2a44&height=190&section=header&text=Tejas%20H%20%20%C2%B7%20%20CSE%20'28%20%20%C2%B7%20%20IIIT%20Dharwad&fontColor=c5d3ee&fontSize=33&fontAlignY=42" width="100%" />

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1200&color=C9D1D9&center=true&vCenter=true&width=600&height=40&lines=Backend+%26+Distributed+Systems+Enthusiast;I+design+for+the+failure+mode+first;Open+Source+Contributor+at+Checkstyle;Competitive+Programmer" alt="Typing SVG" /></a>

</div>
   
## 👨‍💻 About Me

I build backend and distributed systems, and I design for the failure mode first so they stay consistent and reliable under load.<br>
I built a fault-tolerant reservation ledger on AWS with Saga orchestration and circuit breaking, load-tested at 229 RPS with p95 315 ms.<br>
I've also shipped Querion (AI SQL index optimizer), Beacon-AI (AI career coach) and Marginly (per-customer LLM cost analytics SaaS).<br>
I actively contribute to open source, and I'm looking for backend and SDE internships where I can work on distributed systems at scale.

## 🧠 Tech Stack

<img src="https://skillicons.dev/icons?i=java,py,react,nextjs,nodejs,fastapi,aws,gcp,mongodb,postgres&theme=dark&perline=10" />

## 🔥 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
  <h3>AWS Distributed Reservation Ledger</h3>
  <p>A fault-tolerant reservation backend that keeps bookings consistent under high concurrency and partial failures, built in two iterations.</p>
  <ul>
    <li><b>v1:</b> <b>Saga pattern</b> on <b>AWS Step Functions</b> with compensating transactions, <b>Redis</b> for fast hot-path holds and <b>DynamoDB</b> as the durable record, plus <b>token-bucket rate limiting</b> and a <b>circuit breaker</b>. Load-tested at <b>229 RPS, p95 315 ms</b></li>
    <li><b>Gap analysis:</b> audited my own design and documented four gaps: no expiry reconciliation between Redis and DynamoDB, non-idempotent compensating transactions, no RDS Proxy, and an unbounded Redis set</li>
    <li><b>v2:</b> rebuilt to close each documented gap, so every change traces back to a known flaw and not to guesswork</li>
  </ul>
  <sub>TypeScript · AWS Step Functions · DynamoDB · Redis</sub>
</td>
    <td width="50%" valign="top">
  <h3>Beacon-AI: AI Career Coach</h3>
  <p>A full-stack AI career coaching platform, built solo for HackHazards '26, that helps users prepare for their job search with mock interviews and resume scoring.</p>
  <ul>
    <li>LLM-driven <b>mock interviews</b> built with <b>LangChain</b> and <b>Gemini</b> for realistic interview practice</li>
    <li><b>ATS scoring</b> that shows how a resume is likely to perform in applicant tracking systems</li>
    <li>Background jobs and workflows handled with <b>Inngest</b>, keeping the UI responsive during AI processing</li>
    <li>Secure authentication with <b>Clerk</b> and data stored in <b>Neon serverless Postgres</b>, designed and built end to end by one developer</li>
  </ul>
  <sub>Next.js · LangChain · Gemini · Neon Postgres · Clerk · Inngest</sub>
</td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Marginly</h3>
      <p>A usage-based cost analytics SaaS that shows teams exactly what each customer costs them in LLM API spend.</p>
      <ul>
        <li>Ingests uploaded <b>LLM usage logs</b> and attributes token and API cost <b>per customer</b></li>
        <li>Interactive dashboard with <b>Recharts</b> visualizations to spot unprofitable accounts</li>
        <li>Typed data layer with <b>Prisma</b> and <b>PostgreSQL</b>, with <b>Clerk</b> for multi-user auth</li>
        <li>Built end to end in <b>TypeScript</b> (Node/Express API, React + Vite frontend)</li>
      </ul>
      <sub>TypeScript · Node/Express · Prisma · PostgreSQL · React · Tailwind</sub>
    </td>
    <td width="50%" valign="top">
      <h3>Querion</h3>
      <p>An AI-assisted SQL query optimizer that analyzes slow queries and validates index recommendations before they touch a real database.</p>
      <ul>
        <li>Parses queries into an <b>AST with sqlglot</b> to find optimization opportunities</li>
        <li>Tests candidate indexes with <b>HypoPG hypothetical indexing</b>, with no real index builds needed</li>
        <li><b>Gemini</b> explains bottlenecks and suggests rewrites, streamed over <b>Server-Sent Events</b></li>
        <li><b>Monaco diff viewer</b> for rewrites and <b>D3.js</b> visualizations of plan costs</li>
      </ul>
      <sub>Next.js · FastAPI · PostgreSQL · sqlglot · HypoPG · Gemini · D3.js</sub>
    </td>
  </tr>
</table>


## 🤝 Connect With Me

<p align="left">
<a href="https://linkedin.com/in/tejas-h-blitz"><img src="https://img.shields.io/badge/LinkedIn-1e2a44?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2YwZjZmYyIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8%2bPC9zdmc%2b" /></a>  <a href="mailto:tejashtejuhtj@gmail.com"><img src="https://img.shields.io/badge/Email-1e2a44?style=for-the-badge&logo=gmail&logoColor=f0f6fc" /></a>
  <a href="https://github.com/Tejas-h-blitz"><img src="https://img.shields.io/badge/GitHub-1e2a44?style=for-the-badge&logo=github&logoColor=f0f6fc" /></a>
</p>

📍 Shivamogga, Karnataka, India

<img src="https://capsule-render.vercel.app/api?type=waving&color=1e2a44&height=120&section=footer" width="100%" />

