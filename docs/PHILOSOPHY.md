# Philosophy

linux consumer labs exists because "Just Works" is an experience, not a feature checklist. Consumers do not care about package formats, init systems, or desktop theology. They care whether things work predictably when they sit down to use their computer.

Our philosophy is deliberately provocative for a Linux-focused organization. It is not provocation for its own sake — it is a research method.

## 1. Exploring What-Ifs

Linux development culture often optimizes for correctness, composability, and user sovereignty. Those are virtues. They are also not always the same virtues that produce a frictionless first-run experience.

We treat **what-if** questions as legitimate research instruments:

- What if we optimized for recovery instead of configuration?
- What if we hid complexity by default and exposed it progressively?
- What if we accepted a little less flexibility in exchange for a lot less failure?

A what-if is not a proposal. It is a lens. Many will not survive contact with evidence. That is expected.

## 2. Exploring How Other OSes Fix These Issues

Other operating systems are not enemies or idols. They are **comparative data**.

When macOS handles sleep/wake reliably, when Windows delivers a driver without asking the user to understand PCI IDs, when ChromeOS updates silently — we ask:

1. What problem is being solved?
2. What invariant does the platform enforce to make that possible?
3. Which invariants are unacceptable on Linux?
4. Which could be approximated in userland?

We reject both blind imitation and reflexive dismissal.

## 3. Not Strictly Following Linux Practices

"That's not how we do it on Linux" is an observation, not a conclusion.

Linux has accumulated practices — some essential, some historical accident, some optimized for a different user than today's consumer. We document the trade-offs honestly:

| Practice | Consumer benefit | Consumer cost |
|----------|------------------|---------------|
| Maximum choice | Power, self-determination | Decision fatigue, inconsistent UX |
| Package fragmentation | Distro identity | App availability gaps |
| Terminal-first recovery | Precision | Excludes most users |

We are not here to abolish Linux culture. We are here to **measure** where it helps consumers and where it does not.

## 4. Not Fighting the Linux Kernel But Working Alongside It

The kernel is a foundation, not an opponent.

We do not pursue research that requires:
- Maintaining hostile forks of core infrastructure
- Disabling security models for convenience
- Promising "just works" by bypassing the kernel's contract with hardware

We *do* pursue research that:
- Uses existing kernel capabilities better
- Builds policy and UX layers above stable interfaces
- Pushes for upstream improvements with evidence, not slogans
- Accepts hard limits and designs around them transparently

## Research Outputs We Value

1. **Honest failure reports** — "We tried X; it fails because Y" is valuable
2. **Constraint maps** — what is fixed by kernel, distro, DE, app, or policy
3. **Portable patterns** — ideas a distro or DE could adopt without owning the whole stack
4. **Small prototypes** — one hypothesis, one demo, clear boundaries

## What Success Looks Like

Success is not "Linux becomes macOS."

Success is: a maintainer, distro lead, or upstream developer reads our work and says *"I hadn't framed the problem that way — and now I see a path I can actually ship."*

That is the bar.
