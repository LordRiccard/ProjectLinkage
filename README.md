# ProjectLinkage
### Overview
Project based around the DATASUS databases SINASC and SIM
Focused around finding correlations between both
### Objectives
- Creating a set of files for each database for future use
- Matching data between both to create a new database
### Workflow
```mermaid
flowchart LR
    A[Errors] --> B[Filter]
    B --> C[Aggregation]
    C --> D[Type]
    D --> E[Final Aggregation]
```