# Hi, I'm Thiago

Senior Solutions Architect. Seventeen years in large-scale enterprise systems, most of it in mainframe modernization, working the technical side of decisions that touch a lot of infrastructure and a lot of money. For the last few years I've been turning that same instinct toward AI-agent tooling: how you get an agent to remember, to act inside limits, and to check its own work.

## What I'm building

This is a build-in-public ladder, one repo, grown one chapter at a time. It starts small: a memory tool that stops Claude Code from forgetting everything between sessions. From there it grows into loading only the context a task needs, naming repeated work as skills, agents that brief other agents instead of doing everything themselves, work that splits into parallel pieces and checks itself, a setup that watches its own use and tunes itself, and finally a single command that runs a task end to end with a human still holding the gate at the important points.

Nothing here is a pitch. The git history is the evidence: you can watch each piece get added, chapter by chapter, and see what's actually built versus what's still a plan.

## The ladder

| Chapter | What it teaches | Status | Link |
|---|---|---|---|
| warmstart | Session memory in plain markdown files, no database, no embeddings | Live | [warmstart](https://github.com/thiagoamaro91/warmstart) <!-- LinkedIn post: warmstart launch --> |
| Dispatch | Agents that write a proper briefing for other agents, so a task can be handed off without losing context | Live | [dispatch](https://github.com/thiagoamaro91/warmstart/tree/main/dispatch) <!-- link + LinkedIn post: dispatch --> |
| Workflows | Work that fans out into parallel pieces and has a second pass check the first pass's output | Next up | [PR #4](https://github.com/thiagoamaro91/warmstart/pull/4) <!-- link + LinkedIn post: workflows --> |

The rest of the ladder (context tiering, skills, skill-tuner, /autonomous, loop altitudes) already runs in my private setup and lands here one chapter at a time. A chapter gets a row when it has something you can click; I'd rather say a thing isn't public yet than imply it is.

## Where to start

If you only click one thing, click [warmstart](https://github.com/thiagoamaro91/warmstart). It's small, it's live, and it's the first rung of everything else on this list.
