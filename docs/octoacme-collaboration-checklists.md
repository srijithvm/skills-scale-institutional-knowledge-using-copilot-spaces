# Cross-Functional Collaboration Checklists

This document provides detailed checklists to ensure all roles are properly engaged and informed at critical project touchpoints. Use these checklists to maintain clarity, accountability, and seamless collaboration.

---

## Project Kickoff Checklist

**Owner**: Project Manager  
**Timeline**: Week 1 of project  
**Participants**: All project roles

### Pre-Kickoff (Lead Coordinator: Project Manager)
- [ ] Schedule kickoff meeting with all roles (min 2 hours)
- [ ] Share project charter and objectives document 48 hours in advance
- [ ] Define project governance, RACI matrix, and decision authority
- [ ] Prepare communication plan (meeting frequency, channels, escalation paths)
- [ ] Brief Product Manager on stakeholder context and priorities

### During Kickoff
- [ ] **Project Manager**: Present project overview, objectives, and success metrics
- [ ] **Product Manager**: Present user context, business drivers, and feature priorities
- [ ] **UX Researcher**: Share user research and personas (if available)
- [ ] **Developers**: Ask clarifying questions, identify technical unknowns
- [ ] **QA Lead**: Define quality standards and testing approach
- [ ] **Change Manager**: Explain change control process and procedures
- [ ] **Release Coordinator**: Outline release approach and dependencies
- [ ] **All Roles**: Establish working norms and communication preferences
- [ ] **Project Manager**: Confirm RACI matrix and role clarity

### Post-Kickoff (Lead: Project Manager)
- [ ] Send kickoff minutes and agreed decisions to all roles
- [ ] Confirm next meeting schedule (standups, planning, status reviews)
- [ ] Share project board, wiki, and documentation locations
- [ ] Follow up with individuals who need clarity on expectations
- [ ] Track action items from kickoff

---

## Planning Phase Collaboration Checklist

**Owner**: Project Manager  
**Timeline**: Weeks 2-4 of project  
**Key Dependencies**: Product Manager, Developers, QA Lead, Release Coordinator

### Requirements & Scope Planning (Lead: Product Manager)
- [ ] Document detailed requirements with acceptance criteria
- [ ] **QA Lead**: Review and validate acceptance criteria
- [ ] **Developers**: Assess feasibility, ask clarifying questions
- [ ] **Change Manager**: Identify potential scope change points
- [ ] **Product Manager**: Finalize requirements and get stakeholder sign-off

### Technical Planning (Lead: Developers with Project Manager oversight)
- [ ] **Developers**: Create technical design document
- [ ] **QA Lead**: Review design for testability and quality risks
- [ ] **Release Coordinator**: Identify deployment and infrastructure dependencies
- [ ] **Project Manager**: Identify technical risks and mitigation strategies
- [ ] **All Technical Roles**: Identify dependencies and integration points

### Quality Planning (Lead: QA Lead)
- [ ] Define quality standards and acceptance criteria clarity
- [ ] Create test strategy and testing approach
- [ ] **Developers**: Agree on unit testing approach and coverage targets
- [ ] **Project Manager**: Identify testing timeline and resource requirements
- [ ] Define quality gates for different project phases

### Release Planning (Lead: Release Coordinator)
- [ ] Assess release feasibility with Developers and Infrastructure teams
- [ ] **Project Manager**: Align release timing with project schedule
- [ ] Create release plan with milestones and go/no-go criteria
- [ ] Identify deployment dependencies and infrastructure needs
- [ ] Plan rollback and contingency scenarios

### Risk Identification & Management (Lead: Project Manager)
- [ ] Conduct risk assessment with all roles
  - [ ] **Developers**: Technical and capacity risks
  - [ ] **QA Lead**: Quality and timeline risks
  - [ ] **UX Researcher**: User experience and adoption risks
  - [ ] **Release Coordinator**: Deployment and infrastructure risks
- [ ] Document risk register with mitigation strategies
- [ ] Assign risk owners and review frequency

### Planning Review (Lead: Project Manager)
- [ ] **All Roles**: Review integrated plan for completeness
- [ ] Confirm resource availability and capacity
- [ ] Validate timeline, budget, and quality expectations
- [ ] Get stakeholder sign-off on plan
- [ ] Document assumptions and constraints

---

## Weekly Execution Standup Checklist

**Owner**: Project Manager  
**Frequency**: Weekly (or daily during critical phases)  
**Duration**: 30-60 minutes  
**Participants**: All project roles (asynchronous option available)

### Pre-Standup (Project Manager)
- [ ] Schedule standup at consistent time/location
- [ ] Send agenda 24 hours in advance
- [ ] Review previous week action items
- [ ] Identify agenda topics from risks, issues, changes

### Standup Agenda
- [ ] **Each Role** provides update:
  - What was completed last week
  - What is planned for this week
  - Any blockers, risks, or dependencies
- [ ] **Blockers**: Project Manager facilitates resolution
- [ ] **Risks**: Flag any emerging risks; QA Lead highlights quality concerns
- [ ] **Changes**: Change Manager reports on status of approved changes
- [ ] **Progress Metrics**: Review against timeline and quality targets
- [ ] **Next Steps**: Assign action items and owners

### Post-Standup (Project Manager)
- [ ] Send standup summary to all stakeholders
- [ ] Track action items and follow up on completion
- [ ] Update project board with status
- [ ] Escalate blockers and risks as needed
- [ ] Prepare for next standup

---

## Quality Gate Review Checklist

**Owner**: QA Lead  
**Timing**: Conducted at defined quality gates (design review, code review, pre-release)  
**Participants**: QA Lead, Developers, Project Manager, Product Manager (if needed)

### Pre-Gate Review
- [ ] **Developers**: Confirm all work is complete and tested
- [ ] **QA Lead**: Review readiness for quality gate assessment
- [ ] **Project Manager**: Confirm timing aligns with project schedule

### Design Review Quality Gate
- [ ] Requirements traceability confirmed
- [ ] Design quality and standards met
- [ ] Risk assessment complete
- [ ] Test plan prepared and feasible
- [ ] **Decision**: Approved / Requires Changes

### Code Review Quality Gate
- [ ] Code quality standards met (coverage, style, documentation)
- [ ] Unit tests passing and coverage target met
- [ ] Code review completed by peers
- [ ] Security and performance reviewed
- [ ] **Decision**: Approved / Requires Changes

### Pre-Release Quality Gate
- [ ] All acceptance criteria validated
- [ ] No open critical or high-priority defects
- [ ] Test coverage and execution complete
- [ ] Performance and security testing passed
- [ ] Release notes prepared and accurate
- [ ] Rollback plan prepared and tested
- [ ] **QA Lead Decision**: Release Approved / Hold Release

### Gate Gate Resolution (if "Requires Changes")
- [ ] Document specific issues to address
- [ ] Define remediation approach and timeline
- [ ] Assign ownership for fixes
- [ ] Schedule re-review
- [ ] Communicate timeline impact to Project Manager

---

## Change Request Checklist

**Owner**: Change Manager  
**Trigger**: Change request submitted  
**Timeline**: Assess and communicate within 2 business days

### Change Request Intake
- [ ] Document change request in change register
- [ ] Classify change (scope, timeline, quality, process, etc.)
- [ ] Assign priority based on urgency and impact
- [ ] Notify all affected roles of pending change

### Impact Analysis (Lead: Change Manager)
- [ ] **Developers**: Assess technical impact and effort
- [ ] **QA Lead**: Assess quality and testing impact
- [ ] **Project Manager**: Assess timeline and resource impact
- [ ] **Product Manager**: Assess business impact and prioritization
- [ ] **Release Coordinator**: Assess deployment impact (if applicable)
- [ ] **Document**: Change impact assessment with all considerations

### Stakeholder Approval
- [ ] Present change impact to decision authority (typically Product Manager or Sponsor)
- [ ] Communicate approval decision to all roles
- [ ] If approved: schedule implementation; if rejected: document reason

### Approved Change Implementation
- [ ] **Project Manager**: Update project plan to reflect change
- [ ] **Developers**: Incorporate into backlog and schedule
- [ ] **QA Lead**: Update test plans if impacted
- [ ] **Release Coordinator**: Update release plan if needed
- [ ] **Change Manager**: Archive change in change register

---

## Pre-Release Readiness Checklist

**Owner**: Release Coordinator  
**Timing**: 1-2 weeks before planned release  
**Participants**: All roles

### Code & Build Readiness
- [ ] **Developers**: All code merged and committed
- [ ] All acceptance criteria items completed
- [ ] Release branch created and stable
- [ ] Build process tested and working
- [ ] Deployment artifacts prepared

### Quality Sign-Off
- [ ] **QA Lead**: Final quality gate approved
- [ ] No open critical/high defects
- [ ] All test suites passing
- [ ] Performance baseline met
- [ ] Security review completed
- [ ] Accessibility standards verified

### Documentation Complete
- [ ] Release notes drafted and reviewed
- [ ] User documentation updated
- [ ] API documentation updated (if applicable)
- [ ] Deployment runbook prepared and reviewed
- [ ] Rollback procedures documented and tested

### Deployment Planning
- [ ] **Release Coordinator**: Deployment checklist prepared
- [ ] Deployment schedule confirmed with all teams
- [ ] Infrastructure readiness verified
- [ ] Monitoring and alerting configured
- [ ] Incident response procedures ready

### Stakeholder Communication
- [ ] **Change Manager**: Release announcement prepared
- [ ] **Project Manager**: Stakeholder briefing scheduled
- [ ] Go/no-go meeting scheduled
- [ ] Post-release support staffing confirmed
- [ ] User communication prepared

### Go/No-Go Meeting (1-2 days before release)
- [ ] **Release Coordinator**: Review readiness status
- [ ] **QA Lead**: Confirm quality sign-off and any remaining risks
- [ ] **Developers**: Confirm code readiness and hotfix plan
- [ ] **Project Manager**: Confirm stakeholder alignment
- [ ] **All Participants**: Go or No-Go decision

---

## Release Day Coordination Checklist

**Owner**: Release Coordinator  
**Duration**: Throughout deployment window  
**Participants**: Release Coordinator, Developers, QA Lead, Project Manager, Release Support Team

### Pre-Deployment (2 hours before)
- [ ] **All Participants**: Join release war room (in-person or virtual)
- [ ] **Release Coordinator**: Review deployment plan and runbook
- [ ] **Developers**: Final code readiness confirmation
- [ ] **QA Lead**: Testing environment readiness
- [ ] **Infrastructure**: Production environment readiness
- [ ] **Change Manager**: Notify stakeholders of deployment window

### Deployment Execution
- [ ] **Release Coordinator**: Execute deployment steps per runbook
- [ ] **Developers**: Monitor code deployment and services
- [ ] **QA Lead**: Conduct smoke testing and validation
- [ ] **All Participants**: Actively monitor for issues
- [ ] **Release Coordinator**: Document all deployment steps and timing

### Post-Deployment Verification
- [ ] **QA Lead**: Conduct post-deployment validation tests
- [ ] **Developers**: Monitor service health and logs
- [ ] **Infrastructure**: Monitor infrastructure metrics
- [ ] **Release Coordinator**: Confirm deployment complete and stable
- [ ] All participants confirm green status

### Issue Response (if needed)
- [ ] **Severity Assessment**: Quick determination of issue impact
- [ ] **If Minor**: Document issue, schedule for next release
- [ ] **If Major**: Assess rollback vs. hotfix approach
- [ ] **Rollback Decision**: Change Manager and Product Manager approval required
- [ ] **Execution**: Release Coordinator leads rollback or hotfix
- [ ] **Communication**: Project Manager updates stakeholders

### Post-Deployment Wrap-Up
- [ ] **Release Coordinator**: Release closeout meeting (within 24 hours)
- [ ] Release declared successful
- [ ] Production monitoring baseline confirmed
- [ ] Post-release support handoff confirmed
- [ ] Release notes published to users

---

## Post-Release Monitoring Checklist

**Owner**: Release Coordinator (Week 1) → Normal Operations (Ongoing)  
**Duration**: First week intensified, then standard monitoring

### Week 1 Post-Release (Enhanced Monitoring)
- [ ] **Daily Check-Ins**: Release Coordinator leads 15-min standup
- [ ] **Developers**: Monitor error rates, performance metrics, logs
- [ ] **QA Lead**: Execute post-release validation tests daily
- [ ] **Product Manager**: Gather early user feedback
- [ ] **Infrastructure**: Monitor system health and capacity
- [ ] **Project Manager**: Collect stakeholder feedback

### Issue Triage (Ongoing)
- [ ] **Release Coordinator**: Assess reported issues
- [ ] **Severity Classification**:
  - [ ] Critical: Production down, data loss, security - immediate response
  - [ ] High: Major functionality broken - hotfix planned
  - [ ] Medium: Feature works but not as intended - next release or hotfix
  - [ ] Low: Minor issues, no customer impact - backlog
- [ ] **Critical/High Issues**: Escalate to Change Manager for urgent change process

### Success Metrics Review (1-2 weeks after release)
- [ ] **Product Manager**: Compare against success metrics
- [ ] **QA Lead**: Review production stability metrics
- [ ] **Developers**: Analyze error rates and performance
- [ ] **UX Researcher**: Share user feedback and satisfaction metrics
- [ ] **Release Coordinator**: Generate post-release report

### Retrospective (2-3 weeks after release)
- [ ] **Project Manager**: Schedule retrospective meeting
- [ ] **Participants**: All roles attend
- [ ] **What went well**: Celebrate successes
- [ ] **What could improve**: Identify areas for process improvement
- [ ] **Action Items**: Assign improvements for next release
- [ ] **Document**: Capture lessons learned

---

## Retrospective Checklist

**Owner**: Project Manager  
**Timing**: 2-3 weeks after release  
**Duration**: 1.5-2 hours  
**Participants**: All project roles

### Pre-Retrospective
- [ ] Schedule retrospective with all roles
- [ ] Gather data: metrics, issue reports, feedback
- [ ] Share agenda: focus on learning, not blame
- [ ] Collect anonymous feedback if preferred by team

### Retrospective Meeting Agenda

#### 1. Project Overview (15 min)
- [ ] **Project Manager**: Recap project goals and outcomes
- [ ] Review actual vs. planned timeline, scope, quality
- [ ] Share success metrics and user feedback

#### 2. What Went Well (20 min)
- [ ] **Each Role**: Share 2-3 things they're proud of
- [ ] Celebrate successes and strong collaboration
- [ ] Recognize individuals and team contributions
- [ ] Identify practices to repeat in future projects

#### 3. What Could Improve (20 min)
- [ ] **Each Role**: Share 2-3 challenges or improvements
- [ ] Focus on process, not people
- [ ] Identify root causes, not symptoms
- [ ] QA Lead: Quality process improvements
- [ ] Project Manager: Schedule/planning improvements
- [ ] Developers: Technical or workflow improvements
- [ ] Release Coordinator: Deployment improvements

#### 4. Action Items (15 min)
- [ ] **Team**: Prioritize top 3-5 improvements
- [ ] Assign ownership for each improvement
- [ ] Define success criteria and timeline
- [ ] Confirm commitment from owners

#### 5. Close & Commit (10 min)
- [ ] **Project Manager**: Summarize action items
- [ ] **Team**: Confirm commitment to improvements
- [ ] **All**: Thank team for great collaboration
- [ ] Schedule follow-up: when will improvements be implemented?

### Post-Retrospective
- [ ] **Project Manager**: Document retrospective findings and action items
- [ ] Share retrospective summary with stakeholders
- [ ] Track action item completion in next project
- [ ] Use lessons learned for process improvements

---

## Continuous Collaboration Best Practices

### Communication
- [ ] **Transparency**: Share status, risks, decisions with all stakeholders proactively
- [ ] **Clarity**: Use specific language, confirm understanding before decisions
- [ ] **Frequency**: Match communication cadence to project phase and need
- [ ] **Channels**: Use appropriate channels (meetings, written, async) for different topics

### Escalation
- [ ] **Early**: Escalate issues quickly, don't wait for problems to compound
- [ ] **Clear**: Document issue, impact, and recommended action
- [ ] **Empowered**: Give decision-makers the information they need
- [ ] **Documented**: Document decisions and rationale for future reference

### Decision-Making
- [ ] **RACI**: Use RACI matrix to clarify roles in decisions
- [ ] **Data-Driven**: Base decisions on facts, metrics, and analysis
- [ ] **Timely**: Make decisions quickly, revisit if circumstances change
- [ ] **Documented**: Record decisions and rationale in project documentation

### Accountability
- [ ] **Clear Ownership**: Every task and decision has a clear owner
- [ ] **Regular Check-Ins**: Track progress through standups and status meetings
- [ ] **Consequence Clarity**: Understand impact of delays or quality issues
- [ ] **Support**: Provide resources and help when role owners are blocked

### Continuous Improvement
- [ ] **Retrospectives**: Conduct regular retrospectives to learn and improve
- [ ] **Feedback**: Gather feedback from team members on process effectiveness
- [ ] **Metrics**: Track collaboration metrics (issue resolution time, rework, etc.)
- [ ] **Evolution**: Update checklists and processes based on lessons learned
