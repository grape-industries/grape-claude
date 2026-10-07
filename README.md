# Grape for Claude Code

Grape searches the documents that you keep in it. These are PDFs, Office files, e-books, notes, audio transcripts and GitHub repositories. This plugin connects Claude Code to Grape. Claude then finds passages in all your projects and quotes the project, the file and the line.

## Install

1. In Claude Code, add the marketplace:
   ```
   /plugin marketplace add grape-industries/grape-claude
   ```
2. Install the plugin:
   ```
   /plugin install grape@grape-industries
   ```

## Sign in

1. Run `/mcp`.
2. Select `grape`.
3. Select **Authenticate**.
4. Sign in with your Grape account, then select **Allow**.

You must have a Grape account. To make one, go to https://grape-inc.in.

## Tools

All tools only read. They cannot change or delete your projects.

| Tool | What it does |
| --- | --- |
| `search` | Finds passages in all your projects, or in the projects that you select. |
| `fetch` | Gets one search result in full. |
| `read_file` | Reads a file, or a range of lines in a file. |
| `list_projects` | Shows your projects and their files. |

## Policies

- Privacy: https://grape-inc.in/privacy
- Terms: https://grape-inc.in/terms
