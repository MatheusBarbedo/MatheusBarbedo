# Matheus Barbedo

Senior full stack developer at **Autoglass** since 2021, based in Vitória, Brazil. I build back-end services, APIs and integrations in C#/.NET with Angular front ends, and I design multi-agent AI workflows (Claude Code and GitHub Copilot) that take a ticket from plan to tested change.

[Portfolio](https://matheusbarbedo.github.io) · [LinkedIn](https://www.linkedin.com/in/matheus-eugenio-barbedo-da-silva/) · [matheus.barbedo.2001@gmail.com](mailto:matheus.barbedo.2001@gmail.com)

## What I work on

- **Vehicle inspection platform** (.NET 8, Angular 21, Oracle, NHibernate): a plug-and-play product where new insurers and integrators are onboarded through configuration. OAuth2 client_credentials with AWS Cognito, a mobile self-inspection web app, Liquibase migrations with safe rollback.
- **Legacy integrations** (.NET Framework, Dapper): REST, XML and SFTP exchanges with insurers, SQS and Kafka messaging, SMS and WhatsApp delivery tracking with Infobip and Zenvia.
- **Platform and production**: CI/CD migration from Jenkins and Docker Swarm to Azure DevOps and Kubernetes; root-cause work on pod OOMKills, queue redelivery and slow reports with Grafana, Loki and Thanos; Angular 18 to 21 upgrade in production.
- **AI agent engineering**: an orchestrator that routes each ticket to domain subagents with a complexity gate, evals on a regression golden dataset, context and token budgets, and knowledge agents for .NET, Angular and Oracle that cite official sources.

## Selected projects

| Project | What it is | Stack |
|---|---|---|
| [context-saver](https://github.com/MatheusBarbedo/context-saver) | Token saver for AI coding agents: a hook compresses verbose command output and keeps the exit code | Node.js, zero dependencies |
| [Copylândia](https://github.com/MatheusBarbedo/copylandia-backend) | Self-service printing kiosk with Pix checkout and payment webhook (capstone) | .NET 8, Angular, EF Core |
| [e7-shop-refresher](https://github.com/MatheusBarbedo/e7-shop-refresher) | Game shop automation with a GUI, OCR and an installer | Python, ADB, Tesseract |
| Nosso Dinheiro | Desktop finance app for couples with expense splitting and budgets (private) | Tauri 2, React, Supabase |
| limbus-companion | Desktop companion that reads live game state and automates runs (private) | Tauri 2, Vue 3, C++ |

More on the [portfolio](https://matheusbarbedo.github.io/projetos.html).

## Stack

**Back end:** C#, .NET 8, ASP.NET Core, Minimal API, Dapper, NHibernate, EF Core, xUnit<br>
**Front end:** Angular, TypeScript, React, Vue 3<br>
**Data:** Oracle SQL/PLSQL, Liquibase, MongoDB, Supabase<br>
**Cloud and messaging:** AWS (Cognito, SQS, S3), Kafka<br>
**Delivery and operations:** Azure DevOps, Kubernetes, Docker, Grafana, Loki, Thanos, Kibana, SonarQube<br>
**AI:** Claude Code, GitHub Copilot, multi-agent orchestration, evals, context engineering
