<p align="center">
  <img src="./assets/cortext-signal.svg" alt="yw profile banner showing a local-first AI tooling signal map" width="100%" />
</p>

# ywkuno

I build local-first developer tools and AI coding workflows that make large codebases cheaper to understand, slice, and act on.

My current focus is **context saving for AI agents**: deterministic repo maps, compact context slices, token estimates, and optional visual replay for understanding what an agent touched.

<p>
  <a href="https://github.com/ywkuno/cortext"><img alt="Cortext" src="https://img.shields.io/badge/project-Cortext-111827?style=for-the-badge"></a>
  <img alt="Local first" src="https://img.shields.io/badge/local--first-tools-2563eb?style=for-the-badge">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-3776ab?style=for-the-badge&logo=python&logoColor=white">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-graph%20state-044a64?style=for-the-badge&logo=sqlite&logoColor=white">
</p>

## Featured

### [Cortext](https://github.com/ywkuno/cortext)

Local-first context saving and token optimization for AI coding agents.

```bash
contextopt map .
contextopt slice "what I am changing"
contextopt visualize
```

Cortext turns a repository into an inspectable graph before an assistant reads the whole tree. It exports Markdown, JSON, DOT, SQLite, and a static browser viewer so the context path stays visible instead of hidden inside a chat window.

## Current Tracks

- **Context engineering**: repo maps, query-first context, token estimates, focused slices
- **Visual code intelligence**: optional graph viewers, activity replay, folder-aware layouts
- **Agent tooling**: local artifacts, deterministic parsing, safe activity streams
- **Practical automation**: CLIs, GitHub Actions, Windows-friendly developer workflows

## Stack I Reach For

```text
Python      SQLite      GitHub Actions
TypeScript  JavaScript  HTML/SVG
PowerShell  Git         Local-first tooling
```

## Operating Principles

- Map first, then read.
- Keep useful artifacts inspectable.
- Prefer deterministic parsing before heavy magic.
- Measure before making token-saving claims.
- Build tools that stay useful when the network is off.

## Public Work

- [Cortext](https://github.com/ywkuno/cortext) — codebase map, context pack, and visual agent replay

