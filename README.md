# Hi there, I'm Tejas H 👋
   
<div align="center">

![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=1F6FEB&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;Competitive+Programmer;Distributed+Systems+Enthusiast;Open+Source+Contributor)

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
      <sub>TypeScript · AWS Step Functions · DynamoDB · Redis</sub><br><br>
      <a href="https://github.com/Tejas-h-blitz/Aws-Distributed-Reservation-Ledger"><img src="https://img.shields.io/badge/View_Project-1a1a1a?style=flat-square&logo=github&logoColor=white" /></a>
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
      <sub>Next.js · LangChain · Gemini · Neon Postgres · Clerk · Inngest</sub><br><br>
      <a href="https://github.com/Tejas-h-blitz/REPO-NAME"><img src="https://img.shields.io/badge/View_Project-1a1a1a?style=flat-square&logo=github&logoColor=white" /></a>
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
      <sub>TypeScript · Node/Express · Prisma · PostgreSQL · React · Tailwind</sub><br><br>
      <a href="https://github.com/Tejas-h-blitz/REPO-NAME"><img src="https://img.shields.io/badge/View_Project-1a1a1a?style=flat-square&logo=github&logoColor=white" /></a>
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
      <sub>Next.js · FastAPI · PostgreSQL · sqlglot · HypoPG · Gemini · D3.js</sub><br><br>
      <a href="https://github.com/Tejas-h-blitz/REPO-NAME"><img src="https://img.shields.io/badge/View_Project-1a1a1a?style=flat-square&logo=github&logoColor=white" /></a>
    </td>
  </tr>
</table>

## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tejas-h-blitz)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/tejas_h_06)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tejashtejuhtj@gmail.com)

📍 Shivamogga, Karnataka, India
