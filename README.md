# Goal-First Tracking System for Research Management

## Overview

This document outlines a **goal-first tracking methodology** for managing research teams at HAAG. The system shifts focus from individual researcher contributions to project goal achievement, using Slack Lists (Kanban) as the primary tracking tool.

## The Paradigm Shift

### Traditional Approach (Researcher-First)
- Meetings focus on what each person accomplished
- Individual tasks are the primary unit of tracking
- Goal progress is a secondary concern

### Goal-First Approach (Proposed)
- Meetings focus on initiative progress toward goals
- Individual contributions emerge naturally from goal discussions
- Primary questions: "Are we closer to our goal today than yesterday?" and "Are we moving fast enough to meet our deadlines?"

---

## Work Organization Framework

### Hierarchy of Work

**Initiatives** → **Goals** → **Tasks**

#### 1. Initiatives
What you want to achieve during a semester or across multiple semesters. These are the high-level outcomes that define success for your research team.

**Examples:**
- Publish paper
- Speak at conference
- Devise a novel 3D generative model architecture

#### 2. Goals
Deliverables that, when completed, provide an end product that clearly drives you closer to completing an Initiative. Goals are concrete, measurable outcomes.

**Examples:**
- Close the chamfer distance to an acceptable number for publishing
- Submit a test paper to understand publication requirements
- Complete literature review of existing architectures
- Investigate alternative loss functions for improved convergence (investigation/spike work)

**Rule:** Each Goal must logically connect to an Initiative. If you cannot draw a clear line from Goal to Initiative, reconsider the Goal.

#### 3. Tasks
Smaller units of work done to achieve a Goal. These are the lowest priority in this framework and should be your lowest concern.

**Important Note:** In the previous researcher-first paradigm, Tasks were often the first thing tracked and the main metric of progress. In goal-first tracking, Tasks are de-emphasized. 

**We are research-focused, not researcher-focused.** The assumption is that all researchers are successfully fulfilling their duties. Only when Goal tracking begins to falter should we examine individual researcher contributions. Focus on whether Goals are being achieved, not on tracking individual Tasks.

---

## Tracking Mechanism: Slack Lists (Kanban)

**Test Kanban Board:** [View Board](https://humanaugmente-e7j6563.slack.com/lists/T071VTSFLCV/F0AGD5C76DR?view_id=View0AG45LAN4X)

### Board Columns
1. **Not Started** - Planned work not yet started
2. **In Progress** - Active work items
3. **Completed** - Work finished by researchers (optional separate column)
4. **Verified** - Completed work verified by professor or advisor
5. **Blocked** - Work items that cannot proceed due to dependencies or obstacles

**Note:** "Completed" and "Verified" can be a single column or two separate columns depending on team preference. If separate, managers may move items to "Completed" when work is done, and professors/computational advisors move items to "Verified" as they are best qualified to validate the work.

### Workflow
1. Initiatives and Goals are planned and loaded onto the board
2. Goals are assigned to researchers
3. Researchers move Goals to "In Progress" when work begins
4. Upon completion, Goals move to "Completed" (or directly to "Verified" if using a single column)
5. Professors/computational advisors verify and move to "Verified"
6. If work is blocked, items move to "Blocked" with notes explaining the obstacle

**Note:** Tasks may be tracked informally but are not the primary focus of the Kanban board. Researchers can check off Tasks themselves when they feel they have completed their work.

### Organizing Information
**The main responsibility for getting unorganized information into a clear Kanban setting lies on the manager.** This includes:
- Creating and structuring Goals on the board
- Adding links, notes, and comments to Goals
- Connecting important Slack channel threads to relevant Goals in the comments section
- Maintaining board organization and clarity

### Goal Labeling
Goal titles can start with labels to differentiate size, scope, and purpose:
- **[Epic]** - Large, multi-week deliverables
- **[Goal]** - Standard deliverables (days to weeks)
- **[Spike]** - Investigation or research work
- Other labels as needed for your team

### Adding Context
Links, notes, and comments can all be added to Goals. Important threads within the main Slack channel should be connected to Tasks/Goals/Spikes in the comments section to maintain context and traceability.

---

## Operational Procedures

### Weekly/Bi-Weekly Sync (15 minutes)
**Attendees:** Manager, TAs, Advisors

**Agenda:**
- Review Initiative and Goal progress
- Adjust, remove, or reorganize Goals as needed
- Identify blockers or risks to Initiative achievement
- Focus on goal velocity, not individual task completion

### Asynchronous Work
Most operational tracking happens asynchronously through the Kanban board. Team members update their work status independently.

### Manager Responsibilities
- **Organize unorganized information into a clear Kanban setting** (primary responsibility)
- Monitor board progress toward Initiatives
- Facilitate sync meetings
- Escalate blockers that threaten Initiative or Goal achievement
- Track whether the team is moving fast enough to meet deadlines
- De-emphasize individual Task tracking in favor of Goal completion

---

## Validation & Success Metrics

### Data Collection
Compare goal-first tracking groups against control groups using researcher-first tracking:

**Control Groups:**
- Historical data from teams tracking researcher contributions
- Current teams using traditional methods

**Experimental Groups:**
- Teams implementing goal-first tracking this semester

### Key Metrics
- **Goal Achievement Rate:** Percentage of goals met on time
- **Manager Intervention:** How often managers helped teams meet goals
- **Pain Points:** Identified challenges in each approach
- **Velocity:** Speed of progress toward goals

### Success Criteria
The goal-first approach succeeds if experimental groups show:
- Higher goal achievement rates
- Fewer missed deadlines
- More effective manager interventions focused on goal obstacles

---

## Intended Audience

- **Research Team Managers**
- **Professors**
- **Computational Advisors**

---

## Example: 3D Generative Models Research Team

**Initiative:** Publish paper on novel 3D generative model architecture

**Sample Goals:**
- Close chamfer distance to acceptable publishing threshold
- Complete literature review and related work section
- Implement and validate architecture variant A
- Submit test paper to target conference

**Sample Tasks (tracked informally, not primary focus):**
- Run experiment batch #3
- Update training script with new hyperparameters
- Draft methodology section

---

## Getting Started

1. Define your semester Initiative(s)
2. Break down each Initiative into concrete Goals (deliverables)
3. Set up your Slack Lists Kanban board
4. Load Initiatives and Goals onto the board
5. Schedule your first 15-minute sync meeting with Computational Advisors/TAs, Professors, and Managers
6. Begin tracking progress toward Goals and Initiatives, not individual Tasks

---

## Questions or Feedback?

This is an experimental initiative. Your feedback will help refine the approach for future research teams.
