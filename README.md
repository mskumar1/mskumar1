<div align="center">
  
  <!-- Dynamic Capsule Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:7952b3,100:39ff14&height=200&section=header&text=Mohana%20Sai%20Kumar%20Rongala&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Backend%20Engineer%20%7C%20Founder%20of%20MatchSolver%20%7C%20Tata%20Nexarc&descAlignY=56&descSize=16&descColor=a9b1d6" alt="Header Banner" width="100%" />
  <br/>

  <!-- Typing SVGs -->
  <!-- Clean Typing SVG Banner -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Software+Developer+at+Tata+Nexarc;Founder+of+MatchSolver.com;Java+%7C+Spring+Boot+%7C+Microservices;Andhra+Pradesh%2C+India+%F0%9F%87%AE%F0%9F%87%B3" alt="Typing SVG" />

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

### 💫 About Me
🚀 **Backend Developer** passionate about building clean, high-performance, and scalable systems.

- 💼 Currently engineering solutions at **Tata Nexarc**.
- 🚀 Founder of **[MatchSolver.com](https://matchsolver.com)**, an AI-powered career growth platform.
- 🛠️ Specializing in **Java, Spring Boot, Microservices, and System Design**.
- 💳 Experienced in **Payment Gateways, Transactions, and OCR Invoice Systems**.
- 🎮 Casual gamer & massive fan of the **GTA** franchise.
- 🇮🇳 Based in **Andhra Pradesh, India**.

---

## 🚀 Technical Contributions & Impact

<div align="center">

![Systems Integrated](https://img.shields.io/badge/Systems%20Integrated-5%2B-2ea44f?style=for-the-badge&logo=spring&logoColor=white)
![APIs Designed](https://img.shields.io/badge/APIs%20Designed-30%2B-388bfd?style=for-the-badge&logo=postman&logoColor=white)
![OCR Systems Built](https://img.shields.io/badge/OCR%20Systems%20Built-2-f78166?style=for-the-badge&logo=image&logoColor=white)
![Database Engines Managed](https://img.shields.io/badge/Databases-MySQL%20%7C%20Postgres%20%7C%20Redis-a371f7?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

### Key Contributions & Features

| Platform / Project | Area of Contribution | Key Impact & Details |
|---|---|---|
| **Tata Nexarc** | **OCR Invoice Parsing Engine** | Built robust pipelines using OCR libraries to extract metadata from invoices, minimizing manual inputs. |
| **Tata Nexarc** | **Transaction & Payment Gateway** | Engineered reliable, high-availability checkout flows, handling webhook notifications and transaction reconciliation. |
| **Tata Nexarc** | **Concurrency & Thread Safety** | Implemented Redis-based distributed locking to guarantee double-spend protection during payment processing surges. |
| **MatchSolver.com** | **ATS Match Optimizer** | Architected the resume parser and analyzer evaluating ATS scores and calculating semantic gaps in resumes. |
| **MatchSolver.com** | **Asynchronous File Pipelines** | Designed asynchronous processing queues utilizing RabbitMQ to handle multi-format file conversions (PDF, Image, Docs). |

---

### 🚀 Featured Project: [MatchSolver.com](https://matchsolver.com)
**AI-Powered Career Optimization & Document Management Platform**

* 🤖 **AI Career Intelligence**: Integrates resume building, cover letter optimization, ATS screening, and mock interview preparation.
* ⚙️ **50+ Automated Utilities**: Instant online processing suite for PDF, image, and text document formatting.
* ⚡ **Production-Grade Architecture**: Engineered for high concurrency, low latency file parsing, and secure payment processing.

<div align="center">
  <br/>
  <img src="assets/matchsolver_preview.png" alt="MatchSolver Feature Mockup" width="90%" style="border-radius: 8px; border: 1px solid #333;" />
  <br/><br/>
</div>

#### MatchSolver Key Architecture & Features:
* **Resume Parsing Engine**: Utilizes custom optical character recognition (OCR) and text-processing pipelines to extract structured sections from uploaded PDFs and Word files.
* **AI Match Optimizer**: Evaluates job descriptions alongside user resumes to calculate ATS match rates, highlighting keyword gaps, formatting issues, and offering action-oriented optimizations.
* **Scale & Throughput**: Designed to process large file uploads asynchronously using thread pools, optimizing resource utilization and minimizing user response time.

---

### 💼 Professional Experience: Tata Nexarc
As a backend developer at **Tata Nexarc**, I focus on building reliable transactional features and processing document data:

1. **OCR Invoice Systems**:
   - Engineered pipelines to parse, extract, and structure invoice information using OCR utilities, reducing manual invoice indexing overhead.
   - Built validation layers to ensure parsed transactional data maps cleanly to double-entry ledger structures.
2. **Transaction & Payment Gateways**:
   - Integrated reliable checkout pipelines with major payment gateways, handling webhook processing, automatic transaction retries, and reconciliation routines.
   - Implemented distributed locking (via Redis) to prevent double-spending and ensure transaction consistency under concurrent request spikes.

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

### ⚙️ Core Backend Engineering Principles
* **High Availability & Fault Tolerance**: Implementing Circuit Breakers (Resilience4j) and fallback mechanisms to keep downstream outages from propagating.
* **Database Optimization**: Designing normalized schemas, writing indexed queries, optimizing JPA/Hibernate mapping relationships to avoid the $N+1$ query problem, and configuring connection pools (HikariCP).
* **Caching & Session Routing**: Leveraging Redis for fast read-through and write-behind cache strategies, API rate-limiting, and managing shared user sessions across distributed instances.
* **Messaging & Event-Driven Architecture**: Decoupling long-running operations (like AI-processing and OCR conversions) from direct HTTP request threads using RabbitMQ queues to guarantee reliable job execution.

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

### 📐 Coding Standards & Design Patterns
* **SOLID Design**: Strictly adhering to SOLID principles and Clean Code rules to keep codebases understandable and modular.
* **API Standardization**: Structuring restful APIs with clean HTTP status mappings, custom exception handlers (`@ControllerAdvice`), and comprehensive Swagger/OpenAPI documentation.
* **Testing Guidelines**: Writing comprehensive unit and integration tests using JUnit, Mockito, and Testcontainers to validate behavior across database layers.

---

### 🛠️ Specialized Architectures & Design Patterns
Below are the core architectural patterns I implement to maintain system decoupling and performance:
* **CQRS (Command Query Responsibility Segregation)**: Segregating read and write operations using separate database models (like PostgreSQL for transactional writes and Redis/ElasticSearch for optimized reads).
* **Transactional Outbox Pattern**: Assuring reliable message publishing to RabbitMQ or Kafka in distributed microservices transactions by using an outbox table within the same relational database boundary.
* **Distributed Locking (Redis/Redlock)**: Implementing distributed lock mechanisms to manage concurrency and prevent race conditions on payment captures and inventory deductions.

---

### 📈 DevOps, Monitoring & Reliability
I believe that a backend system is only as good as its observability:
* **Observability**: Setting up distributed tracing with Spring Cloud Sleuth (Micrometer) and Zipkin/Jaeger to track user requests across microservice boundaries.
* **Log Aggregation & Monitoring**: Working with Prometheus and Grafana dashboards to monitor JVM health metrics, thread pools, and active DB connection parameters.
* **CI/CD Pipelines**: Constructing automated Jenkins/GitHub Actions pipelines to build Docker images, execute unit/integration test suites, and deploy to AWS Elastic Container Service (ECS).

---

### 🌱 Current Focus & Learning Journey
* 🧠 Delving deeper into **System Architecture Patterns** and high-throughput low-latency network protocols (gRPC, WebSockets).
* 🔧 Researching distributed consensus algorithms (Raft, Paxos) and cloud-native container orchestration using Kubernetes.
* 🤖 Experimenting with the integration of AI models and OCR libraries to automate complex business workflows.

---

### 📊 GitHub Metrics & Insights

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-readme-stats-nu-ten-46.vercel.app/api?username=mskumar1&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true&border_radius=10" width="100%" alt="GitHub Stats" />
      </td>
      <td align="center" width="50%">
        <img src="https://github-readme-stats-nu-ten-46.vercel.app/api/top-langs/?username=mskumar1&layout=compact&theme=tokyonight&border_radius=10" width="100%" alt="Top Languages" />
      </td>
    </tr>
  </table>
  
  <br/>
  
  <img src="https://streak-stats.demolab.com/?user=mskumar1&theme=tokyonight&border_radius=10&cache_seconds=1800" alt="GitHub Streak Stats" width="100%" />
</div>

---

### 🐍 My GitHub Activity Snake
<div align="center">
  <img src="https://raw.githubusercontent.com/mskumar1/mskumar1/output/github-contribution-grid-snake.svg" alt="GitHub Activity Snake" width="100%" />
</div>

---

<div align="center">
  <p>⭐ <b>If you like my work, consider giving a star to my repositories!</b></p>
</div>
