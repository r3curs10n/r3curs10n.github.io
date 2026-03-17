---
title: "AI and the Illusion of Productivity"
description: "As companies rush to adopt AI, nobody actually knows how to measure productivity anymore."
date: 2026-03-16
---

As companies rush to adopt AI and encourage employees to "use more of it," there's a critical missing piece:

Nobody actually knows how to measure productivity anymore.

To be fair, this has always been somewhat true. But historically, we relied on rough proxy metrics:

- Pull requests
- Lines of code
- Code reviews
- Commits

These weren't perfect, but they worked because writing code was expensive. Engineers had to think carefully before committing code. The friction forced deliberation about whether something was actually worth building.

AI has fundamentally changed that equation.

Writing code is now cheap. Extremely cheap.

As a result, everyone (and their grandmother) can generate large volumes of code. The barrier to building something is no longer effort — it's judgment.

And that's where the real productivity problem begins.

Engineering leaders now need to understand which code actually drives business impact — and which doesn't. More importantly, incentives need to be aligned so that both humans and AI focus on writing high-impact code.

One useful way to think about this is by categorizing the types of code being written:

## 1. Prototypes

There are good prototypes and bad prototypes.

Good prototypes are experiments. An engineer is testing a hypothesis and doing pathfinding that informs technical or product strategy. Even personal learning can be valuable if it generates new insight.

Bad prototypes are just token wastage.

Think: cloning some product with a one-line prompt, building something flashy, and then throwing it away without learning anything meaningful.

## 2. New Products / Features

This is the work that eventually reaches customers.

But code isn't the main bottleneck here. Other constraints dominate:

- Users have limited attention — you can't spam features
- The feature must be financially viable
- It must integrate coherently with the rest of the product ecosystem

Feature velocity without product discipline creates noise, not value.

## 3. High-Value Fixes

These are small, targeted changes that move important business metrics:

- Revenue
- Cost efficiency
- User engagement
- Reliability

They often require a deep understanding of how multiple systems interact. Identifying these opportunities usually involves significant analysis and experience.

Ironically, these changes may involve very little code but very high impact.

## 4. Low-Value Fixes

Every engineering team accumulates long-tail issues: minor bugs, small annoyances, edge cases.

There can easily be dozens or hundreds of these. Many never get fixed — and often for good reason.

## 5. Refactors / Migrations

This is the cost of operating software systems.

Dependencies evolve, infrastructure changes, and migrations are necessary to keep the system healthy. Sometimes straightforward. Sometimes painful.

But unavoidable.

---

Here's the problem:

A huge portion of AI-generated code today falls into Category 1 (prototypes) and Category 4 (low-value fixes).

If organizations aren't careful, they will optimize for code volume instead of business impact.

What we actually need is the opposite:

- More Category 2 (new products/features)
- More Category 3 (high-value fixes)
- Better Category 1 prototypes that produce meaningful pathfinding

And far less noise.

As token usage (and AI infrastructure costs) continue to rise, observability into where those tokens translate into business impact becomes essential.

Without that visibility, organizations will continue celebrating their "AI-native transformation" while quietly wondering:

*Why are our AI costs exploding… but the business isn't moving?*
