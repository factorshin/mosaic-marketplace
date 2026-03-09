# Mosaic Marketplace

Claude Code plugin marketplace for **Mosaic** — DCVE methodology for systematic project planning, and Discuss for multi-perspective debate and decision-making — both powered by Claude Code agent teams.

## Installation

### 1. Add this marketplace

```
/plugin marketplace add factorshin/mosaic-marketplace
```

### 2. Install the plugin

```
/plugin install mosaic@mosaic-marketplace
```

### 3. Verify

Start a new session and type `/mosaic:run-dcve` or `/mosaic:run-discuss` to verify the skills trigger.

## Available Plugins

| Plugin | Skills | Description |
|--------|--------|-------------|
| **mosaic** | DCVE, Discuss | Structured project planning (DCVE) and multi-perspective debate for decision-making (Discuss) |

## Usage

After installation, start a new session and use:

```
/mosaic:run-dcve     # Start a DCVE cycle for project planning & execution
/mosaic:run-discuss  # Start a multi-perspective discussion & debate
```

Or describe your intent naturally — skills trigger automatically:
- **DCVE**: "I want to build a new project from scratch", "design a new system"
- **Discuss**: "help me decide between X and Y", "discuss pros and cons"

## Requirements

- Claude Code with agent teams enabled (`CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS`)

## License

MIT
