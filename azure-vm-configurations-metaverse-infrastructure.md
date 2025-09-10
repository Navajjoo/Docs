# Azure VM Configurations / Metaverse Infrastructure

### ⚡ Azure VM Configurations for the Metaverse

Below is a comparison of different Azure Virtual Machine setups depending on the stage of the project.

| Level       | VM Type / Specs                                                                 | Use Case                                                                      | Monthly Cost (USD) |
| ----------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ------------------ |
| **Minimal** | Standard D16as v5 — 16 vCPU, 64 GB RAM (CPU only)                               | Early development, small-scale tests, low traffic                             | \~$600             |
| **Optimal** | Standard NVadsA10 v5 — 24 vCPU, 220 GB RAM, 2× NVIDIA A10 GPU (24GB VRAM each)  | Full Metaverse launch with Unity rendering, hundreds of concurrent users      | \~$2,800           |
| **Maximum** | Standard NDm A100 v4 — 32 vCPU, 256 GB RAM, 2× NVIDIA A100 GPU (40GB VRAM each) | Large-scale deployment, advanced AI simulation, thousands of concurrent users | \~$6,000–6,500     |

***

#### Notes

* **Minimal** → suitable for internal dev/testing, not for public release.
* **Optimal** → balanced choice: enough GPU power for real-time Unity rendering and live Metaverse sessions.
* **Maximum** → enterprise-grade power, required only when user traffic scales massively.

We plan to start with **Optimal setup** and scale up depending on user adoption.
