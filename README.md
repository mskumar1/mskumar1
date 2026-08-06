<div align="center">
  
  <!-- Sleek Header Title -->
  <h1>👋 Hi, I'm Mohan Sai Kumar!</h1>
  <h3>🚀 Backend Developer & Systems Engineer</h3>
  <br/>

  <!-- Typing SVGs -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=7952B3&background=1a1b26&center=true&vCenter=true&width=600&height=50&lines=Software+Developer+at+Tata+Nexarc;Java+%E2%80%A2+Spring+Boot+%E2%80%A2+Microservices;System+Design+%E2%80%A2+Scalable+Architectures" alt="Typing SVG 1" />
  <br/>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=2500&pause=800&color=39FF14&background=1a1b26&center=true&vCenter=true&width=600&height=40&lines=Founder+of+MatchSolver.com;Building+clean+%26+scalable+APIs;Always+learning%2C+always+shipping!" alt="Typing SVG 2" />

  <br/><br/>

  <!-- Social Icons / Badges -->
  <p align="center">
    <a href="https://github.com/mskumar1" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://www.linkedin.com/in/mohana-sai-kumar-rongala/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:mohansaikumar.rongala@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://matchsolver.com" target="_blank">
      <img src="https://img.shields.io/badge/Website-MatchSolver-7952B3?style=for-the-badge&logo=google-chrome&logoColor=white" alt="MatchSolver Website" />
    </a>
    <a href="https://buymeacoffee.com/mskumar" target="_blank">
      <img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee" />
    </a>
  </p>
</div>

---

<table width="100%">
  <tr>
    <td>
      <h3>💫 About Me</h3>
      <p>🚀 <b>Backend Developer</b> passionate about building clean, high-performance, and scalable systems.</p>
      <ul>
        <li>💼 Currently engineering solutions at <b>Tata Nexarc</b>.</li>
        <li>🚀 Founder of <a href="https://matchsolver.com"><b>MatchSolver.com</b></a>, an AI-powered career growth platform.</li>
        <li>🛠️ Specializing in <b>Java, Spring Boot, Microservices, and System Design</b>.</li>
        <li>💳 Experienced in <b>Payment Gateways, Transactions, and OCR Invoice Systems</b>.</li>
        <li>🎮 Casual gamer & massive fan of the <b>GTA</b> franchise.</li>
        <li>🇮🇳 Based in <b>Andhra Pradesh, India</b>.</li>
      </ul>
    </td>
  </tr>
</table>

---

<table width="100%">
  <tr>
    <td>
      <h3>🚀 Featured Project: <a href="https://matchsolver.com">MatchSolver.com</a></h3>
      <p><b>AI-Powered Career Optimization & Document Management Platform</b></p>
      
      <ul>
        <li>🤖 <b>AI Career Intelligence</b>: Integrates resume building, cover letter optimization, ATS screening, and mock interview preparation.</li>
        <li>⚙️ <b>50+ Automated Utilities</b>: Instant online processing suite for PDF, image, and text document formatting.</li>
        <li>⚡ <b>Production-Grade Architecture</b>: Engineered for high concurrency, low latency file parsing, and secure payment processing.</li>
      </ul>

      <div align="center">
        <br/>
        <img src="assets/matchsolver_preview.png" alt="MatchSolver Feature Mockup" width="90%" style="border-radius: 8px; border: 1px solid #333;" />
        <br/><br/>
      </div>

      <h4>MatchSolver Key Architecture & Features:</h4>
      <ul>
        <li><b>Resume Parsing Engine</b>: Utilizes custom optical character recognition (OCR) and text-processing pipelines to extract structured sections from uploaded PDFs and Word files.</li>
        <li><b>AI Match Optimizer</b>: Evaluates job descriptions alongside user resumes to calculate ATS match rates, highlighting keyword gaps, formatting issues, and offering action-oriented optimizations.</li>
        <li><b>Scale & Throughput</b>: Designed to process large file uploads asynchronously using thread pools, optimizing resource utilization and minimizing user response time.</li>
      </ul>
    </td>
  </tr>
</table>

---

<table width="100%">
  <tr>
    <td>
      <h3>💼 Professional Experience: Tata Nexarc</h3>
      <p>As a backend developer at <b>Tata Nexarc</b>, I focus on building reliable transactional features and processing document data:</p>
      <ol>
        <li><b>OCR Invoice Systems</b>:
          <ul>
            <li>Engineered pipelines to parse, extract, and structure invoice information using OCR utilities, reducing manual invoice indexing overhead.</li>
            <li>Built validation layers to ensure parsed transactional data maps cleanly to double-entry ledger structures.</li>
          </ul>
        </li>
        <li><b>Transaction & Payment Gateways</b>:
          <ul>
            <li>Integrated reliable checkout pipelines with major payment gateways, handling webhook processing, automatic transaction retries, and reconciliation routines.</li>
            <li>Implemented distributed locking (via Redis) to prevent double-spending and ensure transaction consistency under concurrent request spikes.</li>
          </ul>
        </li>
      </ol>
    </td>
  </tr>
</table>

---

### 🛠️ Architecture & Workflows (Typical Microservices System)
Here is a high-level representation of the backend workflows and API architectures I design and build:

```mermaid
graph TD
    %% Styling
    classDef default fill:#1a1b26,stroke:#7aa2f7,stroke-width:2px,color:#a9b1d6;
    classDef gateway fill:#ff9e64,stroke:#f7768e,stroke-width:2px,color:#1a1b26,font-weight:bold;
    classDef service fill:#2ac3de,stroke:#0db9d7,stroke-width:2px,color:#1a1b26,font-weight:bold;
    classDef db fill:#9ece6a,stroke:#73daca,stroke-width:2px,color:#1a1b26;

    %% Nodes
    Client["📱 Client Apps / Tata Nexarc / MatchSolver"]
    Gateway["🛡️ API Gateway (Spring Cloud / Security)"]:::gateway
    
    subgraph Microservices ["Core Backend Layer"]
        Auth["🔑 Auth Service (OAuth2 / JWT)"]:::service
        Invoice["📄 OCR Invoice Processing Service"]:::service
        Payment["💳 Payment Gateway & Transactions"]:::service
    end

    subgraph DataStore ["Data & Event Streaming"]
        DB[("🗄️ PostgreSQL / MySQL / Hibernate")]:::db
        Cache[("⚡ Redis Cache")]:::db
        Queue[("✉️ RabbitMQ Message Broker")]:::db
    end

    %% Flows
    Client -->|REST APIs / HTTPS| Gateway
    Gateway --> Auth
    Gateway --> Invoice
    Gateway --> Payment

    Invoice -->|Async Jobs| Queue
    Payment -->|Transaction Events| Queue
    Queue -->|Database Persistence| DB
    Auth -->|Session Cache| Cache
```

---

<table width="100%">
  <tr>
    <td>
      <h3>⚙️ Core Backend Engineering Principles</h3>
      <ul>
        <li><b>High Availability & Fault Tolerance</b>: Implementing Circuit Breakers (Resilience4j) and fallback mechanisms to keep downstream outages from propagating.</li>
        <li><b>Database Optimization</b>: Designing normalized schemas, writing indexed queries, optimizing JPA/Hibernate mapping relationships to avoid the $N+1$ query problem, and configuring connection pools (HikariCP).</li>
        <li><b>Caching & Session Routing</b>: Leveraging Redis for fast read-through and write-behind cache strategies, API rate-limiting, and managing shared user sessions across distributed instances.</li>
        <li><b>Messaging & Event-Driven Architecture</b>: Decoupling long-running operations (like AI-processing and OCR conversions) from direct HTTP request threads using RabbitMQ queues to guarantee reliable job execution.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 💻 Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Backend & Databases</b></td>
      <td align="center"><b>Frontend & UI</b></td>
      <td align="center"><b>DevOps & Tools</b></td>
    </tr>
    <tr>
      <td>
        <img src="https://skillicons.dev/icons?i=java,spring,hibernate,mysql,postgres,redis,rabbitmq" alt="Backend Stack" />
      </td>
      <td>
        <img src="https://skillicons.dev/icons?i=js,ts,react,vite,tailwind,html,css" alt="Frontend Stack" />
      </td>
      <td>
        <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,git,github,jenkins,postman" alt="DevOps Stack" />
      </td>
    </tr>
  </table>
</div>

---

<table width="100%">
  <tr>
    <td>
      <h3>📐 Coding Standards & Design Patterns</h3>
      <ul>
        <li><b>SOLID Design</b>: Strictly adhering to SOLID principles and Clean Code rules to keep codebases understandable and modular.</li>
        <li><b>API Standardization</b>: Structuring restful APIs with clean HTTP status mappings, custom exception handlers (<code>@ControllerAdvice</code>), and comprehensive Swagger/OpenAPI documentation.</li>
        <li><b>Testing Guidelines</b>: Writing comprehensive unit and integration tests using JUnit, Mockito, and Testcontainers to validate behavior across database layers.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 📊 GitHub Metrics & Insights

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-stats-extended.vercel.app/api?username=mskumar1&show_icons=true&theme=tokyonight&count_private=true&border_radius=10" width="100%" alt="GitHub Stats" />
      </td>
      <td align="center" width="50%">
        <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=mskumar1&layout=compact&theme=tokyonight&border_radius=10" width="100%" alt="Top Languages" />
      </td>
    </tr>
  </table>
  
  <br/>
  
  <img src="https://streak-stats.demolab.com/?user=mskumar1&theme=tokyonight&border_radius=10" alt="GitHub Streak Stats" width="100%" />
</div>

---

### 🐍 My GitHub Contribution Snake
<div align="center">
  <img src="https://raw.githubusercontent.com/mskumar1/mskumar1/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake" width="100%" />
</div>

---

<div align="center">
  <p>⭐ <b>If you like my work, consider giving a star to my repositories!</b></p>
</div>
