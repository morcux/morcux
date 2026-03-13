<div align="center">
  <h1>Hi there, I'm Dmytro Melnyk! 👋</h1>
  <h3>Backend Systems Engineer | Distributed Systems | Infrastructure</h3>
  
  <p>
    Building resilient, high-throughput distributed systems and custom storage engines. <br>
    Passionate about <b>Go internals, Consensus Protocols (Raft), and Cloud-Native orchestration</b>.
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

I spend my free time building infrastructure tooling and high-load data pipelines from scratch:

*   📦 **[Distributed KV Storage](https://github.com/morcux/kv-storage)** — A custom, high-performance distributed key-value database written in Go. Features a from-scratch **Raft consensus** implementation (Leader Election, Log Replication, Snapshots, Read Index) and a Bitcask-style storage engine.
*   ☸️ **[KV Kubernetes Operator](https://github.com/morcux/kv-operator)** — A custom K8s Operator built with **Kubebuilder** to automate the deployment, Raft bootstrapping, and lifecycle management of the `kv-storage` cluster via CRDs and StatefulSets.
*   📈 **[Binance Market Data Ingestor](https://github.com/morcux/binance-ingestor)** — High-frequency crypto data pipeline. Streams WebSocket ticks, stores raw order books in **ClickHouse**, and calculates 1-minute OHLCV candles on-the-fly using `SummingMergeTree` & Materialized Views.
*   🛴 **[Fleet Telemetry System](https://github.com/morcux/fleet-telemetry-system)** — High-throughput IoT tracking backend. Uses a custom **26-byte binary protocol**, **NATS JetStream**, and **Uber H3** geospatial indexing to track 10k+ concurrent connections.
*   🎥 **[Stream Relay](https://github.com/morcux/stream-relay)** — A custom WebRTC Selective Forwarding Unit (SFU) written in Go using **Pion**, featuring low-level RTP/RTCP packet handling for scalable video routing.

---

### 🚀 Technical Focus

My professional and open-source work primarily revolves around:

*   **Distributed Systems:** Implementing consensus algorithms (Raft), handling split-brain scenarios, and ensuring linearizability.
*   **High-Frequency Processing:** Building zero-allocation Go pipelines, custom binary protocols, and real-time event streaming (NATS JetStream).
*   **Storage & OLAP:** Engineering custom storage layers (LSM/Bitcask) and optimizing real-time aggregations in ClickHouse.
*   **Cloud-Native Orchestration:** Extending Kubernetes API via custom Controllers and Operators.

---

### 🛠️ Tech Stack & Tools

<div align="center">

**Languages**  
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />

**Core Infrastructure & Messaging**  
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=for-the-badge&logo=nats&logoColor=white" />
<img src="https://img.shields.io/badge/gRPC-144D75?style=for-the-badge&logo=grpc&logoColor=white" />

**Databases & Storage**  
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />

**Specialized Knowledge**  
![Distributed](https://img.shields.io/badge/Distributed_Systems-Raft_|_CAP_|_Linearizability-blueviolet?style=flat-square)
![K8s](https://img.shields.io/badge/Orchestration-K8s_Operators_|_CRDs-success?style=flat-square)
![Engines](https://img.shields.io/badge/Storage_Engines-Bitcask_|_LSM--Trees-black?style=flat-square)

</div>

<br>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=morcux&show_icons=true&theme=transparent&hide_border=true" alt="GitHub Stats" />
</div>
