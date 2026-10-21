<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,50:2563eb,100:7c3aed&height=180&section=header&text=yw%20%C2%B7%20ywkuno&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=indie%20solo%20dev%20%C2%B7%20Australia%20%C2%B7%20cat%20lover&descSize=18&descAlignY=58" width="100%" alt="banner" />

I build **local-first AI developer tools**, **game-streaming infrastructure**, **game mods**, and
**reverse-engineering research tooling**, shipped under [**Kuno Labs**](https://github.com/kunolabs) and here.
Most of my work is private while it is being built; the public pieces below are the ones that have real users.

<p>
  <a href="https://github.com/kunolabs/yukistreams-addon"><img alt="YukiStreams" src="https://img.shields.io/badge/project-YukiStreams-db2777?style=for-the-badge"></a>
  <a href="https://github.com/kunolabs/codeprism"><img alt="CodePrism" src="https://img.shields.io/badge/project-CodePrism-111827?style=for-the-badge"></a>
  <a href="https://github.com/kunolabs/Nimbus"><img alt="Nimbus" src="https://img.shields.io/badge/project-Nimbus-2563eb?style=for-the-badge"></a>
  <a href="https://github.com/ywkuno/godot-mcp-agents"><img alt="Godot MCP Agents" src="https://img.shields.io/badge/project-Godot%20MCP%20Agents-478CBF?style=for-the-badge"></a>
  <img alt="Local first" src="https://img.shields.io/badge/local--first-developer%20tools-16a34a?style=for-the-badge">
  <img alt="AI tools" src="https://img.shields.io/badge/AI%20tools-code%20agents-7c3aed?style=for-the-badge">
  <a href="https://ko-fi.com/kunolabs"><img alt="Ko-fi" src="https://img.shields.io/badge/support-ko--fi-ff5e5b?style=for-the-badge"></a>
</p>

## Featured

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kunolabs/yukistreams-addon">🌸 YukiStreams</a></h3>
      <p>Stremio addon for anime, Asian drama, movies, and series, with optional Real-Debrid and TorBox
      support. The most-used thing I ship: a public instance, real users, real uptime expectations.</p>
      <p><a href="https://stremio.yukistreams.xyz/configure">stremio.yukistreams.xyz</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kunolabs/codeprism">🔍 CodePrism</a></h3>
      <p>Local-first context for AI coding agents: <em>map first, slice next, retrieve exactly.</em> Turns a
      repository into an inspectable graph before an assistant reads the whole tree; exports Markdown, JSON,
      DOT, SQLite, and a static browser viewer. Ships Claude Code hooks and a skill.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kunolabs/Nimbus">☁️ Nimbus</a></h3>
      <p>Community-maintained game-streaming <strong>host</strong> fork in the Vibepollo → Apollo → Sunshine
      lineage. Virtual display reliability, Windows capture behaviour, frame pacing, Android TV compatibility,
      and honest release hygiene, for people who actually stream from a gaming PC.</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ywkuno/godot-mcp-agents">🎮 Godot MCP Agents</a></h3>
      <p>An MCP server that gives Claude Code and other agents control of Godot 4.x: 158 tools across headless
      scene operations, runtime introspection, gameplay debugging and a live TCP bridge, with
      <strong>tier-aware tool budgets</strong> (<code>full</code> / <code>lite</code> / <code>minimal</code>)
      so the surface fits any client's tool limit.</p>
    </td>
  </tr>
</table>

```bash
# CodePrism in three lines
codeprism prime "what I am changing" --changed
codeprism query "where does this behavior live?"
codeprism visualize
```

## In the Lab (private while it is being built)

- 🔱 **Trinity**: a supervisor-to-worker delegation runtime. Frontier orchestrators (Claude Code, Codex) hand
  bounded tasks to persistent DeepSeek workers over MCP/ACP, inside Windows AppContainer sandboxes, with host
  receipts and gated evidence instead of worker claims.
- 📱 **DSH Remote**: phone remote control for DeepSeek Harness sessions over Tailscale.
- 🧪 **Reverse-engineering research**: GraalVM native-image symbol recovery, packet-structure scoping, and game
  preservation tooling, kept private and read-only by design.

## Also on the Bench

- 🛠️ [baro-hud-vitals](https://github.com/ywkuno/baro-hud-vitals): Barotrauma crew vitals HUD (LuaCs, Workshop).
- 🤖 [baro-crew-tweaks](https://github.com/ywkuno/baro-crew-tweaks): Barotrauma bot behaviour fixes, published as *Smarter Bot AI - Patched2K*.
- 🔫 [rangecrafting](https://github.com/ywkuno/rangecrafting): 7 Days to Die crafting-only linked inventory (C# ModAPI).
- 🐢 [node](https://github.com/ywkuno/node): Node.js fork carrying libuv 1.53 / AppContainer pipe research branches.
- 🕹️ Godot prototypes and cozy games, driven by the MCP server above.

## What I Am Building Toward

- Local-first AI tooling that works before it talks to the network.
- Codebase maps, slices, receipts and replay artifacts that make agent work inspectable.
- Streaming projects with honest release notes and reproducible builds.
- Desktop tools that are practical for non-technical users.
- Game and mod utilities that favour readability, stability, and fast iteration.

## Stack I Reach For

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,ts,js,nodejs,react,nextjs,html,css,sqlite,git,github,githubactions,powershell,bash,docker,linux,cpp,cmake,rust,java,cs,kotlin,lua,vue,tailwind,threejs,tauri,godot&perline=10" alt="Python, TypeScript, JavaScript, Node.js, React, Next.js, HTML, CSS, SQLite, Git, GitHub, GitHub Actions, PowerShell, Bash, Docker, Linux, C++, CMake, Rust, Java, C#, Kotlin, Lua, Vue, Tailwind CSS, Three.js, Tauri, and Godot" />
  </a>
</p>

## Operating Principles

> Map first, then read.<br>
> Keep useful artifacts inspectable.<br>
> Prefer deterministic parsing before heavy magic.<br>
> Measure before making performance or token-saving claims.<br>
> Worker claims are not evidence; receipts are.<br>
> Make public maintenance boring, transparent, and repeatable.<br>
> Build tools that stay useful when the network is off.

## Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-rainbow.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-gitblock.svg" />
    <img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D GitHub contribution graph" width="100%" />
  </picture>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ywkuno&theme=github_dark" alt="GitHub profile summary" width="100%" />
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ywkuno&theme=github_dark" alt="GitHub stats" width="49%" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ywkuno&theme=github_dark&utcOffset=10" alt="Commit time of day" width="49%" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:2563eb,100:0f766e&height=100&section=footer" width="100%" alt="footer" />
