# Why Projects Fail Before They Start: A Map of Core PM Concepts

*By Samin Salehi, PMP · Companion notes for the Project Manager Land video [Why Most Projects Fail Before They Start (5 Steps to Fix It)](https://www.youtube.com/watch?v=ZPpq8Pobk5g) (Nov 2026)*

> **Note:** these notes follow the video's chapter outline. The explanations are standard project management practice written for this repository, not a transcript. Watch the video for Samin's own explanation.

Many projects are set up to fail on day one: the goal is vague, the scope is open-ended and nobody agrees on who decides what. This page maps the concepts that prevent that, in the order the video covers them.

---

## 1. Project vs. operations
- A **project** is temporary, has a defined result, and ends.
- **Operations** are ongoing, repeatable work.

See [Guide 1](01-what-is-project-management.md) for the hospital room example.

## 2. What a project manager does
The project manager plans, coordinates, communicates, tracks progress and helps the team make decisions. Communication is a large share of the job: keeping people connected and making it clear when a decision is needed.

## 3. Waterfall vs. Agile vs. Hybrid
| Approach | Works best when | Typical tools |
|----------|-----------------|---------------|
| **Waterfall (predictive)** | Scope is well understood and changes are expensive (for example, building and fit-out work) | Charter, WBS, Gantt chart, critical path |
| **Agile (adaptive)**: Scrum, Kanban | Requirements will evolve and feedback cycles are short | Backlog, sprints, boards |
| **Hybrid** | Some parts are fixed and some need flexibility | A predictive overall plan with iterative delivery inside it |

## 4. The triple constraint: scope, time and cost
Scope, time and cost are linked. Change one and at least one other moves. Adding scope without adding time or budget usually puts **quality** at risk.

## 5. The five process groups
1. **Initiating:** define why, get authorization ([Project Charter](../templates/project-charter.md))
2. **Planning:** scope statement, WBS, schedule, budget, risk and communication plans
3. **Executing:** do the work, manage the team and stakeholders
4. **Monitoring and controlling:** compare actual progress with the plan, control changes
5. **Closing:** accept, hand over, capture lessons learned ([Closeout Checklist](../checklists/handover-and-closeout-checklist.md))

## 6. Where projects really break
Most failures trace back to early gaps: an unclear goal, unclear scope, missing stakeholders, an unrealistic schedule, or no process for handling change.

## 7. Stopping scope creep
- Write a **scope statement** that says what's included *and excluded* ([template](../templates/scope-statement.md)).
- Route every new request through a **change control process** ([Change Request template](../templates/change-request.md)).
- Assess the impact on scope, time and cost before anyone says yes.

## 8. Stakeholders and the risk register
- A **stakeholder matrix** maps people by influence and interest, so you know who to manage closely and who to keep informed ([Stakeholder Register](../templates/stakeholder-register.csv)).
- A **risk register** lists each risk with its likelihood, impact, owner and response ([Risk Register](../templates/risk-register.csv)).
- **Three-point estimates** use optimistic (O), most likely (M) and pessimistic (P) durations. The PERT estimate is (O + 4M + P) / 6.

## 9. Communication, time and budget
Set a reporting rhythm early (see the [Weekly Status Report](../templates/weekly-status-report.md)). Track the schedule against the baseline and spending against the budget.

## 10. Team roles and the RACI chart
For each deliverable, mark who is **R**esponsible, **A**ccountable (exactly one person), **C**onsulted and **I**nformed ([RACI template](../templates/raci-matrix.csv)).

## 11. Tracking progress: schedule and cost variance
Earned value management (EVM) basics:
- **PV** (planned value): the budgeted cost of work scheduled to date
- **EV** (earned value): the budgeted cost of work actually completed
- **AC** (actual cost): what the completed work actually cost
- **Schedule variance** SV = EV − PV (negative means behind schedule)
- **Cost variance** CV = EV − AC (negative means over budget)
- **SPI** = EV / PV, **CPI** = EV / AC (below 1.0 is unfavorable)

*Worked example:* by week 6 you planned $50,000 of work (PV), completed $40,000 of it (EV) and spent $45,000 (AC). SV = −$10,000 (behind schedule) and CV = −$5,000 (over budget).

## 12. Which certification?
| Certification | From | Typical fit |
|---------------|------|-------------|
| CAPM® | PMI | Entry level, no project experience required |
| PMP® | PMI | Experienced project managers |
| PMI-ACP® | PMI | Agile practitioners |
| CSM® | Scrum Alliance | Scrum Master role |

Always check current eligibility rules with the certifying body.

---

### Putting it all together
Before the work starts, confirm you have: an agreed goal, a written scope with exclusions, a realistic schedule built from a WBS, named decision-makers, a risk register, and a change process. Use the [Project Kickoff Checklist](../checklists/project-kickoff-checklist.md).
