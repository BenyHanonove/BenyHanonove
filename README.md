# Benjamin Hanonove

**Backend developer · Node.js · TypeScript · AWS serverless** · Netanya, Israel

I build backends that run in production. As a freelancer I design, build and run serverless
TypeScript platforms on AWS. The biggest one is a real-time operations platform used daily by
2 paying venues: ~130 Lambda handlers, defined as code with SST, with separate dev and prod stages.

- ⚡ **Real time:** DynamoDB Streams → EventBridge Pipes → broadcaster Lambda → WebSockets
- 🔐 **Access control:** role-based, with field-level redaction enforced in the API and mirrored in the UI
- ✅ **Tests:** integration suites run against a live dev stage and gate every production deploy
- 🎟️ Before that: NestJS + PostgreSQL REST/WebSocket endpoints for live seat availability and checkout at a ticketing startup, deployed on AWS ECS

B.Sc. Computer Science (GPA 86). M.Sc. in progress, on the thesis track.

### Stack
`TypeScript` · `Node.js` · `NestJS` · `Express` · `Go` · `Python` · `SQL`
`AWS Lambda` · `API Gateway (HTTP / WebSocket)` · `DynamoDB` · `EventBridge` · `Cognito` · `S3` · `SES` · `ECS` · `SST`
`PostgreSQL` · `MongoDB` · `Redis` · `Docker` · `Vitest` · `Playwright`

### Public work
| Project | What it is | Stack |
|---|---|---|
| [robot-tls-padding-oracle](https://github.com/BenyHanonove/robot-tls-padding-oracle) | 3 services on Docker Compose running a parallel Bleichenbacher (ROBOT) attack on TLS 1.2 in a lab network | Go · goroutines · Docker |
| [pqc-gpu-side-channels](https://github.com/BenyHanonove/pqc-gpu-side-channels) | M.Sc. thesis groundwork: side-channel leakage of post-quantum crypto (ML-KEM) on GPUs | research · Python |

The client work is in private repos. I'm happy to walk through the architecture and code in an interview.

📫 [benyhanonove@gmail.com](mailto:benyhanonove@gmail.com) · [LinkedIn](https://www.linkedin.com/in/beny-hanonove-9b1902220)
