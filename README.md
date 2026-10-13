# Zhi Kai's Daybook

One page to run the day: a full to-do system plus calendar, habits, goals, money, journal, notes, fitness, a focus timer and a weekly review. Built for juggling Polymath Learning Centre, CC Collectibles, corporate AI training, family and health in one place.

Everything lives in a single file, `index.html`. No build step, no server, no account.

## Open it

- **Any browser:** download `index.html` and open it, or serve the folder with any static host (GitHub Pages works).
- **Inside Claude:** the published Claude version saves privately to your Claude account and syncs between phone and computer. It also turns on the Claude buttons (see below).

## What's inside

| Section | What it does |
|---|---|
| **Today** | Big date header with class-day marker, quick capture, highlighted Top 3, due and overdue tasks, agenda with a "now" line, habit check-ins, mood, money due this week, week strip, focus shortcut |
| **Tasks** | Smart lists (Inbox, Today, Upcoming, No date, Waiting on, Completed) and a list per area. Three layouts: list, drag-and-drop board, urgent/important matrix. Steps, repeats, time estimates, priorities, goal links, notes |
| **Calendar** | Week grid with overlapping events laid out side by side, month grid, phone-friendly day list. Repeating events (weekly classes only need adding once), remove a single occurrence or the whole series |
| **Habits** | Weekly tick grid, current and best streaks, 30-day completion, 26-week heatmap, per-habit schedule days, archive |
| **Goals** | Quarterly goals with measurable results, progress rings, on-track/behind pace check, linked tasks |
| **Money** | Income and spending by area, 6-month chart, spending by category, monthly bills with paid status, "to collect" list — marking a payment received logs it as income |
| **Journal** | Mood, energy, three good things, wins, notes, tomorrow's intention, daily prompt, mood calendar, writing streak |
| **Notes** | Search, tags, pinning, area colour, simple Markdown preview (headings, lists, checklists, bold, links), turn a note into a task |
| **Fitness** | Workouts against a weekly target, minutes per week, weeks-on-target streak, body-weight trend. Logging a workout ticks a "Workout" habit automatically |
| **Focus** | Pomodoro timer (focus, short and long breaks) linked to a task, keeps running across sections, chime at the end, session log |
| **Weekly review** | Pulls the week's numbers from every section, a reflection checklist, three prompts, goal progress, past reviews |
| **Settings** | Name, areas (rename, recolour, reorder), class days, week start, targets, timer lengths, currency, theme, backup export/import, clear examples, erase |

## Quick add

Type tasks the way you'd say them. The preview under the box shows what was understood.

```
Mark P5 papers fri 4pm #polymath !high ~45m
Call supplier tmr 9.30am #cc
Pay rent 1/11 monthly
Stock count every sat #cc
Read report in 2w !low
```

| Type | Means |
|---|---|
| `today` `tmr` `fri` `next mon` `20/10` `3 nov` `in 2w` `eom` | due date (dates are day/month) |
| `4pm` `15:30` `tonight` | time |
| `#polymath` `#cc` `#family` | area (any area name or tag, prefixes work) |
| `!high` `!med` `!low` | priority |
| `~30m` `~1.5h` | time needed |
| `daily` `weekdays` `weekly` `monthly` `every sat` | repeats |

## Keyboard

| Key | Action |
|---|---|
| `⌘K` / `Ctrl K` or `/` | Search tasks, notes, goals and events, jump anywhere, or type a new task |
| `N` | New task |
| `1`–`9` | Jump to a section (Today is 1) |
| `Esc` | Close the open panel or dialog |

## Where your data is saved

- **Opened from Claude (signed in as the owner):** a private store attached to the page. Access rules let only the owner read or write it, even if the link is shared.
- **Opened anywhere else:** this browser's local storage. The sync badge says **This device**. Use **Settings → Export backup** to move data between browsers; **Import backup** restores it.

## Claude buttons

When the page runs inside Claude, four helpers appear. Each asks permission the first time.

- **Plan my day** — time blocks from now until evening around your events, tasks and habits
- **Suggest Top 3** — picks today's three most important tasks with a one-line reason
- **Suggest steps** — breaks a task into concrete next steps
- **Summarise my week** — a short read on the week plus three focus points for next week

They stay hidden when the page is opened outside Claude.

## Tech

Plain HTML, CSS and JavaScript in one file. Fonts from Google Fonts with system fallbacks. Light and dark themes follow the device, with a manual switch in Settings. Works at phone width with a bottom dock.
