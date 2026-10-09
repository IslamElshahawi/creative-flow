# Contributing

## Structure

- **`agents/`** hold *workflow*: role, method, output contract, quality bar, failure modes.
- **`skills/`** hold *portable knowledge*: durable domain facts and craft technique that work in any harness, with or without the agents.

Keep the split clean. If a skill starts describing a sequence of steps, it probably belongs in an agent. If an agent starts explaining domain facts, they probably belong in a skill.

## Writing a skill

Every `SKILL.md` needs YAML frontmatter with exactly two keys:

```yaml
---
name: skill-name
description: Use when <trigger>. Covers <contents>. Do not use for <boundary>.
---
```

The `description` is the only thing an agent sees when deciding whether to load the skill. Write it as a trigger condition, not a summary. Include the negative boundary — it prevents misfires more than the positive description attracts correct ones.

Keep skills under roughly 500 lines. If one grows past that, split it or move detail into `references/`.

## Writing an agent

Frontmatter: `name`, `description`, `tools`, `model`, `color`.

Body sections, in order: Role → Core principle → Input → Method → Output → Quality bar → What you do not do → Failure modes.

The last two matter more than they look. "What you do not do" prevents agents bleeding into each other's territory; "Failure modes" is where hard-won experience accumulates.

## The specificity standard

This applies to prose in the repo as much as to art direction. Prefer:

- A number over an adjective
- A named mechanism over a mood word
- A worked example over a description of one
- An explicit ban over a vague preference

If a paragraph could appear unchanged in a competitor's repo, cut it.

## Cultural accuracy

Anything about the Saudi market, Arabic language, or Islamic practice must be **checkable**. Cite a source or mark it as uncertain. Do not smooth over a gap in knowledge with confident-sounding prose — in this domain a plausible invention is worse than an admitted gap.

Corrections from people who live and work in the market are the most valuable contribution to this repo.

## Compliance content

`ksa-compliance` is a working checklist, not legal advice, and must keep saying so. Regulatory claims need a public source link. If a rule has changed, update the source with it.

## Promoting a stub

Stubs carry `> STATUS: STUB` at the top and a "Planned contents" section. To promote one:

1. Write it to the same depth as `art-director` or `ksa-compliance`
2. Remove the status line
3. Update the status table in `README.md`
4. Test it on a real brief before claiming it works

## Testing

There is no automated test suite — outputs are creative judgements. The real test is running a full brief and asking whether the frames cut together and whether a Saudi viewer would find anything false. Record what broke in the run log and feed it back into the failure-modes section of the responsible agent.
