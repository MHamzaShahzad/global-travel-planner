# Global Travel Planner: Claude Skill

A [Claude skill](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) that turns Claude into an elite global travel consultant and tour planner. It designs realistic, visa-aware, budget-optimized trips for any nationality, budget, and travel style.

## What it does

- **Plans around visas.** It checks entry rules for the traveller's specific passport and residence status, including transits, before recommending a route.
- **Builds realistic itineraries.** It accounts for transfers, check-in times, fatigue, opening hours, and seasons, and avoids backtracking.
- **Optimizes the budget** across flights, stays, transport, food, activities, visas, insurance, and a buffer, giving honest ranges rather than invented prices.
- **Personalizes the trip.** Honeymoons, families, luxury, backpacking, religious travel, bleisure, and multi-country trips each get a different plan.
- **Delivers a full plan**: summary, route, day-by-day itinerary, where to stay, transport, budget, entry requirements, tips, and alternatives.

## Structure

```
SKILL.md
references/
  intake-checklist.md      # What to learn about the traveller
  official-sources.md      # Where to verify visas, advisories, logistics
  trip-plan-template.md    # Structure for a full trip plan
```

## Installation

- **Claude.ai:** Settings → Capabilities → Skills → upload the packaged `.skill` / zip of this folder.
- **Claude Code:** copy this folder into `~/.claude/skills/global-travel-planner/`.

## Disclaimer

Visa rules, prices, and schedules change frequently. Always reconfirm entry requirements with official sources before booking.
