# Hybrid-Athlete-Coach

A skill for Claude you can use to create a personalized coach that improves your running, lifting, cycling etc.

---

<img width="596" height="335" alt="image" src="https://github.com/user-attachments/assets/6e2d580a-49da-442f-ad83-c78b9cba4a85" />

## What This Is

Most AI fitness prompts produce generic advice. This skill produces a coaching system calibrated so specifically to one athlete that no part of it could be copy-pasted to someone else.

It guides Claude through seven structured phases: designing a named coach persona, conducting a full athlete intake interview, running sport-specific research, building a phased plan on actual calendar dates, generating four permanent coach documents, creating a session tracker with a weekly check-in loop, and installing everything for permanent reuse.

The result is a coach, not a plan — one that runs weekly, updates when life changes, and tells the truth.

---

## Who It's For

Anyone who wants a real training system, not a template:

- **Runners** — marathon, 5K, trail, ultra, etc.
- **Strength athletes** — powerlifting, Olympic lifting, general strength
- **Endurance sports** — cycling, triathlon, rowing, swimming
- **Skill/combat sports** — with adaptation for technique-heavy goals
- **Body composition** — fat loss or muscle gain with a performance lens
- **Return from injury** — structured re-entry with honest benchmarks

The skill is sport-agnostic. The coach it builds is sport-specific. There is no scientific proof that this works for everyone. I tested the first version myself and it improved my running and strength scientifically.

---

## The Seven Phases

| Phase | Name | What Happens |
|-------|------|--------------|
| 1 | **Design the Coach** | Choose persona, personality, ruthlessness dial, feedback style, anti-list |
| 2 | **The Intake** | Full athlete interview — goal, dates, data, history, constraints, health |
| 3 | **The Research** | Research plan shown first → deep dive → findings briefing with honest math |
| 4 | **The Plan** | Full program on real calendar dates → review together → revise → sign-off |
| 5 | **The Coach Documents** | Four permanent files produced and delivered one at a time |
| 6 | **The Tracker & Weekly Loop** | Session tracker + one rest-day check-in ritual, calendar scheduling |
| 7 | **Deliver & Install** | Step-by-step handover for Claude Projects, Claude Code, or plain chat |

Everything happens in the open. Claude announces each phase, shows the research plan before running it, and shows reasoning behind every structural decision. The athlete watches a coaching staff assemble around them — the transparency is part of the product.

---

## Quality Guarantees

The skill enforces a quality bar. Claude will not exit Phase 5 without all of the following:

- A **named persona** with defined voice, backstory, beliefs, and refusal list — a coach, not an assistant
- A **campaign**, not a plan — goal stack in priority order, hard dates, floor / target / stretch tiers
- A **profile built on constraints**, not wishes — actual access, actual days, actual life load
- **Every session has a purpose and a number** — no "easy run 45 min" without a pace cap; no "squats" without sets, reps, and effort target
- **Research with an evidence hierarchy** — peer-reviewed science and practitioner consensus on top, confidence labels on every claim
- A **working operating system** — tracker + weekly ritual
- **Anti-sycophancy guardrails** — the coach tells the truth about gaps; never pretends the goal is guaranteed

---

## Installation

### Option A — Claude Projects *(recommended)*

This is the easiest and most reliable setup for ongoing use.

1. Open [claude.ai](https://claude.ai) and create a new **Project** (name e.g. Coach)
2. (skip this step if you don't want to use skill.md; just add the skill.md to instructions instead) Go to customize and manually add the skill (either through copying the skill.md text or dragging the file over), name it Coach, and then add it to your skills.
3. Go back to your project. If you use a smartwatch or Strava you can either download previous training data and put it in project files or you could use a third-party tool (e.g. GetFast(kailo))
4. When you're done with previous steps you write /Coach to use the skill and then add what you want the coach to do or just click enter. (Make sure you use the best model available for you and highest effort for best results)
5. Now Claude will guide you through a setup process (about 30 min for most). Now you have your own personal Coach. Now the coach will be able to start creating your plan. (detailed information under ## Usage)

https://github.com/user-attachments/assets/fd103319-f256-4a87-8720-a5207db4d659

https://github.com/user-attachments/assets/348e9f4d-c10a-4824-83c0-6d4f9c21a419

Note that the coach activates automatically when you ask about training, sessions, debriefs, pacing, recovery, gear, nutrition, or anything connected to your program even if you don't address it by name, inside that project or any other chat.

### Option B — Claude Code

You use Claude Code and go through a similar setup as Option A

### Option C — Plain Chat

Keep the files saved anywhere. At the start of a new conversation:

1. Paste or attach `SKILL.md`
2. Attach the relevant reference file when the question needs it (`full_plan.md` for week questions, `event_day.md` in race week)

Least convenient, works everywhere without any setup.

---

## Usage — Running the Build

Start a new conversation (or open your Project) and paste this: /Coach I want to build my coaching system. Let's start by interviewing me before building Phase 1.

Claude will take it from there, phase by phase. The full build typically takes one conversation session of 30–60 minutes depending on how much data you have ready.

**Things to have ready before you start:**
- Your goal — as specific as possible (a time, a weight, a race, a standard)
- Your event date or a target test date
- Recent training data — paste from Strava, Garmin, Apple Health, or your training log or use a third-party app e.g. GetFast (kailo)
- Your schedule — which days you can train, for how long
- Your gym/equipment access — which days, which equipment, any restrictions
- Any injury history worth knowing about
---
## The Weekly Loop — How It Works After the Build
Once installed, the only thing the athlete does is one check-in on their rest day:
> *"Here's my week: [one line per session or pasted app stats]"*
The coach handles everything else:
1. Reviews the week against plan — what did its job, what didn't
2. Updates the tracker and status block
3. Recalibrates if a benchmark landed
4. Generates next week's sessions with full prescriptions
5. Schedules them (Google Calendar if connected, or outputs a copy-paste block)
Miss a check-in? The next one covers both weeks. The coach notices and says so.
---
## Keeping It Current
**When life changes** — new job, injury, moved cities, new gym — tell the coach once. It updates the profile and venue model, not just that week's sessions.
**Updating files outside Claude Code:** The coach can't edit saved files from chat. When it outputs an updated document, replace the old version in your Project Knowledge (or saved files) yourself.
**The plan is a hypothesis.** If reality keeps disagreeing with it, the plan changes. That's the system working, not failing.
---
## Honest Expectations
This skill is built with **anti-sycophancy** as a design requirement. The coach will:
- Tell you if your goal isn't reachable in the time you have — and propose a recalibrated version
- Give you a floor / target / stretch breakdown based on real demographic data, not best-case math
- Flag if your constraints make the plan harder than you're assuming
- Label research claims as `VERIFIED`, `COACH` (best-practice, not independently verified), or `REFUTED`
It will not tell you what you want to hear just because you want to hear it.
---
---
## Contributing
Pull requests welcome. If you use this for a sport not yet represented in the examples, or find a phase that breaks for a specific goal type, open an issue describing what happened and what the correct behavior should be.
When editing `SKILL.md`, preserve the quality bar and the evidence hierarchy — those are load-bearing. Everything else is fair game.
---
## License
MIT — use it, fork it, build on it. If you build something good, share it back.
---
*Built to run in Claude (claude.ai). Tested with Claude Projects and Claude Code.*
*Sport-agnostic. Calibrated per athlete. Generic advice is a bug, not a feature.*
