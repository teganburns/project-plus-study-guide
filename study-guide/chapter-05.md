---
layout: default
title: "Ch. 5: Managing Scope, Modifications, and Change Control"
permalink: /study-guide/chapter-05/
---

# Ch. 5: Managing Scope, Modifications, and Change Control

<p class="lede">This chapter focuses on defining what the project will deliver, controlling changes, and keeping the plan aligned as work becomes more detailed.</p>

<ul class="quick-links">
  <li><a href="{{ '/quizzes/chapter-05/' | relative_url }}">Chapter 5 Quizzes</a></li>
  <li><a href="{{ '/study-guide/' | relative_url }}">All Study Guide Chapters</a></li>
</ul>

## Planning Activities

Planning turns the approved project idea into a coordinated plan for how the work will be delivered. The main output of planning is the project management plan, supported by more detailed planning documents for scope, schedule, budget, resources, risk, and transition.

```text
Project Charter approved
        |
        v
Planning activities
        |
        v
Project Management Plan
  plus supporting scope, schedule, budget, resource, risk, and transition details
```

Common planning activities include:

- Develop a project management plan.
- Develop a detailed scope statement.
- Define units of work.
- Assess the resource pool.
- Assign project resources.
- Develop a schedule.
- Determine the budget.
- Assess risks.
- Develop a transition plan.

| Planning activity | Why it matters |
| --- | --- |
| Project management plan | Pulls together the overall approach for managing the project. |
| Detailed scope statement | Defines what is included and excluded so the team can control scope. |
| Units of work | Breaks the project into manageable work pieces. |
| Resource pool and assignments | Identifies who or what is available and assigns resources to the work. |
| Schedule and budget | Establishes timing and cost expectations. |
| Risk assessment | Identifies uncertainty before it becomes a project problem. |
| Transition plan | Plans how the final product, service, or result will move into use or operations. |

<p class="study-note"><strong>Exam cue:</strong> planning is where the project management plan is built. Scope, schedule, budget, resources, risks, and transition details all support that plan.</p>

## Triple Constraint

The triple constraint, sometimes called the iron triangle, shows how scope, cost, and time interact. Quality sits in the middle because changing one side usually puts pressure on the others.

<figure class="study-visual" aria-labelledby="triple-constraint-caption">
  <figcaption id="triple-constraint-caption">The iron triangle: scope, cost, and time all influence quality.</figcaption>
  <div class="constraint-visual-grid">
    <svg class="iron-triangle" viewBox="0 0 640 460" role="img" aria-labelledby="iron-triangle-title iron-triangle-desc">
      <title id="iron-triangle-title">Triple constraint iron triangle</title>
      <desc id="iron-triangle-desc">A triangle with scope at the top, cost at the lower left, time at the lower right, and quality in the middle.</desc>
      <polygon points="320,82 86,388 554,388" fill="#38bdf8" stroke="#0ea5e9" stroke-width="8" />
      <line x1="320" y1="248" x2="320" y2="148" stroke="#1f2933" stroke-width="5" stroke-linecap="round" />
      <polyline points="306,164 320,148 334,164" fill="none" stroke="#1f2933" stroke-width="5" stroke-linecap="round" stroke-linejoin="round" />
      <line x1="284" y1="278" x2="174" y2="342" stroke="#1f2933" stroke-width="5" stroke-linecap="round" />
      <polyline points="195,342 174,342 185,324" fill="none" stroke="#1f2933" stroke-width="5" stroke-linecap="round" stroke-linejoin="round" />
      <line x1="356" y1="278" x2="466" y2="342" stroke="#1f2933" stroke-width="5" stroke-linecap="round" />
      <polyline points="455,324 466,342 445,342" fill="none" stroke="#1f2933" stroke-width="5" stroke-linecap="round" stroke-linejoin="round" />
      <text x="320" y="242" text-anchor="middle" fill="#1f4f82" font-size="44" font-weight="800">Quality</text>
      <text x="320" y="38" text-anchor="middle" fill="#1f2933" font-size="30" font-weight="800">Scope</text>
      <text x="320" y="66" text-anchor="middle" fill="#586574" font-size="20">features, functionality</text>
      <text x="110" y="424" text-anchor="middle" fill="#1f2933" font-size="30" font-weight="800">Cost</text>
      <text x="110" y="448" text-anchor="middle" fill="#586574" font-size="20">resources, budget</text>
      <text x="530" y="424" text-anchor="middle" fill="#1f2933" font-size="30" font-weight="800">Time</text>
      <text x="530" y="448" text-anchor="middle" fill="#586574" font-size="20">schedule</text>
    </svg>

    <div class="constraint-slider-board" aria-label="Cost scope and time priority sliders">
      <p class="constraint-slider-title">Trade-off sliders</p>
      <div class="constraint-slider-grid">
        <div class="constraint-slider">
          <span>cheap</span>
          <div class="constraint-track" aria-hidden="true"></div>
          <span>expensive</span>
          <p class="constraint-name">Cost</p>
        </div>
        <div class="constraint-slider">
          <span>more</span>
          <div class="constraint-track" aria-hidden="true"></div>
          <span>less</span>
          <p class="constraint-name">Scope</p>
        </div>
        <div class="constraint-slider">
          <span>fast</span>
          <div class="constraint-track" aria-hidden="true"></div>
          <span>slow</span>
          <p class="constraint-name">Time</p>
        </div>
      </div>
    </div>
  </div>
</figure>

As a memory cue: cheap, fast, and full-featured are all desirable, but it is hard to maximize all three at once. If the customer wants more scope, the project may need more time, more budget, or a reduction in quality risk. If the timeline gets shorter, the project may need more resources, reduced scope, or a quality trade-off.

| Constraint | What it means | Common pressure |
| --- | --- | --- |
| Scope | Features, functionality, and deliverables. | More scope usually requires more time, more cost, or both. |
| Cost | Budget, people, tools, and other resources. | Lower cost may limit scope, speed, or quality. |
| Time | Schedule and deadlines. | Less time may require reduced scope, more cost, or higher quality risk. |

Key takeaways:

- A constraint is a limiting factor that can affect project success.
- Cost, time, and scope form the triple constraint, also known as the iron triangle.
- If one constraint changes, the others may need to change to compensate; otherwise quality can suffer.
- Delivering less scope quickly and cheaply aligns well with Agile's MVP idea.
- The project manager should help stakeholders understand that these constraints need to stay balanced.

<p class="study-note"><strong>Exam cue:</strong> when one part of the triple constraint changes, expect an impact on at least one other part. Scope, cost, and time trade-offs affect quality.</p>

## Gather Requirements

Requirements are gathered from stakeholders. The project team may use a wide variety of data-gathering techniques, such as interviews, surveys, workshops, observation, document review, and questionnaires.

The stakeholder register and stakeholder assessment help the team decide whose input should be prioritized. For example, stakeholders with high power, influence, or impact on acceptance may need extra attention during requirements gathering.

Not every requirement gathered will necessarily be included in the project. Requirements still need to be analyzed, prioritized, approved, and controlled through scope and change processes.

```text
Stakeholders
  |
  v
Requirements gathered
  |
  v
Requirements Traceability Matrix
  |
  v
Scope statement, WBS deliverables, and test criteria
```

A Requirements Traceability Matrix (RTM) tracks each requirement from its source through to the work and testing that prove it has been satisfied.

| RTM field | Why it matters |
| --- | --- |
| ID | Gives each requirement a unique reference. |
| Description | States what is being requested. |
| Requestor | Shows who asked for the requirement. |
| Business justification | Explains why the requirement matters. |
| Status | Tracks whether it is proposed, approved, deferred, rejected, or complete. |
| Test criteria | Defines how the team will know the requirement has been met. |
| WBS deliverables | Links the requirement to the work or deliverable that satisfies it. |
| Comments | Captures notes, assumptions, or decisions. |

<p class="study-note"><strong>Exam cue:</strong> requirements gathering collects stakeholder input, but it does not automatically make every request part of the project scope. The RTM helps trace approved requirements from requestor and business need to deliverables and tests.</p>

## Detailed Scope Statement

One important planning activity is developing a detailed scope statement. The scope statement officially declares what is going to be done.

It describes the major deliverables and any exclusions, so the project team and stakeholders understand what is included and what is not included.

```text
Scope Statement
  |
  |-- What work will be done
  |-- Major deliverables
  |-- Boundaries and exclusions
  |-- Basis for controlling scope changes
```

A good scope statement helps prevent misunderstandings and scope creep. If someone asks for extra work later, the team can compare the request against the approved scope statement and decide whether it belongs in the project or needs formal change control.

| Scope statement element | Purpose |
| --- | --- |
| Work to be done | Clarifies what the project team is expected to deliver. |
| Major deliverables | Lists the important outputs or results. |
| Exclusions | Makes clear what is outside the project. |
| Boundaries | Helps the team decide whether later requests are in scope or out of scope. |

<p class="study-note"><strong>Exam cue:</strong> the scope statement says what will be done, what major deliverables are expected, and what is excluded.</p>

## Work Breakdown Structure

A Work Breakdown Structure (WBS) breaks the project scope into smaller, manageable deliverable pieces. It is a hierarchical view of the project work, starting with the overall project and decomposing it into major deliverables, then smaller work packages.

```text
TV Studio Upgrade
  |
  |-- Lighting
  |     |-- Power Cabling
  |     |-- DMX Distribution
  |     |-- Plot Software
  |
  |-- Cameras
  |
  |-- Staging
```

The lowest-level pieces are usually called work packages. Work packages should represent deliverables or outputs, not day-to-day activities. For example, "Power Cabling" can be a deliverable work package; "meet with electrician" is an activity that may support that work package.

| WBS idea | What to remember |
| --- | --- |
| Hierarchical | The project is decomposed from broad deliverables into smaller pieces. |
| Deliverable-oriented | The WBS focuses on what will be produced, not every task on the schedule. |
| Work packages | The lowest manageable pieces of work in the WBS. |
| WBS dictionary | Provides supporting detail about each WBS element or work package. |
| Scope baseline | The approved scope statement, WBS, and WBS dictionary together form the scope baseline. |

Benefits of the WBS include:

- Provides a clear picture of what needs to be done.
- Acts as a communication tool for the project team and stakeholders.
- Reduces the risk of missing important work.
- Encourages transparency and accountability.
- Helps track the impact of issues against affected deliverables.
- Provides input to the project schedule.

The WBS does not list every schedule activity by itself. Instead, it gives the team a deliverable-based structure that can later be used to define activities, estimate effort, assign resources, and build the schedule.

<p class="study-note"><strong>Exam cue:</strong> WBS work packages are deliverables, not activities. Activities come later when the team builds the schedule.</p>

## Units Of Work

Not all units of work are equal. Some are large and need to be decomposed further; others are small enough to estimate, assign, and track.

The way a team defines units of work depends on the project approach:

| Approach | How units of work are defined |
| --- | --- |
| Agile | The product backlog helps define and prioritize units of work, often as user stories or backlog items. |
| Predictive / waterfall | Major deliverables from the scope statement are decomposed into WBS work packages. |

In predictive projects, the WBS shows a hierarchy of deliverables and work packages. The WBS dictionary supports that structure by providing more detail about each WBS element or work package.

The scope statement, WBS, and WBS dictionary together form the scope baseline once approved.

<p class="study-note"><strong>Exam cue:</strong> Agile units of work usually live in the product backlog. Predictive units of work are decomposed from scope statement deliverables into WBS work packages.</p>

## Requirements To Scope Baseline

Product and project requirements are gathered from stakeholders. The final approved requirements are then used to create detailed descriptions of both the product and the project work.

```text
Stakeholder input
  |
  v
Product and project requirements
  |
  v
Requirements Traceability Matrix
  |
  v
Detailed Scope Statement
  |
  v
Scope Baseline
```

The scope statement includes the product and project descriptions, major deliverables, and any exclusions. It may be elaborated throughout initiation and planning as the team learns more and decisions become more detailed.

Once the detailed scope statement is approved, it becomes part of the scope baseline along with the WBS and WBS dictionary. After that point, changes are tightly controlled through formal change control.

| Step | Key purpose |
| --- | --- |
| Gather requirements | Collect product and project needs from stakeholders. |
| Document requirements | Track requirements in an RTM so they can be traced to deliverables and tests. |
| Select final requirements | Decide which requirements belong in the project. |
| Create the scope statement | Describe the project, product, major deliverables, and exclusions. |
| Approve the scope baseline | Lock the approved scope package for comparison and change control. |

<p class="study-note"><strong>Exam cue:</strong> gathered requirements feed the scope statement. The approved scope statement becomes part of the scope baseline, and changes after approval require formal control.</p>

## Scope Change Control

Once the scope baseline has been approved, scope changes should not be slipped into the project casually. In a predictive or waterfall environment, the project manager should remind stakeholders that only approved changes will be incorporated.

The scope baseline is the approved version of the scope statement, WBS, and WBS dictionary. It can be changed, but only through formal change control. Without that control, the project can suffer scope creep.

Scope creep is the uncontrolled expansion of product or project scope without matching adjustments to time, cost, or resources. Even a small change can create knock-on effects across schedule, budget, staffing, risk, quality, testing, and communications.

```text
Approved Scope Baseline
  |
  v
Change requested
  |
  v
Impact assessed
  |
  v
Approved or denied
  |
  v
Plan updated, change implemented, result validated
```

### Formal Change Control Process

| Step | What happens |
| --- | --- |
| 1. Create or receive the change request | Anyone associated with the project may submit a change request. It should be written and explain the reason and justification for the change. |
| 2. Log the request | Record the request in the change request log so it can be tracked. |
| 3. Preliminary review | Talk with the project team and subject matter experts to decide whether the change appears feasible. |
| 4. Assess impact | Review the likely impact on scope, schedule, cost, resources, skills, risk, testing, regression work, benefits, and the product itself. |
| 5. Document the recommendation | Record the assessment findings and recommendation. |
| 6. Determine decision makers | Identify who has authority to approve or deny the change. Smaller changes may be approved by the project manager; larger changes may need the sponsor or Change Control Board. |
| 7. Escalate to the CCB if required | A Change Control Board is a group with authority to review, approve, or deny changes. |
| 8. Document and communicate status | Update the request status, decision, and reason for the decision, then communicate it to the right stakeholders. |
| 9. Update the project plan | If approved, update affected components such as the scope statement, schedule, budget, risk register, communications plan, or other subsidiary plans. |
| 10. Implement the change | Complete the approved change. |
| 11. Validate implementation | Confirm that the implemented change meets the requirements of the original change request. |
| 12. Communicate deployment | Tell stakeholders that the change has been deployed, often through normal project status communications. |

The change request log is the tracking document for change requests.

| Log field | Purpose |
| --- | --- |
| ID | Gives the request a unique identifier. |
| Name of requestor | Shows who submitted the request. |
| Description of request | Explains what is being requested. |
| Status | Tracks where the request is in the process. |
| Approved / denied | Records the decision. |
| Notes or reason | Captures the reason for the decision and any follow-up information. |

Impact assessment is where the team spends real thinking time. Useful questions include:

- What other parts of the project or product would this change affect?
- Do we have the skills and resources to implement it?
- What regression testing or rollback planning is needed?
- Does this change alter the risk assessment?
- Do the benefits outweigh the costs?

In Agile environments, change is expected and usually handled through backlog refinement, reprioritization, and iteration planning rather than the same heavyweight formal process. Predictive projects rely more heavily on formal change control because the approved scope baseline is used as the comparison point for actual results.

<p class="study-note"><strong>Exam cue:</strong> predictive scope changes go through formal change control. Scope creep means uncontrolled scope growth without adjusting time, cost, or resources.</p>

## Project Management Plan Key Takeaways

The project management plan is the main output of project planning activities. It defines how the project will be executed, monitored and controlled, and closed.

The project management plan is usually not just one small document. It can contain many subsidiary plans, such as:

- Change Management Plan
- Communications Management Plan
- Risk Management Plan
- Scope Management Plan
- Schedule Management Plan
- Cost Management Plan

It also includes project baselines. Baselines are fixed reference points used to measure progress and compare actual performance against the approved plan.

Common baselines include:

| Baseline | What it measures |
| --- | --- |
| Scope baseline | The approved scope statement, WBS, and WBS dictionary used to compare planned scope against actual results. |
| Schedule baseline | The approved timeline used to compare planned progress against actual progress. |
| Cost baseline | The approved budget used to compare planned spending against actual spending. |

```text
Project Management Plan
  |
  |-- Subsidiary plans: change, communications, risk, scope, schedule, cost
  |
  |-- Baselines: scope, schedule, cost
```

<p class="study-note"><strong>Exam cue:</strong> subsidiary plans explain how areas will be managed; baselines are approved reference points for measuring progress.</p>
