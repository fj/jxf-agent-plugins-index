# jxf-agent-plugins-index

Released builds of the plugins in [fj/agent-plugins](https://github.com/fj/agent-plugins). Each plugin has one write-only repo per harness, included here as a submodule. Do not edit these repos by hand.

| Plugin | Description | Claude Code | Pi |
|---|---|---|---|
| foundry-finder | Discovers Azure AI Foundry deployments at startup and registers them as pi models. | - | 0.1.20261006022043 |
| jxf | Personal coding workflow. | 0.1.20261006021853 | 0.1.20261006021853 |
| mod-jxf-fancy-details | Prompt and tool timers, per-reply usage prefixes and a usage footer. | 0.3.20261029064641 | 0.3.20261029064641 |
| mod-jxf-session-title | Names a session from its first prompt with a small model and shows the name above the prompt. | 0.1.20261018170407 | 0.1.20261018170407 |
| mod-jxf-tmux-spinner | Marks the tmux window of an agent as busy, waiting for you, or done. | 0.1.20261019124257 | - |

## Install

### Claude Code

```sh
claude plugin marketplace add fj/jxf-agent-plugins-index
claude plugin install jxf@jxf
claude plugin install mod-jxf-fancy-details@jxf
claude plugin install mod-jxf-session-title@jxf
claude plugin install mod-jxf-tmux-spinner@jxf
```

### Pi

```sh
pi install git:github.com/fj/jxf-agent-plugins-foundry-finder-pi@v0.1.20261006022043
pi install git:github.com/fj/jxf-agent-plugins-jxf-pi@v0.1.20261006021853
pi install git:github.com/fj/jxf-agent-plugins-mod-jxf-fancy-details-pi@v0.3.20261029064641
pi install git:github.com/fj/jxf-agent-plugins-mod-jxf-session-title-pi@v0.1.20261018170407
```
