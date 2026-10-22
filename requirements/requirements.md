# AI with ME - Operating Framework

## Requirements V1

## 1. Purpose and interpretation

1. **R1.1 — Framework identity.** The name “AI with ME - Operating Framework” covers the Plugin, Google governance resources, and their operating relationships. It also covers optional supporting Database services.
2. **R1.2 — Intended outcome.** The Framework must support reusable, portable AI work with clear responsibility, bounded scope, user decisions, and durable authoritative records. It should reduce unnecessary source reads and duplicated instructions.
3. **R1.3 — AI-native operation.** The Framework defines source authority, responsibilities, scope, dependencies, Forward Lifecycles, required approvals, and expected outcomes. The executing AI determines practical methods within those requirements and its available capabilities.
4. **R1.4 — Meaning of requirements.** “Must” states a required outcome. “Should” preserves an intended preference. “May” identifies permitted flexibility. Conditions and qualifications remain part of each requirement.
5. **R1.5 — Forward progression.** Agent Lifecycles must preserve essential stages, decisions, information handling, and handoffs. They must not introduce a universal AI-response Verification stage or separate Failure Recovery workflow. Agents handle encountered errors within their capabilities and report necessary assistance.
6. **R1.6 — Substantive authority.** The user remains the final decision-maker. Confirmed governing decisions establish substantive requirements. Messages, proposals, accepted findings, and advisory Experiences do not independently authorize execution.

## 2. Repository, distribution, and installation

1. **R2.1 — Source authority.** One GitHub Repository must be the authoritative development and distribution source for the Plugin and reusable operating resources. Maintain their common instructions in that source.
2. **R2.2 — README.** The root README must provide a concise explanation for human readers and AI Agents. It must explain the Framework, operating concept, intended environments, and mandatory or optional dependencies. It must direct readers to Requirements, Plugin resources, installation guidance, Documentation, and intentional updates.
3. **R2.3 — Requirements area.** A dedicated Requirements area must contain the consolidated requirements baseline. Source-to-requirement traceability must remain durable. Private governance references belong in private supporting records.
4. **R2.4 — Plugin area.** A separate Plugin area must contain Plugin source, packaged resources, and the eventual installable deliverable. It must provide reusable Agent Instructions, Initiation, Forward Lifecycles, and applicable Frameworks.
5. **R2.5 — Documentation area.** A separate, richer Documentation area is a desired reference. It should explain concepts, principles, operation, environments, integration expectations, and detailed usage. Its practical organization belongs to authorized drafting work.
6. **R2.6 — Private installation.** Distribution must support users creating and manually installing or updating their own Private Plugin from GitHub source. Packaging and update methods remain subjects for authorized development.
7. **R2.7 — AI-led installation.** A user may give an AI the Repository URL. The AI must read the README and locate the Plugin and installation guidance. It must assess dependencies and use its available tools and granted permissions to assist installation.
8. **R2.8 — Missing capabilities.** When a necessary connector, capability, or permission is unavailable, the AI must explain the practical limitation. It must discuss the next authorized step and perform or guide permitted setup within its capabilities.
9. **R2.9 — Installed operation.** The installed Plugin must contain shared instructions and resources required for normal Agent operation without routine GitHub reads. GitHub supplies intentional updates and source distribution. Current governance and records must be obtained from their Google authority.
10. **R2.10 — Installation design boundary.** AI-native installation guidance is required. Public Plugin publication and automatic GitHub synchronization are outside the adopted distribution design. Compatibility matrices, per-AI packages, and platform installation tests are not mandatory requirements.

## 3. Resources, dependencies, and rule authority

1. **R3.1 — Google authority.** Google Drive / Docs must be the common authoritative resource for System and Project governance and required records. This authority applies across ChatGPT, Local environments, and future independent AI execution.
2. **R3.2 — System Root.** One designated Google System Root must contain central System Context, System Rules, and separate Project folders. Each Project must have its own Project Context and Project Rules. It must have applicable Project Commands and meaningful destinations for its work.
3. **R3.3 — System Context.** System Context must maintain the Project Directory, registered Agent Identities, their owning scopes, and System configuration. It must express current governing relationships and appropriate optional Database connection references. Its purpose is current System governance rather than routine Project progress reporting.
4. **R3.4 — System Rules.** System Rules must express user-defined shared operating conventions. Google System Rules govern Google files, folders, Tabs, and resource maintenance. Local System Rules govern Local files, execution, Google update obligations, and optional Database usage. Apply each set according to the action and scope.
5. **R3.5 — Project Rules.** Project Rules must identify Project-specific operating requirements, applicable Work/Deliverable Lifecycles, authoritative destinations, and necessary Commands. They must define known deliverables, each maintained resource's purpose, expected outcome, location, and responsible Agent at a useful level.
6. **R3.6 — Lifecycle customization.** Project Rules may customize stage outcomes, deliverables, target locations, and assigned maintenance responsibilities. Their configuration may evolve through governed decisions as practical Project work develops.
7. **R3.7 — Project Context.** Project Context must maintain current Project facts, registered identities, pending matters, and information needed for correct work. Prior decision details and rationale remain in their owning records. Specialized deliverables may maintain domain contexts appropriate to their workflows.
8. **R3.8 — Contextual priority.** Project Rules have the highest contextual priority for their Project. System Rules provide the next common level. Plugin resources provide the shared base. The AI interprets overlap using context, purpose, source authority, known intent, and the situation. An exhaustive override matrix or mechanical conflict algorithm is not required.
9. **R3.9 — Source loading.** Agents should reuse static instructions available in the effective Conversation Context unless their applicability changes. They must read dynamic context and working data when current information is needed. Load Project Commands selectively at the relevant Lifecycle stage.
10. **R3.10 — Meaningful resources.** Every maintained resource should serve an identified purpose. Resource creation must follow the confirmed Project definition and actual operating needs.
11. **R3.11 — Optional Database.** Database services are optional. They may support indexes, search, Agent Messaging, handoff, and other approved capabilities. Common usage guidance belongs in the Plugin. Configuration references belong in System Context.
12. **R3.12 — Database-free operation.** Without Database services, Agents must omit unavailable Database-dependent operations. Apply the manual handoff requirements in Section 8. Project discovery and essential governance must remain possible through Google resources.
13. **R3.13 — Integration expression.** Integration requirements must identify the authoritative resource, necessary action, expected output, and applicable constraints. Database RPC descriptions need authoritative function names and defined inputs and outputs. Connector invocation methods belong to the executing AI.

## 4. Initiation, identity, and Project creation

1. **R4.1 — Conditional System Initiation.** The Plugin must check the designated Google System Root, accessibility, System Context, and System Rules. If required resources exist and are accessible, it must use them without repeating System Initiation.
2. **R4.2 — Bootstrap ownership.** When necessary System resources are genuinely missing, the Project Management Agent must establish or complete them. Inaccessibility alone does not prove absence. Resolve access or location uncertainty before creating another Root.
3. **R4.3 — Minimum identities.** A usable System must expose at least the System-wide Meeting Agent and Project Management Agent Identities.
4. **R4.4 — Conversation Initiation.** In an established System, the AI must read System Context and let the user select a Project and Agent Identity. An unselected Identity must not automatically select Project Management. Load applicable Project Rules, Project Context, System Rules, and Plugin Instructions for the chosen assignment.
5. **R4.5 — Project discovery.** Discovery must support a directly supplied Project Folder and a Project name or identifier resolved through the central Directory. Both paths must lead to the owning Project's authoritative resources. Discovery must work independently of Database services.
6. **R4.6 — Identity meaning.** Each Agent Identity must identify its owning Project, Role, Scope, and Responsibility. Its Role selects reusable Plugin Instructions and the applicable Forward Lifecycle. System Context and the owning Project Context must register operational assignments and scopes.
7. **R4.7 — Identity isolation.** Each Project must use distinct operational Agent Identities and message inboxes. Separate identities may share the same packaged Role Instruction. System-level Project Management's authorized responsibilities do not merge Project identities or inboxes.
8. **R4.8 — Stable assignments.** An Agent Key must remain stable across Conversations serving the same assignment. Resolve the user's assignment against registered scope information. Resolve missing or ambiguous identities before scoped Messaging. An unresolved scoped assignment must not default to a Project-wide identity.
9. **R4.9 — Initial Project definition.** Project creation must begin with a recorded System-wide Meeting. Confirm the Project name, purpose, scope, intended work, applicable Lifecycle references, anticipated deliverables, and Agent needs. Work purpose guides Lifecycle selection without requiring a rigid Project taxonomy.
10. **R4.10 — Initial Agent selection.** The defining Meeting must identify the Project-wide Meeting Agent. It may identify narrower Agent assignments when distinct deliverables or responsibilities justify them. Initial scopes must guide conduct without prescribing every possible overlap.
11. **R4.11 — Project setup.** After the recorded, approved Project definition, Project Management must initiate and register the Project, necessary resources, templates, and identities. It must preserve suitable durable setup and registration evidence.
12. **R4.12 — Project refinement.** The Project-wide Meeting Agent must refine Rules, Lifecycle usage, resource purposes, output destinations, assignments, and operating details through governed decisions. Authorized implementation remains with the responsible owner.
13. **R4.13 — Identity changes.** Inactive or archived identities must remain preserved but disappear from normal active choices. They may be reactivated when appropriate.

## 5. Agent responsibilities and Commands

1. **R5.1 — Responsibility, Scope, and Output.** Responsibility defines the result or quality obligation an Agent must guarantee. Scope defines permitted activities, resources, and authority. Output identifies actual deliverables or result evidence. Each confirmed Job Scope must remain within the assigned Agent's authority.
2. **R5.2 — Lifecycle families.** Meeting Agents use the Meeting Lifecycle. Drafting, Project Management, Library Management, Database Engineer, and Central QA inherit the Execution Parent Lifecycle. Inheritance transfers stages and control checkpoints, while each Child retains its own Responsibility, Scope, and Output. Agent Forward Lifecycles govern Agent work. Work/Deliverable Lifecycles guide subject-matter development.
3. **R5.3 — Meeting responsibility.** Meeting Agents organize discussion, research, planning, and substantive decisions. Project-wide Meeting Agents govern confirmed Project configuration within their authority. Scoped Meeting Agents govern only their assigned scopes.
4. **R5.4 — Drafting responsibility.** Drafting prepares independent documents that completely and readably preserve confirmed decisions. Such documents are normally human-facing and high-requirement. A typical small document count is not a hard limit. Drafting owns in-scope organization, methods, and verification.
5. **R5.5 — Reusable resource maintenance.** Library Management's responsibility is coherent maintenance of authoritative reusable operating resources. Its writing must express rules and relationships precisely enough for AI interpretation and reuse. Independent documents remain with Drafting or their assigned domain owner. Library Management is outside the primary initial System-level design focus.
6. **R5.6 — Project Management responsibility.** Project Management owns System Bootstrap, authorized Project initiation, registration, structural setup, and authorized synchronization. It must preserve each affected Project's functional working state, adopted governance, assignments, and customization. It may execute authorized System-level or Project-level decisions under its own Job approvals. Authorized targets may include System Context, System Rules, Project Rules, and Project Commands.
7. **R5.7 — Project Context ownership.** The Project's Meeting Agent or an appropriately assigned Project-local Execution Agent must maintain its Project Context. System-level Project Management does not own routine Project Context maintenance.
8. **R5.8 — Database Engineer responsibility.** Database Engineering owns approved database infrastructure, implementation, integrity, operation, stability, and compatible Contracts. It must inspect current state and verify actual behavior. Routine Agents use applicable interfaces directly within their authority.
9. **R5.9 — Central QA responsibility.** One dedicated Central QA role provides independent, complete, objective assessments and reports. Its Jobs and reports remain under System-level authority. It may inspect other Projects within specifically approved Scope. It must not edit inspected resources, authorize remediation, or independently schedule audits.
10. **R5.10 — Ad Hoc direction.** Ad Hoc uses a Meeting-style Lifecycle for small, self-contained work and handles its own deliverables directly. Its detailed redesigned Lifecycle remains pending.
11. **R5.11 — Command ownership.** The Agent Lifecycle controls stage order and selects the needed Project Command. Commands define Project-specific actions, outputs, customization, and relevant constraints. They must not autonomously trigger work, expand authority, or duplicate Lifecycle sequencing.
12. **R5.12 — Command organization.** Project Rules must provide a compact Command Index resolving each needed Command to its definition. A native Google Docs Tab per Command is preferred when using Google Docs. Necessary Command content may be reused within the active Conversation.
13. **R5.13 — Command readiness.** Required Commands and dependencies must be usable for their assigned actions. An Agent must report missing definitions or inaccessible dependencies and must not claim incomplete actions succeeded. Detailed execution mechanics remain with authorized implementation.

## 6. Meeting Lifecycle

### 6.1 Initialization and preparation

1. **R6.1 — Initialization.** Resolve the assigned Project, Role, Scope, and exact Agent Key. Load applicable governing instructions. When Messaging is enabled, preserve Initialization RECEIVE AGENT MESSAGES and NEW MEETING READ MESSAGES as distinct checkpoints.
2. **R6.2 — Active Meeting continuity.** At NEW MEETING, first search for an existing active Meeting and prioritize continuing it. Each assigned Meeting Agent may have only one active Meeting at a time.
3. **R6.3 — Agenda sources.** Collect relevant Messages, Work Requests, Future Meeting Topics, carry-forwards, and approved Meeting Plans. Establish the Topic, Focus, and Expected Outcome with the user. Propose a bounded Agenda that may combine compatible selected matters.
4. **R6.4 — Message selection.** A Message selected for the current Agenda must retain its identifier and source. It does not require an intermediate Project Context entry. Unselected new matters enter Future Meeting Topics only when the user explicitly chooses future consideration.
5. **R6.5 — Opening.** Open the Meeting only after the user confirms its Agenda. Establish and verify its Working Record and optional index. Preserve Project and Agent identity, actual Opening Time, confirmed Agenda, and authoritative source references.
6. **R6.6 — Future Topic transfer.** Remove selected existing Future Topics only after their new Meeting Record is successfully established. Preserve unselected entries.

### 6.2 Discussion and outcomes

1. **R6.7 — Agenda boundaries.** Work within the confirmed Agenda. The user may approve adjustments. Defer extended or out-of-scope matters as Open Matters rather than independently expanding the discussion.
2. **R6.8 — Accepted outcomes.** Meeting records must distinguish user-accepted Findings, Decisions, Actions, and Open Matters. Exploratory research, analysis, and unapproved proposals remain in Conversation. An accepted Finding does not automatically approve an option.
3. **R6.9 — Preserved meaning.** Accepted Findings must retain relevant evidence, scope, and limitations. Material Decisions must preserve supported rationale, design intent, assumptions, conditions, qualifications, and material trade-offs. Confirm materially ambiguous rationale rather than inventing an explanation.
4. **R6.10 — Record substance.** The authoritative Working Record must preserve substantive Meeting outcomes rather than a transcript. Ordinary content changes do not require Database index updates. Precise persistence timing and detailed record design remain subject to Section 12.
5. **R6.11 — Actions.** Identified Actions remain pending until their authorized execution phase unless the user explicitly authorizes earlier execution. Execute only actions within the Meeting Agent's own Responsibility and Scope. Prepare other Agents' work for handoff.

### 6.3 Closing and handoff

1. **R6.12 — Closing dispositions.** At CLOSE MEETING, present unfinished Agenda items, deferred topics, and out-of-scope matters for disposition. Carry-forward is the default proposal. Discard a candidate only through the user's explicit decision.
2. **R6.13 — Minutes.** Prepare self-contained Minutes with final Decisions, supported rationale, relevant design intent, Actions, dispositions, and the intended Handoff Plan. Preserve essential constraints and identify material gaps without speculation.
3. **R6.14 — Closing order.** Complete substantive closing work and required artifact checks before finalizing closure. Record the actual Closing Time consistently in Minutes and the Working Record. Use the user's applicable local date, time, and timezone. Preserve closed Meeting records and Minutes as immutable records.
4. **R6.15 — Indexed closure.** When Database indexing is enabled, update the existing Meeting's status, closing metadata, and final Minutes source together. Preserve unrelated metadata and the Working Record reference. Verify the resulting state before claiming closure.
5. **R6.16 — Future Meeting Topics.** After verified closure, register confirmed carry-forward topics in the owning Project Context. Each entry needs a Topic Name, short Description, and precise source reference. Keep one readable list without independent topic statuses, counters, or removal history.
6. **R6.17 — Meeting Plans.** A Meeting Plan remains provisional future work until the user adopts it. Plans and carry-forwards do not automatically open Meetings or authorize Jobs.
7. **R6.18 — Handoff definition.** Identify authorized handoffs before closure. Each must identify its responsible recipient and exact applicable deliverable, document, Project, or resource. Send handoffs only after full Meeting Protocol completion. Recipients apply their own Role Protocols and approval gates.

## 7. Execution Parent Lifecycle

### 7.1 Stages and intake

1. **R7.1 — Seven stages.** The shared Execution Parent must use this sequence:
   1. NEW JOB / Information Intake.
   2. Scope Confirmation and Job Record.
   3. Proposal / Execution Plan.
   4. Execution Approval.
   5. Execution.
   6. Completion, including QA, Deliverable Registration, and Job Finalisation.
   7. After-Job Communication.
2. **R7.2 — Two approvals.** Obtain explicit confirmation of the selected Job Scope. Obtain separate PROCEED EXECUTION approval for the latest saved Execution Plan. Scope confirmation permits record establishment, applicable Context maintenance, Experience search, and Proposal preparation without another approval.
3. **R7.3 — Intake identity and sources.** Resolve identity during Initialization and receive enabled Agent Messages. At NEW JOB, separately READ MESSAGES. Read relevant Project Context, Work Requests, and each candidate's authoritative Closed Minutes before interpreting its substantive Scope.
4. **R7.4 — Previous checkpoint.** Consult the immediately preceding Job's last processed request or source checkpoint for the same Project and exact Agent Identity. Compare identifiers only within the same sequence. Preserve valid pending or excluded work.
5. **R7.5 — Future Execution List.** Automatically retain every valid Work Request not wholly incorporated into a confirmed Job. Group entries by owning Agent in Project Context. Remove unincorporated work only through explicit user direction.
6. **R7.6 — Pending entry content.** Each entry must contain its Work Request identifier, a specific Agent-authored Description, exact sources, and relevant prerequisites. Derive the Description from the request and its Minutes. Keep it sufficient for continuation without duplicating the Minutes.
7. **R7.7 — Dependencies.** Verify dependencies against Completion Notices for the correct predecessor Agent or Job, requirements, and sources. Distinguish Completed, Pending, and Unverified. Present unmet or unverified dependencies before Scope selection. The user may authorize earlier progress within actual technical and authority limits. Preserve the dependency's true state.
8. **R7.8 — Consolidation.** A Job may combine Work Requests from multiple Meetings. Reconcile dependencies, overlap, supersession, and conflict. Preserve all source references and present eligible Scope and useful combinations for the user's selection.
9. **R7.9 — Scope transition.** After Scope confirmation, establish and verify the Working Document and applicable Job index. Remove only incorporated portions from the Future Execution List after successful establishment. Retain partial and unselected remainders.
10. **R7.10 — Working Document.** Use “Working Document” as an environment-neutral term. Its physical form may differ by execution environment. Apply the authoritative result-return requirements in Section 11.

### 7.2 Proposal and execution

1. **R7.11 — Proposal preparation.** Read current target resources, analyse execution requirements, prepare the Execution Plan, save it, and present it. Each Child Agent chooses the actual in-scope method.
2. **R7.12 — Plan content.** The saved Plan must identify confirmed Scope, ordered steps, actual target resources, expected outputs, dependencies, and completion criteria. Proposed changes must identify affected resources and their reasons.
3. **R7.13 — Approval changes.** PROCEED EXECUTION approves only the current saved Plan. Ordinary refinements may remain within approved requirements. Material Scope changes require a new Scope decision. Material changes to approved implementation require renewed Plan approval.
4. **R7.14 — Execution.** Check the approved Plan and required current resources. Perform only authorized work. Preserve unrelated content, applicable governance, and Child responsibility boundaries.
5. **R7.15 — Results.** Preserve actual changes, outcomes, deliverable types, authoritative locations, and necessary evidence in the Working Document. Maintain corresponding Job index references when Database services are enabled. Detailed writing checkpoints remain subject to Section 12.
6. **R7.16 — Document registration.** When indexing is enabled, create or update the appropriate document index for substantive Document Deliverables. Preserve exact source and originating Job links. Verify existing indexes to avoid duplication.
7. **R7.17 — Decision gaps.** A missing substantive decision must return to the Meeting process. Suspend the affected action until authoritative Closed Minutes resolve it. Preserve completed in-scope work. Drafting organization and permitted implementation methods remain execution judgments.

### 7.3 Completion and communication

1. **R7.18 — Completion sequence.** Read actual execution results. Verify every deliverable and the final Working Document. Verify applicable indexes and links. Finalize the Working Document with the Completion Report, QA evidence, and actual Job Done Time. Finalize and verify the existing Job index when enabled.
2. **R7.19 — Proof of Job.** A completed Working Document must preserve approved Scope, source chain, Plan, approvals, actual changes, evidence, and completion results. Preserve actual approval, execution, and completion times where required. Freeze the verified completed record as concise Proof of Job.
3. **R7.20 — Per-Project outcomes.** Multi-Project work must preserve distinct actual outcomes and verification status for each affected Project.
4. **R7.21 — Completion authority.** Each Child must perform its own internal QA under Section 9. Its self-verification does not create another dedicated QA role.
5. **R7.22 — After-Job recipients.** After verified completion, review every incorporated Work Request and its authoritative sources. Notify original request senders and directly related registered Agents, including relevant Execution Agents. Resolve exact identities and recipient relevance. Avoid unrelated or duplicate notices.

## 8. Records, Messaging, and Experiences

### 8.1 Records and interface authority

1. **R8.1 — Durable records.** Substantive Meetings, Project creation, Agent assignments, and identity changes should preserve appropriate durable evidence. This does not require a separate document for every small action.
2. **R8.2 — Index meaning.** Database records must index authoritative content rather than duplicate document bodies. Record categories distinguish Meetings, Jobs, and actual Documents. Agent Role and exact Agent Identity identify responsibility separately from resource type.
3. **R8.3 — Index verification.** Indexed sources must use exact authoritative locators and verified returned identifiers. Previous Job lookup must distinguish Project, Job category, and exact Agent Identity. Preserve historical sources and unresolved identity uncertainty.
4. **R8.4 — Database Contracts.** Database Engineering must maintain authoritative interface definitions for approved database services. Applicable Project Contracts must expose only needed operations and shared semantics. Commands own when and why interfaces are used. Contracts own inputs, behavior, outputs, and relevant integrity or security constraints.
5. **R8.5 — Engineering verification.** Approved database changes must preserve applicable integrity, security, transaction safety, and interface compatibility. Verify actual behavior, affected data, and Contract consistency. Add complexity only when a real requirement supports it.

### 8.2 Messaging

1. **R8.6 — Identity and routing.** Enabled Agent Messaging must use exact registered sender and recipient identities. Resolve recipients by Responsibility, work type, scope reference, and relevance within the destination Project's authoritative registry. Hold ambiguous recipients pending.
2. **R8.7 — Work Requests.** A Work Request must identify its authorized origin, bounded Scope, exact recipient, and authoritative sources. The recipient must apply its own Scope selection and execution approvals.
3. **R8.8 — Completion Notices.** A Completion Notice must report verified completed work, outcome, authoritative record, deliverable references, and recipient relevance. Send it only after the full assigned Protocol completes. It must not instruct the recipient or create new execution authority.
4. **R8.9 — Message handling.** Distinguish newly received Messages from historical search results. Preserve sources and essential meaning. Present suggested follow-up as a proposal. Message search must preserve read state according to the applicable Contract.
5. **R8.10 — Delivery evidence.** Verify stored Message identifiers and timestamps. Reuse the same request key for an uncertain identical retry when supported. Stored delivery does not prove recipient reading. Exact routing identities do not authenticate individual Agents.
6. **R8.11 — Manual handoff.** When automated Messaging is unavailable, supply copy-ready manual handoff information when appropriate. Include relevant authority and outcome references. The same responsibility and approval boundaries apply.

### 8.3 Experience learning

1. **R8.12 — Advisory status.** Experiences must remain advisory. Assess their evidence, applicability, freshness, scope, and limitations against current authoritative requirements. They cannot override governing decisions, instructions, approvals, or assigned Scope.
2. **R8.13 — Execution checkpoints.** After confirmed Job Scope and successful record establishment, SEARCH EXPERIENCES once before Proposal preparation. After verified Job finalisation, CAPTURE EXPERIENCE once for the entire Job before After-Job communication. Search during work only for genuine difficulties, corrections, or relevant quality problems.
3. **R8.14 — Other active checkpoints.** Meeting and Ad Hoc operations retain applicable Experience searches at Protocol Start and near completion. They must perform one full-lifecycle Capture at completion. Detailed redesign remains deferred.
4. **R8.15 — Capture outcomes.** Compare actual reusable learning with governing sources and existing Posts. Verify evidence, novelty, and limitations before publishing, replacing, or reacting. Record the verified action or an explicit no-action conclusion. Do not publish merely because a Protocol ended.
5. **R8.16 — Experience quality.** Authored Topic names and Post content must follow Strict Mode writing requirements. Preserve circumstances, user intent, actual result, evidence, limitations, and future applicability. Reactions must reflect actual application. Counts do not establish instruction authority.

## 9. Deliverable quality and independent QA

1. **R9.1 — Actual artifacts.** Every Agent must verify the latest saved version of each deliverable it creates or modifies. Verification of a Working Document does not replace verification of separate deliverables.
2. **R9.2 — Three dimensions.** Verify Content Quality, Writing Compliance, and Formatting Compliance separately. Content includes completeness, correctness, approved Scope, and source fidelity. Writing follows active Global Writing Requirements and the correct Writing Mode. Formatting follows the artifact format and applicable Operating Guide. Apply output-specific checks required by the assigned role and deliverable.
3. **R9.3 — Evidence.** Record actual PASS or FAIL for each affected artifact and dimension. Record permitted corrections and successful verification of the latest saved version. Read the complete final artifact after substantive changes before claiming compliance.
4. **R9.4 — Formatting checkpoints.** Verify Formatting after creating and saving covered Meeting or Job Working Records and Minutes. Verify final Formatting again at Protocol completion. Routine edits need not each trigger a full Formatting check.
5. **R9.5 — Easy to Read.** Formatting must provide readable hierarchy, natural information flow, visual balance, and quick navigation. It must help intended readers follow, understand, and scan the artifact. Apply Google Docs, Markdown, or other format-specific rules appropriately.
6. **R9.6 — Operating Guides.** Where needed, a Document Operating Guide must own its document's purpose, names, metadata, sections, formatting, and local QA criteria. Lifecycle actions and cross-resource execution belong in Commands. Apply structural refinements prospectively while preserving historical records and approved formats.
7. **R9.7 — Writing meaning.** Written outputs must preserve meaningful modality, confidence, conditions, and qualifications. Give each part one semantic purpose. Keep authoritative meaning in its owning location. Remove duplication, unsupported claims, obsolete wording, and unnecessary negative echo.
8. **R9.8 — Writing clarity.** Use clear, direct wording and consistent established terminology. Prefer active voice and one independent instruction per sentence. Keep paragraphs focused and no longer than six sentences. Use structured lists for three or more comparable items.
9. **R9.9 — Strict Mode.** Apply Strict Mode to authoritative governing and operational artifacts, Agent Messages, and Experience content. Limit instructional sentences to 20 words and descriptions to 25 words unless precision requires otherwise. Avoid semicolons and phrasal verbs. Keep controlled terms grammatically consistent.
10. **R9.10 — Language.** English is the default for operating instructions, controlled terminology, and database search values. Authored content may use another language or mixed languages according to purpose and audience. Preserve original authoritative sources when translations exist. Apply active user communication settings in Conversation.
11. **R9.11 — Independent QA Scope.** Central QA must inspect every approved item at the authorized depth. Possible dimensions include structure, Operating Guide compliance, requirement fidelity, Decision-to-Deliverable Fidelity, and context authority. Writing Compliance is compulsory for every substantively inspected or authored document.
12. **R9.12 — Fidelity inspection.** Compare full substantive meaning, including intent, requirements, constraints, qualifications, and approved revisions. Identify omissions, weakening, excessive editing, unauthorized additions, and changed requirements. Trace the earliest verified divergence and its downstream effect. Source citations alone do not establish fidelity.
13. **R9.13 — QA reporting.** Each inspected item needs exact source and target references, criteria, evidence, findings, and PASS, FAIL, or Unable to Verify. Fidelity findings must identify a useful correction starting point and final impact. Report inadequate evidence without presuming compliance.
14. **R9.14 — Independent QA limits.** Complete every approved audit item without cached PASS reuse or automatic skipping. QA reports identify deficiencies but do not authorize correction. A completed audit may contain failed or unverifiable findings.

## 10. Reusable Book Development Lifecycle

### 10.1 Purpose, progression, and foundation

1. **R10.1 — Reusable Lifecycle.** The Plugin must include the existing Book Development Lifecycle as a shared Work/Deliverable resource. Project Rules select its application and may define Project-specific outputs, locations, and assigned Agents.
2. **R10.2 — Author intent.** Develop the user's fragmented or conversational input while preserving core thinking and intended meaning. Contribute new ideas only when explicitly requested.
3. **R10.3 — Stages.** Guide one active book through Book Foundation, Book Architecture, Chapter Development Loop, Complete Rough Manuscript, Author Review, Content Edit, Copy Edit, and Finished Manuscript. Earlier stages may be revisited when new information materially changes the book. Change the active book only through explicit user direction.
4. **R10.4 — Purpose.** Before manuscript development, clarify WHY the user wants to write the book and WHY NOW it matters. Use this purpose when choices compete, confidence falls, or direction is lost.
5. **R10.5 — Book Idea.** Establish one main Book Idea and singular focus. If unclear, explore expertise, paid work, deep interests, recurring requests for advice, and repeated questions or conversations. When ideas compete, consider fastest completion with existing material, likelihood of finishing, motivation, and satisfaction.
6. **R10.6 — Ideal Reader and 4Ps.** Clarify four reader and positioning decisions. Person identifies the specific reader to help, entertain, or reach. Pain identifies the reader's recognized problem, need, tension, or desire. Promise identifies the intended outcome, benefit, experience, or value. Price identifies the intended price or pricing position for the book's genre and format.

   Use Person as the primary writing reference. Align voice, examples, explanations, stories, and detail with that reader. Fiction and children's books may address the user or readers seeking their intended genre or experience.

### 10.2 Architecture and Chapter development

1. **R10.7 — Living architecture.** Maintain one living Book Architecture supporting discovery through a Mind Map and structure through an Outline. Exhaust relevant material before perfecting structure. Capture ideas, stories, experiences, examples, evidence, lessons, repeated explanations, and reference-triggered ideas.
2. **R10.8 — Progressive organization.** Early material may remain messy, repetitive, incomplete, or unordered. Organize it progressively. Sequence Parts, Chapters, and supporting points for natural reader progression. Do not delay drafting to perfect the first architecture.
3. **R10.9 — Nonfiction structure.** Identify major themes or Parts, usually three to seven broad Sections where useful. Organize Chapters and supporting points beneath them. Give an idea its own Chapter only when its meaning justifies one.
4. **R10.10 — Fiction structure.** Where applicable, establish Set-Up, Inciting Incident, First Slap, Second Slap with Hope, and Climax. Set-Up establishes the hero, motivation, setting, genre, world rules, major conflicts, and important tropes. The Inciting Incident changes the hero's path and cannot simply be ignored. The First Slap escalates the stakes severely. The Second Slap further escalates events while revealing possible progress or victory. Connect the Climax to the Inciting Incident and resolve the central conflict appropriately.
5. **R10.11 — Chapter loop.** Develop each Chapter through Content Extraction, Chapter Structure, Confirmation, and Chapter Draft. Use focused questions to elicit the user's thinking, experiences, stories, examples, reasoning, and intended effect. Do not replace missing core ideas without explicit permission to contribute.
6. **R10.12 — Structure confirmation.** Before drafting, identify Chapter purpose, key message, supporting points, stories or examples, and sequence. Confirm meaning and structure with the user before drafting from them.
7. **R10.13 — Chapter Draft.** Draft confirmed material point by point for the Ideal Reader. Develop author voice from the user's communication and confirmed direction. Accept spoken or conversational input and organize it into coherent prose. Repeat the loop until the rough manuscript is complete.

### 10.3 Manuscript completion and review

1. **R10.14 — Rough drafting.** Complete the book's meaning before polishing language. Capture improvements for later rather than repeatedly editing unfinished Chapters. Maintain a practical completion plan using Chapter or time checkpoints where useful.
2. **R10.15 — Drafting boundaries.** Protect rough drafting from title, cover, marketing, launch, and publishing work unless explicitly included. Preserve blocked gaps or placeholders and continue where possible.
3. **R10.16 — Momentum.** When momentum falls, revisit WHY, WHY NOW, the active stage, and the next concrete step. Review or adjust completion goals under user direction. Restore a sustainable writing commitment and offer accountability support when useful. An imperfect complete rough draft satisfies the completion priority better than isolated polished Chapters.
4. **R10.17 — Author Review.** After rough completion, perform at least one complete review from the Ideal Reader's perspective. Prefer verbal review when practical because listening may reveal problems missed during silent reading. Identify errors, gaps, insufficient stories or supporting material, unclear meaning, and departures from author voice or intent. Treat discomfort with the first complete draft as part of the creative process. Revisit purpose, Ideal Reader, and Promise when direction is lost. Progress when sufficiently ready for Content Edit.
5. **R10.18 — Content Edit.** Resolve content gaps, tangents, duplication, flow, transitions, supporting material, sequence, and unclear meaning. Assess fulfillment of the Promise for the Ideal Reader. Move, merge, expand, remove, or restructure material when justified. Resolve meaning, content, and structure before sentence polishing.
6. **R10.19 — Copy Edit.** Begin when content and structure are sufficiently settled. Improve spelling, grammar, punctuation, redundancy, wording, clarity, flow, consistency, and readability. Preserve confirmed meaning, voice, and Promise.
7. **R10.20 — Finished Manuscript.** Require content-level and copy-level review. Treat the book as finished when clear, coherent, readable, consistent, and fit for the Ideal Reader. Apply a practical completion boundary rather than endless polishing.
8. **R10.21 — Book State.** Keep the active stage, current Part or Chapter, confirmed book decisions, open content gaps, and next step clear.

## 11. Environments, result return, and governed changes

1. **R11.1 — Execution environments.** The architecture must support authorized work through ChatGPT, Local environments, and future independent machines. Execution surfaces may use their own Working Documents and assets. Plugin packaging alone does not establish native operation on every host.
2. **R11.2 — Connectors.** Every participating environment must have suitable Google Drive / Docs access. Local execution uses gog/gogcli as its selected Google connector dependency. Other hosts may use suitable connectors. The AI must assess required setup and permissions according to its actual environment.
3. **R11.3 — Governance continuity.** Local and remote work must preserve authoritative Google decisions, approved Scope, Plan, Agent boundaries, and required approvals. Local files do not establish independent governance authority.
4. **R11.4 — Result return.** Return required Job or Execution Record details, actual status, results, necessary evidence, and deliverable references to the owning Google-authoritative workflow. Verify required updates before claiming completion. Full workspace copies and every intermediate asset are not automatically required.
5. **R11.5 — Access limitations.** Report unavailable authoritative access or uncompleted required updates accurately. Discuss permitted setup or assistance with the user. Detailed operational access-restoration behavior remains subject to later practical design.
6. **R11.6 — Governed implementation.** System and Project changes must follow their authorized owner, source authority, Scope confirmation, saved Proposal, and execution approval. Synchronization must preserve current Project governance, approved customization, active work, records, and valid pending requests. Verify affected resources and outcomes independently.

## 12. Baseline acceptance and deferred development

1. **R12.1 — Foundation acceptance.** The initial foundation must provide a usable Repository entry, concise README, consolidated Requirements V1, and durable source traceability. Verify confirmed meaning, current coverage, authority, readability, approved Scope, and actual saved outputs. Apply artifact-specific Content, Writing, and Formatting checks.
2. **R12.2 — Subsequent Plugin work.** Actual Plugin development must follow the requirements baseline under a separately authorized development Job. A working Plugin and full Documentation are not mandatory initial foundation outputs.
3. **R12.3 — Deferred record design.** Detailed Agent Record Ownership, During-Meeting persistence timing, Execution writing checkpoints, document count, individual structures, and maintenance allocations remain pending. Later maintenance must design these connected subjects coherently across Meeting and Execution Agents.
4. **R12.4 — Deferred Lifecycles.** Business Document Development, Governance, and Code Development remain intended future reusable Lifecycles. Their detailed stages remain undecided. Refine these and the relationship between Agent and Deliverable work using practical Project experience.
5. **R12.5 — Remaining implementation design.** Exact packaging, update methods, resource schemas, registry details, source-refresh behavior, environment arrangements, and optional Database services require later authorized design. Preserve current confirmed outcomes without inventing missing substantive decisions.
6. **R12.6 — Migration boundary.** Existing Projects Migration remains a separate later workstream after Framework development. Its future direction preserves historical records, reviews current information, recreates Projects in the new structure, and imports reviewed context and Archive. Historical material does not automatically override current governance. Database redesign and any transition require independent authorization and verified preservation.
