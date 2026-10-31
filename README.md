# Claude Skills

A personal collection of reusable skills for Claude and compatible coding assistants. Each skill lives in its own directory and is described by a `SKILL.md` file.

## Find a skill

Start with the [skill index](INDEX.md), then read the selected skill's instructions and prerequisites. Some skills include scripts, reference material, or templates in subdirectories.

## Local setup

```bash
git clone https://github.com/jeaxes/claude-skills.git ~/.claude/skills-repo
```

Install the individual skill directories you need into the skills directory supported by your assistant. Preserve their relative files and review existing installations before replacing them.

## Cloud environments

Use your environment's setup script to obtain this repository and install the selected skills at session startup. The earlier session-specific `setup.sh` is not included in this repository, so its configuration must be supplied by the environment.

## Conventions

Repository documentation, issues, pull requests, and new commit messages use English. Individual skills may explicitly request another language for their generated output. Keep bundled license notices and upstream attribution with the relevant files.

See [contributing conventions](CONTRIBUTING.md).
