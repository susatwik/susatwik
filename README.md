# Susatwik Manuri

<div align="center">
  <img src="assets/hero/hero-banner.svg" alt="Hero banner for Susatwik Manuri" width="100%" />
</div>

<div align="center">
  <strong>From Algorithms to Autonomous Systems</strong>
</div>

<div align="center">
  CS undergraduate building source-backed AI products, backend systems, and live demos.
</div>

<div align="center">
  <a href="https://github.com/susatwik"><img src="https://img.shields.io/badge/GitHub-susatwik-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://susatwik-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Live-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/susatwik/"><img src="https://img.shields.io/badge/LinkedIn-susatwik-0F172A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.codechef.com/users/susatwik"><img src="https://img.shields.io/badge/CodeChef-Profile-0F172A?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef profile" /></a>
  <a href="https://leetcode.com/u/susatwik/"><img src="https://img.shields.io/badge/LeetCode-Profile-0F172A?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode profile" /></a>
  <a href="mailto:susatwik.manuri@sasi.ac.in"><img src="https://img.shields.io/badge/Email-Contact-0F172A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

## At a glance

- Focus: AI systems, backend architecture, product engineering
- Proof: 4 case studies, 4 repos, 4 live demos
- Competitive programming: CodeChef 4★, 1800+ solved, LeetCode profile
- Brand: From Algorithms to Autonomous Systems

## Hero

<div align="center">
  <img src="assets/hero/profile-intro.svg" alt="Intro panel showing focus, proof, and positioning" width="100%" />
</div>

- Who I am: CS undergraduate building AI and backend products.
- What I build: resume analysis, recovery automation, restaurant ops, and pet-care workflows.
- Why it stands out: every project ships with a screenshot, architecture diagram, repo, and demo.

## Projects

<details id="career-compass" open>
<summary><strong>Career Compass</strong></summary>

<img src="assets/screenshots/hirescale-dashboard.png" alt="Career Compass dashboard showing resume analysis and interview prep" width="100%" />

- Context: Resume analysis and interview prep with Supabase auth, Edge Functions, and RLS-backed storage.
- Proof: [screenshot](assets/screenshots/hirescale-dashboard.png) · [diagram](diagrams/hirescale.mmd) · [repo](https://github.com/susatwik/stateful-interview-system) · [demo](https://stateful-interview-system.vercel.app)

</details>

<details id="recoverymate">
<summary><strong>RecoveryMate</strong></summary>

<img src="assets/screenshots/recovermate-dashboard.png" alt="RecoveryMate dashboard showing recovery planning workflows" width="100%" />

- Context: Recovery planning with a Vite client, Express server, and MongoDB persistence.
- Proof: [screenshot](assets/screenshots/recovermate-dashboard.png) · [diagram](diagrams/recovermate.mmd) · [repo](https://github.com/susatwik/RecoverMate) · [demo](https://recovermate-web.onrender.com)

</details>

<details id="restaurantflow">
<summary><strong>RestaurantFlow</strong></summary>

<img src="assets/screenshots/restaurantflow-dashboard.png" alt="RestaurantFlow dashboard showing order and kitchen coordination" width="100%" />

- Context: Orders, prep, and service coordination in one board.
- Proof: [screenshot](assets/screenshots/restaurantflow-dashboard.png) · [diagram](diagrams/restaurantflow.mmd) · [repo](https://github.com/susatwik/Restaurant-Ordering-Kitchen-Management-Platform) · [demo](https://restaurant-ordering-kitchen.vercel.app)

</details>

<details id="pawdentify">
<summary><strong>Pawdentify</strong></summary>

<img src="assets/screenshots/pawdentify-dashboard.png" alt="Pawdentify dashboard showing pet records and reminders" width="100%" />

- Context: Pet records, visits, and reminders in one place.
- Proof: [screenshot](assets/screenshots/pawdentify-dashboard.png) · [diagram](diagrams/pawdentify.mmd) · [repo](https://github.com/susatwik/pawdentify) · [demo](https://pawdentify-frontend.vercel.app)

</details>

## Brand

<div align="center">
  <img src="assets/branding/personal-brand.svg" alt="Brand ladder showing algorithms to autonomous systems" width="100%" />
</div>

<details>
<summary><strong>Brand narrative</strong></summary>

Algorithms → backend systems → AI products → operational software.

</details>

## Snapshot

<details>
<summary><strong>YAML profile</strong></summary>

```yaml
identity:
  name: Susatwik Manuri
  role: CS undergraduate
  location: India

focus:
  primary: AI systems and backend architecture
  secondary: RAG workflows and automation

proof:
  projects: 4
  demos: 4

competitive_programming:
  codechef: 4★
  solved: 1800+
```

</details>

## Architecture

<details>
<summary>Career Compass</summary>

```mermaid
flowchart LR
  UI[React 18 + Vite 5 UI] --> AUTH[Supabase Auth]
  UI --> DASH[Resume analysis + interview prep]
  DASH --> FUNC[Supabase Edge Functions]
  FUNC --> RULES[Deterministic ATS logic]
  FUNC --> GEMINI["Gemini fallback"]
  FUNC --> DB[(Postgres + RLS)]
```

</details>

<details>
<summary>RecoveryMate</summary>

```mermaid
flowchart LR
  UI[Vite React client] --> API[Express server]
  API --> UPLOAD[Multer uploads]
  API --> PARSE[pdf-parse]
  API --> GENAI["@google/genai"]
  API --> DB[(MongoDB + Mongoose)]
```

</details>

<details>
<summary>RestaurantFlow</summary>

```mermaid
flowchart LR
  UI[Dashboard UI] --> FLOW[Order flow]
  FLOW --> KITCHEN[Kitchen board]
  KITCHEN --> STATUS[Status updates]
  STATUS --> ALERTS[Alerts]
```

</details>

<details>
<summary>Pawdentify</summary>

```mermaid
flowchart LR
  UI[Pet records UI] --> VIS[Visit timeline]
  UI --> REM[Reminders]
  VIS --> NOTES[Notes]
  REM --> NOTIF[Notifications]
```

</details>

## Metrics dashboard

<table>
  <tr>
    <td><strong>Showcase projects</strong><br />4</td>
    <td><strong>Public source repos</strong><br />4</td>
    <td><strong>Live demos</strong><br />4</td>
  </tr>
  <tr>
    <td><strong>CodeChef</strong><br />4★</td>
    <td><strong>Problems solved</strong><br />1800+</td>
    <td><strong>Brand</strong><br />From Algorithms to Autonomous Systems</td>
  </tr>
</table>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=susatwik&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" alt="GitHub stats card" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=susatwik&theme=github-compact&hide_border=true" alt="GitHub contribution graph" width="100%" />
</div>

## Tech stack

<details>
<summary><strong>Stack details</strong></summary>

Languages: TypeScript, Python, JavaScript, SQL, Bash  
Frontend: React, Next.js, Tailwind CSS, shadcn/ui, Framer Motion  
Backend: Node.js, Express, REST, Webhooks  
Data: PostgreSQL, MongoDB, Redis  
AI: LLMs, RAG, embeddings, tool calling  
Cloud: Vercel, Docker, Kubernetes  
DevOps: GitHub Actions, CI/CD, observability  
Tools: Git, Linux, Postman, pnpm, Turbo, VS Code

</details>

## Competitive programming

<details>
<summary><strong>Problem solving</strong></summary>

- Profiles: [CodeChef](https://www.codechef.com/users/susatwik) · [LeetCode](https://leetcode.com/u/susatwik/)
- Strengths: arrays, strings, graphs, dynamic programming, greedy, trees

</details>

## Connect

<div align="center">
  <a href="https://susatwik-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/susatwik/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/susatwik"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:susatwikmanuri@sasi.ac.in"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

<div align="center">
  <img src="assets/footer/footer-glow.svg" alt="Footer glow" width="100%" />
</div>
