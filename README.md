# Pi Skills Collection

A collection of [pi](https://github.com/earendil-works/pi) skills curated by the Microbial Pangenomes Lab.

## Installation

Install the full collection in pi via GitHub:

```bash
pi install git:github.com/microbial-pangenomes-lab/pi-nb-cli-skill
```

Or add to your `~/.pi/settings.json`:

```json
{
  "packages": ["git:github.com/microbial-pangenomes-lab/pi-nb-cli-skill"]
}
```

## Available Skills

### notebook-cli

Use the `nb` CLI for all Jupyter notebook (`.ipynb`) operations — reading, creating, editing cells, executing, and working with connected JupyterLab sessions. Replaces raw notebook JSON manipulation with a deterministic CLI.

See [skills/notebook-cli/SKILL.md](skills/notebook-cli/SKILL.md) for full documentation.

**Key commands:**
- `nb read` — inspect notebook structure and content
- `nb create` — create new notebooks
- `nb cell` — add, update, delete cells
- `nb execute` — run notebooks or specific cells
- `nb connect` — work with JupyterLab sessions

**Requirements:** The `nb-cli` tool must be installed and available in your PATH. For connected mode, JupyterLab must be running.

### uv

Guide for using [uv](https://docs.astral.sh/uv/), the fast Python package and project manager. Covers scripts, projects, tools (`uvx`), the pip interface, and migration from pyenv/pipx/pip-tools.

See [skills/uv/SKILL.md](skills/uv/SKILL.md) for full documentation.

**Source:** Adapted from [astral-sh/claude-code-plugins](https://github.com/astral-sh/claude-code-plugins/blob/main/plugins/astral/skills/uv/SKILL.md) (Apache-2.0). (c) Astral Software Inc.

## License

This collection is BSD-3-Clause. Individual skills may be under different licenses; see each skill's frontmatter or SKILL.md:

- `notebook-cli` — BSD-3-Clause
- `uv` — Apache-2.0 (adapted from [astral-sh/claude-code-plugins](https://github.com/astral-sh/claude-code-plugins))

## Contributing

PRs welcome for new skills. Each skill lives in `skills/<name>/` with a `SKILL.md` at minimum. Follow the [Agent Skills standard](https://agentskills.io/specification).