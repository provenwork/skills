# provenwork skills

**Agent skills that make coding agents prove their work.** One marketplace, every provenwork plugin.

```bash
# Claude Code
/plugin marketplace add provenwork/skills
/plugin install <plugin>@provenwork
```

Each plugin is also installable on its own in any agent that reads `SKILL.md`: `npx skills add provenwork/<plugin>`.

## Plugins

<!-- plugins:start -->
| Plugin | What it does | Install |
|---|---|---|
| [nobluff](https://github.com/provenwork/nobluff) | Your coding agent stops saying "done" until it's proven. | `/plugin install nobluff@provenwork` |
| [toskill](https://github.com/provenwork/toskill) | Turn any repository into an agent skill: digest the docs, lint the SKILL.md, prepare the upstream PR. | `/plugin install toskill@provenwork` |
<!-- plugins:end -->

MIT. Every plugin states what it does not do; read that section before installing.
