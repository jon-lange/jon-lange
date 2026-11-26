# Jon Lange

**I build AI products and the systems that help teams ship them.**

Senior Director, AI at Ripple Treasury. These are my personal projects and notes.

[Website](https://jon-lange.github.io/) · [LinkedIn](https://www.linkedin.com/in/jonathan-lange-ai-architect/) · [X](https://x.com/langej117)

## Building LangSpan

### Run agents in parallel. Build as a team.

Your agents. On the same page.

I'm building [LangSpan](https://langspan.dev/), the open-source coordination
layer for parallel agentic development.

Running multiple coding agents is only part of the problem. Their changes need
to work together. Separate branches can merge cleanly and still produce an
incompatible interface.

LangSpan brings related work into existing agent sessions, coordinates
supported local edits, tracks session-owned changes and helps verify the
combined Git tree. It complements Git worktrees and your existing tools.
People set direction and review the result.

[![Illustrated local workflow: LangSpan flags an overlapping edit while unrelated work continues](https://langspan.dev/assets/product/langspan-overview.svg)](https://langspan.dev/#edit-coordination)

[Explore the product](https://langspan.dev/) ·
[See the parallel-work illustration](https://langspan.dev/#scale) ·
[Why a clean merge can break the build](https://langspan.dev/#why) ·
[Source on GitHub](https://github.com/Langspan/LangSpan.dev)

LangSpan v0.1.0 is open source and available for macOS and Linux.
The illustration is not a live recording; reduced rework remains a hypothesis.

## Supporting work

- **[Botbench](https://botbenchhq.github.io/)** — a local workbench for Claude
  Code and Codex, with task worktrees and review of branches, diffs and checks.
- **[Botbench design system](https://github.com/botbenchhq/design-system)** —
  tokens, components, and UI checks for interfaces built with coding agents.
- **[A small mutation-test experiment](https://github.com/jon-lange/not-evidence/tree/main/specimens/11-mutation-check)** —
  three constructed test cases, a deliberately broken redactor, and a runnable
  demonstration of how a passing assertion can miss a broken redactor.

More work: [AI evaluation teaching labs](https://github.com/jon-lange/field-tested),
[Settleview](https://github.com/jon-lange/settleview), and
[notes from my personal agent setup](https://github.com/jon-lange/grok-bot-team).

## Writing

[When Building Is Free](https://www.linkedin.com/pulse/when-building-free-jonathan-lange-ouk3c)
— what changes when implementation gets faster and feedback becomes the constraint.

**Clear problems. Faster decisions. Better feedback.**

<sub>Greater Chicago Area · Personal projects and views.</sub>
