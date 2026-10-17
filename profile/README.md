<div align="center">

<img src="https://cortex-md.tech/icon-192.png" width="64" height="64" alt="Cortex">

# Cortex

**Notes you own. Everything else, built in.**

A local-first Markdown workspace, built in the open.

[Website](https://cortex-md.tech) · [Docs](https://cortex-md.tech/docs) · [Roadmap](https://cortex-md.tech/roadmap) · [Changelog](https://cortex-md.tech/changelog) · [Marketplace](https://cortex-md.tech/marketplace)

</div>

---

Cortex opens a folder you control and keeps every note as a plain `.md` file. On top of those files
it gives you the tools you would otherwise spread across five apps: databases, tasks, templates,
version history, comments, search and sync. They all live in the same workspace and work on the
same files.

## What we believe

### Your files come first
A vault is an ordinary folder of Markdown. Open it in any editor, put it under Git, back it up
however you like. Cortex keeps its own state in a hidden `.cortex/` folder next to your notes, so
nothing about your writing depends on Cortex being installed.

### Everything inside the workspace
Structure without leaving your notes:

- **Live Preview editor** with callouts, tables, math, Mermaid diagrams, wikilinks and a Reading View
- **Properties and databases**: frontmatter with a vault schema, and folders that become table,
  board, calendar and gallery views
- **Tasks and reminders** with native notifications
- **Templates, version history and comments**, stored as files in the vault
- **Quick Finder, command palette, full-text search, backlinks, tags and bookmarks**
- **Cortex Sync (optional)**: encrypted on your device before it leaves, with shared vaults and
  members, hosted or self-hosted

### Open source by principle
The app, the sync server, the CLI and the plugin registry are all public. You can read how your data
is stored and synced, run your own sync server without a Cortex Cloud plan, and change what you
don't like. The roadmap is public and built from GitHub issues.

### Built to be extended
Every action in Cortex is a command, and plugins use the same system as core features. Commands,
views, settings, Markdown transforms and themes all go through a public, typed API.

## Repositories

| Repository | What it is |
| --- | --- |
| [**cortex-app**](https://github.com/cortex-md/cortex-app) | The workspace: desktop app (macOS, Windows, Linux), mobile app in development, website, docs and shared packages |
| [**sync**](https://github.com/cortex-md/sync) | The Cortex Sync server, ready to self-host |
| [**cli**](https://github.com/cortex-md/cli) | `@cortex.md/cli`: create, develop, check and release plugins and themes |
| [**registry**](https://github.com/cortex-md/registry) | The reviewed list of community plugins and themes behind the Marketplace |

## Get involved

- **Try it.** Pre-release builds are on the [Releases](https://github.com/cortex-md/cortex-app/releases) page.
- **Build a plugin or theme.** `npm install -g @cortex.md/cli`, then `cortex create`. Start with the
  [plugin docs](https://cortex-md.tech/docs).
- **Contribute.** Read [CONTRIBUTING.md](https://github.com/cortex-md/cortex-app/blob/main/CONTRIBUTING.md),
  pick an issue, or propose an idea on the [roadmap](https://cortex-md.tech/roadmap).
