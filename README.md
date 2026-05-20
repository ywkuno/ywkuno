# ywkuno

I build local-first AI developer tools, open source game-streaming forks,
desktop experiments, and game/mod utilities.

My current focus is **CodePrism** and **Nimbus**: tools and systems that help
developers inspect large codebases, keep AI-assisted work grounded, and make
home game streaming more reliable for real users.

<p>
  <a href="https://github.com/kunolabs/codeprism"><img alt="CodePrism" src="https://img.shields.io/badge/project-CodePrism-111827?style=for-the-badge"></a>
  <a href="https://github.com/kunolabs/Nimbus"><img alt="Nimbus" src="https://img.shields.io/badge/project-Nimbus-2563eb?style=for-the-badge"></a>
  <img alt="Lucent" src="https://img.shields.io/badge/planned-Lucent-f59e0b?style=for-the-badge">
  <img alt="Local first" src="https://img.shields.io/badge/local--first-developer%20tools-16a34a?style=for-the-badge">
  <img alt="Game streaming" src="https://img.shields.io/badge/game%20streaming-host%20%2B%20client-0f766e?style=for-the-badge">
  <img alt="AI tools" src="https://img.shields.io/badge/AI%20tools-code%20agents-7c3aed?style=for-the-badge">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-3776ab?style=for-the-badge&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-apps-3178c6?style=for-the-badge&logo=typescript&logoColor=white">
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,ts,js,nodejs,react,nextjs,html,css,sqlite,git,github,githubactions,powershell,bash,docker,linux,cpp,cmake,java,cs,lua,vue,tailwind,threejs,tauri,godot&perline=9" alt="Python, TypeScript, JavaScript, Node.js, React, Next.js, HTML, CSS, SQLite, Git, GitHub, GitHub Actions, PowerShell, Bash, Docker, Linux, C++, CMake, Java, C#, Lua, Vue, Tailwind CSS, Three.js, Tauri, and Godot" />
  </a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-rainbow.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-gitblock.svg" />
    <img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D GitHub contribution graph" width="100%" />
  </picture>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ywkuno&theme=github_dark" alt="GitHub profile summary" width="100%" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ywkuno&theme=github_dark" alt="GitHub stats" width="49%" />
</p>

## Featured

### [CodePrism](https://github.com/kunolabs/codeprism)

Local-first context saving and token optimization for AI coding agents.

```bash
codeprism prime "what I am changing" --changed
codeprism query "where does this behavior live?"
codeprism visualize
```

CodePrism turns a repository into an inspectable graph before an assistant reads
the whole tree. It exports Markdown, JSON, DOT, SQLite, and a static browser
viewer so the context path stays visible instead of hidden inside a chat window.

### [Nimbus](https://github.com/kunolabs/Nimbus)

Community-maintained game streaming host fork based on the Vibepollo, Apollo,
and Sunshine lineage.

Nimbus is the host side of my game-streaming work: virtual display reliability,
Windows capture behavior, frame pacing, Android TV compatibility, release
hygiene, and public maintainer practices. The goal is to make the fork useful to
people who actually stream from a gaming PC to living-room and handheld clients.

### Lucent

Planned companion client track for the Artemis/Moonlight Android lineage.

Lucent is the client-side direction I want to grow after the Nimbus host
foundation is stable: Android TV polish, controller ergonomics, reliable pairing,
and clear compatibility with Nimbus, Artemis, and Moonlight where possible.

## What I Am Building Toward

- Local-first AI tooling that works before it talks to the network.
- Codebase maps, slices, and replay artifacts that make agent work inspectable.
- Game streaming forks with honest release notes and reproducible builds.
- Desktop tools that are practical for non-technical users.
- Game and mod utilities that favor readability, stability, and fast iteration.

## Stack I Reach For

```text
Python      TypeScript  JavaScript  Node.js
SQLite      GitHub Actions           PowerShell
C++         CMake       Java         C#
Lua         Godot       Vue          React
Tailwind    Three.js    Tauri        Docker
```

## Operating Principles

- Map first, then read.
- Keep useful artifacts inspectable.
- Prefer deterministic parsing before heavy magic.
- Measure before making performance or token-saving claims.
- Make public maintenance boring, transparent, and repeatable.
- Build tools that stay useful when the network is off.

## Public Work

- [CodePrism](https://github.com/kunolabs/codeprism) - codebase maps, context
  slices, and visual agent replay.
- [Nimbus](https://github.com/kunolabs/Nimbus) - game streaming host fork and
  public-maintenance effort.
