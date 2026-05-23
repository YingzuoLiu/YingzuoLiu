# Yingzuo Liu

AI Agent / LLM Runtime Engineer focused on building reliable multi-step AI systems.

I work on:
- Agent runtime architecture: Planner / Executor / Validator
- Typed AgentState, StatePatch, reducer-based state updates
- Tool calling, workflow validation, retry, blocker propagation
- RAG pipelines, retrieval evaluation, hallucination control
- Python, FastAPI, PyTorch, HuggingFace, FAISS, Redis, Docker

## Featured Projects

### 1. Travel Agent Runtime Demo
A runnable multi-turn travel planning Agent runtime focused on state consistency, partial replanning, deterministic validation, and trace logging.

Key ideas:
- Typed AgentState with Pydantic
- StatePatch + reducer
- Partial replanning
- Validator-based hard constraint checking
- FastAPI service entrypoint
- Traceable execution

### 2. ReAct Quant Research Agent
A ReAct-style quantitative research agent with workflow planning, market data retrieval, factor computation, ranking, pipeline validation, and repair loop handling.

Key ideas:
- Planner-visible step catalog
- Workflow construction
- Runtime execution
- Required-step validation
- Idle detection and repair prompts

### 3. RAG / Retrieval Systems
Projects exploring document ingestion, embedding retrieval, reranking, answer grounding, and evaluation metrics such as Hit@K, Recall@K, MRR, and hallucination checks.

## Current Focus

I am especially interested in:
- Agent runtime / harness engineering
- Long-horizon task control
- Skill-based tool orchestration
- Evaluation-driven Agent systems
