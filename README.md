# Interview Coach Skills

Two skills for [Claude](https://claude.ai) that coach customer discovery interviews using *The Mom Test* by Rob Fitzpatrick.

| Skill | What it does |
|---|---|
| [`mom-test-interview-coach`](./mom-test-interview-coach) | A coach for discovery interviews. Modes: **TRAIN** (LEARN, RATE, SPOT, BUILD), **PREP**, **LIVE**, **DEBRIEF**, **PATTERNS**. Includes the rubric, interview flow and a 10-question calibration set. |
| [`interview-learnings-log`](./interview-learnings-log) | Keeps a running log of your interviews (one LOG ENTRY per interview) and reads it back to find patterns across them. Works with the coach's DEBRIEF and PATTERNS modes. |

## How to use them

Start a message with a mode keyword, for example:

- `TRAIN` to practice (new to the Mom Test? Say so and it starts with LEARN)
- `PREP` and paste the questions you plan to ask
- `LIVE` for quick help during an interview
- `DEBRIEF` and paste your transcript or notes
- `PATTERNS` to find themes across your logged interviews

## Install in Claude

Skills are available on Free, Pro, Max, Ultra, Team and Enterprise plans, and need code execution to be enabled.

1. Download the skill folder you want (see **Download** below). It must be a **zip** containing the skill folder, with `SKILL.md` inside.
2. In Claude, click **Customize** in the left sidebar, then open **Skills**.
3. Click **+**, then **+ Create skill**, then **Upload a skill**, and choose the zip.
4. Toggle the skill on.

Do this on the Claude website or desktop app. The skill then works in your chats on your account.

Prefer not to zip anything? Open a skill's `SKILL.md`, copy the text, start a Claude chat, paste it, and ask: "Create a skill from this."

## Download

Use the zips on the [Releases](../../releases) page. Each zip already has the right structure. GitHub's green **Code > Download ZIP** button zips the whole repo, which will not upload as a single skill.

## Before you start

- **Bring your own brief.** The coach does not know who you are interviewing. Have your segment and your 3 big questions ready, and it will ask for them.
- **Keep your own log.** The learnings-log skill describes the format, but your interview log is yours. Keep it in a doc you can paste or point to.
- **Examples reference Friendlyr**, a social app for small-group events. Swap in your own product when you practice.

## Credit
Built on the ideas in *The Mom Test* by Rob Fitzpatrick. This repo is not affiliated with the author or publisher.
