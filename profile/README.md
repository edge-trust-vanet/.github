<div align="center">
  <h1>EdgeTrust-VANET</h1>
  <p><b>An Edge-based Trust Management and Machine Learning Framework for Secure Vehicular Ad Hoc Networks (VANETs)</b></p>
</div>

---

## About the Initiative

EdgeTrust-VANET is a dedicated research and development initiative focused on securing Vehicular Ad Hoc Networks (VANETs). 
While traditional Public Key Infrastructure (PKI) effectively authenticates vehicles, it is inherently limited in determining whether an authenticated node behaves maliciously after joining the network. To address this critical security gap, **EdgeTrust-VANET** integrates **behavioral trust management** with **machine learning-based attack detection** at the network edge.

## Mission & Objectives

- **Develop a trust-based behavior evaluation model** for vehicular nodes to continuously assess reliability.
- **Train robust machine learning models** for precise, real-time attack detection.
- **Deploy ML inference at Roadside Units (RSUs)** to substantially minimize detection latency.
- **Fuse trust and ML decisions** to lower false positive rates and enhance overall detection accuracy.
- **Provide a highly scalable architecture** suited for next-generation Intelligent Transportation Systems (ITS).

## Architecture Overview

Our system architecture spans across four primary layers to ensure rapid and accurate threat mitigation:
1. **Vehicle Layer**: Responsible for generating beacons, safety messages, and mobility updates.
2. **Edge Layer (RSUs)**: Computes trust scores, extracts communication features, executes ML inference, and performs decision fusion.
3. **Fog Layer**: Handles regional trust synchronization and coordinates inter-RSU communications.
4. **Cloud Layer**: Manages large-scale dataset storage, model retraining, and comprehensive analytics.

## Simulation & Technology Stack

We utilize a robust and standardized simulation environment to model and evaluate our framework:

| Component | Technology |
|-----------|------------|
| **Traffic Simulator** | SUMO |
| **Network Simulator** | OMNeT++ |
| **VANET Framework** | Veins |
| **Machine Learning** | Python, Scikit-learn |

## Repositories Overview

- **[edgetrust-core](https://github.com/edge-trust-vanet/edgetrust-core)**: Contains core simulations, trust score computation algorithms, and networking models.
- **[edgetrust-ml](https://github.com/edge-trust-vanet/edgetrust-ml)**: Houses the machine learning framework, feature extraction modules, and training datasets.
- **[edgetrust-web](https://github.com/edge-trust-vanet/edgetrust-web)**: Features web-based dashboards and visualizations for real-time monitoring.

## Current Progress & Future Roadmap

We have successfully completed our architecture design and fundamental mobility simulations. 
Currently, our primary efforts are concentrated on integrating SUMO with Veins, logging vehicular behavior under dynamic conditions, and training our baseline Random Forest models for RSU-side inference.

Moving forward, our roadmap includes the exploration of:
- Federated Learning for decentralized, privacy-preserving model updates.
- Blockchain-assisted mechanisms for immutable trust verification.
- Explainable AI (XAI) for transparent and interpretable decision-making.
- Integration with 5G/6G V2X communication standards.

---
<div align="center">
  <i>Securing the future of Intelligent Transportation Systems.</i>
</div>
