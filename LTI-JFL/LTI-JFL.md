# LTI Design Package

## Context and assumptions

This document defines **LTI** as a **collaboration-first, automation-heavy, AI-assisted full-cycle Applicant Tracking System (ATS)** for **employer-side mid-market knowledge-work companies**.

### Extracted baseline product scope
From the uploaded project description, the baseline LTI scope covers the full hiring cycle, including:
- job creation,
- job publishing,
- application intake,
- review and screening,
- assessments,
- interview scheduling,
- hiring,
- and onboarding handoff.

This extracted scope is used as supporting product context, but it does **not** define the final product strategy, prioritization, or business model.

### Working assumptions
- Initial ICP: employer-side mid-market companies with roughly **100–1000 employees**
- Primary hiring context: **knowledge-work roles** with recruiter + hiring manager collaboration
- Initial go-to-market: **English-first**, likely US / international English-speaking customers first
- Product strategy: **best-of-breed recruiting system**, not a full HRIS/HCM suite and not a staffing-agency CRM
- AI strategy: **assistive, explainable, auditable, human-in-the-loop**, not fully autonomous hiring decisioning

---

## 1. Brief description of the LTI software, added value, and competitive advantages

### What LTI is
LTI is a **full-cycle ATS** designed to help mid-market hiring teams run a faster, more consistent, and more collaborative hiring process from requisition to onboarding handoff. The product is optimized not just for recruiters, but for the **entire hiring team**: recruiters, hiring managers, interviewers, coordinators, and talent leaders.

### Core value proposition
**LTI helps recruiters and hiring managers make faster, better hiring decisions by combining structured workflows, real-time collaboration, workflow automation, recruiting-operations intelligence, and trustworthy AI assistance.**

### Why this business model is attractive
The ATS market is crowded, but there is still strong replacement demand. Aptitude Research reports that **1 in 4 companies are replacing their ATS in 2025**, **82% say their current system has significant functionality gaps**, and only **22% believe their ATS alone can support true talent transformation**.[^aptitude]

This means a new entrant should not try to win as a generic ATS. It should win by solving a sharper problem better than incumbents. LTI's chosen wedge is:

> **Make hiring teams work better together, reduce manual coordination, and improve decision quality with structured workflows and practical AI.**

### Added value
LTI's added value comes from five sources:

1. **Better recruiter–manager alignment**  
   Shared hiring plans, role calibration, scorecards, interview kits, action tracking, and clearer decision ownership.

2. **Lower operational burden**  
   Automation reduces chasing, scheduling overhead, status management, and approval bottlenecks.

3. **Better hiring signal**  
   Candidate information is turned into structured evidence and decision-ready summaries instead of document overload.

4. **Better process visibility**  
   Real-time analytics show what is stuck, where candidates drop, and which stakeholders are slowing the funnel.

5. **Safer, more useful AI**  
   AI is used to summarize, draft, highlight, and recommend — not to make opaque final hiring decisions.

### Competitive advantages
LTI's most defensible competitive advantages should be:

#### 1) Collaboration-first design
Many ATS products support collaboration, but fewer make it the center of the product. LTI should be designed so hiring managers have a clear, low-friction operating experience instead of being occasional users forced into recruiter-centric workflows.

#### 2) Workflow automation across the full recruiter–manager loop
The product should automate not only candidate emails or isolated triggers, but the operational glue of hiring: reminders, approvals, escalations, interview coordination, and handoffs.[^workable]

#### 3) Recruiting operations intelligence as a core product layer
Analytics should not be a reporting afterthought. LTI should surface bottlenecks, feedback latency, stage conversion issues, and application friction in real time, following the direction validated by analytics-forward products like Ashby.[^ashby]

#### 4) Trustworthy AI assistance embedded in actual workflows
AI should accelerate the tasks teams already do — candidate summarization, interview prep, debrief synthesis, communication drafting, next-best-action recommendations — while preserving human judgment and auditability. This matters especially because employment-related AI use cases are treated as **high-risk** under the EU AI Act.[^ai-act]

#### 5) Signal-rich, low-friction candidate intake
LTI should reduce repetitive candidate effort and improve recruiter signal at the same time by extracting structured data from CVs, minimizing duplicate forms, supporting better alternatives to generic cover letters, and surfacing evidence-based summaries.

### Honest assessment
This strategy is attractive, but not easy.

LTI will compete against vendors that already cover parts of this story: Greenhouse on structured hiring, Ashby on analytics, Workable on practical automation, Teamtailor on candidate experience and collaboration, and others.[^greenhouse][^ashby][^workable]

Therefore, LTI will only win if the following are genuinely strong in the product:
- hiring-manager experience,
- workflow automation,
- real-time operational visibility,
- and practical AI usefulness.

If those are shallow, LTI risks becoming another mid-market ATS with familiar messaging and no compelling reason to switch.

---

## 2. Explanation of the main functions

The goal is **not** to build every ATS feature equally. The goal is to be excellent in the feature areas that directly support the strategic wedge.

### Main functionality set

#### A. Structured hiring workflow
**Why it matters:** This is the operating backbone of the product. Structured hiring is still one of the clearest sources of hiring quality improvement and recruiter–manager alignment.[^greenhouse]

**What it includes:**
- Requisition creation and approval
- Role brief and hiring plan
- Standardized pipeline stages
- Scorecard design
- Interview kits and interviewer guidance
- Decision framework and final hiring log

**Why it is a success driver:** Without this layer, LTI cannot credibly improve consistency or decision quality.

---

#### B. Hiring-manager collaboration workspace
**Why it matters:** In mid-market recruiting, many bottlenecks come from delayed manager reviews, incomplete feedback, unclear role alignment, and inconsistent interview participation.

**What it includes:**
- Shared recruiter–manager kickoff workspace
- Manager inbox for pending reviews, approvals, and feedback
- Candidate context view tailored to manager needs
- Debrief workspace with structured evidence
- Decision history by stakeholder and criterion
- SLA visibility for delayed actions

**Why it is a success driver:** This is the strongest differentiator. If LTI becomes the ATS that hiring managers actually like using, that creates real preference and retention power.

---

#### C. Workflow automation engine
**Why it matters:** Recruiters spend too much time coordinating people rather than making decisions. Automation is a direct efficiency lever.[^workable]

**What it includes:**
- Reminders for review, approval, and feedback deadlines
- Escalations for stalled actions
- Automated candidate communication by stage
- Interview scheduling flows and fallback rules
- Offer routing and approval flows
- Post-acceptance onboarding handoff triggers
- Duplicate candidate detection and merge support

**Why it is a success driver:** This functionality produces visible ROI quickly by reducing administrative work and time-to-hire.

---

#### D. Recruiting operations intelligence
**Why it matters:** Modern ATS buyers increasingly expect their recruiting platform to explain what is broken and how to improve it, not just store data.[^ashby]

**What it includes:**
- Time in stage by role and team
- Hiring-manager responsiveness
- Feedback completion rate and delay alerts
- Source-to-hire funnel analysis
- Stuck-role diagnostics
- Application drop-off and completion analytics
- Offer acceptance and late-stage leakage visibility

**Why it is a success driver:** This turns LTI from a workflow system into a decision-support system.

---

#### E. Trustworthy AI assistance layer
**Why it matters:** Recruiters face more volume and more noise. LinkedIn reports that applicants per open role in the US have doubled since spring 2022, while recruiters still struggle to find qualified talent efficiently.[^linkedin]

**What it includes:**
- CV and application summarization
- Structured evidence extraction from CV + answers + optional cover letter
- Candidate-to-role relevance summary
- Interview brief generation per interviewer
- Debrief summary generation
- Draft candidate communications
- Next-best-action recommendations
- Safe, structured candidate feedback drafting

**Why it is a success driver:** AI should reduce reading, writing, and coordination work without becoming a black-box gatekeeper.

**Guardrails:**
- No hidden ranking logic as the final decision basis
- No fully autonomous rejection logic
- No unsupported claims about candidate suitability
- Human review on sensitive actions
- Auditability for AI-generated suggestions

---

#### F. Signal-rich, low-friction candidate intake
**Why it matters:** Long and repetitive applications hurt candidate conversion and do not necessarily improve recruiter signal.

**What it includes:**
- CV upload with extract-first / confirm-second flow
- Autofill with explicit candidate confirmation
- Role-adaptive application requirements
- Optional structured motivation prompts instead of generic cover letters
- Candidate application save/resume flow
- Recruiter-facing evidence summary of candidate inputs

**Why it is a success driver:** It improves candidate experience and recruiter efficiency at the same time.

---

#### G. Offer and onboarding handoff
**Why it matters:** A weak end-of-funnel handoff reduces the perceived completeness of the ATS and creates re-entry work.

**What it includes:**
- Offer creation and approval
- Offer acceptance tracking
- Transition checklist to onboarding / HRIS handoff
- New-hire packet / data handoff workflow

**Why it is a success driver:** It reinforces the “full-cycle” promise of LTI and improves operational continuity.

### What should not be over-positioned as differentiation
LTI should still support these, but they are not the core wedge:
- job board publishing,
- careers page basics,
- standard integrations,
- generic email templates,
- standard reports and exports,
- basic parsing.

These are expected. They should work well, but they should not be the headline story.

---

## 3. Lean Canvas diagram

| Lean Canvas Block | LTI Definition |
|---|---|
| **Problem** | Mid-market hiring teams struggle with recruiter–manager misalignment, slow decisions, inconsistent evaluation, excessive manual coordination, weak operational visibility, and low-signal candidate artifacts. |
| **Customer Segments** | Primary: employer-side mid-market knowledge-work companies (100–1000 employees). Users: recruiters, hiring managers, interviewers, TA leaders, coordinators, HR operations. Buyers: Head of Talent, VP People, CHRO, HR Director. |
| **Unique Value Proposition** | **A collaboration-first, automation-heavy, AI-assisted full-cycle ATS that helps hiring teams make faster, better, more consistent decisions.** |
| **Solution** | Structured hiring workflow, manager collaboration workspace, automation engine, recruiting ops analytics, trustworthy AI assistance, signal-rich candidate intake, offer/onboarding handoff. |
| **Channels** | Founder-led sales, HR / TA communities, content marketing around structured hiring and recruiting ops, partnerships with recruiting consultants, targeted outbound to mid-market TA leaders, product-led demos. |
| **Revenue Streams** | Annual SaaS subscription by employee band or hiring volume; platform tiering by feature depth; optional premium modules for advanced analytics, AI assistance, and workflow automation. |
| **Cost Structure** | Product development, cloud hosting, AI inference and model costs, customer success/onboarding, integrations, sales, compliance and security investment. |
| **Key Metrics** | Time-to-hire, time-in-stage, manager response time, feedback completion rate, application completion rate, recruiter hours saved, offer acceptance rate, logo retention, expansion revenue. |
| **Unfair Advantage / Defensibility** | Better recruiter–manager UX, workflow-native intelligence, auditable AI assistance, operational analytics embedded into the ATS, and compounding workflow data that improves recommendations over time. |

### Lean Canvas interpretation
The business model is strongest when LTI is sold not as another place to manage applicants, but as:
- a **decision-quality improvement system**,
- a **recruiting workflow operating system**,
- and a **manager-adoption improvement layer** for hiring teams.

---

## 4. PRD (Product Requirements Document)

# PRD — LTI Collaboration-First Mid-Market ATS

## 4.1 Product vision
LTI will become the operating system for mid-market hiring teams that need more structure, coordination, and operational intelligence than lightweight ATS tools provide, but without the heaviness of enterprise suites.

## 4.2 Problem statement
Mid-market knowledge-work companies often outgrow spreadsheets, email-heavy coordination, and lightweight ATS tooling, but still suffer from several persistent failures:
- hiring managers delay reviews and decisions,
- recruiters spend too much time coordinating people and process,
- candidate information is not converted into decision-ready signal,
- interview feedback is inconsistent or late,
- analytics are too limited to manage bottlenecks in real time,
- and candidate experience suffers from long or repetitive workflows.

Current ATS products often solve parts of this problem, but many teams still operate with fragmented decision-making, limited visibility, and too much manual effort.[^aptitude]

## 4.3 Target users
### Primary users
- Recruiters / talent acquisition specialists
- Hiring managers
- Talent acquisition leaders / Head of Talent
- Recruiting coordinators / People operations

### Secondary users
- Interviewers
- HR / People leadership
- New-hire handoff stakeholders

### Economic buyer
- Head of Talent
- VP People / People Director
- CHRO / HR Director
- Sometimes Finance or Operations for procurement approval

## 4.4 Value proposition
For employer-side mid-market knowledge-work companies, LTI provides a full-cycle ATS that:
- improves recruiter–manager alignment,
- reduces coordination overhead,
- structures hiring decisions,
- surfaces bottlenecks in real time,
- and uses AI to accelerate work without removing human judgment.

## 4.5 Goals
### Business goals
- Win the initial ICP with a differentiated ATS story
- Achieve credible replacement value versus incumbent ATS workflows
- Build a platform foundation for expansion into analytics, AI, and adjacent hiring workflow modules

### Product goals
- Increase hiring manager participation and responsiveness
- Reduce recruiter administrative time
- Improve speed and consistency of candidate movement through the funnel
- Improve quality and usefulness of evaluation data
- Reduce candidate application friction while preserving hiring signal

## 4.6 Measurable goals
The following measurable goals are recommended for the first 12 months after initial production launch for the target ICP.

### Adoption and engagement goals
- At least **70% of active hiring managers** in live customer accounts complete at least one review, approval, or feedback action each month.
- At least **80% of interview loops** in live customer accounts have complete structured feedback submitted before final debrief.
- At least **60% of recruiter users** actively use one or more automation rules each month.
- At least **50% of recruiter users** actively use at least one AI-assisted workflow each month.

### Efficiency goals
- Reduce average **time-to-first-review** for shortlisted candidates by **30%** versus the customer’s baseline process.
- Reduce average **overdue manager review items** by **40%** versus baseline.
- Reduce average **time-in-stage** for core screening and interview stages by **20%** versus baseline.
- Reduce recruiter-reported administrative time per open role by at least **25%**.

### Candidate experience goals
- Improve completed application rate for CV-based applications by **15%** versus customer baseline where redundant data entry is reduced.
- Keep candidate save-and-resume failure or abandonment caused by product-side issues below **1%** of started applications.

### Business outcome goals
- Achieve customer gross retention of at least **90%** in the first renewal cycle.
- Achieve at least **25% attach rate** for advanced automation or AI features among live customers after initial rollout.

These targets should be refined during discovery and pilot phases, but they provide a measurable operating definition of success.

## 4.7 Non-goals
LTI is **not** initially intended to be:
- a full HRIS/HCM platform,
- a staffing agency CRM,
- a frontline / hourly hiring specialist tool,
- an enterprise-global governance-heavy suite,
- or a fully autonomous AI screening and rejection system.

## 4.8 Business model summary
### Packaging hypothesis
- **Core platform**: structured ATS workflow + collaboration + basic analytics
- **Pro tier**: advanced automation + advanced analytics + AI assistance
- **Enterprise / advanced tier later**: deeper controls, compliance features, advanced integrations, multi-entity administration

### Pricing logic
Recommended starting model:
- annual SaaS subscription,
- priced by employee band or hiring volume,
- with generous / unlimited hiring-manager and interviewer access,
- premium pricing for advanced analytics, AI assistance, and automation depth.

### Why this model fits
Mid-market buyers want value tied to hiring complexity and team usage, but penalizing manager participation through per-seat pricing can weaken adoption.

## 4.9 Core use cases
1. Recruiter and hiring manager define a role and agree on success criteria
2. Recruiter opens a requisition and routes for approval
3. Job is published and applications begin arriving
4. Candidate CV is parsed; structured candidate profile is created
5. Recruiter triages candidates with AI summaries and role-linked evidence
6. Hiring manager reviews prioritized candidates in a task-oriented inbox
7. Interview plan and scorecards are assigned
8. Interviewers receive role-specific interview briefs and submit structured feedback
9. Recruiter and manager run a structured debrief and make a decision
10. Offer is generated, approved, and sent
11. Accepted candidate is handed off to onboarding / HR systems
12. TA leader monitors funnel bottlenecks, manager responsiveness, and conversion rates

## 4.10 Main user stories
### Recruiter user stories
- As a recruiter, I want to create a requisition with a structured hiring plan so that the role is aligned before candidates enter the pipeline.
- As a recruiter, I want the system to remind managers and interviewers about pending actions so that I spend less time chasing people manually.
- As a recruiter, I want AI-generated candidate summaries tied to job requirements so that I can triage applications faster without losing important evidence.
- As a recruiter, I want a structured debrief workspace so that hiring decisions are easier to compare and document.
- As a recruiter, I want to automate stage-based communication and approval routing so that routine tasks do not slow down the funnel.

### Hiring manager user stories
- As a hiring manager, I want a simple inbox of pending candidate reviews and approvals so that I know exactly what requires my attention.
- As a hiring manager, I want to see concise candidate evidence rather than raw application overload so that I can make faster, more informed decisions.
- As a hiring manager, I want interview scorecards and evaluation criteria tied to the role so that my team evaluates consistently.
- As a hiring manager, I want to participate in a structured debrief with clear evidence so that final decisions are more confident and less subjective.

### Interviewer user stories
- As an interviewer, I want role-specific interview guidance and a simple feedback form so that I know what to assess and can submit useful feedback quickly.

### Talent leader user stories
- As a talent leader, I want real-time visibility into stuck roles, response delays, and stage conversion so that I can fix process problems before they impact hiring outcomes.
- As a talent leader, I want to understand whether automation and AI features are improving speed and consistency so that I can justify continued investment.

### Candidate user stories
- As a candidate, I want the system to extract information from my CV and only ask me to confirm or complete missing fields so that I do not retype what is already present.
- As a candidate, I want application requirements to feel relevant to the role so that the process feels fair and not unnecessarily repetitive.
- As a candidate, I want timely, clear communication throughout the process so that I understand my status and next steps.

## 4.11 Functional requirements

### FR-1 Requisition and hiring plan management
The system shall allow recruiters and managers to create a requisition, define role requirements, assign an approval flow, and configure the hiring plan.

**Key capabilities**
- Job requisition creation
- Approval routing
- Role brief and hiring goals
- Interview plan template selection
- Hiring team assignment

### FR-2 Structured hiring configuration
The system shall support creation of scorecards, evaluation rubrics, and interview kits tied to role requirements.[^greenhouse]

**Key capabilities**
- Scorecard templates
- Required competencies and evaluation criteria
- Stage-specific interview kits
- Role-specific interviewer guidance

### FR-3 Hiring-manager collaboration workspace
The system shall provide a dedicated collaboration interface for hiring managers.

**Key capabilities**
- Manager task inbox
- Candidate review queue
- Feedback due indicators
- Approval actions
- Debrief participation view
- Decision history and rationale view

### FR-4 Candidate intake and profile generation
The system shall ingest candidate applications and produce structured candidate records.

**Key capabilities**
- CV upload and parsing
- Candidate confirmation of extracted fields
- Role-adaptive application flows
- Candidate duplicate detection
- Candidate profile history

### FR-5 Candidate signal extraction
The system shall convert submitted candidate artifacts into structured recruiter- and manager-friendly summaries.

**Key capabilities**
- Candidate evidence summary
- Requirement-to-evidence mapping
- Key strengths / gaps view
- Optional structured motivation prompts
- Optional cover-letter summarization

### FR-6 Workflow automation
The system shall support configurable workflow automations across the hiring process.[^workable]

**Key capabilities**
- Reminder triggers
- Escalation triggers
- Communication triggers
- Approval routing triggers
- Offer routing automation
- Handoff automation

### FR-7 Interview coordination and feedback collection
The system shall support interview planning, scheduling support, and structured feedback submission.

**Key capabilities**
- Interview loop planning
- Candidate scheduling support
- Interviewer assignment
- Feedback due reminders
- Structured feedback forms
- Debrief preparation package

### FR-8 Real-time recruiting ops analytics
The system shall provide real-time operational reporting and alerts.[^ashby]

**Key capabilities**
- Funnel conversion dashboard
- Time-in-stage reporting
- Stuck-role alerts
- Hiring-manager responsiveness view
- Feedback completion dashboard
- Application abandonment and completion analytics

### FR-9 AI assistance
The system shall provide assistive AI features embedded into recruiter and manager workflows.

**Key capabilities**
- Candidate summarization
- Relevance explanation draft
- Interview brief generation
- Debrief summary generation
- Candidate message drafting
- Next-best-action recommendations
- Safe feedback draft suggestions

**AI guardrails**
- Human review on sensitive communications
- Auditability of generated content
- Explanation of input basis where appropriate
- No unreviewed, high-stakes autonomous decisioning

### FR-10 Offer and onboarding handoff
The system shall manage offer workflow and downstream handoff.

**Key capabilities**
- Offer draft and approval
- Candidate response tracking
- Handoff checklist
- Basic HRIS / onboarding transfer package

## 4.12 Non-functional requirements
These are product-level requirements, not implementation design.

### Security and privacy
- Role-based access control
- Audit logging for sensitive actions
- Protection of candidate PII
- Configurable retention and deletion policies

### Reliability
- Core workflow actions should be dependable and recoverable
- Candidate application submission should be robust and not fail silently

### Usability
- Recruiter flows must reduce clicks for repetitive operations
- Hiring-manager experience must be simple enough for infrequent users
- Candidate application experience must minimize redundant work

### Explainability and governance
- AI-assisted outputs must be clearly marked as AI-generated or AI-assisted where appropriate
- Sensitive AI usage must allow human review and correction
- Product behavior should support customer governance requirements in hiring workflows[^ai-act]

### Reporting integrity
- Operational analytics should reflect current workflow state with trustworthy, reconcilable data

## 4.13 Acceptance criteria
These acceptance criteria are written at the product-feature level so they can guide later story breakdown.

### AC-1 Structured hiring workflow
- A recruiter can create a requisition, assign a hiring manager, and configure a hiring plan without leaving the main workflow.
- A hiring manager can review and approve a requisition with visible role requirements and interview plan context.
- Scorecards and interview kits can be attached to a role before candidates are advanced to interview stages.

### AC-2 Hiring-manager collaboration workspace
- A hiring manager sees all pending candidate reviews, feedback tasks, and approvals in a single task-oriented view.
- The workspace clearly shows overdue actions and required next steps.
- Recruiters and managers can access a shared decision log tied to explicit evaluation criteria.

### AC-3 Workflow automation
- Admins or recruiters can configure reminders, escalations, and communication triggers without engineering support.
- Automated reminders are sent when configured deadlines are missed.
- Offer and handoff workflows can trigger downstream tasks after candidate acceptance.

### AC-4 Candidate intake and signal extraction
- A candidate can upload a CV and receive extracted fields for confirmation instead of re-entering all information manually.
- Recruiters can view a structured candidate summary with evidence linked to job requirements.
- The system can support role-specific application questions without forcing the same flow for every role.

### AC-5 Interview coordination and feedback
- Recruiters can assign interviewers and collect structured feedback for each stage.
- Interviewers receive role-specific context before interviews.
- Debrief preparation includes consolidated feedback and candidate evidence.

### AC-6 Recruiting ops analytics
- Recruiters and talent leaders can view current time-in-stage, overdue feedback, and manager responsiveness in-product.
- Roles that exceed configurable delay thresholds are surfaced as stuck or at risk.
- Application completion and abandonment data is visible for each role.

### AC-7 AI assistance
- AI summaries are clearly labeled and presented as assistive output, not final decisions.
- Users can review and edit AI-generated drafts before sending or saving sensitive outputs.
- AI-generated content is traceable to the relevant candidate inputs, role requirements, or workflow context.

### AC-8 Offer and onboarding handoff
- Recruiters can generate and route offers for approval in-product.
- Accepted candidates can be moved into a defined onboarding handoff workflow without re-entering core information.

## 4.14 MVP scope
The MVP should focus on the parts of the product most central to the wedge.

### In MVP
- Requisition and approval management
- Structured hiring plan and scorecards
- Hiring-manager collaboration workspace
- Candidate intake and structured candidate profile
- Basic AI summaries for candidate review and interview prep
- Core workflow automation (reminders, approvals, communications)
- Interview coordination and structured feedback
- Core real-time recruiting ops dashboard
- Offer workflow and onboarding handoff basics

### Deliberately later
- Broad marketplace / ecosystem depth
- Extensive board syndication breadth
- Heavy compliance module depth by geography
- Advanced workforce planning connections
- Deep CRM / nurture campaigns
- Enterprise-grade multi-entity administration
- Advanced AI features that require greater governance complexity

## 4.15 Prioritization

### P0 — must-have to support positioning
- Structured hiring workflow
- Hiring-manager workspace
- Workflow automation basics
- Candidate intake + profile generation
- Interview feedback collection
- Core recruiting ops analytics

### P1 — strong differentiators
- AI candidate summaries
- AI interview briefs
- AI debrief summaries
- Application friction analytics
- Decision logs and accountability signals
- Safe candidate feedback drafting

### P2 — later expansion
- Advanced AI recommendations
- Extended integrations ecosystem
- Advanced benchmarking
- Broader CRM / talent pooling capabilities
- Verticalized templates by industry

## 4.16 Success metrics / KPIs

### Product usage metrics
- Hiring-manager weekly active usage
- Feedback completion rate
- Average time to review shortlisted candidates
- Automation utilization rate
- AI assistance utilization rate

### Outcome metrics
- Time-to-hire
- Time-in-stage reduction
- Candidate application completion rate
- Offer acceptance rate
- Recruiter time saved per role
- Reduction in overdue approvals / feedback

### Business metrics
- Logo acquisition in target ICP
- Time-to-first-live-role after purchase
- Gross retention and net retention
- Expansion into advanced analytics / AI tiers
- Win rate versus incumbent ATS alternatives

## 4.17 Assumptions, dependencies, and risks

### Assumptions
- Mid-market buyers value manager adoption and workflow quality enough to switch ATS
- Recruiter pain is operational enough that automation and analytics will resonate strongly
- Candidate-signal improvement matters more than simply collecting more text or more applicants

### Dependencies
- A strong initial UX for recruiters and hiring managers
- Reliable integrations with calendars, email, and downstream HR handoff systems
- Careful AI governance and messaging

### Risks
1. **Crowded market risk**  
   The ATS category is competitive; weak differentiation will be punished quickly.

2. **Execution risk on collaboration UX**  
   If the manager experience is clumsy, the strategic wedge weakens significantly.

3. **AI overreach risk**  
   If AI is positioned as autonomous or opaque, trust and compliance concerns can outweigh its value.[^ai-act]

4. **Scope creep risk**  
   Trying to serve SMB simplicity, enterprise governance, staffing workflows, and high-volume hiring simultaneously will weaken the product.

5. **Data quality risk**  
   Recruiting analytics and AI usefulness depend on disciplined workflow capture.

## 4.18 Open questions for the next iteration
- Should LTI begin with one functional-industry focus inside knowledge-work (e.g., B2B SaaS / tech-enabled services)?
- How much configurability should the initial workflow engine expose versus guided defaults?
- Which candidate-facing feedback features should be enabled by default versus optional?
- What is the best pricing packaging for encouraging hiring-manager participation without reducing revenue potential?
- Which integrations are truly required for first-wave adoption versus nice-to-have?

---

## Final recommendation summary
LTI should move forward as a **collaboration-first, automation-heavy, AI-assisted full-cycle ATS for employer-side mid-market knowledge-work companies**.

This direction is recommended because it best fits the existing LTI product scope, targets a segment with real pain and real willingness to pay, and allows meaningful differentiation beyond generic ATS or generic AI positioning. The product should win not by trying to be everything to everyone, but by being visibly better at:
- recruiter–manager collaboration,
- workflow automation,
- recruiting operations intelligence,
- and trustworthy AI assistance.

---

## References
[^aptitude]: Aptitude Research, *Beyond Tracking: The Evolution of the ATS in an Intelligent and Agentic Era* (2025). Key findings surfaced on the report page: [Aptitude Research report page](https://www.aptituderesearch.com/research_report/beyond-tracking-the-evolution-of-the-ats-in-an-intelligent-and-agentic-era/)
[^greenhouse]: Greenhouse, *Interviewing & decision making* and structured hiring resources: [Interviewing & decision making](https://www.greenhouse.com/interviewing-decision-making) and [Structured hiring introduction](https://support.greenhouse.io/hc/en-us/articles/360007245452-Structured-hiring-Introduction)
[^ashby]: Ashby, *Powerful Analytics and Reporting*: [Ashby recruiting analytics](https://www.ashbyhq.com/platform/recruiting/analytics)
[^workable]: Workable Help Center, *Setting up automated actions*: [Workable automated actions](https://help.workable.com/hc/en-us/articles/1500007691921-Setting-up-automated-actions)
[^linkedin]: LinkedIn, *LinkedIn Research: Talent 2026*: [LinkedIn Talent 2026](https://news.linkedin.com/en-us/2026/LinkedIn-Research-Talent-2026)
[^ai-act]: European Commission, *Navigating the AI Act*; recruitment/employment AI is part of the high-risk system framework: [Navigating the AI Act](https://digital-strategy.ec.europa.eu/en/faqs/navigating-ai-act)