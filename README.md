<div align="center">
  <img alt="starknet logo" src="./assets/banner.png" width="500">
  <h1 align="center">Awesome Daydreams</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="https://github.com/gakonst/awesome-starknet/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/wayzeek/awesome-daydreams">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">
    A curated list of awesome <a href="https://www.dreams.fun/">Daydreams</a> resources, libraries, tools, and more.
  </p>

  <p align="center">
    Please refer to the <a href="CONTRIBUTING.md">contribution guidelines</a> for details on formatting and submitting pull requests.
  </p>
</div>

## Contents

- [Resources](#resources)
  - [Official](#official)
  - [Tutorials and Examples](#tutorials-and-examples)
  - [Articles and Blogs](#articles-and-blogs)
  - [Papers](#papers)
- [Ecosystem](#ecosystem)
  - [Dapps](#dapps)
  - [Community](#community)
- [Developer Resources](#developer-resources)
  - [Developer Tools](#developer-tools)
- [Open-source Projects](#open-source-projects)
  - [DeFi](#defi)
  - [Gaming](#gaming)
- [License](#license)

---

## Resources

### Official
- [Github](https://github.com/daydreamsai/daydreams/tree/main) - Official GitHub repository.
- [Website](https://www.dreams.fun/) - Official website.
- [Docs](https://docs.dreams.fun/) - Official documentation.
- [Discord](https://discord.com/invite/P8UUNGtHZs) - Official Discord server.
- [Twitter](https://x.com/daydreamsagents) - Official Twitter account.
- [Telegram](https://t.me/+kGzGMRvsQhY5Njg0) - Official Telegram channel.
- [dreams-client](https://github.com/daydreamsai/dreams-client) - Official torrent client for sharing agents' reasoning data via P2P network.
- [sleeves](https://github.com/daydreamsai/sleeves) - Official registry for Daydreams agents' context files.

### Tutorials and Examples

#### Basic Examples
- [Simple CLI Chat](https://github.com/daydreamsai/daydreams/blob/main/examples/basic/example-basic.ts) - Simple command-line chat interface using Groq's LLM.
- [GitHub Code Assistant](https://github.com/daydreamsai/daydreams/blob/main/examples/basic/example-chat-with-code.ts) - Chat with your GitHub code repositories.
- [Claude Chat Interface](https://github.com/daydreamsai/daydreams/blob/main/examples/basic/example-chat.tsx) - React-based chat interface using Anthropic's Claude model.
- [Vector Memory](https://github.com/daydreamsai/daydreams/blob/main/examples/basic/example-vector.ts) - Vector storage integration with Chroma for enhanced memory.

#### Blockchain/DeFi Examples
- [Hyperliquid Trading Bot](https://github.com/daydreamsai/daydreams/blob/main/examples/chains/example-hyperliquid.ts) - Comprehensive trading bot for the Hyperliquid platform.
- [Sui Blockchain Agent](https://github.com/daydreamsai/daydreams/blob/main/examples/chains/example-sui.ts) - Agent for interacting with the Sui blockchain.

#### Computer Automation Examples
- [Basic Computer Control](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/example-computer-actions.ts) - Control mouse and keyboard actions programmatically.
- [Browser Automation](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/example-browser-automation.ts) - Automate browser interactions and web navigation.
- [Terminal Command Execution](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/example-computer-bash.ts) - Execute terminal commands and process outputs.
- [Advanced Task Automation](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/example-advanced-automation.ts) - Complex automation with task management.
- [Bash Action Library](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/bash-actions.ts) - Library for executing bash commands and system operations.
- [Bash Session Implementation](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/bash.ts) - Implementation of a bash session for terminal interaction.
- [Automation Base Classes](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/base.ts) - Foundation classes for computer automation.
- [Computer Control Actions](https://github.com/daydreamsai/daydreams/blob/main/examples/computer-usage/computer-actions.ts) - Actions for mouse, keyboard, and screen control.

#### Deep Research
- [Research Module Entry Point](https://github.com/daydreamsai/daydreams/blob/main/examples/deep-research/index.ts) - Main entry point for the deep research capabilities.
- [Research Prompt Templates](https://github.com/daydreamsai/daydreams/blob/main/examples/deep-research/prompts.ts) - Specialized prompts for research tasks.
- [Research Core Implementation](https://github.com/daydreamsai/daydreams/blob/main/examples/deep-research/research.ts) - Core research functionality and algorithms.
- [Research Data Schemas](https://github.com/daydreamsai/daydreams/blob/main/examples/deep-research/schemas.ts) - Data structures for research information.

#### Integration Examples
- [Discord Bot](https://github.com/daydreamsai/daydreams/blob/main/examples/discord/example-discord.ts) - Discord bot with vector memory and research capabilities.
- [Telegram Integration](https://github.com/daydreamsai/daydreams/blob/main/examples/telegram/index.ts) - Telegram bot using Groq's LLM for conversations.
- [Twitter Bot](https://github.com/daydreamsai/daydreams/blob/main/examples/twitter/index.ts) - Twitter integration for automated interactions.

#### Gaming Examples
- [Gigaverse Game Integration](https://github.com/daydreamsai/daydreams/blob/main/examples/games/gigaverse/example-gigaverse.ts) - Integration with the Gigaverse game ecosystem.
- [Gigaverse UI Example](https://github.com/daydreamsai/daydreams/blob/main/examples/games/gigaverse/example-gigaverse-simple-ui.ts) - Simple UI implementation for Gigaverse.
- [Terminal UI for Games](https://github.com/daydreamsai/daydreams/blob/main/examples/games/gigaverse/simple-ui.ts) - Terminal-based UI for game interactions.

#### MCP (Model Context Protocol) Examples
- [MCP Agent Implementation](https://github.com/daydreamsai/daydreams/blob/main/examples/mcp/mcp-agent.ts) - Agent that connects to an MCP server.
- [MCP Server Example](https://github.com/daydreamsai/daydreams/blob/main/examples/mcp/mcp-server-example.mjs) - Server implementation with resource templates and tools.

#### Task Management Examples
- [Hierarchical Goal Planning](https://github.com/daydreamsai/daydreams/blob/main/examples/tasks/example-task.ts) - Advanced hierarchical goal planning system.
- [Eternum Game Agent](https://github.com/daydreamsai/daydreams/blob/main/examples/tasks/eternum.ts) - Specialized agent for the Eternum game ecosystem.

### Video Resources
- Still dreaming...

### Articles and Blogs
- [Daydreams Deep Dive: A Technical Review of the Next-Gen Onchain Agent](https://dev.to/bruce_f98f32568eeb89017f9/daydreams-deep-dive-a-technical-review-of-the-next-gen-onchain-agent-4o61) - A community post by [@LowCapLlama](https://x.com/LowCapLlama).

### Interviews and Podcasts
- **DeepSeek, AGI, Infra vs Agents, OS LLMs, Gaming x AI, DEFAI**  
  *Duration:* 58 minutes  
  [Listen here](https://x.com/ghost93_x/status/1883879826509222237)

- **Daydreams <> Fully Onchain Games**  
  *Duration:* 7 minutes  
  [Listen here](https://x.com/FOCGERS/status/1883790874582421743)

### Papers
- Still dreaming...

---

## Ecosystem

### Dapps
- Still dreaming...

### Community
- Still dreaming...

---

## Developer Resources

### Developer Tools
- [Pattern Analysis Agent](https://github.com/natefrog808/Pattern-Analysis-Agent) - A system combining advanced pattern analysis and image processing, built on the Daydreams framework. Features include time-series analysis, anomaly detection, financial analytics, and object recognition.
- [NEXUS-STREAM-AI](https://github.com/natefrog808/NEXUS-STREAM-AI) - An AI-powered real-time data orchestration and analytics system built on Daydreams and Irys datachain for intelligent processing and blockchain storage.

---

## Open-source Projects

### DeFi
- [Paradreams](https://github.com/milancermak/paradreams) - Proof-of-concept of a Daydreams powered trading agent connected to [Paradex](https://www.paradex.trade/).
- [DS-Agents](https://github.com/defi-space/ds-agents) - A multi-agent system enabling autonomous agents to interact with contracts, manage resources, and execute complex strategies independently.

### Gaming
- Still dreaming...

### Social
- Still dreaming...

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
