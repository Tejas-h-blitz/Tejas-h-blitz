<img src="https://capsule-render.vercel.app/api?type=waving&color=1e2a44&height=190&section=header&text=Tejas%20H%20%20%C2%B7%20%20CSE%20'28%20%20%C2%B7%20%20IIIT%20Dharwad&fontColor=c5d3ee&fontSize=33&fontAlignY=42" width="100%" />

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1200&color=C9D1D9&center=true&vCenter=true&width=600&height=40&lines=Backend+%26+Distributed+Systems+Enthusiast;I+design+for+the+failure+mode+first;Open+Source+Contributor+at+Checkstyle;Competitive+Programmer" alt="Typing SVG" /></a>

</div>
   
## 🚀 About Me
 
CSE '28 @ IIIT Dharwad. I build backend systems that hold up under load.

 
- ⚡ Built a distributed reservation ledger — Saga pattern, Redis→DynamoDB fallback, 229 RPS @ p95 315ms
- 🧠 Shipped an AI SQL optimizer that rewrites queries using hypothetical index simulation (Querion)
- 🤖 Built an AI career coach with LLM-driven mock interviews and ATS scoring (Beacon-AI)
- 🌐 Comfortable across the stack: from AWS infra to React UIs
- 📖 I read production postmortems for fun
- 💼 Full-Stack Development intern @ CodeAlpha
- 📫 Always open to connecting — reach me on [LinkedIn](https://www.linkedin.com/in/tejas-h-blitz)
 
> **How I approach a new system:**
> Read the spec for what breaks it, not what it promises.
> Design for the failure mode first.
<br> Ship it, then measure — never trust an unmeasured number.

## 🧠 Tech Stack

<img src="https://skillicons.dev/icons?i=java,py,react,nextjs,nodejs,fastapi,aws,gcp,mongodb,postgres&theme=dark&perline=10" />

## 🔥 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>AWS Distributed Reservation Ledger</h3>
      <p>A fault-tolerant reservation backend that keeps bookings consistent under high concurrency and partial failures.</p>
      <ul>
        <li>Multi-step booking workflows using the <b>Saga pattern</b> on <b>AWS Step Functions</b>, with compensating transactions for clean rollback</li>
        <li><b>Tiered persistence</b>: Redis for fast hot-path holds, DynamoDB as the durable system of record</li>
        <li><b>Token-bucket rate limiting</b> and a <b>circuit breaker</b> to contain cascading failures</li>
        <li>Load-tested at <b>229 RPS, p95 315 ms</b></li>
      </ul>
      <sub>TypeScript · AWS Step Functions · DynamoDB · Redis</sub>
    </td>
    <td width="50%" valign="top">
      <h3>Beacon-AI: AI Career Coach</h3>
      <p>A full-stack AI career coaching platform, built solo for HackHazards '26, that gives users personalized guidance.</p>
      <ul>
        <li><b>LangChain</b> with <b>Gemini</b> for context-aware guidance based on the user's profile and goals</li>
        <li>Long-running AI workflows handled as background jobs with <b>Inngest</b>, keeping the UI responsive</li>
        <li>Secure authentication with <b>Clerk</b> and data stored in <b>Neon serverless Postgres</b></li>
        <li>Designed and built end to end by one developer</li>
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
  <a href="https://linkedin.com/in/tejas-h-blitz"><img src="https://img.shields.io/badge/LinkedIn-1e2a44?style=for-the-badge&logo=linkedin&logoColor=f0f6fc" /></a>
  <a href="mailto:tejashtejuhtj@gmail.com"><img src="https://img.shields.io/badge/Email-1e2a44?style=for-the-badge&logo=gmail&logoColor=f0f6fc" /></a>
  <a href="https://github.com/Tejas-h-blitz"><img src="https://img.shields.io/badge/GitHub-1e2a44?style=for-the-badge&logo=github&logoColor=f0f6fc" /></a>
</p>

📍 Shivamogga, Karnataka, India

<img src="https://capsule-render.vercel.app/api?type=waving&color=1e2a44&height=120&section=footer" width="100%" />

