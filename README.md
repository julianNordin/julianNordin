### Hi, I'm Julian 👋

Computer Engineer (B.Sc., Mid Sweden University) with a focus on AI/ML, backend development, and databases. My bachelor's thesis explored Federated Learning for privacy-preserving image classification, and I'm currently continuing toward a master's in Visual AI. I like building full systems end-to-end — from database schema to API to a working UI — and I'm especially interested in applying machine learning to real-world, privacy-sensitive problems.

- 🎓 B.Sc. Computer Engineering, Mid Sweden University (2021–2024)
- 🔭 Currently exploring AI, machine learning, and Visual AI (M.Sc. studies)
- 🏗️ Lately building production-style backend systems — authentication, concurrency control, CI/CD, and infrastructure as code — across .NET, Java/Spring, and NestJS
- 🌍 Based in Stockholm, Sweden
- 📫 julian.nordin94@gmail.com · [LinkedIn](https://www.linkedin.com/in/julian-nordin94/) · [Portfolio](https://portfolio-tau-neon-66.vercel.app)

---

### 🛠️ Skills

**Languages:** Python · Java · C# · C++ · TypeScript/JavaScript · PHP · SQL · HTML/CSS

**Backend & APIs:** ASP.NET Core · Spring Boot · NestJS · Node.js/Express.js · Jakarta EE (JAX-RS, JPA) · REST APIs · EF Core · Prisma

**Frontend:** React · Angular · Next.js · TanStack Query

**Databases:** PostgreSQL · SQL Server · MariaDB · MySQL

**Cloud & DevOps:** Azure (Bicep, Key Vault, managed identity) · Docker/Docker Compose · GitHub Actions (CI/CD) · RabbitMQ

**Testing:** xUnit · JUnit 5 · Vitest · Playwright · Testcontainers

**AI / Machine Learning:** TensorFlow Federated · Keras · CNNs · Federated Learning · Differential Privacy

**Tools & Platforms:** Git/GitHub · Linux · Android Studio · IntelliJ IDEA · VS Code · Raspberry Pi

---

### 📌 Featured projects

**Backend & APIs**

| Project | Description |
|---|---|
| 📚 [LibrarySystem.Api](https://github.com/julianNordin/LibrarySystem.Api) | ASP.NET Core REST API for library lending (EF Core, SQL Server) with real business rules — active-loan caps, no double-lending, overdue tracking — enforced server-side, not just CRUD. |
| 🔐 [secure-notes-identity-jwt](https://github.com/julianNordin/secure-notes-identity-jwt) | A notes API where auth is the feature: ASP.NET Core Identity, JWT access tokens, rotating refresh tokens with reuse detection, three authorization models — 103 tests against real PostgreSQL. |
| 🥗 [recipe-api-java-spring](https://github.com/julianNordin/recipe-api-java-spring) | Java 21 + Spring Boot 3.5 REST API for recipes and ingredients with specification-based search and serving-count rescaling — 181 tests via JUnit 5/Mockito/Testcontainers. |
| 🎫 [event-booking-nestjs](https://github.com/julianNordin/event-booking-nestjs) | NestJS + Prisma + PostgreSQL API for event registrations, built around the one problem a CRUD demo can't show: two people racing for the last seat, resolved with `SELECT ... FOR UPDATE`. 650 tests. |
| 📦 [order-processing-worker](https://github.com/julianNordin/order-processing-worker) | An order pipeline on RabbitMQ: an ASP.NET Core API accepts an order and answers immediately, while a separate .NET worker consumes it and generates a receipt asynchronously. |

**Frontend**

| Project | Description |
|---|---|
| 💻 [LibrarySystem.Web](https://github.com/julianNordin/LibrarySystem.Web) | React + TypeScript frontend for the library API — browsing, borrowing/returning, loan history — consuming a real REST API instead of mocked data. |
| 💰 [expense-tracker-angular](https://github.com/julianNordin/expense-tracker-angular) | Angular expense tracker with categorized spending, monthly summaries, and per-category budgets; filters live in the URL. Standalone components, zoneless change detection, 430 tests. |
| 📓 [recipe-journal](https://github.com/julianNordin/recipe-journal) | A recipe site on the Next.js App Router where Server Components read Postgres directly and Server Actions write through it — no client-side data layer at all. |

**Cloud & DevOps**

| Project | Description |
|---|---|
| ☁️ [librarysystem-azure-deploy](https://github.com/julianNordin/librarysystem-azure-deploy) | The library system deployed to Azure entirely from code: infrastructure in Bicep, secrets in Key Vault via managed identity, and a GitHub Actions pipeline that authenticates with zero stored credentials. |
| 🔗 [shortlink-docker-cicd](https://github.com/julianNordin/shortlink-docker-cicd) | A URL shortener used as the vehicle for multi-stage Docker builds, Docker Compose, PostgreSQL, and a GitHub Actions pipeline publishing to GHCR. |
| 🟢 [statuspage](https://github.com/julianNordin/statuspage) | A status page that doesn't depend on the system it's reporting on. |

**Testing**

| Project | Description |
|---|---|
| 🧪 [library-test-automation](https://github.com/julianNordin/library-test-automation) | End-to-end test automation for the library stack: Playwright driving a real browser against a live ASP.NET Core API, React SPA, and SQL Server. |

<details>
<summary><b>📚 Earlier projects</b> (academic & coursework)</summary>

| Project | Description |
|---|---|
| 🧠 [Federated Learning for Image Classification](https://github.com/julianNordin/federated-learning-image-classification) | Bachelor's thesis on privacy-preserving image classification with TensorFlow Federated, comparing model accuracy against differential-privacy noise levels on EMNIST. |
| 🍽️ [Restaurant Order Management System](https://github.com/julianNordin/restaurant-order-management-system) | Full-stack system for a restaurant: Jakarta EE REST API, MariaDB, and an Android app for staff to manage orders, menus, bookings, and schedules. |
| 🦋 [MOTH Surveillance System](https://github.com/julianNordin/moth-surveillance-system) | Privacy-conscious occupancy tracking with PIR sensors on a Raspberry Pi, a Node.js sensor service, and a PHP dashboard — built with a 5-person team. |
| 🎮 [Maze++](https://github.com/julianNordin/cpp-maze-game) | A 2D maze game in C++ and SFML with procedural maze generation, key/door mechanics, and a limited-visibility "flashlight" view. |
| 📊 [C++ Data Structures & Algorithms](https://github.com/julianNordin/cpp-data-structures-algorithms) | Sorting and searching algorithms implemented and empirically benchmarked in C++, with results plotted in Python. |
| 💬 [PHP Q&A Forum](https://github.com/julianNordin/php-guestbook-app) | A Stack Overflow-style forum with authentication, posts, comments, and search, built with PHP/PDO and vanilla JS. |

</details>

---

<sub>Profile last updated September 2026.</sub>
