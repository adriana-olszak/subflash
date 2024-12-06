# ADR 1 - Record Architecture Decision

#### Date

2024-12-04

## Status

Accepted

## Context

Even though this project is started by single person capturing archtecure decisions is crucial for high maintainability of the package. It will also serve as a place for recording results of experiments and selected path.

## Decision Drivers

- Written documentation as long-term maintainability improvement
- Improved developer experience in case other contributors join the project
- Possibly long development timeline - having access to historical rationale is crucial
- Need for consistent decision-making process and documentation

## Decisions

- All significant architectural decision MUST be documented using ADRs
- ADRs MUST use [RFC2119](https://datatracker.ietf.org/doc/html/RFC2119) keywords to clearly communicate their meaning
- Diagrams SHOULD be included when they help clarify complex architectural concepts
- All Diagrams MUST be written in Mermaid markup language to ensure they remain in version control and are easily modifiable
- Each ADR MUST include Context, Decision Drivers, Decisions, and Consequences sections

## When to write an ARD

And ADR SHOULD be written when a decision:

- Has a significant impact on the system Architecture
- Affects multiple components or stakeholders
- Introduces or modifies technical contraints
- Changes previously documented decisions
- Involves selection between multiple viable alternatives
- Has long-term implications for maintainability or scalability

## Consequences

### Positive

- Improved project documentation and maintainability
- Clear record of decisions rationale for future reference
- Easier onboarding for new contributors
- Structured approach to decision making

### Negative

- Additional overhead
- Need to maintain and update ADRs as decisions evolve
- Risk of over-documenting
