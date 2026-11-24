# Termote plugins

The termote plugin for Claude Code and Codex: a skill that coordinates the coding agents running
in your [termote](https://termote.ohnice.app) panes from one session. It needs termote installed and running
natively (`termote start`), at a release that has `termote agents`; the skill says when to update.

Generated from [lamngockhuong/termote](https://github.com/lamngockhuong/termote) at each release;
do not edit it here.

## Install

Claude Code:

```
/plugin marketplace add lamngockhuong/termote-plugins
/plugin install termote@termote
```

Codex:

```bash
codex plugin marketplace add lamngockhuong/termote-plugins
codex plugin add termote@termote
```

The same skill also comes with termote itself: `termote skills install`. Use one of the two,
not both, or the agent sees the skill twice.
