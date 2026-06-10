# pm-p0-preflight

**P0 clarification preflight** for PMflow: before running `/pm-flow`, get the right questions, draft answers, and a paste-ready reply block.

## Install

Unzip and merge the `.cursor` folder into your project root:

```
your-project/
└── .cursor/
    ├── skills/pm-p0-preflight/
    └── commands/pm-p0-preflight.md   # optional slash command
```

Or copy only the skill to personal skills: `~/.cursor/skills/pm-p0-preflight/`

## One-liner

**Preflight P0 first, confirm, then run pm-flow.**

```
/pm-p0-preflight
One-line requirement: [your requirement]
```

## When to use

| Scenario | You provide | Skill output |
|----------|-------------|--------------|
| New requirement | One-line requirement | P0 questions + draft answers |
| Existing P0 list | pm-flow P0 checklist | Audit + line-by-line drafts |
| With docs/prototype | `@path/to/01 or HTML` | Answers grounded in project context |
| Screenshot feedback | Red-box / annotation | Map fixes to P0 IDs, fix inconsistencies |
| Interaction-heavy UX | Entry, modal, list, contacts… | Entry, back path, posture; infer defaults when scenario is clear |
| Multiple-choice P0 | A/B/C options | Answers mapped to options, not free-form drift |

**Not for:** 02 solution docs, 03 feature lists, prototype code, or pure concept Q&A.

## Workflow

1. Run `/pm-p0-preflight` with requirement (+ optional `@` files / screenshots)
2. Review **open items** and edit draft answers
3. Paste **ready-to-paste reply block** into `/pm-flow`
4. Continue to 01 / 02 / 03

## Relation to pm-flow

- **pm-p0-preflight** = preflight & drafts (this package)
- **pm-flow** = formal PM process (needs project rules + product-manager skill)

Packaged: 2026-06-10
