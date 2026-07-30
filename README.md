# Westley Yarlott

CS student + STEM instructor, building AI agent tooling and developer infrastructure.

Python, C. Open-source Claude Code skills, cybersecurity infrastructures at USF.

[LinkedIn](https://www.linkedin.com/in/westley-yarlott)

## Projects

### [claude-manager-mode](https://github.com/Westopoli/claude-manager-mode) — disciplined parallel-agent TDD for Claude Code

Claude Code skill pack that lets you run many sub-agents in parallel without the usual mess: blocks file collisions before agents spawn, forbids ambiguous design language in task descriptions, caps task size, reverts merges on regression, and coordinates sibling agents via file-mediated channels (shared-assumption reads, a question ledger, and contract proposals) so the cascade stays tree-shaped. Paired evals on the coordination patterns — old skill 78%, new skill 100%.

```bash
curl -fsSL https://raw.githubusercontent.com/Westopoli/claude-manager-mode/main/install.sh | bash
```

`Claude Code` · `Python` · `TDD`

### [claude-investigate](https://github.com/Westopoli/claude-investigate) — evidence-first bug diagnosis for Claude Code

Claude Code skill that isolates bugs without guessing. Runs one targeted isolation step per round — debug prints, log greps, boundary tests, narrow repros — until the root cause is backed by direct evidence. Outputs HYPOTHESIS / EVIDENCE / SOLUTION and stops. No fixes, no speculation.

```bash
curl -fsSL https://raw.githubusercontent.com/Westopoli/claude-investigate/main/install.sh | bash
```

`Claude Code` · `Debugging`

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
