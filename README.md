# System Design Master

> A structured, stage-by-stage system design course, from fundamentals to full HLD and LLD case studies.

- **By PKS** 

- **Youtube** · [@IamPradeepKumarSaini](https://www.youtube.com/@IamPradeepKumarSaini)
- **Instagram** · [@IamPradeepKumarSaini](https://www.instagram.com/iampradeepkumarsaini)

---

## About

This repository holds all my system design notes, diagrams, and case studies. The course is organised into 8 stages, each building on the previous one. Use the checkboxes to track progress as topics get published.

## Table of Contents

- [Stage 1: Introduction](#stage-1-introduction)
- [Stage 2: Scalability & Load Balancing](#stage-2-scalability--load-balancing)
- [Stage 3: Database Design](#stage-3-database-design)
- [Stage 4: Caching & CDN](#stage-4-caching--cdn)
- [Stage 5: Networking & API Design](#stage-5-networking--api-design)
- [Stage 6: System Design Trade-offs](#stage-6-system-design-trade-offs)
- [Stage 7: HLD Case Studies](#stage-7-hld-case-studies)
- [Stage 8: Low-Level Design](#stage-8-low-level-design)

---

## Stage 1: Introduction

- [ ] What is System Design?
- [ ] How to approach system design problems methodically?

## Stage 2: Scalability & Load Balancing

- [ ] Scalability (Horizontal vs Vertical Scaling)
- [ ] Load Balancers & Algorithms
- [ ] Availability
- [ ] Latency, Throughput & Fault Tolerance
- [ ] Forward Proxy & Reverse Proxy

## Stage 3: Database Design

- [ ] Basics of Databases (SQL & NoSQL)
- [ ] ACID Properties
- [ ] Database Indexing
- [ ] Database Sharding
- [ ] Replication Strategies
- [ ] CAP Theorem
- [ ] Consistent Hashing

## Stage 4: Caching & CDN

- [ ] Basics of Caching
- [ ] Caching Strategies
- [ ] Redis
- [ ] CDN

## Stage 5: Networking & API Design

- [ ] DNS Basics
- [ ] HTTP/HTTPS & TCP/UDP
- [ ] REST vs GraphQL vs gRPC
- [ ] Rate Limiting
- [ ] API Gateway

## Stage 6: System Design Trade-offs

- [ ] Strong vs Eventual Consistency
- [ ] Stateful vs Stateless Design
- [ ] Synchronous vs Asynchronous
- [ ] Kafka vs RabbitMQ (Internals)
- [ ] Monolith vs Microservices
- [ ] Load Balancer vs API Gateway

## Stage 7: HLD Case Studies

- [ ] URL Shortener (TinyURL)
- [ ] Cab Booking App (Uber / Ola)
- [ ] Photo & Video Sharing (Instagram)
- [ ] Video Streaming Platform (Netflix)
- [ ] Chat System (WhatsApp)
- [ ] E-Commerce System (Amazon / Flipkart)

## Stage 8: Low-Level Design

- [ ] How to approach Low-Level Design
- [ ] Object-Oriented Design Principles
- [ ] UML & Class Diagrams
- [ ] DB Design & ER Diagrams
- [ ] SOLID Principles
- [ ] KISS, DRY, YAGNI
- [ ] Design Patterns: Singleton, Factory, Observer, Builder & More

---

## Suggested Repository Structure

```
system-design/
├── README.md
├── 01-introduction/
├── 02-scalability-and-load-balancing/
├── 03-database-design/
├── 04-caching-and-cdn/
├── 05-networking-and-api-design/
├── 06-tradeoffs/
├── 07-hld-case-studies/
├── 08-low-level-design/
└── assets/            # diagrams, images, thumbnails
```

Each topic gets its own `.md` file inside its stage folder (e.g. `03-database-design/sharding.md`).

## Recommended Learning Path

1. Work through the stages in order. Each one assumes the previous.
2. For every case study in Stage 7, first attempt your own design, then compare it with the write-up.
3. Revisit Stage 6 after the case studies, as the trade-offs will make more sense in context.

## Contributing

Found a mistake or have a suggestion? Open an issue or submit a pull request.

## License

All rights reserved © PKS, unless stated otherwise.
