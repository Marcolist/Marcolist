# Hi, I'm Marco 👋

**Independent developer building blockchain infrastructure, AI systems, industrial software, and embedded hardware.**

I build across the stack: node installers and indexers, trading research platforms, mobile and desktop apps, and physical products with custom firmware and handcrafted enclosures.

My work connects low-level infrastructure with interfaces people can use — whether that's operating a validator, inspecting a lens manufacturing job, managing a smart home, or putting a crypto portfolio on a wooden desk display.

## Selected projects

| Project | What I'm building |
| --- | --- |
| [QRX Node Suite](https://github.com/Marcolist/qrx-node-suite) | Node and validator operations for QRX: Go agent, web dashboard, monitoring, alerts, and signed update/rollback tooling. Under active development. |
| [SolaxyEasyNode](https://github.com/Marcolist/SolaxyEasyNode) | One-command setup for a Solaxy SVM rollup node, Celestia DA, PostgreSQL, systemd services, a web dashboard, and Telegram integration. |
| [NeuraLiquid](https://github.com/Marcolist/NeuraLiquid_AI-Bot) | Modular Hyperliquid trading research and automation: AI-assisted analysis, pattern strategies, copy trading, ML filters, backtesting, and hardware dashboards. Public overview; private implementation. |
| **DCSpro** | Portable C# / WPF workspace for optical manufacturing: OMA/VCA/MCH files, separate right/left 2D and 3D views, laser marking and PNG stamps, SQL measurement results, and configurable file interfaces. |
| **NCSHIFT** | C++ Windows tool for translating VCA/DAT templates between CNC lens edging systems, with sequence mapping, tool comparison, batch conversion, and a folder watchdog. |
| [MosEs](https://github.com/Marcolist/MosEs_Core) | Modular, self-hosted everyday screen for Raspberry Pi: calendar, weather, traffic, solar production, crypto, and news through independently installable [plugins](https://github.com/Marcolist/MosEs_plugins). |
| **WoodChain ONE** | ESP32-S3 crypto portfolio display in a handcrafted solid wood enclosure, with an LVGL touch UI, market data, multi-wallet/multi-chain views, and OTA updates. |
| **TokenReaper** | Mobile token risk scanner for iOS and Android, covering token authorities, liquidity, creator history, and transaction simulation, with RevenueCat subscriptions. |

The portfolio below includes private implementations, research tools, and prototypes. Public links lead to source repositories or project overviews; concepts and early-stage work are marked.

## More of my work

<details>
<summary><strong>Blockchain infrastructure, indexers & wallets</strong></summary>

- **[OrbitNode](https://github.com/Marcolist/orbitnode) / [orbitnode.dev](https://orbitnode.dev)** — Node operations, network monitoring, and validator tooling, including Solaxy infrastructure and EigenLayer operator work.
- **[neptoon.me](https://neptoon.me)** — DEX frontend for Solaxy with candlestick charts, swaps, and liquidity pool exploration.
- **NeptoonOrbit / Solaxy Indexer / Orbit Indexer** — DEX event indexing, pool and token data, swaps, liquidity events, REST APIs, and explorer dashboards using PostgreSQL and ClickHouse across implementations.
- **[Solaxy Hub](https://github.com/Marcolist/SolaxyHub)** — React Native wallet work for iOS and Android, combining asset management, DEX and bridge access, a dApp browser, and WalletConnect.
- **[Solaxy Wallet Snap](https://github.com/Marcolist/solaxy-snap)** — MetaMask Snap integration for Solaxy/SVM key derivation, transaction signing, and message signing.
- **Hyperlane tooling** — Solaxy/BSC Warp Route configurations, bridge UI adaptations, and cross-chain integration experiments.
- **Solaxy State Uploader** — State/genesis distribution tools supporting node setup and recovery.
- **Solaxy protocol research** — Source-level and on-chain analysis, transaction-format reverse engineering, and structured technical findings and evidence documentation.

</details>

<details>
<summary><strong>AI agents, developer tools & smart home</strong></summary>

- **Homer** — AI agent command center for local smart-home orchestration.
- **EDITH** — Raspberry Pi home-lab command center for server monitoring, remote execution, Docker management, and AI agent orchestration through a dashboard, mobile PWA, and Telegram.
- **CC-Brain** — Native macOS app and CLI for persistent, searchable knowledge across Claude Code projects and sessions.
- **JARVIS-Frame** — Raspberry Pi family dashboard in a wooden frame, combining voice interaction, speaker recognition, personal briefings, and smart-home data.
- **PhoneGhost** — Raspberry Pi 5 AI phone assistant with SIP / FRITZ!Box integration, a web setup wizard, call summaries, and bootable-image packaging.
- **BugBuy Studio** — Container-isolated smart-contract security research platform with AI analysis, fork-based finding verification, and report generation.

</details>

<details>
<summary><strong>Trading systems & market analytics</strong></summary>

- **TokenReaper for Hyperliquid** — Portfolio risk and orderflow dashboard with sub-account analytics, liquidation views, whale flows, and NeuraLiquid signal integration.
- **SolReaper** — Solana DEX arbitrage research and execution engine with token discovery, risk checks, and monitoring.
- **[GapHunter](https://github.com/Marcolist/GapHunter)** — Cross-chain token price divergence monitor for studying convergence and potential trading signals.
- **[ERICORE](https://github.com/Marcolist/ERICORE)** — Telegram signal parsing, validation, risk management, and MetaTrader 5 execution tooling.

</details>

<details>
<summary><strong>Embedded hardware, networking & security</strong></summary>

- **[EspMoveLamp](https://github.com/Marcolist/EspMoveLamp)** — ESP32 motorized WS2812 light bar with a separate touchscreen scene controller and local web editor. Hardware prototype in progress.
- **NetworkGuard** — Go-based passive network monitoring appliance for Raspberry Pi 5, with packet metadata analysis and UniFi / RouterOS integration boundaries. Early implementation.
- **Glitchy** — Native C / LVGL security toolkit prototype for Linux on repurposed iPads, with an ESP32 companion-runtime design. Device support remains under qualification.
- **[RentenDisplay](https://github.com/Marcolist/RentenDisplay)** — Low-power Arduino / E-Ink retirement countdown with RTC, workday calculations, and enclosure design.

</details>

<details>
<summary><strong>Industrial software & practical business tools</strong></summary>

- **LensClaw** — Barcode-driven desktop tool for inspecting and editing optical manufacturing interface files, with right/left previews and atomic file writes.
- **JUNA** — Portable C# regulatory-document monitoring pilot with local SQLite storage, review workflows, and PDF evidence exports.
- **VCA Interface Splitter** — Python utility for splitting large manufacturing interface dumps while keeping each right/left lens order together.
- **InstaStudio** — Multi-tenant content creation tool for opticians, with campaign templates, branded image rendering, and downloadable asset bundles.

</details>

<details>
<summary><strong>Apps, utilities & creative experiments</strong></summary>

- **BaggerPilot** — Web, iOS, and Android planning tool for excavator operations, combining vehicle-specific routing, provider search, and handover documentation.
- **Bikecheck** — Local used-motorcycle search and comparison tool with deduplication, scoring, filters, and a desktop dashboard.
- **Fernorbit** — Sci-fi colony-builder concept and preproduction project focused on sustainable ecosystems, exploration, and voluntary trade.
- **FreiesPferd** — Personal Swift / iOS app project.
- **[ExcelCall](https://github.com/Marcolist/ExcelCall)** — Excel-to-vCard converter for importing contact lists into an iPhone, available as a Python CLI and Windows GUI.
- **[Pi SMB Print Server](https://github.com/Marcolist/Pi_SMB_PRINT-SERVER)** — Raspberry Pi bridge connecting legacy Windows printing workflows to modern printers through Samba, CUPS, and a watched folder.

</details>

## Tech I work with

| Area | Technologies |
| --- | --- |
| Languages | TypeScript / JavaScript, Python, Go, C#, C / C++, Swift, Bash |
| Web & mobile | React, Next.js, React Native, Node.js, FastAPI, Capacitor |
| Desktop & embedded UI | WPF / .NET, CustomTkinter, LVGL |
| Blockchain | Solana / SVM, Sovereign SDK, Celestia DA, Hyperlane, Hyperliquid, QRX node integration |
| Data & infrastructure | PostgreSQL, ClickHouse, SQLite, Docker, systemd, Linux, VPS and bare-metal servers |
| Hardware & interfaces | ESP32 / ESP32-S3, Raspberry Pi, Arduino, E-Ink, SIP / Asterisk, laser cutting, CNC |
| Development & diagnostics | Claude Code, GitHub Actions, Vediamo, DTS-Monaco |

## Open to collaboration

- Node tooling, indexers, validator operations, and cross-chain infrastructure
- AI agent architecture, developer tools, and self-hosted automation
- Wallet UX, DEX frontends, trading research, and on-chain analytics
- Industrial desktop software and manufacturing data interfaces
- Hardware products combining useful software with embedded systems and thoughtful enclosures

## Get in touch

[GitHub](https://github.com/Marcolist) · [Email](mailto:listmarco@gmail.com) · [Telegram: @ML1985DE](https://t.me/ML1985DE)
