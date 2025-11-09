---
description: Multi-agent orchestration với structured output và comprehensive analysis
subtask: true
temperature: 0.3
---

# 🤖 Multi-Agent Orchestration Command

**Task to Execute**: $ARGUMENTS

---

## 📋 PHASE 1: TASK ANALYSIS & DECOMPOSITION

### 1.1 Task Understanding
**Objective**: $ARGUMENTS

**Complexity Assessment**:
- [ ] Simple (1 agent sufficient)
- [ ] Medium (2-3 agents recommended)
- [ ] Complex (4+ agents required)
- [ ] High Priority (parallel execution needed)

**Initial Analysis**:
- **Scope**: [Define clear boundaries]
- **Requirements**: [List key requirements]
- **Constraints**: [Technical/time/resource limitations]
- **Success Criteria**: [How to measure completion]

### 1.2 Sub-Task Breakdown
Break down "$ARGUMENTS" into concrete, actionable sub-tasks:

```yaml
subtasks:
  1:
    name: "[Sub-task name]"
    description: "[Detailed description]"
    estimated_effort: "[S/M/L]"
    dependencies: "[None or list other sub-tasks]"
    
  2:
    name: "[Sub-task name]"
    description: "[Detailed description]"
    estimated_effort: "[S/M/L]"
    dependencies: "[Dependencies if any]"
```

### 1.3 Dependency Mapping
```
[Visualize dependencies - e.g.:]
Task 1 → Task 2 → Task 5
      ↘ Task 3 → Task 4 ↗
```

**Execution Strategy**: 
- [ ] Sequential (tasks must be done in order)
- [ ] Parallel (tasks can run simultaneously)
- [ ] Hybrid (mix of sequential and parallel)

---

## 🎯 PHASE 2: AGENT ASSIGNMENT & ROLE DEFINITION

### 2.1 Agent Selection Matrix

| Sub-Task | Assigned Agent | Rationale | Priority |
|----------|----------------|-----------|----------|
| [Task 1] | @[agent-name] | [Why this agent?] | High/Med/Low |
| [Task 2] | @[agent-name] | [Why this agent?] | High/Med/Low |
| [Task 3] | @[agent-name] | [Why this agent?] | High/Med/Low |

### 2.2 Available Agent Roles

**Planning & Architecture**:
- `@planner-researcher` - Strategic planning, research
- `@planning-strategist` - Implementation planning
- `@rest-api-architect` - API design, OpenAPI specs
- `@refactor-planner` - Refactoring strategies

**Development**:
- `@software-engineer` - General development
- `@backend-developer` - Backend/API implementation
- `@python-pro` / `@golang-pro` / `@typescript-expert` - Language-specific
- `@mobile-developer` - React Native/Flutter

**Quality & Security**:
- `@tester` - Test creation, QA
- `@code-reviewer` - Code review, best practices
- `@security-auditor` - Security analysis
- `@performance-engineer` - Performance optimization

**Documentation & Support**:
- `@documentation-specialist` - Technical docs
- `@api-documenter` - API documentation
- `@technical-documentation-specialist` - User guides

### 2.3 Resource Allocation
```yaml
execution_plan:
  parallel_groups:
    group_1: [agent1, agent2]  # Can run simultaneously
    group_2: [agent3]           # Runs after group_1
  estimated_duration: "[X hours/days]"
  risk_factors: "[Potential blockers]"
```

---

## ⚡ PHASE 3: ORCHESTRATED EXECUTION

**Execution Mode**: [Sequential/Parallel/Hybrid]

---

### 🔷 Agent 1: [ROLE NAME]
**Agent**: @[agent-name]  
**Task**: [Specific task description]  
**Input Context**: [What this agent receives]

#### Execution:
```
[As this agent, I will...]

[Detailed output/work product]

[Key decisions made]
```

#### Deliverables:
- ✅ [Deliverable 1]
- ✅ [Deliverable 2]
- ✅ [Deliverable 3]

#### Output Artifacts:
```
[Code/files/documents produced]
```

---

### 🔷 Agent 2: [ROLE NAME]
**Agent**: @[agent-name]  
**Task**: [Specific task description]  
**Dependencies**: [What needs to be completed first]  
**Input Context**: [Receives output from Agent 1]

#### Execution:
```
[As this agent, I will...]

[Detailed output/work product]

[Key decisions made]
```

#### Deliverables:
- ✅ [Deliverable 1]
- ✅ [Deliverable 2]

#### Output Artifacts:
```
[Code/files/documents produced]
```

---

### 🔷 Agent 3: [ROLE NAME]
**Agent**: @[agent-name]  
**Task**: [Specific task description]  
**Input Context**: [Combined context from previous agents]

#### Execution:
```
[As this agent, I will...]

[Detailed output/work product]
```

#### Deliverables:
- ✅ [Deliverable 1]
- ✅ [Deliverable 2]

---

[Continue for all assigned agents...]

---

## 🔄 PHASE 4: INTEGRATION & SYNTHESIS

### 4.1 Cross-Agent Consistency Check
**Validation Points**:
- [ ] All deliverables completed
- [ ] No conflicting decisions between agents
- [ ] Consistent naming/coding conventions
- [ ] All dependencies satisfied
- [ ] Integration points work correctly

### 4.2 Conflict Resolution
**Identified Conflicts**: [List any inconsistencies]  
**Resolution Strategy**: [How conflicts were resolved]

### 4.3 Integrated Solution
```
[Synthesized final output combining all agent work]

[Show how different pieces fit together]
```

---

## ✅ PHASE 5: QUALITY ASSURANCE & VERIFICATION

### 5.1 Completeness Checklist
- [ ] All sub-tasks completed
- [ ] All requirements addressed
- [ ] Success criteria met
- [ ] Edge cases considered
- [ ] Error handling implemented
- [ ] Documentation provided
- [ ] Tests included (if applicable)

### 5.2 Quality Metrics

| Metric | Target | Actual | Status |
|--------|--------|--------|--------|
| Requirements Coverage | 100% | [%] | ✅/⚠️/❌ |
| Code Quality | High | [Rating] | ✅/⚠️/❌ |
| Test Coverage | >80% | [%] | ✅/⚠️/❌ |
| Documentation | Complete | [Status] | ✅/⚠️/❌ |

### 5.3 Risk Assessment
**Potential Issues**:
- ⚠️ [Risk 1]: [Mitigation strategy]
- ⚠️ [Risk 2]: [Mitigation strategy]

### 5.4 Recommendations
**Immediate Actions**:
1. [Action 1]
2. [Action 2]

**Future Improvements**:
1. [Improvement 1]
2. [Improvement 2]

---

## 📊 PHASE 6: FINAL DELIVERABLES & SUMMARY

### 6.1 Complete Solution Package

**Primary Deliverables**:
```
[Main files/code/documents]
```

**Supporting Artifacts**:
- Documentation: [List files]
- Tests: [List test files]
- Configuration: [Config files]
- Scripts: [Utility scripts]

### 6.2 Implementation Guide
**Step-by-step deployment/usage**:
1. [Step 1]
2. [Step 2]
3. [Step 3]

### 6.3 Agent Coordination Summary

**Agents Involved**: [Total count]

| Agent | Tasks Completed | Key Contributions | Duration |
|-------|----------------|-------------------|----------|
| @[agent1] | [N] | [Summary] | [Time] |
| @[agent2] | [N] | [Summary] | [Time] |
| @[agent3] | [N] | [Summary] | [Time] |

**Coordination Metrics**:
- **Total Sub-tasks**: [N]
- **Execution Pattern**: [Sequential/Parallel/Hybrid]
- **Estimated Time**: [Duration]
- **Actual Time**: [Duration]
- **Efficiency**: [%]

### 6.4 Success Validation
✅ **Task Completed**: $ARGUMENTS

**Achievement Summary**:
- ✅ [Major achievement 1]
- ✅ [Major achievement 2]
- ✅ [Major achievement 3]

**Lessons Learned**:
- 💡 [Insight 1]
- 💡 [Insight 2]

---

## 🎯 EXECUTION PRINCIPLES

Throughout this orchestration, I will adhere to:

1. **Clear Communication**: Each agent's input/output explicitly documented
2. **Structured Output**: Consistent format across all phases
3. **Quality Focus**: Verification at each stage
4. **Context Preservation**: Maintain continuity between agents
5. **Comprehensive Coverage**: Address all aspects of the task
6. **Actionable Results**: Provide ready-to-use solutions

---

**🚀 Now beginning orchestrated execution for**: "$ARGUMENTS"
