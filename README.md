### Kevin Toles

I build AI platforms for teams whose code is increasingly written by AI agents, and the quality gates that make that code trustworthy: grounded retrieval, deterministic validation, and evals that measure whether a change actually helped.

My own platform is written largely by coding agents. These repositories show how I keep their work honest.

| Repository | What it shows |
|---|---|
| [callgraph-accuracy](https://github.com/kevin-toles/callgraph-accuracy) | The accuracy program for the call-graph builder agents use to judge change impact: every one of 80 untouched repositories across 20 languages at ≥98% precision under blind review, plus frozen-baseline gates, determinism checks and a 339-case golden corpus |
| [etdi-decision-evals](https://github.com/kevin-toles/etdi-decision-evals) | Small experiments that settled design questions on real data: an embedding-model bake-off, a pre-load gate tested by fault injection, a golden set grounded in human-vetted answers, and a code-vs-prose detector |
| [claude-code-agent-kit](https://github.com/kevin-toles/claude-code-agent-kit) | The rules my coding agents work under (design-line anchoring, no fabricated values), blind grader agents for building eval sets, and platform-grounded skills |
| [mcp-gateway](https://github.com/kevin-toles/mcp-gateway) | The MCP gateway that exposes 79 platform tools to coding agents, with auth, rate limiting, injection guards and on-demand service lifecycle |
| [llm-gateway](https://github.com/kevin-toles/llm-gateway) | An OpenAI-compatible gateway with multi-provider routing, fallback and circuit breaking |

Languages I work in day to day: Python, Rust, Go, C++, TypeScript.
