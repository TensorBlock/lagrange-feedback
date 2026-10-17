# LagrangeCloud feedback

This is where you report bugs and request features for [LagrangeCloud](https://lgr.tensorblock.co), the agent cloud by TensorBlock.

LagrangeCloud's source code is not in this repository. This repository only holds issues.

## What LagrangeCloud does

- **Deploy the agent you built in Codex or Claude Code.** One sentence from your agent's folder uploads its instructions, skills, scripts and MCP servers, stores its keys as secrets, and gives you an endpoint.
- **Use it three ways.** Call it from your app through an OpenAI-compatible API, embed it as a chat widget on your site, or run it on a schedule.
- **Trace every run.** See each model call and tool call, with cost and timing.
- **Improve with every run.** Lagrange reads the traces, proposes a cheaper or faster version, tests it on live traffic, and promotes it once you approve.

## Links

| | |
|---|---|
| Website | https://lgr.tensorblock.co |
| Console | https://lgr.tensorblock.co/console/ |
| Docs | https://lgr.tensorblock.co/docs/ |
| Quickstart | https://lgr.tensorblock.co/docs/quickstart |
| Plugin for Codex and Claude Code | https://github.com/TensorBlock/lagrange-plugins |

## Get started

You need Node.js 22 or later. Install the plugin in Claude Code:

```bash
claude plugin marketplace add https://github.com/TensorBlock/lagrange-plugins
claude plugin install lagrange@tensorblock
```

Then open Claude Code in your agent's folder and ask: `Deploy this agent to LagrangeCloud`.

For Codex and the full walkthrough, see the [quickstart](https://lgr.tensorblock.co/docs/quickstart).

## Give feedback

- **Something is broken:** [report a bug](https://github.com/TensorBlock/lagrange-feedback/issues/new?template=bug.yml)
- **You want something new or different:** [request a feature](https://github.com/TensorBlock/lagrange-feedback/issues/new?template=feature.yml)
- **Search first:** someone may have reported it already. A 👍 on an existing issue helps us prioritize it.

**Issues are public.** Never paste API keys, secrets, tokens or private data. Replace them with `***`.

To report a security vulnerability, do not open an issue. Email contact@tensorblock.co instead.

## What happens next

We reply to new issues as soon as we can. We may ask for more details, then label the issue, fix it or plan it, and close it with a note on the fix.
