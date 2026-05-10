agent_system/
│
├── planner/
│   ├── planner_engine.py
│   ├── reflection_engine.py
│   ├── goal_manager.py
│   └── graph_builder.py
│
├── kernel/
│   ├── runtime.py
│   ├── scheduler.py
│   ├── executor.py
│   ├── hydrator.py
│   ├── hydration_pipeline.py
│   ├── reference_manager.py
│   ├── model_router.py
│   ├── resource_manager.py
│   ├── budget_manager.py
│   ├── policy_engine.py
│   ├── action_validator.py
│   ├── session_manager.py
│   ├── task_store.py
│   ├── interrupts.py
│   ├── state_machine.py
│   ├── event_bus.py
│   └── subscribers/
│       ├── logging.py
│       ├── metrics.py
│       └── reflection.py
│
├── memory/
│   ├── reference_registry.py
│   ├── working_refs.py
│   ├── semantic_store.py
│   ├── episodic_store.py
│   ├── entity_graph.py
│   ├── reference_graph.py
│   ├── compression.py
│   ├── cache.py
│   └── index_manager.py
│
├── artifacts/
│   ├── registry.py
│   └── result_store.py
│
├── storage/
│   ├── sqlite_backend.py
│   ├── vector_backend.py
│   ├── artifact_backend.py
│   └── cache_backend.py
│
├── workers/
│   ├── reasoning_worker.py
│   ├── parser_worker.py
│   ├── retrieval_worker.py
│   └── embedding_worker.py
│
├── tools/
│   ├── mcp_client.py
│   ├── capability_registry.py
│   ├── terminal_tool.py
│   ├── crawler_tool.py
│   └── rag_tool.py
│
└── protocols/
    ├── acp.py
    ├── actions.py
    └── messages.py


    
| ---------- | -------------------- |
| Runtime    | cognition manager    |
| References | virtual memory       |
| Hydrator   | load minimal context |
| LLM        | reasoning only       |
| Workers    | execution            |
| Storage    | persistence          |
