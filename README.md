# David Grace

> *"I cannot guarantee a win — but I can engineer systems that make failure mathematically expensive, bounded, and observable."*

| | |
|:---|:---|
| **Role** | Chief Engineer · [Graceman](https://github.com/gracemann365) |
| **Academic** | MSc Candidate, Research in Computer & Systems Engineering · [Technische Universität Ilmenau](https://www.tu-ilmenau.de/en/) |


---

## Research Orientation

Graceman is a research engineering organisation operating at the intersection of **autonomous systems**, **adversarial AI**, and **high-assurance machine intelligence**. The long-term thesis is the construction of AI systems whose failure modes are formally bounded — not probabilistically hoped away.

The current phase is directed skill acquisition and empirical validation across two high-consequence application domains where the cost of AI failure is structurally intolerable:

| # | Domain | Core Thesis |
|:---|:---|:---|
| **01** | **Autonomous Systems & Defense Applications** | Adversarial and contested environments impose verification requirements that consumer AI ignores entirely. Reliable autonomy under denied, degraded, and operationally constrained conditions is an open engineering problem. |
| **02** | **AI-Driven Quantitative Modelling & Trading** | Financial systems punish distributional shift and model overconfidence at speed. Building robust statistical and learned models for dynamic market regimes is both commercially viable and technically instructive. |

Both domains converge on the same deep problem: **what does it mean for an AI system to behave correctly when the environment is actively hostile?** That question is the research north star.

---

## Engineering Portfolio

---

### Pillar I — Autonomous Systems & Defense Applications

*Primary research and commercial direction. All infrastructure domains serve this pillar.*

| Cluster | Subjects | Strategic Rationale |
|:---|:---|:---|
| **Computer Vision** | Object detection (YOLO-family), multi-object tracking, semantic segmentation, scene understanding | Foundation for perception stacks in ISR, drone, and surveillance systems |
| **Edge AI & Embedded Inference** | TensorRT, ONNX Runtime, OpenVINO, NVIDIA Jetson ecosystem, INT8/FP16 quantisation | Field-deployed AI cannot assume cloud connectivity or unlimited power budget |
| **Robotics & Autonomous Systems** | ROS2, SLAM, path planning (A\*, RRT, D\*), sensor fusion, localisation | Ground robotics and drone autonomy — the primary application layer |
| **Signal Processing & Electronic Warfare** | DSP fundamentals, radar signal processing, EW principles, FFT, adaptive filtering | Surveillance systems and contested-spectrum operational context |
| **Hardware & Embedded Systems** | FPGA fundamentals (Vivado/HLS), microcontroller programming, RTOS (FreeRTOS), PCIe/hardware interfaces | Deliberately closing the undergraduate gap — non-negotiable for this domain |
| **Systems Engineering** | Linux internals, distributed edge compute, node orchestration, IaaC, tactical network stack | Infrastructure for deployed autonomous systems at the edge |
| **Adversarial ML & Robustness** | Adversarial attack and defence, OOD detection, reliability under sensor noise and degradation | The verification problem that defines mission-critical AI |
| **Secure & Resilient Communications** | Mesh networking, tactical comms protocols, applied cryptography, secure enclaves | Operations in denied or contested communication environments |
| **HPC & Low-Latency Inference** | CUDA programming, kernel optimisation, latency profiling, memory bandwidth management | Real-time decision systems operating under hard latency budgets |

---

### Pillar II — AI-Driven Quantitative Modelling & Trading

*Parallel commercial direction. Shares mathematical foundations with Pillar III.*

| Cluster | Subjects | Strategic Rationale |
|:---|:---|:---|
| **Financial Mathematics** | Stochastic calculus (Itô), Black-Scholes, interest rate models, derivatives pricing | Formal language of the domain — fluency required, not familiarity |
| **Time Series & Statistical Modelling** | ARIMA/GARCH, Kalman filtering, cointegration, hidden Markov models, regime detection | Market signal extraction and structural break identification |
| **Reinforcement Learning for Finance** | Deep RL (PPO, SAC), reward shaping for PnL, multi-agent market simulation | Execution strategy optimisation and adaptive portfolio management |
| **Portfolio Optimisation** | Modern portfolio theory, convex optimisation, Black-Litterman, risk parity, factor attribution | Capital allocation and fund construction |
| **Market Microstructure** | Order book dynamics, execution cost modelling, slippage, adverse selection, HFT mechanics | Operational environment understanding — not optional for production systems |
| **Statistical Arbitrage** | Pairs trading, cross-sectional factor models, alpha generation, rigorous backtesting methodology | Core quantitative research loop |
| **Risk Modelling** | VaR, CVaR, drawdown analysis, stress testing, tail risk quantification | Non-negotiable for any institutional-grade system |
| **Quantitative Engineering Stack** | NumPy/SciPy/Pandas at depth, JAX for differentiable modelling, Zipline/Backtrader | Execution and experimentation environment |
| **Low-Latency Execution Systems** | C++ fundamentals for HFT context, FIX protocol, order routing architecture | Ceiling-raiser for latency-sensitive strategy deployment |

---

### Pillar III — RCSE Academic Track · Technische Universität Ilmenau

*Mathematical and theoretical foundation layer. Ring-fenced for depth, not breadth. Exclusive output channel: MSc research.*

| Cluster | Subjects | Strategic Rationale |
|:---|:---|:---|
| **Control Theory** | Classical control (PID, root locus), modern state-space (LQR, MPC), nonlinear systems | RCSE core — direct application to autonomous systems design |
| **Systems Theory** | Dynamical systems, Lyapunov stability, observability and controllability | Maps directly to multi-agent AI architecture and coordination problems |
| **Formal Methods & Verification** | TLA+, model checking, temporal logic, programme verification | Long-game bridge to the Deterministic AI research thesis |
| **Optimisation Theory** | Convex optimisation, integer and combinatorial programming, Lagrangian methods | Shared with Pillar II — high-leverage double acquisition |
| **Numerical Methods** | ODE/PDE solvers, numerical linear algebra, stability and convergence analysis | Underpins simulation fidelity across both operational pillars |
| **Probability & Stochastic Processes** | Measure-theoretic probability, Markov chains, SDEs, martingales | Shared theoretical foundation with Pillar II quant modelling |
| **Theoretical Computer Science** | Complexity theory, computability, algorithm analysis and lower bounds | Sharpens formal reasoning across all research activity |
| **Linear Algebra at Research Depth** | Spectral theory, tensor algebra, matrix decompositions, operator theory | The actual mathematical language of ML at research level |

---

## Domain Architecture

```
                    ┌──────────────────────────────────────┐
                    │          RCSE · TU Ilmenau           │
                    │    Mathematical & Theoretical Core   │
                    │  Control Theory  ·  Formal Methods   │
                    │  Optimisation    ·  Stochastic Sys.  │
                    └───────────────┬──────────────────────┘
                                    │ funds and formalises
               ┌────────────────────┼────────────────────────┐
               ▼                                             ▼
┌──────────────────────────┐              ┌──────────────────────────────┐
│  Autonomous Systems &    │              │  AI-Driven Quantitative      │
│  Defense Applications    │              │  Modelling & Trading         │
│                          │              │                              │
│  Vision · Edge AI        │              │  Stochastic Models           │
│  Robotics · EW · FPGA    │              │  RL Execution · Arbitrage    │
│  Adversarial ML          │              │  Risk · Microstructure       │
│  Systems Engineering     │              │  Low-Latency Execution       │
└─────────────┬────────────┘              └──────────────┬───────────────┘
              │                                          │
              └─────────────────┬────────────────────────┘
                                ▼
               ┌────────────────────────────────────┐
               │             GRACEMAN               │
               │   Foundational AI Research Lab     │
               │                                    │
               │   Long-term thesis:                │
               │   Deterministic & High-Assurance   │
               │   AI Systems — failure that is     │
               │   bounded, observable, expensive.  │
               └────────────────────────────────────┘
```

---

## Contact

| Channel | Address |
|:---|:---|
| **Email** | [gracemann365@gmail.com](mailto:gracemann365@gmail.com) |
| **GitHub Org** | [github.com/gracemann365](https://github.com/gracemann365) |
| **Personal** | [github.com/davidgracemann](https://github.com/davidgracemann) |

---

*Last Update [April 2026]*
