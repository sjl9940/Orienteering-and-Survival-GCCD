# Tunables

Generated from `@tune` headers by the menu `CGDD/Export Trace Docs`. Hand edits are overwritten on the next export.

| Script | Field | Type | Range | Default | Note |
| --- | --- | --- | --- | --- | --- |
| ForestGameManager | levelOneAdditionalWood | int | 1-100 | 14 | Extra firewood required in Level 1. |
| ForestGameManager | levelOneMatchPickupCount | int | 0-20 | 4 | Random match bundles spawned in Level 1. |
| ForestGameManager | levelTwoMatchSpawnMinDelay | float | 5-300 | 18 | Minimum delay between new match pickups in Level 2. |
| ForestGameManager | levelTwoMatchSpawnMaxDelay | float | 5-600 | 28 | Maximum delay between new match pickups in Level 2. |
| ForestGameManager | levelThreeMatchSpawnMinDelay | float | 5-300 | 30 | Minimum delay between new match pickups in Level 3. |
| ForestGameManager | levelThreeMatchSpawnMaxDelay | float | 5-600 | 48 | Maximum delay between new match pickups in Level 3. |
| ForestGameManager | maxCampaignMatchPickups | int | 1-10 | 3 | Maximum uncollected campaign match bundles at once. |
| ForestGameManager | campaignMatchSpawnMinDistance | float | 4-100 | 8 | Minimum distance from player for a new campaign match bundle. |
| ForestGameManager | campaignMatchSpawnMaxDistance | float | 5-200 | 24 | Maximum distance from player for a new campaign match bundle. |
| ForestGameManager | levelOneNoteCount | int | 0-20 | 5 | Random readable notes placed in Level 1. |
| ForestGameManager | coyoteSpawnMinDelay | float | 1-300 | 32 | Minimum random delay before a Level 1 coyote spawns. |
| ForestGameManager | coyoteSpawnMaxDelay | float | 1-600 | 52 | Maximum random delay before a Level 1 coyote spawns. |
| ForestGameManager | coyoteRespawnDelay | float | 0-600 | 20 | Extra cooldown after each encounter before another coyote can spawn. |
| ForestGameManager | chasingFlashesToScareCoyote | int | 1-10 | 4 | Flashlight flashes needed to scare a coyote during its chase. |
| ForestGameManager | coyotesToKillForJacket | int | 1-100 | 10 | Coyote kills needed to unlock the gun progression and jacket. |
| ForestGameManager | levelTwoCoyoteMinDelay | float | 1-300 | 5 | Minimum Level 2 coyote spawn delay. |
| ForestGameManager | levelTwoCoyoteMaxDelay | float | 1-600 | 8 | Maximum Level 2 coyote spawn delay. |
| ForestGameManager | levelTwoCoyoteCooldown | float | 0-300 | 1 | Extra Level 2 cooldown after each coyote encounter. |
| ForestGameManager | levelTwoCoyoteWarningSeconds | float | 1-20 | 4.5 | Warning time before a Level 2 Coyote starts chasing. |
| ForestGameManager | gunShotRange | float | 1-300 | 80 | Maximum distance for shooting a Coyote. |
| ForestGameManager | gunShotCooldown | float | 0.05-5 | — | Minimum time between gunshots. |
| ForestGameManager | levelThreeDeadlineSeconds | float | 30-1800 | 420 | Maximum exploration time before Level 4. |
| ForestGameManager | levelThreeCoyoteDelayMultiplier | float | 1-10 | 4 | Multiplier for coyote delay during Level 3. |
| ForestGameManager | levelThreeNoteTexts | string[] | 1-20 | — | Editable campaign note text used to reveal the island story. |
| ForestGameManager | jacketColdDrainMultiplier | float | 0-1 | — | Hypothermia drain multiplier while wearing the jacket. |
| ForestGameManager | godHeightInPlayerHeights | float | 2-50 | 22 | Boss height as a multiple of player height. |
| ForestGameManager | cultureCampMapPosition | Vector2 | 0-1 | — | Normalized terrain position of the abandoned campsite. |
| ForestGameManager | cultureTempleMapPosition | Vector2 | 0-1 | — | Normalized terrain position of the western temple. |
| ForestGameManager | cultureEyeGroveMapPosition | Vector2 | 0-1 | — | Normalized terrain position of the eye-tree grove. |
| ForestGameManager | cultureShelterMapPosition | Vector2 | 0-1 | — | Normalized terrain position of the abandoned shelter. |
| ForestGameManager | godChaseSpeed | float | 1-20 | 3.4 | God movement speed during the final chase. |
| ForestGameManager | godStartDistance | float | 10-200 | 55 | Distance behind the player when the chase begins. |
| ForestGameManager | godExitInset | float | 5-100 | 14 | How far inside the terrain edge the final capture beacon appears. |
| ForestGameManager | godGrabDistance | float | 1-50 | 5 | Distance at which the God catches the player during the chase. |
| ForestGameManager | godFinalFadeSeconds | float | 0.1-10 | 2.5 | Duration of the final screen fade before the ending. |
| ForestGameManager | godChantVolume | float | 0-1 | — | Volume of the looping chant during the God chase. |
| ForestGameManager | godCatchGraceSeconds | float | 0-180 | 60 | Seconds the God chases before it is allowed to catch the player. |
| ForestGameManager | godGrowthPlayerHeightsPerSecond | float | 0-2 | — | How many player-heights the God grows each second. |
| ForestGameManager | godMaxHeightInPlayerHeights | float | 2-100 | 38 | Maximum God height as a multiple of player height. |
| ForestGameManager | gunBodyHitRadius | float | 0.1-5 | — | Shot tolerance around the Coyote body. |
| ForestGameManager | levelFourPlayerSpeed | float | 0-100 | 30 | Player movement speed during the Level 4 chase. |
| ForestGameManager | levelFourCoyoteMinDelay | float | 5-300 | 14 | Minimum Level 4 Coyote delay. |
| ForestGameManager | levelFourCoyoteMaxDelay | float | 5-600 | 22 | Maximum Level 4 Coyote delay. |
| ForestGameManager | levelFourCoyoteCooldown | float | 0-300 | 2 | Cooldown after a Level 4 Coyote encounter. |
| ForestGameManager | levelFourCoyoteWarningSeconds | float | 1-20 | 3 | Warning time before a Level 4 Coyote chases. |
| ForestGameManager | levelFourCoyoteSpawnMinDistance | float | 3-100 | 8 | Minimum distance ahead for a Level 4 Coyote spawn. |
| ForestGameManager | levelFourCoyoteSpawnMaxDistance | float | 4-150 | 16 | Maximum distance ahead for a Level 4 Coyote spawn. |
| ForestGameManager | levelFourCoyoteLateralRange | float | 0-30 | 2 | Side-to-side spawn spread for Level 4 Coyotes. |
| Movement | moveSpeed | float | 0-20 | 4 | Base walking speed for exploration. |
| Movement | jumpHeight | float | 0-5 | 0.75 | Player jump height. |
| Movement | sprintMultiplier | float | 1-3 | 1.6 | Speed multiplier while holding Shift. |

