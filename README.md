<p align="center">
  <img src="./assets/header.svg" alt="Dante — AI agents and inference infrastructure" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-101826?style=for-the-badge&amp;logo=python&amp;logoColor=7dd3fc" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-101826?style=for-the-badge&amp;logo=typescript&amp;logoColor=7dd3fc" alt="TypeScript" />
  <img src="https://img.shields.io/badge/AI_Agents-101826?style=for-the-badge&amp;logoColor=5eead4" alt="AI agents" />
  <img src="https://img.shields.io/badge/LLM_Serving-101826?style=for-the-badge&amp;logoColor=5eead4" alt="LLM serving" />
</p>

### Hi, I'm Dante.

Software engineer focused on **AI agents and inference infrastructure**. I'm interested in the runtime details that make agents useful: tool execution, context replay, execution budgets, and model serving.

<p align="center">
  <img src="./assets/agent-harnesses.svg" alt="Agent harnesses: tool calls and context replay" width="280" />
  <img src="./assets/inference-infrastructure.svg" alt="Inference infrastructure: pipeline parallelism and KV cache" width="280" />
  <img src="./assets/reliable-execution.svg" alt="Reliable execution: budgets, state, and validation" width="280" />
</p>

### Selected open-source contributions

| Project | Contribution | Pull request |
| :--- | :--- | :--- |
| **[SGLang](https://github.com/sgl-project/sglang)** | Bound startup profiling by available KV-cache capacity, including the smaller SWA pool. Reproduced the original PP startup failure on two T4 GPUs. | [![SGLang PR #51481](https://img.shields.io/github/pulls/detail/state/sgl-project/sglang/51481?style=flat-square&label=%2351481)](https://github.com/sgl-project/sglang/pull/51481) |
| **[OpenCode](https://github.com/anomalyco/opencode)** | Disambiguate reused tool-call IDs during Chat Completions and Responses replay, keeping results paired with their calls and stored history unchanged. | [![OpenCode PR #66544](https://img.shields.io/github/pulls/detail/state/anomalyco/opencode/66544?style=flat-square&label=%2366544)](https://github.com/anomalyco/opencode/pull/66544) |

### On my radar

Agent evaluation · Post-training · Agent security

---

<p align="center">
  <sub>Reproduce the problem. Understand the runtime. Verify the fix.</sub>
</p>
