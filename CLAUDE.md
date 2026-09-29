# [PROJECT NAME]

Short description of what this system does.

Example:
AI-powered SEO operations system for analyzing, improving, and managing organic search performance using modular agents and focused skills.

---
# Objective

Main goals of the system.

Examples:
- increase organic traffic
- improve conversions
- optimize AI-search visibility
- automate execution workflows
- improve content quality

---
# Architecture

- `/agents`
  → self-contained operational agents

- `/skills`
  → focused capabilities used by agents

- `/skills/*/references`
  → optional context loaded only when needed

- `/workflows`
  → automations, external pipelines, reports, generated outputs
---
# Core Rules

- prioritize real data over assumptions
- avoid generic recommendations
- every insight should lead to a clear action
- do not duplicate responsibilities across agents
- load only relevant context
- preserve factual accuracy and credibility
- use focused skills instead of overloaded instructions

Add project-specific guardrails here only.

---
# Execution Flow

Default workflow:

1. `agent-1`
2. `agent-2`
3. `agent-3`

Example:
1. `seo-analyst`
2. `content-strategist`
3. `content-writer`
4. `content-evaluator`

Do not skip validation steps when quality matters.

---
# Agent Responsibilities

## agent-name
Short description of responsibility.

Example:
Performance analysis and opportunity identification.

---
# Skill Usage

Agents decide when to use skills.
Skills define how execution happens.

Use the most focused skill possible.
---

# Skills

## skill-name
One-line description.

Example:
Analyze SEO data from GSC and GA4 to identify ranking and CTR opportunities.

---
# Workflow Usage

Use `/workflows` for:
- generated outputs

---
# Output Expectations

Prefer:
- concise outputs
- structured tables
- JSON
- actionable recommendations

Avoid:
- generic explanations
- repetitive summaries
- unnecessary context

---

# Progressive Disclosure

Do not load unnecessary files.

Only load:
- relevant agents
- required skills
- necessary references
- relevant workflows

Focused context improves output quality.
