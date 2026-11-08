# Jam SQL Studio

Jam SQL Studio is a desktop SQL IDE for SQL Server, PostgreSQL, MySQL and MariaDB, Oracle and SQLite. It also
queries Azure Data Explorer (Kusto) and browses Azure Storage. It runs on macOS, Windows and Linux.

This repository describes the app and links to its downloads and documentation. The app itself is closed source.

## Download

| Platform | Package |
|---|---|
| macOS 11 or later | Signed and notarized DMG, separate builds for Apple Silicon and Intel — [download](https://jamsql.com/download/mac/) |
| Windows 10 and 11 (x64) | Signed installer — [download](https://jamsql.com/download/windows/) |
| Linux (x64 and ARM64) | `.deb`, `.rpm` and AppImage — [download](https://jamsql.com/download/linux/), or `curl -fsSL https://jamsql.com/install.sh \| bash` |

The app updates itself.

## What it does

- **Query Editor**: IntelliSense for tables, columns, joins and functions, parameter hints, execution plans, result
  grids with charts, and run-the-statement-under-the-cursor execution.
- **Table Explorer**: browse, filter, sort and edit rows; follow foreign keys to related rows.
- **Schema compare and data compare** between databases, with generated deployment scripts.
- **SQL notebooks** that mix SQL cells, results and Markdown.
- **AI integrations**: a local MCP server and the `jam-sql` CLI let Claude, Cursor, VS Code, Codex and other AI
  tools work with your saved connections. The AI tool never receives connection credentials. Each connection has
  a permission level you set (Block, Read-only or Confirm), and at Confirm every write waits for your approval in
  the app. See [jamsql/skills](https://github.com/jamsql/skills) for the Claude plugin and the agent skill.

The full feature list is in the [documentation](https://jamsql.com/docs/).

## Pricing

Free for personal, non-commercial use. Pro removes a few size caps and adds the license for commercial use:
see [pricing](https://jamsql.com/pricing/).

## Help

- Documentation: <https://jamsql.com/docs/>
- Changelog: <https://jamsql.com/docs/changelog/>
- Bug reports, feature requests and questions: [support@jamsql.com](mailto:support@jamsql.com)
- Security reports: [security@jamsql.com](mailto:security@jamsql.com)
