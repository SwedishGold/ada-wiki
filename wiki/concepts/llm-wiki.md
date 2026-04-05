---
type: concept
created: 2026-04-05
tags: [knowledge-base, ai, wiki, karpathy]
---

# LLM Wiki

## Definition
A pattern for building personal knowledge bases where an LLM incrementally builds and maintains a persistent wiki — a structured, interlinked collection of markdown files.

## Core Principles

1. **Persistent compounding** - Wiki is a persistent artifact that keeps growing
2. **LLM does bookkeeping** - Humans curate sources, LLM maintains structure
3. **Three layers** - Raw sources → Wiki → Schema

## Three Layers

| Layer | Description |
|-------|-------------|
| Raw sources | Immutable source documents |
| The Wiki | LLM-generated markdown files |
| The Schema | Configuration telling LLM conventions |

## Operations

- **Ingest** - LLM reads new source, updates wiki
- **Query** - LLM searches wiki, synthesizes answer
- **Lint** - Health check for contradictions, orphans

## Quote

> "The tedious part of maintaining a knowledge base is not the reading or the thinking — it's the bookkeeping."

## Source
- [Karpathy's Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)
- Stars: 4,273
- Forks: 862

## Related
- [[karpathy]]
- [[knowledge-management]]
- [[obsidian]]
