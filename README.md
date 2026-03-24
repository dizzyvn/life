# Life

Personal goal tracking and reflection system, managed with Claude Code.

## Structure

- **goals/** — Active goals and archived ones
- **reflections/daily/** — End-of-day reflections (one per day)
- **reflections/weekly/** — Weekly reviews (one per week)
- **check-ins/** — Hourly check-in logs (JSONL, one file per day)
- **.state/** — Running context for the reflection coach

## Usage

```bash
# Quick hourly check-in
/reflect check-in

# Recurring hourly check-ins
/loop 1h /reflect check-in

# End of day review
/reflect daily

# Weekly review
/reflect weekly
```

## GitHub Issues

Major goals are also tracked as GitHub Issues with labels:
`health`, `career`, `finance`, `learning`, `relationships`, `creative`
