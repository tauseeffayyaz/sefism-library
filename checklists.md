# Checklists

[← Back to the Sefism Library](README.md)

42 checklists on [sefism.com/checklists](https://www.sefism.com/checklists/). Go through a release, a codebase or your own career step by step: each check says how to verify it and how much it matters. The first 2 chapters of each are open to read, no account needed. Members keep the whole checklist, with progress and chapter quizzes, for 2 credits, and some are free in full.

- [Stacks and tools](#stacks-and-tools) (3)
- [Cloud and DevOps](#cloud-and-devops) (7)
- [Data and ML](#data-and-ml) (4)
- [Security](#security) (5)
- [AI](#ai) (6)
- [Career](#career) (11)
- [Build and earn](#build-and-earn) (5)
- [Students](#students) (1)

## Stacks and tools

### [Web Accessibility Checklist](https://www.sefism.com/checklists/web-accessibility-checklist/)

A practical web accessibility checklist built on WCAG 2.2 level AA, with a severity and a concrete way to verify every check.

- **Chapters:** 8, with 46 checks
- **For:** web developers and designers shipping to production

### [Web Performance Checklist](https://www.sefism.com/checklists/web-performance-checklist/)

A practical web performance checklist built on Core Web Vitals: LCP, INP and CLS, with a severity and a concrete way to verify every check.

- **Chapters:** 8, with 35 checks
- **For:** web developers shipping to production

### [Pull Request Checklist: Before You Open a PR](https://www.sefism.com/checklists/pull-request-checklist/)

A pull request checklist to run before you ask for review: scope and size, a clean diff, tests, a clear description, safe releases and a tidy branch, each with a way to verify it.

- **Chapters:** 8, with 37 checks
- **For:** developers opening pull requests

## Cloud and DevOps

### [Incident Response Checklist](https://www.sefism.com/checklists/incident-response-checklist/)

Prepare for and handle production incidents: on-call, severity levels, declaring, roles, mitigation, security containment, status updates and blameless postmortems.

- **Chapters:** 7, with 37 checks
- **For:** engineering teams that run production systems

### [Production Readiness Checklist](https://www.sefism.com/checklists/production-readiness-checklist/)

Check a service before it takes real traffic: ownership, SLOs, capacity, timeouts and retries, alerts, rollout and rollback, backups, security and on-call.

- **Chapters:** 7, with 37 checks
- **For:** teams launching or inheriting a service

### [Kubernetes Production Checklist](https://www.sefism.com/checklists/kubernetes-production-checklist/)

Verify a workload and its cluster before real traffic: requests and limits, probes, PDBs, spread, Pod Security, RBAC, network policies, secrets, images, autoscaling, upgrades and backups.

- **Chapters:** 9, with 46 checks
- **For:** teams taking a workload to production on Kubernetes

### [Cloud Cost Optimization Checklist](https://www.sefism.com/checklists/cloud-cost-optimization-checklist/)

FinOps for engineers: tagging and allocation, budgets and anomaly alerts, rightsizing, scheduling, commitments, storage lifecycle, egress, idle resources and unit cost metrics.

- **Chapters:** 9, with 37 checks
- **For:** engineers who own cloud workloads and their bill

### [Disaster Recovery Checklist](https://www.sefism.com/checklists/disaster-recovery-checklist/)

Backups and DR you can prove: RPO and RTO per system, backup coverage, off-site and immutable copies, restore tests, zone and region choices, runbooks, drills, dependencies and communication.

- **Chapters:** 7, with 39 checks
- **For:** teams responsible for data and uptime

### [Software Supply Chain Security Checklist](https://www.sefism.com/checklists/software-supply-chain-security-checklist/)

Check your dependencies and builds before a release: lockfiles, update bots, pinned actions, CI permissions, SLSA provenance, Sigstore signing, SBOMs and a plan for a compromised package.

- **Chapters:** 9, with 44 checks
- **For:** teams that build, publish or deploy software

### [Database Migration Checklist](https://www.sefism.com/checklists/database-migration-checklist/)

Check a schema or data migration before it ships: expand and contract, lock behaviour, online indexes, batched backfills, rehearsal on real data, backups, rollback, deploy order and monitoring.

- **Chapters:** 11, with 49 checks
- **For:** backend developers and anyone who ships schema changes

## Data and ML

### [ML Model Deployment Checklist](https://www.sefism.com/checklists/ml-model-deployment-checklist/)

An ML model deployment checklist: baselines, training and serving consistency, validation, model registry, canary rollout, rollback, drift monitoring and ownership, with how to verify each.

- **Chapters:** 7, with 30 checks
- **For:** engineers putting ML models into production

### [Data Quality Checklist](https://www.sefism.com/checklists/data-quality-checklist/)

A data quality checklist for warehouse tables: ownership, freshness, volume, schema, nulls, uniqueness, referential checks, anomaly monitoring and data incidents, with how to verify each.

- **Chapters:** 8, with 33 checks
- **For:** data engineers and analysts who own tables

### [Analytics Dashboard Checklist](https://www.sefism.com/checklists/analytics-dashboard-checklist/)

An analytics dashboard checklist for launch day: purpose and audience, metric definitions, data freshness, correctness, performance, access, accessibility, ownership and adoption.

- **Chapters:** 9, with 32 checks
- **For:** analysts and engineers launching dashboards

### [Data Privacy Checklist for Engineers and Analysts](https://www.sefism.com/checklists/data-privacy-checklist/)

A data privacy checklist for people who build with personal data: inventory, minimization, PII classification, pseudonymization, retention, access, transfers, logging, vendors and breaches.

- **Chapters:** 11, with 40 checks
- **For:** engineers and analysts handling personal data

## Security

### [Web Application Security Checklist](https://www.sefism.com/checklists/web-app-security-checklist/)

A practical web application security checklist built on the OWASP Top 10:2025 and ASVS 5.0, with a severity and a way to verify every check.

- **Chapters:** 8, with 35 checks
- **For:** web developers shipping to production
- **Free in full**

### [API Security Checklist](https://www.sefism.com/checklists/api-security-checklist/)

Check your REST or GraphQL API against the OWASP API Security Top 10: authentication, object authorization, rate limits, input validation, SSRF, CORS and logging.

- **Chapters:** 7, with 35 checks
- **For:** backend and full-stack developers

### [Linux Server Hardening Checklist](https://www.sefism.com/checklists/linux-server-hardening-checklist/)

Harden an Ubuntu, Debian or RHEL server step by step: accounts and sudo, SSH, updates, firewall and open ports, permissions, logging and CIS benchmark scans.

- **Chapters:** 7, with 38 checks
- **For:** developers who run their own Linux servers

### [AWS Account Security Checklist](https://www.sefism.com/checklists/aws-account-security-checklist/)

Lock down an AWS account: root user, IAM Identity Center, roles instead of keys, CloudTrail, GuardDuty, S3 Block Public Access, IMDSv2 and guardrails.

- **Chapters:** 8, with 38 checks
- **For:** developers and small teams running on AWS

### [Mobile App Security Checklist](https://www.sefism.com/checklists/mobile-app-security-checklist/)

Check an Android or iOS app against OWASP MASVS: data storage, network security, authentication, platform interaction, code quality, resilience and privacy.

- **Chapters:** 8, with 36 checks
- **For:** Android, iOS and cross-platform developers

## AI

### [RAG Production Checklist](https://www.sefism.com/checklists/rag-checklist/)

A RAG production checklist: chunking, embeddings, hybrid search, reranking, per-user permissions, citations, evals, re-indexing and cost, with how to verify each check.

- **Chapters:** 7, with 30 checks
- **For:** developers shipping retrieval-augmented generation

### [LLM Evaluation Checklist](https://www.sefism.com/checklists/llm-evaluation-checklist/)

An LLM evaluation checklist: success criteria, eval datasets, code and model graders, judge calibration, agent evals, safety tests and production monitoring, with how to verify each check.

- **Chapters:** 7, with 32 checks
- **For:** developers testing LLM features and agents

### [AI Feature Launch Checklist](https://www.sefism.com/checklists/ai-feature-launch-checklist/)

An AI feature launch checklist: use case fit, evals, UX for errors, disclosure, human override, abuse filters, rate limits, cost caps, prompt privacy, monitoring and rollback.

- **Chapters:** 8, with 34 checks
- **For:** teams shipping an LLM feature to real users

### [AI Agent Security Checklist](https://www.sefism.com/checklists/ai-agent-security-checklist/)

An AI agent and MCP security checklist: least-privilege tools, MCP server auth, prompt injection through tool output, approvals, sandboxing, secrets, audit logs and supply chain.

- **Chapters:** 8, with 37 checks
- **For:** developers shipping agents, tools and MCP servers

### [EU AI Act Readiness Checklist](https://www.sefism.com/checklists/eu-ai-act-readiness-checklist/)

An EU AI Act readiness checklist for teams building or deploying AI: scope and roles, prohibited practices, risk classification, transparency, GPAI duties, oversight and dates.

- **Chapters:** 7, with 32 checks
- **For:** teams building or deploying AI that reaches EU users

### [LLM Cost Optimization Checklist](https://www.sefism.com/checklists/llm-cost-optimization-checklist/)

An LLM cost optimization checklist: cost per request, model routing, prompt caching, batch APIs, trimming context, output limits, response caching, retries, budgets and alerts.

- **Chapters:** 8, with 31 checks
- **For:** developers paying for LLM APIs in production

## Career

### [LinkedIn Profile Checklist for Developers](https://www.sefism.com/checklists/linkedin-profile-checklist/)

Check your LinkedIn profile section by section: photo, headline, About, Experience, Featured, Skills, custom URL, Open to Work, posting and privacy.

- **Chapters:** 7, with 30 checks
- **For:** developers, students and fresh graduates
- **Free in full**

### [GitHub Profile Checklist for Developers](https://www.sefism.com/checklists/github-profile-checklist/)

Check your GitHub profile part by part: name, photo and bio, profile README, pinned repositories, project READMEs, licences, contribution graph, commit email and account security.

- **Chapters:** 7, with 30 checks
- **For:** developers, students and fresh graduates

### [First 90 Days in a New Developer Job: Checklist](https://www.sefism.com/checklists/first-90-days-developer-checklist/)

What to do before day one, in week one and by day 30, 60 and 90 in a new developer job: setup, codebase, first PR, your manager, questions and feedback.

- **Chapters:** 7, with 32 checks
- **For:** new hires, interns and fresh graduates

### [Freelance Developer Client Checklist](https://www.sefism.com/checklists/freelance-developer-client-checklist/)

Run every freelance client project the same safe way: qualify the client, scope, proposal, contract, deposits, international payments, changes, handover and red flags.

- **Chapters:** 8, with 35 checks
- **For:** freelance and part-time developers

### [Open Source Contribution Checklist](https://www.sefism.com/checklists/open-source-contribution-checklist/)

Make your first and next open source contributions the way maintainers expect: pick a healthy project, read the rules, claim an issue, fork, open a clean pull request and handle review.

- **Chapters:** 8, with 38 checks
- **For:** students and developers new to open source

### [Remote Developer Job Checklist](https://www.sefism.com/checklists/remote-job-checklist/)

Land a remote developer job safely and do well in it: spot fake employers, read the contract, get paid across borders, set up your workspace, work across time zones and asynchronously.

- **Chapters:** 8, with 38 checks
- **For:** developers working remotely for teams abroad

### [Relocating Abroad for a Tech Job: Developer Checklist](https://www.sefism.com/checklists/relocating-abroad-developer-checklist/)

Move abroad for a developer job step by step: research visa routes on official sites, check the offer and sponsor, avoid immigration scams, prepare documents and money, and settle in.

- **Chapters:** 7, with 34 checks
- **For:** developers moving abroad for work

### [Job Offer Evaluation Checklist for Developers](https://www.sefism.com/checklists/job-offer-evaluation-checklist/)

Compare and accept a developer job offer with your eyes open: total pay, equity basics, notice, IP and non-compete clauses, benefits, remote terms, team, growth and negotiating politely.

- **Chapters:** 8, with 38 checks
- **For:** developers holding one or more job offers

### [Layoff Preparedness Checklist for Developers](https://www.sefism.com/checklists/layoff-preparedness-checklist/)

Prepare for a layoff before it happens and act well if it does: emergency fund, documents and contacts, severance, benefits, references, a record of your work and a plan for the search.

- **Chapters:** 8, with 35 checks
- **For:** developers worried about or facing a layoff

### [Career Switch into Tech Checklist](https://www.sefism.com/checklists/career-switch-into-tech-checklist/)

Move into software from another field step by step: choose a direction, follow a learning plan, build proof of skill, use your previous domain, network, plan your runway and target a first role.

- **Chapters:** 7, with 31 checks
- **For:** people moving into software from another career

### [Developer Portfolio Website Checklist](https://www.sefism.com/checklists/portfolio-website-checklist/)

Check your developer portfolio site end to end: clear intro, 3 to 5 strong projects, live demos and code, speed, accessibility, SEO basics, custom domain, contact, analytics and upkeep.

- **Chapters:** 8, with 40 checks
- **For:** developers, students and fresh graduates

## Build and earn

### [App Store and Google Play Launch Checklist](https://www.sefism.com/checklists/app-store-launch-checklist/)

Launch a mobile app on the App Store and Google Play: accounts, build rules, review guidelines, privacy labels, Data safety, listing, in-app purchases, testing, crashes and staged rollout.

- **Chapters:** 9, with 37 checks
- **For:** developers shipping their own or a client's mobile app

### [Getting Paid Internationally Checklist for Freelancers](https://www.sefism.com/checklists/getting-paid-internationally-checklist/)

Get paid by foreign clients safely: agree currency and fees, send proper invoices, choose a payment platform available in your country, keep records for tax and follow your own country's rules.

- **Chapters:** 6, with 26 checks
- **For:** freelancers and contractors paid from abroad

### [Freelance Platform Profile Checklist](https://www.sefism.com/checklists/freelance-platform-profile-checklist/)

Build a freelance profile that wins work on Upwork, Fiverr, Toptal or Contra: niche, title, overview, portfolio, rates, first jobs, proposals, reviews, and each platform's rules and fees.

- **Chapters:** 9, with 31 checks
- **For:** developers starting on freelance marketplaces

### [Selling Digital Products Checklist for Developers](https://www.sefism.com/checklists/selling-digital-products-checklist/)

Sell templates, starter kits, e-books, courses or plugins the safe way: product choice, licensing, platforms, merchant of record, pricing, delivery, refunds, taxes, marketing and updates.

- **Chapters:** 9, with 38 checks
- **For:** developers selling their own digital products

### [Indie Product Launch Checklist for Developers](https://www.sefism.com/checklists/indie-product-launch-checklist/)

Launch a side project or indie product properly: validate the idea, cut scope, build a landing page, take payments, handle tax basics and legal pages, measure, launch, support users and iterate.

- **Chapters:** 8, with 36 checks
- **For:** developers launching a side project or indie product

## Students

### [FYP Team and Supervisor Checklist](https://www.sefism.com/checklists/fyp-team-and-supervisor-checklist/)

Run your final year project team well: pick teammates, choose a supervisor, meet and take notes, split work fairly, use Git as a team, keep evidence and handle a teammate who does not contribute.

- **Chapters:** 8, with 34 checks
- **For:** final year and capstone project teams
- **Free in full**

---

Generated from [sefism.com](https://www.sefism.com/) on 2026-10-31. The site is always the latest version.

<sub>Sefism is an independent project by Tauseef Fayyaz. It is not affiliated with, endorsed by, or operated on behalf of any current or former employer. All views are my own.</sub>
