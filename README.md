# Westley Yarlott

CS graduate who builds automation and test suites with AI coding agents.

QA / test automation and integration, agent-driven SDLC tooling, applied cryptography in C.

[LinkedIn](https://www.linkedin.com/in/westley-yarlott)

## Projects

### [Ouroboros Manifold](https://github.com/Westopoli/ouroboros-manifold) — a full Agile SDLC run by agent teams

Multi-era RTS (C simulation, Godot client, byte-deterministic across platforms) used as the proving ground for an agent build harness. I design the process and the gates; agents write most of the code.

- **Requirements → stories → tests.** Every story exists as failing tests before any code, in fenced paths builders cannot edit. Stories are accepted by a human, not by the agent that built them.
- **Test-first, one owner per file.** Frozen contracts (C header, pipe frames) change only as their own documented piece; two in-flight pieces never own the same file.
- **Merge gate is the only way to main.** Twenty-odd stages: build, equation/signature lints, reachability lint, three test suites, a scripted playthrough of the real client, and an `-O0` vs `-O2` checksum trace that catches any non-determinism.
- ~5,600 commits in two months; harness measured, broken, and rebuilt three times.

`Agile` · `TDD` · `CI` · `C` · `Claude Code`

### [claude-manager-mode](https://github.com/Westopoli/claude-manager-mode) — disciplined parallel-agent TDD for Claude Code

Claude Code skill pack that lets you run many sub-agents in parallel without the usual mess: blocks file collisions before agents spawn, forbids ambiguous design language in task descriptions, caps task size, reverts merges on regression, and coordinates sibling agents via file-mediated channels (shared-assumption reads, a question ledger, and contract proposals) so the cascade stays tree-shaped. Paired evals on the coordination patterns — old skill 78%, new skill 100%.

```bash
curl -fsSL https://raw.githubusercontent.com/Westopoli/claude-manager-mode/main/install.sh | bash
```

`Claude Code` · `Python` · `TDD`

### [Jarvis](https://github.com/Westopoli/jarvis) — voice interface for Claude Code sessions

Pipecat voice pipeline into tmux-hosted Claude Code sessions. Local Ollama model with automatic cloud failover, phone route with a caller allow-list, exposed over Tailscale. Spec-first: three specs built as manager-mode cascades, 46 test files.

`Python` · `Pipecat` · `TDD`

### Prosper _(private, freelance)_ — secure desktop database for an insurance agency

Searchable desktop app for sensitive client records, delivered from written requirements and a fixed-price proposal. Built test-first under a written TDD contract: 533 tests, CI for test and deploy, signed releases with a signed update channel.

`Python` · `TDD` · `CI/CD`

### ETL pipeline _(private, internship)_

PostgreSQL-backed ETL: data ingestion, transformation, scheduled refresh. Built during an ongoing internship.

`PostgreSQL` · `PL/pgSQL` · `ETL`

### [Cybersecurity Infrastructures](https://github.com/Westopoli/Cybersecurity-Infrastructures) — applied cryptography in C

Four ground-up implementations of cryptographic systems, built against OpenSSL primitives:

- **Forward-secure aggregate log auditing** — hash-chained HMAC + AES-CTR; a logger and an auditor that detect any tampering in a stream of encrypted messages.
- **Client–server proof-of-work** — SHA-256 hash puzzles for DoS mitigation; brute-force solver + leading-zero verifier.
- **ChaCha20 stream cipher with integrity check** — XOR keystream encryption between two parties, SHA-256 acknowledgment, file-based IPC.
- **Merkle hash tree** — root computation over 8 leaves + authentication-path generation for indexed verification.

`C` · `OpenSSL` · `ChaCha20` · `SHA-256` · `HMAC` · `AES-CTR`

### [Python-Projects](https://github.com/Westopoli/Python-Projects) — applied ML and adversarial search

- **Particle-labeling MLP** — PyTorch multi-layer perceptron + SVM ensemble for 2D point classification; 5-minute training budget, peaked at **95.8%** predict accuracy on held-out data.
- **Adversarial chess agent** — minimax with alpha-beta pruning under a 3-second per-move budget; custom scoring over board position and piece geometry on a modified ruleset.
- **Maze-solver agent** — search agent over grid worlds.
- **Matrix-visualization puzzle solver** — constraint-based solver with visual state tracking.

`Python` · `PyTorch` · `ML` · `Adversarial Search`
