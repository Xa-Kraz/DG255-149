```mermaid
sequenceDiagram
participant PO as Producer
participant Team as Dev Team
participant QA
PO->>Team: Sprint Planning
loop Sprint (2 weeks)
Team->>Team: Daily Work
Team->>QA: Build for Testing
QA-->>Team: Bug Report
end
Team->>PO: Sprint Review
PO->>Team: Retrospective
```
