# Hoyeon "Julian" Chae 

Backend engineer specializing in performance engineering and JVM internals.

Diagnoses concurrency bottlenecks through distributed metrics (Grafana) and low-level profiling (JFR/Thread Dumps) with hypothesis-driven analysis.

## 🎯 Featured Project

**SLAM!** — Concert Seat Reservation System handling high-concurrency bookings with real-time availability and payment processing
> [Repository Link](./slam)
- **Performance**: P99 latency 1.04s → 355ms (-66%), throughput +54% — root-caused G1GC STW pauses via JFR analysis and Little's Law verification
- **Reliability**: 3-layer API idempotency (Redis Response Cache → Redisson Distributed Lock → DB Unique Constraint)
- **Capacity Control**: Redis Sorted Set waiting queue with 90% network RTT reduction via pipelining
- **Observability**: Prometheus, Grafana, Loki with Trace ID correlation and threshold alerting

## Tech Stack

- **Languages & Frameworks**: Java 17, Spring Boot 3, Spring Data JPA, JUnit 5, Python
- **Data & Infrastructure**: MySQL 8.0, Redis 7.0, AWS (EC2, RDS, ECR, S3), Docker, GitHub Actions
- **Observability & Analysis**: Prometheus, Grafana, Loki, JFR, Thread Dump Analysis

## Contact
📧 julian247.dev@gmail.com · [LinkedIn](https://linkedin.com/in/ho-yeon-chae-095162341)
