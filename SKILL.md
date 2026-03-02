---
name: proverbs-a-day
description: Send the Korean text of the daily Proverbs chapter (day 1→chapter 1 ... day 31→chapter 31) to the user at 06:00 local time by default, with configurable schedule/timezone. Use when setting up, running, or adjusting daily Proverbs delivery automation.
---

# Proverbs a Day

## Defaults
- Time: 06:00
- Timezone: Asia/Seoul (configurable)
- Mapping: day-of-month N → Proverbs chapter N (1-31)

## Workflow
1. Determine today's local date in configured timezone.
2. Select Proverbs chapter equal to day-of-month.
3. Send full chapter in Korean (with verse numbers like `1절`, `2절`, ...).
4. Optionally append a one-line reflection.
5. Deliver to configured channel/recipient.

## Configurable
- time (default 06:00)
- timezone (default Asia/Seoul)
- channel/recipient
- include_reflection (true/false)
- delivery format (full text, verse-number style)
