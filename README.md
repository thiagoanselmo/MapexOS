# 🌐 MapexOS

**MapexOS** is an open-source, modular IoT operating system designed to unify device communication, rule automation, and edge/cloud deployment under a single extensible platform.

---

## 👤 About Me

Hi! I'm **Thiago Anselmo**, a software engineer and entrepreneur with over 16 years of experience building high-impact solutions — from scalable web systems to industrial-grade IoT platforms.

I'm the founder of **MAPEX**, a company born to develop cutting-edge technology. Our first software product is **MapexOS**, and we’re proud to launch it as a **100% open-source platform** — designed to empower developers, integrators, and businesses around the world.

---

## 📖 Why MapexOS?

Over the years, I’ve worked with platforms like **ChirpStack** and **ThingsBoard**, which have helped shape the IoT ecosystem. While powerful, these platforms fall short when applied to **real-world, scalable, multi-tenant environments** — especially when simplicity, extensibility, and enterprise integration are required.

Here’s what drove me to create **MapexOS**:

- ❌ **No native SSO or identity integration** in ChirpStack — hard to scale securely across teams or customers  
- ⚠️ **ThingsBoard offers a rule engine**, but it's heavily based on **Node-RED-style flows**, which require **technical knowledge** of protocols and internal message structures — making it **inaccessible to non-developers**  
- ❌ **No first-class support for data lake storage**, especially common backends like **AWS S3** or **Delta Lake**  
- ❌ Protocol support is fragmented — needing complex setups or external services to combine HTTP, MQTT, CoAP, and LoRaWAN  
- ❌ Difficult to customize or extend components (e.g., rule engine, alert system, data routing) without deep internal rewiring  
- ❌ Limited user experience for defining business logic or monitoring device state in a human-friendly way  

These challenges led to the vision behind **MapexOS** — a truly **modular**, **open**, and **developer + business-friendly** IoT platform that lowers the entry barrier while increasing flexibility.

---

## 🎯 What Makes MapexOS Different?

MapexOS is designed from day one to solve these pain points with:

- ✅ **Enterprise-ready auth**: Native integration with **SSO**, **OAuth2**, **OIDC**, and **Keycloak**
- ✅ **Data lake integration**: Built-in routing to **AWS S3** and future support for **Delta Lake**, **MinIO**, etc.
- ✅ **Simplified Rule Engine**: Designed to be **intuitive for non-technical users**, while still giving developers the power to define advanced logic
- ✅ **Unified Protocol Support**: Native ingestion of **HTTP**, **MQTT**, and **CoAP** (with **LoRaWAN** coming soon)
- ✅ **Clear modular architecture**: Easy to extend, replace, or plug into any part of the pipeline
- ✅ **Edge + Cloud-native**: Lightweight **Go-based ingestion**, with **NestJS** backend for business logic and event handling
- ✅ **Built-in alerting & messaging**: Integrated with **RabbitMQ**, **Kafka**, and **webhooks** for real-time automation

---

## 🧱 Tech Stack

| Component       | Technology            |
|----------------|------------------------|
| Cloud Backend   | NestJS + TypeScript |
| Edge Ingestion  | Go (Golang)            |
| Frontend        | Vue 3 + Quasar Framework |
| Protocols       | HTTP, MQTT, CoAP (initial) |
| Rule Engine     | Low-code & JavaScript-based rule workers |
| Messaging       | RabbitMQ, Kafka (event integration) |
| Data Lake       | AWS S3 (native), Delta Lake, MinIO |
| Auth            | OAuth2, OIDC, Keycloak |
| Deployment      | Kubernetes-ready |

---

## 🚀 Roadmap (WIP)

### ✅ Phase 1 — Core Platform

- [x] Protocol ingestion modules (Go): HTTP, MQTT, CoAP
- [x] Backend API with NestJS
- [x] Frontend with Vue 3 + Quasar for:
  - Multi-tenancy management
  - Device and gateway registry
  - Event log visualization
  - Alert configuration (Slack, Teams, Telegram, Email)
  - Basic rule manager (UI)
- [x] Event routing via HTTP, RabbitMQ, or Kafka
- [x] Integration with Keycloak or compatible SSO
- [x] Friendly and intuitive UI for both developers and non-tech users

### 🚧 Phase 2 — Advanced Intelligence & LNS

- [ ] Integration of a custom **LoRaWAN Network Server**
- [ ] Rule engine isolation using **JavaScript workers**
- [ ] Visual no-code environment for rule creation
- [ ] Advanced device profiling and dynamic configuration engine

---

## 🤝 Inspired by

We stand on the shoulders of giants. MapexOS takes inspiration from:
- ChirpStack
- ThingsBoard
- Node-RED
- Temporal.io for eventual workflow modeling

---

## 📢 Get Involved

This project is in **early development**. I'm opening it up to developers, makers, and contributors who believe in building **open, powerful, and flexible IoT infrastructure**.

Follow the roadmap, suggest ideas, or contribute code — let’s build something extraordinary together.

---

## 📄 License

This project is licensed under the **Apache 2.0 License** — open, permissive, and ready for collaboration.

---

> Built with ❤️ by Thiago Anselmo
