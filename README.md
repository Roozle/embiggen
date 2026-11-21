# embiggen

> When you "can't", think smaller. When you are "done", think bigger.

An agent skill. Agents call it on their own, without a prompt, when they are
about to say they can't do something or that they are done.

## Why

embiggen is a scoping skill, not a way to stop an agent ending its turn.

An agent does what it thinks is correct, at the level it thinks is correct.
It then spends its turn budget branching off that first thought, staying at
the same level. embiggen makes the agent change scope instead.

When it "can't", it thinks smaller. Fixing one smaller part of the problem
often reshapes the whole problem.

When it is "done", it thinks bigger. Once an agent believes it is done, it has
no reason to continue. Ralph loops force it to continue anyway; embiggen is a
softer touch. It asks whether the result is complete at the right level, and
whether there is a larger problem it could solve.

The skill is two sentences on purpose. An agent smart enough to reach for it
is smart enough not to end its turn, so it needs no hooks or checklists.

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
