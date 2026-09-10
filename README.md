## Joseph DeVille, GTM Engineer

I build the internal systems that go-to-market teams run on. Not just CRM configuration: TypeScript services, AI agents against live revenue data, and the guardrails that let both run unattended.

Most recently the in-house GTM Engineer at Cortex, where the systems I shipped were credited with influencing $1.57M in pipeline.

### Public work

**[GTM Account Intelligence](https://github.com/josephdeville/sanity-gtm-account-intelligence)** · [live demo](https://jd-sanity-gtm-brief.netlify.app)

A Claude agent scores ICP accounts by buying signal and writes structured briefs into Sanity Content Lake, rendered as a ranked queue in Studio. Every brief clears a coded eval rubric before it publishes: grounding, score consistency, evidence behind competitor claims, confidence calibration. Clean briefs auto-publish, flagged ones stay drafts for a human. Speed from the model, trust from the rubric.

Built on Sanity itself, in an afternoon. The dataset is public, so you can query Content Lake without credentials.

**[GTM Context Engine](https://github.com/josephdeville/ClaudeGTM)**

Domain in, GTM playbook out. ICP segments, buyer personas, battlecards, a qualification framework, and outreach sequences, generated as one structured artifact instead of a research doc somebody still has to translate into work.

### Systems built at Cortex

The code belongs to Cortex and stays private. The shape is the part worth reading.

**Lead delivery that reps actually used.** BDRs were building their own lists off Salesforce reports, which meant every rep worked a different definition of a good account. I moved delivery into a Slack bot: leads arrive with a personalized opener, the underlying Salesforce report linked at the end for anyone who wants to audit it. Reps stopped building their own lists, and open rates went up.

**Account research agents.** Claude-based, running against Salesforce, Gong and Neon Postgres, producing account briefs and personalization at a volume no one was going to do by hand.

**Preflight checks on every integration.** Nothing touches a user until its dependencies answer. A silent API failure raises an alert instead of quietly writing bad data into the CRM for a week before anyone notices.

### How I build

Prompt caching, because an unattended agent gets expensive faster than anyone budgets for.

Evals, because "it looked right when I tested it" is not a quality bar you can put a revenue system on.

Integration health checks, because the failure that hurts is never the loud one.

I came up through cloud administration, 600+ devices and MDM at scale, then SDR, then engineering. That order shapes the work. I've been the person whose week gets wrecked by a bad sync, so I build for the operator who has to live with the system, not for the demo.

### Elsewhere

[Portfolio](https://josephdeville.github.io) · [LinkedIn](https://www.linkedin.com/in/joseph-deville/) · josephdeville523@gmail.com
