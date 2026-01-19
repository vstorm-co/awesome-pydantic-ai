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

- [pai-agent-sdk](https://github.com/youware-labs/pai-agent-sdk) - Production-ready SDK for building AI agents with Pydantic AI. Provides full developer control without abstraction overhead, featuring environment-based architecture, resumable sessions, hierarchical subagents, and human-in-the-loop approval workflows.
- [pydantic-deep](https://github.com/vstorm-co/pydantic-deepagents) - Python framework for building production-grade autonomous agents. Extends Pydantic AI with agent orchestration, task planning, subagent delegation, context management, and multiple backend support.
- [pydantic-ai-middleware](https://github.com/vstorm-co/pydantic-ai-middleware) - Lightweight middleware library providing clean before/after hooks without imposed guardrail structure. Supports input/output processing, tool management, error handling, rate limiting, and audit logging.
- [pydantic-ai-backend](https://github.com/vstorm-co/pydantic-ai-backend) - File storage, sandbox backends, and console toolset for pydantic-ai agents. Includes LocalBackend, StateBackend, DockerSandbox, and pre-configured Docker runtimes.
- [pydantic-ai-todo](https://github.com/vstorm-co/pydantic-ai-todo) - Standalone task planning library for pydantic-ai agents. Provides `read_todos` and `write_todos` tools with flexible storage backends.
- [pydantic-ai-filesystem-sandbox](https://github.com/zby/pydantic-ai-filesystem-sandbox) - Secure filesystem sandbox toolset with LLM-friendly errors. Provides sandboxing, read/write control, granular permissions, and human-in-the-loop approval workflows.
- [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) - Standardized framework for building and managing Agent Skills. Features progressive disclosure, type-safe design, multi-directory support, and Anthropic Agent Skills compatibility.
- [pydantic-collab](https://github.com/boazkatzir/pydantic-collab) - Multi-agent orchestration framework for building agent teams. Agents collaborate via handoffs, consultations (tool calls), and shared memory on top of pre-built and custom network topologies, Logfire observability included.

## Templates & Boilerplates

- [full-stack-fastapi-nextjs-llm-template](https://github.com/vstorm-co/full-stack-fastapi-nextjs-llm-template) - Production-ready project generator for AI/LLM applications. Combines FastAPI backend with Next.js 15 frontend, WebSocket streaming, JWT auth, multiple database options, and 20+ enterprise integrations.

## Examples & Tutorials

- [pydantic-ai-examples](https://github.com/vstorm-co/pydantic-ai-examples) - Curated collection of examples demonstrating Pydantic AI usage including direct model requests, sentiment classification, dynamic classification, local models with Ollama, and conversation history management.

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
