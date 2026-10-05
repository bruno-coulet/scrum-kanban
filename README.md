# Scrum framework

## Project context


This project is part of first the year program of the [Master of science Data /AI degree](https://laplateforme.io/mastere/intelligence-artificielle/) delivered by la [Plateforme](https://laplateforme.io/)<br>
**Duration** : 5 days<br>
**Team** : 1 person<br>

## Goal

Acquire the understangind and the technics of the agile **scrum** framework and apply them to the planification of an AI project.
No code is needed, just conception and planning.


## The Case Study — RAG Assistant for Dangerous Cargo Operations

The Scrum framework is applied to a concrete, real-world AI project: an internal
assistant for **CMA-CGM's Dangerous Cargo Office (DCO)**.

**The problem** — The DCO booking process for dangerous goods is complex. Large
volumes of emails from commercial agents reach the DCO Head Office asking about
handling procedures (IMDG Code, internal Custom Rules, P&R), delaying bookings.

**The proposed solution** — A **RAG (Retrieval-Augmented Generation)** pipeline that
anchors an LLM on the IMDG Code and internal documentation:

1. The system **intercepts** each agent request
2. The RAG pipeline **generates a sourced answer** (exact citations: part/section/UN number)
3. The request and draft answer are submitted to the **DC adviser for review** —
   who approves, edits, or rejects it

**Human-in-the-loop (HITL) by construction**: no answer is ever sent without human
validation. Automation applies to drafting, not to decision-making — a key
safety-critical requirement when handling dangerous goods regulations.

**Planning deliverables (no code)** — The one-week exercise covers the full Scrum
planning chain:

- User stories (INVEST, Given/When/Then) and an Epic
- 5 Capabilities → 8 Components (K1–K8)
- Architecture decisions (RAG over fine-tuning, mandatory HITL review, batch ingestion)
- An ordered **Product Backlog** (9 items)
- The first **Sprint Backlog**: a "walking skeleton" increment — one end-to-end
  request on a reduced document corpus (18 person-days, 10 tasks)

**Key constraints**: near-zero budget, IMDG Code licensing as a blocking legal
dependency, tabular corpus requiring hierarchical chunking, biennial regulatory
updates.

## To do:

1. Slides

An explicative set of [Diapositives / Slides](https://www.figma.com/deck/uZQ3aWykcW9jZg9pFijbZE/prez-scrum?node-id=6-511&t=dRioIFOirXEEMUgd-1)<br> that presents the work achieved
Including little text an  plenty of visual icons to present  key concepts<br>
Ending with a finals lide showing measurable benefits from the scrum method

---
2. [Complete documentation](scrum_guide.md)

A complete documentation : a clear .pdf guide strucutred in sections
- introduction
- roles
- events
- artifacts
- Use cases


