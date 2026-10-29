<h1 align="center">Hi 👋, I'm MOHAMMAD SIDDIQ SHAIK</h1>

<h3 align="center">B.Tech CSE '27 | Aspiring Cloud Data Engineer | Software Engineering & Applied AI</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=msiddiq786&label=Profile%20Views&color=0e75b6&style=flat" alt="GitHub profile views counter for msiddiq786" />
</p>

### 👨‍💻 About Me

I'm a B.Tech Computer Science Engineering student at **JAIN (Deemed-to-be University), Bengaluru**, graduating in 2027 with a **CGPA of 9.10**. My interests are in **cloud data engineering**, software engineering, full-stack development, and applied AI, and I focus on building practical, well-structured software.

I have built REST APIs, database-driven applications, and AI-powered systems. On the cloud side, I'm developing hands-on skills with **AWS**, including serverless workflows, data processing, and ETL concepts. I back this with a strong foundation in **Data Structures and Algorithms in C++** (100+ problems solved) and experience collaborating on team-based software projects.

I'm seeking opportunities in **Cloud Data Engineering and Software Engineering** where I can keep learning while contributing to real-world solutions.

📫 **Contact:** [skmsiddiqsiddiq@gmail.com](mailto:skmsiddiqsiddiq@gmail.com)

### 🧰 Technical Skills

> **Legend:** ✅ Hands-on in projects &nbsp;·&nbsp; 📘 Learning & practice &nbsp;·&nbsp; 🔭 Exploring

| Area | Technologies |
|:--|:--|
| **Programming** | ✅ C++ · Python · JavaScript · SQL |
| **Full-Stack** | ✅ React.js · Node.js · Express.js · Flask · HTML5 · CSS3 · Tailwind CSS · REST APIs · JWT |
| **Databases** | ✅ MySQL · MongoDB · SQLite · PostgreSQL · Amazon RDS (MySQL) <br> 📘 Redis · Aurora PostgreSQL fundamentals |
| **AWS Infrastructure** | ✅ EC2 · S3 · IAM · VPC · Security Groups · SSH & Linux · Nginx |
| **AWS Serverless** | ✅ Lambda · API Gateway · Step Functions · EventBridge · SNS · CloudWatch · Secrets Manager |
| **Data Engineering** | ✅ SQL processing · ETL concepts · data validation · AWS Glue <br> 📘 Redshift (COPY from S3) · PySpark / Spark fundamentals · data warehousing · OLTP vs OLAP <br> 🔭 Pipeline monitoring & troubleshooting at scale |
| **AI & Computer Vision** | ✅ Google Gemini API · LLM-based apps · YOLOv8 · OpenCV · NLP <br> 🔭 RAG · AI agents |
| **DevOps & Tools** | ✅ Git · GitHub · Docker · Postman (API testing) <br> 📘 CI/CD · GitHub Actions |

<details>
<summary><b>☁️ Microsoft Azure — learning and service comparison (concept-level; no Azure deployments claimed)</b></summary>
<br>

| Purpose | Azure service | AWS equivalent I compare it with |
|:--|:--|:--|
| Compute | Virtual Machines · Functions | EC2 · Lambda |
| Storage | Blob Storage | S3 |
| Identity & security | Microsoft Entra ID · Azure RBAC · Key Vault | IAM · Secrets Manager |
| Networking | Virtual Network | VPC |
| Data & analytics | Data Factory · Databricks · Synapse Analytics · Azure SQL Database | Glue · EMR / Spark · Redshift · RDS |
| Events & automation | Event Grid · Logic Apps | EventBridge · Step Functions |
| Monitoring | Azure Monitor | CloudWatch |

</details>

---

### 🚀 Featured Projects

#### 🔨 Currently Building — New AI-Based Project
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)
<!-- TODO: replace this block with your project's real title, problem statement, AI component, stack, features built so far, and repo link. -->
An AI-based project in active development. Details will be added here as the implementation takes shape.

---

#### ☁️ AWS College Admission Processing & Verification System
![Cloud](https://img.shields.io/badge/Cloud%20%26%20Data%20Engineering-FF9900?style=flat-square) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
<!-- TODO: link repo: [AWS College Admission Processing & Verification System](YOUR_REPO_URL). Confirm each status below against your repo. -->
Serverless workflow that ingests college applications, validates them, orchestrates processing, stores records, sends notifications, and prepares data for analytics.

```text
Application submission → API Gateway → Lambda validation → S3 (documents / JSON)
        → Step Functions orchestration → RDS (MySQL) storage + SNS notifications
        → AWS Glue processing → Amazon Redshift analytics (in progress)
```

| Component | Role | Status |
|:--|:--|:--|
| API Gateway · Lambda | Application submission and validation | ✅ Implemented |
| S3 | Application documents and JSON data | ✅ Implemented |
| Step Functions · EventBridge | Workflow orchestration and event-driven automation | ✅ Implemented |
| SNS | Notifications | ✅ Implemented |
| Secrets Manager · RDS (MySQL) | Credentials and application records | ✅ Implemented |
| CloudWatch | Logging and debugging | ✅ Implemented |
| AWS Glue | ETL and data processing | ✅ Implemented |
| Redshift · PySpark | Analytical loading and processing | 📘 Learning / in progress |

**Stack:** `AWS Lambda` `API Gateway` `Step Functions` `S3` `SNS` `EventBridge` `CloudWatch` `Secrets Manager` `RDS MySQL` `AWS Glue`

---

#### 🛡️ AI Security & Attendance Management System
<!-- TODO: link repo: [AI Security & Attendance Management System](YOUR_REPO_URL) -->
Real-time face detection and recognition that automates student attendance.
* Camera-based detection with **YOLOv8** and **OpenCV**; attendance records in **SQLite**
* **Flask REST APIs** for authentication, student management, attendance tracking, dashboard statistics, and reports
* **React.js** frontend

**Stack:** `Python` `Flask` `React.js` `YOLOv8` `OpenCV` `SQLite` `REST APIs`

---

#### 🎯 SkillBridge — AI-Powered Interview & Career Platform
<!-- TODO: add Live Demo URL and repo link: [Live Demo](YOUR_DEMO_URL). Check whether "CareerX AI" is the same project; if so keep only this name. -->
Full-stack career platform with resume analysis, ATS scoring, interview preparation, skill-gap analysis, and career guidance.
* **Google Gemini API** and LLM workflows generate interview questions, analyze skills, and suggest career paths
* RESTful APIs with **JWT authentication** and **MongoDB** data management; responsive **React.js** interface

**Stack:** `React.js` `Node.js` `Express.js` `MongoDB` `Mongoose` `Google Gemini API` `JWT`

---

#### 🌐 Deep Packet Inspection Engine
<!-- TODO: link repo: [Deep Packet Inspection Engine](YOUR_REPO_URL) -->
Network traffic analysis project that captures and inspects packets in real time using **socket programming** and **TCP/IP** concepts.

---

#### 🖥️ AWS Static Hosting — EC2 + Nginx and S3
![Status](https://img.shields.io/badge/Docs-In%20Progress-yellow?style=flat-square)
<!-- TODO: link repo once published: [AWS S3 Static Hosting](YOUR_REPO_URL) -->
Portfolio website hosted on an **EC2 Linux server with Nginx**, documented alongside **S3 static hosting**, VPC networking, security groups, and an S3 vs EC2 + Nginx comparison, with screenshots.

---

### 🛠️ Languages and Tools

| | |
|:--|:--|
| **Programming** | <img src="https://skillicons.dev/icons?i=cpp,py,js,mysql" height="30" alt="C++, Python, JavaScript, SQL icons" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=html,css,react,tailwind" height="30" alt="HTML5, CSS3, React, Tailwind CSS icons" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,flask" height="30" alt="Node.js, Express.js, Flask icons" /> |
| **Databases** | <img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,sqlite,redis" height="30" alt="MongoDB, MySQL, PostgreSQL, SQLite, Redis icons" /> |
| **Cloud** | <img src="https://skillicons.dev/icons?i=aws,azure,linux,docker,nginx" height="30" alt="AWS, Microsoft Azure, Linux, Docker, Nginx icons" /> <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white" height="22" alt="Amazon Web Services badge" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" height="22" alt="Microsoft Azure badge" /> |
| **Data Engineering** | <img src="https://img.shields.io/badge/S3-569A31?style=flat-square" height="22" alt="Amazon S3" /> <img src="https://img.shields.io/badge/Lambda-FF9900?style=flat-square" height="22" alt="AWS Lambda" /> <img src="https://img.shields.io/badge/Glue-8C4FFF?style=flat-square" height="22" alt="AWS Glue" /> <img src="https://img.shields.io/badge/Redshift-8C4FFF?style=flat-square" height="22" alt="Amazon Redshift" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" height="22" alt="PySpark" /> |
| **AI & Vision** | <img src="https://skillicons.dev/icons?i=opencv" height="30" alt="OpenCV icon" /> <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logoColor=black" height="22" alt="YOLOv8" /> <img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" height="22" alt="Google Gemini API" /> |
| **Tools** | <img src="https://skillicons.dev/icons?i=git,github,postman,vscode" height="30" alt="Git, GitHub, Postman, VS Code icons" /> |

---

### 🧠 Core Computer Science

* **Data Structures & Algorithms:** arrays, hashing, linked lists, stacks, queues, trees, graphs, binary search, sliding window, two pointers, dynamic programming
* **Object-Oriented Programming**
* **DBMS & SQL:** relational design and querying
* **Operating Systems**
* **Computer Networks:** TCP/IP and HTTP/HTTPS
* **REST API fundamentals**
* **Problem solving and algorithmic thinking**

---

### 🎓 Education

| Institution | Qualification | Year | Score |
|:--|:--|:--:|:--:|
| **JAIN (Deemed-to-be University)**, Bengaluru | B.Tech, Computer Science Engineering | 2023 – 2027 | **CGPA 9.10** |
| Narayana College – BIEAP | Class XII | 2023 | **97.9%** |
| Narayana School – CBSE | Class X | 2021 | **93%** |

---

### 💼 Professional Experience

**Web Development Intern — Infotact Solutions** · *Apr 2026 – Jun 2026*
* Developed three MERN-stack applications using React.js, Node.js, Express.js, MongoDB, and REST APIs
* Built responsive interfaces; worked on debugging, testing, and version control

**Python Programming Intern — EISystems Technologies** · *Jan 2026 – Mar 2026*
* Developed and tested Python applications using OOP, data structures, algorithms, and modular programming
* Worked on debugging, reliability, maintainability, and code quality

---

### 🏆 Certifications and Achievements

| 📜 Certifications | Issuer | Year |
|:--|:--|:--:|
| Introduction to Web Applications | Akamai Technologies | 2025 |
| Development Python Program | E & ICT Academy, IIT Kanpur | 2024 |
| Introduction to Operating Systems Specialization | Codio | 2024 |
| Introduction to Graph Theory *(with Honors)* | UC San Diego | 2024 |

**🥇 Achievements**
* Ranked among the **top 10 students** in the batch
* Solved **100+ DSA problems** on coding platforms, including LeetCode
* Led collaborative academic and software development projects

---

### 🔭 What I'm Working On

**🔨 Building**
* A new AI-based project *(details coming soon)*
* Full-stack applications and REST APIs
* AWS serverless workflows and data processing

**📘 Learning and exploring**
* AWS data engineering and ETL pipeline design
* AWS Glue, Amazon Redshift, and PySpark
* Data warehousing and analytical SQL
* Reliable cloud deployment, monitoring, and CI/CD
* Azure services through AWS comparison
* RAG, AI agents, and LLM integrations

---

### 💻 Development Focus

| Focus | Direction |
|:--|:--|
| ☁️ **Cloud & Data Engineering** | Serverless workflows, ETL, and analytics on AWS |
| 🌐 **Full-Stack Development** | MERN and Flask applications with REST APIs |
| 🤖 **Applied AI** | LLM-based tools and computer-vision systems |
| 🧩 **DSA & Fundamentals** | C++ problem solving and core CS |

---

### 🔗 Connect With Me

<p align="center">
  <a href="https://github.com/msiddiq786" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/md-siddiq786/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/u/m_siddiq/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <a href="https://www.instagram.com/sk__m__siddiq/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="mailto:skmsiddiqsiddiq@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=msiddiq786&show_icons=true&locale=en&theme=tokyonight&hide_border=true" alt="GitHub stats for msiddiq786" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs?username=msiddiq786&locale=en&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages for msiddiq786" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=msiddiq786&theme=tokyonight&hide_border=true" alt="GitHub contribution streak for msiddiq786" />
</p>

---

### 🎯 Current Focus

<p align="center">
  <b>Cloud & Data Engineering → SQL & PySpark → AWS Data Pipelines → Full-Stack Development → Applied AI</b>
</p>

<p align="center">
  <i>💡 Learn continuously. Build practically. Solve efficiently.</i>
</p>
