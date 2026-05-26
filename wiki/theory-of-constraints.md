# Theory of Constraints

**Summary**: Goldratt's insight: every system has one bottleneck that limits throughput. Find it. Everything else is secondary.

**Sources**: Eliyahu Goldratt, "The Goal". "The Phoenix Project" (Kim, Behr, Spafford). Personal practice.

**Last updated**: 2026-05-26

---

The core idea: in any system, there is one constraint that determines the throughput of the whole. Optimising anything that is not the constraint does not improve the system. It may even make things worse.

Goldratt developed this in manufacturing. "The Phoenix Project" brought it into software and IT, making it much more concrete for developers and managers.

## The five focusing steps

1. **Identify** the constraint.
2. **Exploit** it — get the most out of it without spending money.
3. **Subordinate** everything else to the constraint.
4. **Elevate** the constraint — invest to increase its capacity.
5. **Repeat** — once the constraint moves, find the new one.

## Why this matters in software

Software teams routinely optimise the wrong thing. They speed up the build pipeline when the constraint is the code review queue. They hire more developers when the constraint is unclear requirements. They add monitoring when the constraint is deployment frequency.

The discipline of finding the actual constraint before acting is not natural. It requires stepping back from the urgency of local optimisation.

## Connection to the rest of the philosophy

Theory of Constraints applies at the system level what [[challenge-the-solution]] applies at the requirements level: stop solving the first problem you see. Find the real one.

It also connects to [[it-is-always-your-turn]] — knowing where the constraint is tells you where to point your agency.

## Related pages

- [[challenge-the-solution]]
- [[it-is-always-your-turn]]
- [[software-is-a-human-discipline]]
