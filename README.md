# AI with ME - Operating Framework

AI with ME - Operating Framework is a target design for an instruction-led AI system spanning a Plugin, Google governance resources, and optional Database services. It aims to support portable, reusable Agent work while preserving user approvals, clear responsibility, and authoritative records.

## 1. Read the requirements

This repository consolidates the framework's development requirements. The descriptions below express the target design, rather than verified installed capabilities.

Read [Development Requirements](docs/requirements.md) for the complete requirements, source references, lifecycle details, and unresolved design matters. Packaging, installation, compatibility, and release methods remain development decisions.

## 2. Understand the system

The framework has three main components:

1. **Plugin.** GitHub is the single authoritative source for the Plugin package, Agent Instructions, reusable Frameworks, and shared operating requirements. The intended installed Plugin supplies common instructions and drives Conversation Initiation without routine GitHub reads.
2. **Google governance resources.** Google Drive / Docs is mandatory for authoritative System and Project governance, formal Meeting Minutes, and required Working / Job Records. One designated Google System Root contains the central System resources and separate Project folders.
3. **Optional Database.** A Database may support indexes, Agent Messaging, handoff, and later-approved services. Without it, Agents omit unavailable Database-dependent actions and provide copy-ready manual handoff information when appropriate.

The design aims to reduce unnecessary external reads and repeated instruction loading. Agents must still obtain current dynamic information when their decisions require it.

## 3. Keep resource ownership clear

| Resource | Purpose in the target design |
| --- | --- |
| System Context | Maintains the central Project Directory, registered Agent Identities, configuration, and current System governance relationships. |
| System Rules | Define shared operating conventions. Google System Rules govern Google resources. Local System Rules govern local work and required Google updates. |
| Project Context | Maintains current Project facts and pending matters. |
| Project Rules | Define Project-specific requirements and subject-matter business lifecycles. |
| Project Commands | Customize required Agent actions and outputs when selected by the Agent Lifecycle. |

Conversation Initiation reads System Context to resolve the Project and its registered Agent Identity, then selectively loads applicable Project information. Project discovery accepts a supplied Project Folder or a Project identifier/name resolved through the central Directory. Discovery operates independently of the optional Database.

Each Project registers distinct Agent Identities with an owning Project, Responsibility, and Scope. Separate identities may use the same packaged Role Instruction while retaining separate messages and authority boundaries.

System-level Project Management may execute authorized governance changes across Projects under its own Job Protocol and approval gates. Each Project's Meeting Agent or appropriately assigned Project-local Execution Agent maintains its Project Context.

## 4. Follow the Agent's lifecycle

The target design preserves two principal lifecycle families:

1. **Meeting Agent Lifecycle.** The Agent prepares an Agenda for user confirmation, records accepted outcomes, completes authoritative Minutes, and performs authorized communication after closure. Unresolved matters require the user's disposition during closing.
2. **Execution Parent Lifecycle.** The Agent receives work, confirms Scope, prepares a saved Execution Plan, and obtains execution approval. It then executes, completes deliverable QA and records, and communicates results. The user confirms the selected Job Scope and separately approves the latest saved Plan through `PROCEED EXECUTION`.

Drafting, Project Management, Library Management, Database Engineer, and Central QA Agents inherit the Execution Parent Lifecycle. Each retains its own Responsibility, Scope, and Output definition. Lifecycle inheritance does not transfer another Agent's authority.

Project business lifecycles remain separate from Agent operating lifecycles. The Agent Lifecycle selects Project Commands at the relevant stage, and Agents reuse applicable instructions already available within the active Conversation.

## 5. Develop for reuse across environments

The target architecture supports authorized execution through ChatGPT, Local environments, and future independent machines. Every participating environment must have a compatible Google connector. Local execution uses [gog/gogcli](https://github.com/openclaw/gogcli) as its selected Google connector dependency.

Executing Agents must preserve approved Scope and Plan across environments. They must return required records, results, evidence, and Deliverable references to the owning Google-authoritative System / Project. They must verify those updates before claiming completion.

Agents assess missing dependencies in their current environment and discuss setup options and permissions with the user. Detailed installation and connector setup methods remain the executing Agent's responsibility within granted authority.

The intended distribution shares GitHub source so others may create, manually install, and manually update their own Private Plugin. Support for independent machines requires later implementation and verification.

Existing Projects Migration is a separate later workstream, planned after framework development.
