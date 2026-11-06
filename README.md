## Joseph DeVille

GTM engineer who builds AI outbound engines across signal detection, account research, contact discovery, personalization, sequencing, and CRM sync. HubSpot specialist with Salesforce range, holding Salesforce Certified Platform Administrator, HubSpot Revenue Operations Administrator, and Clay Automated Outbound certifications.

### Outbound engines

**[AI SDR Engine](https://github.com/josephdeville/ai-sdr-engine)**
AI SDR engine featuring an automated account research, personalization, and sequencing pipeline. Orchestrates multi-step agent reasoning to evaluate target accounts, identify buying committee personas, generate personalized outreach, and coordinate outbound delivery.

**[GTM Account Intelligence](https://github.com/josephdeville/sanity-gtm-account-intelligence)** · [Live Demo](https://jd-sanity-gtm-brief.netlify.app)
Claude agent that scores target accounts against buying signals (competitor tech stack, headless frontend readiness, job postings, digital footprint, timing) and writes structured briefs into Sanity Content Lake. Governed by a coded eval rubric checking grounding, score consistency, and evidence before publishing to a ranked rep queue in Studio, holding flagged accounts for human review.

**[GTM Context Engine](https://github.com/josephdeville/ClaudeGTM)**
Domain-in, GTM-playbook-out engine built with Claude and TypeScript. Analyzes company domains to generate structured outbound strategy assets including ICP segments, buyer personas with pain points and objection handling, competitive battlecards, qualification scoring frameworks, and ready-to-use email and LinkedIn outreach sequences. Includes both CLI and web interfaces.

### Private client builds (live demo on request)

- **Legal-industry origination engine:** Multi-step agent pipeline that tracks lateral hiring and practice expansion signals to score prospective firms and generate tailored partner outreach.
- **Contact-center outbound engine:** Outbound research system that identifies customer operations leaders, detects support infrastructure gaps, and triggers personalized sequences.
- **Clay GTM enrichment workflow:** Waterfall enrichment pipeline combining multiple data providers to verify contact details, map buying committees, and populate custom outbound attributes.
- **LinkedIn Sales Navigator prospecting workflow:** Prospecting engine automating search extraction, ICP qualification, and decision-maker mapping with bi-directional CRM synchronization.
- **BDR API service:** Custom webhook service and API microservice providing sales reps with on-demand account research dossiers and personalized openers.

### How I build

- **Signals:** Ingest first-party and third-party buying signals (job postings, tech stack changes, funding, leadership hires) via webhooks and external APIs.
- **Account intel:** Run LLMs with tool calling to research accounts, score ICP fit, and extract competitive context into structured schemas.
- **Buying committee:** Map economic buyers, champions, and evaluators across Apollo, Clay, and LinkedIn Sales Navigator for multi-threaded account coverage.
- **Personalization:** Generate role-specific value props and objection handling grounded in verified account triggers rather than generic templates.
- **Multichannel:** Orchestrate coordinated email and LinkedIn touches with custom tracking domains, inbox rotation, and deliverability monitoring.
- **CRM sync:** Bi-directional sync across HubSpot and Salesforce enforcing deduplication, lead-to-account matching, and clean stage progression.
- **Measurement:** Monitor meeting booking rates, reply sentiment, and pipeline attribution to iteratively tune scoring models and messaging angles.
- **Human-in-the-loop:** Automated eval rubrics test output grounding and calibration; high-confidence leads queue automatically while edge cases route to reps for review.
- **Failure handling:** Preflight integration health checks, API rate limiting, schema validation, and dead-letter alerting prevent silent failures and keep bad data out of the CRM.

### Stack

HubSpot, Salesforce, Clay, Apollo, LinkedIn Sales Navigator, Python, TypeScript, Node.js, REST APIs, Webhooks, LLM tool calling, evals

### Contact

[Portfolio](https://josephdeville.github.io) · [LinkedIn](https://www.linkedin.com/in/joseph-deville/) · josephdeville523@gmail.com
