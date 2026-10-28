# The forgewright-ai family

**Craft well. Quality and privacy first. Earn trust. Grow.**

We build useful, focused tools that help people learn, create and work on
machines they own and control. Technology should serve the person using it;
AI is an optional capability, never a requirement for the whole experience.

## Shared direction, distinct responsibilities

- **forgewright-ai** holds the shared vision and principles.
- **spark** focuses on local AI, models, memory, shell intelligence and
  controlled execution.
- **spark-shell** provides the terminal environment and an optional Linux
  desktop, functional without AI.
- **spark.forgewright.ai**, the website, carries the documentation, learning
  and public reports.

Repeatable engineering, scaffolding and distribution practices support the
family without becoming product dependencies. Each product stays focused and
can evolve independently through thin, explicit interfaces. Each spark app
lives in its own `spark-<app>` repository as a client of spark's documented
surfaces, installed the app's own way.

## Engineering philosophy

- **Local first, private by design.** Put user ownership and control at the
  center of data, models and execution. Make any external data flow explicit.
- **Use the platform well.** Prefer native operating system capabilities over
  duplicating them. Add infrastructure only when a demonstrated need justifies it.
- **Keep products minimal and modular.** Avoid mandatory AI, feature bloat and
  unnecessary coupling. Integrations should preserve independent usefulness.
- **Make actions understandable.** Explain consequential actions, seek
  confirmation where appropriate and favor reversible operations.
- **Build quality before expanding.** Treat accessibility, reliability,
  security and maintainability as foundations, not later additions.
- **Earn trust with evidence.** Communicate capabilities and limitations
  honestly. Support claims with verification and distinguish intent from
  demonstrated behavior.
- **Grow through learning.** Improve from real use, feedback and independent
  review while keeping the scope deliberate.

## Collaboration and authority

People remain responsible for decisions. AI implementers and independent
reviewers support the work; review and evidence determine readiness. Use GitHub
to preserve approved decisions and implementation history.

This document is the canonical family vision and engineering philosophy.
Each product repository remains authoritative for its architecture, technical
contracts, implementation, tests and releases. Keep those details there and
link to them when needed rather than duplicating them here.

Keep shared public documentation safe to publish: omit private repository
inventory, sensitive infrastructure details and internal assessments.
