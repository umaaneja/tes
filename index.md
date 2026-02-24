AI agents are powerful, but they consume resources — compute, API calls, tokens, memory

### LLM Agent Resource Drivers

| Driver | Description | Example |
| :--- | :--- | :--- |
| **LLM Calls** | Each API call or model token usage costs money | GPT-4 calls, local GPU compute |
| **Memory / Storage** | Short-term & long-term memory storage | Vector embeddings, conversation logs |
| **Actions / External Calls** | API calls, database queries, or side-effects | Payment API, email, file upload |
| **Iteration Loops** | Number of reasoning cycles per session | Multi-step planning loops |

### Iteration Management

**Maximum Iterations:** Limit steps to avoid runaway loops.

**Adaptive Iteration:** Stop early if goal is reached.

**Escalation Trigger:** If iteration threshold exceeded, escalate to human or fallback.

### Token / Compute Budget

**Token Limit:** Max tokens per LLM call to avoid overuse

**Batching / Summarization:** Reduce repeated calls to large memory contexts

**Model Selection:** Use smaller models when possible; reserve large models for critical tasks
