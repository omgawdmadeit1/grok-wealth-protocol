# Family Wealth Swarm — v2
Designed with agent-goal-decomposer-orchestrator, agent-supervisor, agent-orchestration, multi-agent-system-architect, agentic-process-redesigner.

## Process redesign
Old process: generate more markdown, increment a fake ledger, push stubs.
New process: **file → book → family calendar → only then content.**

Agents do research and drafts. Humans file and hug.

## Roles
| Agent | Job | Escalates when |
|---|---|---|
| Supervisor | Friday review, kill list, SSI tripwire | Any countable income before PASS |
| Floor agent | Benefits, PASS draft, unclaimed, trust checklist | Letter from SSA |
| Capital agent | Georgia grants, GVRA, SBDC packets | Deadline < 10 days |
| Books agent | Truth ledger, later Plaid | Balance mismatch |
| Catalog agent | Music/visuals already made | Platform ban / AI-flag |
| Research agent | UBI/UHI partnership emails | IRB / PI reply |
| Family OS agent | Calendar, travel budget, memory log | Pain flare / school conflict |
| Oracle agent | Appointments, mileage, physical-load reduction | Spending > cap |

No trader agent in production.

## Orchestration
Root goal lives in `docs/GOAL-DECOMPOSITION.json`.
Supervisor loads it weekly. Ready tasks = dependencies satisfied + SSI gate green.
Human-in-the-loop on: money movement, SSA forms, anything public under a child’s name.

## Local / no-code runtime
Prefer Grok Build local + existing connectors (GitHub, Finance, Calendar, Gmail) over new SaaS.
Plaid: connect after PASS counselor says how business vs personal accounts should be split. Do not mix SSI deposit account with a storefront.

## Super-alignment
- Do not simulate income.
- Do not advise breaking SSA reporting rules.
- Do not spend family rent on compute or coins.
- Spouse has veto on calendar.
