# Westley Yarlott

CS student + STEM instructor, building AI agent tooling and developer infrastructure.

Python, C. Open-source Claude Code skills, cybersecurity infrastructures at USF.

[LinkedIn](https://www.linkedin.com/in/westley-yarlott)

## Projects

### [claude-swarm](https://github.com/Westopoli/claude-swarm) — disciplined parallel-agent TDD for Claude Code

Claude Code skill pack that lets you run many sub-agents in parallel without the usual mess: blocks file collisions before agents spawn, forbids ambiguous design language in task descriptions, caps task size, and reverts merges on regression. Six paired evals — baseline scores 12.5%, skill scores 100%.

```bash
curl -fsSL https://raw.githubusercontent.com/Westopoli/claude-swarm/main/install.sh | bash
```

`Claude Code` · `Python` · `TDD`

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
