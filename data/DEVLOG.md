# DEVLOG

Only append. Do not edit old sections. Two samples stay so students can see the format.

Only changes to the game itself are logged: the verb, win and loss, pressure, and what the player can feel.
Site language, diagram styling, and click-to-read-script do not go into an Interaction or a Stage Reflection.

Each gameplay change should add a section `## Interaction NNN — title` (the Agent can append this when it changes the game).
Add `## Stage Reflection NNN — title` only when you ask for one: Keep / Change / Cut, and which AI suggestions you accepted or rejected. That reflection stays on the game.

## Interaction 000 — EXAMPLE (sample, do not delete)

- Date: —
- Who asked: teacher (sample)
- Request: Tighten one tunable and see if it is still the same game.
- What changed: Sample only. The current code was not changed. A real change would touch only one `@tune` field.
- Result: The player's verb did not change. Win and loss did not change. Pressure changed, not the skeleton.

## Stage Reflection 000 — EXAMPLE (sample, do not delete)

### Keep
- A core verb you can say in one sentence, and a clear win/loss.

### Change
- To make it harder, turn an existing `@tune` first. Do not add a new system yet.

### Cut
- No shop, no deep inventory, no optimization that is off-lesson.

### AI
- Accept: tune feel with existing fields; avoid opening new scripts.
- Reject: GraphView, object pools, long hand-written scene YAML. This class is about script relationships and tunable numbers.


## Interaction 001 — Match pickups and field notes

- Date: 2026-10-26
- Who asked: student
- Request: Add scarce match pickups and readable notes with distinct visuals.
- What changed: Level 1 now places four match bundles among fourteen firewood pickups; each bundle adds two matches. Five readable notes spawn at separate random locations and open/close with R. Match count, spawn counts, spacing, and note text can be edited in the ForestGameManager Inspector.
- Result: The player can search for extra warmth and read environmental story details. Win/loss and the core survival objective did not change.


## Interaction 002 — Coyote chase defense and helicopter checkpoint

- Date: 2026-10-27
- Who asked: student
- Request: Let the player scare coyotes during a chase, make spawn timing editable, and keep deposited firewood after death.
- What changed: Flashing can now repel a chasing coyote after four aimed flashes. Spawn frequency is tunable with a random minimum/maximum delay plus a fixed post-encounter cooldown. Death restarts preserve firewood already deposited at the helicopter; carried wood is lost. Level replay after completion still begins from the tutorial deposit.
- Result: Win/loss conditions and the player’s flashlight action stayed the same. The coyote chase is more recoverable and helicopter deposits now preserve objective progress.


## Interaction 003 — Campaign expansion and God capture ending

- Date: 2026-10-30
- Who asked: student
- Request: Add the culture-board ideas as playable spaces and story clues, then add Levels 2–4 with the requested controls and final chase.
- What changed: Level 2 teaches the separate flashlight and gun actions: flashlight misses repel coyotes, while a body hit kills one; ten kills unlock the jacket and Level 3. The jacket reduces cold drain to 12%. Level 3 places three campaign notes and a map opened with F; finding every note or reaching seven minutes starts Level 4. The final God is a bipedal, Inspector-scaled stand-in that chases the player to the far map edge. Reaching the edge triggers the only ending, a scripted capture; the God can also catch the player earlier. Added abandoned camp, shelter, temple, eye-tree grove, and repeated trail symbols as in-world culture-board landmarks.
- Result: The player now explores, reads, aims and shoots, and runs. The final outcome is still capture, with the edge serving as the chase objective that triggers it. Level progression adds new actions and pressure rather than a separate safe victory.

## Interaction 004 — Gun hunt and growing God chase

- Date: 2026-10-30
- Who asked: student
- Request: Make the gun mode more active, support warmth in Levels 2–3, make Level 3 easier to navigate, and give the final chase more time and escalation.
- What changed: Gunfire now plays the project’s gun sound and sends a visible projectile; direct body hits kill Coyotes while misses scare them away. Level 2 uses shorter Coyote spawn intervals, and Levels 2–3 receive timed match bundles. Level 3 points to the F map, nearby notes, and named landmarks. In Level 4 the God chases immediately, grows over time, moves more slowly, and cannot catch the player for 60 seconds; the chant loops during the chase.
- Result: Shooting, survival supply, note finding, and escape pressure are more active. The player’s actions and campaign ending remain the same: reaching the God ends in capture.


## Interaction 005 — Cutscene death recovery and level skip

- Date: 2026-10-30
- Who asked: student
- Request: Fix repeated death after the Level 1-to-2 Coyote transition and add a key to skip a level.
- What changed: Dying to the Level 2 tutorial Coyote now offers a safe continuation into Level 2 instead of replaying that Coyote encounter. The restart button and R key use the same recovery route. Pressing P skips the active tutorial or campaign level and advances to the next stage; during the final chase it triggers the existing capture ending.
- Result: The transition cannot trap the player in a repeated Coyote death, and P advances the campaign without changing its final outcome.


## Interaction 006 — Accessible notes and a dangerous final run

- Date: 2026-10-30
- Who asked: student
- Request: Move the blocked Level 3 note, make the God chase feel faster, add Coyotes to Level 4, and change the map-edge ending.
- What changed: Level 3 notes now search nearby ground for a player-sized clear spot around each landmark. Level 4 sets movement speed to 30, places a Coyote in the route at the start, and spawns later Coyotes on an adjustable timer. Reaching the beacon triggers the God’s three-line confrontation before the capture animation. The existing jumpscare scream plays when the God bites.
- Result: Note spots avoid scene colliders, the final run adds immediate enemy pressure, and reaching the map edge leads to a distinct capture scene. The final outcome remains capture.
