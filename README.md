<div align="center">
  
  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/type=waving&color=auto&height=220&section=header&text=Mohan%20Sai%20Kumar&fontSize=50&animation=fadeIn&theme=tokyonight" width="100%" alt="Header Banner" />

  <!-- Typing SVG -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=7952B3&center=true&vCenter=true&width=600&lines=Software+Developer+at+Tata+Nexarc;Java+%E2%80%A2+Spring+Boot+%E2%80%A2+Microservices;System+Design+%E2%80%A2+Scalable+Architectures" alt="Typing SVG" />

  <!-- Social Icons / Badges -->
  <p align="center">
    <a href="https://www.linkedin.com/in/mohana-sai-kumar-rongala/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:mohansaikumar.rongala@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
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
- 🛠️ Specializing in **Java, Spring Boot, Microservices, and System Design**.
- 💳 Experienced in **Payment Gateways, Transactions, and OCR Invoice Systems**.
- 🎮 Casual gamer & massive fan of the **GTA** franchise.
- 🇮🇳 Based in **Andhra Pradesh, India**.

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
    Client["📱 Client Apps / Tata Nexarc Platform"]
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

### 📊 GitHub Metrics & Insights

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-readme-stats.vercel.app/api?username=mskumar1&show_icons=true&theme=tokyonight&count_private=true&border_radius=10" width="100%" />
      </td>
      <td align="center" width="50%">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mskumar1&layout=compact&theme=tokyonight&border_radius=10" width="100%" />
      </td>
    </tr>
  </table>
  
  <br/>
  
  <img src="https://github-profile-trophy.vercel.app/?username=mskumar1&theme=tokyonight&row=1&column=7&margin-w=15" alt="GitHub Trophies" />
</div>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/mskumar1/mskumar1/github-contribution-grid-snake/ocean.svg" alt="Snake animation" width="100%" />
</div>

---

<div align="center">
  <p>⭐ <b>If you like my work, consider giving a star to my repositories!</b></p>
</div>
