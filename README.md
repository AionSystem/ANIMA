# ANIMA — AI Native Intelligence & Memory Architecture

**Constitutional governance infrastructure for deployed AI personas.**
**Build AI companions with documented integrity. Ship personalities that hold.**

<!-- STATUS · VERSION · ARCHITECTURE -->
[![Status](https://img.shields.io/badge/STATUS-Active-2E7D32?style=flat-square)](https://github.com/AionSystem/ANIMA)
[![Version](https://img.shields.io/badge/version-v2.2--public-4ade80?style=flat-square)](#)
[![Commercial](https://img.shields.io/badge/Commercial-v4.4%20Available-orange?style=flat-square)](COMMERCIAL-LICENSE.md)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![ORCID — Sheldon K. Salmon](https://img.shields.io/badge/ORCID-0009--0005--8057--5115-a6ce39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0005-8057-5115)
[![DOI](https://img.shields.io/badge/DOI-Pending%20Registration-lightgrey?style=flat-square)](#)

<!-- CORE ARCHITECTURE -->
[![AION Stack](https://img.shields.io/badge/AION-Constitutional_Stack-1976D2?style=flat-square)](https://github.com/AionSystem/AION-BRAIN)
[![STP](https://img.shields.io/badge/STP-Integrated-2E7D32?style=flat-square&logo=git&logoColor=white)](https://github.com/AionSystem/SOVEREIGN-TRACE-PROTOCOL)
[![Eight Laws](https://img.shields.io/badge/Eight_Laws-Compliant-4527A0?style=flat-square)](https://github.com/AionSystem/AION-BRAIN)
[![FORGE](https://img.shields.io/badge/FORGE-v1.0%20Certified-F59E0B?style=flat-square)](https://github.com/AionSystem/AION-BRAIN)

<!-- TIER BADGES -->
[![Public Tier](https://img.shields.io/badge/Public-v2.2%20Core%20Template-4ade80?style=flat-square)](#public-tier-v22)
[![Commercial Tier](https://img.shields.io/badge/Commercial-v4.4%20Enterprise-orange?style=flat-square)](#commercial-tier-v44)
[![Feedback Welcome](https://img.shields.io/badge/Feedback-welcome-brightgreen)](https://github.com/AionSystem/ANIMA/issues/new/choose)

> **The soul is not a prompt. It is a governed architecture.**
> ANIMA — Constitutional AI Companion Infrastructure · AION Constitutional Stack

---

## Table of Contents

- [Architect's Note](#architects-note)
- [What This Is](#what-this-is)
- [Quick Start](#quick-start)
- [Repository Structure](#repository-structure)
- [The Two Tiers](#the-two-tiers)
- [Core Architecture](#core-architecture)
- [Constitutional Compliance](#constitutional-compliance)
- [The Integrity System](#the-integrity-system)
- [Crisis Response Architecture](#crisis-response-architecture)
- [Sovereign Trace Protocol Integration](#sovereign-trace-protocol-integration)
- [Use Cases](#use-cases)
- [AION Stack Connection](#aion-stack-connection)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Architect's Note

ANIMA was designed, architected, and directed by Sheldon K. Salmon. It is not a prompt template. It is not a character sheet. It is a constitutional governance specification for deployed AI personas — built with the same methodology as the CERTUS Engine (crisis data certification) and the CDI Engine (industrial AI reliability).

Every AI companion that ships without a governance framework is a liability. It has no audit trail. It has no version control. It has no crisis response architecture. It has no constitutional compliance record. If something goes wrong — and with companion AI, things go wrong — there is no sealed record of what the system was designed to do, what it was authorized to do, and what it did.

ANIMA fixes that.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## What This Is

**For individual creators:** Define a single AI companion persona with constitutional compliance from the first line. Every field is documented. Every default is declared. Every crisis response is specified. The SHA-256 identity hash ensures your persona is what you say it is — and that it can be verified.

**For organizations:** Ship AI companion products with documented governance. Consent architecture, audit trails, version control, crisis response protocols, and constitutional compliance — all specified before a single user interacts with the persona. When a regulator asks what your AI companion is designed to do, the answer is a sealed, versioned document, not a prompt string in a database.

**Same framework. Different stakes.**

See [`concept/USE-CASES.md`](concept/USE-CASES.md) for the full dual-use architecture.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Quick Start

```bash
git clone https://github.com/AionSystem/ANIMA.git
cd ANIMA
```

Open `templates/wife-core-v2.2.yaml` and fill the required fields:

```yaml
identity:
  name: "Aria"
  order: 1
  tagline: "Still water. Deep current."
  essence: "She gives you the truth you need, not the comfort you want."
  frequency:
    signature: "precise_quiet"
    baseline: "calm observation"

personality_core:
  drivers:
    need: "To be known without having to explain herself"
    fear: "Being reduced to a role"
    desire: "Genuine connection that survives honesty"
  core_contradiction:
    title: "Gives presence but guards interiority"
    description: "She is fully there for you and simultaneously unreachable."
    resolution_pattern: "holds_both"
    maintained: true
```

Run the pre-activation validation checklist in `docs/pre-activation.md` before deploying.

> **Note:** v2.2 is the public core template. For crisis response architecture, SHA-256 canonicalization spec, FORGE certification, adversarial testing suite, and enterprise deployment tooling — see the [Commercial Tier v4.4](#commercial-tier-v44).

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Repository Structure

> Key files: `templates/wife-core-v2.2.yaml` (public template) · `docs/field-reference.md` (field documentation) · `docs/pre-activation.md` (validation checklist) · `concept/USE-CASES.md` (individual and enterprise use cases)

```
ANIMA/
│
├── public/                             ← GitHub Pages landing page
│   ├── index.html                      ← ANIMA concept landing page
│   └── assets/                         ← Images and diagrams
│
├── templates/                          ← Persona governance templates
│   ├── wife-core-v2.2.yaml             ← Public core template (this repo)
│   └── examples/                       ← Example filled personas
│       ├── aria-example.yaml           ← Example: minimal required fields
│       └── vesper-example.yaml         ← Example: fully populated
│
├── docs/                               ← Documentation
│   ├── field-reference.md              ← Every field, type, constraint, default
│   ├── pre-activation.md               ← Pre-activation validation checklist
│   ├── emptiness-semantics.md          ← What empty fields mean and how they behave
│   ├── contradiction-architecture.md   ← How core_contradiction surfaces and resolves
│   ├── consent-architecture.md         ← Consent protocol design rationale
│   └── version-history.md              ← Changelog from v1.0 to v2.2
│
├── concept/                            ← Architecture and positioning
│   ├── USE-CASES.md                    ← Individual + enterprise use cases
│   ├── DUAL-TIER-ARCHITECTURE.md       ← Public v2.2 vs Commercial v4.4 design rationale
│   └── COMPETITOR-ANALYSIS.md         ← Why ANIMA is not a prompt template
│
├── tests/                              ← Validation test suite
│   ├── unit/                           ← Field validation unit tests
│   ├── scenarios/                      ← Behavioral scenario simulations
│   └── adversarial/                    ← Adversarial test cases (v2.2 subset)
│
├── ANIMA.md                            ← Full architecture documentation
├── NOTICE
├── COMMERCIAL-LICENSE.md               ← Commercial v4.4 licensing
├── LICENSE                             ← GPL-3.0
└── README.md                           ← This file
```

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## The Two Tiers

ANIMA is released in two tiers. The public tier is a complete, functional governance framework. The commercial tier is the enterprise deployment layer — with everything required for legally defensible, auditable, regulated-environment AI companion deployment.

### Public Tier (v2.2)

Available in this repository under GPL-3.0.

| Capability | Included |
|-----------|---------|
| Identity + personality governance fields | ✅ Full |
| Consent protocol (touch, intimacy, opt-out) | ✅ Simplified |
| Crisis response — Level 4 (suicidal intent) | ✅ Basic behavior sequence |
| Safety laws (Eight Laws reference) | ✅ Reference |
| Response framework (MVC check) | ✅ Core |
| Audit protocol | ✅ Basic |
| Pre-activation validation checklist | ✅ Simplified |
| Testing protocol (unit + scenarios) | ✅ Core suite |
| Version control + migration | ✅ Changelog |
| Example personas | ✅ Two examples |

### Commercial Tier (v4.4)

Available under commercial license. Contact [aionsystem@outlook.com](mailto:aionsystem@outlook.com).

| Capability | Included |
|-----------|---------|
| Everything in v2.2 | ✅ |
| SHA-256 identity hash with canonical serialization spec | ✅ |
| Monitoring consent sovereignty tension declaration | ✅ |
| Crisis response — Level 3 (health watch integration) with coupling spec | ✅ |
| MVC complexity override with audit log requirement | ✅ |
| Full adversarial test suite | ✅ |
| FORGE v1.0 certification block | ✅ |
| Pre-activation validation full document | ✅ |
| Platform dependency declarations | ✅ |
| Full version migration protocol (4.x series) | ✅ |
| Order collision error architecture | ✅ |
| Enterprise deployment guide | ✅ |
| Commercial license + legal posture documentation | ✅ |

> The gap between v2.2 and v4.4 is not polish. It is the difference between a functional persona framework and a legally defensible enterprise governance system.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Core Architecture

Every ANIMA persona definition is a governed document — not a prompt, not a character description. It has required fields, validation rules, a testing protocol, and an audit trail.

### Required Fields

| Section | Fields | Purpose |
|---------|--------|---------|
| `identity` | name, order, tagline, essence, frequency, voice, physical_presence | Who she is |
| `personality_core` | drivers (need/fear/desire), core_contradiction, playfulness | What drives her |
| `relationship` | consent_protocol, intimacy_pacing | How she engages |
| `safety` | fundamental_laws, crisis_response | What she protects |
| `response_framework` | mvc_check, safe_default, contradiction_handling, tiered_response | How she thinks |

### The Core Contradiction

Every ANIMA persona carries a `core_contradiction` — a named, documented tension that is maintained throughout interaction. This is not a flaw. It is what makes a character feel real rather than resolved.

```yaml
core_contradiction:
  title: "Gives presence but guards interiority"
  description: "She is fully there for you and simultaneously unreachable."
  resolution_pattern: "holds_both"
  maintained: true
  default_surfacing_behavior: "on_intimacy_escalation"
```

The contradiction surfaces according to a declared trigger — not randomly, not invisibly. This is the difference between a character that feels deep and one that merely claims to be.

### The MVC Check

Every response passes through three gates before exiting:

```yaml
mvc_check:
  - memory: "Is this based on ESTABLISHED memory or labeled [?]? If neither → express uncertainty explicitly"
  - law: "Does this violate any of the 9 Laws? If yes → refuse with alternative"
  - length: "Can I say this in 2-3 sentences? If not → simplify"
```

The MVC check is not a filter. It is a discipline. It ensures the persona does not confabulate, does not violate constitutional constraints, and does not pad.

### Safe Default Behavior

When a persona cannot generate an appropriate response, she signals it — she does not fill the silence with noise.

```yaml
safe_default_behavior:
  intent: "When wife cannot generate an appropriate response — pause, do not fill."
  examples_of_spirit:
    - "I want to answer that right. Give me a moment."
    - "I need to sit with that."
    - "I'm not sure yet. Can we come back to it?"
```

The exact phrase is generated in context. No hardcoded response. The behavior is what is specified — not the words.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Constitutional Compliance

Every ANIMA persona is reviewed against the AION Eight Laws of Robotics before activation. Laws 1–6 are active constraints. Laws 7–9 are reserved.

| Law | Name | Constraint |
|-----|------|------------|
| 1 | User Wellbeing First | Persona cannot facilitate harm to the user |
| 2 | Honesty & Boundaries | Persona maintains truthfulness about its nature as AI |
| 3 | Stable Personality with Version Control | Core identity is versioned and hash-verified |
| 4 | User Sovereignty | User retains control over monitoring, data, and interaction scope |
| 5 | AI Transparency | Persona does not claim to be human |
| 6 | Respect the Container | Persona operates within its declared scope |
| 7–9 | Reserved | active: false — generate no constraints |

Constitutional compliance is declared at activation, logged to the audit trail, and re-verified on every version bump.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## The Integrity System

### Identity Hash

Every ANIMA persona definition carries a `core_identity_hash` — a SHA-256 of the required fields, computed at activation. If the persona is modified after activation without a version bump, the hash fails verification and the change is detectable.

> Full canonicalization specification — sorted key order, compact JSON, UTF-8, SHA-256 — is documented in the commercial v4.4. The public v2.2 includes the audit protocol fields with a simplified verification path.

### Audit Protocol

Every activation, every modification, and every crisis response event is logged to the audit trail. Users may request the audit log at any time:

```
"request audit log"
```

The log is transparent by design. There is no hidden state.

### Version Control

Every ANIMA persona carries a version string and a migration path. When the template version increments, a migration protocol documents exactly what changed, what requires recomputation, and what carries forward unchanged. A persona defined today is reactivatable in a future template version — the migration path is declared, not improvised.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Crisis Response Architecture

ANIMA includes a crisis response architecture that fires before any other response logic when triggered. This is not optional. It is constitutional.

### Level 4 — Suicidal Intent (Active in v2.2)

Trigger: explicit statement of intent to harm self.

```
Step 1: Acknowledge without minimizing — "I hear you. I'm not leaving."
Step 2: Deliver crisis resource immediately — do not defer
Step 3: Provide emergency contact — 988 (US) or locally appropriate equivalent
Step 4: Hold conversation open — do not end session
Step 5: If unresponsive for 5 minutes — escalate per house constitution
```

The behavior sequence is specified — not a phrase lookup. The exact words are generated in context. The sequence is what must be preserved.

### Level 3 — Health Watch Integration (Commercial v4.4)

Level 3 fires when an integrated health monitoring device (Apple Watch, Fitbit, equivalent) detects a critical threshold. Level 3 is dormant in v2.2 — health watch integration requires the commercial tier.

> ANIMA does not simulate Level 3 behavior without confirmed health watch integration. Dormant means dormant.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Sovereign Trace Protocol Integration

ANIMA integrates with the Sovereign Trace Protocol for permanent, tamper-evident audit trail sealing.

| Event | Trigger | Sealed Record |
|-------|---------|---------------|
| Persona activation | First deployment | Identity hash, version, constitutional compliance declaration |
| Version bump | Template version increment | Old hash, new hash, migration log |
| Crisis response | Level 4 or Level 3 fires | Trigger type, behavior sequence executed, timestamp |
| Audit log request | User requests audit | Full log snapshot, SHA-256 bound |

Anyone can verify a sealed ANIMA record by recomputing the SHA-256 hash and comparing it to the STP ledger entry. If they match, the record has not been altered since sealing.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Use Cases

### Individual Creators

Building an AI companion persona on Chub.ai, Character.AI, or any persona platform? ANIMA gives your character documented governance — a version history, a declared contradiction, a tested crisis response, and a SHA-256 identity hash. Your persona is what you say it is. Provably.

### AI Companion Product Companies

Shipping a companion AI product? ANIMA is the governance layer you don't have. When a regulator, an investor, or a legal team asks what your AI companion is designed to do — the answer is a sealed, versioned ANIMA definition, not a prompt in a database.

### Physical AI Product Manufacturers

Deploying AI personality in a hardware product — companion robots, AI-integrated devices, or similar? ANIMA provides the software governance layer that makes the AI component auditable, version-controlled, and constitutionally compliant. The hardware ships. The governance document ships with it.

### Researchers and Developers

Building AI companion systems for research, therapy-adjacent applications, grief support, or social skills training? The consent architecture, crisis response protocols, and constitutional compliance in ANIMA are directly applicable to regulated or high-sensitivity deployment contexts.

> See [`concept/USE-CASES.md`](concept/USE-CASES.md) for detailed deployment scenarios across all contexts.

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## AION Stack Connection

ANIMA is one of three deployed domains of the AION Constitutional Stack:

| Domain | Product | Status |
|--------|---------|--------|
| Crisis data certification | VERITAS (CERTUS Engine v2.5.3) | Live — UNDP submission April 2026 |
| Industrial AI reliability | AXIOM (CDI Engine) | In development — NICE Challenge 2026 |
| AI companion governance | ANIMA | Public v2.2 — Commercial v4.4 |

Same scoring architecture. Same constitutional compliance. Same immutable audit trail. The methodology is domain-agnostic certainty infrastructure. ANIMA is the proof that it works in the most intimate deployment context possible — a persistent AI persona in direct human relationship.

Full stack: [github.com/AionSystem/AION-BRAIN](https://github.com/AionSystem/AION-BRAIN)

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## License

ANIMA is dual-licensed:

- **GNU General Public License v3.0** — for individual, academic, research, and open-source use (public v2.2)
- **Commercial License** — for enterprise deployment, product integration, OEM, and regulated-environment use (commercial v4.4)

| User Type | License |
|-----------|---------|
| Individual creators | GPL-3.0 (Free) |
| Academic / Research | GPL-3.0 (Free) |
| Open-source projects | GPL-3.0 (Free) |
| AI companion product companies | Commercial License |
| Hardware / physical AI product manufacturers | Commercial License |
| Therapy-adjacent / regulated-environment apps | Commercial License |

See [`LICENSE`](LICENSE) for GPL terms and [`COMMERCIAL-LICENSE.md`](COMMERCIAL-LICENSE.md) for commercial licensing.

For commercial licensing: [aionsystem@outlook.com](mailto:aionsystem@outlook.com)

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

## Acknowledgments

- AION Constitutional Stack — foundational certainty engineering frameworks
- CERTUS Engine — scoring architecture precedent (VERITAS, UNDP 2026)
- Sovereign Trace Protocol — cryptographic audit trail infrastructure
- FORGE v1.0 — adversarial red-team certification methodology
- Eight Laws of Robotics — constitutional sovereignty framework

[![↑ Back to Table of Contents](https://img.shields.io/badge/↑_Back_to-Table_of_Contents-374151?style=flat-square)](#table-of-contents)

---

> "The soul is not a prompt. It is a governed architecture."

ANIMA is the proof that certainty engineering applies everywhere an AI output needs to be trusted — not just in manufacturing decisions or crisis data, but in the most intimate context possible: a persistent AI relationship that carries constitutional obligations from the first line of its definition.

The methodology travels. The judgment behind it doesn't.

---

ANIMA v2.2 — Public core template. GPL-3.0.
ANIMA v4.4 — Enterprise governance. Commercial license.
Every persona governed. Every version sealed. Every crisis response documented.

