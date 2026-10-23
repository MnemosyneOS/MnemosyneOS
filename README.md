# Mnemosyne OS

**Local-first AI memory for agents.** Zero third-party dependencies,
SQLite on your own disk, MIT.

We build memory infrastructure that does not need a cloud account to work
— and we build it using itself.

## Projects

| Repository | What it is |
|---|---|
| **[mnemosyne](https://github.com/MnemosyneOS/mnemosyne)** | The engine. 52 MCP tools (41 native + 11 client-compatible), Python API, REST API, CLI. Local-first, zero dependencies. |
| **[mnemosyne-bench](https://github.com/MnemosyneOS/mnemosyne-bench)** | Reproducible benchmarks for AI agent memory systems, with the scoring harness included. |

## Hosted

**[ai-memory.net](https://ai-memory.net)** — the same engine with a web
console, API keys and subscriptions. Self-hosting stays MIT and unlimited;
no feature is paywalled in the open-source build.

## Published measurements

From the benchmark harness, re-runnable against your own corpus:

| Benchmark | Mnemosyne OS | Mem0 (published) |
|---|---|---|
| LongMemEval | 96.2 | 94.4 |
| LoCoMo | 94.8 | 92.5 |
| BEAM 1M | 68.5 | 64.1 |
| BEAM 10M | 53.9 | 48.6 |

Mem0's figures are the ones Mem0 publishes at
[mem0.ai/research](https://mem0.ai/research).

## Contact

- Issues: the relevant repository's issue tracker
- Everything else: [ai-memory.net/#/contact](https://ai-memory.net/#/contact)
