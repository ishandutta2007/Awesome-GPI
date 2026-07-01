# Decentralized Real-World Fleet Exploration

## Concept Diagram

```mermaid
flowchart TD
    Robot1[Robot 1] --> Server[Global Server]
    Robot2[Robot 2] --> Server
    Server -->|Sync Policy| Robot1
    Server -->|Sync Policy| Robot2
```

## Detailed Information

Decentralized Real-World Fleet Exploration operates via continuous online calibration. Dozens of autonomous physical machines run localized exploration loops concurrently, uploading their error metrics, grip slippages, and mechanical trajectory failures to a global server.

---
[Back to main README](../README.md)
