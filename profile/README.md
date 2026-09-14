<p align="center">
  <a href="https://github.com/ANTEVO-CH/plugins"><img alt="Antevo: a question field cycling through questions your assistant can now answer, beside a lens where signals from the world travel inward to you" src="https://raw.githubusercontent.com/ANTEVO-CH/plugins/main/assets/cover.svg" width="100%"></a>
</p>

<h3 align="center">Antevo watches the world. You focus on what matters.</h3>

<p align="center">
  <a href="https://antevo.ch">antevo.ch</a> &nbsp;·&nbsp;
  <a href="https://antevo.ch/mcp">Connect</a> &nbsp;·&nbsp;
  <a href="https://registry.modelcontextprotocol.io/v0/servers?search=ch.antevo">MCP Registry</a> &nbsp;·&nbsp;
  <a href="https://www.npmjs.com/package/@antevo/cli">npm</a> &nbsp;·&nbsp;
  <a href="mailto:contact@antevo.ch">contact@antevo.ch</a>
</p>

<br>

Antevo connects developments in the world to the things you own, manage and protect — with the record behind each connection. Bring it into the assistant you already use: Claude, Cursor, VS Code, Gemini CLI, or a terminal.

<p align="center"><b><a href="https://github.com/ANTEVO-CH/plugins">Start with ANTEVO-CH/plugins →</a></b><br><sub>Five connections and 28 skills for Claude, one install each</sub></p>

## The connections

| | Connection | Address | Access |
|:--|:--|:--|:--|
| **I.** | **Executive** — the daily editorial read on markets and the world, the risk radar, a dated archive and a century of macro-economic history | `https://api.antevo.ch/mcp/executive/mcp` | Public |
| **II.** | **Trademark** — screen a name across the registers, read who holds a mark, check the opposition window | `https://trademark.antevo.ch/mcp` | Public screening |
| **III.** | **Crypto** — one reference price per major pair, with daily history and technical signals | `https://api.antevo.ch/mcp/crypto/mcp` | Public |
| **IV.** | **Wealth** — your household: holdings, allocation, risk and real assets | `https://api.antevo.ch/mcp/wealth/mcp` | Your account |
| **V.** | **Mandates** — your firm's client book: reviews due, meeting preparation, succession | `https://api.antevo.ch/mcp/mandates/mcp` | By arrangement |

All five are listed in the official [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=ch.antevo) under `ch.antevo`.

## Begin in one line

**Claude** — Claude Code, Claude Desktop and claude.ai

```text
/plugin marketplace add ANTEVO-CH/plugins
/plugin install antevo-executive@antevo
```

**A terminal** — no account, nothing installed

```bash
npx @antevo/cli brief
```

**Gemini CLI**

```bash
gemini extensions install https://github.com/ANTEVO-CH/antevo-mcp
```

**Cursor and VS Code** — one-click links in [INSTALL.md](https://github.com/ANTEVO-CH/antevo-mcp/blob/main/INSTALL.md).

**Anything else** — paste an address from the table into any client that speaks MCP over Streamable HTTP. There is nothing to download and nothing to run.

## A thoughtful question

> **Executive** — *"What could go wrong from here?"* <br>
> **Trademark** — *"Has anyone filed anything close to my brand name?"* <br>
> **Crypto** — *"Is bitcoin above its 200-day average?"* <br>
> **Wealth** — *"Where am I concentrated?"* <br>
> **Mandates** — *"Which clients are due a review this month?"*

## A considered connection

- **Public where it can be.** Executive, Trademark screening and Crypto need no account and reach no personal data.
- **Your permission where it matters.** Wealth and Mandates sign in over OAuth 2.1 with PKCE. Your assistant receives a scoped token, never your password, and your account's own permissions apply.
- **Nothing trades, nothing moves money.** Mandates can update your own firm's records; an irreversible change returns a plan first and waits for confirmation.
- **Intelligence, not advice.**

## Repositories

| | |
|:--|:--|
| [**antevo-mcp**](https://github.com/ANTEVO-CH/antevo-mcp) | Connection metadata — registry manifests, Cursor plugins, the Gemini CLI extension and install links. MIT. |
| [**plugins**](https://github.com/ANTEVO-CH/plugins) | Claude plugins — each connection with its skills, 28 in all, one install. |
| [**cli**](https://github.com/ANTEVO-CH/cli) | `@antevo/cli` — the same connections from a terminal, scriptable. |

<br>

<p align="center"><sub>Antevo · Switzerland · Security reports to <a href="mailto:contact@antevo.ch">contact@antevo.ch</a></sub></p>
