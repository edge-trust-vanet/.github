# EdgeTrust-VANET Research Initiative

**An Edge-Intelligence and Hierarchical Trust Management Framework for Secure Connected and Autonomous Vehicles**

[![Initiative](https://img.shields.io/badge/Initiative-EdgeTrust--VANET-blue.svg)]()
[![Affiliation](https://img.shields.io/badge/Institution-Amrita%20Vishwa%20Vidyapeetham-red.svg)](https://www.amrita.edu/)
[![Department](https://img.shields.io/badge/Department-Computer%20Science%20%26%20Engineering-orange.svg)]()
[![Focus](https://img.shields.io/badge/Focus-VANET%20Security%20%26%20Edge%20AI-purple.svg)]()
[![Status](https://img.shields.io/badge/Status-Active%20Research-brightgreen.svg)]()

---

## Executive Mission

The **EdgeTrust-VANET** initiative is an academic and applied research project focused on solving life-critical security vulnerabilities in Vehicular Ad-hoc Networks (VANETs) and Cooperative Intelligent Transportation Systems (C-ITS).

Modern connected and autonomous vehicles broadcast Basic Safety Messages (BSMs) at 10 Hz over Dedicated Short-Range Communications (DSRC) and IEEE 802.11p wireless channels. While standard Public Key Infrastructure (PKI) and Elliptic Curve Digital Signatures (ECDSA) verify transmitter authenticity, they cannot assess whether the kinematic data inside the payload is truthful. A compromised insider vehicle or sensor malfunction can broadcast digitally valid signatures over completely fabricated GPS coordinates, false emergency braking alerts, or ghost Sybil identities, leading to physical collisions and traffic disruptions.

EdgeTrust-VANET addresses this fundamental semantic gap by unifying **client-side kinematic heuristic firewalls**, **sub-microsecond edge machine learning inference**, **regional fog consensus ledgers**, and **software-defined network routing**.

---

## Four-Tier System Architecture

The initiative defines and validates a four-tier decentralized intelligence hierarchy:

```
+===================================================================================+
|                                    TIER 4                                         |
|                   CENTRALIZED SOFTWARE-DEFINED NETWORKING (SDN)                  |
|  - Global Topology Graphing & Dynamic Flow Enforcement                           |
|  - Trust-Penalized Multi-Hop Dijkstra Shortest Path Routing                      |
|  - Network-Wide Isolation & Eviction of Confirmed Attackers (T < 0.40)           |
+===================================================================================+
                                         ^
                                         | Secure Optical Backhaul (OpenFlow)
                                         v
+===================================================================================+
|                                    TIER 3                                         |
|                        REGIONAL FOG COMPUTING LEDGER                             |
|  - Cross-RSU Handover Tracking & Boundary Discrepancy Resolution (|delta| > 0.20)|
|  - Observation-Weighted Beta-Bayesian Reputation Consensus                       |
|  - Deterministic Safety Overrides & Regional Vehicle Dossiers                    |
+===================================================================================+
                                         ^
                                         | Low-Latency I2I Fiber / 5G Xn Interface
                                         v
+===================================================================================+
|                                    TIER 2                                         |
|                    EDGE ROADSIDE UNIT (RSU) TRUST ENGINE                          |
|  - 14-Dimensional Spatiotemporal Feature Extraction (x in R^14)                  |
|  - Native C++ Machine Learning Inference (0.38 us LR, 5.00 us AdaBoost)          |
|  - Exponential Moving Average (EMA) Trust Update (alpha = 0.70)                  |
|  - 3-Class Priority QoS Queue & Decision Fusion (ACCEPT / WARN / QUARANTINE)     |
+===================================================================================+
                                         ^
                                         | Dedicated Short-Range Communications (DSRC)
                                         | IEEE 802.11p / 1609.4 Control Channel (CCH)
                                         v
+===================================================================================+
|                                    TIER 1                                         |
|                    ON-BOARD UNIT (OBU) KINEMATIC FIREWALL                         |
|  - Client-Side Kinematic Plausibility Checks (v <= 45 m/s, |a| <= 8 m/s^2)        |
|  - Dead Reckoning Telemetry Consistency & Heading Drift Verification              |
|  - Local Beacon Filtering (Drops 34.2% Malicious Frames Before Multi-Hop Retx)   |
+===================================================================================+
```

---

## Repository Ecosystem

The EdgeTrust-VANET codebase is modularized across three specialized repositories:

| Repository | Primary Scope | Primary Technologies | Key Deliverables |
| :--- | :--- | :--- | :--- |
| **[edgetrust-core](https://github.com/edge-trust-vanet/edgetrust-core)** | Discrete-Event Simulation & C++ Edge Engine | C++17, OMNeT++ 6.4.0, SUMO 1.20+, Veins 5.3.1 | Full 4-tier simulation runtime, native C++ ML predictors without IPC, Fog ledger, and SDN routing. |
| **[edgetrust-ml](https://github.com/edge-trust-vanet/edgetrust-ml)** | Feature Engineering & 17-Model Benchmark Suite | Python 3.8+, Scikit-Learn, LightGBM, XGBoost, CatBoost | 23,970-sample unified multi-source dataset, mathematical zero-leakage audit, 17-model benchmark, and C++ model exporter. |
| **[edgetrust-web](https://github.com/edge-trust-vanet/edgetrust-web)** | Public Web Platform & Interactive Simulator | React 18, TypeScript, Vite, Tailwind CSS, Canvas API | 60 FPS microscopic mobility simulation, interactive benchmark explorer, systematic survey of 285 papers, and engineering devlog. |

---

## Key Research Findings and Metrics

- **Overall Detection Accuracy:** **97.45%** on unified multi-source benchmark data (VeReMi 72.88%, EdgeTrust 20.86%, V-RADD 6.26%).
- **Peak F1-Score:** **97.28%** (Precision: 98.15%, Recall: 97.45%).
- **False Positive Rate Reduction:** Slashed from **12.42% down to 1.85%** (an 85.1% relative reduction) via dynamic EMA trust and dead reckoning fusion.
- **Edge Inference Latency:** **0.38 us** for native C++ Logistic Regression, **5.00 us** for Decision Trees, **329 us** for LightGBM.
- **End-to-End Decision Cycle:** **0.38 ms** on edge Roadside Units, operating well below the 100 ms vehicular safety deadline.
- **Control Channel Bandwidth Savings:** **34.2% reduction** in retransmitted malicious frames achieved via Tier 1 OBU kinematic filtering.
- **Cryptographic Data Leakage:** **0.00%** SHA-256 cross-split sample overlap under Stratified GroupKFold partitioning by vehicle identity.

---

## Research Team and Institutional Affiliation

Conducted at the **Department of Computer Science and Engineering, Amrita School of Computing, Amrita Vishwa Vidyapeetham, Coimbatore, India**:

- **Ms. Neethu M R** - *Project Guide & Assistant Professor* (`mr_neethu@cb.amrita.edu`)
- **Madisetty Mounik Sai** - *Undergraduate Researcher* (`cb.sc.u4cse23561@cb.students.amrita.edu`)
- **Edavalapati Aashiq** - *Undergraduate Researcher* (`cb.sc.u4cse23560@cb.students.amrita.edu`)
- **Chitturi Vivek Vardhan** - *Undergraduate Researcher* (`cb.sc.u4cse23360@cb.students.amrita.edu`)
- **Nishanth K** - *Undergraduate Researcher* (`cb.sc.u4cse23523@cb.students.amrita.edu`)
- **Juturu Naga Abhinava Sai** - *Undergraduate Researcher* (`cb.sc.u4cse23563@cb.students.amrita.edu`)

---

## Academic Citation

```bibtex
@inproceedings{edgetrust_vanet_2026,
  author    = {Neethu, M. R. and Mounik Sai, M. and Aashiq, E. and Vivek Vardhan, C. and Nishanth, K. and Abhinav, J.},
  title     = {EdgeTrust-VANET: A Decentralized Four-Tier Hierarchical Trust Management and Kinematic Filtering Framework for Vehicular Ad-Hoc Networks},
  booktitle = {Proceedings of the IEEE International Conference on Communications (ICC) / VTC},
  year      = {2026},
  pages     = {1--8},
  address   = {Coimbatore, India}
}
```
