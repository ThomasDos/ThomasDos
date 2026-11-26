# Thomas Dos Anjos

**Senior AI Engineer · Tech Lead · Full Stack Developer**\
Freelance, fully remote from France · French native, fluent English

I design and ship AI agents (LLMs, RAG) and web applications, including public services used at national scale, with documented code your team can take over.

## Now

* **Quaesis**: cofounder, CTO & CPO of a generative AI platform for accounting and audit firms
* **IGN**, the French national mapping agency: freelance Product Engineer on the National Building Register (RNB) and the National Address Database (BAN)

## Selected work

### [Quaesis](https://quaesis.com)
AI workflows for accounting and audit firms · sole developer
* Users describe their method in plain language; Quaesis turns it into a workflow, runs it with human review at the steps they choose and returns a checked deliverable.
* Hybrid RAG over 133,000 passages of official sources (law, tax doctrine, accounting standards), with verified citations and a recall@10 of 0.95 on an evaluation set.
* Model routing by task with automatic fallback, data pseudonymised before any LLM call, signed audit trail with RFC 3161 timestamps.

### [Mentiora AI](https://www.mentiora.ai) (2025 to 2026)
Swiss AI agent platform for customer experience · [mentiora-sdk](https://github.com/mentiora-ai/mentiora-sdk)
* Was one of the first developers, in an English speaking team led by a former Google DeepMind tech lead.
* Built the Zendesk connector that lets the agent handle tickets and hand over to a human in real time, with full context.
* Designed hybrid RAG isolated per client for healthcare and finance customers, traced with OpenTelemetry.
* Launched the TypeScript and Python SDKs; migrated agent orchestration from LangChain and LangGraph to Vercel AI SDK and Mastra.

### [National Building Register](https://rnb.beta.gouv.fr) and National Address Database
IGN · [RNB-coeur](https://github.com/fab-geocommuns/RNB-coeur)
* RNB: about 45 million buildings, 75 million API calls to date. Zero downtime API deployments, automatic restart of interrupted imports, an alert on every failure.
* Two factor authentication for password and ProConnect sign in, upgrade to PostgreSQL 17, leaner database on Scaleway (22.5 GB of unused indexes dropped).
* BAN: hiring and training the team, and running the handover of the service to IGN.

### [France VAE](https://vae.gouv.fr) (2023 to 2026)
National public service for the recognition of prior learning · [betagouv/reva](https://github.com/betagouv/reva)
* The service reached 53,000 candidates in 2025; average time to certification went from 18 to 8 months.
* One of the two main developers for three years: 1,994 commits, second largest contributor to the project.
* Fully online eligibility file, FranceConnect sign in through Keycloak, interoperability API for certifiers, pentest remediation and two factor authentication.

### Also built
* [ClassifIA](https://github.com/betagouv/classifia), solo: classifies support conversations with Albert, the French government's LLM, and vector similarity, to surface recurring topics for the product roadmap.
* [Dotations Locales](https://github.com/ThomasDos/dotations-locales), lead frontend: simulation of state grants for every French local authority, built from scratch with the government design system (DSFR), accessibility and Playwright tests.

Earlier: Tech Lead of an AI training marketplace (LangGraph agents), Familiar (hotel CRM, Temporal), Zelty (point of sale used by 4,000 restaurants), Air Liquide Healthcare (React Native), SNCF.

## How I can help

* **Build**: ship your AI product or feature, from scratch or on your existing codebase.
* **Embed**: join your team as a senior Full Stack and AI developer.
* **Lead**: take the Tech Lead role (architecture, code review, hiring, mentoring).

Full time or part time, for a few weeks or for many months.

## Stack

* **AI**: LangGraph, LangChain, Vercel AI SDK, Mastra, OpenAI, Anthropic, pgvector, Langfuse
* **Web**: TypeScript, Python, React, Next.js, NestJS, Node.js, FastAPI, Django, GraphQL, PostgreSQL, PostGIS
* **Infra**: Docker, Kubernetes, Terraform, GCP, Scaleway, GitHub Actions, OpenTelemetry

## Contact

Open to remote freelance work in France, Switzerland, the US and beyond.

[LinkedIn](https://www.linkedin.com/in/thomasdosanjos/) · [Malt](https://www.malt.fr/profile/thomasdosanjos) · [dosanjos.thomas@gmail.com](mailto:dosanjos.thomas@gmail.com)

Off keyboard: PADI scuba diving instructor; I have worked across Asia, Europe, the Americas and the Pacific.
