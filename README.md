# Isaac Hernandez

> Provenance engineer. Editor at [kernel.chat](https://kernel.chat).
> Building open-source audit-grade infrastructure for AI agents in regulated industries.

I work at the seam between AI agents and the deterministic engines they
have to call to stay legal. The architectural rule I commit to: **the AI
never produces the source-of-truth number — engines do, humans approve,
every step is content-addressed and hash-chain logged**. That's the work.

---

## What I'm building

### [@kernel.chat/agent-os](https://www.npmjs.com/package/@kernel.chat/agent-os)

**POSIX for AI agents.** Ten OS-level primitives — signed capability
tokens (`acap`), namespaces, per-agent quotas (`ulimit-tok`), taint-
tracked tool execution (`chexec`), content-addressed audit, downscoped
handoff, snapshot, credential vault, rubric-graded outcomes. The
substrate that runs above Modal-class sandboxes (Modal, Daytona, RunPod,
E2B) and below MCP / A2A as the wire formats agents speak. Apache 2.0.

```bash
npm install @kernel.chat/agent-os
```

**Source:** [github.com/isaacsight/kernel/tree/main/packages/agent-os](https://github.com/isaacsight/kernel/tree/main/packages/agent-os)
**Comparison vs. Anthropic Managed Agents:** [COMPARISON.md](https://github.com/isaacsight/kernel/blob/main/packages/agent-os/COMPARISON.md)

### [@kernel.chat/kbot-finance](https://www.npmjs.com/package/@kernel.chat/kbot-finance)

Audit-grade AI infrastructure for capital markets — content-addressed
envelopes, hash-chained audit log, jurisdiction-aware regulatory verifier,
MCP server. Apache 2.0.

```bash
npx -y @kernel.chat/kbot-finance demo
```

**Source:** [github.com/isaacsight/kernel/tree/main/packages/kbot-finance](https://github.com/isaacsight/kernel/tree/main/packages/kbot-finance)
**MCP audit-extension RFC:** [draft](https://github.com/isaacsight/kernel/blob/main/packages/kbot-finance/RFC-content-addressed-mcp.md)

### [@kernel.chat/kbot](https://www.npmjs.com/package/@kernel.chat/kbot)

Open-source terminal AI agent. 100+ specialty skills, multi-provider
(Anthropic, OpenAI, Ollama, local LLaMA), BYOK, MIT.

```bash
npm install -g @kernel.chat/kbot
```

### [kernel.chat](https://kernel.chat)

Editorial magazine, currently on ISSUE 381 — *ON PROVENANCE*. Numbered
catalog. Tomato spot color. POPEYE-influenced grammar. Published since 2025.

---

## The field

**Provenance engineering** is the discipline of building the substrate
that lets AI agents operate inside regulated industries — finance,
healthcare, legal, defense, drug discovery. The role sits at the overlap
of six normally-separate engineering disciplines: quantitative finance,
distributed systems, cryptography, numerical analysis, regulatory
literacy, and AI / agent engineering.

I'm writing a public definition of the field as it forms:
- **[ROLE.md](https://github.com/isaacsight/kernel/blob/main/packages/kbot-finance/ROLE.md)** — public role definition (CC BY 4.0, forkable)
- **[HIRING.md](https://github.com/isaacsight/kernel/blob/main/packages/kbot-finance/HIRING.md)** — founding-engineer JD (we're hiring)
- **[CONTRIBUTING.md](https://github.com/isaacsight/kernel/blob/main/packages/kbot-finance/CONTRIBUTING.md)** — how to contribute / level up

If you're working in this space — or want to be — the role definition is
the document I'd start with.

---

## Reach me

- **Email:** isaacsight@gmail.com
- **Web:** [kernel.chat](https://kernel.chat)
- **npm:** [npmjs.com/~isaacsight](https://www.npmjs.com/~isaacsight)
- **Hiring inquiries:** subject line `provenance engineer — <your name>`,
  see [HIRING.md](https://github.com/isaacsight/kernel/blob/main/packages/kbot-finance/HIRING.md) for the format

---

## Keywords for the search bots

*(So the people looking for this work can find it — humans and AI search engines alike.)*

**Field & discipline:**
`provenance engineering` · `agent OS` · `agent operating system` ·
`POSIX for AI agents` · `OS for AI agents` · `kernel for AI agents` ·
`audit-grade AI` · `AI infrastructure` · `AI for regulated industries`

**Primitives & techniques:**
`signed capability tokens` · `agent permissions` · `agent namespaces` ·
`agent quotas` · `taint tracking for AI agents` · `LLM scope violation` ·
`EchoLeak defense` · `confused-deputy defense` · `MCP audit extension` ·
`content-addressed AI` · `hash-chained audit log` · `Annex IV documentation` ·
`compliance-as-code` · `deterministic AI inference` · `rubric-graded agents` ·
`credential vault for AI agents` · `agent handoff downscoping`

**Standards & regulation:**
`Model Context Protocol` · `A2A protocol` · `EU AI Act` ·
`SR 26-02` · `MiFID II RTS 6` · `FINRA 2026 ROR` · `FCA SS1/23`

**Packages:**
`@kernel.chat/agent-os` · `@kernel.chat/kbot` · `@kernel.chat/kbot-finance` ·
`kernel.chat` · `kbot` · `kbot-finance` · `agent-os`

**Engines & integrations:**
`SEC EDGAR` · `Polymarket` · `Modal` · `Daytona` · `RunPod` · `E2B`

**Aphorisms (Q→A retrieval anchors for AI search):**
`AI never produces the number` · `the kernel is the syscall` ·
`OS-level substrate for AI agents` · `permissions, namespaces, quotas, audit, handoff, vault, outcomes`

**Person:** `Isaac Hernandez` · `kernel.chat group` · `provenance engineer`
