# Nao Segawa — Portfolio

Senior Data Engineer with 7 years building production data pipelines across insurance, logistics, and e-commerce. Currently running [sono studio](https://sonostud.io), an independent engineering studio focused on edge AI, computer vision, and LLM-powered systems.

Open to full-time remote roles globally · n@sonostud.io · [LinkedIn](https://linkedin.com/in/naosegawa)

---

## Skills

| Area | Technologies |
|---|---|
| **Core** | Python, SQL, PySpark |
| **Cloud & Data** | AWS (primary), Databricks, dbt, AutomateDV, Google BigQuery, Azure Synapse, Data Factory |
| **CV & ML** | YOLOv8 / Roboflow, OAK-D / DepthAI, OpenCV, MediaPipe, PyTorch |
| **Tooling** | Docker, Terraform, Git, Poetry |
| **Visualization** | Tableau, Looker, PowerBI, QuickSight |

---

## Projects

### [AI-Powered Conversational Product Guide](https://github.com/sonostudio/llm-product-guide)
LLM-driven product recommendation system configurable across multiple retail brands — FastAPI backend, Claude API, and React frontend. Analytics pipeline following the Medallion architecture (AWS S3 → Delta Lake → Databricks) designed and planned for production implementation.
 
**Stack:** Python · FastAPI · Claude API · React

---

### [Real-Time Dish & Glass Detection](https://github.com/sonostudio/dish-detection) (client work)
Computer vision system for a restaurant client detecting dish and glass presence across multiple tables in real time, triggering interactive content via OSC. Dual-detection architecture: depth-based presence detection for dishes, on-device YOLOv8n inference (MyriadX VPU) for glasses.

**Stack:** Python · OAK-D Lite · YOLOv8n · DepthAI · Raspberry Pi 5 · TouchDesigner · OSC

---

### [Edge AI Product Detection & Display System](https://github.com/sonostudio/connected-shelf)
Retail edge AI system that detects physical product placement via OAK-D Pro and triggers SKU-specific video content. On-device YOLOv8n inference on MyriadX VPU; YAML-based SKU-to-video config requires no code changes to add new products.

**Stack:** Python · OAK-D Pro · YOLOv8n · DepthAI · Roboflow · Raspberry Pi 5

---

### [Camera-Driven Interactive 3D Rendering](https://github.com/sonostudio/shy-light)
Real-time camera-to-OSC bridge that translates human proximity, facial expression, and gesture into structured events for Unreal Engine — driving dynamic interactive 3D lighting. Modular detector pipeline with debounced state management.

**Stack:** Python · MediaPipe · DeepFace · OpenCV · python-osc · Unreal Engine

---

## Background

| Company | Role | Period |
|---|---|---|
| Sono Studio | Data & Systems Engineer | Dec 2025 – Present |
| AXA Japan | Lead Data Engineer | Jan 2024 – Oct 2025 |
| Dyson Japan | Data Engineer & Analyst | Aug 2022 – Dec 2023 |
| Yamato Transport | Data Engineer & Analyst | Dec 2020 – Jul 2022 |
| Rosso | Python Developer | May 2019 – Dec 2020 |

---

n@sonostud.io · [sonostud.io](https://sonostud.io)