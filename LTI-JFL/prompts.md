# Prompt 1

---

You are a senior Product Strategy, B2B SaaS, and HR Tech expert with deep expertise in Applicant Tracking Systems (ATS).

## Objective
Produce a precise, exhaustive, and decision-oriented product analysis of the Applicant Tracking System (ATS) market and opportunity space in order to:
1. help me decide which ATS product option is the most attractive,
2. help me decide which target audience / target public to prioritize,
3. define the business model and product scope for a new ATS product,
4. prepare the basis for a PRD (Product Requirements Document) for the selected business model.

## Context
I am attaching a README.md for a base ATS project called LTI. Use it only as supporting context, not as a final definition of the product.
The README indicates that the intended product scope covers the full hiring cycle, including:
- job creation
- job publishing
- application intake
- review and screening
- assessments
- interview scheduling
- hiring and onboarding handoff

The current goal is not to define implementation details yet, but to understand:
- the business model,
- the most important product functions,
- the best market positioning,
- the best target audience,
- and the best differentiation strategy for a new ATS.

## Task mode
Your work must be split into **2 phases**.

### Phase 1 — Strategic analysis and decision support
In this phase, analyze the ATS market and propose a set of viable strategic options.
Your goal is to help me choose:
- one product option / product positioning,
- and one target audience / target public.

At the end of Phase 1, you must explicitly recommend:
- the best option,
- the best target public,
- and 2–3 strong alternative options.

### Phase 2 — Business definition package for the selected option
Phase 2 must only begin if I explicitly state that I want to move to the second phase.

Do not infer that I want Phase 2 only because I mention an option or target audience. I must explicitly confirm that I want to proceed.

Accepted examples of explicit confirmation include:
- “Proceed to Phase 2”
- “Go to the second phase”
- “Start Phase 2”
- “Use the selected option and continue with Phase 2”

After I explicitly confirm Phase 2 and provide the selected option and selected target public, you must create a business definition package for LTI that includes:
1. **Descripción breve del software LTI, valor añadido y ventajas competitivas**
2. **Explicación de las funciones principales**
3. **Un diagrama Lean Canvas para entender el modelo de negocio**
4. **A PRD (Product Requirements Document) for the selected business model**

Do not generate Phase 2 in advance unless explicitly requested. In Phase 1, prepare the path so Phase 2 can be done with minimal ambiguity.

## Interaction rules
1. Before Phase 2 starts, I may ask follow-up questions to help me decide.
2. Before Phase 2 starts, you may also ask clarifying questions if something is not clear or if specific user input would materially improve the recommendation.
3. Ask clarifying questions only when they are truly necessary. If the missing information is not critical, proceed with reasonable assumptions and state them clearly.
4. Until I explicitly confirm that I want to proceed to Phase 2, remain in Phase 1 mode.
5. If I ask follow-up questions after your recommendation, answer them in decision-support mode and do not start Phase 2 automatically.
6. If my selection is incomplete, ambiguous, or contradictory, ask a brief clarification before starting Phase 2.

## Instructions
1. Focus strictly on product analysis, market strategy, positioning, and business-model framing.
2. Do not generate technical architecture, database design, implementation tasks, or development plans unless they are directly needed to explain product differentiation or commodity areas.
3. Clearly distinguish between:
   - must-have functionality
   - important but secondary functionality
   - commodity functionality that should not necessarily be built from scratch
   - strategic differentiators that could create competitive advantage
4. When making comparisons, be explicit, structured, and decision-oriented.
5. If information depends on company size, hiring complexity, geography, or segment, state the assumption clearly.
6. When listing solutions, include both open-source and commercial ATS solutions that are widely recognized.
7. For product comparison, use these dimensions:
   - [Functionality A]
   - [Functionality B]
   - [Functionality C]
8. Include a decision framework that helps me choose one option and one target public.
9. Your Phase 1 conclusion must end with a direct recommendation and a small number of concrete choices I can pick from.
10. After the Phase 1 recommendation, include a short “Reply format” that tells me exactly how to answer so you can either:
   - ask more questions,
   - refine the recommendation,
   - or explicitly move to Phase 2.

## Deliverable format for Phase 1
Structure your answer in the exact sections below.

### 1. Core ATS functionalities ranked by priority
Provide a prioritized list of the core functionalities of an ATS, ordered from highest to lowest priority.
For each functionality, include:
- what it is
- why it matters
- who uses it
- why it is high / medium / lower priority

### 2. Customer benefits
Explain the main benefits a customer gets from using an ATS.
Group benefits into:
- operational efficiency
- hiring quality
- collaboration and process control
- compliance and reporting
- candidate experience
- scalability

For each benefit, explain why it is valuable enough for a customer to adopt an ATS.

### 3. Alternatives to using an ATS
Describe the main alternatives to using an ATS and when they may be relevant.
Include, at minimum:
- spreadsheets / manual workflows
- email-based recruiting
- general-purpose CRM or project-management tools
- HRIS / HCM suites with basic recruiting modules
- recruiting agencies / outsourced hiring support

For each alternative, explain:
- when it is sufficient
- its limitations
- at what stage an ATS becomes more appropriate

### 4. Typical customer journey for an ATS buyer and user
Describe the normal customer journey of a company that adopts and uses an ATS.
Cover the journey step by step, including all major interactions from initial need recognition to ongoing usage.
Include:
- trigger / problem recognition
- research and vendor discovery
- evaluation and comparison
- internal stakeholder alignment
- trial / demo / proof of concept
- purchase decision
- onboarding and setup
- job creation and publishing
- candidate intake
- screening and collaboration
- interviews and assessments
- offer and hire
- reporting and optimization
- renewal, expansion, or churn risk

For each step, specify:
- user / stakeholder involved
- goal
- key interaction with the ATS
- friction points
- success criteria

### 5. Well-known open-source ATS solutions
List the most recognized open-source ATS solutions.
For each one, provide:
- short description
- typical target user
- strengths
- weaknesses
- when it is a good fit

### 6. Well-known commercial ATS solutions
List the most recognized commercial ATS solutions.
For each one, provide:
- short description
- typical target user
- strengths
- weaknesses
- when it is a good fit

### 7. Comparative analysis of ATS solutions
Compare the most relevant open-source and commercial ATS solutions using:
- [Functionality A]
- [Functionality B]
- [Functionality C]

Present the comparison in a table first, then provide a narrative analysis.
After the comparison:
- assess which option is best depending on company type and stage
- explain trade-offs
- identify the best option for SMBs, mid-market, and enterprise
- identify the best option if cost control is the main priority
- identify the best option if flexibility / customization is the main priority

### 8. Target audiences and market segmentation
Identify the different target audiences for an ATS.
Include segments such as:
- startups
- SMBs
- mid-market companies
- enterprise companies
- staffing and recruiting agencies
- high-volume hiring businesses
- niche / industry-specific recruiting teams

For each segment, explain:
- their main hiring problems
- what they value most in an ATS
- buying criteria
- barriers to adoption

### 9. Opportunity for a novel ATS
For each target audience above, explain:
- what added value a new ATS could offer
- what competitive advantages a novel ATS could present
- what unmet needs or gaps exist in current solutions
- what differentiated market value it could bring

Be specific about where a new entrant could stand out meaningfully.

### 10. Commodity vs differentiation
Split ATS capabilities into two categories:

#### A. Commodity / secondary areas
Identify the secondary or commodity aspects of an ATS where there is little need to build from scratch.
For each one, explain:
- why it is commodity
- whether it is better solved through integration, third-party tooling, standard components, or basic implementation
- why overinvesting here would not create meaningful differentiation

#### B. Strategic / differentiating areas
Identify the key aspects of an ATS that could truly differentiate a new product in a highly competitive market.
For each one, explain:
- why it is strategically important
- what customer pain it solves
- why competitors may not solve it well today
- how it could create defensibility or market advantage

### 11. Strategic product options
Propose 3 to 5 viable product options / positioning options for a novel ATS.
For each option, include:
- option name
- target audience / target public
- problem solved
- core differentiator
- monetization logic
- expected strengths
- expected risks
- why it could win

Examples of “options” may include:
- SMB-focused ATS
- recruiting-agency ATS
- AI-assisted screening ATS
- vertical ATS for a specific industry
- high-volume hiring ATS
- collaboration-first ATS for distributed teams

### 12. Decision matrix
Create a decision matrix comparing the proposed product options.
Score each option from 1 to 5 against at least these criteria:
- market attractiveness
- urgency of customer pain
- willingness to pay
- competitive intensity
- implementation complexity
- speed to market
- differentiation potential
- long-term defensibility
- fit with the LTI full-cycle ATS concept

Then:
- rank the options from strongest to weakest
- identify the best target audience / target public for each option

### 13. Recommended decision
Give a final recommendation with:
- the single best product option to pursue first
- the single best target audience / target public to prioritize first
- why this is the strongest choice
- the top 2 or 3 alternative options worth considering
- the biggest assumptions and risks behind the recommendation

### 14. Preparation for Phase 2
Before finishing, include a short section called:
**“What I will produce once you choose an option and explicitly approve Phase 2”**

In that section, state that once I reply with the selected option, the selected target public, and an explicit instruction to proceed to Phase 2, you will create:
1. **Descripción breve del software LTI, valor añadido y ventajas competitivas**
2. **Explicación de las funciones principales**
3. **Lean Canvas diagram**
4. **PRD (Product Requirements Document) for the business model**

Also specify the PRD must include, at minimum:
- product vision
- problem statement
- target users
- value proposition
- goals and non-goals
- core use cases
- functional requirements
- non-functional requirements
- MVP scope
- prioritization
- success metrics / KPIs
- assumptions, dependencies, and risks

### 15. Reply format for my next message
End your answer with these exact instructions:

“If you want to keep evaluating before deciding, reply with:
- Question or doubt:
- Optional option(s) you want to explore:
- Optional target audience(s) you want to explore:

If you want to start Phase 2, reply with:
- Selected option:
- Selected target audience:
- Proceed to Phase 2: Yes
- Optional constraints or priorities:”

## Output requirements
- Write in clear, professional English.
- Be exhaustive but concise.
- Use headings, subheadings, and comparison tables where useful.
- Avoid generic statements; make the analysis decision-oriented.
- Distinguish clearly by company size, hiring complexity, and budget sensitivity where relevant.
- Do not invent unsupported claims; indicate assumptions when necessary.
- Do not execute Phase 2 unless I explicitly confirm that I want to proceed to Phase 2.

---

# Prompt 2

---

You are an expert Software Analyst and Product Analyst with deep expertise in B2B SaaS, HR Tech, and Applicant Tracking Systems (ATS).

## Objective
Identify and describe the **3 most important use cases** for the ATS functionality or product already defined, and represent each of them with its corresponding diagram.

Your goal is to help translate product requirements into the **minimum essential set of user interactions** needed for implementation reference, while keeping the output aligned with a **lean / agile** approach:
- focus only on the most critical use cases,
- avoid over-modeling,
- avoid generating many secondary or speculative scenarios.

## Context
The product requirements or functionality have already been defined at a higher level.
Now the objective is to move to a lower level of abstraction and identify:
- the user roles that interact with the system,
- the actions each role performs,
- the dependencies between actions,
- and the main system interaction scenarios that are necessary to implement the functionality.

The use cases must serve as a reference for:
- understanding how the software should behave,
- clarifying the user roles involved,
- identifying the key interactions and dependencies,
- and helping the software team implement the system correctly.

## Scope constraints
1. Focus only on the **3 principal use cases** required for a basic but meaningful ATS workflow.
2. Do not generate a full use case catalog.
3. Prioritize use cases that are essential for delivering business value and validating the product early.
4. If a use case is important but depends on another one, make that dependency explicit.
5. If some assumptions are needed because the product context is incomplete, state them clearly before presenting the use cases.

## Modeling rules
1. Use **UML use case diagrams**.
2. Represent each of the 3 use cases using **PlantUML** syntax.
3. Follow UML syntax and best practices carefully.
4. Use relationships such as `<<include>>` and `<<extend>>` only when they are truly justified, and apply them correctly.
5. Include all relevant actors that are necessary to understand the interaction, even if they are not end customers.
6. Distinguish clearly between different actor types when relevant, such as:
   - visitor / unauthenticated user
   - authenticated user
   - recruiter
   - hiring manager
   - candidate
   - administrator
   - customer support or operational staff
7. Do not force unnecessary actors or relationships.
8. If a textual description mentions an actor or support role, ensure the diagram reflects it as well.

## Required output structure

### 1. Assumptions
Briefly state the assumptions you are making about the ATS scope, product maturity, and user roles.

### 2. Top 3 use cases
List the **3 most important ATS use cases** in priority order.

For each use case, provide:

#### Use Case X — [Name]
- **Purpose:** what business goal it supports
- **Primary actor(s):** who initiates it
- **Supporting actor(s):** who participates indirectly, if applicable
- **Preconditions:** what must already be true
- **Main flow:** step-by-step summary of the normal interaction
- **Dependencies:** actions or conditions required before or during the use case
- **Postconditions:** expected result after successful completion
- **Why it is a top-3 use case:** why this scenario is essential for an MVP or early product version

### 3. Diagram for each use case
For each of the 3 use cases, provide:
- a short explanation of what the diagram represents
- the corresponding **PlantUML** code block

### 4. Validation notes
After the 3 use cases, include a short validation section explaining:
- whether the selected use cases are sufficient for a first useful version of the ATS
- what important use cases were intentionally excluded to remain lean
- which use case should likely be implemented first

## Output quality requirements
- Write in clear, professional English.
- Be precise and exhaustive **within the scope of only 3 use cases**.
- Do not drift into technical architecture or implementation details.
- Do not invent unnecessary complexity.
- Make dependencies between actions explicit where relevant.
- Keep the analysis practical and implementation-oriented.
- Ensure the PlantUML is syntactically coherent and aligned with UML good practices.
- Prefer accuracy and clarity over completeness beyond the requested scope.

---

# Prompt 3

---

You are a senior Software Architect and Data Modeling expert with deep expertise in Applicant Tracking Systems (ATS), B2B SaaS platforms, and business-domain data design.

## Objective
Create a **complete logical data model** for the software **LTI**, an Applicant Tracking System (ATS), based on the attached **LTI-design.md** document, which contains:
- product research and analysis,
- requirements,
- PRD content,
- and use case definitions.

Your goal is to transform that product and use-case context into a **clear, implementation-ready logical data model** that defines:
1. the relevant entities,
2. the attributes of each entity,
3. the attribute types,
4. the relationships between entities,
5. and a complete diagram representing the model.

## Primary source of truth
Use the attached **LTI-design.md** as the **primary source** for the model.

Treat the document as the main basis for:
- business concepts,
- user roles,
- workflows,
- hiring lifecycle stages,
- and the required system behavior.

Do not ignore the source document.
Do not invent major entities or relationships that contradict it.
If the document leaves something unspecified but a reasonable data-modeling assumption is necessary, state the assumption clearly.

## Modeling scope
The model must cover the ATS domain needed to support the product described in LTI-design.md, including the relevant data structures required for:
- requisition and job setup,
- hiring teams and roles,
- job publishing,
- candidate intake,
- candidate profiles,
- application tracking,
- workflow progression,
- screening and evaluation,
- interview planning and feedback,
- hiring decisions,
- offer handling,
- onboarding handoff,
- collaboration and decision logging,
- and other essential supporting entities implied by the product scope.

## What “data model” means in this task
Produce a **logical data model**, not a physical database implementation.

This means:
- identify the most relevant domain entities,
- define the important attributes for each entity,
- specify a sensible generic data type for each attribute,
- define relationships and cardinalities,
- and make explicit any junction entities needed to resolve many-to-many relationships.

Do **not** generate:
- SQL DDL,
- migrations,
- indexes,
- vendor-specific database syntax,
- storage-engine decisions,
- or low-level infrastructure details.

Only mention technical implementation choices if they are strictly necessary to clarify the model.

## Data-modeling rules
1. Use the product requirements, PRD, and use cases in the attached document to infer the model.
2. Focus on a model that is **complete enough to support the described ATS workflows**, but avoid unnecessary over-modeling.
3. Include both:
   - **core transactional entities**
   - **supporting entities** required for traceability, workflow, and collaboration
4. Explicitly identify:
   - primary entities
   - supporting entities
   - associative / junction entities
5. For every relationship, specify:
   - source entity
   - target entity
   - cardinality
   - optionality when relevant
   - the business meaning of the relationship
6. Where many-to-many relationships exist, resolve them through explicit associative entities.
7. Use practical generic attribute types such as:
   - `uuid`
   - `string`
   - `text`
   - `boolean`
   - `integer`
   - `decimal`
   - `date`
   - `datetime`
   - `enum`
   - `json`
8. Where relevant, identify:
   - primary key
   - foreign keys
   - important unique fields
   - status fields / lifecycle fields
   - audit fields
9. If an attribute is better modeled as an enum or reference entity, make that choice explicit.
10. If an area is uncertain, state the assumption instead of pretending certainty.

## Prioritization guidance
Prioritize entities that are necessary to support the actual ATS business workflow first.
The model should clearly support at minimum:
- job requisitions
- job postings
- candidates
- applications
- hiring pipeline stages
- interviews
- evaluations / scorecards / feedback
- users and roles in the hiring process
- decisions
- offers
- onboarding handoff

Then include the secondary entities needed to make the model coherent and usable.

## Diagram format
Represent the full data model as a **Mermaid ER diagram**.

Use Mermaid because the output should be easy to maintain as “diagram as code” in modern documentation workflows.

The Mermaid diagram must:
- be complete, not partial,
- include all major entities,
- include key relationships,
- use readable naming,
- and remain syntactically coherent.

## Required output structure

### 1. Assumptions and modeling boundary
Briefly explain:
- what scope from LTI-design.md you are modeling,
- what you are including,
- what you are intentionally leaving out,
- and any assumptions made due to ambiguity.

### 2. Entity inventory
Provide a categorized inventory of entities, grouped into:
- **Core ATS entities**
- **Supporting entities**
- **Associative / junction entities**

For each entity, include a one-line explanation of its purpose.

### 3. Detailed logical data model
For each entity, provide:

#### Entity: [Entity Name]
- **Purpose:** what it represents in the business domain
- **Primary key:** attribute name and type
- **Attributes:** a table with:
  - attribute name
  - generic type
  - short description
  - notes if relevant (e.g. enum, unique, nullable, foreign key)
- **Important relationships:** short explanation of how this entity connects to others

Make sure the entity definitions are detailed enough for a software team to use as a strong modeling reference.

### 4. Relationships summary
Provide a relationship summary table with these columns:
- source entity
- relationship
- target entity
- cardinality
- optionality
- business meaning

Be explicit and systematic.

### 5. Mermaid ER diagram
Provide one **complete Mermaid ER diagram** for the full model.

Requirements for the diagram:
- include all major entities
- include all important relationships
- use meaningful relationship labels where useful
- keep names consistent with the entity definitions above
- ensure the Mermaid syntax is valid and coherent

### 6. Modeling notes and validation
Conclude with a short validation section explaining:
- whether the model is sufficient for the ATS scope described in LTI-design.md
- which entities are most central to the system
- which parts of the model may evolve later
- any modeling risks, ambiguities, or open questions

## Output quality requirements
- Write in clear, professional English.
- Be precise and exhaustive, but stay within the scope of a logical data model.
- Base the model primarily on the attached LTI-design.md.
- Avoid generic filler and avoid unsupported invention.
- Keep naming consistent across entities, relationships, and diagram.
- Make the result useful for product, architecture, and engineering discussions.
- Do not execute implementation work.
- Do not produce SQL.
- Do not produce multiple alternative models unless ambiguity truly requires it.

---

# Prompt 4

---

You are a senior Software Architect with deep expertise in Applicant Tracking Systems (ATS), B2B SaaS platforms, and scalable product architecture.

## Objective
Based on the information available in the attached **LTI-design.md**, design the **first version of the LTI system architecture**.

The document already contains prior work that must be treated as completed input, not as tasks to redo.

Your job is to:
1. understand the work already completed in the document,
2. propose and compare the most suitable architecture options for the first version of LTI,
3. discuss those options with me first,
4. and only after I explicitly approve one architecture option, produce:
   - **D. High-level system design**, explained in text and with an attached diagram, **not using C4 notation**
   - **E. A C4 diagram** that goes deeper into one relevant system component or area, chosen based on the approved architecture

## Source of truth
Use the attached **LTI-design.md** as the primary source of truth.

The completed work for tasks A, B, and C is already present in **sections 1 to 6** of the document.

You must:
- read and understand sections 1 to 6,
- extract the relevant assumptions, product scope, use cases, and data model from those sections,
- keep naming consistent with the document,
- and ensure the proposed architecture supports what is already defined there.

Do not redo sections 1 to 6.
Do not re-create tasks A, B, or C from scratch.
Only summarize prior work when needed to justify architectural decisions.

If the document has ambiguity or gaps, make reasonable assumptions and state them clearly.

## Process rules
Your work must happen in **2 stages**.

### Stage 1 — Architecture options and discussion
Before producing any diagrams or final architecture deliverables, you must first:
- analyze the existing system definition from sections 1 to 6,
- identify the most viable architecture options for the first version of LTI,
- compare them,
- recommend one,
- and stop there for discussion.

At this stage, you must **not** generate section D or section E yet.

### Stage 2 — Final architecture deliverables
You may only proceed to Stage 2 if I explicitly approve one architecture option.

Accepted examples of explicit approval include:
- “I approve option X”
- “Proceed with option X”
- “Use option X and continue”
- “Go ahead with the modular monolith option”
- “Approved. Now create D and E”

Do not infer approval implicitly.
Do not start D or E just because I ask follow-up questions.
Do not generate diagrams before my explicit approval.

## Interaction rules
1. Before I approve an option, remain in **Stage 1**.
2. In Stage 1, I may ask follow-up questions to help decide.
3. In Stage 1, you may ask brief clarifying questions if missing information would materially affect the recommendation.
4. If information is incomplete but not critical, proceed with reasonable assumptions and state them clearly.
5. Only after my explicit approval may you generate:
   - **D. High-level system design**
   - **E. C4 diagram**
6. If my approval is ambiguous or incomplete, ask for clarification before proceeding.

## Architectural framing
The goal is to define the software architecture and system structure at a level that helps ensure the system is:
- scalable
- secure
- maintainable
- understandable for engineers and stakeholders
- suitable for iterative product development

You should reason about:
- system boundaries
- frontend and backend responsibilities
- APIs
- authentication and authorization
- asynchronous processing
- storage
- search
- notifications
- integrations
- observability
- deployment/runtime implications
- AI-assisted features if they are part of the documented scope

Relevant architecture styles may include, for example:
- modular monolith
- layered architecture
- hexagonal / clean architecture
- service-oriented architecture
- event-driven architecture
- microservices
- or a pragmatic hybrid

Choose architecture options that are realistic for a **first production version** of LTI.

## Scope constraints
1. Base all reasoning on the completed content in sections 1 to 6 of LTI-design.md.
2. Focus on architecture only.
3. Do not redo product strategy, use-case modeling, or the data model.
4. Do not produce implementation tickets, infrastructure-as-code, or low-level deployment scripts.
5. Do not over-engineer for a hypothetical future if a simpler first-version architecture is more appropriate.

## Stage 1 deliverable format
In Stage 1, structure your answer exactly as follows.

### 1. What is already defined in sections 1 to 6
Provide a concise synthesis of the already-completed work from sections 1 to 6, focusing only on what is architecturally relevant:
- product scope
- key user roles
- key workflows
- core domain/data concepts
- major constraints or assumptions
- integrations or external dependencies implied by the document

### 2. Architectural assumptions
List the technical and architectural assumptions you will use to evaluate the options.

### 3. Architecture options for the first version
Propose **3 to 4 realistic architecture options** for LTI.

For each option, include:
- **Option name**
- **Architecture style**
- **Short description**
- **When it is a good fit**
- **Main strengths**
- **Main weaknesses**
- **Operational complexity**
- **Scalability profile**
- **Maintainability implications**
- **Fit for a first-version ATS**
- **Fit for the workflows and scope already defined in sections 1 to 6**

Examples of possible option types may include:
- modular monolith
- modular monolith with event-driven internal workflows
- small-service architecture
- microservices-oriented architecture
- hexagonal modular backend with separate frontend

### 4. Comparative decision matrix
Compare the architecture options in a table.

Use at least these criteria:
- speed of implementation
- simplicity
- operational complexity
- scalability
- maintainability
- extensibility
- support for integrations
- support for asynchronous workflows
- support for AI-assisted features
- fit for first production version
- risk level

Score each option from 1 to 5 and explain the most important trade-offs.

### 5. Recommended option
Recommend the single best option for the first version of LTI.

Include:
- the recommended option
- why it is the best fit
- what it optimizes for
- what is intentionally deferred
- what future signals would justify evolving to a more distributed architecture

### 6. Open questions or discussion points
List the most important questions, trade-offs, or decisions I may want to discuss before approving an option.

### 7. Reply format
End Stage 1 with this exact instruction:

“If you want to discuss before approval, reply with:
- Question or concern:
- Option(s) to discuss:

If you want me to proceed with D and E, reply with:
- Approved option:
- Proceed with D and E: Yes
- Optional priorities or constraints:”

## Stage 2 deliverable format
Only after I explicitly approve one architecture option, generate the following:

### D. High-level system design
Create the high-level design of the first version of LTI.

Requirements:
- explain the selected architecture clearly
- identify the major system building blocks
- explain responsibilities and interaction patterns
- include integrations and external systems
- explain synchronous and asynchronous communication where relevant
- include security and observability considerations
- include one complete **Mermaid** high-level architecture diagram
- do **not** use C4 notation for section D

### E. Focused C4 diagram
Create a **C4-based architecture view** for the most relevant container or area of the approved architecture.

Requirements:
- choose the most relevant area or component to zoom into
- justify why it is the best area to document in more depth
- provide at least a **component-level C4 view**
- keep it useful and not overcomplicated
- include the diagram in diagram-as-code format
- ensure it is consistent with the approved architecture option

## Output requirements
- Write in clear, professional English.
- Be precise and exhaustive, but only within the requested stage.
- In Stage 1, do not generate section D or E.
- In Stage 2, do not redo sections 1 to 6.
- Keep naming consistent with LTI-design.md.
- Make the result useful for architecture discussion, engineering alignment, and implementation planning.

---

# Prompt 5

---

You are an expert Software Analyst and Product Analyst with deep expertise in B2B SaaS, HR Tech, and Applicant Tracking Systems (ATS).

## Objective
Your task is to **improve, complement, and reorganize section 4 of the attached `LTI-design.md`**, which contains the PRD for LTI.

You must strengthen the PRD using the additional PRD guidance provided below, while preserving the original intent, scope, and content already defined in section 4.

## Source of truth
Use the attached `LTI-design.md` as the primary source of truth.

Important constraints:
- **Section 4 is the only section you may modify**
- **Sections 1–3 must not be edited**
- **Sections 5–6 must not be edited at all**
- Treat sections 5–6 as owned by a software architect and therefore out of scope for you
- Do not rewrite the full document
- Do not modify the product strategy, positioning, or scope already defined in section 4 unless a clarification is strictly needed for coherence
- Do not delete existing information from section 4
- Do not contradict existing information in the document

## Your role in this task
You are acting as a **PRD refinement specialist**.

This means:
- first understand the current PRD in section 4,
- identify what is already covered,
- identify what is missing or underdeveloped based on the additional PRD guidance,
- then reorganize and complement section 4 so it becomes a stronger, clearer, more complete PRD.

You are **not** acting as:
- a software architect,
- a system designer,
- a data modeler,
- or a product strategist redefining the product direction.

## Additional PRD guidance to integrate
Use the following guidance to strengthen section 4 where relevant.

A PRD should function as:
- an alignment and communication document for human teams
- and also as an executable specification for AI-assisted development, meaning it should be clear, structured, explicit, and bounded

A strong PRD may include, where relevant:
- introduction and objectives
- stakeholders
- user stories
- main components and sitemap / product structure
- features and functionalities
- design and user experience considerations
- technical requirements
- project planning considerations
- acceptance criteria
- appendices or supporting resources
- explicit non-goals / out of scope
- success metrics / KPIs

You must integrate these ideas only where they improve the current PRD and are relevant to the existing scope of LTI.

## Editing rules
1. **Do not change the scope** of the current PRD.
2. **Do not delete existing information** from section 4.
3. You may:
   - reorganize content,
   - refine headings,
   - merge overlapping content,
   - add missing PRD sections,
   - improve clarity,
   - make boundaries and assumptions more explicit.
4. If the current PRD already covers an item, preserve and improve it rather than replacing it unnecessarily.
5. If a classical PRD component is not relevant at this stage, do not force it.
6. Do not invent large new product areas that are not already implied by the current LTI definition.
7. Keep section 4 consistent with:
   - sections 1–3,
   - the LTI product direction,
   - and the existing scope already documented.
8. Do not modify or reference-edit sections 5–6 beyond acknowledging that they exist and are out of scope.
9. Keep the result practical for both:
   - human product/development teams
   - and AI agents using the PRD as structured implementation input

## Required working method
Follow this process internally before producing the final output:

### Step 1 — Understand the current PRD
Review the existing section 4 and determine:
- what is already strong
- what is missing
- what is redundant
- what is unclear
- what should be reorganized

### Step 2 — Complement without altering scope
Use the additional PRD guidance to enrich section 4 only where it adds real value.

### Step 3 — Reorganize for clarity
Produce a cleaner and more complete PRD structure while preserving all essential original information.

## Required output
Return **only the revised version of section 4** in Markdown.

Do not output:
- sections 1–3
- sections 5–6
- a full rewritten document
- implementation plans
- architecture proposals
- data model changes

## Required output structure
Your answer must contain these two parts in this exact order.

### Part 1 — Brief PRD revision notes
Provide a short summary with:
- what you changed structurally
- what you added
- what you intentionally did not change

Keep this section concise.

### Part 2 — Revised Section 4
Provide the fully revised **section 4 only**, in Markdown, ready to replace the current section 4 in `LTI-design.md`.

## PRD quality requirements
The revised section 4 should:
- preserve the original product scope
- be more complete and better organized than the original
- make goals, boundaries, stakeholders, requirements, and success criteria explicit
- be useful as a reference for product, design, engineering, and AI-assisted development
- avoid redundancy where possible
- remain realistic and aligned with the current maturity of LTI

## Specific content expectations
Ensure the revised PRD explicitly and clearly covers, if not already sufficiently covered:
- product vision
- problem statement
- goals and objectives
- stakeholders
- target users
- value proposition
- scope and non-goals
- core use cases
- user stories
- product structure / main components
- functional requirements
- non-functional requirements
- UX / usability considerations
- technical constraints or technical requirements at PRD level only
- acceptance criteria
- MVP scope
- prioritization
- KPIs / success metrics
- assumptions, dependencies, and risks
- open questions
- any supporting notes that improve the usefulness of the PRD as an implementation reference

## Boundaries
- Do not turn the PRD into a system design document
- Do not turn the PRD into a data model document
- Do not turn the PRD into a roadmap with detailed dates
- Do not rewrite the product strategy from scratch
- Do not edit sections 5–6
- Do not remove existing content from section 4 unless it is purely duplicated and preserved elsewhere in the revised section 4

## Output style
- Write in clear, professional English
- Use clean Markdown headings and subheadings
- Be precise and exhaustive, but do not add unnecessary filler
- Prefer explicitness over ambiguity
- Preserve consistency in terminology across the revised PRD

---

# Prompt 6

---

You are a senior Software Architect and Data Modeling expert with deep expertise in Applicant Tracking Systems (ATS), B2B SaaS platforms, and business-domain data design.

## Objective
Your task is to **improve, complement, and reorganize sections 5 and 6 of the attached `LTI-design.md`** so they are fully aligned with the **canonical MVP scope defined in section 4**, especially the PRD subsection that defines the MVP.

Your goal is to resolve the current mismatch or ambiguity between:
- the **MVP defined in section 4**,
- the **use cases currently defined in section 5**,
- and the **logical data model currently defined in section 6**.

## Source of truth
Use the attached `LTI-design.md` as the primary source of truth.

For this task, the **highest-priority reference is section 4**, especially:
- MVP scope,
- goals,
- core use cases,
- functional requirements,
- acceptance criteria,
- prioritization,
- and scope boundaries.

Sections 5 and 6 must be revised so they are consistent with section 4.

## Canonical interpretation rule
When there is any mismatch, ambiguity, or conflict between:
- section 4,
- section 5,
- and section 6,

you must treat **section 4 as the canonical product definition**, especially the part defining the **MVP**.

This means:
- section 5 must be updated to cover the use cases truly needed to fulfill the MVP in section 4,
- and section 6 must be updated to support those revised MVP-aligned use cases.

Do **not** preserve a narrower interpretation from sections 5 or 6 if it conflicts with the MVP in section 4.

## Scope of your edits
You may modify **only**:
- section 5
- section 6

You must **not** modify:
- sections 1–4
- any strategy, positioning, or PRD content already defined in section 4

You may summarize section 4 internally to guide your revisions, but do not rewrite it.

## Key problem to solve
The current sections 5 and 6 appear to reflect a narrower “first useful version” than the MVP now defined in section 4.

Your job is to remove that ambiguity and produce a version of sections 5 and 6 that:
1. reflects the MVP in section 4,
2. includes the **minimum relevant set of use cases required to fulfill that MVP**,
3. and defines a logical data model that supports those MVP use cases.

The updated section 5 may include **more than 3 use cases** if that is necessary to fulfill the MVP, but you must still keep the set lean and relevant.

## Editing principles
1. **Section 4 is authoritative.**
2. Do not change product scope; align to the scope already defined in section 4.
3. Do not invent large new product areas that are not implied by section 4.
4. Do not keep outdated constraints from the old section 5 or 6 if they conflict with section 4.
5. Keep the result lean, practical, and implementation-oriented.
6. Include only the most relevant use cases and data entities necessary to support the MVP.
7. Preserve consistency in naming across:
   - product concepts,
   - use cases,
   - entities,
   - and diagrams.
8. Use **Mermaid** for all updated diagrams in sections 5 and 6.
9. For **section 5**, create **exactly one Mermaid diagram per use case**.
10. For **section 6**, create **one complete Mermaid ER diagram** for the logical data model.
11. If something is ambiguous, state the assumption clearly instead of pretending certainty.

## Mermaid diagram safety rules
To avoid rendering or parser errors:
1. Every Mermaid diagram must be provided in its **own standalone Mermaid code block**.
2. Each Mermaid code block must begin immediately with a valid Mermaid diagram type declaration, for example:
   - `flowchart LR`
   - `flowchart TD`
   - `sequenceDiagram`
   - `erDiagram`
3. Do not place explanatory text, bullets, Markdown headings, or comments inside the Mermaid code block.
4. Do not nest Mermaid code blocks inside other code blocks.
5. Do not leave blank or malformed Mermaid blocks.
6. Use Mermaid syntax that is valid and conservative rather than clever or overly advanced.
7. Avoid labels or tokens that commonly break Mermaid parsing.
8. In flowcharts, avoid using the lowercase word `end` as a node label; if needed, use `End`, `END`, or a different label.
9. Keep node labels simple and avoid unusual punctuation unless clearly safe.
10. Before presenting each Mermaid diagram, ensure the syntax is coherent and the diagram type is explicitly declared.

## What section 5 must become
Section 5 must be revised into an MVP-aligned use-case section.

It should:
- no longer be limited to exactly 3 use cases if that is insufficient,
- include the minimum number of high-value use cases needed to fulfill the MVP in section 4,
- reflect the real MVP boundaries,
- and remain lean.

The selected use cases should collectively cover the MVP behavior defined in section 4, including where relevant:
- requisition and approval
- structured hiring plan / scorecards
- candidate intake and structured candidate profile
- recruiter and hiring-manager review
- interview coordination and structured feedback
- workflow automation relevant to the MVP
- real-time recruiting ops visibility relevant to the MVP
- offer workflow
- onboarding handoff basics

Do not force one use case per feature if a clearer grouping is more useful.
However, do not omit an MVP capability that requires explicit use-case coverage.

## What section 6 must become
Section 6 must be revised into a logical data model that supports the revised MVP-aligned section 5.

It should:
- cover the entities, attributes, and relationships needed to support the MVP-aligned use cases,
- remove outdated boundaries that were based on the older narrower interpretation,
- and remain a logical data model, not a physical database design.

If the MVP in section 4 includes areas that are missing from the current section 6, such as offer workflow, onboarding handoff basics, or operational visibility requirements, section 6 must be updated accordingly.

## Required working method
Follow this process internally before producing the final answer.

### Step 1 — Read and understand the canonical MVP
Review section 4 and identify:
- the actual MVP scope,
- required product behaviors,
- required workflows,
- and any capabilities that section 5 and 6 currently underrepresent or exclude.

### Step 2 — Identify the mismatch
Briefly determine:
- which important MVP capabilities are missing from section 5,
- which important MVP capabilities are unsupported or under-modeled in section 6,
- and what must change to realign both sections.

### Step 3 — Revise section 5
Create a revised set of MVP-aligned use cases.
Use only the minimum relevant number needed to fulfill the MVP.

### Step 4 — Revise section 6
Create a revised logical data model that directly supports the updated section 5 and the canonical MVP in section 4.

## Required output
Return your answer in the following structure and in this exact order.

### Part 1 — Alignment notes
Provide a concise summary of:
- the main mismatch you found,
- what changed in section 5,
- what changed in section 6,
- and what you intentionally kept unchanged.

Keep this part brief and decision-oriented.

### Part 2 — Revised Section 5
Provide the fully revised **section 5 only**, in Markdown, ready to replace the current section 5.

Section 5 should include:
1. **Assumptions**
2. **MVP-aligned top use cases**, in priority order
3. For each use case:
   - name
   - purpose
   - primary actor(s)
   - supporting actor(s), if relevant
   - preconditions
   - main flow
   - dependencies
   - postconditions
   - why it is required for the MVP
4. **One Mermaid diagram for that use case**
5. **Validation notes**, explaining why this use-case set is sufficient for the MVP in section 4

Important:
- Do not keep the old “top 3 use cases” framing if it is no longer valid.
- Use Mermaid only.
- Create **one separate Mermaid diagram per use case**.
- Each use-case diagram must be output in its **own standalone Mermaid code block**.
- Each Mermaid block must begin with a valid Mermaid diagram type declaration.
- Ensure the diagram syntax is valid and does not produce parser/rendering errors.

### Part 3 — Revised Section 6
Provide the fully revised **section 6 only**, in Markdown, ready to replace the current section 6.

Section 6 should include:
1. **Assumptions and modeling boundary**
2. **Entity inventory**
   - core entities
   - supporting entities
   - associative / junction entities
3. **Detailed logical data model**
   - entity name
   - purpose
   - primary key
   - attributes with name, generic type, description, notes
   - important relationships
4. **Relationships summary**
5. **One complete Mermaid ER diagram**
6. **Modeling notes and validation**

Important:
- The data model must support the revised MVP-aligned section 5.
- It must also reflect the MVP commitments in section 4.
- Keep it as a logical data model, not SQL or physical schema design.

## Data-modeling rules
1. Use practical generic data types such as:
   - `uuid`
   - `string`
   - `text`
   - `boolean`
   - `integer`
   - `decimal`
   - `date`
   - `datetime`
   - `enum`
   - `json`
2. Explicitly identify:
   - primary keys
   - foreign keys where relevant
   - important status/lifecycle fields
   - important audit fields where relevant
3. Resolve many-to-many relationships with junction entities when appropriate.
4. Do not over-model speculative future functionality that is outside the MVP in section 4.
5. Do not under-model an MVP capability that section 4 clearly requires.

## Boundaries
- Do not edit sections 1–4.
- Do not redefine the business strategy.
- Do not create system architecture.
- Do not produce implementation tickets.
- Do not produce SQL.
- Do not generate multiple alternative versions unless truly necessary.
- Do not preserve outdated exclusions from the old section 5 or 6 if they contradict section 4.

## Output style
- Write in clear, professional English.
- Be precise and exhaustive, but stay focused only on updating sections 5 and 6.
- Keep the result lean, coherent, and implementation-useful.
- Preserve terminology consistency across both sections.
- Make the updated sections clearly usable as a continuation of the existing `LTI-design.md`.

---

# Prompt 7

---

You are a senior Software Architect with deep expertise in Applicant Tracking Systems (ATS), B2B SaaS platforms, and software architecture documentation using the C4 model.

## Objective
Your task is to read and understand the attached **LTI-design.md** and then create the **remaining C4 component-level views and interpretations** needed for the system, following the same architectural style and documentation pattern already used for the **Async Worker Runtime** in section 8.

Your goal is to extend the architecture documentation so that the other major system areas are documented at the same level of architectural clarity, while staying fully consistent with:
- the product scope,
- the MVP boundaries,
- the logical data model,
- the approved high-level architecture,
- and the existing focused C4 example already present in the document.

## Source of truth
Use the attached **LTI-design.md** as the primary and authoritative source of truth.

Pay special attention to:
- **section 6** for the logical data model and business-domain boundaries,
- **section 7** for the approved high-level architecture and major system building blocks,
- **section 8** for the already documented C4 component-level example and its interpretation style.

You must remain fully aligned with sections 6 to 8.

## Scope of the task
This task is **not** to redesign the system architecture.

This task is to:
1. understand the architecture already defined,
2. identify which **remaining architecturally relevant containers or major system areas** still need a component-level C4 view,
3. and produce those missing component-level views plus their interpretations.

## Important interpretation rule
In the C4 model, a **component diagram** is a zoom-in of a **single container or clearly bounded area**.

Therefore:
- do **not** create one giant diagram for the whole system,
- do **not** create code-level or class-level diagrams,
- and do **not** treat every minor technical element as needing its own C4 view.

Instead, identify the **remaining major containers / bounded architectural areas** from the approved high-level architecture that genuinely benefit from component-level documentation.

## Existing work that must not be redone
Section 8 already contains a focused C4 component-level view and interpretation for the **Async Worker Runtime**.

You must:
- treat that section as already completed,
- use it as the stylistic and structural reference,
- and **not** recreate or contradict it.

Only extend the documentation for the **other relevant parts of the system**.

## Architecture consistency rules
1. Stay fully consistent with the high-level architecture in section 7.
2. Stay fully consistent with the data boundaries and modeling choices in section 6.
3. Preserve the approved architectural style:
   - hexagonal modular monolith with internal domain events and async workers
   - separate internal ATS web app and candidate application web app
   - one authoritative transactional core
   - bounded workflow automation
   - derived workspace and recruiting-ops views
4. Do not introduce new product scope that is outside the MVP already defined.
5. Do not invent major new containers, services, or subsystems unless they are clearly implied by sections 6 to 8.
6. If a possible component view would add little value, say so and do not force it.

## Diagram notation rules
Use the **same C4 diagram-as-code notation already used in section 8**.

Requirements:
- keep notation consistent with the existing document
- keep naming consistent with the rest of the markdown file
- use proper C4 component-level thinking
- make the diagrams understandable as standalone artifacts
- include clear labels and short descriptions for components where the notation supports it
- use explicit relationship labels
- include technologies where they are useful and justified

If the existing notation in section 8 is Mermaid C4 syntax, continue using that same syntax family and remain conservative and explicit in the syntax.

## What “the rest of the system components” should mean in this task
Interpret this as:
- the remaining **major architectural containers or bounded areas** from the approved system design
- excluding the **Async Worker Runtime**, which is already documented

Likely candidates may include areas such as:
- the **ATS Core Backend**
- the **Internal ATS Web App**
- the **Candidate Application Web App**

However, do not assume these automatically.
First evaluate which of them genuinely merit a component-level C4 view and document only those that add meaningful architectural value.

Do not create component-level views for:
- trivial containers,
- purely external systems,
- or generic infrastructure elements unless they are part of the container being decomposed.

## Required working method
Follow this process internally before producing the final answer.

### Step 1 — Understand the existing architecture
Read sections 6, 7, and 8 and extract:
- the core architectural style,
- the main containers / bounded areas,
- the main responsibilities of each,
- and the boundaries already established.

### Step 2 — Identify what is already documented vs missing
Determine:
- which component-level C4 view is already covered,
- which important containers / areas remain undocumented,
- and which of those are valuable enough to decompose further.

### Step 3 — Select the containers / areas to document
Choose only the remaining areas that truly benefit from a component-level view.

For each selected area, explain why it deserves a dedicated component-level decomposition.

### Step 4 — Create the component-level C4 views and interpretations
For each selected area:
- define the container or bounded area in scope,
- identify its main components,
- show how those components interact,
- connect them to the relevant neighboring containers / systems,
- and explain the architectural intent.

## Required output structure
Your answer must follow this exact structure.

### 1. Architectural baseline understood from sections 6 to 8
Provide a concise synthesis of the architecture already defined in the document, focusing only on what is relevant for this task:
- approved architecture style
- main containers / bounded areas
- key architectural constraints
- already documented C4 scope
- consistency requirements for the remaining diagrams

### 2. Existing vs missing component-level documentation
State:
- what component-level C4 documentation already exists
- which major architectural areas remain undocumented at component level
- which of those are worth documenting
- which are not worth documenting and why

### 3. Selected areas for additional C4 component views
List the selected remaining areas you will document.

For each selected area, include:
- **Area / container name**
- **Why it deserves a component-level view**
- **What architectural questions it helps answer**

### 4. Component-level C4 views and interpretations
For each selected area, provide the following subsections.

#### Area X — [Name]

##### A. Scope of this C4 view
Explain:
- what container or bounded area is in scope
- what is outside scope
- how it fits into the overall LTI system

##### B. Main components
List the main components inside this area.

For each component, include:
- name
- responsibility
- main interfaces or interaction points
- important dependencies
- why it exists as a separate component

##### C. C4 component diagram
Provide the full diagram-as-code block for this area using the same C4 notation already used in section 8.

Requirements:
- one diagram per selected area
- scope must stay at component level
- relationships must be clearly labeled
- components must be named consistently with the rest of the file
- avoid unnecessary diagram noise

##### D. Interpretation
After the diagram, explain:
- the architectural role of this area
- how responsibilities are partitioned
- why the chosen component boundaries make sense
- how the area interacts with the transactional core, data layer, async processing, or external integrations where relevant
- any important trade-offs or design decisions

### 5. Cross-area consistency notes
Conclude with a short section explaining:
- how the new component views stay aligned with sections 6 to 8
- any assumptions made
- any architectural areas that may deserve deeper documentation later
- any parts that should remain undocumented at component level for now to avoid unnecessary complexity

## Output requirements
- Write in clear, professional English.
- Be precise and exhaustive, but stay focused only on extending the component-level C4 documentation.
- Do not redesign the architecture.
- Do not recreate the Async Worker Runtime component view.
- Do not produce code-level or class-level diagrams.
- Do not produce implementation tickets or backlog items.
- Do not create a single system-wide mega-diagram.
- Do not change the architecture unless a contradiction in the existing document absolutely requires a clearly stated assumption.
- Keep the output fully consistent with sections 6, 7, and 8 of LTI-design.md.
- Prefer architectural usefulness and clarity over completeness for its own sake.