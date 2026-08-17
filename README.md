# Hi, I'm Jiangyi Zhou (Ryan)

I work at the intersection of AI systems, efficient vision models, agentic systems,
and edge/distributed computing.

My current work spans lightweight Vision Transformer research, algorithm-evaluation
infrastructure, safety-aware reliability agents, and reproducible optimization systems.

## Research Interests

- Efficient Vision Models and Model Compression
- AI Systems and Distributed Execution
- Agentic AI
- Edge and Distributed Intelligence
- Reproducible Machine Learning Research

## Research & Ongoing Work

### Efficient Vision Models

**Status: Ongoing research**

I am studying lightweight and hierarchical vision models through vHeat and Vision
Transformer reproduction and analysis. Current work covers reproducible ImageNet
validation, component- and stage-wise parameter/FLOP analysis, stage-aware FFN
reduction, and surrogate-guided study of accuracy-efficiency trade-offs with frozen
holdout evaluation.

### [MEC Optimization](https://github.com/Ryan-Yii/mec-rdho-offloading)

**Status: Established research artefact**

A manuscript-oriented reproducibility package for capacity-feasible MEC task
offloading, execution-node selection, and physical CPU allocation. It includes
configuration-driven paired experiments across multiple baselines, controlled
comparisons, ablations, sensitivity studies, statistical analysis, and raw evidence.

### Agentic AI / AutoSRE

**Status: Ongoing project**

A safety-aware agentic workflow for diagnosing, planning, executing, verifying, and
rolling back remediation actions in cloud-native systems. The project is being
designed around reproducible fault scenarios and measurable diagnosis, recovery,
MTTR, and safe-action outcomes.

## Systems & Engineering

### Algorithm Evaluation Platform — Industry Engineering Experience

Worked on a full-stack algorithm evaluation platform spanning FastAPI backend
services, React/Vite frontend workflows, Kubernetes/Pod-based execution, and
frontend-backend integration.

- Built and debugged run-management, structured-evaluator, correctness/quality-metric,
  artifact-discovery, and result-visualization workflows.
- Contributed to testing, CI, GitHub-integrated development, and iterative platform
  engineering across the evaluation lifecycle.

### [Distributed Task Scheduler](https://github.com/Ryan-Yii/mec-distributed-task-scheduler)

**Status: Open-source software**

A public Redis-backed distributed-execution foundation with a FastAPI control plane,
concurrent workers, atomic claiming, lifecycle controls, leases, retries, timeouts,
cancellation, heartbeats, observability, tests, and containerized deployment. Its
current `main` provides the systems foundation and does not claim completed formal
policy-performance conclusions.

## Open-Source Research Software

### [ReproAudit](https://github.com/Ryan-Yii/reproaudit)

**Status: Open-source research software**

A deterministic auditing tool for checking consistency across experiment
configurations, raw runs, summaries, and reported research claims, with structured
reports and CI-oriented validation.

### Supporting Open-Source Work

- **[MEC Offloading Visualizer](https://github.com/Ryan-Yii/mec-offloading-visualizer)**
  — a deterministic simulator for local, edge, and cloud baseline analysis.
- **[Supervised ML Foundations](https://github.com/Ryan-Yii/supervised-ml-foundations)**
  — reproducible supervised-learning and IoT predictive-maintenance learning and
  engineering practice.

## Current Research Direction

- Efficient Vision Transformer and vHeat architecture research
- Model compression and surrogate-guided architecture search
- Agentic systems with measurable safety, diagnosis, and recovery behavior
- Reproducible AI-systems experimentation and research auditing
- Edge and distributed intelligence where it supports these research questions

## Technical Stack

**ML / Research:** PyTorch, scikit-learn, model evaluation, optimization, statistical analysis

**AI Systems:** FastAPI, Redis, Docker, Kubernetes, REST APIs

**Frontend / Platform:** React, Vite, visualization and evaluation interfaces

**Engineering:** Python, Git/GitHub, CI, testing, reproducible experiment pipelines

## Contact

[ryan.zhoujiangyi@gmail.com](mailto:ryan.zhoujiangyi@gmail.com)
