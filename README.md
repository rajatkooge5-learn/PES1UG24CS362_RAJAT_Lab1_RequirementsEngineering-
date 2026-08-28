# Lab 1: Requirements Engineering & UML Use-Case Modelling

**Name:** Rajat Kiran Kooge
**SRN:** PES1UG24CS362
**Section:** F
**Course:** Software Engineering
**Institution:** PES University

## Problem Statement

**#53 — Freelance Content Creator Escrow Platform**

A freelance contract management system allowing creators and sponsors to define deliverable milestones, review watermarked draft assets, and trigger secure milestone payment releases.

**Stakeholders:** Content Creator, Client Sponsor

## Deliverables

| File | Description |
|------|-------------|
| `PES1UG24CS362_Lab1_Requirements_Rajat.xlsx` | Requirements table with 5 Functional Requirements (FR-001–FR-005) and 2 Non-Functional Requirements (NFR-001–NFR-002), each with ID, Type, Description, Priority, Acceptance Criteria, and Rationale |
| `PES1UG24CS362_RAJAT_USECASE_DAIGRAM_.pdf` | UML Use-Case Diagram with 3 actors, 7 use cases, one `<<include>>` and one `<<extend>>` relationship |
| `PES1UG24CS362_Lab1_UseCase_Flow_Rajat.pdf` | Use-Case Flow specification for UC-05 (Approve Draft Deliverable), including Main Success Scenario and Alternate Flow |

## Summary

- **Actors:** Content Creator, Client Sponsor, Payment Gateway (external system)
- **Use Cases:** Define Milestone, Submit Draft Deliverable, Watermark Draft, Review Draft, Approve Draft, Release Milestone Payment, Reject Draft
- **Relationships:**
  - `<<include>>` — Submit Draft Deliverable → Watermark Draft
  - `<<include>>` — Approve Draft → Release Milestone Payment
  - `<<extend>>` — Reject Draft → Review Draft

## Tools Used

- draw.io — UML Use-Case Diagram
- Microsoft Excel — Requirements Table
- Microsoft Word — Use-Case Flow Specification
