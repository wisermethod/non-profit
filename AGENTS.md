---
root: non-profit
---

# Non Profit

A WISER plugin for not-for-profits, schools, and other public entities: grant writing, fundraising, and the domain skills and experts that work requires.

This root is a placeholder. It is empty and unscoped as of 2026-09-03, and the plugin has not been designed.

## Do not author here yet

Do not add skills, experts, tools, connectors, or standards to this root on your own initiative. The plugin's scope, its boundaries, and what it refuses to do are decisions that have not been made, and a public-entity plugin built ahead of those decisions is worse than an empty one.

A build starts as a Playbook in `WISER Plugins/zBuilds/playbooks/`, authored by the Playbook Author skill. When that Playbook exists and a human has set it Active, this file is replaced by the real constitution from `zBuilds/templates/repo-scaffold/AGENTS.md.template`.

## Standing constraint

This plugin loads alongside `wiser` and may assume it is present. It references `wiser` primitives rather than duplicating them. Copying a `wiser` writing, playbook, or connecting primitive into this tree to remove the dependency is a defect.
