# SolWear Claude Plugin

The official [Claude Code](https://claude.com/claude-code) plugin for SolWear —
build apps for SolWear OS and contribute to the platform.

## Install

```
/plugin marketplace add SolWear/SolWear-Claude-Plugin
/plugin install solwear
```

## What it provides

- **Skill `build-a-solwear-app`** — the app developer loop for SolWear OS:
  scaffold, build, run in the host emulator, package to `.swa`, sign, and
  publish to the store, all through the published `@solwear/cli`. Claude loads
  it automatically when you ask to build, run, or publish a SolWear app. Only
  needs `npm install --global @solwear/cli`.
- **`/solwear:task`** — act as the Architect: analyse a task and produce a
  scoped work unit (used inside the SolWear OS monorepo).
- **`/solwear:review`** — act as the Reviewer: review a diff for contract
  conformance, security, correctness, and clarity.

See <https://docs.solwear.tech> for the full platform documentation, and
[SolWear/SolWear_OS](https://github.com/SolWear/SolWear_OS) for the source.

## License

Apache-2.0.
