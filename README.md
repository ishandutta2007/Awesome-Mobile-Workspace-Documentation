# Awesome-Mobile-Workspace-Documentation

# Top Mobile Workspace & Documentation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Mobile Note-Taking, Offline Knowledge Bases & Self-Hosted Documentation*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile Workspace & Documentation**. These tools enable individuals and teams to capture notes, build knowledge bases, and access documentation on mobile devices—turning scattered thoughts into organized, searchable personal and team knowledge.

**Examples** include Confluence Mobile, Notion Mobile, Coda Mobile, Evernote, Google Keep, Microsoft OneNote, Bear, ClickUp Mobile, Craft Docs, and Obsidian (the category leaders).

**Open-source emphasis**: Mobile Workspace & Documentation is a domain where open-source tooling is **genuinely mature for personal knowledge management but fragmented for true mobile-first experiences**. **Joplin** is the standout—an AGPL-3.0 licensed, cross-platform note-taking app with Markdown support, end-to-end encryption, self-hosted sync, web clipper, and plugins, rated by PCMag as the best open-source note app of 2026 . **TriliumNext** offers the most powerful hierarchical knowledge base—self-hosted sync, Excalidraw canvas, mind maps, geo maps, and proven scalability to 100,000+ notes, with a touch-optimized mobile web interface . **AFFiNE** combines docs, whiteboards, and databases in a local-first workspace with iOS and Android apps . The critical caveat: **no open-source project matches the polished native mobile apps** of Notion or Bear—open-source tools rely on web interfaces or third-party mobile apps (like TriliumDroid for Trilium), while commercial platforms invest heavily in native iOS/Android experiences.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Confluence Mobile](https://www.atlassian.com/software/confluence)**  
  Mobile access to Atlassian's team workspace; view and edit pages, comment, and access team knowledge on iOS and Android.

- **[Notion Mobile](https://www.notion.com/)**  
  Mobile apps for Notion's all-in-one workspace; access wikis, docs, and databases on the go with offline support.

- **[Coda Mobile](https://coda.io/)**  
  Mobile access to Coda's document-tool hybrid; view and edit docs, tables, and controls on mobile devices.

- **[Evernote](https://evernote.com/)**  
  The long-standing note-taking platform with native mobile apps; web clipper, OCR, and cross-platform sync.

- **[Google Keep](https://keep.google.com/)**  
  Simple note-taking with Google ecosystem integration; voice notes, lists, and reminders on mobile.

- **[Microsoft OneNote](https://www.microsoft.com/en-us/microsoft-365/onenote/digital-note-taking-app)**  
  Microsoft's digital notebook with native mobile apps; freeform canvas, drawing, and Office integration.

- **[Bear](https://bear.app/)**  
  Apple-exclusive Markdown note-taking app known for its polished design and seamless iCloud sync.

- **[ClickUp Mobile](https://clickup.com/)**  
  Mobile access to ClickUp's all-in-one productivity platform; tasks, docs, and goals on the go.

- **[Craft Docs](https://www.craft.do/)**  
  Document and note-taking app with native Apple apps; block-based editor with a focus on design and collaboration.

- **[Obsidian](https://obsidian.md/)**  
  Local-first Markdown knowledge base with mobile apps; files stored as plain text on your device, with paid sync service.

## Open-Source GitHub Projects

### Full Knowledge Bases (Joplin, TriliumNext, AFFiNE)

- **[Joplin](https://github.com/laurent22/joplin)**  
  The **most recommended open-source note-taking app** (AGPL-3.0, PCMag's "Best Open-Source App" for 2026)  . Features: **Markdown notes** with optional rich text editor; **end-to-end encrypted sync** via Joplin Cloud, Dropbox, OneDrive, Nextcloud, or self-hosted Joplin Server  ; **web clipper** for Firefox/Chrome; **plugins** for OCR, Kanban boards, themes, and more; **import from Evernote** (ENEX); **offline OCR** for PDFs; and apps for Windows, macOS, Linux, Android, and iOS  . **2026 addition**: built-in AI with **local semantic search** (140MB model downloaded to device, no note content sent to cloud) and an MCP server listening only on 127.0.0.1  . **Best for users wanting a proven, privacy-focused Evernote alternative** with the broadest platform support—but mobile apps are functional rather than polished, and advanced features like OCR require plugins  .

- **[TriliumNext](https://github.com/TriliumNext/Trilium)**  
  The **most powerful open-source hierarchical knowledge base** (AGPL-3.0, community-maintained successor to the original Trilium)  . Features: **arbitrarily deep note tree** with cloning (a note can exist in multiple places without duplicating data) ; **WYSIWYG editor** with Markdown autoformat, tables, images, and math; **Excalidraw canvas** for sketching diagrams; **mind maps** (Mind Elixir) ; **geo maps** with GPX tracks; **Mermaid diagrams**; **note versioning**; **per-note encryption** (AES-128) ; **REST API** for automation; **Web Clipper**; **OpenID + TOTP** for secure login; and **self-hosted sync server**  . **Scalability**: proven to **100,000+ notes** with no performance issues (SQLite backend)  . **Mobile access**: touch-optimized **mobile web frontend** for smartphones/tablets; **TriliumDroid** provides a native Android app (available on IzzyOnDroid) ; no official iOS app  . **Best for power users wanting a self-hosted "second brain"** with maximum data ownership—but requires server setup and the mobile experience is web-first or third-party.

- **[AFFiNE](https://github.com/toeverything/AFFiNE)**  
  Open-source **knowledge base combining docs, whiteboards, and databases** in one local-first workspace (MIT editor, source-available backend)  . Features: **switch between document and infinite canvas** with a click; **AI-powered creation** (writing, slides, summaries, mind maps) with configurable API keys or local LLMs; **offline use with server sync**; Docker self-hosting with PostgreSQL and Redis; **free for up to 10 seats** per workspace, then $10/seat/month  . **Native mobile apps**: iOS and Android clients available  . **Best for teams wanting a Notion + Miro replacement** with mobile apps—but the backend is source-available, not fully open source.

### Mobile-Optimized Markdown Editors

- **[Tiro Notes](https://github.com/tiro-notes/tiro-notes)**  
  Open-source **cross-platform Markdown editor** designed for extensibility (npm package, v0.43.46) . Features: **Markdown notes with custom tags** (`[[latex]]`, `[[diagram]]`, `[[view]]`, `[[script]]`) ; **multi-window interface** for custom workspaces; **note encryption** (RSA 2048) ; **note history**; **PDF export**; **text-to-speech**; **fast search** (~2s for 30k notes) ; and **no database required**—Markdown files only  . **Mobile access**: **Android via Termux** and **any browser** (mobile, tablet, desktop interfaces) ; iOS via iSH (untested)  . **Best for users wanting a lightweight, extensible Markdown editor** accessible on mobile via browser or Termux—but it is not a native mobile app and requires technical setup for mobile use.

### Additional Strong Open-Source Options

- **Standard Notes** — Privacy-focused note-taking with **end-to-end encryption**, unlimited device sync, and offline access on the free plan; paid tiers add Markdown, checklists, spreadsheets, and web clipper  . **Best for users prioritizing encryption** over feature richness—but it is simpler than Joplin or TriliumNext.
- **Notesnook** — Privacy-focused, feature-rich note-taking with **rich-text notes**, images, attachments, reminders, and no device limit on the free plan (50MB monthly storage, 50 notebooks)  . **Best for users wanting a more permissive free tier** than Evernote—but it is newer and less proven than Joplin.
- **Noteriv** — Open-source Markdown editor (Tauri 2) with graph view, plugin API, themes, Git/WebDAV sync, and **AI MCP integration**; includes board view, calendar view, and canvas/whiteboard  . **Best for desktop-focused users** wanting Obsidian-like features—but mobile support is not documented.

**Frameworks for building custom systems**: For **proven, cross-platform note-taking with E2E encryption and self-hosted sync**, Joplin is the mature standard  . For **a self-hosted hierarchical "second brain" with maximum data ownership**, TriliumNext (accepting web-first mobile)  . For **native mobile apps with docs + whiteboards + databases**, AFFiNE (accepting source-available backend)  . For **lightweight Markdown editing accessible on mobile via browser**, Tiro Notes  . **No open-source project matches the polished native mobile experience** of Notion or Bear—commercial platforms invest heavily in iOS/Android apps, while open-source relies on web interfaces or third-party clients.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile workspace platforms handling personal and team notes must comply with applicable privacy regulations (GDPR, CCPA) and organizational data governance policies; **self-hosted solutions place full responsibility for backups, security patches, and sync infrastructure on the operator**.
- **Open-source mobile workspace is mature for desktop-first tools but fragmented for native mobile apps**—Joplin provides the most proven cross-platform experience  , TriliumNext offers the most powerful self-hosted knowledge base with web mobile access  , and AFFiNE provides native iOS/Android apps  . However, **no open-source project matches the polish of Notion or Bear on mobile**—commercial platforms invest in native app development that open-source projects often lack. Choose based on whether you prioritize data ownership (Joplin, TriliumNext) or native mobile experience (commercial).
- Verify license terms for commercial use; Joplin uses AGPL-3.0  , TriliumNext uses AGPL-3.0  , and AFFiNE uses MIT for the editor with a source-available backend  .
