# Week 1 Deliverables — IntelliCredit Corporate Loan Risk Assessment-(Multi-Agent)

## What we froze this week

1. Use case structured spec (Goal, boundaries, user types, conversations)
2. Agent workflow state machine + Mermaid diagram
3. Tool list + JSON schemas (extract_entities, compare_documents, compute_adjusted_total)
4. Tool fixtures (sample inputs/outputs)5) Prompts (system, tool-use, safety policy)6) Test scripts + prompts + evaluation rubric

## Assumptions in Week 1-

Tolerance baseline: 2% (user-confirmed)- Escalation threshold: INR 50,000- Agent does NOT execute payments or send emails automatically.

## What starts in Week 2-

Implement tools as local Python functions- Add unit tests for each tool- Create sample KB/policy file as local reference data- Start integrating the single agent loop (Week 3)
