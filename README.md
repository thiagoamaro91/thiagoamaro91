# Hi, I'm Thiago

Senior Solutions Architect. Fifteen years in large-scale enterprise systems, most of it in mainframe modernization, working the technical side of decisions that touch a lot of infrastructure and a lot of money. For the last few years I've been turning that same instinct toward AI-agent tooling: how you get an agent to remember, to act inside limits, and to check its own work.

## What I'm building

This is a build-in-public ladder, one repo, grown one chapter at a time. It starts small: a memory tool that stops Claude Code from forgetting everything between sessions. From there it grows into loading only the context a task needs, naming repeated work as skills, agents that brief other agents instead of doing everything themselves, work that splits into parallel pieces and checks itself, a setup that watches its own use and tunes itself, and finally a single command that runs a task end to end with a human still holding the gate at the important points.

Nothing here is a pitch. The git history is the evidence: you can watch each piece get added, chapter by chapter, and see what's actually built versus what's still a plan.

## The ladder

| Chapter | What it teaches | Status | Link |
|---|---|---|---|
| warmstart | Session memory in plain markdown files, no database, no embeddings | Live | [warmstart](https://github.com/thiagoamaro91/warmstart) <!-- LinkedIn post: warmstart launch --> |
| Context tiering | Loading only the context a task needs, when it needs it, instead of stuffing everything in up front | Shipping soon | <!-- link + LinkedIn post: context tiering --> |
| Skills | Turning work you do repeatedly into a named, repeatable command instead of re-explaining it every time | Shipping soon | <!-- link + LinkedIn post: skills --> |
| Dispatch | Agents that write a proper briefing for other agents, so a task can be handed off without losing context | Shipping soon | <!-- link + LinkedIn post: dispatch --> |
| Workflows | Work that fans out into parallel pieces and has a second pass check the first pass's output | Shipping soon | <!-- link + LinkedIn post: workflows --> |
| Skill-tuner | A setup that reviews its own use over time and improves the parts that aren't working | Shipping soon | <!-- link + LinkedIn post: skill-tuner --> |
| /autonomous | One command that runs a whole task end to end, with a human still checking in at two points | Shipping soon | <!-- link + LinkedIn post: autonomous --> |
| Loop altitudes | A short doc on the three levels a system like this can loop at, and why that distinction matters | Shipping soon | <!-- link + LinkedIn post: loop altitudes --> |

Everything marked "shipping soon" already runs in my private setup. Each chapter is being cleaned up and packaged for release over the next few weeks. I'd rather say a thing isn't public yet than imply it is.

## Where to start

If you only click one thing, click [warmstart](https://github.com/thiagoamaro91/warmstart). It's small, it's live, and it's the first rung of everything else on this list.
