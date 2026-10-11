# Student Pilot skills for Claude

Three skills for student pilots working toward a U.S. Private Pilot certificate (airplane single-engine land). Each one is a spoken, turn-by-turn session designed for hands-free use, such as in the car on the way to or from the airport.

| Skill | Say | What it does |
|---|---|---|
| `radio-call-practice` | "radio practice" | You make every radio call for a flight out loud. Claude plays the weather recording, UNICOM, ATC and other traffic, and corrects what was missed. Works for towered and non-towered airports. |
| `flight-lesson-debrief` | "lesson debrief" | You talk through the lesson you just flew. Claude pulls out the hours, landings and notes, checks them against the FAA logging rules, reads them back, and saves them. |
| `pilot-oral-quiz` | "oral quiz" | Short-answer drill for the knowledge test, or a scenario-based oral in the style of the checkride, graded against an answer key checked against the regulations. |

## Install

**As a plugin (paid Claude plans).** In the Claude app: Customize > Plugins > Add > Add marketplace > Add from a repository, then enter `OWNER/REPO` and add Student Pilot. In Claude Code:

```
claude plugin marketplace add OWNER/REPO
claude plugin install student-pilot@student-pilot-skills
```

**As single skills (any plan, including Free).** Zip one folder from `skills/` so the folder itself is the top level of the zip, then in the Claude app: Customize > Skills > + > Create skill > Upload a skill. Code execution must be turned on.

## Make it yours

Nothing in these skills is tied to one pilot. Each ends with a **Pilot profile** section that is blank: home airport, aircraft, and where to keep logs. When a line is blank, Claude uses what it already knows about you or asks. Pick whichever of these suits you:

- Tell Claude once and ask it to remember: "Remember my pilot profile: I train at KXYZ in N123AB, a 1978 Cessna 172N, for my Private."
- Keep your chats in a Project and paste your profile into the Project's instructions.
- If you installed single skills, fill in the Pilot profile section of each `SKILL.md` before you zip it.

The oral quiz will not state V-speeds or other aircraft numbers unless you supply them from your own aircraft's handbook.

## Optional: a progress tracker

`flight-lesson-debrief` can log each flight to a tracker page with a milestone checklist and running hour totals for both the Private and the Sport-then-Private paths. Say "set up my flight training tracker" and Claude publishes your own private copy from `skills/flight-lesson-debrief/assets/flight-training-tracker.html`. Without a tracker, the debrief keeps notes only.

## What was checked, and when

Checked in October 2026 against the eCFR (14 CFR Parts 1, 43, 61 and 91, and 49 CFR Part 830), the Aeronautical Information Manual (effective July 9, 2026), the Private Pilot Airplane Airman Certification Standards (FAA-S-ACS-6C), the Aviation Instructor's Handbook and the Pilot's Handbook of Aeronautical Knowledge. Rules change, so treat anything older than a year as due for another check.

Airport facts are not stored in the skills. Claude looks them up when you name an airport and reads them back for you to confirm. Check every frequency and runway against the current Chart Supplement before you use it in an airplane.

## Limits

- These are study aids. They are not flight instruction, not a logbook and not a source for navigation. Your instructor, your logbook, your aircraft's handbook and the regulations come first.
- Not affiliated with or endorsed by the FAA.
- Saving to a tracker or a document needs a Claude session that can reach those tools. Whether skills and tools are available in voice mode varies; if a skill does not start by voice, start it in a text chat and continue that chat by voice.

## License

MIT. See `LICENSE`.
