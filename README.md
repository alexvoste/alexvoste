# Alex Voste

**Network Systems Engineer | Low-Level Developer | Infrastructure Specialist**

[📧 Email](mailto:wien8825@gmail.com) &nbsp;•&nbsp; [✈️ Telegram](https://t.me/wienton) &nbsp;•&nbsp; [💻 GitHub](https://github.com/wienton)

---

## Professional Summary

Engineer focused on building high-performance, reliable networked systems. I work close to the metal—designing protocols, optimizing I/O paths, and hardening infrastructure where latency, throughput, and correctness are non-negotiable.

**Core competencies:**
- Systems programming in C with POSIX/Linux APIs
- Network protocol implementation and analysis (TCP/UDP/HTTP/WebSocket)
- Event-driven architectures: epoll, kqueue, libevent, async I/O
- Observability: custom agents, Prometheus/Grafana integration
- Infrastructure automation: Docker, CI/CD, Bash tooling

---

## Technical Stack

### Languages & Runtimes

C • C++ • Python • Node.js • Bash • Java


### Networking & Systems
| Layer | Technologies |
|-------|-------------|
| **Transport** | TCP, UDP, Raw Sockets, Socket Options, Non-blocking I/O |
| **Application** | HTTP/1.1–2, WebSocket, DNS, Custom binary protocols |
| **Multiplexing** | epoll, select, poll, kqueue, io_uring (exploratory) |
| **Concurrency** | pthreads, mutexes, condition variables, atomics, lock-free patterns |
| **OS Internals** | Signals, IPC (pipes, shared mem, sockets), daemonization, cgroups |

### Data & Storage
- **Relational**: PostgreSQL (query optimization, connection pooling)
- **In-Memory**: Redis (pub/sub, caching patterns, persistence tuning)
- **Serialization**: Protobuf, MessagePack, custom TLV formats

### Observability & DevOps
- **Monitoring**: Prometheus exporters, Grafana dashboards, structured logging
- **Deployment**: Docker, multi-stage builds, minimal base images
- **Automation**: GitHub Actions, Bash orchestration, idempotent provisioning

---

## Engineering Focus

🔹 **High-Performance Servers**  
Building from scratch: connection handling, backpressure, graceful shutdown, zero-copy techniques.

🔹 **Protocol Engineering**  
Specification analysis, wire-format reverse-engineering, conformance testing, fuzzing.

🔹 **System Reliability**  
Defensive coding, resource accounting, timeout strategies, circuit breakers, health checks.

🔹 **Performance Diagnostics**  
Profiling with perf/eBPF, latency histograms, flame graphs, bottleneck isolation.

🔹 **Infrastructure as Code**  
Reproducible environments, declarative configuration, drift detection.

---

## Selected Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=wienton&show_icons=true&theme=github_dark&hide_title=true&hide=stars,commits,prs,issues,contribs" alt="GitHub Stats" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wienton&layout=compact&theme=github_dark&hide=jupyter%20notebook" alt="Top Languages" width="49%" />
</p>

> Metrics reflect public activity. Production systems often live where badges don't reach.

---

## Principles

1. **Clarity over cleverness** — Code is read far more than it's written.
2. **Measure before optimizing** — Intuition is a starting point, not proof.
3. **Fail explicitly** — Silent errors are technical debt with compound interest.
4. **Design for observability** — If you can't measure it, you can't improve it.
5. **Respect the stack** — Abstractions are tools, not substitutes for understanding.

---

## Current Focus

- Refining a minimal, zero-dependency TCP server framework in C
- Building eBPF-based network telemetry for latency attribution
- Documenting protocol state machines for team onboarding
- Exploring Rust for safe systems programming without GC overhead

---

<sub>Updated: March 2026 • Preferences: Unix philosophy, static linking, minimal dependencies, RFC-first design.</sub>
