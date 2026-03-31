# Sharuf Zaryab

Rust backend engineer. I build distributed systems, async APIs, and real-time backends. Background in C++ before switching full-time to Rust.

---

## Stack

**Language:** Rust · C++  
**Web:** Axum · REST · WebSockets  
**Async:** Tokio  
**Databases:** PostgreSQL · Redis  
**Messaging:** Apache Kafka  
**RPC:** gRPC · Tonic · Protocol Buffers  
**Auth:** JWT · Argon2  
**Infra:** Docker · Docker Compose · SQLx  

---

## Projects

### [Vehicle Detailing Platform](https://github.com/Sharufkhanniazi/vehicle-detailing)
Uber-style on-demand service backend — built as a full microservices system in Rust.

- 7 independent services communicating via **Kafka** (event-driven architecture)
- **gRPC** pricing service using Tonic + Protocol Buffers
- Real-time detailer tracking with **WebSockets** + Redis location caching
- Proximity-based detailer matching using **Haversine formula**
- Saga pattern for distributed transactions across services
- Integration tests per service, full Docker Compose setup

### [Real-Time Chat API](https://github.com/Sharufkhanniazi/Chat-Api)
Production-grade chat backend with rooms, DMs, and real-time messaging.

- WebSocket broadcasting with one-connection-per-user design
- Chat rooms, direct messaging, invitations, blocking, muting
- Redis caching layer + PostgreSQL with optimized indexes
- JWT auth, Argon2 password hashing, soft deletion

---

## Open to Work

I'm currently looking for **remote backend engineering roles** — Rust preferred, open to other backend opportunities.  
Feel free to reach out.
