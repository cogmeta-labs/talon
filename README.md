# Talon

**Context intelligence for Agentic Development** by [CogMeta](https://cogmeta.ai)

Talon is a context intelligence engine that sits between your codebase and your AI coding agent. It builds a structural graph of your code, scores files for relevance using multi-signal consensus, and delivers precise context before the agent starts working — reducing costs by 35%, turns by 49%, and context consumption by 55-80%.

## Install

```bash
pip install talon
```

Requires Python 3.10+.

## Quickstart

```bash
# 1. Authenticate
talon auth

# 2. Navigate to your project and initialise
cd your-project
talon init

# 3. Start coding — Talon is now active
claude
```

That's it. Talon operates transparently in the background via MCP. No configuration files, no infrastructure, no workflow changes.

## What it does

- **Multi-signal consensus scoring** — identifies the minimal set of files relevant to each task
- **Adaptive response routing** — calibrates depth and token budget to query complexity
- **Behavioural guardrails** — detects and prevents waste patterns (excessive reads, unbatched edits, test spirals)

## Supported languages

Python, TypeScript, JavaScript, Go, Rust, Java, C++, C#, Ruby, PHP, Swift, Kotlin, and more. Multi-language repositories are fully supported.

## How it works

Talon integrates with Claude Code through the [Model Context Protocol (MCP)](https://modelcontextprotocol.io). The local MCP server runs on your machine — your source code never leaves your environment.

## Links

- [Documentation & Quickstart](https://cogmeta.ai/quickstart)
- [How It Works](https://cogmeta.ai/howitworks)
- [Evidence & Benchmarks](https://cogmeta.ai/research)
- [Support](https://cogmeta.ai/support)

## License

Apache-2.0 — see [LICENSE](LICENSE)
