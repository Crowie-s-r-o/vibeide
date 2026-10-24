# VibeiDE

**A local desktop workspace for Codex, Claude Code and OpenCode.** VibeiDE puts your installed coding agents behind project task queues, with live activity, saved conversations and a review step for every finished task.

[Website](https://vibeide.dev/) · [Download](https://vibeide.dev/releases/desktop/) · [Product tour](https://vibeide.dev/features/) · [Docs](https://vibeide.dev/docs/) · [Product guide](https://vibeide.dev/docs/product-facts/) · [Changelog](https://vibeide.dev/changelog/) · [Blog](https://vibeide.dev/blog/)

![VibeiDE](https://vibeide.dev/marketing/social.png)

> [!NOTE]
> This repository holds public information and links about VibeiDE. The application source is proprietary and is not published here. Product questions and corrections: info@vibeide.dev.

## What it does

- **Project task queues.** Queue requests per project, reorder waiting work and let VibeiDE start each task when a provider slot frees up.
- **Provider concurrency limits.** Separate slot limits per project for Codex, Claude Code and OpenCode. More slots do not increase your provider allowance.
- **Live activity.** Watch every running task from one monitor: plan steps, commands, file changes, messages and results.
- **Completion review.** Finished tasks wait in Ready for review with the request, activity, result and available patches.
- **Saved conversations.** Continue a supported Claude Code or Codex conversation from the task that holds its original request.
- **Plan council.** Codex or Claude Code drafts a read-only plan, the other reviews it, and the author revises it before a separate execution handoff.
- **Turbo.** A fresh planner builds a dependency graph, then a separate executor implements and verifies the whole graph.
- **Standup.** Turns completed work from a chosen day into short Added, Changed and Fixed notes.
- **Mobile control.** Queue and review work on your paired computer from your phone, end-to-end encrypted.
- **Your own accounts.** VibeiDE runs the CLIs you already installed and signed in to. Credentials stay in those CLIs.

## Supported coding agents

| Agent | How VibeiDE runs it | Page |
| --- | --- | --- |
| Codex | Interactive terminal inside the app | [vibeide.dev/for/codex](https://vibeide.dev/for/codex/) |
| Claude Code | Interactive terminal inside the app | [vibeide.dev/for/claude-code](https://vibeide.dev/for/claude-code/) |
| OpenCode | Headless, with any model you configure in OpenCode | [vibeide.dev/for/opencode](https://vibeide.dev/for/opencode/) |

One working CLI is enough for a first task.

## Platforms

| Platform | Status |
| --- | --- |
| macOS | Supported and fully validated |
| Windows | Supported; complete product validation is on macOS |
| Linux x64 | Experimental (AppImage); packaged startup and PTY smoke coverage, manual updates |

Download the installer for your system from [vibeide.dev/releases/desktop](https://vibeide.dev/releases/desktop/).

## Pricing

A 14-day trial starts when a computer first links to an account, with no payment card. Paid plans and current launch prices are on [vibeide.dev/#pricing](https://vibeide.dev/#pricing) and [vibeide.dev/teams](https://vibeide.dev/teams/). Provider subscriptions and model usage are billed separately by your provider.

## Get started

1. Install or sign in to Codex or Claude Code, or configure a model in OpenCode, and check that the CLI works in a terminal.
2. [Download VibeiDE](https://vibeide.dev/releases/desktop/), open a project folder and start with one provider slot.
3. Send a small read-only request, such as "find the main entry point and the test command", and check the result in Ready for review.

The [first-task walkthrough](https://vibeide.dev/docs/quick-start/) covers each step.

## Learn more

- [Comparisons with Conductor, Claude Squad, Warp, tmux and separate terminals](docs/comparisons.md)
- [Workflows and use cases](docs/workflows.md)
- [Guides for Claude Code, Codex and OpenCode](docs/guides.md)
- [Weekly model benchmark](https://vibeide.dev/benchmark/): Claude and GPT models build the same scene every week, scored against a fixed target.

## Made with VibeiDE badge

[![Made with VibeiDE](https://vibeide.dev/marketing/made-with-vibeide.svg)](https://vibeide.dev/)

Built something with VibeiDE? Add the badge to your README:

```md
[![Made with VibeiDE](https://vibeide.dev/marketing/made-with-vibeide.svg)](https://vibeide.dev/?utm_source=readme&utm_medium=badge&utm_campaign=made_with)
```

## Follow

[X @vibeide_dev](https://x.com/vibeide_dev) · [LinkedIn](https://www.linkedin.com/company/vibeide/) · [dev.to](https://dev.to/vibeide-dev) · [Peerlist](https://peerlist.io/patrikkelemen/project/vibeide)

## About

VibeiDE is made by [Crowie s.r.o.](https://vibeide.dev/about/) See the [privacy policy](https://vibeide.dev/privacy/), [terms](https://vibeide.dev/terms/) and [imprint](https://vibeide.dev/imprint/).

VibeiDE is proprietary software. All rights reserved. This repository does not grant a licence to the application or its source.
