# Generative World Models for Physics Simulation

## Concept Diagram

```mermaid
flowchart LR
    State[Current State] --> WorldModel[Latent World Model]
    Action[Proposed Action] --> WorldModel
    WorldModel --> PredictedState[Predicted Future State]
```

## Detailed Information

Generative World Models use generative diffusion and flow-matching video architectures optimized to act as predictive simulators. By reading a robot's current kinetic state and proposed control inputs, the world model synthesizes a physically consistent future video rollout inside its hidden layers.

---
[Back to main README](../README.md)
