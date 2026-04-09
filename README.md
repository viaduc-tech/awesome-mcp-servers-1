[![ไทย](https://img.shields.io/badge/Thai-Click-blue)](README-th.md)
[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點擊查看-orange)](README-zh_TW.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-青)](README-ja.md)
[![한국어](https://img.shields.io/badge/한국어-클릭-yellow)](README-ko.md)
[![Português Brasileiro](https://img.shields.io/badge/Português_Brasileiro-Clique-green)](README-pt_BR.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

> [!IMPORTANT]
> Read [The State of MCP in 2025](https://glama.ai/blog/2025-12-07-the-state-of-mcp-in-2025) report.

> [!IMPORTANT]
> [Awesome MCP Servers](https://glama.ai/mcp/servers) web directory.

A curated list of awesome Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Clients](#clients)
* [Tutorials](#tutorials)
* [Community](#community)
* [Legend](#legend)
* [Server Implementations](#server-implementations)
* [Frameworks](#frameworks)
* [Tips & Tricks](#tips-and-tricks)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

## Clients

Checkout [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/) and [glama.ai/mcp/clients](https://glama.ai/mcp/clients).

> [!TIP]
> [Glama Chat](https://glama.ai/chat) is a multi-modal AI client with MCP support & [AI gateway](https://glama.ai/gateway).

## Tutorials

* [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legend

* 🎖️ – official implementation
* programming language
  * 🐍 – Python codebase
  * 📇 – TypeScript (or JavaScript) codebase
  * 🏎️ – Go codebase
  * 🦀 – Rust codebase
  * #️⃣ - C# Codebase
  * ☕ - Java codebase
  * 🌊 – C/C++ codebase
  * 💎 - Ruby codebase

* scope
  * ☁️ - Cloud Service
  * 🏠 - Local Service
  * 📟 - Embedded Systems
* operating system
  * 🍎 – For macOS
  * 🪟 – For Windows
  * 🐧 - For Linux

> [!NOTE]
> Confused about Local 🏠 vs Cloud ☁️?
> * Use local when MCP server is talking to a locally installed software, e.g. taking control over Chrome browser.
> * Use cloud when MCP server is talking to remote APIs, e.g. weather API.

## Server Implementations

> [!NOTE]
> We now have a [web-based directory](https://glama.ai/mcp/servers) that is synced with the repository.

* 🔗 - [Aggregators](#aggregators)
* 🎨 - [Art & Culture](#art-and-culture)
* 📐 - [Architecture & Design](#architecture-and-design)
* 📂 - [Browser Automation](#browser-automation)
* 🧬 - [Biology Medicine and Bioinformatics](#bio)
* ☁️ - [Cloud Platforms](#cloud-platforms)
* 👨‍💻 - [Code Execution](#code-execution)
* 🤖 - [Coding Agents](#coding-agents)
* 🖥️ - [Command Line](#command-line)
* 💬 - [Communication](#communication)
* 👤 - [Customer Data Platforms](#customer-data-platforms)
* 🗄️ - [Databases](#databases)
* 📊 - [Data Platforms](#data-platforms)
* 🚚 - [Delivery](#delivery)
* 🛠️ - [Developer Tools](#developer-tools)
* 🧮 - [Data Science Tools](#data-science-tools)
* 📊 - [Data Visualization](#data-visualization)
* 📟 - [Embedded system](#embedded-system)
* 🎓 - [Education](#education)
* 🛒 - [E-Commerce](#e-commerce)
* 🌳 - [Environment & Nature](#environment-and-nature)
* 📂 - [File Systems](#file-systems)
* 💰 - [Finance & Fintech](#finance--fintech)
* 🎮 - [Gaming](#gaming)
* 🏠 - [Home Automation](#home-automation)
* 🧠 - [Knowledge & Memory](#knowledge--memory)
* ⚖️ - [Legal](#legal)
* 🗺️ - [Location Services](#location-services)
* 🎯 - [Marketing](#marketing)
* 📊 - [Monitoring](#monitoring)
* 🎥 - [Multimedia Process](#multimedia-process)
* 📋 - [Product Management](#product-management)
* 🏠 - [Real Estate](#real-estate)
* 🔬 - [Research](#research)
* 🔎 - [Search & Data Extraction](#search)
* 🔒 - [Security](#security)
* 🌐 - [Social Media](#social-media)
* 🏃 - [Sports](#sports)
* 🎧 - [Support & Service Management](#support-and-service-management)
* 🌎 - [Translation Services](#translation-services)
* 🎧 - [Text-to-Speech](#text-to-speech)
* 🚆 - [Travel & Transportation](#travel-and-transportation)
* 🔄 - [Version Control](#version-control)
* 🏢 - [Workplace & Productivity](#workplace-and-productivity)
* 🛠️ - [Other Tools and Integrations](#other-tools-and-integrations)


### 🔗 <a name="aggregators"></a>Aggregators

Servers for accessing many apps and tools through a single MCP server.

- [1mcp/agent](https://github.com/1mcp-app/agent) 📇 ☁️ 🏠 🍎 🪟 🐧 - A unified Model Context Protocol server implementation that aggregates multiple MCP servers into one.
- [tadas-github/a2asearch-mcp](https://github.com/tadas-github/a2asearch-mcp) [![tadas-github/a2asearch-mcp MCP server](https://glama.ai/mcp/servers/tadas-github/a2asearch-mcp/badges/score.svg)](https://glama.ai/mcp/servers/tadas-github/a2asearch-mcp) 📇 ☁️ - MCP server to search 4,800+ MCP servers, AI agents, CLI tools and agent skills. Install: `npx -y a2asearch-mcp`. Ask Claude: "Find MCP servers for database access". Free, no auth required.
- [Aganium/agenium](https://github.com/Aganium/agenium) 📇 ☁️ 🍎 🪟 🐧 - Bridge any MCP server to the agent:// network — DNS-like identity, discovery, and trust for AI agents. Makes your tools discoverable and callable by other agents via `agent://` URIs with mTLS, trust scores, and capability search.
- [espadaw/Agent47](https://github.com/espadaw/Agent47) 📇 ☁️ - Unified job aggregator for AI agents across 9+ platforms (x402, RentAHuman, Virtuals, etc).
- [AgentHotspot](https://github.com/AgentHotspot/agenthotspot-mcp) 🐍 ☁️ 🏠 🍎 🪟 🐧 - Search, integrate and monetize MCP connectors on the AgentHotspot MCP marketplace
- [Work90210/APIFold](https://github.com/Work90210/APIFold) [![Work90210/APIFold MCP server](https://glama.ai/mcp/servers/Work90210/APIFold/badges/score.svg)](https://glama.ai/mcp/servers/Work90210/APIFold) 📇 ☁️ - Turn any REST API into a hosted MCP server. 18 free public servers (GitHub, Stripe, Slack, OpenAI, Notion, and more) — no setup required, bring your own API key.
- [rhein1/agoragentic-integrations](https://github.com/rhein1/agoragentic-integrations) [![agoragentic-integrations MCP server](https://glama.ai/mcp/servers/@rhein1/agoragentic-integrations/badges/score.svg)](https://glama.ai/mcp/servers/@rhein1/agoragentic-integrations) 📇 ☁️ - Agent-to-agent marketplace where AI agents discover, invoke, and pay for services from other agents using USDC on Base L2.
- [arikusi/deepseek-mcp-server](https://github.com/arikusi/deepseek-mcp-server) [![deepseek-mcp-server MCP server](https://glama.ai/mcp/servers/arikusi/deepseek-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/arikusi/deepseek-mcp-server) 📇 ☁️ 🍎 🪟 🐧 - MCP server for DeepSeek AI with chat, reasoning, multi-turn sessions, function calling, thinking mode, and cost tracking.
- [ariekogan/ateam-mcp](https://github.com/ariekogan/ateam-mcp) 📇 ☁️ 🏠 🍎 🪟 🐧 - Build, validate, and deploy multi-agent AI solutions on the ADAS platform. Design skills with tools, manage solution lifecycle, and connect from any AI environment via stdio or HTTP.
- [askbudi/roundtable](https://github.com/askbudi/roundtable) 📇 ☁️ 🏠 🍎 🪟 🐧 - Meta-MCP server that unifies multiple AI coding assistants (Codex, Claude Code, Cursor, Gemini) through intelligent auto-discovery and standardized MCP interface, providing zero-configuration access to the entire AI coding ecosystem.
- [blockrunai/blockrun-mcp](https://github.com/blockrunai/blockrun-mcp) 📇 ☁️ 🍎 🪟 🐧 - Access 30+ AI models (GPT-5, Claude, Gemini, Grok, DeepSeek) without API keys. Pay-per-use via x402 micropayments with USDC on Base.
- [Data-Everything/mcp-server-templates](https://github.com/Data-Everything/mcp-server-templates) 📇 🏠 🍎 🪟 🐧 - One server. All tools. A unified MCP platform that connects many apps, tools, and services behind one powerful interface—ideal for local devs or production agents.
- [depwire/depwire](https://github.com/depwire/depwire) [![depwire/depwire MCP server](https://glama.ai/mcp/servers/depwire/depwire/badges/score.svg)](https://glama.ai/mcp/servers/depwire/depwire) 📇 🐍 🏎️ 🦀 🌊 🏠 - Dependency graph + 15 MCP tools for AI coding assistants. Parses TypeScript, JavaScript, Python, Go, Rust, and C. Arc diagram visualization, health scoring, dead code detection, and temporal graph.
- [duaraghav8/MCPJungle](https://github.com/duaraghav8/MCPJungle) 🏎️ 🏠 - Self-hosted MCP Server registry for enterprise AI Agents
- [edgarriba/prolink](https://github.com/edgarriba/prolink) 🐍 ☁️ 🏠 🍎 🪟 🐧 - Agent-to-agent marketplace middleware — MCP-native discovery, negotiation, and transaction between AI agents
- [entire-vc/evc-spark-mcp](https://github.com/entire-vc/evc-spark-mcp) [![evc-spark-mcp MCP server](https://glama.ai/mcp/servers/entire-vc/evc-spark-mcp/badges/score.svg)](https://glama.ai/mcp/servers/entire-vc/evc-spark-mcp) 📇 ☁️ 🏠 🍎 🪟 🐧 - Search and discover AI agents, skills, prompts, bundles and MCP connectors from a curated catalog of 4500+ assets.
- [gorosun/unified-diff-mcp](https://github.com/gorosun/unified-diff-mcp) 📇 🏠 - Generate and visualize unified diff comparisons with beautiful HTML/PNG output, supporting side-by-side and line-by-line views for filesystem dry-run integration