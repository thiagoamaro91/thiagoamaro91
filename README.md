# Hi, I'm Thiago

Senior Solutions Architect. Seventeen years in large-scale enterprise systems, most of it in mainframe modernization, working the technical side of decisions that touch a lot of infrastructure and a lot of money. For the last few years I've been turning that same instinct toward AI-agent tooling: how you get an agent to remember, to act inside limits, and to check its own work.

## What I'm building

This is a build-in-public ladder, one repo, grown one chapter at a time. It starts small: a memory tool that stops Claude Code from forgetting everything between sessions. From there it grows into loading only the context a task needs, naming repeated work as skills, agents that brief other agents instead of doing everything themselves, work that splits into parallel pieces and checks itself, a setup that watches its own use and tunes itself, and finally a single command that runs a task end to end with a human still holding the gate at the important points.

Nothing here is a pitch. The git history is the evidence: you can watch each piece get added, chapter by chapter, and see what's actually built versus what's still a plan.

## The ladder

| Chapter | What it teaches | Status | Link |
|---|---|---|---|
| warmstart | Session memory in plain markdown files, no database, no embeddings | Live | [warmstart](https://github.com/thiagoamaro91/warmstart) |
| Dispatch | Agents that write a proper briefing for other agents, so a task can be handed off without losing context | Live | [dispatch](https://github.com/thiagoamaro91/warmstart/tree/main/dispatch) |
| Workflows | Work that fans out into parallel pieces and has a second pass check the first pass's output | Live | [workflows](https://github.com/thiagoamaro91/warmstart/tree/main/workflows) |
| skill-tuner | A loop that reads how the tools actually got used and rewrites them, auto-applying only the changes that cannot alter behaviour | Live | [skill-tuner](https://github.com/thiagoamaro91/warmstart/tree/main/skill-tuner) |
| dreamer | An overnight pass that consolidates what the day produced, so memory gets smaller instead of larger | Live | [dreamer](https://github.com/thiagoamaro91/warmstart/tree/main/dreamer) |
| /autonomous | One command that runs a task end to end, with research at the front and adversarial review at the back | Live | [autonomous](https://github.com/thiagoamaro91/warmstart/tree/main/autonomous) |

Seven plugins ship from one marketplace as of [v0.3.0](https://github.com/thiagoamaro91/warmstart/releases). The rest of the ladder (context tiering, loop altitudes) still runs only in my private setup and lands here one chapter at a time. A chapter gets a row when it has something you can click; I'd rather say a thing isn't public yet than imply it is.

## Measuring the thing, not just building it

[caveat](https://github.com/thiagoamaro91/caveat) is the other half. It reads vendor Statements of Work from the buyer's side and flags clauses that quietly favour the vendor: pricing that looks fixed but is not, assumptions that let the vendor reopen commercial terms, change control only one side can trigger, missing exit terms.

The agent is not the point. The eval harness around it is: 25 synthetic SOW excerpts with 1 to 3 planted defects each, plus 5 clean decoys, a scorer, and a scoreboard that reports what it got wrong as plainly as what it got right. Ground truth is free because the defects are planted at generation time.

I spent years on the other side of those clauses. This is that judgment written down as a test set.

## Where to start

If you only click one thing, click [warmstart](https://github.com/thiagoamaro91/warmstart). It's small, it's live, and it's the first rung of everything else on this list. If you care more about whether any of it works than how it's built, click [caveat](https://github.com/thiagoamaro91/caveat) and read the scoreboard.

If you'd rather have the context than the code, [thiago-amaro.com](https://thiago-amaro.com) is the longer version: how eleven years of running mainframes turned into building this, and why I think the bottleneck in enterprise AI is the translation rather than the models.
