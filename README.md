# Benjamin Hanonove

**Backend developer · Node.js · TypeScript · AWS serverless** · Netanya, Israel

I build backends that run in production. As a freelancer I design, build and run serverless
TypeScript platforms on AWS. The biggest one is a real-time operations platform used daily by
2 paying venues: ~130 Lambda handlers, defined as code with SST, with separate dev and prod stages.

- ⚡ **Real time:** DynamoDB Streams → EventBridge Pipes → broadcaster Lambda → WebSockets
- 🔐 **Access control:** role-based, with field-level redaction enforced in the API and mirrored in the UI
- ✅ **Tests:** integration suites run against a live dev stage and gate every production deploy
- 🎟️ Before that: NestJS + PostgreSQL REST/WebSocket endpoints for live seat availability and checkout at a ticketing startup, deployed on AWS ECS

B.Sc. Computer Science . M.Sc. in progress, on the thesis track.

### Stack
`TypeScript` · `Node.js` · `NestJS` · `Express` · `Go` · `Python` · `SQL`
`AWS Lambda` · `API Gateway (HTTP / WebSocket)` · `DynamoDB` · `EventBridge` · `Cognito` · `S3` · `SES` · `ECS` · `SST`
`PostgreSQL` · `MongoDB` · `Redis` · `Docker` · `Vitest` · `Playwright`

### Public work
| Project | What it is | Stack |
|---|---|---|
| [kick-showcase](https://github.com/BenyHanonove/kick-showcase) | Real-time serverless operations platform for bars & event venues (2 paying customers): ~130 Lambdas, DynamoDB Streams → EventBridge Pipes → WebSockets, optimistic locking, versioned Redis cache | TypeScript · AWS Serverless · SST · Vue 3 |
| [robot-tls-padding-oracle](https://github.com/BenyHanonove/robot-tls-padding-oracle) | 3 services on Docker Compose running a parallel Bleichenbacher (ROBOT) attack on TLS 1.2 in a lab network | Go · goroutines · Docker |
| [pqc-gpu-side-channels](https://github.com/BenyHanonove/pqc-gpu-side-channels) | M.Sc. thesis groundwork: side-channel leakage of post-quantum crypto (ML-KEM) on GPUs | research · Python |
| [earthquake-network-analysts](https://github.com/BenyHanonove/earthquake-network-analysts) | Graph-theoretic analysis of 1995–2023 global earthquakes with NetworkX: centrality and community detection surface the Ring of Fire | Python · NetworkX |

Other client work is in private repos. I'm happy to walk through the architecture and code in an interview.

📫 [benyhanonove@gmail.com](mailto:benyhanonove@gmail.com) · [LinkedIn](https://www.linkedin.com/in/beny-hanonove-9b1902220)
