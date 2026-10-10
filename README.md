### Hi, I'm Sudheer

I'm a backend engineer with almost five years of experience, mostly in Java and Spring Boot, and more recently Node.js and NestJS. I started at Accenture on a Spring Boot platform that grew to 10,000+ people online at once, with Kafka for the slow work and Docker and Kubernetes for shipping it. These days I automate an enterprise Microsoft 365 environment of 40,000+ users through the Graph API and mentor the juniors on my team, and in 2025–26 I built an internal client management platform on my own for a CA firm.

I'm looking for a Java backend role, or a backend or full-stack one, in Thailand, remote, or India, starting from November 2026. I live in Bengaluru and I'm ready to relocate to Bangkok. I'm a Thai citizen and also authorized to work in India, so I need no visa sponsorship in either, and I speak fluent English, conversational Thai and Hindi.

**Newest work: [OpsFlow AI](https://github.com/iamsrkg/opsflow-ai)** (October 2026). A system for the team that handles customer problems: it tracks each one through fixed steps, suggests a fix and waits for a manager to approve it. Spring Boot, Kafka, PostgreSQL and Redis, tested against the real services, and you can [run all of it in one click](https://codespaces.new/iamsrkg/opsflow-ai?quickstart=1).

**Portfolio: [iamsrkg.github.io/portfolio](https://iamsrkg.github.io/portfolio/).** It follows one request through a backend (edge, rate limiter, auth, service, database, queue) and shows where I've built each part. There's a live API you can try to break, too.

#### What I've done at work
- **Accenture, 2021–24:** Spring Boot microservices on Kubernetes for 10,000+ concurrent users. Indexes, rewritten queries and Redis caching made our APIs 75–80% faster. Document uploads went to S3, with processing moved onto Kafka and RabbitMQ consumers.
- **Freelance, 2025–26:** an internal client management platform in NestJS and TypeScript, on my own. I split auth into its own service (about 60% less coupling), added JWT, RBAC, rate limiting and audit logs, got responses under 100 ms on MySQL, and cut deploys from about 20 minutes to 3 with multi-stage Docker builds.
- **Accenture, 2024–now:** PowerShell and Microsoft Graph automation for an enterprise Microsoft 365 environment of 40,000+ users and ~100,000 sites. It took away about 75% of the manual work. I also build the governance dashboards and mentor junior team members.

#### Public code you can run
| Repo | What it is | Built with |
|---|---|---|
| [opsflow-ai](https://github.com/iamsrkg/opsflow-ai) · [run it](https://codespaces.new/iamsrkg/opsflow-ai?quickstart=1) | **My latest.** A system for the team that handles customer problems, such as "I was charged but my order is still pending". It tracks each problem through fixed steps, works out what probably happened, suggests a fix, and waits for a manager to approve it. | Java 17, Spring Boot 3.3, Kafka (outbox, idempotent consumers), PostgreSQL + pgvector, Redis, React. 45 tests against the real services, Kubernetes manifests checked in CI, and a load test (about 590 requests a second, p95 188 ms, no event lost). |
| [task-management-api](https://github.com/iamsrkg/task-management-api) · [run it](https://codespaces.new/iamsrkg/task-management-api?quickstart=1) | An API for projects and tasks used by many customers at once, where each customer can only ever see their own data. It comes with interactive docs you can click through. | Java 21, Spring Boot 4, PostgreSQL, Flyway, Redis rate limiting, JWT with refresh tokens. 26 tests. |
| [Video-Based-Dynamic-Human-Authentication-System](https://github.com/iamsrkg/Video-Based-Dynamic-Human-Authentication-System) · [try it](https://iamsrkg.github.io/Video-Based-Dynamic-Human-Authentication-System/) | A gate logger: it recognises the faces of people walking past a camera and records who came in and when. It runs in your browser, and nothing leaves your device. | Python, OpenCV, JavaScript |
| [tic-tac-toe](https://github.com/iamsrkg/tic-tac-toe) · [play it](https://iamsrkg.github.io/tic-tac-toe/) | A two-player game played live from two phones or two browser tabs. | React Native, Expo, PubNub |
| [portfolio](https://github.com/iamsrkg/portfolio) · [open it](https://iamsrkg.github.io/portfolio/) | My portfolio. It follows one request through a backend and has a live API you can try to break. | HTML, CSS, JavaScript, no framework |

**What I work with:** Java, Spring Boot, Spring Security, Spring Data JPA, JUnit, Node.js, NestJS, TypeScript, PostgreSQL, MySQL, Redis, Kafka, RabbitMQ, pgvector, Flyway, Testcontainers, Docker, Kubernetes, AWS, React, React Native.

AWS Certified Solutions Architect – Associate · [sudheerkgupta@outlook.com](mailto:sudheerkgupta@outlook.com) · [LinkedIn](https://www.linkedin.com/in/iamsrkg)
