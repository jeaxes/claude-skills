# claude-skills

Persönliche Claude-Skills als zentrale Quelle für alle Umgebungen.
Jeder Unterordner ist ein Skill mit eigener `SKILL.md`.

## Verwendung in Claude Code Cloud-Sessions
Siehe `setup.sh` (aus der Session). Im Cloud-Environment unter **Setup script**
einfügen, `SKILLS_REPO` auf die URL dieses Repos setzen. Das Script klont die
Skills beim Session-Start nach `~/.claude/skills`.

## Lokal (anderer Rechner)
```bash
git clone <repo-url> ~/.claude/skills-repo
cp -R ~/.claude/skills-repo/* ~/.claude/skills/
```
