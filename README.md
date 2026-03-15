<div align="center">
  <h1>Hi there, I'm Dmytro Melnyk! 👋</h1>
  <h3>Backend Systems & Platform Engineer | Distributed Systems | Kubernetes</h3>
  
  <p>
    Building resilient, high-throughput distributed systems and deep-system observability tools. <br>
    Passionate about <b>Go internals, Linux Kernel (eBPF), Consensus Protocols (Raft), and Cloud-Native orchestration</b>.
  </p>

  <a href="mailto:dmytro.mircus@gmail.com">
    <img src="https://img.shields.io/badge/Email-Me-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/morcux">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

---

### 🏆 Featured Open Source Projects

I spend my free time building infrastructure tooling, kernel-level tracers, and cloud-native control planes from scratch:

*   🐝 **[eBPF TCP Connection Scanner](https://github.com/morcux/ebpf-scanner)** — A zero-instrumentation Linux network observability tool. Uses **eBPF (kprobes)** written in C to hook into the kernel's TCP stack (`tcp_sendmsg`), tracking active connections, PIDs, and TX byte throughput in real-time.
*   🚦 **[Kubernetes Gateway API Controller](https://github.com/morcux/k8s-custom-controller)** — A custom ingress proxy implementing the modern **Gateway API** (`HTTPRoute`). Features a `controller-runtime` control plane watching `EndpointSlices`, and an embedded reverse proxy data plane with an atomic **Round-Robin load balancer** that routes traffic directly to Pod IPs.
*   📦 **[Distributed KV Storage](https://github.com/morcux/kv-storage)** — A custom, high-performance distributed key-value database written in Go. Features a from-scratch **Raft consensus** implementation (Leader Election, Log Replication, Snapshots, Read Index) and a Bitcask-style storage engine.
*   ☸️ **[KV Kubernetes Operator](https://github.com/morcux/kv-operator)** — A custom K8s Operator built with **Kubebuilder** to automate the deployment, Raft bootstrapping, and lifecycle management of the `kv-storage` cluster via CRDs and StatefulSets.
*   📈 **[Binance Market Data Ingestor](https://github.com/morcux/binance-ingestor)** — High-frequency crypto data pipeline. Streams WebSocket ticks, stores raw order books in **ClickHouse**, and calculates 1-minute OHLCV candles on-the-fly using `SummingMergeTree` & Materialized Views.
*   🛴 **[Fleet Telemetry System](https://github.com/morcux/fleet-telemetry-system)** — High-throughput IoT tracking backend. Uses a custom **26-byte binary protocol**, **NATS JetStream**, and **Uber H3** geospatial indexing to track 10k+ concurrent connections.

---

### 🚀 Technical Focus

My professional and open-source work primarily revolves around:

*   **Cloud-Native Orchestration:** Extending Kubernetes via custom Controllers, Operators (Kubebuilder), and modern routing standards (Gateway API).
*   **Linux Kernel Observability:** Writing custom eBPF programs in C, safely interacting with kernel space via BPF Maps, and building lockless IPC with Go user-space daemons.
*   **Distributed Systems:** Implementing consensus algorithms (Raft), handling split-brain scenarios, and ensuring linearizability.
*   **High-Frequency Processing:** Building zero-allocation Go pipelines, custom network proxies, and real-time event streaming (NATS JetStream).
*   **Storage & OLAP:** Engineering custom storage layers (LSM/Bitcask) and optimizing real-time aggregations in ClickHouse.

---

### 🛠️ Tech Stack & Tools

<div align="center">

**Languages**  
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />

**Core Infrastructure & Observability**  
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/eBPF-ebaa4c?style=for-the-badge&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=for-the-badge&logo=nats&logoColor=white" />

**Databases & Storage**  
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />

**Specialized Knowledge**  
![Linux](https://img.shields.io/badge/Linux_Kernel-eBPF_|_kprobes_|_BPF__Maps-ebaa4c?style=flat-square)
![K8s](https://img.shields.io/badge/Orchestration-Operators_|_Gateway__API-success?style=flat-square)
![Distributed](https://img.shields.io/badge/Distributed_Systems-Raft_|_CAP_|_Linearizability-blueviolet?style=flat-square)

</div>
