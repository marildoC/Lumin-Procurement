# Lumin Procurement

### Procurement Intelligence & Decision Orchestration

**Lumin Procurement** is a procurement intelligence environment built around the full decision lifecycle of a tender — from opportunity formation and supplier participation to structured evaluation, comparative analysis, and final selection.

The system treats procurement not as a sequence of disconnected forms, but as an **evidence-driven decision process**. Tender state, vendor submissions, evaluator assessments, scoring, operational signals, and outcomes are brought into a common workflow so that each decision can be understood within the context that produced it.

## Decision Architecture

Lumin separates participation, evaluation, and decision authority while maintaining a unified representation of procurement state.

This enables:

- structured multi-actor evaluation
- comparative scoring and evidence aggregation
- controlled tender-state progression
- vendor and evaluator separation
- decision traceability across the procurement lifecycle
- operational visibility into progress, timing, and outcomes

The objective is to move procurement from administrative processing toward a more explicit **decision architecture**, where evidence, responsibility, and state transitions remain connected.

## Intelligence Layer

Lumin introduces an intelligence layer above the procurement workflow, designed to surface patterns that may otherwise remain distributed across submissions, evaluations, timelines, and vendor histories.

Its current decision-support surfaces explore concepts such as:

- supplier performance signals
- evaluation progress and bottlenecks
- submission completeness
- comparative tender metrics
- procurement timeline deviations
- scoring and ranking context

The present implementation uses prototype-driven insight data rather than a production AI inference service. The architecture is intended to provide a foundation for future **document intelligence, semantic tender analysis, supplier-risk modelling, anomaly detection, ranking assistance, and human-in-the-loop recommendation systems**.

## Human-in-the-Loop by Design

Lumin does not treat automation as a replacement for procurement judgment.

The system is structured around a **human-in-the-loop model** in which computational intelligence can organize evidence, expose patterns, and support comparison while evaluation and award authority remain explicit parts of the workflow.

## Technical Foundation

Built with **TypeScript, React, Vite, React Router, TanStack Query, Radix/shadcn UI, and Tailwind CSS**.

Lumin Procurement represents the application and decision-model layer of a broader vision: transforming procurement data into structured, explainable, and increasingly intelligent decision workflows.
