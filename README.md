<div align="center">

<img src="assets/hero.svg" alt="Nikhil Kumar Singh, Java Backend Engineer" width="100%" />

<br/>

<a href="mailto:ns94301918@gmail.com"><img src="https://img.shields.io/badge/EMAIL-040815?style=for-the-badge&logo=gmail&logoColor=5b9dff&labelColor=040815&color=0b1a3d" alt="Email" /></a>
<a href="https://www.linkedin.com/in/nikhil-kumar-singh-a167b2279/"><img src="https://img.shields.io/badge/LINKEDIN-040815?style=for-the-badge&logo=linkedin&logoColor=5b9dff&labelColor=040815&color=0b1a3d" alt="LinkedIn" /></a>
<a href="https://leetcode.com/u/Gasmonkey/"><img src="https://img.shields.io/badge/LEETCODE-040815?style=for-the-badge&logo=leetcode&logoColor=ffa726&labelColor=040815&color=0b1a3d" alt="LeetCode" /></a>
<a href="https://drive.google.com/file/d/1bm8whV2pOMs44I5w2UVcwXDwyb3iwwo2/view?usp=drive_link"><img src="https://img.shields.io/badge/R%C3%89SUM%C3%89-040815?style=for-the-badge&logo=googledrive&logoColor=ffa726&labelColor=040815&color=0b1a3d" alt="Résumé" /></a>

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-about.svg" alt="About" width="100%" />

Java backend engineer with **2+ years** of professional and internship experience building scalable REST APIs, microservices, and full-stack applications. My work centers on event-driven systems, distributed transactions, secure authentication, and production payment flows, deployed on AWS with Docker and automated CI/CD.

Comfortable across the stack with React, Next.js, and Node.js, but strongest where correctness, reliability, and data consistency matter.

<img src="assets/metrics.svg" alt="Key metrics: 5 production applications, 50,000+ users, 99.9% uptime, ~40% deployment efficiency gain, 4 payment gateways" width="100%" />

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-stack.svg" alt="Tech Stack" width="100%" />

<img src="assets/stack.svg" alt="Technology stack drawn as constellations: languages, frameworks, messaging and data, delivery" width="100%" />

<details>
<summary><b>Detailed skill matrix</b></summary>
<br/>

| Area | Details |
|---|---|
| **Java Platform** | OOP, Collections, Multithreading, Executor Framework, CompletableFuture, Streams, Lambdas, JDBC, Exception Handling, Virtual Threads |
| **Spring** | Spring Boot, Spring MVC, Spring Security, Spring Cloud Gateway, Hibernate / JPA |
| **Architecture** | REST API Design, Microservices, Event-Driven Architecture, Saga Pattern, Distributed Transactions, API Gateway (Spring Cloud Gateway, KrakenD), Service Discovery (Eureka), Design Patterns, System Design |
| **Data** | PostgreSQL, MySQL, MongoDB, MSSQL, Redis, Prisma, Mongoose |
| **Messaging** | Apache Kafka, RabbitMQ, gRPC |
| **Security** | JWT, RBAC, OAuth 2.0, Refresh Token Rotation, Rate Limiting, Webhook Signature Verification, Idempotency |
| **DevOps** | Docker, Docker Compose, AWS (EC2, S3), GitHub Actions CI/CD, Nginx, Linux |
| **Frontend** | React, Next.js, Redux Toolkit, Tailwind CSS, GSAP |
| **Tooling** | Git, GitHub, IntelliJ IDEA, Maven, Jira, Confluence |

</details>

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-experience.svg" alt="Experience" width="100%" />

### Software Developer · Narola Infotech
`JANUARY 2025 – PRESENT`

| Area | Contribution |
|---|---|
| **Engineering** | Designed and built REST APIs and microservices with Java, Spring Boot, and Hibernate/JPA |
| **Messaging** | Implemented asynchronous service communication using Apache Kafka and RabbitMQ |
| **Consistency** | Built distributed transaction workflows with the Saga Pattern and compensating transactions |
| **Security** | Implemented JWT authentication, RBAC, and refresh-token rotation |
| **Payments** | Integrated Razorpay with webhook verification and idempotency to prevent duplicate processing |
| **Performance** | Added Redis caching to reduce API latency and database load |
| **Delivery** | Containerized services with Docker, automated CI/CD with GitHub Actions (~40% faster deployments), and deployed on AWS |

**Outcome:** 5 production applications · 50,000+ users · 99.9% uptime
**Systems delivered:** `DONRIFA` `ENIRA` `ALICE` `HIVEONE` `ERP Automation` `OCR System`

### Web Development Intern · TechnoHacks EduTech, CodSoft, Bharat Intern
`JULY 2023 – SEPTEMBER 2023`

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-projects.svg" alt="Projects" width="100%" />

### Java Backend and Microservices

| Project | Stack | Highlights |
|---|---|---|
| **Banking Microservices** | `Java` `Spring Boot` `Kafka` `PostgreSQL` | Saga Pattern, compensating transactions, event-driven communication, idempotent consumers |
| **Salon Booking Platform** | `Spring Boot` `Cloud Gateway` `Eureka` `PostgreSQL` `Docker` | Six services (users, salons, categories, services, bookings, payments) with service discovery and gateway routing |
| **Job Application Portal** | `Spring Boot` `Kafka` `Redis` `JWT` | API Gateway, refresh-token rotation, caching, event messaging, Razorpay integration |
| **Real-Time Chat Application** | `Java` `RabbitMQ` `Redis` | Concurrent messaging with asynchronous queues and caching |
| **Redis Caching Module** | `Java` `Redis` | Caching layer that reduces API response times |

### Full-Stack and Other

| Project | Stack | Highlights |
|---|---|---|
| **E-Commerce Application** | `MERN` `Redux` `Stripe` | Cart management, payments, automated email workflows |
| **AgroNet** | `MERN` | Farmers sell directly to buyers: listings, orders, authentication |
| **GenAI Applications** | `Node.js` `AI APIs` | Text, image, and audio generation via asynchronous pipelines |
| **3D Animated Website** | `GSAP` `Locomotive Scroll` | Scroll-triggered animation, parallax, smooth transitions |
| **Platform Clones** | `React` `CSS` | Responsive UIs modeled on Spotify, Netflix, Amazon, X.com |

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-payments.svg" alt="Payment Systems" width="100%" />

| Gateway | Region | Implementation |
|---|---|---|
| **Square** | US / Global | Payments API, Orders API, OAuth 2.0, webhook handling |
| **Place to Pay** | Latin America | Session-based checkout, status polling, HMAC validation |
| **ATH Móvil** | Puerto Rico | Production payment request flow and callback handling |
| **Razorpay** | India | Orders API, capture, refunds, UPI, cards, webhook verification |

<details>
<summary><b>Implementation practices</b></summary>
<br/>

- Full lifecycle handling: session creation, checkout, confirmation, cancellation.
- Webhook listeners for asynchronous status updates and order reconciliation.
- Idempotency to prevent duplicate payment processing.
- Defensive error handling and logging for production use.
- Unified payment service abstraction inside a microservices architecture.
- PCI-oriented design: raw card data is never stored.

</details>

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-analytics.svg" alt="Analytics" width="100%" />

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Nikhil79922&hide_border=true&background=040815&ring=5B9DFF&fire=8FD0FF&currStreakNum=E8F1FF&sideNums=E8F1FF&currStreakLabel=8FD0FF&sideLabels=7F93B8&dates=7F93B8" alt="Contribution streak" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nikhil79922/Nikhil79922/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Nikhil79922/Nikhil79922/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/Nikhil79922/Nikhil79922/output/github-snake-dark.svg" width="100%" />
</picture>

<br/>

<a href="https://leetcode.com/u/Gasmonkey/">
  <img src="https://leetcard.jacoblin.cool/Gasmonkey?theme=dark&font=Karma&ext=heatmap" alt="LeetCode statistics" width="620" />
</a>

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-recognition.svg" alt="Recognition" width="100%" />

| Recognition | Details |
|---|---|
| **Agile Person of the Team 2026** | Narola Infotech, for Agile/Scrum ownership and delivery |
| **Employee of the Month** | Narola Infotech, for consistent performance and ownership |
| **LeetCode 100-Day Streak Badge** | 100 consecutive days of problem solving |
| **200+ DSA Problems Solved** | LeetCode, CodeChef, GeeksforGeeks |

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-education.svg" alt="Education" width="100%" />

**B.Tech, Computer Science and Engineering** · Sandip University, Nashik
Graduated 2025 · CGPA **9.11**

<img src="assets/divider.svg" alt="" width="100%" />

<img src="assets/h-contact.svg" alt="Contact" width="100%" />

<div align="center">

<a href="mailto:ns94301918@gmail.com"><img src="https://img.shields.io/badge/EMAIL_ME-040815?style=for-the-badge&logo=gmail&logoColor=5b9dff&labelColor=040815&color=0b1a3d" alt="Email" /></a>
<a href="https://www.linkedin.com/in/nikhil-kumar-singh-a167b2279/"><img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-040815?style=for-the-badge&logo=linkedin&logoColor=5b9dff&labelColor=040815&color=0b1a3d" alt="LinkedIn" /></a>
<a href="https://github.com/Nikhil79922"><img src="https://img.shields.io/badge/FOLLOW_ON_GITHUB-040815?style=for-the-badge&logo=github&logoColor=ffa726&labelColor=040815&color=0b1a3d" alt="GitHub" /></a>

<br/><br/>

<img src="assets/footer.svg" alt="Let's build something reliable" width="100%" />

</div>