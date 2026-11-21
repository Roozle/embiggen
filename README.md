# embiggen

> When you "can't", think smaller. When you are "done", think bigger.

An agent skill. It loads when an agent is about to say it can't do something,
or that it is done.

## Install

Any harness with agent skills support (Claude Code, Codex, Cursor, OpenCode and more):

```sh
npx skills add Roozle/embiggen
```

Add `-g` to install it for your user rather than the current project.

Claude Code plugin:

```text
/plugin marketplace add Roozle/embiggen
/plugin install embiggen@embiggen
```

By hand: copy [`skills/embiggen`](skills/embiggen) into your harness's skills
folder, for example `~/.claude/skills/` or `~/.agents/skills/`.
