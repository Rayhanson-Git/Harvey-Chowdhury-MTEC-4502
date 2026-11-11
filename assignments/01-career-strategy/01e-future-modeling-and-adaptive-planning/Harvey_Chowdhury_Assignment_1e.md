# Assignment 1e v2

## Future Modeling, Recursive Competency Mapping, and Adaptive Planning

Harvey Chowdhury  
MTEC 4502 - Career and Portfolio Seminar  
Dr. David B. Smith  
November 11, 2026

**Review draft.** Personal ratings and growth targets await my review. The shared Zotero save is pending. This is not marked ready to submit.

## 1. Future-of-work synthesis

My goal is to become an applied AI engineer who builds agentic systems, retrieval applications, and automation tools. I also want to connect that work with game design, visual design, sound, and video. Game design was my original ambition. My portfolio now includes a small browser game, gesture-controlled experiences, an audio story, and workout applications. Those projects give me a starting point, but they do not establish that I am ready for every engineering role.

In Assignment 1d, I clarified that automation and integration matter more to me than choosing a polished job title. I still agree with that direction. What has changed is the evidence available to explain it. My contribution to Tesseract gives me an example of working on an existing shared-memory system. JimBro and my creative projects show other ways I connect an idea with an interactive result. I need a strategy that develops the engineering underneath those experiences.

The World Economic Forum expects AI-related skills to grow in importance while analytical thinking, creativity, and adaptability remain valuable [S1]. Its forecast reaches 2030. For the following five to ten years, approximately 2031 to 2036, I treat changes as scenarios rather than predictions. One possibility is that applied engineers spend less time assembling standard components and more time defining problems, evaluating results, and maintaining systems. Another is that roles split between general integration work and deeper specializations in retrieval, evaluation, or interactive tools.

Anthropic's coding study shows substantial delegation to coding agents, including workflows that still involve human feedback [S2]. That supports my interest in directing systems, but the study does not prove that generated code is correct or that developers become more productive. Repetitive scaffolding, simple interface assembly, and routine asset variations may become less distinctive portfolio evidence. Debugging, data handling, evaluation, and explaining why a system behaves as it does remain priorities in my plan.

My interest in games needs the same scrutiny. GDC's survey reports both generative-AI use and strong negative sentiment, alongside employment concerns [S3]. Easier prototyping does not guarantee a good player experience or a job. I want to build beyond Wasp Dodge+, but I need to demonstrate mechanics, feedback, iteration, and testing. My creative background can help me identify useful applications, rather than assume every game task benefits from automation.

My most robust strategy is connecting technical systems with practical and creative problems. Tesseract began with a need I could explain: several agents should share useful memory without repeated interruptions. I tested the original setup, investigated weaknesses, reviewed code, and directed changes. My merged contribution addresses concurrent note creation and agent identity [E1]. In my own setup, I report that daily maintenance, live writing, and reduced interruptions work. Those reports are different from a controlled benchmark or proof of other users' results.

The vulnerable part is retrieval quality. I sometimes received outdated or less relevant memory, and I have not implemented a specific fix. My planned Rust system will investigate dated records, conflicting facts, and verified updates. Newer records cannot automatically count as more accurate. I need tests that distinguish when information was recorded from when it became valid, and retain uncertainty when a conflict cannot be resolved.

My revised chart therefore separates integration from evaluation and leaves unverified abilities unassessed. An applied-AI role example also expects programming, retrieval, reliable prototypes, and communication [S4]. I will first build a small memory-evaluation set, then a bounded Rust retrieval prototype. A later game prototype can test the same engineering habits in a creative setting. I will review the chart after each milestone instead of raising scores simply because I have added another feature.

**Synthesis word count:** 599, including in-text source markers and excluding headings, tables, and references.

## 2. Role-level competency map

**Direction:** Applied AI engineering with creative and game-development applications.

These are provisional assessments for review, not employer scores or grades. They describe the evidence available on November 11, 2026. Tools and collaborators are permitted within a competency when their contribution is explained. Project code alone does not establish individual programming depth. Not assessed means evidence is insufficient, not that ability is zero. Targets are proposed development goals by May 2028 and are not employer requirements. A parent score is a holistic judgment, not the arithmetic mean of its sub-radar. The lower evaluation score reflects informal testing evidence rather than the sophistication of the software.

**Scale:** 1 = Not yet demonstrated | 2 = Emerging | 3 = Basic competence | 4 = Strong and consistent | 5 = Advanced or able to teach and lead. Not assessed is outside the numerical scale.

![Role-level radar](visuals/role-radar.png)

| ID | Competency | Observable behavior | Current | Target | Evidence |
| --- | --- | --- | --- | --- | --- |
| M1 | AI integration | Connect existing models, memory, and tools into a usable application. | 3 | 4 | E1, E7, E8 and student setup report |
| M2 | Programming and debugging | Trace behavior, isolate a defect, and justify a code change. | Not assessed | 4 | E1, E3, E6 and student code-review account |
| M3 | Interactive prototyping | Build a task or play loop with clear input, state, and feedback. | 3 | 4 | E3, E4, E6, E9, E10 |
| M4 | Creative production | Shape visual or audio material to communicate an intended experience. | 3 | 4 | E9, E10, E11, E12 |
| M5 | Testing and evaluation | Define success, challenge failures, and compare observed outcomes. | 2 | 4 | Student Tesseract stress tests, E1 and E3 test artifacts |
| M6 | Research and adaptation | Compare evidence and use it to justify a technical or career decision. | 3 | 4 | Prior 1b job analysis, 1d decisions and Tesseract investigation |
| M7 | Collaboration and communication | Explain contributions, coordinate changes, and respond to feedback. | 3 | 4 | E1, E2, E3 reflection and E12 |
| M8 | Workflow and delivery | Package, publish, document, and maintain usable project versions. | 4 | 4 | E3, E5-E12 and repository release records |


### Why these axes

The main chart combines technical execution with research, collaboration, communication, and delivery. S1 supports that mixed approach. S4 provides a concrete role example for integration, programming, evaluation, and communication. Creative production and interactive prototyping reflect my intended application area rather than duties required by every AI engineering role. The chart is a planning model, not a qualification claim for S4.

## 3. Recursive competency maps

### AI integration

![AI integration sub-radar](visuals/integration-radar.png)

This breaks M1 into component configuration, memory workflows, agent identity, retrieval quality, and autonomous operation. A working connection and a correct retrieved answer are different claims. My unresolved freshness issue belongs on the chart even though I report that the surrounding workflow works well.

### Testing and evaluation

![Testing and evaluation sub-radar](visuals/evaluation-radar.png)

This breaks M5 into exploration, reproduction, automated regression, retrieval evaluation, and user testing. Repository test files are evidence that checks exist. They do not by themselves establish what I personally ran or how I interpreted a failure. Missing assessed evidence is shown as a gap rather than zero.

## 4. Competency rubrics

### M1 - AI integration

| Criterion | Description |
| --- | --- |
| Observable behavior | Connect existing models, memory, and tools into a usable application. |
| 1 | Cannot yet connect a model or tool in a guided exercise. |
| 2 | Connects one component with guidance but cannot trace the full flow. |
| 3 | Demonstrates a bounded integration and explains its input and output. |
| 4 | Reproduces integrations consistently and handles dependency failures. |
| 5 | Leads reusable integration architecture and validates adoption by others. |
| Current / target | 3 / 4 |
| Evidence | E1, E7, E8 and student setup report |
| Rating rationale | A merged multi-agent contribution and creative model integrations support basic integration. Wider reliability remains unverified. |
| Next action | Document one complete integration with repeatable setup and failure tests. |

### M2 - Programming and debugging

| Criterion | Description |
| --- | --- |
| Observable behavior | Trace behavior, isolate a defect, and justify a code change. |
| 1 | Cannot yet trace a simple program or locate an identified defect. |
| 2 | Makes guided edits and recognizes basic error messages. |
| 3 | Explains a module and fixes a bounded defect with a passing test. |
| 4 | Diagnoses unfamiliar defects and checks regressions across modules. |
| 5 | Leads difficult debugging and teaches the reasoning to collaborators. |
| Current / target | Not assessed / 4 |
| Evidence | E1, E3, E6 and student code-review account |
| Rating rationale | Repository code exists and code inspection is reported. A direct walkthrough is still needed to assess individual programming depth. |
| Next action | Walk through one defect and fix with a reproducible test and explanation. |

### M3 - Interactive prototyping

| Criterion | Description |
| --- | --- |
| Observable behavior | Build a task or play loop with clear input, state, and feedback. |
| 1 | Cannot yet assemble an interactive sequence. |
| 2 | Creates isolated controls with incomplete state transitions. |
| 3 | Produces a working bounded flow with understandable feedback. |
| 4 | Refines complete flows through observed use and edge-case testing. |
| 5 | Leads reusable interaction patterns validated across users and projects. |
| Current / target | 3 / 4 |
| Evidence | E3, E4, E6, E9, E10 |
| Rating rationale | Several working project structures support basic competence. Recent human validation is not established by this inspection. |
| Next action | Observe another person completing a task and revise one confusing interaction. |

### M4 - Creative production

| Criterion | Description |
| --- | --- |
| Observable behavior | Shape visual or audio material to communicate an intended experience. |
| 1 | Cannot yet prepare a usable visual or audio asset. |
| 2 | Produces simple assets with inconsistent technical or narrative control. |
| 3 | Creates a coherent bounded piece and documents production decisions. |
| 4 | Iterates consistent media quality against audience and delivery needs. |
| 5 | Directs a cohesive production and mentors others through its pipeline. |
| Current / target | 3 / 4 |
| Evidence | E9, E10, E11, E12 |
| Rating rationale | Published visuals and a documented audio story support a bounded production claim. The music video remains uninspected. |
| Next action | Publish a before-and-after edit with rationale and audience feedback. |

### M5 - Testing and evaluation

| Criterion | Description |
| --- | --- |
| Observable behavior | Define success, challenge failures, and compare observed outcomes. |
| 1 | Cannot yet identify a checkable success or failure condition. |
| 2 | Explores failures and records observations informally. |
| 3 | Runs repeatable cases with expected results and records fixes. |
| 4 | Combines regression, retrieval, and usability evidence across releases. |
| 5 | Designs evaluation strategy and independently audits coverage and limits. |
| Current / target | 2 / 4 |
| Evidence | Student Tesseract stress tests, E1 and E3 test artifacts |
| Rating rationale | Exploratory stress testing is described. Existing automated test artifacts do not establish which evaluations the student personally ran. |
| Next action | Convert exploratory checks into a repeatable test set with expected outcomes. |

### M6 - Research and adaptation

| Criterion | Description |
| --- | --- |
| Observable behavior | Compare evidence and use it to justify a technical or career decision. |
| 1 | Cannot yet locate or identify a relevant source. |
| 2 | Collects sources but accepts claims without checking fit. |
| 3 | Uses relevant sources and explains a decision with stated limitations. |
| 4 | Triangulates conflicting sources and tests uncertain technical claims. |
| 5 | Builds reusable research methods and helps others evaluate evidence. |
| Current / target | 3 / 4 |
| Evidence | Prior 1b job analysis, 1d decisions and Tesseract investigation |
| Rating rationale | Prior career analysis and the reported investigation show evidence-led iteration. Current source selection still needs final student review. |
| Next action | Compare two retrieval approaches with citations, tradeoffs, and a small experiment. |

### M7 - Collaboration and communication

| Criterion | Description |
| --- | --- |
| Observable behavior | Explain contributions, coordinate changes, and respond to feedback. |
| 1 | Cannot yet explain role or communicate a proposed change. |
| 2 | Shares progress but contribution boundaries remain unclear. |
| 3 | Explains a bounded contribution and responds to review or feedback. |
| 4 | Coordinates multi-person changes with clear handoffs and documented outcomes. |
| 5 | Leads collaboration and develops practices adopted by others. |
| Current / target | 3 / 4 |
| Evidence | E1, E2, E3 reflection and E12 |
| Rating rationale | The merged pull request and clarified contributor role support a bounded collaboration claim, not team leadership. |
| Next action | Add a concise contribution case study linking request, review, change, and outcome. |

### M8 - Workflow and delivery

| Criterion | Description |
| --- | --- |
| Observable behavior | Package, publish, document, and maintain usable project versions. |
| 1 | Cannot yet produce a runnable or shareable project version. |
| 2 | Shares a project that depends on undocumented setup. |
| 3 | Publishes a usable version with setup and limitation notes. |
| 4 | Repeatedly delivers projects with organized source and release evidence. |
| 5 | Leads a reproducible delivery process that others can maintain independently. |
| Current / target | 4 / 4 |
| Evidence | E3, E5-E12 and repository release records |
| Rating rationale | Multiple live projects and dated release records support a provisional four. Maintenance by other users has not been demonstrated. |
| Next action | Test one clean installation or recovery with another user. |

### A1 - Model and tool configuration

| Criterion | Description |
| --- | --- |
| Observable behavior | Configure a model or service and explain its operational inputs. |
| 1 | Cannot yet configure a guided model call. |
| 2 | Runs a sample configuration without explaining its options. |
| 3 | Configures a bounded service and explains key options and outputs. |
| 4 | Reproduces configuration and manages version or dependency changes. |
| 5 | Creates reusable configuration standards validated by other users. |
| Current / target | 3 / 4 |
| Evidence | E7, E8 and student Tesseract setup |
| Rating rationale | Creative projects integrate existing vision models. This is application evidence, not evidence of model training. |
| Next action | Reproduce configuration from a clean documented setup. |

### A2 - Memory workflows

| Criterion | Description |
| --- | --- |
| Observable behavior | Describe and implement when agents read, write, and maintain memory. |
| 1 | Cannot yet trace where a memory record is stored. |
| 2 | Reads or writes a sample note with guidance. |
| 3 | Demonstrates a bounded write, retrieval, and maintenance flow. |
| 4 | Checks persistence and recovery across repeated sessions. |
| 5 | Designs audited memory lifecycles used reliably by other teams. |
| Current / target | 3 / 4 |
| Evidence | E1 and student report of daily maintenance and live writes |
| Rating rationale | The student reports a working personal setup. No independent daily-scheduler run was observed in this review. |
| Next action | Record a repeatable write-to-recall journey and recovery case. |

### A3 - Agent identity and shared writes

| Criterion | Description |
| --- | --- |
| Observable behavior | Preserve contributor identity and prevent conflicting note creation. |
| 1 | Cannot yet distinguish contributors or detect a collision. |
| 2 | Labels agents manually without checking concurrent writes. |
| 3 | Implements a bounded identity or collision fix with test evidence. |
| 4 | Reproduces concurrent behavior across supported platforms and failure paths. |
| 5 | Designs shared-write contracts and validates independent multi-agent deployments. |
| Current / target | 3 / 4 |
| Evidence | E1 and its multi-agent test file |
| Rating rationale | Merged PR #21 specifically addresses identity and create collisions. Tests were inspected, not rerun here. |
| Next action | Reproduce concurrent writes and inspect identity metadata. |

### A4 - Retrieval relevance and freshness

| Criterion | Description |
| --- | --- |
| Observable behavior | Select relevant current evidence while retaining historical context. |
| 1 | Cannot yet explain whether a retrieved item answers a question. |
| 2 | Recognizes irrelevant or stale recall but lacks a measured correction. |
| 3 | Evaluates a repeatable query set and implements one verified improvement. |
| 4 | Handles current, historical, and conflicting evidence with measured results. |
| 5 | Leads temporal retrieval evaluation with independently reviewed benchmarks. |
| Current / target | 2 / 4 |
| Evidence | Student report of stale or less relevant recall |
| Rating rationale | The problem was observed and explained. No specific Tesseract retrieval correction was implemented. |
| Next action | Build dated and contradictory memory cases with expected answers. |

### A5 - Autonomous operation

| Criterion | Description |
| --- | --- |
| Observable behavior | Schedule background work with clear behavior and visible failures. |
| 1 | Cannot yet run a background task reliably in a guided setup. |
| 2 | Runs a manual task but repeated execution needs intervention. |
| 3 | Demonstrates scheduled operation and explains its intended behavior. |
| 4 | Records repeated runs and recovers from a realistic interruption. |
| 5 | Designs unattended operation validated across independently maintained installations. |
| Current / target | 3 / 4 |
| Evidence | Student report of daily maintenance and fewer interruptions |
| Rating rationale | The personal setup is reported working. One-time setup for a wider user population is an untested usability hypothesis. |
| Next action | Record scheduled runs, exceptions, and a failure-recovery example. |

### T1 - Exploratory testing

| Criterion | Description |
| --- | --- |
| Observable behavior | Challenge a system with varied inputs and record what happens. |
| 1 | Cannot yet suggest a meaningful variation in input. |
| 2 | Tries variations without recording their purpose or result. |
| 3 | Targets a failure area and explains an observed problem. |
| 4 | Systematically explores boundaries and preserves reproducible findings. |
| 5 | Leads risk-based exploratory sessions and improves others' test coverage. |
| Current / target | 3 / 4 |
| Evidence | Student Tesseract stress-testing account |
| Rating rationale | The student identified interruption and retrieval problems through varied personal use. |
| Next action | Turn one exploratory session into a dated issue log. |

### T2 - Failure reproduction

| Criterion | Description |
| --- | --- |
| Observable behavior | Capture conditions that reliably produce a reported defect. |
| 1 | Cannot yet describe a failure beyond saying it did not work. |
| 2 | Describes a failure but lacks sufficient steps to reproduce it. |
| 3 | Supplies repeatable steps and separates symptom from cause. |
| 4 | Minimizes intermittent failures and confirms cause with controlled changes. |
| 5 | Creates reusable diagnostic methods for complex system failures. |
| Current / target | 2 / 4 |
| Evidence | Student recall and approval-interruption reports |
| Rating rationale | Symptoms are clear, but no captured failing query or approval trace was supplied in this exchange. |
| Next action | Save minimal inputs, environment details, and expected versus actual output. |

### T3 - Automated regression

| Criterion | Description |
| --- | --- |
| Observable behavior | Use repeatable checks to protect behavior after changes. |
| 1 | Cannot yet execute or interpret a guided automated check. |
| 2 | Runs a suite with help but cannot explain its assertions. |
| 3 | Adds or explains a regression case and interprets its result. |
| 4 | Maintains representative regression coverage across releases. |
| 5 | Designs evaluation infrastructure and audits misleading or weak assertions. |
| Current / target | Not assessed / 4 |
| Evidence | E1 and E3 automated test artifacts |
| Rating rationale | Tests exist in repositories. Personal execution and interpretation remain unassessed, rather than scored as low ability. |
| Next action | Personally run a focused suite and explain a failing and passing case. |

### T4 - Retrieval evaluation

| Criterion | Description |
| --- | --- |
| Observable behavior | Compare returned evidence against a defined correct or acceptable answer. |
| 1 | Cannot yet define a relevant answer for a sample query. |
| 2 | Judges individual results informally without a stable evaluation set. |
| 3 | Runs labeled queries and reports relevance or freshness outcomes. |
| 4 | Compares versions with defined measures and analyzes failures. |
| 5 | Publishes reproducible evaluations with independent review and contamination controls. |
| Current / target | 2 / 4 |
| Evidence | Student report of stale or irrelevant memory |
| Rating rationale | Informal recall challenges were reported. No measured relevance or freshness score is established. |
| Next action | Create 20 queries covering current facts, changes, conflicts, and unknowns. |

### T5 - User and player testing

| Criterion | Description |
| --- | --- |
| Observable behavior | Observe another person using a flow and revise from evidence. |
| 1 | Cannot yet define an observable task for a tester. |
| 2 | Collects general opinions without observing task behavior. |
| 3 | Observes a task, records difficulties, and makes a justified revision. |
| 4 | Repeats testing across user types and checks whether revisions help. |
| 5 | Leads a rigorous user-testing process with defensible outcomes. |
| Current / target | Not assessed / 3 |
| Evidence | E4 next-step statement and E6 gameplay artifact |
| Rating rationale | Artifacts establish interfaces and a game. Fresh human test outcomes were not established in the reviewed material. |
| Next action | Observe two people performing a task and playing one short session. |


## 5. Adaptive action plan

My strongest documented area is delivering and presenting projects. My vulnerable areas are measured retrieval quality, repeatable failure reproduction, and evidence of individual programming depth. I will prioritize the Rust memory project because it addresses a problem I actually encountered. I will preserve game development as a connected direction, using a small prototype rather than beginning a large game alongside the retrieval rebuild. The previously recorded planning limit is 3-4 project hours weekly and $20-$60 monthly total AI spending. I will reconfirm those limits before expanding scope. No new hardware purchase or subscription is assumed.

| When | Priority | Evidence of progress | Constraint | Axes |
| --- | --- | --- | --- | --- |
| Weeks 1-2 after review | Define a memory evaluation set | 20 labeled queries covering current facts, older facts, contradictions, irrelevant matches, and unknown answers. Record expected evidence and output before changing retrieval. | 2 weekly sessions within the previously recorded 3-4 project hours | M5, A4, T2, T4 |
| Weeks 3-4 | Test the current baseline | Run the same queries, record source dates and relevance judgments, and write a reproducible account of at least one stale-result failure. Record maintenance runs and interruption causes separately. | No new paid service assumed | A2, A5, T1, T4 |
| Weeks 5-8 | Build a bounded Rust retrieval prototype | Use a small synthetic dataset. Store event time, record time, source, and update links. Test verified updates, incorrect newer statements, and unresolved conflicts against the baseline. | Keep full Tesseract feature parity outside this milestone | M1, M2, A4, T3 |
| Weeks 9-12 | Validate and communicate | Ask another person to run setup or recall tasks. Document results and my contribution. Build one small game or creative interaction only if the retrieval milestone is complete and time permits. | Retain school and family priorities | M3, M7, M8, T5 |
| Each milestone through May 2028 | Review the chart | Update scores only when the rubric and evidence support a change. Recheck relevant job expectations, revise the portfolio, and select the next gap. | Reconfirm available time and budget before expansion | All axes |


The plan changes my earlier framework from a broad automation ambition into a testable sequence. I will collect a baseline, implement a bounded change, compare results, and update the chart. Chronology alone is not correctness. My proposed memory design will retain sources and history, distinguish event dates from recording dates, and mark unresolved conflicts instead of selecting the newest text automatically.

## 6. Annotated research

### S1 - The Future of Jobs Report 2025 - Skills outlook

World Economic Forum. 2025. Core reading. Accessed November 11, 2026.

https://www.weforum.org/publications/the-future-of-jobs-report-2025/3-skills-outlook

The employer survey anticipates changing skill needs through 2030 and emphasizes analytical, technical, creative, and adaptive capabilities. I use it to justify a mixed competency map, while treating employer expectations as forecasts rather than guaranteed outcomes.

### S2 - Anthropic Economic Index: AI's impact on software development

Anthropic. 2025-04-28. New independent research. Accessed November 11, 2026.

https://www.anthropic.com/research/impact-software-development

This analysis examines 500,000 coding interactions and distinguishes task automation from collaboration with developers. It helps me examine how implementation work could change, but it does not measure final code quality or prove productivity gains.

### S3 - GDC 2026 State of the Game Industry Reveals Impact of Layoffs, Generative AI, and More

Beth Elderkin. 2026. New independent research. Accessed November 11, 2026.

https://gdconf.com/article/gdc-2026-state-of-the-game-industry-reveals-impact-of-layoffs-generative-ai-and-more/

The official survey summary describes AI use, employment pressures, and contrasting attitudes among game-industry professionals. I use it to challenge the assumption that easier production automatically means easier entry into games, while recognizing that respondents do not represent every studio.

### S4 - Applied AI Demo Engineer

Anthropic. n.d.. New role-specific source. Accessed November 11, 2026.

https://job-boards.greenhouse.io/anthropic/jobs/5455961008

This employer listing combines LLM applications, retrieval, integrations, reliable prototypes, and technical communication. I use its duties as one concrete role comparison rather than an entry-level promise or a universal definition of AI engineering.

Zotero status: Pending authenticated save to group 6416274 and verification of item links. The browser is signed out and reports a security-check error. The accompanying RIS file contains all four research records and two-sentence annotations. It is an import aid, not proof that the records are already in Zotero. Check for duplicates before importing.

## 7. Project evidence

### E1 - Tesseract MCP contribution

**State:** Merged contribution

**What it demonstrates:** Concurrent note creation and configurable agent identity

**Evidence limits:** PR #21 by Rayhanson-Git merged November 4, 2026. Source and tests inspected. No new test run in this review.

[Project](https://github.com/DeepExtrema/tesseract/pull/21) · [Source](https://github.com/DeepExtrema/tesseract)

**Relevant skills:** AI integration, collaboration, debugging

### E2 - Tesseract macOS/Linux proposal

**State:** Contribution proposed

**What it demonstrates:** Portability, scheduling, and workflow guidance

**Evidence limits:** PR #10 itself is not marked merged. Similar upstream changes must not be attributed solely from this PR.

[Project](https://github.com/DeepExtrema/tesseract/pull/10) · [Source](https://github.com/Rayhanson-Git/tesseract-mcp-MacOS)

**Relevant skills:** Workflow, research, integration

### E3 - JimBro

**State:** Published

**What it demonstrates:** Integrated scheduling, workout logging, local storage, backups, and animated character

**Evidence limits:** Core source and live entry screen inspected. November 10 QA record reports 49 domain checks and deployed Chromium journeys. Those checks were not rerun in this review.

[Project](https://rayhanson.tech/projects/jimbro/) · [Source](https://github.com/Rayhanson-Git/Harvey-Chowdhury-MTEC3200/tree/release/jimbro-web)

**Relevant skills:** Product development, delivery, documentation

### E4 - GymLog

**State:** Published prototype

**What it demonstrates:** Post-set logging, editable values, confirmation, and correction paths

**Evidence limits:** Sample data lasts for the page session. Portfolio describes participant testing as a next validation step.

[Project](https://rayhanson.tech/projects/gymlog/) · [Source](https://github.com/Rayhanson-Git/Rayhanson-Git.github.io/blob/main/projects/gymlog/prototype.html)

**Relevant skills:** UX, prototyping, iteration

### E5 - LeaveBy

**State:** Published

**What it demonstrates:** Backward scheduling with input validation and date calculations

**Evidence limits:** Source and live form inspected. Uses user estimates rather than live transit information.

[Project](https://rayhanson.tech/projects/leaveby/) · [Source](https://github.com/Rayhanson-Git/Harvey-Chowdhury-MTEC3200)

**Relevant skills:** Problem definition, application logic

### E6 - Wasp Dodge+

**State:** Published browser game

**What it demonstrates:** Movement, collision detection, four lives, cooldown, scoring, and restart logic

**Evidence limits:** Source and live game menu inspected. Full playthrough and player testing were not performed in this review.

[Project](https://rayhanson.tech/projects/wasp-dodge/) · [Source](https://github.com/Rayhanson-Git/MTEC1201_Harvey/tree/main/Assignments/Midterm_Final_HarveyC)

**Relevant skills:** Game development, interaction

### E7 - Gesture Particles

**State:** Published

**What it demonstrates:** MediaPipe landmarks mapped to Three.js particle behavior

**Evidence limits:** Source and live interface inspected. Camera-based behavior was not tested in this review. Integrates an existing model.

[Project](https://rayhanson.tech/projects/gesture-particles/) · [Source](https://github.com/Rayhanson-Git/Gesture-Particles)

**Relevant skills:** Computer vision integration, creative coding

### E8 - Virtual Theremin

**State:** Published

**What it demonstrates:** Hand tracking mapped to pitch, volume, bass, and drum triggers

**Evidence limits:** MediaPipe and Tone.js integration inspected. Live start screen opened. Camera and audio performance were not tested.

[Project](https://rayhanson.tech/projects/virtual-theremin/) · [Source](https://github.com/Rayhanson-Git/Virtual-Theremin)

**Relevant skills:** Interactive audio, integration

### E9 - Neon Orbit Arcade

**State:** Published

**What it demonstrates:** Particles, portals, forces, and Calm/Chaos modes

**Evidence limits:** Source and rendered live canvas inspected.

[Project](https://rayhanson.tech/projects/neon-orbit/) · [Source](https://github.com/Rayhanson-Git/neon-orbit-final)

**Relevant skills:** Simulation, creative coding

### E10 - Orbit Playground

**State:** Published

**What it demonstrates:** Orbiters, changing palettes, adjustable speed, and input response

**Evidence limits:** Source and rendered live canvas inspected.

[Project](https://rayhanson.tech/projects/orbit-playground/) · [Source](https://github.com/Rayhanson-Git/orbit_playground)

**Relevant skills:** Generative visuals, interaction

### E11 - Studio Apartment Evening

**State:** Published audio

**What it demonstrates:** Audio storytelling and multitrack editing in Adobe Audition

**Evidence limits:** Published 186-second audio loaded and session screenshot inspected. The page credits 11 self-recorded sounds. No listening assessment was performed in this review.

[Project](https://rayhanson.tech/projects/studio-apartment-evening/) · [Source](https://github.com/Rayhanson-Git/Rayhanson-Git.github.io/tree/main/projects/studio-apartment-evening)

**Relevant skills:** Creative production, storytelling

### E12 - Portfolio website

**State:** Published

**What it demonstrates:** Case studies, visual identity, responsive navigation, and project presentation

**Evidence limits:** Nine case studies and core portfolio interaction code inspected.

[Project](https://rayhanson.tech/) · [Source](https://github.com/Rayhanson-Git/Rayhanson-Git.github.io)

**Relevant skills:** Communication, visual design, delivery

### E13 - Devil May Cry music video

**State:** Completed, student-reported

**What it demonstrates:** Video editing and game-related storytelling

**Evidence limits:** Not yet published on the portfolio. Media and editing timeline not inspected.


**Relevant skills:** Potential creative-production evidence

### E14 - Rust retrieval system

**State:** Planned

**What it demonstrates:** Time-aware memory, conflict resolution, and retrieval evaluation

**Evidence limits:** No working Rust implementation established in this conversation.


**Relevant skills:** Growth project, not current competency evidence

## Review before submission

- Confirm the provisional current scores and proposed May 2028 targets.
- Complete the shared Zotero save and add verified item links.
- Confirm any revised Brightspace deadline and upload requirements.
- Retain earlier 1c ratings as a historical assessment. This chart uses different axes and does not establish measured improvement since 1c.
- Keep the unpublished music video and planned Rust system distinct from inspected work.
- See the separate [collaboration record](../../../reflections/ai-collaboration-log.md).
