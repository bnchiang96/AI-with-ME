# AI with ME - Operating Framework

AI with ME - Operating Framework defines an instruction-led approach to AI work across Projects. It combines reusable Plugin instructions, authoritative Google governance resources, and optional Database services. The design preserves user decisions, Agent responsibilities, approved work boundaries, and durable records across conversations and execution environments.

## 1. Development status and navigation

This repository is the authoritative development and distribution source for the Framework's Plugin and reusable operating resources.

| Location | Purpose | Status |
| --- | --- | --- |
| [Requirements V1](requirements/requirements.md) | Consolidated requirements for Framework development. | Available |
| `plugin/` | Agent Instructions, initiation guidance, Agent Lifecycles, reusable Work Lifecycles, and the installable Plugin. | Planned |
| `documentation/` | Detailed concepts, operating guidance, environment expectations, and reference information. | Planned |

The current deliverable is the repository foundation and Requirements V1. An installable Plugin and installation instructions remain future deliverables.

## 2. Operating concept

1. **Shared instructions.** The intended installed Plugin supplies reusable instructions and resources for normal Agent operation without routine GitHub reads.
2. **Current governance.** Google System Context identifies Projects and registered Agent Identities. Each Identity specifies its owning Project, Role, Scope, and Responsibility. The user selects the Project and Agent Identity for the conversation.
3. **Governed work.** Meeting Agents organize user decisions and authoritative Minutes. Execution Agents implement approved work through Scope Confirmation, a saved Execution Plan, separate execution approval, and verification of actual Deliverables.
4. **Project configuration.** Project Rules select applicable Work Lifecycles and define Project-specific outcomes, resource purposes, destinations, and responsibilities. Agent Lifecycles govern Agent work, while Work Lifecycles guide subject-matter outputs.

The [requirements](requirements/requirements.md) define initiation, role boundaries, approvals, records, and quality verification in detail.

## 3. Environments and dependencies

The design supports authorized execution through ChatGPT, Local environments, and future independent machines. Each participating environment must have an appropriate Google connector and granted access.

1. **Required: Google Drive / Docs.** Google Drive / Docs holds authoritative System and Project governance, formal Meeting Minutes, and required Working and Job Records. Local execution uses gog/gogcli as the selected Google connector. Other AI environments may use suitable connectors.
2. **Optional: Database.** Database services may support indexes, search, Agent Messaging, and handoff. Without Database services, Agents omit unavailable operations and provide copy-ready manual handoff information when appropriate.

Executing Agents must return required records, results, evidence, and Deliverable references to the owning Google-authoritative System or Project. They must verify those updates before claiming completion.

## 4. Installation and updates

The intended distribution lets users create, manually install, and manually update their own Private Plugin from this repository.

When the Plugin becomes available, the intended installation flow is:

1. Provide this repository's URL to an AI.
2. The AI reads this README and locates the Plugin and applicable installation guidance in `plugin/`.
3. The AI assesses its environment and dependencies, then assists installation using available tools and granted permissions.

If a required capability, connector, or permission is unavailable, the AI should explain the limitation. It should discuss the next authorized step with the user.

GitHub supplies source for intentional updates. Future Plugin installation and update guidance will be discoverable from this README as those deliverables become available.

## 5. License

This repository uses the [MIT License](LICENSE).
