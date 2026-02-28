> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Knowledge graph - The markdown-based memory system
- Workspace - The `~/.rowboat/` directory
- Background agents - Automated workflows that run on schedule
- Skills - Capabilities loaded by the AI agent (meeting prep, email drafting, etc.)

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use "knowledge graph" not "knowledge base"
- Use "background agents" not "scheduled tasks"

## Content boundaries

- Focus on user-facing features and workflows
- Document the desktop app, CLI, Python SDK, and web platform
- Include configuration and setup guides
- Cover integrations (Gmail, Calendar, Slack, MCP)
- Don't document internal implementation details unless necessary for advanced users
