# Notebook CLI Skill for pi

A pi skill that provides the `nb` CLI for Jupyter notebook operations.

## Installation

Install this skill in pi by adding it via GitHub:

```bash
pi install git:github.com/microbial-pangenomes-lab/pi-nb-cli-skill
```

Or add to your `~/.pi/settings.json`:

```json
{
  "packages": ["git:github.com/microbial-pangenomes-lab/pi-nb-cli-skill"]
}
```

## Usage

Once installed, use the `/skill:notebook-cli` command to load the skill instructions, or reference it in your prompts.

The skill provides:
- `nb read` - Inspect notebook structure and content
- `nb create` - Create new notebooks
- `nb cell` - Add, update, delete cells
- `nb execute` - Run notebooks or specific cells
- `nb connect` - Work with JupyterLab sessions
- And more...

See [SKILL.md](skills/notebook-cli/SKILL.md) for full documentation.

## Requirements

- The `nb-cli` tool must be installed and available in your PATH
- For connected mode, JupyterLab must be running

## License

MIT
