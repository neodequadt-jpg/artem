# RFC-0007

## Title

Repository Architecture Revision 1

## Status

Draft

---

## Motivation

The current repository architecture separates engineering artifacts into multiple directories.

During the development of ARTEM Pre-Theory, it became clear that Foundation should not explain engineering principles.

Foundation defines them.

Theory explains them.

This separation reduces conceptual coupling and improves long-term maintainability.

---

## Proposed Repository Architecture

ARTEM/

├── Foundation/
├── Theory/
├── Protocols/
├── Laboratory/
├── Reference/
├── Modules/
├── Research/
├── RFC/
├── ADR/
├── Governance/
├── Brand/
└── Examples/

---

## Responsibilities

Foundation
Defines immutable engineering knowledge.

Theory
Explains and justifies Foundation.

Protocols
Defines engineering processes.

Laboratory
Hosts experimental ideas.

Reference
Contains validated examples and evidence.

Modules
Contains domain-specific extensions.

Research
Stores scientific investigations.

Governance
Defines project governance.

---

## Status

Draft

This proposal requires Review Engine evaluation before acceptance.

