<p align="center">
  <br>
  <img width="800" src="./awesome-ai.jpg" alt="awesome-ai: A Curated Resource List">
  <br>
  <br>
</p>

## Awesome AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome AI tools, frameworks, plugins, and resources.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Resources](#resources)
  - [Official Resources](#official-resources)
  - [AI Platforms & Hubs](#ai-platforms--hubs)
  - [Curated Lists](#curated-lists)
  - [Learning & Courses](#learning--courses)
- [AI Coding](#ai-coding)
  - [Cloud Autonomous Coding Agents](#cloud-autonomous-coding-agents)
  - [Local Coding Agents & Assistants](#local-coding-agents--assistants)
  - [AI Code Editors](#ai-code-editors)
  - [Collaborative AI Coding](#collaborative-ai-coding)
- [AI Agent Frameworks](#ai-agent-frameworks)
  - [Orchestration & Workflows](#orchestration--workflows)
  - [Multi-Agent Systems](#multi-agent-systems)
- [Protocols & Standards](#protocols--standards)
- [AI Search](#ai-search)
  - [AI Search Engines](#ai-search-engines)
  - [AI Search APIs](#ai-search-apis)
- [AI Development & Observability](#ai-development--observability)
- [AI Model Training & Fine-Tuning](#ai-model-training--fine-tuning)
- [AI Infrastructure](#ai-infrastructure)
  - [Browser Infrastructure](#browser-infrastructure)
- [AI-Powered Content Creation](#ai-powered-content-creation)
  - [Video](#video)
- [Knowledge & Understanding](#knowledge--understanding)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## Resources

### Official Resources

- [Anthropic](https://www.anthropic.com/) - AI safety company and creator of Claude
- [Google DeepMind](https://deepmind.google/) - Google's AI research lab
- [OpenAI](https://openai.com/) - AI research and deployment company

### AI Platforms & Hubs

> Central platforms where the AI community **shares, discovers, and collaborates on models, datasets, and applications**. They serve as the ecosystem hubs — hosting pre-trained models, providing inference APIs, and enabling the community to build on each other's work.

- [Hugging Face](https://huggingface.co/) - The open-source AI community hub for sharing models, datasets, and Spaces — hosting 1M+ models with inference APIs, training tools, and collaborative workflows

### Curated Lists

> Community-maintained **collections of AI tools, libraries, and projects** organized by topic. Great starting points to discover what's available in specific AI domains.

- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - A curated collection of awesome LLM apps built with RAG and AI agents, using OpenAI, Anthropic, Google, and open-source models

### Learning & Courses

> High-quality **courses, tutorials, and educational resources** for learning AI, machine learning, and LLM development — from fundamentals to advanced topics.

- [Deeplearning.AI](https://www.deeplearning.ai/) - Andrew Ng's education platform offering courses on AI, deep learning, and LLMs — from beginner fundamentals to advanced specializations
- [MCP Course](https://huggingface.co/mcp-course) - Hugging Face's free course on the Model Context Protocol (MCP), teaching how to build and integrate MCP servers and clients for AI tool use

## AI Coding

### Cloud Autonomous Coding Agents

> Agents that run **asynchronously in the cloud**. Unlike traditional code assistants that autocomplete while you type, these agents spin up a virtual machine (sandbox), clone your repo, install dependencies, analyze context, create an action plan, and write code autonomously — delivering results as pull requests. You assign a task and come back later.

- [Jules](https://jules.google.com) - Google's autonomous AI coding agent powered by Gemini 2.5 Pro that creates cloud sandboxes, plans multi-step fixes, and submits PRs directly to your GitHub repo
- [Devin](https://devin.ai) - Autonomous AI software engineer by Cognition Labs that plans, codes, debugs, and deploys in its own cloud sandbox with shell, editor, and browser
- [GitHub Copilot Coding Agent](https://github.com/features/copilot) - GitHub's asynchronous cloud-based coding agent that autonomously completes tasks in background dev environments, opening PRs with built-in security scanning
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open-source (MIT) AI software engineering platform where autonomous agents write code, run commands, and browse the web in sandboxed containers, with native GitHub/GitLab/Slack integrations
- [Tembo](https://www.tembo.io) - Autonomous coding agent platform that automates development tasks like shipping code, reviewing PRs, and fixing bugs across Slack, Linear, and GitHub
- [Replit](https://replit.com) - Cloud AI agent platform that turns natural language prompts into full-stack applications with autonomous coding, testing, and one-click deployment — all in the browser

### Local Coding Agents & Assistants

> Agents that run **locally on your machine**, directly in your terminal or IDE. They have full access to your local filesystem, tools, and environment. You interact in real-time, iterating together — they read your code, run commands, edit files, and execute tasks while you stay in control.

- [Claude Code](https://www.anthropic.com/claude-code) - Anthropic's agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster through natural language — edits files, runs commands, and handles git workflows locally
- [Codex](https://github.com/openai/codex) - OpenAI's lightweight coding agent that runs in your terminal, connecting to OpenAI models to write and edit code, run commands, and iterate — with built-in sandboxing for safe execution

### AI Code Editors

> Full code editors (or editor forks) with **AI built into the core experience**. They go beyond plugins: the entire editing environment is designed around AI-powered code generation, multi-file editing, and codebase-aware chat. You write code alongside the AI in real-time.

- [Cursor](https://cursor.com) - AI-first code editor (VS Code fork) with codebase-aware chat, multi-file editing, and multi-model support (GPT, Claude, Gemini)

### Collaborative AI Coding

> Tools focused on **multiplayer AI-assisted development**. Multiple developers share an AI coding session in real-time, enabling pair programming and team collaboration with AI as a shared teammate.

- [Claude Duet](https://github.com/EliranG/claude-duet) - Real-time pair programming tool that lets two developers share a Claude Code session with end-to-end encryption for collaborative AI-assisted development

## AI Agent Frameworks

### Orchestration & Workflows

> Frameworks for **building stateful AI agents and multi-step workflows**. They provide the plumbing — state management, tool calling, branching logic, human-in-the-loop checkpoints, and durable execution — so you can focus on designing your agent's behavior rather than reinventing control flow.

- [LangGraph](https://github.com/langchain-ai/langgraph) - Low-level orchestration framework by LangChain for building stateful AI agents and multi-step workflows with durable execution, human-in-the-loop control, and streaming support

### Multi-Agent Systems

> Frameworks for **orchestrating teams of AI agents that collaborate on tasks**. Instead of one monolithic agent, you define specialized agents with distinct roles, tools, and goals — and the framework manages their communication, delegation, and coordination.

- [CrewAI](https://github.com/crewAIInc/crewAI) - Lean Python framework for orchestrating collaborative multi-agent systems with support for autonomous teams (Crews) and event-driven control flows (Flows)

## Protocols & Standards

> Open **protocols and specifications that define how AI systems communicate and interoperate**. These are not tools or products — they are standards that tools implement. They establish the shared language so that models, agents, and tools from different vendors can work together seamlessly.

- [MCP (Model Context Protocol)](https://modelcontextprotocol.io) - Open standard by Anthropic (Linux Foundation) providing a universal protocol for connecting AI models to external tools, data sources, and systems — the "USB-C for AI"
- [A2A (Agent-to-Agent Protocol)](https://github.com/a2aproject/A2A) - Open protocol by Google (Linux Foundation) enabling communication and interoperability between AI agents built on diverse frameworks across different organizations

## AI Search

### AI Search Engines

> AI-powered **search engines that understand natural language queries and synthesize answers** from multiple sources. Instead of returning a list of blue links, they read, analyze, and cite web content to deliver direct, conversational answers with verifiable references.

- [Perplexity](https://perplexity.ai) - AI-powered answer engine that searches the web in real-time to deliver accurate, conversational answers backed by cited and verifiable sources

### AI Search APIs

> **Search-as-a-service APIs designed for AI agents and LLM applications**. They handle web search, content extraction, and data retrieval through a single API call — so your AI agent can access live web data without building and maintaining its own scraping infrastructure.

- [Tavily](https://tavily.com) - Real-time search API purpose-built for AI agents, providing web search, content extraction, and crawling through a single secure interface optimized for LLM consumption

## AI Development & Observability

> Platforms for **monitoring, debugging, and improving LLM-powered applications**. They provide tracing, evaluations, prompt management, and usage metrics — the DevOps/observability layer for AI applications.

- [Langfuse](https://langfuse.com) - Open-source LLM engineering platform providing tracing, evaluations, prompt management, and metrics to debug and improve LLM applications
- [Entire.io](https://entire.io) - Developer platform that hooks into your Git workflow to capture AI agent sessions on every push, unifying code with its context and reasoning

## AI Model Training & Fine-Tuning

> Tools for **training, fine-tuning, and running AI models locally**. Instead of relying solely on API calls to cloud providers, these platforms let you customize models on your own hardware, optimizing for your specific use case, data, and cost constraints.

- [Unsloth](https://github.com/unslothai/unsloth) - Unified platform to run and fine-tune AI models (text, audio, vision, embeddings) locally with a web-based Studio UI and code-based Core library

## AI Infrastructure

### Browser Infrastructure

> **Headless browser infrastructure purpose-built for AI agents**. These services provide isolated browser sessions in the cloud so that AI agents can navigate the web, interact with pages, and extract data — handling CAPTCHAs, anti-bot detection, and session management automatically.

- [Steel](https://steel.dev) - Cloud browser infrastructure for AI agents providing isolated browser sessions with built-in anti-bot stealth and CAPTCHA-solving capabilities

## AI-Powered Content Creation

### Video

> Frameworks that let developers **create video programmatically using code** instead of traditional video editing software. Write components or scripts, and the framework renders real MP4/WebM videos — perfect for data-driven, templated, or AI-generated video content.

- [Remotion](https://remotion.dev) - React framework that lets developers create real MP4 videos programmatically by writing React components instead of using traditional video editing software

## Knowledge & Understanding

> Tools that **transform codebases and documents into navigable knowledge structures**. They analyze relationships, dependencies, and semantics to produce interactive graphs, visual dashboards, and queryable representations — helping you understand complex systems at a glance.

- [Understand Anything](https://github.com/Lum1104/Understand-Anything) - Plugin that turns any codebase into an interactive knowledge graph you can explore, search, and query via a visual dashboard

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdatea/zero/1.0/)
