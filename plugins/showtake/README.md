# ShowTake for Claude Code (plugin marketplace)

Adds the ShowTake MCP server and a `film-app-demo` skill to Claude Code. Requires the ShowTake Mac app
(https://showtake.app, free tier available).

```
/plugin marketplace add orchestero/showtake-claude-plugin
/plugin install showtake@showtake
```

Without the plugin, one command does the same for the MCP server:

```
claude mcp add --scope user showtake -- "/Applications/ShowTake.app/Contents/MacOS/showtake-mcp"
```

Then ask: "Film a 20-second demo of adding a task in my app and export an App Store preview."

Bugs and requests: https://github.com/orchestero/showtake-issues · Plugin source: https://github.com/orchestero/showtake-claude-plugin
