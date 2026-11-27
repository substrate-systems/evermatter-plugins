# Evermatter plugins

The Claude Code marketplace for Evermatter. It lists one plugin, `evermatter`, for an Evermatter account. The plugin connects Claude to Evermatter and adds Evermatter's skills and its automatic recall and capture hooks.

## Install

1. In Claude Code, run `/plugin marketplace add substrate-systems/evermatter-plugins`.
2. Run `/plugin install evermatter@evermatter`.
3. Run `/mcp`, select the Evermatter server and sign in to your Evermatter account.

The plugin's files come from the folder `plugins/cloud/generated/claude-hooks` of [substrate-systems/evermatter](https://github.com/substrate-systems/evermatter), which builds them. This repository holds only the marketplace entry.
