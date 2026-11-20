# LLM Gateways & Routers

One API in front of many model providers — so your apps survive a provider outage, a price change or a better model shipping next week.

### [BerriAI/litellm](https://github.com/BerriAI/litellm) — ⭐ ~64k
LiteLLM is an AI gateway that lets you call 100+ LLM APIs in the OpenAI format, with cost tracking, guardrails, load balancing, fallbacks and logging built in. Run it as a proxy and your apps never hold provider keys directly.

### [omnilabs-ai/OmniRouter](https://github.com/omnilabs-ai/OmniRouter) — ⭐ ~140
OmniRouter proves model swaps before you make them: it replays samples of your own production traffic against candidate models in shadow, scores quality, cost and latency with confidence intervals, and compiles accepted recommendations into routing policies for the gateway you already run.
Status: pre-alpha and under active construction — one to watch, not yet one to bet a production system on.

---

Know a gateway or router that belongs here? See [CONTRIBUTING.md](../CONTRIBUTING.md).
