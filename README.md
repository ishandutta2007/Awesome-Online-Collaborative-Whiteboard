# Awesome-Online-Collaborative-Whiteboard

# Top Online Collaborative Whiteboard Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Infinite Canvas, Real-Time Collaboration & Self-Hosted Visual Workspaces*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Online Collaborative Whiteboards**. These tools enable teams to sketch ideas, diagram systems, run workshops, and visualize thinking together on an infinite canvas—turning meetings and brainstorming into persistent, shareable artifacts.

**Examples** include Atlassian Whiteboards, Miro, Mural, FigJam, Lucidspark, Canva Whiteboards, Webex Whiteboard, Conceptboard, Klaxoon, and Stormboard (the category leaders).

**Open-source emphasis**: Collaborative Whiteboard is a domain where open-source tooling is **genuinely mature but carries a critical licensing fork**. **Excalidraw** is the clear standout—MIT-licensed, 134k+ GitHub stars, with a distinctive hand-drawn aesthetic, real-time collaboration via a separate `excalidraw-room` server, component libraries, and exports to PNG/SVG . **tldraw** offers a more polished, Figma-like canvas with richer shape/tool plugins, but **it is source-available, not open source**—since SDK 4.0 (September 2025), production use requires a license key (100-day trial, free hobby license with watermark, or commercial license via sales, reported around $6k/year for small teams) . **AFFiNE** combines docs, whiteboards, and databases in one local-first workspace (MIT editor, source-available backend), self-hostable with Docker, free for up to 10 seats . **Diwan** takes a different approach—a single Go binary with an Excalidraw-based whiteboard, CRDT-native peer-to-peer sync over end-to-end encryption, and full self-hosting with no cloud dependency . The critical caveat: **if OSI-approved licensing is a hard requirement, tldraw is disqualified**—Excalidraw and Diwan are the safe choices .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Atlassian Whiteboards](https://www.atlassian.com/)**  
  Whiteboard capability within the Atlassian ecosystem; integrates with Jira and Confluence for collaborative planning and diagramming alongside work items.

- **[Miro](https://miro.com/)**  
  The market-leading collaborative whiteboard platform; infinite canvas with templates, voting, timers, and integrations across the enterprise stack. The benchmark against which all alternatives are measured.

- **[Mural](https://www.mural.co/)**  
  Collaborative whiteboard focused on guided workshops and team facilitation; strong for design thinking and agile ceremonies.

- **[FigJam](https://www.figma.com/figjam/)**  
  Figma's whiteboard tool; integrates tightly with Figma design files for collaborative brainstorming that flows into design work.

- **[Lucidspark](https://lucid.co/)**  
  Collaborative whiteboard within the Lucid suite; integrates with Lucidchart for diagramming and visual collaboration.

- **[Canva Whiteboards](https://www.canva.com/)**  
  Whiteboard capability within Canva's design platform; combines freeform collaboration with Canva's template and asset library.

- **[Webex Whiteboard](https://www.webex.com/)**  
  Whiteboard within Cisco Webex; integrates with Webex meetings for real-time visual collaboration during calls.

- **[Conceptboard](https://conceptboard.com/)**  
  Visual collaboration platform with whiteboards, project management, and feedback tools; positioned for enterprise teams.

- **[Klaxoon](https://klaxoon.com/)**  
  Collaborative workshop platform with whiteboards, quizzes, and activities; focused on engaging meetings and training.

- **[Stormboard](https://stormboard.com/)**  
  Digital sticky note and whiteboard platform; focused on structured brainstorming and decision-making.

## Open-Source GitHub Projects

### OSI-Approved Whiteboards (MIT)

- **[Excalidraw](https://github.com/excalidraw/excalidraw)**  
  The **leading OSI-approved open-source whiteboard** (MIT, 134k+ GitHub stars, actively maintained) . Features: **distinctive hand-drawn aesthetic**; infinite canvas with shapes, arrows, freehand, text, and images; **real-time collaboration** via the separate `excalidraw-room` WebSocket server ; **component libraries** for reusable shapes and icons; export to PNG, SVG, and native `.excalidraw` format . **Self-hosting**: the drawing engine runs in the browser, and the server only handles collaboration sync—**a 1 vCPU / 1 GB RAM VPS handles 20+ concurrent users comfortably** . **Caveat**: React-only as an embeddable component (344 kB minified+gzipped across 31 dependencies), and the hand-drawn aesthetic is hard to restyle away . **Best for teams wanting maximum maturity with MIT licensing**—the safest open-source Miro alternative.

- **[Diwan](https://github.com/vul-os/diwan)**  
  A **self-hostable collaborative office suite** that includes a whiteboard built on the MIT Excalidraw editor (MIT, single Go binary) . Features: **infinite hand-drawn canvas** with shapes, arrows, freehand, text, and images; **real-time co-editing** via **CRDT-native peer-to-peer sync over end-to-end encryption**—peers connect directly over WebRTC with a content-blind relay only as a hard-NAT fallback; **no central document server** . Also includes documents, spreadsheets, slides, and PDF signing in the same binary. **Self-hosting**: `docker run` one-liner with local files + SQLite by default, optional PostgreSQL and S3-compatible storage. **Best for teams wanting a full productivity suite with an E2E-encrypted whiteboard**—but it is a broader suite, not a standalone whiteboard.

### Source-Available Whiteboards (Licensing Caveat)

- **[tldraw](https://github.com/tldraw/tldraw)**  
  A **polished, Figma-like infinite canvas SDK** (51k+ GitHub stars) with richer shape and tool plugin architecture than Excalidraw, sticky notes, multi-page support, refined snapping/alignment, and experimental AI features ("Make Real" converts sketches to HTML/CSS) . **CRITICAL LICENSING CAVEAT**: **it is source-available, not OSI-approved open source**. Since SDK 4.0 (September 2025), production use requires a license key: 100-day free trial, free hobby license (non-commercial, watermark required), or commercial license via sales—**no public price list, with reports of ~$6k/year for small teams** . **Best for funded products** where the license cost is acceptable and the richer editor framework justifies it—**not for projects requiring true open-source licensing** .

### All-in-One Workspaces with Whiteboards

- **[AFFiNE](https://github.com/toeverything/AFFiNE)**  
  An **open-source, local-first knowledge base** combining docs, whiteboards, and databases in one workspace (MIT editor and most client code; backend source-available under AFFiNE EE license) . Features: **every page can be a document, an infinite canvas, or a database view**—not a whiteboard bolted onto a doc editor; **AI** for drafting, summaries, mind maps, and presentations; **offline-first** local workspaces . **Self-hosting**: Docker Compose with PostgreSQL and Redis; **free for up to 10 seats per workspace**, then $10/seat/month billed annually . **Best for teams wanting a Notion + Miro replacement in one tool**—but the backend is source-available, not fully open source.

### Additional Strong Open-Source Options

- **Penpot** — Open-source design platform (Figma competitor) with a canvas-based interface for visual collaboration, wireframing, and prototyping; real-time multi-user editing with SVG-native output . **Best for design work** that goes beyond simple whiteboarding—heavier than Excalidraw (needs PostgreSQL + Redis, 2–4 GB RAM) .
- **CryptPad Whiteboard** — End-to-end encrypted whiteboard module within CryptPad; simpler than Excalidraw (basic shapes, freehand, text) but **the server never sees your drawings** . **Best for sensitive brainstorming** where encryption is non-negotiable—needs 1–2 GB RAM for a small team .
- **draw.io (diagrams.net)** — Industry standard for technical diagramming (network topologies, flowcharts, ERDs, architecture diagrams); can run as a static web app or self-hosted with collaboration . **Best for structured technical diagrams** rather than freeform whiteboarding.
- **nexcanvas** — Self-hosted whiteboard in the spirit of Apple Freeform; sticky notes, shapes, text, lines, pen/highlighter, photos, and PDFs on an endless board; frames, scenes, shape library, templates, PNG/PDF export, and JSON Canvas exchange . **Best for users wanting a Freeform-style experience** on their own server—newer and less community-validated.

**Frameworks for building custom systems**: For **maximum maturity with MIT licensing**, Excalidraw is the safe default . For **E2E-encrypted peer-to-peer whiteboarding within a full office suite**, Diwan . For **a polished, Figma-like canvas where the license cost is acceptable**, tldraw . For **docs + whiteboards + databases in one self-hosted workspace**, AFFiNE . For **design-focused visual collaboration**, Penpot . For **encrypted brainstorming**, CryptPad . **If OSI-approved licensing is a hard requirement, avoid tldraw** .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Collaborative whiteboard platforms handling team content must comply with organizational data governance policies; **self-hosted solutions place full responsibility for security, backups, and uptime on the operator**.
- **Open-source whiteboarding is mature but carries a critical licensing fork**—Excalidraw is MIT and the safest choice , while **tldraw is source-available, not open source**, and requires a license key for production use since SDK 4.0 (reported ~$6k/year for small teams) . **If OSI-approved licensing is a hard requirement, tldraw is disqualified**. AFFiNE's backend is source-available under its EE license, though the editor is MIT .
- Verify license terms for commercial use; Excalidraw uses MIT , Diwan uses MIT , tldraw uses a custom source-available license requiring production keys , and AFFiNE uses MIT for the editor with a source-available backend .

---

**Made for product teams, designers, facilitators, and organizations choosing their visual collaboration stack.**  
Let's make collaborative whiteboarding more open, but with clear eyes about the licensing fork that separates true open source from source-available traps.
