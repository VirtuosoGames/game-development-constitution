---
name: game-development-constitution
description: Use for any game-development task or decision in this repository, including gameplay, systems, level design, UX, balance, performance, multiplayer, production, prototyping, QA, monetization, narrative, shipping, or Unreal Engine 5.8 work. Routes to the smallest relevant Constitution records or one appropriate Unreal skill.
---

# Game Development Constitution

Use this repository's public Game Development Constitution as focused decision support. Work from the repository root; do not depend on a machine-specific location.

## Route the request

- For a concrete Unreal Engine implementation or diagnosis, read [`UNREAL_AI_START_HERE.md`](../../../UNREAL_AI_START_HERE.md), choose exactly one primary owner from [`skills/INDEX.md`](../../../skills/INDEX.md), then read that skill's `SKILL.md` and only the references needed for the request.
- For any other game-development decision, read [`AI_START_HERE.md`](../../../AI_START_HERE.md). Query [`public/data/principles.json`](../../../public/data/principles.json) with the request's concrete terms and likely domains. Select the smallest useful set, normally one to five records, and read each selected record fully.
- Read [`public/data/manifest.json`](../../../public/data/manifest.json) when reporting corpus version or integrity, and use the corresponding canonical record in [`content/principles/`](../../../content/principles/) for exact wording or citations.

## Answer contract

- Cite relevant principle IDs and the public-edition version.
- Apply each record's scope, exceptions, dependencies, conflicts, and confidence before recommending an action.
- Distinguish durable guidance from project-specific decisions; project evidence and user constraints take priority.
- For Unreal tasks, give exact actions, assumptions, parameter effects, verification, failure checks, and any explicit ownership seams.
- Do not ingest the repository, README, website output, PDF, or DOCX wholesale. Keep retrieval narrow and stop once the answer is supported.
