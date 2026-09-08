# M-T-D-N

**Local-first tools for AI coding agents on Windows.**

Windows에서 AI 코딩 에이전트와 함께 쓰는 도구와 작업 방식을 만들고 공유합니다.

[AgentMemory](#agentmemory-for-codex-on-windows) · [Workflow skills](#codex-workflow-skills) · [Translation experiment](#koharu-hyqwen-pipeline)

[![AgentMemory for Codex on Windows](https://raw.githubusercontent.com/M-T-D-N/agentmemory-codex-windows/main/assets/social-preview.png)](https://github.com/M-T-D-N/agentmemory-codex-windows)

## Projects

### AgentMemory for Codex on Windows

An independent Windows-native AgentMemory downstream for OpenAI Codex Desktop and Codex CLI.

- Managed lifecycle hooks for Codex Desktop and CLI
- Exact-project memory writes
- Source-labelled federated recall
- Optional loopback-only local graph extraction
- Source-only public preview for Windows 11

[Explore the repository](https://github.com/M-T-D-N/agentmemory-codex-windows) · [Release](https://github.com/M-T-D-N/agentmemory-codex-windows/releases/tag/v0.1.0-preview.1) · [한국어](https://github.com/M-T-D-N/agentmemory-codex-windows/blob/main/READMEs/README.ko-KR.md) · [日本語](https://github.com/M-T-D-N/agentmemory-codex-windows/blob/main/READMEs/README.ja-JP.md)

### Codex Workflow Skills

Nine independently installable skills for grounded changes, evidence-driven debugging, lean execution, bounded delegation, critical review, task handoff, and visual prompt reconstruction.

필요한 스킬만 골라 설치할 수 있습니다. <code>swarm</code>은 로컬 작업자 우선 판단, 준비 완료 후 재라우팅, 작업 결과 검증과 소유 서비스 정리를 다룹니다.

[Browse the skills](https://github.com/M-T-D-N/codex-workflow-skills) · [Installation](https://github.com/M-T-D-N/codex-workflow-skills#설치) · [Swarm](https://github.com/M-T-D-N/codex-workflow-skills/blob/main/skills/swarm/SKILL.md)

### Koharu HY–Qwen Pipeline

An independent Japanese-to-Korean manga translation experiment, with a pinned headless API/MCP patch for Koharu. This is an experimental project, separate from upstream Koharu.

[Explore the experiment](https://github.com/M-T-D-N/koharu-hy-qwen-pipeline) · [Upstream Koharu](https://github.com/koharu-rs/koharu)

## Why I build these tools

Native Windows users should be able to operate persistent agent memory with explicit project boundaries, visible provenance, and a managed Codex workflow. The workflow skills share practical ways to carry that work from a clear request through implementation and verification.

## Scope and validation

For AgentMemory, most downstream changes were generated and revised with OpenAI Codex from my requirements. I tested the supported Windows/Codex workflow, but I have not manually reviewed every source file and no independent audit has been performed. Detailed validation evidence, limitations, and upstream attribution are documented in the repository.

Each project's README describes its own scope, AI assistance, and validation limits.
