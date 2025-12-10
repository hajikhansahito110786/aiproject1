<!--
---
Sync Impact Report
---
- Version change: 1.0.0 -> 2.0.0
- Rationale: Complete replacement of core principles to focus on code quality, testing, UX, and performance.
- Modified Principles:
  - REPLACED: "Spec-Driven Development" -> "Uncompromising Code Quality"
  - REPLACED: "Atomic, Testable Tasks" -> "Rigorous & Automated Testing"
  - REPLACED: "Agent-First Workflow" -> "Consistent User Experience"
  - REPLACED: "Immutable History" -> "Performance as a Feature"
  - REMOVED: "Convention Over Configuration"
  - REMOVED: "Self-Documenting System"
- Templates requiring updates:
  - ✅ .specify/templates/plan-template.md
- Follow-up TODOs:
  - TODO(RATIFICATION_DATE): The original ratification date was not found and needs to be set.
-->
# Gemini CLI Constitution

## Core Principles

### I. Uncompromising Code Quality
All code must be clear, maintainable, and adhere to established language-specific idioms and project-wide style guides. Code is a liability; it must be as lean and high-quality as possible to ensure long-term stability and ease of development.

### II. Rigorous & Automated Testing
A feature is not complete until it is covered by comprehensive automated tests. Every new feature or bug fix must be accompanied by unit, integration, or end-to-end tests that validate its correctness, robustness, and handle edge cases. Test coverage should be actively monitored.

### III. Consistent User Experience
The user interface, whether graphical or command-line, must be predictable, consistent, and intuitive. All user-facing interactions, from command names to error messages, should follow established patterns to reduce cognitive load and enhance usability.

### IV. Performance as a Feature
Application performance is a critical, non-negotiable requirement. Latency, resource consumption (CPU, memory), and overall responsiveness must be measured, monitored, and optimized. Performance goals are to be defined upfront and validated before release.

## Governance

This Constitution is the authoritative source for project standards. Any proposed amendment requires an Architectural Decision Record (ADR) and approval from the project lead. All code reviews MUST validate compliance with these principles.

**Version**: 2.0.0 | **Ratified**: TODO(RATIFICATION_DATE) | **Last Amended**: 2025-12-10