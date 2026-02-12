# WeThrum

### A community nervous system: collective intelligence for the neighborhoods that need it most.

---

**WeThrum** is a hyperlocal platform that turns a community into a living organism. Every member becomes a neuron. The system **senses** what's happening, **thinks** about what it means, and **acts** to keep people safe and connected.

This is not a social network. There are no feeds, no likes, no profiles. There is no engagement optimization. WeThrum exists for one purpose: **community survival and flourishing.**

<br>

## The Problem

Communities already have intelligence. A grandmother who knows every family on the block. A clinic worker who sees the patterns before anyone else. A shop owner who notices when things feel wrong.

But this intelligence is **scattered across hundreds of minds**, unconnected, uncoordinated, and lost every time someone moves away or passes on. When a crisis hits, the community's own knowledge can't move fast enough.

Meanwhile, the platforms that *do* connect people are built to extract attention, harvest data, and serve advertisers. For vulnerable communities, undocumented families, unhoused neighbors, people navigating systems designed to exclude them, these platforms aren't just unhelpful. They're dangerous.

<br>

## What WeThrum Does

WeThrum gives a community **its own collective brain.**

The system is built around three functions: the same way a biological nervous system works:

| | Function | What it means |
|---|---|---|
| **SENSES** | Ambient signal collection | Low-friction observations from community members flow in continuously |
| **THINKS** | Agent-powered synthesis | AI agents verify, cross-reference, and extract meaning from raw signals |
| **ACTS** | Coordinated response | The community responds together, automatically, intelligently |

<br>

## Ten Breakthrough Capabilities

These are the capabilities that make WeThrum fundamentally different from anything that exists today.

### 1. Threat Mesh
Real-time collective danger awareness. Three unconnected people signal the same thing within a timeframe, and only then does the network activate. No single point of failure. No false alarms.

### 2. Resource Pulse
A living map of what's available *right now*. Not a static database from six months ago. Which shelter has beds tonight? Where can you get a meal in the next hour? Updated continuously through human sensing.

### 3. Predictive Patterns
The system learns. Evictions spike on the first of the month. Enforcement increases after certain political events. Resource gaps are seasonal. WeThrum shifts from reactive to **anticipatory**, seeing what's coming before it arrives.

### 4. Trust Web
Anonymous identity through cryptographic vouching. No phone numbers. No government IDs. No data to subpoena. Your reliability is weighted by the depth of your trust chain, not by who you are.

### 5. Mutual Aid Orchestration
Continuous, silent matching of needs to offers. The system knows Maria needs formula and Mrs. Chen has extra. It connects them, without either having to broadcast their situation publicly.

### 6. Counter-Surveillance Intelligence
The community's own eyes, turned outward. Camera locations. Patrol patterns. Raid precursors. Crowdsourced operational security, intelligence analysis inverted to protect instead of pursue.

### 7. Narrative Sovereignty
The community writes its own story. Not journalists. Not politicians. Not algorithms. Multi-perspective, cryptographically timestamped, temporally coherent. The authoritative record belongs to the people who lived it.

### 8. Knowledge Mycelium
Community wisdom that never gets lost. How to navigate immigration court. How to negotiate with a landlord. How to appeal a benefits denial. Structured, searchable, and persistent, surviving every generational turnover.

### 9. Immune Response
When something critical happens, the community swarms. Intelligent dispatch that knows who can do what, assembles a coordinated response in minutes, assigns roles, opens communication channels, all without a central authority.

### 10. Intergenerational Bridge
Memory that outlives individuals. Decades of accumulated wisdom, accessible to newcomers on day one. "Here's what was tried in 2004. Here's why it failed. Here's who to talk to."

<br>

## Architecture

```
                    Community Members (Neurons)
                            │
                    ┌───────▼───────┐
                    │    SENSES     │  Low-friction signal ingestion
                    │  Observations │  Location-aware, anonymous
                    └───────┬───────┘
                            │
                    ┌───────▼───────┐
                    │    THINKS     │  Multi-agent AI orchestration
                    │  Verification │  Cross-reference, pattern match
                    │  Synthesis    │  Confidence scoring, prioritization
                    └───────┬───────┘
                            │
                    ┌───────▼───────┐
                    │     ACTS      │  Coordinated community response
                    │  Alerts       │  Resource matching, swarm dispatch
                    └───────────────┘
```

### Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | Python 3.11 / FastAPI, async SQLAlchemy, Alembic |
| **Frontend** | Next.js 16, TypeScript, Tailwind CSS, PWA |
| **Database** | PostgreSQL + PostGIS + pgvector |
| **Cache** | Redis |
| **Vector Search** | Qdrant (768-dim embeddings) |
| **Real-time** | NATS JetStream |
| **LLM Inference** | Qwen3 14B (signal synthesis), nomic-embed-text (embeddings) |
| **Agent Orchestration** | TypeScript multi-agent system with LLM routing |
| **Identity** | TrustGlyph radial-ring visual encoding, NFC/BLE transport |
| **Infrastructure** | Docker Compose, self-hostable |

<br>

## Current Status

WeThrum is in active development. The foundational infrastructure is built and operational:

**Completed:**
- Trust Web: anonymous cryptographic identity with vouching ceremonies
- TrustGlyph: visual identity encoding (radial-ring claycode, camera-scannable)
- NFC and BLE snap transport for in-person trust ceremonies
- Community creation, joining, and federation protocols
- Signal ingestion and multi-agent processing pipeline
- Resource Pulse: real-time OSM resource tracking with LLM validation
- Threat Mesh: multi-signal verification and alert propagation
- Push notification system with service worker
- PWA installation and onboarding flow

**In Progress:**
- Predictive Patterns: historical analysis for anticipatory intelligence
- Mutual Aid Orchestration: need-to-offer semantic matching
- Counter-Surveillance: crowdsourced surveillance mapping and safe routing
- Narrative Sovereignty: multi-perspective event documentation
- Knowledge Mycelium: structured community wisdom preservation
- Immune Response: swarm coordination for critical threats
- Intergenerational Bridge: persistent generational knowledge

<br>

## Design Principles

**Privacy is non-negotiable.** WeThrum serves people who can be harmed by their own data. No personally identifiable information is stored. Trust chains replace identity verification. The architecture is designed to resist subpoenas, warrants, and data extraction. If it can be weaponized against a community member, it doesn't ship.

**The community owns everything.** Open source. Self-hostable. No platform lock-in. Communities control their own thresholds, policies, and governance. Algorithms are transparent. Data never leaves the community's infrastructure.

**Intelligence requires trust, not identity.** Signal reliability is weighted by trust topology: the depth and breadth of cryptographic vouching chains: not by who someone claims to be.

<br>

## Contributing: Early Builder Access

WeThrum will be fully open source at launch under the **AGPL-3.0 license**. The codebase, documentation, and deployment guides will all be public.

During initial development, the repository is private. This is a deliberate decision, and it's worth explaining why.

### Why private during buildout?

**Quality over speed.** The communities this platform serves don't get a second chance if the first version leaks data, breaks trust ceremonies, or fails during a real crisis. The initial contributor group is kept small so that every architectural decision gets the scrutiny it deserves.

**Security through careful onboarding.** A platform designed to protect vulnerable people from surveillance cannot afford to have its security model probed by adversaries before it's hardened. Early contributors go through a vetting process, not because we're exclusive, but because the people who will depend on this system deserve that diligence.

**Intentional culture.** The first contributors shape the project's culture forever. We're building that foundation carefully, prioritizing people who understand that code serving vulnerable communities carries a different weight than code serving consumers.

### How to apply

If you're a developer who wants to contribute to the initial buildout, apply at:

**[https://wethrum.ai/builders](https://wethrum.ai/builders)**

We're looking for people with experience in:
- Cryptographic identity systems and zero-knowledge architectures
- Real-time distributed systems (NATS, event sourcing, CQRS)
- LLM application development and multi-agent orchestration
- Mobile-first PWA development
- Geospatial systems (PostGIS, OpenStreetMap)
- Security engineering and threat modeling
- Community-centered design and mutual aid networks

You don't need all of these. You need one of them and the conviction that technology should protect people, not extract from them.

### After launch

Once the platform reaches its initial security and stability milestones, the repository goes public and contributions follow a standard open source workflow. Until then, early builders get direct access to shape the architecture, influence the roadmap, and build something that matters.

<br>

## License

[AGPL-3.0](LICENSE): Because community infrastructure should stay community infrastructure.

<br>

## Inspirations

The vision draws from:

- **Daniel Suarez** (*Daemon / Freedom*), emergent collective intelligence through networked holons
- **Asimov** (*Foundation / Gaia*), every organism as a neuron in a planetary brain
- **Octavia Butler** (*Parable of the Sower*), community survival through shared awareness
- **Cory Doctorow** (*Walkaway*), post-institutional self-organizing communities
- **Indigenous oral networks**, distributed memory and knowledge sharing, long before technology

When we make architectural decisions, we ask one question: *Does this make the community more intelligent as a collective organism?*

---

<p align="center">
  <strong>WeThrum</strong> — Because a community that can think together can survive anything.
</p>
