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
  - [Local Coding Agents (Terminal / CLI)](#local-coding-agents-terminal--cli)
  - [AI Code Editors](#ai-code-editors)
  - [AI Desktop Assistants](#ai-desktop-assistants)
  - [AI Code Assistants (IDE Plugins)](#ai-code-assistants-ide-plugins)
  - [AI Agent SDKs](#ai-agent-sdks)
  - [AI App Builders (Vibe Coding)](#ai-app-builders-vibe-coding)
  - [Collaborative AI Coding](#collaborative-ai-coding)
- [AI Agent Frameworks](#ai-agent-frameworks)
  - [Orchestration & Workflows](#orchestration--workflows)
  - [Multi-Agent Systems](#multi-agent-systems)
  - [Autonomous Agent Platforms](#autonomous-agent-platforms)
  - [No-Code AI Agent Builders](#no-code-ai-agent-builders)
- [Workflow Automation](#workflow-automation)
  - [Visual Workflow Builders (AI-Native)](#visual-workflow-builders-ai-native)
  - [General Automation Platforms](#general-automation-platforms)
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
- [AI-Powered Data & Analytics](#ai-powered-data--analytics)
- [Enterprise AI Platforms](#enterprise-ai-platforms)
- [AI Knowledge Management](#ai-knowledge-management)

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

- [Devin](https://devin.ai) - Autonomous AI software engineer by Cognition Labs that plans, codes, debugs, and deploys in its own cloud sandbox with shell, editor, and browser
- [Jules](https://jules.google.com) - Google's autonomous AI coding agent powered by Gemini 2.5 Pro that creates cloud sandboxes, plans multi-step fixes, and submits PRs directly to your GitHub repo
- [GitHub Copilot Coding Agent](https://github.com/features/copilot) - GitHub's asynchronous cloud-based coding agent that autonomously completes tasks in background dev environments, opening PRs with built-in security scanning
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open-source (MIT) AI software engineering platform where autonomous agents write code, run commands, and browse the web in sandboxed containers, with native GitHub/GitLab/Slack integrations
- [Replit Agent](https://replit.com) - Cloud AI agent platform that turns natural language prompts into full-stack applications with autonomous coding, testing, and one-click deployment — all in the browser
- [Tembo](https://www.tembo.io) - Autonomous coding agent platform that automates development tasks like shipping code, reviewing PRs, and fixing bugs across Slack, Linear, and GitHub

### Local Coding Agents (Terminal / CLI)

> Agents that run **locally on your machine**, directly in your terminal. They have full access to your local filesystem, tools, and environment. You interact in real-time, iterating together — they read your code, run commands, edit files, and execute tasks while you stay in control of your own machine.

- [Claude Code](https://www.anthropic.com/claude-code) - Anthropic's agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster through natural language — edits files, runs commands, and handles git workflows locally
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source CLI agent that brings Gemini models (1M token context) to your terminal with built-in tools and MCP support
- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI's lightweight coding agent that runs in your terminal, connecting to OpenAI models to write and edit code, run commands, and iterate — with built-in sandboxing for safe execution
- [GitHub Copilot CLI](https://github.com/github/copilot-cli) - GitHub's terminal-native agentic coding assistant that can plan tasks, edit files, run tests, and iterate — with MCP and autopilot mode
- [OpenCode](https://github.com/anomalyco/opencode) - Open-source terminal-based AI coding agent with TUI, multi-provider support (Claude, OpenAI, Gemini, local models), and MCP integration

### AI Desktop Assistants

> **Native desktop applications** that bring AI capabilities to your OS with a rich graphical interface. They provide chat, file handling, desktop extensions, and deep system integration — offering a more visual and accessible experience than terminal-based tools.

- [Claude Desktop](https://claude.com/download) - Anthropic's native desktop app for macOS and Windows providing chat, Claude Cowork, and Claude Code in a unified interface with desktop extensions and MCP support

### AI Code Editors

> Full code editors (or editor forks) with **AI built into the core experience**. They go beyond plugins: the entire editing environment is designed around AI-powered code generation, multi-file editing, and codebase-aware chat. You write code alongside the AI in real-time.

- [Cursor](https://cursor.com) - AI-first code editor (VS Code fork) with codebase-aware chat, multi-file editing, and multi-model support (GPT, Claude, Gemini)
- [Windsurf](https://windsurf.com) - AI-powered code editor with deep codebase understanding, acquired by Cognition AI (makers of Devin) in 2025

### AI Code Assistants (IDE Plugins)

> AI-powered **plugins and extensions that enhance existing code editors** like VS Code, JetBrains, and Xcode. They integrate into your current workflow, providing autocomplete, inline suggestions, chat, and code explanations — without requiring you to switch editors.

- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer that provides autocomplete suggestions, chat, and multi-file edits across VS Code, JetBrains, Xcode, and more
- [Pixel Agents](https://github.com/pablodelucca/pixel-agents) - VS Code extension that visualizes AI agents as animated pixel-art characters in a virtual office, reflecting their real-time activities (coding, reading files, idle)

### AI Agent SDKs

> **Software development kits for building custom AI agents programmatically**. They expose the same capabilities used by commercial AI coding tools — file I/O, shell execution, code editing, web browsing — as composable building blocks for developers to create their own autonomous agents.

- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) - Anthropic's SDK for programmatically building autonomous AI agents with Claude Code's built-in tools for file reading, command execution, and code editing — available in Python and TypeScript

### AI App Builders (Vibe Coding)

> Platforms where you **describe an app in natural language and the AI builds it end-to-end** — frontend, backend, database, and deployment. Often called "vibe coding": you focus on the what, the AI handles the how. Ideal for rapid prototyping, MVPs, and non-technical creators.

- [Bolt.new](https://bolt.new) - AI-powered web app builder that creates, runs, and deploys full-stack applications directly from natural language prompts in the browser
- [Lovable](https://lovable.dev) - AI-powered full-stack app builder that generates production-ready web applications from conversational prompts with integrated deployment
- [v0](https://v0.dev) - Vercel's AI-powered UI generation tool that creates React and Next.js components and full-stack web apps from text prompts with one-click deployment

### Collaborative AI Coding

> Tools focused on **multiplayer AI-assisted development**. Multiple developers share an AI coding session in real-time, enabling pair programming and team collaboration with AI as a shared teammate.

- [Claude Duet](https://github.com/EliranG/claude-duet) - Real-time pair programming tool that lets two developers share a Claude Code session with end-to-end encryption for collaborative AI-assisted development

## AI Agent Frameworks

### Orchestration & Workflows

> Frameworks for **building stateful AI agents and multi-step workflows**. They provide the plumbing — state management, tool calling, branching logic, human-in-the-loop checkpoints, and durable execution — so you can focus on designing your agent's behavior rather than reinventing control flow.

- [LangGraph](https://github.com/langchain-ai/langgraph) - Low-level orchestration framework by LangChain for building stateful AI agents and multi-step workflows with durable execution, human-in-the-loop control, and streaming support
- [Dify](https://dify.ai) - Open-source LLM app development platform for building agentic workflows, RAG pipelines, and AI-powered applications with a visual orchestration interface

### Multi-Agent Systems

> Frameworks for **orchestrating teams of AI agents that collaborate on tasks**. Instead of one monolithic agent, you define specialized agents with distinct roles, tools, and goals — and the framework manages their communication, delegation, and coordination.

- [CrewAI](https://github.com/crewAIInc/crewAI) - Lean Python framework for orchestrating collaborative multi-agent systems with support for autonomous teams (Crews) and event-driven control flows (Flows)
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Open-source platform for creating, deploying, and managing continuous AI agents that automate complex multi-step workflows autonomously
- [OpenClaw](https://openclaw.ai/) - Open-source autonomous AI agent framework that connects LLMs to apps, browsers, and system tools to execute real tasks on your computer

### Autonomous Agent Platforms

> Platforms for **deploying AI agents that handle real-world business tasks** — sales outreach, customer support, scheduling, operations. These are not developer frameworks; they provide ready-to-use agents you configure for specific business functions.

- [Lindy AI](https://www.lindy.ai) - AI assistant platform that builds and deploys no-code AI agents to automate workflows across email, calendar, meetings, and integrations
- [Relevance AI](https://www.relevanceai.com) - Platform for building and deploying autonomous AI agents that handle sales, marketing, and operations tasks without code

### No-Code AI Agent Builders

> **Visual drag-and-drop interfaces for building LLM-powered agents and workflows** without writing code. Connect models, tools, and data sources by drawing flows on a canvas — ideal for rapid prototyping and non-developer use cases.

- [Flowise](https://github.com/FlowiseAI/Flowise) - Open-source drag-and-drop UI for building LLM-powered agents and workflows visually, built on LangChain
- [LangFlow](https://github.com/langflow-ai/langflow) - Open-source low-code visual builder for creating multi-agent and RAG applications, model- and database-agnostic
- [Draft'n Run](https://draftnrun.com) - Open-source no-code studio for designing, deploying, and monitoring production-ready AI workflows with a visual drag-and-drop interface

## Workflow Automation

### Visual Workflow Builders (AI-Native)

> Automation platforms with **native AI capabilities built in** — not just traditional integrations, but first-class support for LLMs, AI agents, and intelligent processing within automation flows.

- [n8n](https://github.com/n8n-io/n8n) - Fair-code workflow automation platform with native AI capabilities, visual builder, custom code support, and 400+ integrations
- [Pipedream](https://github.com/PipedreamHQ/pipedream) - Developer-first API automation platform with custom code support (JS/Python/Go/Bash), serverless execution, and 2,700+ integrations

### General Automation Platforms

> Established **no-code/low-code automation platforms** that have added AI capabilities. They connect thousands of apps and now offer AI agents, chatbots, and intelligent automation as part of their workflow toolkit.

- [Zapier](https://zapier.com) - Automation platform connecting 8,000+ apps with AI agents, chatbots, and MCP support for building workflows in plain language
- [Make](https://www.make.com) - Visual no-code automation platform for building and scaling AI-powered workflows with 400+ app integrations

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

## AI-Powered Data & Analytics

> AI assistants that let **business users query data using natural language** instead of writing SQL. They translate plain English questions into queries, execute them against your data warehouse, and return results as tables, charts, or summaries — democratizing data access across the organization.

- [Databricks AI/BI Genie](https://www.databricks.com/product/business-intelligence/genie) - AI-powered natural-language-to-SQL assistant that lets business users ask questions in plain English and get instant answers, tables, and visualizations from their data warehouse

## Enterprise AI Platforms

> **End-to-end AI platforms designed for enterprise teams and large organizations**. They combine multiple AI agents, LLM orchestration, and workflow automation into a unified platform — focusing on team productivity, governance, security, and scale across the entire software development lifecycle.

- [CI&T Flow](https://flow.ciandt.com) - Enterprise-grade multi-LLM AI platform with integrated agents (Chat, Steps, Coder, Ops) that accelerates software development workflows and team productivity across the build cycle
- [NemoClaw](https://www.nvidia.com/en-us/ai/nemoclaw/) - NVIDIA's open-source platform that adds enterprise-grade security, privacy guardrails, and policy controls on top of OpenClaw for deploying safe AI agents at scale

## AI Knowledge Management

> Tools that **transform information into navigable knowledge structures**. They analyze relationships, organize notes intelligently, and surface relevant context — helping you understand complex systems and retrieve knowledge effortlessly.

- [Understand Anything](https://github.com/Lum1104/Understand-Anything) - Plugin that turns any codebase into an interactive knowledge graph you can explore, search, and query via a visual dashboard
- [Mem.ai](https://get.mem.ai) - AI-powered note-taking and knowledge management tool that automatically organizes, links, and surfaces relevant notes using AI

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdatea/zero/1.0/)
