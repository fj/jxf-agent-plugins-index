# jxf-agent-plugins-index

Released builds of the plugins in [fj/agent-plugins](https://github.com/fj/agent-plugins). Each plugin has one write-only repo per harness, included here as a submodule. Do not edit these repos by hand.

| Plugin | Description | Claude Code | Pi |
|---|---|---|---|
| foundry-finder | Discovers Azure AI Foundry deployments at startup and registers them as pi models. | - | 0.1.20261006022043 |
| jxf | Personal coding workflow. | 0.1.20261006021853 | 0.1.20261006021853 |
| mod-jxf-fancy-details | Prompt and tool timers, per-reply usage prefixes and a usage footer. | 0.3.20261006033055 | 0.3.20261006024144 |

## Install

### Claude Code

```sh
claude plugin marketplace add fj/jxf-agent-plugins-index
claude plugin install jxf@jxf
claude plugin install mod-jxf-fancy-details@jxf
```

### Pi

```sh
pi install git:github.com/fj/jxf-agent-plugins-foundry-finder-pi@v0.1.20261006022043
pi install git:github.com/fj/jxf-agent-plugins-jxf-pi@v0.1.20261006021853
pi install git:github.com/fj/jxf-agent-plugins-mod-jxf-fancy-details-pi@v0.3.20261006024144
```
