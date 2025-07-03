# Problem Overview

## Business Context

At large retail gas stations, service engineers are responsible for maintaining a wide range of critical devices — pumps, sensors, safety valves, and more. Historically, these engineers log the maintenance activity manually using paper forms, which were later transcribed into internal systems.

This process led to:
- Delays in updating service records
- Limited visibility for operations and maintenance managers
- Missed service windows and compliance risks
- Frustration among engineers and support teams

The business recognized the need to digitize this workflow to increase efficiency, reduce manual effort, and improve real-time visibility of field operations.

---

## Project Objective

To develop a mobile-based solution (tablet or phone app) for field engineers that:
- Allows real-time service updates, alerts, and task closures
- Enables inventory tracking from the field
- Integrates with existing back-office systems
- Works in low-connectivity environments (offline sync)

---

## Technology Landscape (Initial Exploration)

- **Front-End:** React Native (cross-platform mobile UI)
- **Back-End:** REST APIs, middleware integration with existing maintenance systems (e.g., SAP,)
- **Data Layer:** Secure cloud storage with offline sync support
- **Authentication:** OAuth 2.0 with enterprise SSO
- **DevOps:** GitHub Actions, Firebase for analytics and crash monitoring

---

## Methodology Chosen: Lean UX + Agile Delivery

We adopted a hybrid approach:
- **Lean UX** to validate user needs and flows before development
- **Agile** sprint-based delivery for incremental app releases
- **Feedback loops** from real field engineers integrated every 2 weeks

This approach allowed flexibility, faster iterations, and stronger user buy-in.

---

## Why a Pilot (Not a Full Rollout)

We intentionally limited the first release to a **pilot phase** across selected regions to:
- Validate user experience and technical performance
- Capture real-time feedback from field engineers
- Manage deployment risks in a controlled environment
- Provide data for go/no-go decisions before scale-up

---

## PM Contribution in Ideation Phase

As the Project Manager, I played a strategic role during early scoping and planning:

- Initiated user research and shadowed engineers to map pain points
- Facilitated workshops between IT, Ops, and Product to define MVP scope
- Challenged overengineering by proposing iterative rollouts instead of a full-stack platform from day one
- Created the first draft of KPIs tied to business outcomes like service cycle time, adoption rate, and inventory accuracy
- Positioned the pilot as a **proof-of-value**, not just a proof-of-concept

---

## Outcome of This Phase

- Stakeholders aligned on problem definition and MVP vision
- Pilot scope approved for development with clear success criteria
- Field users identified and onboarded early for feedback and testing
