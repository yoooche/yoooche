# Hi, I'm Louis 👋

Java backend engineer based in Taipei, building distributed systems for multi-tenant platforms.

### What I work on

- High-concurrency services with Redis, Kafka, and Spring Boot
- Distributed rate limiting, data aggregation, and SQL tuning
- AI-assisted dev workflows with Claude Skills and MCP

### Tech stack

Java · Spring Boot · Redis · Kafka · RDBMS · GCP · Jenkins · ELK · Grafana

### Featured projects

- **[system-design-lab](https://github.com/yoooche/system-design-lab)**: Companion code for my [30-day iThome Ironman series](https://ithelp.ithome.com.tw/users/20161582/ironman/8273) on system design, a Spring Boot lab with Redis-backed rate limiters (fixed window, sliding window, token bucket, leaky bucket), Kafka messaging, and WebSocket notifications fanned out over Redis Pub/Sub.

### [Kumicare](https://github.com/kumicare)

A side project: an AI-powered LINE assistant for family care in my own household, self-hosted on a Hostinger VPS and built with AI coding agents.

- **kumi-center**: Java 21 / Spring Boot service that ingests door-sensor events over MQTT, stores them in Supabase PostgreSQL, and pushes LINE alerts
- **kumi-care**: Python BLE bridge that relays Xiaomi door-sensor events to MQTT over TLS, with a durable local outbox
- **kumi-brain-sql**: PostgreSQL schema with row-level security, idempotent RPCs, and database tests for shared household tasks
- **kumi-tools**: Agent plugin exposing family task, calendar, and sheet tools through named Supabase RPCs
- **kumi-app**: TypeScript API for deterministic LINE actions plus a React LIFF task app
- **kumi-docs-processor**: FastAPI + OpenCV document-scan MVP

### Currently exploring

AI-assisted development workflows built on Claude Skills and MCP.

[LinkedIn](https://www.linkedin.com/in/yoooche) · louis.yang.che@gmail.com
