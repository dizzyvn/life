# Life

Personal goal tracking and reflection system, managed with Claude Code.

## Structure

- **goals/** — Active goals (strategy: why, what done looks like)
- **reflections/daily/** — End-of-day reflections (one per day)
- **reflections/weekly/** — Weekly reviews (one per week)
- **check-ins/** — Hourly check-in logs (JSONL, one file per day)
- **.state/** — Running context for the reflection coach

## GitHub Projects

| Project | Type | Purpose |
|---------|------|---------|
| **AI Course Prep** | Focused Goal | #1 priority this month — April deadline |
| **Get in Shape** | Focused Goal | Secondary focus — start gym habit |
| **Life** | Catch-all | Everything else: Trusted AI strategy, relationships, one-off tasks |

**Principle:** Only 2-3 Focused Goal Projects active at any time. Everything else lives in Life until it deserves deep attention.

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
