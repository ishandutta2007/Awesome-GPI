# Model Predictive Control & Trajectory Optimization

## Concept Diagram

```mermaid
flowchart LR
    State[Current State] --> Optimizer[Receding Horizon Optimizer]
    Optimizer -->|Compute Control Sequence| Physics[Physics Simulator / Plant]
    Physics -->|Observe Output State| State
```

## Detailed Information

Model Predictive Control (MPC) introduced continuous real-time optimization over short, finite future lookahead horizons. By continuously re-solving equations of motion online and reading tracking sensor updates, physical machines (such as bipedal humanoids or quadrupeds) adapted to dynamic perturbations, surface drops, and payload shifts on-the-fly.

---
[Back to main README](../README.md)
