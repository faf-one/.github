# FAF

**Persistent project context for the AI era.**

A small YAML file of a project's facts (its stack, goal and who it's for) that any AI reads first. Three IANA-registered formats:

| Format | Media type | Layer |
|---|---|---|
| `.faf` | [`application/vnd.faf+yaml`](https://www.iana.org/assignments/media-types/application/vnd.faf+yaml) | Foundational Context Layer |
| `.fafm` | [`application/vnd.fafm+yaml`](https://www.iana.org/assignments/media-types/application/vnd.fafm+yaml) | Voice Memory Layer |
| `.fafa` | [`application/vnd.fafa+yaml`](https://www.iana.org/assignments/media-types/application/vnd.fafa+yaml) | Agent Card / Agentic Layer |

IETF Internet-Drafts: [draft-wolfe-faf-format](https://datatracker.ietf.org/doc/draft-wolfe-faf-format/) · [draft-wolfe-faf-agent](https://datatracker.ietf.org/doc/draft-wolfe-faf-agent/) · JSON Schemas: [faf](https://faf.one/schemas/faf.schema.json) · [fafm](https://faf.one/schemas/fafm.schema.json) · [fafa](https://faf.one/schemas/fafa.schema.json)

## Start here

```bash
npx faf-cli init     # write project.faf from your repo
npx faf-cli go       # answer the goal and six W's, one question at a time
```

Or paste a public repo at **[context.faf.one](https://context.faf.one)**.

## Built on .faf

| | |
|---|---|
| **CLI** | [faf-cli](https://www.npmjs.com/package/faf-cli) · `brew install wolfe-jam/faf/faf-cli` |
| **MCP servers** | Claude [claude-faf-mcp](https://www.npmjs.com/package/claude-faf-mcp) (Anthropic-merged, [#2759](https://github.com/modelcontextprotocol/servers/pull/2759)) · Grok [grok-faf-mcp](https://www.npmjs.com/package/grok-faf-mcp) · Gemini [gemini-faf-mcp](https://pypi.org/project/gemini-faf-mcp/) · Rust [rust-faf-mcp](https://crates.io/crates/rust-faf-mcp) · Cursor, VS Code and other IDEs [faf-mcp](https://www.npmjs.com/package/faf-mcp) · all on the [official MCP Registry](https://faf.one/links#mcp) |
| **SDKs** | Python [faf-python-sdk](https://pypi.org/project/faf-python-sdk/) · Rust [faf-rust-sdk](https://crates.io/crates/faf-rust-sdk) · Browser [faf-wasm-sdk](https://www.npmjs.com/package/faf-wasm-sdk) · Memory [claude-fafm-sdk](https://pypi.org/project/claude-fafm-sdk/) |
| **Kernel** | [faf-kernel](https://crates.io/crates/faf-kernel) (Rust) · [faf-scoring-kernel](https://www.npmjs.com/package/faf-scoring-kernel) (WASM): the always-33 score |
| **Sites** | [faf.one](https://faf.one) · [context.faf.one](https://context.faf.one) · [memory.faf.one](https://memory.faf.one) · [mcpaas.live](https://mcpaas.live) |

On npm, PyPI, crates.io and Homebrew. **Every link, paper and listing: [faf.one/links](https://faf.one/links)**

team@faf.one
