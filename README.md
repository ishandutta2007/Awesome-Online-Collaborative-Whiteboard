# Awesome-Online-Collaborative-Whiteboard

## Top Online Collaborative Whiteboard Ecosystem



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

*Sorted by GitHub Star count in descending order.*

- **[Excalidraw](https://github.com/excalidraw/excalidraw)** [![GitHub stars](https://img.shields.io/github/stars/excalidraw/excalidraw?style=social&color=white)](https://github.com/excalidraw/excalidraw/stargazers)  
  The leading OSI-approved open-source virtual whiteboard (MIT). Features a distinctive hand-drawn aesthetic, infinite canvas with shapes, arrows, freehand, text, images, and real-time multiplayer collaboration via WebSocket (xcalidraw-room). Includes component libraries, local-first in-browser rendering with minimal server footprint, and export to PNG, SVG, or native format.

- **[AFFiNE](https://github.com/toeverything/AFFiNE)** [![GitHub stars](https://img.shields.io/github/stars/toeverything/AFFiNE?style=social&color=white)](https://github.com/toeverything/AFFiNE/stargazers)  
  An open-source, local-first knowledge base combining docs, infinite whiteboard canvas, and multidimensional tables in one unified workspace. Every page can toggle between structured document, whiteboard diagram, and database view. Offers offline-first local storage, AI-assisted mind mapping, and self-hosting with Docker.

- **[Penpot](https://github.com/penpot/penpot)** [![GitHub stars](https://img.shields.io/github/stars/penpot/penpot?style=social&color=white)](https://github.com/penpot/penpot/stargazers)  
  Web-based open-source design and prototyping platform (MPL-2.0). Features an infinite collaborative visual canvas with native SVG support, flex/grid layouts, reusable components, interactive prototyping, and real-time multi-user editing.

- **[tldraw](https://github.com/tldraw/tldraw)** [![GitHub stars](https://img.shields.io/github/stars/tldraw/tldraw?style=social&color=white)](https://github.com/tldraw/tldraw/stargazers)  
  A polished, Figma-like infinite canvas React SDK featuring rich shape and tool plugin architecture, sticky notes, multi-page support, snapping/alignment, and experimental AI sketch-to-code features. *Licensing Note*: Source-available (requires a license key for production use since SDK 4.0; free hobby/trial tiers available).

- **[Drawnix](https://github.com/plait-board/drawnix)** [![GitHub stars](https://img.shields.io/github/stars/plait-board/drawnix?style=social&color=white)](https://github.com/plait-board/drawnix/stargazers)  
  An all-in-one open-source whiteboard (MIT) integrating mind mapping, flowcharts, freehand drawing, and diagramming on an infinite canvas. Built with modern web technologies, modular architecture, and multi-mode editing capabilities.

- **[draw.io (diagrams.net)](https://github.com/jgraph/drawio)** [![GitHub stars](https://img.shields.io/github/stars/jgraph/drawio?style=social&color=white)](https://github.com/jgraph/drawio/stargazers)  
  Industry-standard open-source diagramming web application (Apache-2.0). Provides rich flowcharting, network architecture, UML, and process diagram editing with extensive stencil libraries and integrations with cloud storage and self-hosted environments.

- **[CryptPad Whiteboard](https://github.com/cryptpad/cryptpad)** [![GitHub stars](https://img.shields.io/github/stars/cryptpad/cryptpad?style=social&color=white)](https://github.com/cryptpad/cryptpad/stargazers)  
  End-to-end encrypted collaboration suite (AGPL-3.0) with a dedicated whiteboard application. Client-side encryption ensures all drawings, sketches, and notes remain private and inaccessible to server administrators.

- **[Lorien](https://github.com/mbrlabs/Lorien)** [![GitHub stars](https://img.shields.io/github/stars/mbrlabs/Lorien?style=social&color=white)](https://github.com/mbrlabs/Lorien/stargazers)  
  Infinite canvas drawing and note-taking application (MIT) built on the Godot engine. Focused on fast performance, smooth freehand brushstrokes, infinite canvas zoom/pan, cross-platform desktop support (Windows, Linux, macOS), and a distraction-free UI.

- **[OpenBoard](https://github.com/OpenBoard-org/OpenBoard)** [![GitHub stars](https://img.shields.io/github/stars/OpenBoard-org/OpenBoard?style=social&color=white)](https://github.com/OpenBoard-org/OpenBoard/stargazers)  
  Open-source cross-platform interactive whiteboard application (GPL-3.0) designed for schools, universities, and presentations. Supports stylus pen tablets, interactive widgets, document annotation, podcasting/screen recording, and PDF imports.

- **[Whitebophir](https://github.com/lovasoa/whitebophir)** [![GitHub stars](https://img.shields.io/github/stars/lovasoa/whitebophir?style=social&color=white)](https://github.com/lovasoa/whitebophir/stargazers)  
  Simple, lightweight, real-time collaborative whiteboard (AGPL-3.0) built with Node.js and WebSockets. Allows multiple users to draw simultaneously on a persistent board with zero setup friction and Docker deployment.

- **[Revezone](https://github.com/revezone/revezone)** [![GitHub stars](https://img.shields.io/github/stars/revezone/revezone?style=social&color=white)](https://github.com/revezone/revezone/stargazers)  
  Lightweight, local-first graphic-centric productivity workspace (AGPL-3.0). Combines Excalidraw and Tldraw visual whiteboards with Notion-like structured markdown notes, bidirectional linking, and offline desktop sync.

- **[Spacedeck Open](https://github.com/spacedeck/spacedeck-open)** [![GitHub stars](https://img.shields.io/github/stars/spacedeck/spacedeck-open?style=social&color=white)](https://github.com/spacedeck/spacedeck-open/stargazers)  
  Web-based, real-time collaborative whiteboard application (AGPL-3.0) with rich media support. Enables teams to arrange notes, shapes, audio, video, and documents collaboratively on infinite zoomable spaces.

- **[Whiteboard (cracker0dks)](https://github.com/cracker0dks/whiteboard)** [![GitHub stars](https://img.shields.io/github/stars/cracker0dks/whiteboard?style=social&color=white)](https://github.com/cracker0dks/whiteboard/stargazers)  
  Lightweight collaborative whiteboard and sketchboard (MIT). Built with Node.js and HTML5 canvas, supports real-time co-drawing, undo/redo synchronization, image uploading, and simple self-hosting.

- **[OurBoard](https://github.com/raimohanska/ourboard)** [![GitHub stars](https://img.shields.io/github/stars/raimohanska/ourboard?style=social&color=white)](https://github.com/raimohanska/ourboard/stargazers)  
  Lightweight online collaborative whiteboard with sticky notes, drawings, and images. Features instant real-time synchronization over WebSockets and simple deployment.

- **[Nextcloud Whiteboard](https://github.com/nextcloud/whiteboard)** [![GitHub stars](https://img.shields.io/github/stars/nextcloud/whiteboard?style=social&color=white)](https://github.com/nextcloud/whiteboard/stargazers)  
  Collaborative infinite canvas whiteboard integrated directly into the Nextcloud ecosystem (AGPL-3.0). Supports shapes, drawing, sticky notes, and seamless integration with Nextcloud Files and permissions.

- **[Tableau Noir](https://github.com/tableaunoir/tableaunoir)** [![GitHub stars](https://img.shields.io/github/stars/tableaunoir/tableaunoir?style=social&color=white)](https://github.com/tableaunoir/tableaunoir/stargazers)  
  Interactive online blackboard and whiteboard (GPL-3.0) designed for teaching, tutoring, and presentations. Offers virtual fridge magnets, multi-board pagination, recording, and smooth drawing in a lightweight UI.

- **[Diwan](https://github.com/vul-os/diwan)** [![GitHub stars](https://img.shields.io/github/stars/vul-os/diwan?style=social&color=white)](https://github.com/vul-os/diwan/stargazers)  
  Self-hostable collaborative office suite shipped as a single Go binary (Apache-2.0 / MIT). Features an Excalidraw-based whiteboard with CRDT peer-to-peer sync and end-to-end encryption over WebRTC, alongside docs and spreadsheets.

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
