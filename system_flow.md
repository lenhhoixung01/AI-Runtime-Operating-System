```
User
 ↓
Goal Parser
 ↓
Planner LLM
 ↓
Action Graph + Reference Requests
 ↓
Runtime Kernel
 ├── Scheduler
 ├── Executor
 ├── Hydrator
 ├── Resource Manager
 ├── Policy Engine
 ├── Event Bus
 └── State Machine
 ↓
Reference & Memory System
 ├── Reference Registry
 ├── Semantic Index
 ├── Artifact Store
 ├── Knowledge Graph
 └── Storage Backend
 ↓
Workers & MCP Tools
 ↓
Artifact Outputs
 ↓
Reference Updates
 ↓
Reflection & Replan (conditional only)
```
##
| --------------- | ------------------ |
| LLM             | semantic reasoning |
| Runtime         | orchestration      |
| Reference Store | memory map         |
| Hydrator        | context loader     |
| Workers         | execution          |
| Artifact Store  | persistence        |
