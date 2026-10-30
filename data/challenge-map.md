# How the challenge changes

Look first at whether win and loss change, then at whether the player's verb changes. If neither changes, it is the same game, just tighter or looser.

| Change | Win/loss changed | Verb changed | Data | Script.field |
| --- | --- | --- | --- | --- |
| Start: (describe baseline feel) | — (baseline) | — (player verb) | field=default | ScriptName.field |
| Coyote defense and death checkpoint | No (coyote catch / hypothermia still cause death; Level 1 completion still wins) | No (flash the flashlight) | coyoteSpawnMinDelay=32, coyoteSpawnMaxDelay=52, coyoteRespawnDelay=20, chasingFlashesToScareCoyote=4 | ForestGameManager fields |
| Campaign expansion: gun, jacket, notes, map, and God chase | Yes: reaching the map edge starts the only ending, where the God catches the player; being caught earlier also ends the run | Yes: explore and collect notes, shoot coyotes, then run from the God | coyotesToKillForJacket=10, levelThreeDeadlineSeconds=420, levelThreeCoyoteDelayMultiplier=4, jacketColdDrainMultiplier=0.12, godHeightInPlayerHeights=15, godChaseSpeed=6.1, godExitInset=14 | ForestGameManager fields |

The final sequence has one ending: the player cannot defeat the God or escape the island. Reaching the far map edge completes the chase by triggering the God’s scripted capture; the God can also catch the player before they reach it. Level 3 advances to Level 4 when all three campaign notes are read or the seven-minute timer expires.
