<p align="center">
  <img src="./assets/grillforge-banner.jpg" alt="GrillForge — don't code it, grill it" width="100%">
</p>

<h1 align="center">🔥 GrillForge</h1>

<p align="center">
  <strong>Don’t code the first idea. Grill it until the weak parts break.</strong>
</p>

<p align="center">
  A decision-first AI skill for founders, product builders, engineers, and vibe coders.
</p>

<p align="center">
  <a href="#install">Install</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#example">Example</a> ·
  <a href="#license">License</a>
</p>

---

## Why GrillForge exists

AI is very good at producing code before anyone has earned the right to write it.

You describe a feature, the agent returns a plan, and a few minutes later you are approving files faster than you can explain why they exist. The dangerous part is not bad syntax. It is building on top of an assumption nobody challenged.

GrillForge changes the order:

> **First pressure-test the decision. Then write the code.**

It forces the agent to expose hidden assumptions, attack the risky claims, surface edge cases, and demand real evidence before implementation begins.

## What it does

GrillForge turns a vague idea into explicit claims and puts the critical ones under pressure.

- Maps the claims that must be true for the idea to work
- Ranks them by risk, cost of error, and reversibility
- Attacks substitution, incentives, friction, scale, and real-world behavior
- Detects contradictions and motivated reasoning
- Converts uncertainty into small falsifiable experiments
- Ends with a hard verdict: **Advance, Probe, Pivot, or Kill**

## How it works

GrillForge runs through six stages:

| Stage | Purpose |
|---|---|
| **Claim Stack** | Break the idea into claims that can be examined |
| **Heat Map** | Find the claims that can destroy the whole plan |
| **Five Flames** | Attack alternatives, incentives, friction, scale, and reality |
| **Flip Tests** | Reverse the framing to expose bias |
| **Proof Skewers** | Turn unknowns into cheap tests with pass/fail thresholds |
| **Final Plate** | Issue a clear verdict and the next concrete move |

## Install

Copy [`SKILL.md`](./SKILL.md) into your agent’s skills directory:

```text
skills/
└── grillforge/
    └── SKILL.md
```

Then invoke it explicitly:

```text
Use GrillForge to pressure-test this product idea before we write any code.
```

Or:

```text
Run GrillForge in deep mode on this architecture decision.
```

## Example

**You:**

```text
I want to build an AI meeting assistant for small teams.
```

**GrillForge does not immediately design the app.** It first asks things like:

- What painful behavior exists today without your product?
- Why would users trust it inside private meetings?
- What is the closest existing workaround?
- Which assumption would make the whole product pointless if false?
- What can you test this week without building the product?

It then ends with a verdict:

```text
VERDICT: PROBE

Reason:
The pain appears real, but willingness to grant meeting access is still unproven.

Next move:
Run 10 moderated tests using a manual transcript workflow.

Stop condition:
Fewer than 3 teams request a second session.
```

## Best use cases

- Product and startup ideas
- Feature prioritization
- Architecture and infrastructure decisions
- Go-to-market plans
- Internal tooling
- AI-generated implementation plans
- Expensive or hard-to-reverse decisions

## What GrillForge is not

It is not a brainstorming prompt that agrees with everything.

It is not a long generic questionnaire.

It is not an excuse to stay in analysis forever.

Its job is to find the shortest path from an attractive story to a defensible decision.

## Repository structure

```text
.
├── assets/
│   └── grillforge-banner.jpg
├── docs/
│   ├── methodology.md
│   └── philosophy.md
├── examples/
│   ├── architecture.md
│   ├── product.md
│   └── startup.md
├── LICENSE
├── README.md
└── SKILL.md
```

## Author

Created by [Sepehr Bayat](https://github.com/sepehrbayat).

## License

Copyright © 2026 Sepehr Bayat. All rights reserved.

This project is proprietary source-available work. See [`LICENSE`](./LICENSE) for the full terms.
