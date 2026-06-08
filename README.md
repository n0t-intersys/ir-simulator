# Incident Response Simulator (standalone)

A single-file, offline copy of the branching incident-response tabletop from
intersystechnology.com/ir-simulator. Pick a crisis and work it from three seats
as it escalates: SOC Analyst, then Incident Commander, then CISO. Your decisions
branch and compound, the intel arrives incomplete, and the clock never stops.

## Scenarios

- **Notice Period** (Insider Threat, Standard) - a departing engineer moving data he should not be.
- **Blast Radius** (Ransomware, Hard) - a double-extortion detonation on a Saturday night.
- **Pending Wire** (Business Email Compromise, Standard) - a $1.8M wire on a forged banking change.
- **Trust Anchor** (Supply Chain, Hard) - a trusted vendor ships a signed backdoor to your estate.

Each scenario has seven possible endings and an after-action report that grades
your shift across two situation meters and three stakeholder-trust meters.

## How to run it

Double-click `index.html`. It opens in your default browser and runs immediately.

- no install, no Node, no npm, no build step
- no internet connection required (everything is self-contained in the one file)

If double-clicking opens a code editor instead, right-click the file and choose
"Open With" then your browser (Chrome, Safari, Firefox, Edge).

## Controls

- Click a choice, or press the number keys 1-4 to pick one.
- "Change scenario" (top right) returns to the picker.
- On the after-action screen: run it again, share the result, or try another scenario.

## Notes

- This is a faithful copy of the web version. The scenario content and all the
  branching/scoring logic are compiled directly from the same source, so they are
  identical to the live tool. Only the styling differs (hand-written CSS here
  instead of the site's framework), which is what lets the file run with zero
  external dependencies, offline, forever.
- Everything is fictional. Names, companies, and scenarios are invented for training.
- Validated: 60,000 random playthroughs across the four scenarios with zero
  dead-ends, missing scenes, loops, or errors, and all seven endings reachable in each.
