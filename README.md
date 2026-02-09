# Hoyeon "Julian" Chae

Backend Engineer focused on High-Performance Architecture and Distributed Systems.
Currently exploring low-latency trading engines and JVM internal optimizations.

---

### Project: SLAM! (Concert Reservation Service)

A high-concurrency ticket reservation service designed to handle traffic surges.

* **Problem:** Detected non-linear latency spikes and performance bottlenecks at 800 RPS during stress tests.
* **Resolution:** Analyzed JVM memory patterns and identified OOM killer triggers. Optimized JVM Heap configuration (512MB -> 2GB).
* **Result:** Improved throughput by 54% (1,250 RPS) and reduced P99 latency by 66% (1,040ms -> 355ms).
* **Stack:** Java, Spring Boot 3.4, Redis, AWS RDS, Docker Compose.
* **[Linke to repository](./slam)**

---

### Technical Stack

* **Languages:** Java, Python
* **Frameworks:** Spring Boot, Spring Data JPA
* **Infrastructure:** AWS (EC2, RDS), Docker, Redis, Promtail/Grafana
* **Interests:** Transaction Outbox Pattern, Saga Pattern, Electronic Trading Platforms, FIX Protocol

---

| [Email](julian247.dev@gmail.com) | [LinkedIn](https://www.linkedin.com/in/ho-yeon-chae-095162341/) |
