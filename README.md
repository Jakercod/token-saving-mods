# token-saving-mods

Nine Claude Code mods that cut token cost, plus a `/mods` switchboard and a `/savings` pane. Written by Ben AI (model-router is adapted from davila7/claude-code-templates, MIT).

Needs Claude Code 2.1.287 or newer (terminal) or 2.1.286 or newer (desktop app).

## Install (once per computer)

From a shell (macOS, Linux or Windows):

```bash
claude plugin marketplace add Jakercod/token-saving-mods
```

```bash
for m in input-router effort-optimizer model-router cache-clock handoff research-router efficient-browser-use mods savings-proof; do claude plugin install "$m@token-saving-mods" --scope user; done
```

Or at the prompt of a Claude Code session, one at a time:

```
/plugin install input-router --marketplace Jakercod/token-saving-mods
/plugin install effort-optimizer --marketplace Jakercod/token-saving-mods
/plugin install model-router --marketplace Jakercod/token-saving-mods
/plugin install cache-clock --marketplace Jakercod/token-saving-mods
/plugin install handoff --marketplace Jakercod/token-saving-mods
/plugin install research-router --marketplace Jakercod/token-saving-mods
/plugin install efficient-browser-use --marketplace Jakercod/token-saving-mods
/plugin install mods --marketplace Jakercod/token-saving-mods
/plugin install savings-proof --marketplace Jakercod/token-saving-mods
```

Then `/reload-plugins`, and `/mods` to check them.

Update later with `claude plugin marketplace update token-saving-mods`, then `/reload-plugins`.

## Cloud sessions (claude.ai/code)

The cloud environment's setup script runs the two shell commands above at the start of every new cloud session.

See `INSTALL.md` for the original Windows notes.
