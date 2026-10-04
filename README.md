# Taha Ahmed

**Cloud, Data & AI Platform Engineering**

My foundation is in data and cloud engineering. I'm increasingly working at the
intersection of data platforms and AI infrastructure, with the same questions in mind:
who owns state, what happens when a dependency fails, and how does the next engineer
operate the system?

I work with Python, Azure and Kubernetes/AKS, alongside data platforms, CI/CD,
infrastructure automation and observability. These projects are a way to examine
specific design decisions in code and make their trade-offs visible.

## Selected projects

### [AI Platform Control Plane](https://github.com/tahahmedk/ai-platform-control-plane)

An inference platform needs a place to enforce routing policy and capacity limits.
This FastAPI implementation puts admission and fallback behind a narrow provider
interface. I kept the providers synthetic so the interesting failure paths can be
tested without paid services.

### [Forward-Deployed Data Accelerator](https://github.com/tahahmedk/forward-deployed-data-accelerator)

An unfamiliar customer extract is as much a discovery problem as a data problem.
This toolkit profiles the source, exposes uncertain mappings and separates trusted
records from quarantine. The diagnostic handoff matters as much as the output file.

### [Metadata Lakehouse Orchestrator](https://github.com/tahahmedk/metadata-lakehouse-orchestrator)

A study of execution ownership and recovery: dependency scheduling, durable claims,
replay and atomic checkpoint commits. The design makes the gap between recorded
success and exactly-once external effects explicit.

I prefer designs whose failure behavior I can explain and test. The READMEs and ADRs
describe the choices I made, where they stop being sufficient, and what I would change next.

[LinkedIn](https://www.linkedin.com/in/tahaahmedk/)

## About the public projects

The public projects on this profile are independent clean-room implementations built with synthetic data and generic architecture patterns. They do not contain employer source code, internal datasets, proprietary configuration, copied architecture, or confidential work artifacts.
