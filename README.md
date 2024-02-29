# Asteroblaster
The space shooter of time trials

## Game Development Progression

KEY:
	ISSUE:       Something isn't working right
	CHANGE:      Something doesn't feel right
	MVP:         Minimally viable product
	ENHANCEMENT: New feature work but not MVP (wish)

## ISSUES:
- [x] LOGIC: Fix electric CodW collision with instances causing streaking
- [x] LOGIC: Fix broken screen shake
- [x] LOGIC: Bullets are not shooting through powerups
- [x] BREAK: Fix bullet collision with bullet, only one can win
- [x] LOGIC: Fix enemy missiles blowing up on themselves
- [x] LOGIC: Fix hunter bullets not firing
- [x] LOGIC: Music isn't always stopping when entering the space garage
- [x] LOGIC: Score asteroid at close range not giving enough bonus
- [x] LOGIC: When do we show laser sprite?
- [x] LOGIC: Laser color should be green if we have energy to fire a second time
- [x] LOGIC: When entering the gameover room, the die sound plays twice
- [x] LOGIC: Description for powerup drop rate is wrong. Also should show zero chance for level 0.
- [x] LOGIC: Some small asteroids can go through the ship
- [x] LOGIC: Powerup point of bullet creation is off
- [x] LOGIC: Fix game restart issue
- [x] LOGIC: Score drops persist on ship respawn
- [x] LOGIC: Pause menu not synced with camera
- [x] LOGIC: Missing juggo pause control mapping
- [x] LOGIC: After unpausing, the JUGGO ui goes underneath the laser ui
- [x] LOGIC: Hangar credit labels are not adjusting correctly
- [x] LOGIC: Ship not disappearing in hanger

## CHANGES
- [x] Picking up a powerup will not downgrade a weapon if a stronger weapon is active. It will refresh the current weapon.
- [x] The hunter bullets to homing missiles
- [x] Font for displaying numbers (monospace)
- [x] Update win condition. Use time(?) for how long a level lasts
- [ ] ~Brute should also be slowed by bullets~
- [x] Add laser score to hit factions
- [x] Add some pizzaza to the laser graphics
- [x] Format display numbers
- [ ] ~Laser hitting asteroid should not split it in two, and give bonus based on larger sizes~
- [x] The main music
- [x] Powerups should slowly move towards the ship when within a given range
- [x] Color of shields to make it standout more
- [x] Space garage should tell the user that the cooldown does or does not have cooldown weapons already purchased
- [x] Update current sounds with higher quality
- [ ] New enemy and maybe ship sprites?
- [x] Laser should be a purchased item rather than a powerup
- [x] Shields should be some kind of live effect that dissipates with time to give a visual indication of duration
- [x] Laser should be fired from left trigger
- [x] Electric should be fired from left bumper
- [x] The credit multiplier indicator to the sprite version?
- [x] Garage room to GUI Hanger room
- [x] Consecutive hits on a missile should give added bonus
- [x] Add more colors to the drop score
- [x] Make easy mode easier
- [x] Juggo slashing style animation to spice up the action
- [x] Juggo scoring tailored to faction type and size
- [x] Electric & Laser bars to be icons that animage to full. Also include Juggo's icon.
- [x] Juggo should push the brutes backwards a distance rather than doing damage.
- [x] Juggo key mapping from shift to control
- [ ] Add a level completion bonus after level 2. 10K with increasing per level
- [ ] Add an interest earned bonus for carryover funds not spent. Capped at xxx amount.

## MVP:
- [x] Intergrate game pad controller support - ship
- [x] Intergrate game pad controller support - menu
- [ ] Create website for leaderboard
- [ ] Create database for leaderboard
- [ ]    * Also In game?
- [x] Purchase domain - asteroblaster.com
- [ ] Create kick butt scores page to replace the game over page
- [x] Create an electric (circle of death weapon) that is always available to ship with cooldow. The circle expands outwards from the ship the entire view that also nets you a +score
- [x] Electric CodW should be on a cooldown so it can't be spammed
- [ ] ~Link GX.Games challenges to the game~
- [x] Add a slick screen transition between the rooms
- [x] Add a slick screen transition between the ship respawns
- [x] Add new sounds for various actions:
- [x]	 * space garage scroll and move around
- [x]	 * when picking a powerup drop
- [ ]	 ~space engines?~
- [ ] ~Store cooldown needs to have bulk update or allow for repeated quick purchases~
- [x] Implement credit drop score bonus
- [x] Pause button
- [ ] ~Game pad vibration with camera shake (NOTE This function is currently only available for the standard Windows, PS4 and Xbox One target modules)~
- [x] Bullet shooting should be on a cooldow with a visual bar. Play sound when spent.
- [x] Asteroid explosions sound calculated on sprite size and distance from ship
- [ ] Display difficulty indicator for medium and hard
- [x] Add store items
- [x]    * Reduce bulled spent times, maybe piggyback on the COOLDOWN?
- [x]    * Increase max spent
- [x]    * Increase mode score bonus
- [x] Better splash screen (start or home room)
- [x] Add bullet clip state to gui
- [x] Juggo use sound
- [ ] Level-Long Credit Multiplier
- [ ]    * Destroying 3 or 4 Raider rockets in a row rewards LLCM
- [ ]    * Destroying 2 or 3 Hunters with Juggo rewards LLCM
- [ ]    * Destroying a single Hunter bullet rewards LLCM
- [ ]    * Destroying Brute with laser rewards LLCM
- [ ]    * LLCM award should include a slick twirling animation
- [ ] Store item Heatsink to refresh primary repeater

## ENHANCEMENTS:
- [x] Create lurching forward function that is always available to ship when purchased
- [x] Create side car gunner that can attach to rear side of ship (two in total?) that has independent targeting that also nets you a +score
- [x] Create levels that increase intensity starting with one type of danger and adding new dangers as levels increase.
- [x]   * (level 1) Asteroids only.
- [x]   * (level 2) Asteroids & hunters.
- [x]   * (level 3) Asteroids, hunters, and raiders.
- [x]   * (level 4) Asteroids, hunters, raiders, and brutes.
- [ ]   ~Each level advanced grants one extra life~
- [ ] Create boss fights for levels ? and up. Last boss will throw asteroids at you including other dangers
- [ ] Mini map radar
- [ ] ~Also back up camera style indicator on HUD to indicate where incoming enemy is~
- [ ] ~Asteroids should be built from code rather than sprite (done but obmitted due to complexity of collision detection with ship and special weapons since the game is fully built around sprites)~
- [ ] ~Background stars should be built from code rather than image~
- [ ] Play ambiant sounds in start room and garage
- [ ] Enemy pathfinding
