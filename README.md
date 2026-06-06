# Awesome Pydantic AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> An opinionated list of awesome Pydantic AI frameworks, libraries, software and resources.

[Pydantic AI](https://ai.pydantic.dev/) is a Python agent framework designed to make it easier to build production-grade applications with Generative AI. It brings the "FastAPI feeling" to AI development with type safety, dependency injection, and structured outputs.

## Contents

- [Official Resources](#official-resources)
- [Frameworks & Libraries](#frameworks--libraries)
- [Templates & Boilerplates](#templates--boilerplates)
- [Examples & Tutorials](#examples--tutorials)
- [Observability](#observability)
- [Articles & Blog Posts](#articles--blog-posts)
- [Case Studies](#case-studies)
- [Contributing](#contributing)

## Official Resources

- [Pydantic AI Documentation](https://ai.pydantic.dev/) - Official documentation with guides, API reference, and examples.
- [Pydantic AI Repository](https://github.com/pydantic/pydantic-ai) - Official GitHub repository. Agent framework with model-agnostic architecture, type safety, dependency injection, tool integration, and structured outputs.

## Frameworks & Libraries

- [pai-agent-sdk](https://github.com/youware-labs/pai-agent-sdk) - Application framework for building AI agents with Pydantic AI. Provides full developer control without abstraction overhead, featuring environment-based architecture, resumable sessions, hierarchical subagents, and human-in-the-loop approval workflows.
- [pydantic-deep](https://github.com/vstorm-co/pydantic-deepagents) - Python framework for building production-grade autonomous agents. Extends Pydantic AI with agent orchestration, task planning, subagent delegation, context management, and multiple backend support.
- [pydantic-ai-middleware](https://github.com/vstorm-co/pydantic-ai-middleware) - Lightweight middleware library providing clean before/after hooks without imposed guardrail structure. Supports input/output processing, tool management, error handling, rate limiting, and audit logging.
- [pydantic-ai-backend](https://github.com/vstorm-co/pydantic-ai-backend) - File storage, sandbox backends, and console toolset for pydantic-ai agents. Includes LocalBackend, StateBackend, DockerSandbox, and pre-configured Docker runtimes.
- [pydantic-ai-todo](https://github.com/vstorm-co/pydantic-ai-todo) - Standalone task planning library for pydantic-ai agents. Provides `read_todos` and `write_todos` tools with flexible storage backends.
- [subagents-pydantic-ai](https://github.com/vstorm-co/subagents-pydantic-ai) - Multi-agent orchestration library with dual-mode execution (sync/async), dynamic agent creation, and parent-child communication via `ask_parent` tool.
- [summarization-pydantic-ai](https://github.com/vstorm-co/summarization-pydantic-ai) - Automatic conversation summarization and context management. Provides `SummarizationProcessor` for LLM-based summaries and `SlidingWindowProcessor` for zero-cost message trimming.
- [pydantic-ai-filesystem-sandbox](https://github.com/zby/pydantic-ai-filesystem-sandbox) - Secure filesystem sandbox toolset with LLM-friendly errors. Provides sandboxing, read/write control, granular permissions, and human-in-the-loop approval workflows.
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) - Standardized framework for building and managing Agent Skills. Features progressive disclosure, type-safe design, multi-directory support, and Anthropic Agent Skills compatibility.
- [pydantic-ai-toolguard](https://github.com/stevenkozeniesky02/pydantic-ai-toolguard) - Deny-first tool authorization capability for pydantic-ai agents. Implements glob-based permission rules, parameter conditions, schedule windows, rate limiting, approval workflows, and append-only audit logging. Built on the AgentsID permission specification.
- [pydantic-collab](https://github.com/boazkatzir/pydantic-collab) - Multi-agent orchestration framework for building agent teams. Agents collaborate via handoffs, consultations (tool calls), and shared memory on top of pre-built and custom network topologies, Logfire observability included.
- [semantix-ai](https://github.com/labrat-akhona/semantix-ai) - Semantic output validation for Pydantic AI agents. Validates that LLM outputs match natural-language intents using local NLI inference (~15ms, no API key). Integrates with `output_validator` and `ModelRetry` for automatic self-correction.
- [pydantic-ai-ejentum](https://github.com/ejentum/pydantic-ai-ejentum) - PydanticAI Toolset wrapping the Ejentum Reasoning Harness. `EjentumToolset` subclasses `FunctionToolset` and registers four agent-callable tools (`harness_reasoning`, `harness_code`, `harness_anti_deception`, `harness_memory`). Each call returns a structured cognitive scaffold (named failure pattern, executable procedure, suppression vectors, falsification test) the model reads internally to shape its next response.

- [twzrd-agent-intel](https://github.com/twzrd-sol/twzrd-agent-intel) - Trust scoring and x402 payment verification MCP server for Pydantic AI agents operating on Solana. Exposes `resolve_agent`, `score_agent`, `preflight_check`, `verify_trust_receipt`, and `get_trust_receipt` tools via streamable-http. Zero-install: `{"mcpServers": {"twzrd-agent-intel": {"url": "https://intel.twzrd.xyz/mcp"}}}`.

## Templates & Boilerplates

- [full-stack-fastapi-nextjs-llm-template](https://github.com/vstorm-co/full-stack-fastapi-nextjs-llm-template) - Production-ready project generator for AI/LLM applications. Combines FastAPI backend with Next.js 15 frontend, WebSocket streaming, JWT auth, multiple database options, and 20+ enterprise integrations.

## Examples & Tutorials

- [pydantic-ai-examples](https://github.com/vstorm-co/pydantic-ai-examples) - Curated collection of examples demonstrating Pydantic AI usage including direct model requests, sentiment classification, dynamic classification, local models with Ollama, and conversation history management.
- [pydantic-ai-rlm](https://github.com/vstorm-co/pydantic-ai-rlm) - Recursive Language Models with Pydantic AI.
- [Pydantic AI Walkthrough](https://colab.research.google.com/drive/12oZEM098SG2bYq0D1UGyW9YHKEbEkSNi?usp=sharing) - Interactive notebook covering agents, structured outputs, tool use, dependency injection, and building a Gradio chat UI with Pydantic AI. Created by [Nicolai Thomsen](https://www.linkedin.com/feed/update/urn:li:activity:7439395531006693376/?actorCompanyId=93077574).
- [Pydantic AI: Build Type-Safe LLM Agents in Python](https://realpython.com/pydantic-ai/) - RealPython tutorial on creating language model agents with validated structured outputs, function calling, and dependency injection.

## Observability

- [Pydantic Logfire](https://github.com/pydantic/logfire) - Observability platform for Python applications built by the Pydantic team. Provides logging, tracing, metrics with SQL query interface, OpenTelemetry foundation, and native Pydantic integration.

## Articles & Blog Posts

- [Building Production-Grade AI Agents: How We Brought Deep Agent Patterns to Pydantic](https://vstorm.co/agentic-ai/building-production-grade-ai-agents-how-we-brought-deep-agent-patterns-to-pydantic/) - Introduction to pydantic-deep framework and deep agent architectural patterns for production AI systems.
- [Production-Ready Template for AI/LLM Applications: FastAPI + Next.js + 20+ Integrations](https://vstorm.co/agentic-ai/production-ready-template-for-ai-llm-applications-fastapi-next-js-20-integrations/) - Guide to fastapi-fullstack CLI tool that generates complete full-stack AI applications with enterprise integrations.

## Case Studies

- [Mixam: AI Agent for Order Recommendation](https://pydantic.dev/case-studies/mixam) - How Mixam, a global self-publishing company, used Pydantic AI to create an AI agent that helps customers navigate complex printing specifications.
- [Sophos: Unified Observability with Logfire](https://pydantic.dev/case-studies/sophos) - How Sophos implemented Pydantic Logfire for unified observability across their AI-powered security solutions, achieving end-to-end visibility and proactive issue detection.
- [Boosted.ai: Monitoring AI Investment Research](https://pydantic.dev/case-studies/boostedai) - How Boosted.ai uses Pydantic Logfire to monitor 50,000+ concurrent AI workflows processing billions of tokens daily, reducing issue diagnosis time significantly.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](LICENSE).
