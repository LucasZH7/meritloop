# MeritLoop V1 Product Spec

## Product Summary

MeritLoop is a local-first Buddhist ritual companion that helps users complete daily chanting, dedication, and reflection routines through a robot, shrine device, or on-device agent.

## Default Language

- Primary: English
- Localized: adapt to the host system language when deployed locally
- Fallback: English

## Suggested Launch Languages

- English
- Simplified Chinese
- Traditional Chinese
- Japanese
- Thai

## V1 Product Goal

Help a user maintain a daily spiritual rhythm through scheduled ritual guidance, local content playback, practice logging, and a nightly merit summary.

## V1 User Flow

1. User sets practice times.
2. Device or local agent starts a ritual on schedule.
3. User chants, listens, reads, or sits.
4. System offers a dedication step.
5. Session is logged locally.
6. Merit score updates.
7. Nightly summary is spoken or displayed.

## V1 Feature Set

- Local scheduler
- Local text and audio library
- Chanting session player
- Dedication templates
- Merit-score engine
- Daily and weekly summaries
- Household profiles
- Language auto-selection based on system locale

## Merit Formula Draft

Suggested starting weights:

- Chanting completed: 40
- Dedication completed: 20
- Scripture reading completed: 15
- Silent sitting completed: 20
- Daily streak bonus: 5 x streak day, capped
- High completion quality bonus: 10

Suggested guards:

- Daily soft cap to avoid score farming
- Lower reward for repeated short sessions in a narrow window
- Explain score changes in plain language

## Suggested Daily Schedule

- 6:30 AM: Morning ritual reminder
- 7:00 AM: Short chanting session
- 8:00 PM: Evening chanting or reflection
- 9:30 PM: Nightly merit summary

## Launch Content Pack

- Short daily chants
- Common dedication templates
- Short sutra excerpts
- Guided silent sitting prompts
- Festival reminders

## Deployment Modes

- Desktop robot
- Speaker-like home shrine device
- Local-only app or agent

## Future V2

- Family sync
- Community chanting rooms
- Shared merit boards
- Temple channels
- Cloud backup

## Boundaries

- No claims of enlightenment
- No doctrinal guarantee of merit outcomes
- No replacement of clergy or professional care
