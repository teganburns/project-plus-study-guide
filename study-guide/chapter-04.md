---
layout: default
title: "Ch. 4: Core Principles of Project Initiation"
permalink: /study-guide/chapter-04/
---

# Ch. 4: Core Principles of Project Initiation

<p class="lede">Project initiation is where the project becomes formally authorized and the early boundaries are set.</p>

<ul class="quick-links">
  <li><a href="{{ '/quizzes/chapter-04/' | relative_url }}">Chapter 4 Quizzes</a></li>
  <li><a href="{{ '/study-guide/' | relative_url }}">All Study Guide Chapters</a></li>
</ul>

## Business Case To Project Charter

The project business case and the project charter are closely connected, but they do different jobs.

The business case comes first. It is the value proposition for a proposed project and helps the organization decide whether the project is worth doing. If the organization decides the project should proceed, the information from the business case may be used to create the project charter.

The project charter comes next. It formally authorizes the project to begin and gives the project manager authority to start coordinating the work.

Business Case -> decision to proceed -> Project Charter -> project begins

| Document | Key question | Key purpose |
| --- | --- | --- |
| Business Case | Should the project proceed? | Justifies the proposed project by explaining the business need, options, recommendations, benefits, and feasibility. |
| Project Charter | Is the project authorized to begin? | Formally authorizes the project and defines high-level objectives, boundaries, expectations, and success criteria. |

<p class="study-note"><strong>Key takeaway:</strong> the business case supports the decision to approve the project; the project charter authorizes the approved project to begin.</p>

## Project Charter

The project charter is the document issued by the project sponsor that formally authorizes the existence of a project.

It answers the early question: what are we trying to achieve, and what business need are we meeting?

A project charter may include:

- Project purpose and high-level requirements
- Objectives
- Overall project risk
- Summary schedule and budget
- Key stakeholders
- Success criteria and approval requirements
- Exit criteria
- Project manager name and level of authority

The charter is not the same as a detailed project management plan. It is a high-level authorization document that gives the project permission to exist and gives the project manager authority to begin coordinating the work.

The project charter can also apply in Agile or adaptive frameworks. In Agile projects, expect the charter to be lighter and more likely to be updated as the team learns more. The charter gives the project a starting direction, but it should not pretend every requirement, risk, schedule detail, or delivery decision is already fully known.

Exam cue: the charter formally authorizes the project. It is not a vendor contract, and it is not the full detailed plan.

## Agile Product Vision And Product Roadmap

Agile projects still need direction during initiation. Instead of trying to lock every feature and requirement up front, Agile teams often use a product vision and product roadmap to set a clear purpose and a flexible path forward.

| Artifact | What it does | What it is not |
| --- | --- | --- |
| Product vision | Gives a short, high-level statement of the business purpose of the product. | Not a list of features. |
| Product roadmap | Shows general time frames and major product themes or outcomes. | Not a fixed schedule or detailed project plan. |

Product vision answers: why should this product exist?

Product roadmap answers: what major themes are we aiming toward, and roughly when?

```text
Product Vision
  business purpose and direction
        |
        v
Product Roadmap
  broad themes over time
        |
        v
Backlog and Iterations
  details emerge and change as the team learns
```

Example roadmap view:

| Now | Next | Later |
| --- | --- | --- |
| Validate onboarding needs | Improve reporting experience | Expand integrations |
| Resolve top customer pain points | Add role-based workflow themes | Revisit future market opportunities |

The product roadmap is usually a strategic planning tool. It provides enough time framing to align expectations, but it should stay flexible. In Agile, expect the roadmap to be updated as feedback, priorities, risks, and learning change.

<p class="study-note"><strong>Exam cue:</strong> product vision explains the product's business purpose; product roadmap gives broad themes and time frames. Neither is meant to be a fixed list of every feature.</p>

## Stakeholder Register

A stakeholder register is a project document used to identify people, groups, or organizations that may affect the project or be affected by the project.

It is usually started during initiation because the team needs to know who matters before planning communication, approvals, requirements discussions, risks, and expectations.

```text
Project Charter
  identifies sponsor, project manager, and key stakeholders
        |
        v
Stakeholder Register
  captures stakeholder details, influence, interest, and expectations
        |
        v
Communication and Engagement Planning
  uses the register to decide who needs what information and when
```

A stakeholder register may include:

- Stakeholder name or group
- Role or organization
- Contact information
- Interest in the project
- Level of influence or authority
- Expectations, concerns, or requirements
- Preferred communication method
- Current engagement level or attitude toward the project

| Stakeholder | Role | Interest | Influence | Likely communication need |
| --- | --- | --- | --- | --- |
| Project sponsor | Approves and funds the project | Business value and success criteria | High | Summary status, risks, decisions needed |
| Project manager | Coordinates the project work | Scope, schedule, resources, issues | High | Daily project detail and escalation paths |
| End users | Use the final product or service | Usability, workflow impact, support needs | Medium | Requirements discussions, demos, rollout updates |
| Vendor | Provides products or services | Contract terms, delivery expectations | Medium | Procurement details, milestones, acceptance criteria |

<p class="study-note"><strong>Exam cue:</strong> the stakeholder register is about identifying and understanding stakeholders. It is not the communication plan itself, but it feeds the communication plan.</p>

## RAM And RACI

A Responsibility Assignment Matrix, or RAM, maps project work to the people or roles responsible for that work. It helps clarify stakeholder roles early in the project, especially when deliverables need visible ownership.

RACI is a common type of RAM.

```text
Project deliverables
        |
        v
Responsibility Assignment Matrix (RAM)
        |
        v
RACI view: Responsible / Accountable / Consulted / Informed
```

| RACI letter | Meaning | Role in plain language |
| --- | --- | --- |
| R | Responsible | Does the work. |
| A | Accountable | Approves or signs off the work. |
| C | Consulted | Provides information, input, or expertise. |
| I | Informed | Needs to be kept in the loop. |

Example RACI matrix:

| Deliverable | Project manager | Sponsor | Technical lead | Customer |
| --- | --- | --- | --- | --- |
| Project charter | R | A | C | I |
| Stakeholder register | A/R | C | C | I |
| High-level requirements | I | A | R | C |

The most important RACI rule for the exam: each item should have only one Accountable person. The Accountable person can also be the Responsible person, which is why you may see `A/R` in a single cell.

Consulted and Informed can include multiple people or groups. Consulted stakeholders give input before decisions or work are finalized. Informed stakeholders are kept updated after decisions or progress updates.

These tools can be used early in initiation to clarify roles, and they may also appear later during more detailed resource planning. In Agile environments, use them lightly. Agile teams are often self-organizing, so an overly rigid RACI can work against the way the team collaborates.

<p class="study-note"><strong>Exam cue:</strong> RAM assigns work ownership. RACI expands that into Responsible, Accountable, Consulted, and Informed. One Accountable per item.</p>

## Kickoff Meeting

The kickoff meeting is usually the first official meeting between the project team and the sponsor. It happens early in the project, or at the start of a major phase in a larger project.

The goal is to align people before the work gets moving. It is a good opportunity to:

- Make introductions, such as the project manager, sponsor, team members, and key stakeholders.
- Communicate the project purpose and goals.
- Set expectations about deadlines, challenges, procedures, and working norms.
- Clarify roles and responsibilities.
- Take questions and allow enough time for Q&A.

If important details are still not known, the meeting may need to be delayed briefly or followed by another kickoff later. The point is not to pretend everything is solved. The point is to make sure the right people understand the project purpose, their roles, and what happens next.

```text
Project Charter approved
        |
        v
Stakeholders and roles identified
        |
        v
Kickoff Meeting
  introduce people, share purpose, set expectations, clarify roles, answer questions
        |
        v
Team begins with shared context
```

<p class="study-note"><strong>Exam cue:</strong> kickoff meetings align the team and sponsor around purpose, expectations, roles, and next steps.</p>

## Document Vs Record

In everyday conversation, people may use the words document and record loosely, and sometimes they may seem to mean the same thing. For the exam, the useful distinction is that a document is working information, while a record is evidence of something that happened or was approved.

| Document | Record |
| --- | --- |
| Any piece of written information. | A piece of evidence. |
| Can be edited while the work is in progress. | Is final or preserved as historical proof. |
| May be saved for a short or long period of time. | Is kept for a specific retention period based on policy, industry, location, or information type. |
| Examples: draft project charter, draft requirements, working plans, templates. | Examples: approved charter, signed approval, meeting minutes, completed change record, final acceptance. |

Think of a document as something the team may still be shaping. Think of a record as something the project keeps to show what was decided, approved, completed, or communicated.

<p class="study-note"><strong>Exam cue:</strong> documents can still change; records are retained evidence.</p>
