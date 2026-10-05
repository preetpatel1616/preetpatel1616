<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/masthead-dark.svg">
  <img alt="Preet Patel — backend engineer building reliable AI systems" src="./assets/masthead-light.svg" width="100%">
</picture>

<p align="center">
I build the backend that makes AI features trustworthy: answers that cite their sources,<br>
test sets that catch regressions before they ship, and guardrails that keep cost and latency under control.<br>
<b>Open to full-time backend / AI engineering roles · Pune · Bangalore · Hyderabad · remote (India)</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/preetpatel1616/"><img src="./assets/badge-linkedin.svg" alt="LinkedIn: Preet Patel" height="28"></a>
</p>

### Building now

<table>
<tr>
<td width="50%" valign="top">

**Cited answers over SEBI and RBI circulars**<br>
Answers questions on Indian financial regulations with the exact circular and paragraph cited, tracks which rule is still in force, and refuses when it can't cite.<br>
<sub>Python · FastAPI · PostgreSQL/pgvector · hybrid search · evals in CI</sub><br>
<sub><i>In progress — goes public with measured results</i></sub>

</td>
<td width="50%" valign="top">

**A gateway for every AI-model call**<br>
API-key and OAuth auth, rate limits, prompt cache, provider failover, and per-customer spend caps enforced from a Kafka stream.<br>
<sub>Java 21 · Spring Boot · Redis · Kafka · PostgreSQL</sub><br>
<sub><i>In progress — goes public with measured results</i></sub>

</td>
</tr>
</table>

### Shipped

**[aws-vehicle-compliance-system](https://github.com/preetpatel1616/aws-vehicle-compliance-system)** — reads licence plates from vehicle photos with AWS Rekognition, checks insurance and registration in PostgreSQL, and emails the owner. Next.js, TypeScript, JWT auth, Docker, deploy pipeline to AWS.

### Stack

<p>
  <sub>Used in shipped work</sub><br>
  <img src="./assets/stack-shipped.svg" alt="TypeScript, Next.js, PostgreSQL, Prisma, AWS, Docker, GitHub Actions" height="48">
</p>
<p>
  <sub>Building with</sub><br>
  <img src="./assets/stack-building.svg" alt="Python, FastAPI, Java, Spring Boot, Redis, Kafka" height="48">
</p>

### Currently

Building the SEBI/RBI answer service first. The gateway comes next, and the answer service's model calls will run through it, so the two form one system.
