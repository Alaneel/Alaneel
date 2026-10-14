<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alaneel/Alaneel/main/assets/profile-hero-dark-compact.svg">
  <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Alaneel/Alaneel/main/assets/profile-hero-light-compact.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alaneel/Alaneel/main/assets/profile-hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Alaneel/Alaneel/main/assets/profile-hero-light.svg">
  <img alt="Alan Wang — Backend and distributed systems. Correctness, recovery, and reproducible evidence." src="https://raw.githubusercontent.com/Alaneel/Alaneel/main/assets/profile-hero-light.svg" width="100%">
</picture>

Computer Science graduate from **Nanyang Technological University**, Singapore. I build backend and distributed systems, exploring how they behave under retries, failures, and recovery, with a growing focus on applied AI.

[LinkedIn](https://www.linkedin.com/in/yangming-wang/) · [Email](mailto:WANG1859@e.ntu.edu.sg) · [LeetCode](https://leetcode.com/Alaneel/)

## Selected work

| Project | Engineering focus |
| :--- | :--- |
| **[Redis Reliability Lab](https://github.com/Alaneel/redis-reliability-lab)**<br>Go · Redis Cluster · Docker | Reproducible fault injection, failover, and persistence experiments. Measures service recovery separately from acknowledged-write survival, with inspectable reports and explicit limitations.<br>[Experiments & evidence](https://github.com/Alaneel/redis-reliability-lab#what-the-experiments-expose) |
| **[Video Toolkit](https://github.com/Alaneel/video-toolkit)**<br>Rust · egui · FFmpeg | A desktop app and CLI for local media workflows, with reusable profiles and parallel batch processing. Integration tests inspect actual media outputs.<br>[Download & release notes](https://github.com/Alaneel/video-toolkit/releases/tag/v2.1.0) |

**Also in development:** Transaction Processing Platform — Java, PostgreSQL, and Kafka with a double-entry ledger and reliable event processing; **OpsPilot** — durable incident workflows with evidence, approvals, and recovery checks. Both are being prepared for public release.

## Engineering approach

- **Correctness first.** Define invariants and make committed state inspectable.
- **Failure is part of the design.** Account for retries, partial completion, and recovery.
- **Evidence beside claims.** Keep methods, source data, and limitations next to results.

## Toolkit

| Area | Tools I use |
| :--- | :--- |
| Backend & data | Java · Go · Python · SQL · PostgreSQL · Redis · Kafka |
| Applications & AI | TypeScript · Rust · LangGraph · retrieval · workflow evaluation |
| Platform & delivery | Docker · Kubernetes · Linux · GitHub Actions · Prometheus · Grafana |

**Recognition:** 1st Place — Bank of America Code to Connect 2024 · Gold Award — WorldQuant Challenge.

<!-- Publication candidate, 2026-10-14. Publish all four native SVG assets together
     with this README. TPP and OpsPilot deliberately have no repository links
     until their public release is approved and verified. -->
