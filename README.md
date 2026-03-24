# Life

Personal goal tracking and reflection system, managed with Claude Code.

## Structure

- **goals/** — Active goals (strategy: why, what done looks like)
- **reflections/daily/** — End-of-day reflections (one per day)
- **reflections/weekly/** — Weekly reviews (one per week)
- **check-ins/** — Hourly check-in logs (JSONL, one file per day)
- **.state/** — Running context for the reflection coach

## GitHub Project

One **Life** project board holds everything. Issues are tasks/milestones with checkboxes.
Labels (`health`, `career`, `learning`, `relationships`) filter by goal area.
Board columns show what's active vs. backlog.

## Daily Workflow

```bash
# Morning: plan the day
/life-plan

# During the day: hourly check-ins
/loop 1h /life-reflect check-in

# Evening: review the day
/life-reflect daily

# Friday: review the week
/life-reflect weekly
```
