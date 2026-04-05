# Mosaic Marketplace

Claude Code plugin marketplace for **Mosaic** — Claude Code skills that orchestrate multi-agent teams for the preparation work: project planning (DCVE), decision debates (Discuss), and brownfield team bootstrapping (Assemble).

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

Start a new session and type `/mosaic:run-dcve`, `/mosaic:run-discuss`, or `/mosaic:run-assemble` to verify the skills trigger.

## Available Plugins

| Plugin | Skills | Description |
|--------|--------|-------------|
| **mosaic** | DCVE, Discuss, Assemble | Structured project planning (DCVE), multi-perspective debate for decision-making (Discuss), and brownfield agent-team bootstrapping (Assemble) |

## Usage

After installation, start a new session and use:

```
/mosaic:run-dcve      # Start a DCVE cycle for project planning & execution
/mosaic:run-discuss   # Start a multi-perspective discussion & debate
/mosaic:run-assemble  # Bootstrap an agent team for an existing codebase
```

Or describe your intent naturally — skills trigger automatically:
- **DCVE**: "I want to build a new project from scratch", "design a new system"
- **Discuss**: "help me decide between X and Y", "discuss pros and cons"
- **Assemble**: "assemble a team for this repo", "set up an agent team for my project"

## Requirements

- Claude Code with agent teams enabled via one of:
  - Environment variable: `CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS=1`
  - settings.json: `{"env": {"CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS": "1"}}`

## License

MIT
