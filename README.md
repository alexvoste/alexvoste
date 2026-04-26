# Alex Voste

**Systems Engineer | Low-Level Developer | Infrastructure Architect**

[![Email](https://img.shields.io/badge/Email-alexvoste%40gmail.com-blue?style=flat-square&logo=gmail)](mailto:alexvoste@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alex--Voste-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/alex-voste-232179406/)
[![GitHub](https://img.shields.io/badge/GitHub-alexvoste-181717?style=flat-square&logo=github)](https://github.com/alexvoste)

---

## ⚡ Professional Summary

Systems Engineer dedicated to engineering high-performance, resilient networked environments. I specialize in **low-level development** and **protocol design**, moving beyond high-level abstractions to optimize I/O paths, minimize latency, and ensure system correctness at scale.

**Core Expertise:**
* **Systems Programming:** C/POSIX, Linux internals, and manual resource management.
* **Networking:** Custom protocol implementation, socket state machines, and traffic orchestration.
* **High-Concurrency:** Event-driven architectures (epoll/kqueue) and lock-free synchronization.
* **Infrastructure:** Hardened CI/CD pipelines, containerization, and observability-driven operations.

---

## 🛠 Technical Ecosystem

### Languages & Runtimes
`C` • `C++` • `TypeScript/Node.js` • `Python` • `Bash` • `Java`

### Deep Dive: Networking & Systems
| Domain | Technologies & Concepts |
| :--- | :--- |
| **Transport Layer** | TCP/UDP, Raw Sockets, Non-blocking I/O, Zero-copy (sendfile/splice) |
| **Application Layer** | HTTP/2, WebSockets, gRPC, Custom Binary Serializations (TLV) |
| **I/O Multiplexing** | `epoll`, `kqueue`, `libuv`, `io_uring` |
| **Concurrency** | Pthreads, Atomic operations, Mutex/Cond-var, Signal handling |
| **Kernel & OS** | IPC (Shared Memory, Unix Domain Sockets), eBPF, Namespace isolation |

### Data & Middleware
* **Storage:** PostgreSQL (Advanced indexing & pooling), Redis (Data structures & Pub/Sub).
* **Messaging:** Protobuf, MessagePack, JSON-RPC.
* **Observability:** Prometheus, Grafana, OpenTelemetry, Structured Logging.

---

## 🚀 Engineering Pillars

### 🏗 High-Performance Servers
Building robust backends from the ground up. Expertise in handling C10k+ problems, implementing backpressure mechanisms, and ensuring graceful degradation under peak loads.

### 📐 Protocol Engineering
Analysis and implementation of RFC-compliant protocols. Experienced in wire-format reverse engineering, state machine modeling, and fuzz testing for security hardening.

### 🔍 Performance Diagnostics
Identifying bottlenecks using `perf`, `strace`, and `eBPF`. Utilizing flame graphs and latency histograms to drive data-informed optimizations.

### 🛡 Infrastructure Reliability
Applying the Unix philosophy to DevOps: small, composable tools, reproducible Docker builds, and automated, idempotent deployment workflows.

---

## 📊 Activity & Insights

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=alexvoste&show_icons=true&theme=github_dark&hide_border=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=alexvoste&theme=github_dark&hide_border=true" width="48%" />
</p>
> Note: Public metrics represent a fraction of my work; the most critical systems often operate behind private perimeters.

---

## 📜 Engineering Manifesto

1.  **Code is for humans; execution is for machines.** Prioritize readability and maintainability without sacrificing performance.
2.  **Explicit > Implicit.** Errors should never pass silently. Defensive programming is the baseline, not an extra.
3.  **Observability is not optional.** If a system isn't measurable, it's not production-ready.
4.  **Understand the abstraction.** Using a library is a choice; knowing how it interacts with the kernel is a requirement.

---

## 🔭 Current Initiatives
* **Minimalist C Framework:** Developing a zero-dependency, event-loop driven TCP framework.
* **VPN Infrastructure:** Optimizing proxy-management systems and crypto-payment integrations.
* **Rust Transition:** Evaluating memory-safe systems programming for security-critical components.

---

<p align="center">
  <sub>Updated: April 2026 • <b>Philosophy:</b> Minimal dependencies, RFC-first design, Static linking.</sub>
</p>
