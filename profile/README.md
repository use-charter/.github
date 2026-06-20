<p align="center">
  <a href="https://use-charter.dev">
    <img src="https://use-charter.dev/og.png" alt="Charter — AI-agent readiness, scored." width="600">
  </a>
</p>

<p align="center">
  <b>AI-agent readiness, scored.</b>
</p>

<p align="center">
  An offline CLI that grades any repository <code>0–100</code> on how safely an AI coding<br>
  agent can work in it — deterministic, no telemetry, a concrete fix for every gap.
</p>

<p align="center">
  <a href="https://use-charter.dev"><b>Website</b></a> &nbsp;·&nbsp;
  <a href="https://use-charter.dev/docs"><b>Docs</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/use-charter/charter"><b>Source</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/marketplace/actions/charter-ai-agent-readiness"><b>Marketplace</b></a>
</p>

```sh
brew install use-charter/tap/charter
charter doctor
```

AI agents are only as good as the repo they land in — missing context, exposed secrets, and unpinned tools quietly wreck their output. Charter catches that before an agent does: **18 rules across 9 categories** (context, secrets, MCP safety, agent config, environment, CI, testing, autonomy, governance), a per-category scorecard, diff-first auto-fix, and SARIF straight into GitHub Code Scanning. It runs in under two seconds, makes **zero network calls**, and never sends your code anywhere.

### Projects

- **[charter](https://github.com/use-charter/charter)** — the CLI, rules engine, and GitHub Action. Go · Apache-2.0 · SLSA Level 3.
- **[charter-action](https://github.com/marketplace/actions/charter-ai-agent-readiness)** — gate every pull request on a readiness threshold.

<sub>Free and open source, forever · no LLM in the core · the score only ratchets up.</sub>
