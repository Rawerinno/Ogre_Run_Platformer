# Ogre Jungle Run

2D pixel-art platformer built in Godot 4. The player controls an ogre exploring hostile jungle ruins areas while fighting explorers, various animals, bosses and other enemies.

> Current version: **v1.27**

## Credits

**Alpha testers:** StCrown, Fino, Miroma, Coirato
**Bug Finders:** StCrown

## Version history

### First prototype
The original concept was a 2D pixel-style platformer set in a jungle. The player was a ogre holding a wooden club. Platforms were tree trunks and the first enemies were human explorers carrying torches. The first playable prototype included A/D movement, Space to jump, left-click club attacks, enemy patrols, pits that killed the player, and a tunnel at the end of a single level.

### v1.2
- Added procedural movement, jump, attack, hurt and death animations.
- Improved jungle scenery with trees, roots, vines and vegetation.
- Added fullscreen mode.
- Added attack and hurt sound effects.
- Added 3 player lives.
- Added player HP at 100/100 with a green bar.
- Added enemy HP at 20/20 with red bars.
- Wooden Club dealt 10 damage.
- Torch explorers dealt 10 damage.
- Falling into pits consumed a life and restarted the level.

### v1.3
- Fixed player attacks not damaging enemies reliably.
- Fixed the player becoming frozen after respawning.
- Redesigned the Ogre into a side-profile character.
- Improved running and jumping poses.

### v1.4
- Simplified the HUD so only lives were shown.
- Lives were represented with heart icons.
- Made the wooden club smaller and more believable.
- Shifted the art direction toward a darker, more hostile forest.
- Made the Ogre more intimidating.

### v1.5
- Moved the overall presentation closer to pixel art.
- Added pixel-art backgrounds.
- Player could move while attacking.
- Added coyote jump.
- Enlarged enemy collision areas.
- Extended Level 1 and added a third explorer.
- Added Level 2.
- Added spear explorers.
- Added diagonal platforms in Level 2.
- Added stomp damage when landing on enemies.
- Added variable jump height depending on how long Space is held.
- Changed lives to red pixel hearts.

### v1.6
- Increased spear-enemy attack range.
- Adjusted platform spacing.
- Generated darker pixel-art jungle backgrounds.
- Improved the Ogre running animation.
- Improved club placement.
- Added Level 3.
- Added gorillas that attack with their arms and launch the player upward.
- Increased Level 3 platforming difficulty.

### v1.7
- Added a title screen with PLAY and QUIT.
- Added low-volume forest ambience.
- Added blood effects.
- Reworked Ogre movement.
- Improved gorilla visuals.
- Added the Tiger boss.
- Shortened Level 1.
- Added diversified attack and death sounds.
- Added numeric enemy HP.
- Reduced player max HP.
- Added XP and player levels.
- Torch explorers awarded 2 XP, spear explorers 4 XP, gorillas 5 XP and Tiger 30 XP.
- Level requirements scaled upward.
- Leveling increased club damage and healed the player.
- Added a 10% critical-hit chance.
- Removed odd red dots from backgrounds.
- Refined platform consistency.
- Reworked Level 3 into a tower/temple climb ending in an aerial Tiger boss arena.

### v1.8
- Fixed unreachable platforms in Level 3.
- Enlarged the wooden club slightly.
- Reworked the game further toward true pixel art.
- Added a real Ogre spritesheet with idle, run, jump, attack, hurt and death frames.
- Reworked backgrounds with more consistent pixel sizing.
- Added a visible XP progress bar.
- Critical hits were changed to 200% normal damage.

### v1.9
- Slowed the Tiger boss.
- Enlarged and improved access to the boss arena.
- Made the XP bar smaller.
- Added level-up sounds.
- Added enemy-kill sounds.
- Added piano-like level-transition sounds.
- Converted existing enemies to pixel-art spritesheets.
- Reduced spear range and spear length.
- Improved player grounding/running presentation.
- Added an ESC pause menu with CONTINUE, RESTART and QUIT.
- Converted game UI wording to English.

### v1.10
- Reduced overall audio volume.
- Removed an unwanted bush/vegetation ambience sound.
- Made torch flames visible again.
- Rebuilt spear explorers and shortened their spears.
- Added a +1 DAMAGE level-up indicator.
- Reworked the Level 3 boss approach so the arena was farther to the right.
- Improved jungle backgrounds and ground presentation.

### v1.11
This version was intentionally rebuilt from v10 with only a small set of changes.
- Simplified the torch without changing the rest of the torch explorer.
- Shortened the spear without redesigning the rest of the spear explorer.
- Moved the Tiger arena to the right behind a gap.
- Tiger started at the far-right edge and activated only after the player entered the arena.

### v1.12
- Fixed the broken spear sprite that appeared as separated pieces.
- Made the spear slightly larger again.
- Allowed the player to fall from the right edge of the Tiger arena.

### v1.13
- Reworked ESC pause handling.
- Added a session timer.
- Simplified torch and spear visuals further.
- Removed three unwanted horizontal lines from jungle backgrounds.

### v1.14
- Strengthened pause input handling with a dedicated pause action and direct Escape detection.
- Slightly increased spear length.

### v1.15
- Changed pause handling again to direct per-frame Escape detection.
- Moved the session timer to the top-right and reduced its size.

### v1.16
- Added a jump sound.
- Added collectible coins and a coin counter.
- Reduced XP bar size.
- Tiger death now revealed a tunnel.
- Added Level 4 as a shop.
- Added Wooden Staff for 20 coins.
- Wooden Staff fires stone projectiles.
- Added purchasable Boots, Pants, Chest Armor and Helmet with damage-reduction bonuses.
- Added XP purchases at 2 XP per coin.
- Raised the player level cap to 100.
- Added Level 5 with harder parkour.
- Added Iron Soldiers using ranged weapons.
- Enemies began awarding coins: torch 1, spear 2, gorilla 3, Tiger 15.
- Tiger award remained 30 XP.

### v1.17
- Removed instructional text from the shop.
- Displayed shop items physically on pixel-art shelves.
- E became the shop purchase interaction.
- Purchased equipment became visible on the Ogre.
- Added a visual Staff-equipped Ogre variant.
- Simplified Level 5 and added alternate upper routes.
- Repositioned unreachable coins.
- Added Level 6.
- Added Stone Statues that remain stationary and fire horizontal projectiles.
- Iron Soldiers award 7 XP / 4 coins.
- Stone Statues award 10 XP / 6 coins.
- Replaced the jump sound.

### v1.18
- Repositioned more coins directly above platforms.
- Shop displayed item names and prices.
- Made equipped gear smaller and better aligned to player animation.
- Wooden Staff changed to left-click and replaced the normal melee attack while equipped.
- Added floating damage numbers for dealt and received damage.
- Converted platforms to one-way collision so the player can jump upward through them.
- Simplified a difficult Level 5 gap.
- Improved ranged-enemy projectile origin and slightly slowed its attack rate.

### v1.19
- Added player death sound.
- Added different death sounds for humans, gorillas, Tiger and other enemy categories.
- Smoothed the Level 3 transition toward the Tiger arena.
- Simplified shop visuals to item illustration + coin price + a small E prompt.
- Ensured the Staff visually replaces the Club.
- Expanded high backgrounds so jumping no longer exposed empty gray areas.
- Added physical-feeling tower walls in Level 3.
- Removed coin-pickup audio from enemy coin rewards so death sounds remain clear.
- Added Level 7 with a volcano/lava biome.
- Added Bats that patrol horizontally and deal contact damage.
- Added the Lava Golem boss and multi-fireball attacks.
- Bats awarded 6 XP / 3 coins.
- Lava boss awarded 45 XP / 22 coins.

### v1.20
- Fixed Level 3 transition coins being below platforms.
- Ensured the Staff replaced the Club visually.
- Better aligned invisible tower walls with background pillars.
- Made Stone Statues slightly taller.
- Added light gravity/arcing motion to thrown spear projectiles.
- Gorillas became able to retaliate against stomp attempts.
- Tiger gained a temporary spike-ball defensive state after five consecutive stomps.

### v1.21
- Reduced Tiger spike mode from 5 seconds to 2 seconds.
- Added transparent margins to spritesheets to reduce animation frame bleeding.
- Removed an excess transition platform before the Tiger arena.
- Temporarily raised player attack to 50 for testing.
- Required the player to enter farther into tunnels before transitions trigger.
- Added backward tunnels for returning to previous levels.
- Enemy HP state was made persistent across player deaths where applicable.
- Reworked pause handling again.
- Added title-screen tester credits.
- Windows executable was not bundled because export templates were unavailable in the build environment.

### v1.22
- Moved tester credits.
- Reduced Lava Golem fireball burst from 5 to 3.
- Added boss-adjacent respawn points when dying during boss fights.
- Added HP bars to Bats.
- Replaced the Iron Soldier crossbow with a wooden blowpipe/dart weapon.
- Darts deal low damage and slow movement by 50% for 2 seconds.
- Lava fireballs gained burn damage over 3 seconds equal to the initial hit, for 2x total possible damage.
- Added diversified tunnel-transition sounds and special boss-room transition sounds.
- Added Double Jump as a 30-coin shop purchase.
- Redesigned the Helmet to look more like warrior armor.
- Extended Level 5 background vertically.

### v1.23
- No public v1.23 package was produced; numbering moved directly to v1.24.

### v1.24
- Changed the shop XP icon from a coin-like symbol to an XP symbol.
- Player rendering was moved in front of tunnels so entry looks visually correct.
- Level transitions place the player close to the corresponding tunnel exit instead of too far forward/back.

### v1.25
- Removed the temporary 50 ATK testing value and restored normal base damage.
- Redesigned and centered the OGRE JUNGLE RUN title screen.
- Centered tester credits.
- Added a final congratulations message after completing the game.

### v1.26
Major systems/balance update:
- Removed physical enemy blocking/hitboxes so the player can pass through enemies in a Mario-like way while combat detection remains separate.
- Added an invisible wall behind the initial player spawn.
- Entering tunnels no longer restores HP.
- Collected coins stay collected for the rest of the run and do not respawn on death/level reload.
- Lost lives display as empty heart silhouettes.
- Fixed excessive coyote-jump height.
- Avoided placing Stone Statues on inclined platforms.
- Shortened/reworked the second-boss level.
- Adjusted Bat scale and HP display.
- Falling before the second boss respawns at the level start; dying to the boss can use the boss checkpoint.
- Reworked Tiger behavior and removed the knife.
- Repositioned armor boots visually.
- Increased slow-dart enemy damage.
- Formalized player stats: **ATK 10 / DEF 0 / MAX HP 30**.
- Each player level grants **+1 ATK, +1 DEF, +2 Max HP**.
- Armor purchases now add explicit DEF values.
- Wooden Club and Wooden Staff have 0 weapon ATK: damage comes from player ATK.
- Added safer Staff and spear spritesheet spacing.
- Replaced the Lava Golem concept with a giant Lava Slime-style boss that jumps high toward the player while keeping triple fireball attacks; landing on the player causes heavy damage.
- Added an on-screen ATK / DEF / MAX HP stats panel.
- Added an extra-life Heart pickup during the Level 3 tower climb with no hard maximum-life cap.
- Added a secret alternate route in Level 2 leading to an Iron Club chest.
- Added weapon inventory slots selectable with keys 1-9.
- Added death animations for Stone Statues and Bats.
- Added an original JRPG-inspired background track rather than copyrighted Persona music.

### v1.27
- Extended the original soundtrack to roughly 96 seconds with more variation.
- Redesigned the Ogre with a slimmer pixel-art silhouette.
- Added Left Shift sprint: **+30% move speed only while Shift is held**.
- Removed the DOUBLE text from double jumps.
- Reduced coyote time and made coyote jumps slightly weaker so they no longer feel overpowered.



## Status

This is an actively developed indie prototype.
