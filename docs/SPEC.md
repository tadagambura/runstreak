# RunStreak: Spec

**From couch to consistent** · #23 of 31 · Wave 2: Recurring keepers · Used: 3 times a week · Harder · Revenue potential: Medium · Habits, Health & Learning · Source: Perplexity

## One-liner

A beginner-friendly run and walk-run tracker: GPS distance and pace, run/walk intervals, a weekly goal and streaks, simple plans and shareable run cards.

## Problem / audience

- **Who it's for:** New runners, casual joggers, people training for a first 5K.
- **The problem it solves:** Beginners get overwhelmed by serious running apps and quit.
- **Example:** A beginner follows a 5K plan, logs three runs a week, and shares a card after week four.

## MVP features (ship with only these)

1. GPS tracking: distance, pace, time, route
2. Run/walk intervals with audio cues
3. Weekly goal and streaks
4. Simple beginner plans
5. Shareable run cards

## Not in MVP

- Plans beyond 5K
- Run with a friend
- Offline maps

## Monetisation

| Model | Detail |
|---|---|
| Free | Tracking and one plan, with ads |
| Premium | £4.99/month: all plans, advanced stats, custom intervals |
| Ads | Never during a run |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Planned run days |
| Tiny win | Complete a run |
| Progress | Weekly streak and plan progress |
| Share | Run cards |
| Next step | The next plan after 5K |
| Cadence | 3 times a week |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Run finished: the finish tape snaps and confetti flies
- Planned rest day: the stickman on the sofa with ice packs, streak frozen
- Run/walk switch: he waddles comically on the walk intervals
- Personal best: he runs so fast he leaves a dust cloud
- 5K done: a medal drops and he bites it

**Line we don't cross:** Nothing animated during the run except the essentials.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo native build (background GPS).
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Beginner running; First 5K; Run motivation
- **Shareable output:** Run cards

## Risks

Background GPS, battery use and accuracy are hard to get right. Strong free competition.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
