<div align="center">

![Sharann Manojkumar](assets/header.svg)

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-C8A84B?style=flat-square&logoColor=0B0B0D)](https://sharann.dev)
[![Resume](https://img.shields.io/badge/RESUME-0B0B0D?style=flat-square&logo=adobeacrobatreader&logoColor=EDEAE2)](https://sharann.dev/Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0B0B0D?style=flat-square&logo=linkedin&logoColor=EDEAE2)](https://linkedin.com/in/sharannm)
[![X](https://img.shields.io/badge/X-0B0B0D?style=flat-square&logo=x&logoColor=EDEAE2)](https://x.com/m_sharann)
[![Email](https://img.shields.io/badge/EMAIL-0B0B0D?style=flat-square&logo=gmail&logoColor=EDEAE2)](mailto:sharannmanojkumar@gmail.com)

</div>

![01 — whoami](assets/s01.svg)

I build software at the intersection of **design and data** — native SwiftUI apps, full-stack systems on PostgreSQL, and terminal interfaces that feel better than most GUIs. The throughline: tools that turn personal chaos into structure. Keyboard-first. Always dark mode.

CS @ **VIT Chennai** · '24–'28 — currently doing **AI hallucination–suppression research** (SRIP 2026) while shipping side projects faster than I can name them. Open-source contributor to [**MonkeyType**](https://github.com/monkeytypegame/monkeytype). Member of the **iSpace Club** web/app dev department.

```text
focus     iOS & Mobile · Full-Stack Systems · Terminal UI / CLI · AI-native architecture
research  hallucination suppression in LLMs — SRIP 2026, VIT Chennai
status    open to internships, freelance, and collaboration
```

![02 — system map](assets/s02.svg)

Twelve projects, four platforms, one pipeline. Every node below is a real, working system — dashed lines are data in motion.

![System map](assets/ecosystem.svg)

![03 — flagship](assets/s03.svg)

The three I'd show you first.

<table>
<tr>
<td width="33%" valign="top">

### Kern
**A keyboard-driven personal data OS.**
Schema-free JSONB storage, Monaco editor views, live integrations (GitHub · Notion · Calendar · Linear · RSS) — and its own **MCP server**, so AI can read and write your data natively.

`React` `TypeScript` `PostgreSQL` `MCP`

[**live ↗**](https://kern-alpha.vercel.app/) · [code](https://github.com/Sharann-del/Kern)

</td>
<td width="33%" valign="top">

### Cosmos
**An AI chatbot that lives in your terminal.**
25+ free models via OpenRouter, cloud-synced history across devices, file attachments, rich Markdown — installable in one command, at home in any tmux pane.

`Node.js` `OpenRouter` `TUI` `Supabase`

[**live ↗**](https://cosmos-tui.app) · [code](https://github.com/Sharann-del/Cosmos)

</td>
<td width="33%" valign="top">

### Landroid
**Drone imagery → land intelligence.**
A FastAPI backend ingests orthomosaic GeoTIFFs and derives NDVI insights, plant-health zone maps, and tree-count estimates for real farmland.

`Flutter` `FastAPI` `PostGIS` `Python`

[code](https://github.com/Sharann-del/Landroid)

</td>
</tr>
</table>

<br>

![now](assets/now.svg)

![04 — full index](assets/s04.svg)

Every row expands. Click into anything.

<details>
<summary>&nbsp;<b>kern</b> — keyboard-driven personal data OS &nbsp;·&nbsp; <code>React</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>MCP</code></summary>
<br>

> One inbox for everything you track — bookmarks, notes, tasks, feeds — stored schema-free in JSONB, queried like a database, navigated entirely by keyboard.

- **Storage** — schema-free JSONB rows in PostgreSQL; define a "type" on the fly, get views instantly
- **Views** — Monaco-powered editor surfaces, tables, and boards over the same data
- **Integrations** — GitHub, Notion, Google Calendar, Linear, and RSS sync in live
- **MCP server** — Supabase Edge Function exposing the whole dataset to AI agents as native tools
- **Design system** — brass-gold `#C8A84B` on near-black, hairline rules, mono everywhere

[**live ↗**](https://kern-alpha.vercel.app/) · [code](https://github.com/Sharann-del/Kern)

</details>

<details>
<summary>&nbsp;<b>cosmos</b> — AI chatbot in your terminal &nbsp;·&nbsp; <code>Node.js</code> <code>OpenRouter</code> <code>TUI</code> <code>Supabase</code></summary>
<br>

> A full chat client that never leaves the terminal — because the terminal is where the work already is.

- **Models** — 25+ free models routed through OpenRouter, switchable mid-conversation
- **Sync** — chat history synced through the cloud; pick up a thread on any machine
- **Files** — attach files straight from the shell; responses render as rich Markdown in the TUI
- **Install** — one command, no GUI, no electron

[**live ↗**](https://cosmos-tui.app) · [code](https://github.com/Sharann-del/Cosmos)

</details>

<details>
<summary>&nbsp;<b>landroid</b> — drone-based land intelligence &nbsp;·&nbsp; <code>Flutter</code> <code>FastAPI</code> <code>PostGIS</code> <code>Python</code></summary>
<br>

> Fly a drone over farmland, get back decisions: where the crop is stressed, where the trees are, what to do next.

- **Input** — orthomosaic GeoTIFF imagery from drone surveys
- **Analysis** — NDVI computation, plant-health zone maps, tree-count estimates, overlay PNGs
- **Backend** — FastAPI + PostGIS for spatial queries; Flutter app for the field

[code](https://github.com/Sharann-del/Landroid)

</details>

<details>
<summary>&nbsp;<b>amoeba</b> — self-prompting CLI coding agent &nbsp;·&nbsp; <code>Go</code> <code>CLI</code> &nbsp;·&nbsp; 🟡 building</summary>
<br>

> You send the *first* prompt. Amoeba writes every prompt after that — reading its own output, deciding the next step, looping until it prints `DONE`.

- **Mechanic** — single human prompt → autonomous prompt chain driven by accumulated context
- **Runtime** — pure Go, single binary, terminal-native visual identity

</details>

<details>
<summary>&nbsp;<b>forge</b> — idea → deployable codebase &nbsp;·&nbsp; <code>Tauri v2</code> <code>Next.js</code> <code>Python</code> &nbsp;·&nbsp; 🟡 building</summary>
<br>

> Describe the software. Forge plans it, splits it across a dynamic multi-agent system, and hands back a runnable codebase — all compiled on *your* machine.

- **Agents** — Python asyncio multi-agent pipeline that decomposes, writes, and assembles
- **Architecture** — native desktop shell (Tauri v2 + Next.js), builds run locally → zero server cost
- **Model layer** — bring-your-own-key via OpenRouter

</details>

<details>
<summary>&nbsp;<b>mantle</b> — a personal OS for iOS &nbsp;·&nbsp; <code>SwiftUI</code> <code>iOS 26</code> <code>OpenRouter</code> &nbsp;·&nbsp; 🟡 building</summary>
<br>

> Personal productivity rebuilt as one native surface — Liquid Glass components, pure-black dark mode, editorial typography (Gloock / SF Pro / JetBrains Mono).

- **Platform** — SwiftUI on iOS 26, Liquid Glass design language
- **AI** — bring-your-own-key through OpenRouter, woven through the whole app

</details>

<details>
<summary>&nbsp;<b>lobe</b> — personal knowledge OS for the web &nbsp;·&nbsp; <code>React</code> <code>TypeScript</code> <code>PostgreSQL</code></summary>
<br>

> Rich documents, databases, calendar views, kanban boards — plus a full mind-map of everything you've built.

[code](https://github.com/Sharann-del/Lobe)

</details>

<details>
<summary>&nbsp;<b>arbor</b> — problem-solving as a tree &nbsp;·&nbsp; <code>React</code> <code>React Flow</code> <code>OpenAI API</code></summary>
<br>

> Every node is a task or sub-problem. Recurse down, solve, backtrack — structured reasoning you can *see*.

[code](https://github.com/Sharann-del/Arbor)

</details>

<details>
<summary>&nbsp;<b>student dashboard</b> — one app instead of five broken portals &nbsp;·&nbsp; <code>React</code> <code>Node.js</code> <code>PostgreSQL</code></summary>
<br>

> Attendance, timetable, and planning for VIT students, consolidated from fragmented institutional systems.

[code](https://github.com/Sharann-del/Student-Dashboard-WP)

</details>

<details>
<summary>&nbsp;<b>notionwidgets</b> — Notion databases on your home screen &nbsp;·&nbsp; <code>SwiftUI</code> <code>WidgetKit</code> <code>Notion API</code></summary>
<br>

> Native iOS widgets rendered straight from Notion databases, with smart filtering.

[code](https://github.com/Sharann-del/NotionWidgets)

</details>

<details>
<summary>&nbsp;<b>planner</b> — scheduling, deadlines, clean organization &nbsp;·&nbsp; <code>SwiftUI</code> <code>Core Data</code></summary>
<br>

> A productivity-focused planner in SwiftUI — prioritization and visual clarity first.

[code](https://github.com/Sharann-del/Planner)

</details>

<details>
<summary>&nbsp;<b>terminaltype</b> — MonkeyType, but in the terminal &nbsp;·&nbsp; <code>JavaScript</code> <code>TUI</code></summary>
<br>

> Real-time WPM and accuracy in a clean TUI. Submitted to Terminal Trove.

[code](https://github.com/Sharann-del/terminaltype)

</details>

<details>
<summary>&nbsp;<b>billing system</b> — full-stack invoicing &nbsp;·&nbsp; <code>Node.js</code> <code>TypeScript</code> <code>PostgreSQL</code></summary>
<br>

> Dynamic multi-product invoices, automatic totals, reusable templates. Built during the GeoPacific internship.

[code](https://github.com/Sharann-del/Billing-System)

</details>

![05 — telemetry](assets/s05.svg)

![Telemetry](assets/telemetry.svg)

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sharann-del&show_icons=true&hide_border=true&bg_color=ffffff&title_color=3B5BDB&text_color=1A1A1A&icon_color=3B5BDB&border_color=E5E7EB&hide_rank=false" height="170" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sharann-del&layout=compact&hide_border=true&bg_color=ffffff&title_color=3B5BDB&text_color=1A1A1A&border_color=E5E7EB&langs_count=8" height="170" alt="Top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sharann-del&bg_color=ffffff&color=1A1A1A&line=3B5BDB&point=3B5BDB&area=true&area_color=3B5BDB&hide_border=true&custom_title=Contribution%20telemetry%20—%20live" width="97%" alt="Contribution graph" />

</div>

![06 — the route](assets/s06.svg)

![Timeline](assets/timeline.svg)

```text
2025 MAR — JUL   GeoPacific Solutions · Billing System Developer Intern · Chennai

  + Built a full-stack billing & inventory platform from scratch.
  + JSONB-based PostgreSQL schema → flexible product storage + dynamic invoices.
  + Role-based access (JWT) across admin / franchise / cashier tiers.
  + RESTful Node.js + Express APIs — invoice lifecycle, inventory, reporting.
  + TypeScript-first across every model and API contract.
```

![07 — stack](assets/s07.svg)

```text
languages   Swift · TypeScript · JavaScript · Python · Go · Dart · C++
mobile      SwiftUI · WidgetKit · Core Data · Flutter
web         React · Next.js · Node.js · Express · Tailwind · Vite
data        PostgreSQL · Supabase · FastAPI · PostGIS · Prisma · SQLite
ai          MCP · OpenRouter · OpenAI API · agentic systems · Tauri
tooling     Git · Docker · Figma · Notion · Postman · Neovim · Ghostty · Zellij
```

<br>

![status](assets/footer.svg)

<!--
  ❯ cat /dev/easter-egg
  you read the source. respect.
  this page is 13 hand-built SVGs sharing one design system:
  ink #0B0B0D · bone #EDEAE2 · brass #C8A84B
  say hi → sharannmanojkumar@gmail.com
-->
