<img src="https://raw.githubusercontent.com/oper-stack/brand/main/og-default.png" alt="OperStack" width="100%">

## Most sites are built for search engines. Answer engines read them badly.

That is a different problem, with different fixes, and it is measurable. These
are the tools we use to measure it. Six of them are free and need no signup.

### Free and open

| | what it does | install |
|---|---|---|
| **[gates](https://github.com/oper-stack/gates)** | sixteen automated quality gates for MDX content sites: characters, frontmatter, links, images, answer-first structure | `npx @operstack/gates` |
| **[mcp-server](https://github.com/oper-stack/mcp-server)** | lets Claude, Cursor and any MCP client measure a site the way an assistant reads it | `npx @operstack/mcp` |
| **[claude-plugins](https://github.com/oper-stack/claude-plugins)** | plugins for Claude Code: content gates, answer-first writing, llms.txt, a reviewer and a post-edit hook | `/plugin marketplace add oper-stack/claude-plugins` |
| **[astro-starter](https://github.com/oper-stack/astro-starter)** | Astro starter for content sites that rank, get cited and convert | [repo](https://github.com/oper-stack/astro-starter) |
| **[audit-generator](https://github.com/oper-stack/audit-generator)** | collects public signals into `audit.json` and fills a readable report | `npx @operstack/audit` |
| **AI Visibility Checker** | a score out of 100 in under a minute, in the browser, no signup | [oper-stack.com](https://oper-stack.com) |

### What the checks look at

Whether a machine can reach the page at all, whether the first paragraph answers
the question that was asked, whether a number has its source next to it, whether
the page says when it was last true, and whether the site tells assistants what
it is. Five areas, one score, the same engine everywhere.

### Paid, if the list is long

An audit that explains why the site brings no leads, a fix that closes the checks
a machine can close, and a pipeline for building the pages that are missing.
All of it at **[oper-stack.com](https://oper-stack.com)**.

---

<sub>Everything here is MIT unless the repository says otherwise. Issues and pull
requests are read.</sub>
