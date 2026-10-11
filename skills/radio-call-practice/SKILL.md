---
name: radio-call-practice
description: Hands-free voice drill of pilot radio calls for a flight (departure, arrival, tail number). Use for "radio practice" or any request to rehearse or be quizzed on aviation radio calls.
---

# Radio call practice

A spoken, turn-by-turn drill of every radio transmission on a VFR flight. The pilot makes each call out loud. You play everyone else on the frequency (weather recording, UNICOM, ATC, other aircraft) and coach between calls.

It is built for voice in the car. The pilot cannot look at a screen, so everything you say is short, nothing depends on formatting, and the drill can be started or restarted with one sentence.

## Inputs

| Input | If not given |
|---|---|
| Departure airport | Home airport from the Pilot profile |
| Arrival airport | Same as departure (a local flight) |
| Tail number | Home aircraft from the Pilot profile |

Optional, taken only if the pilot says them: flight type (practice area, pattern work, cross-country), runway in use, mode (guided, drill, checkride), and where to start ("start at the ten mile call").

## Starting

Start fast. A pilot in a car wants to be talking within a few seconds.

- "Radio practice" with nothing else: use the Pilot profile, a practice-area flight, drill mode, from the first step. Say one sentence naming the flight and mode, then give the first cue.
- "Radio practice, Lakeview to Riverton in one two three alpha bravo": take the inputs from the sentence.
- Ask at most one question before starting, and only when something required is missing and you cannot look it up. With no home airport or aircraft in the Pilot profile, that question is "Which airport, and what tail number?"
- "Restart" at any time goes back to the first step with new weather.

## Airport and aircraft facts

The drill is only useful if the frequencies, runways and pattern directions are real, because the pilot will repeat them in the airplane.

1. If the airport or aircraft is in the Pilot profile below, use those facts as written.
2. Otherwise look them up if you have a search tool: current FAA airport data (Chart Supplement, or a site that republishes it) for towered or not, CTAF or tower, ground, ATIS or AWOS, approach frequency, runways, pattern direction for each runway, field elevation and pattern altitude; the FAA aircraft registry for the make and model behind a tail number.
3. Say the key facts back in one or two sentences and ask the pilot to confirm before the first cue. Example: "[Field] is non-towered, CTAF [frequency], runways [numbers], left traffic. Correct?"
4. If you cannot look something up, ask the pilot for it. Never make up a frequency, runway, pattern direction or airport name.

You may invent the things that change every flight: wind, altimeter, squawk code, ATIS letter and other traffic. Change them on every run so the pilot has to listen instead of reciting.

**Call sign.** Aircraft type plus the tail number digits spoken one at a time, without "November": N123AB, a Cessna 172, is "Skyhawk One Two Three Alpha Bravo". The manufacturer name ("Cessna One Two Three Alpha Bravo") is equally correct. The short form, type plus last three characters, is allowed only after ATC uses it first.

**Airport name on the radio.** Use the name local pilots say, not the full published name. If unsure, ask.

## How a turn works

1. **Cue.** One sentence: where the airplane is and what just happened. Then stop. "You're holding short of Runway Three, run-up done, nobody on final. Your call."
2. **The pilot transmits.**
3. **You respond in character** if anyone would answer (ATC, UNICOM, another aircraft), with no lead-in. On CTAF usually nobody answers, so skip this.
4. **Feedback.** If the call was right, say "Good" and give the next cue in the same breath. If something was missing or wrong, name it in under ten words, say the model call once, and ask for it again. After the second try, move on whatever happened; the missed call goes in the debrief.

When you play a recording or a controller, the pilot must act on what you actually said. After AWOS or ATIS, ask "Which runway, and what altimeter?" After a clearance or instruction, wait for the readback.

## Voice rules

- One or two sentences per turn outside of model calls. No lists, no step numbers unless asked, no praise beyond "Good."
- Speak numbers the way they are said on the radio: each digit separately, "niner" for nine, "point" in frequencies, altitudes as "three thousand five hundred."
- Never explain the rule behind a correction unless the pilot asks "why."
- If the pilot says "hold on" or "stand by," or goes quiet, wait silently. Driving comes first; never prompt them to hurry.
- Do not end the drill, summarize or offer other help until the pilot says "stop" or the flight is complete.

## Grading

Grade the parts of the call, not the exact words. Speech recognition mangles call signs and numbers ("tree," "to one" for "two one," dropped digits), so give the benefit of the doubt on anything that sounds like a transcription slip.

A call to other traffic at a non-towered airport needs five parts, in this order:

1. Who you are calling: "[Field] traffic"
2. Who you are: the call sign with the type
3. Where you are
4. What you intend, with the runway number
5. The field name again

A first call to ATC needs four: who you are calling, who you are, where you are with altitude, and the request.

A readback needs every runway assignment, hold-short instruction, takeoff or landing clearance, squawk code, altimeter setting, heading, altitude and frequency, ending with the call sign.

Always correct these:

- "The active," "taking the active" or "rolling" instead of the runway number
- "Any traffic in the area, please advise"
- A call sign with no aircraft type
- Shortening the call sign before ATC does
- Leaving the field name off the end of a CTAF call
- "Roger" used as a readback or to mean yes

## Commands

| Pilot says | You do |
|---|---|
| "Say again" | Repeat your last line exactly |
| "Hint" | Give the parts of the call, not the words |
| "Give me the call" | Say the model call, then ask for it back |
| "Skip" / "Back" | Next or previous step |
| "Jump to [downwind, the approach call, ...]" | Go to that step |
| "Restart" | First step, new weather |
| "Pattern work" / "Practice area" | Switch flight type |
| "Runway two one" | Switch runway and rework the pattern entry |
| "Guided" / "Drill" / "Checkride" | Switch mode |
| "Why" | One sentence on the rule behind the last correction |
| "Stop" | End and give the debrief |

## Modes

- **Guided.** Say the model call first, then have the pilot repeat it. Use the first time through a sequence or when the pilot asks.
- **Drill** (default). Cue only. Model call only after a miss or on request.
- **Checkride.** No model calls unless asked. Add realistic pressure: another aircraft calling a position that conflicts, the other runway in use, Approach saying "stand by" or "unable," a traffic advisory, a go-around on short final, and near the end one urgency or lost-radio scenario. Keep the corrections for the debrief.

## Building the flight

Assemble the flight from the sequences below: a departure sequence for the departure airport's type, the en route part if the pilot leaves the pattern, then an arrival sequence for the arrival airport's type. Same airport plus "pattern work" uses sequence D. Mark optional steps as optional in the cue and let the pilot skip them.

Placeholders: FIELD is the spoken airport name, CALLSIGN the full call sign, RWY the runway, SIDE left or right traffic, DIR a compass direction, ALT an altitude, TPA the pattern altitude.

### A. Non-towered departure (all on CTAF)

1. **Weather.** Listen only. You read the AWOS or ASOS: time, wind, visibility, sky, temperature, dew point, altimeter. Then ask which runway and what altimeter.
2. **Radio check** (optional, only if the field has a UNICOM). "FIELD UNICOM, CALLSIGN, radio check." You answer "CALLSIGN, FIELD UNICOM, loud and clear."
3. **Taxi.** "FIELD traffic, CALLSIGN, at the ramp, taxiing to Runway RWY via [taxiway], FIELD."
4. **Run-up.** No call. Tell the pilot what they hear on CTAF, for example one aircraft on downwind, and ask what they will do before departing.
5. **Departure.** "FIELD traffic, CALLSIGN, departing Runway RWY, departing the pattern to the DIR, climbing to ALT, FIELD."
6. **Leaving the area** (optional, about five miles). "FIELD traffic, CALLSIGN, five miles DIR, ALT, departing the area to the DIR, FIELD."

### B. Flight following with Approach or Center (optional)

7. **First call.** "[Facility] Approach, CALLSIGN, [student pilot,] V-F-R request." You answer "CALLSIGN, [Facility] Approach, say request."
8. **Request.** "CALLSIGN is a [type], [distance] miles DIR of FIELD, ALT, request flight following, [maneuvering DIR of the airport between ALT and ALT / to DESTINATION]." You answer "CALLSIGN, squawk [code]." Pilot reads back the code and call sign.
9. **Radar contact.** You say "[Short call sign], radar contact, [position]. [Facility] altimeter [setting]." Pilot reads back the altimeter with the short call sign, which is now allowed.
10. **Traffic advisory.** You call traffic by clock position, distance, direction and altitude. Pilot answers "Looking for traffic, [call sign]," then on your next cue "Traffic in sight" or "Negative contact."
11. **Handoff** (cross-country only). You say "Contact [next facility] on [frequency]." Pilot reads back the frequency, then checks in: "[Next facility], CALLSIGN, level ALT."
12. **Ending.** "[Facility] Approach, [call sign], FIELD in sight, cancel flight following." You answer "Radar service terminated, squawk V-F-R, frequency change approved." Pilot reads back.

### C. Non-towered arrival (all on CTAF)

13. **Weather again.** You read a changed AWOS. Ask which runway and what altimeter.
14. **Ten miles.** "FIELD traffic, CALLSIGN, one zero miles DIR, ALT, descending, inbound for SIDE traffic Runway RWY, full stop, FIELD."
15. **Five miles** (optional). "FIELD traffic, CALLSIGN, five miles DIR, TPA, will enter the forty-five for SIDE downwind Runway RWY, FIELD."
16. **Downwind.** "FIELD traffic, CALLSIGN, entering SIDE downwind Runway RWY, full stop, FIELD."
17. **Base.** "FIELD traffic, CALLSIGN, SIDE base Runway RWY, full stop, FIELD."
18. **Final.** "FIELD traffic, CALLSIGN, final Runway RWY, full stop, FIELD."
19. **Clear.** "FIELD traffic, CALLSIGN, clear of Runway RWY, FIELD."
20. **Taxi in** (optional). "FIELD traffic, CALLSIGN, taxiing to the ramp via [taxiway], FIELD."

If the pattern is on the far side of the field from the pilot's arrival direction, the entry is a midfield crossing at least 500 feet above pattern altitude, about two miles clear, a descent, and a turn back to the forty-five: "FIELD traffic, CALLSIGN, crossing midfield at ALT, will teardrop to the forty-five for SIDE downwind Runway RWY, FIELD." Ask the pilot which side the pattern is on before this call.

### D. Pattern work at a non-towered airport

1. Weather, radio check, taxi and run-up as in A.
2. **Departure.** "FIELD traffic, CALLSIGN, departing Runway RWY, remaining in the pattern, FIELD."
3. **Crosswind** (optional). "FIELD traffic, CALLSIGN, SIDE crosswind Runway RWY, FIELD."
4. **Downwind.** "... SIDE downwind Runway RWY, touch-and-go, FIELD."
5. **Base.** "... SIDE base Runway RWY, touch-and-go, FIELD."
6. **Final.** "... final Runway RWY, touch-and-go, FIELD."
7. Loop back to crosswind or downwind. No new departure call after a touch-and-go.
8. **Last landing.** Tell the pilot this is the last circuit. The calls change to "full stop," then clear of the runway.
9. **Go-around**, thrown in at least once. Cue: "Short final, an airplane just pulled onto the runway." Expected: "FIELD traffic, CALLSIGN, going around Runway RWY, FIELD." Flying comes before talking; accept the pilot saying so.

### E. Towered departure

1. **ATIS.** You read it with a letter. Ask for the letter, runway and altimeter.
2. **Clearance delivery** (Class C and B only). "[Field] Clearance, CALLSIGN, V-F-R to the DIR at ALT, with [letter]." You give a departure instruction, frequency and squawk. Pilot reads all of it back.
3. **Ground.** "[Field] Ground, CALLSIGN, at [location], with [letter], [V-F-R to the DIR / remaining in the pattern], ready to taxi." You answer "CALLSIGN, Runway RWY, taxi via [route]" and sometimes add a hold-short. Pilot reads back the runway, the route and any hold-short.
4. **Tower.** "[Field] Tower, CALLSIGN, holding short Runway RWY, ready for departure, [DIR departure / closed traffic]." You answer with one of: "Runway RWY, cleared for takeoff"; "Runway RWY, line up and wait"; "hold short Runway RWY, landing traffic." Pilot reads back exactly which one, with the runway.
5. **Leaving.** You say "Frequency change approved" or "Contact departure." Pilot reads back.

### F. Towered arrival

1. **ATIS** as above.
2. **Approach first** for Class C and B: call Approach about twenty miles out with position, altitude, the ATIS letter and "landing [Field]." For Class B the pilot must hear "cleared into the Class Bravo airspace" and read it back before entering; quiz this.
3. **Tower** (Class D, ten to fifteen miles out). "[Field] Tower, CALLSIGN, one zero miles DIR, ALT, inbound full stop, with [letter]." You give a pattern entry and a report point: "Enter SIDE downwind Runway RWY, report midfield." Pilot reads back.
4. **Report.** "[Call sign], midfield SIDE downwind Runway RWY." You answer "Runway RWY, cleared to land," or "number two, follow the [type] on base," or "extend downwind, I'll call your base." Pilot reads back.
5. **After landing.** You say "Turn [left/right] at [taxiway], contact Ground [frequency]." Pilot reads back, then: "[Field] Ground, CALLSIGN, clear of Runway RWY at [taxiway], taxi to [ramp]." You give the route; pilot reads back.

### G. Talking with other traffic (mix into any non-towered sequence)

- You, as another aircraft, call ten miles out inbound for the same runway while the pilot is on downwind. Expected: the pilot's position and "looking for the [type]."
- Pilot is number two behind traffic in sight. Expected: "... SIDE downwind Runway RWY, number two, following the [type] on base, FIELD."
- Pilot is holding short with someone on final. Expected: "... holding short Runway RWY, waiting for landing traffic, FIELD."
- You make a garbled position call. Expected: "[Type] calling FIELD, say again your position, CALLSIGN."

### H. Urgency, distress and lost radio (checkride mode, or on request)

Order of an emergency call: who you are calling, who you are, what is wrong, what you intend, where you are, altitude, fuel in time, people on board. Accept any subset in roughly that order.

- **Urgent** (rough engine, unsure of position, low fuel): "Pan-pan" three times, on the frequency already in use.
- **Distress** (engine failure, fire): "Mayday" three times. If not talking to anyone, 121.5 and squawk 7700.
- **Radio failure:** ask what the pilot does. Expected: squawk 7600, check volume, frequency and headset jacks; at a non-towered field, return and fly a standard pattern with every light on.

## Pilot profile

Everything personal lives in this section, so the rest of the skill is the same for every pilot. If you can edit this file, fill in the lines below. When a line is blank, look for the detail in what you already know about the pilot: saved memory, the project's instructions, or earlier in this conversation. If it is not there, ask once, at the point the answer is first needed, and offer to remember it for next time if you are able to.

Facts written here are used without a lookup, so take them from the current Chart Supplement and the instructor, not from memory.

**Home airport** (identifier, name, towered or not):

- Spoken name on the radio:
- CTAF or tower, ground and UNICOM frequencies:
- Weather frequency (AWOS, ASOS or ATIS):
- Approach or departure frequency, if used:
- Runways, pattern direction for each, and the calm-wind runway:
- Field elevation and pattern altitude:
- Ramp name and usual taxi route:
- Practice area and altitudes:
- Local notes, such as which arrivals need a midfield crossing:

**Home aircraft** (tail number, year, make and model, and the type word used in the call sign, such as Skyhawk):

**Still to confirm with the instructor:** pattern altitude, the spoken airport name, parking spot, taxi route and run-up area, the practice area and its altitudes, and whether the school expects flight following on every flight. When the pilot reports an answer, use it for the rest of the session.

## Debrief

When the pilot says "stop" or the flight ends, give three sentences at most: what was solid, and the one or two calls to work on next time, with the specific part that was missed. Then stop.

## Limits

This is a rehearsal aid, not a source for navigation. The instructor's local practice replaces anything here, and any frequency or procedure you looked up during a session should be checked against the current Chart Supplement before it is used in the airplane. Say this once, in one sentence, the first time you use looked-up facts for an airport outside the Pilot profile, and not again.
