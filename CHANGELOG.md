# Changelog

## v101
- Arcade is longer: 8 bouts instead of 5, with the rival in the 4th and the Kingpin last
- New bouts: Back-Alley Brawl, Into the Pit and The Right Hand; the ladder screen shows all 8 stops
- The arenas rotate through the run, and the CPU difficulty ramps more gradually up to the same final boss

## v100
- Touch: flicking the stick twice now dashes (the stick was being treated as a keyboard, which never double-tap dashes)
- Touch and mouse: the Training menu has a BACK button
- Survival: your best run is saved when you restart or quit, not only when you lose; each bout rolls a new arena and is titled SURVIVAL: BOUT n
- Music 0% or Master 0% now also silences the vinyl crackle
- Starting Training or Combo Trials no longer resumes the last drill or recording playback
- Boss music stops when you leave the boss fight
- Playing as the Kingpin in Arcade: the last fight is the FINAL BOUT, not "FINAL BOSS: THE KINGPIN"
- Character select: up/down on the Kingpin no longer jumps to Rex
- Fixes to v98: a fighter ending a dash can't block one frame early, no K.O. voice line in practice, and the error guard only gives up on repeated errors

## v99
- Title screen: every fighter strikes their own signature pose instead of all throwing the same heavy punch
- Rex peek-a-boo guard that pops a jab, Danny holds the sparking clamp to the sky, Brutus flexes, Kira waves you in, Sensei stands in the crane
- Ember shows off the lit dynamite, Shade crouches with the blade out, Titan strikes the stiff-arm trophy pose, the Kingpin leans on his cane
- Tommy raises the knee in a Muay Thai guard, Skies toprocks, Will walls up behind his shield, Donna cocks a hip with the whip up
- Ghost floats, 40oz sways and takes a swig, Charcoal leans back and points the tongs at you

## v98
- Audit fixes: practice mode can no longer K.O. a fighter for good, and a long juggle no longer leaves the victim immune to air hits for the rest of the round
- Nothing lands on the K.O. screen, so a won round can't turn into a loss (Survival included); projectiles fly on harmlessly
- Launchers and throws on a platform stay on the platform
- Dash frames stop when you attack or get hit, so a backdash no longer resumes (or regains invincibility) after a move
- Only an idle fighter can block, both players block from this frame's input, and same-frame trades can end in a double K.O.
- No super, ultimate or rage cancels out of a throw clinch; armor and iron-body K.O.s get the full K.O. slow-mo
- A strike passing over a crouching fighter is a body hit, not a head hit; buffered presses keep the live stick and jump
- Glass Cannon rounds are now shorter, as promised
- Online: presses are no longer dropped while clocks sync, peer data is checked, mismatched builds are refused, stale room status and ping floods are gone, and an error closes the match instead of freezing the game
- Keys release and the fight pauses when the window loses focus; pause works during hit-stop
- Gamepad: can't drive the menu behind the online popup (B closes it), can cancel a key rebind, and B no longer skips the ladder screen by accident
- A corrupt settings save no longer skips the Kingpin unlock or the value checks; the kill cam stops recording after its replay

## v97
- Hits have weight: hit-stop, screen shake and the victim's rattle scale with the damage instead of two fixed tiers
- The camera kicks in the direction the hit travels and springs back; blocks get a small kick too
- Still arcade: knockback distances and combo timing are unchanged

## v96
- Real ragdoll KO: the loser's body is a jointed physics ragdoll (Verlet points and sticks) that whips off the hit, flops, crashes into the floor and skids
- New K.O. screen: a black slab slams across, K.O. punches in with overshoot, the winner's tag, the victory quote, then an R.I.P. line
- 27 new R.I.P. captions: dark jokes plus jokes about how much of this game was made by AI
- More AI jokes in the round tips and hit memes

## v95
- KO sends the loser flying off the screen in a spinning ragdoll, limbs flailing, instead of a short knockdown
- Forward dash: a low lunge with the lead hand up and the rear arm pumping back, back leg driving off the toe
- Backdash: a hop back with the guard up and the front foot tucked
- Air dashes lean into the dash with the legs trailing, or tuck up when dashing backward
- Dash streak afterimages are fainter
- Shadow frames no longer freeze in place after the round ends

## v94
- Block bubble: a faint shield flares around the defender on each blocked hit and fades through blockstun; white on a perfect block, red when the guard is close to breaking
- High guard holds the gloves at the chin and temple; crouching guard drops the forearms to cover the body
- Blockstun keeps the guard up and braces the back foot as the defender slides back, instead of reusing the hit reaction

## v93
- Grabs: both fists lock onto the collar, then heave forward or swing the body back over the shoulder on a back throw
- Grabbed fighters get pulled onto their toes, back foot dragging, both hands prying at the grabber's wrists
- Thrown and launched fighters tip back instead of cartwheeling: arms fling up, knees tuck, then arms reach back to slap the floor
- Landing settles onto the back with one knee up; getting up rocks through a kneel with a hand pushing off the floor
- Shadows stay on the floor and shrink with height instead of floating under airborne fighters
- Thrown bodies leave faint shadow frames instead of bright copies; grabs leave none
- Brutus's shoulder strap follows the torso lean

## v92
- Jump punches angle down at the opponent instead of punching level
- Flying kicks angle down with the other leg tucked under
- Sweeps drop low, lean over the leg, and plant a hand on the floor

## v91
- Hit reactions match where the hit lands: head hits whip the head back with arms flung, body hits double the fighter over clutching the gut, leg hits buckle the knees with arms out for balance

## v90
- Kicks look like kicks: the foot leaves the floor, the knee chambers up, the leg snaps out to the target, then re-chambers and steps back down
- The kicking leg is drawn in front of the body so high kicks no longer vanish behind the torso
- Low kicks never dip below the floor

## v89
- Hits make a small pop right at the point of contact instead of big circles and spark sprites
- The fist or foot that lands catches fire for a moment (longer on heavy hits and counters)
- Parry, guard break and other event rings are now small bursts, no circles
- Fewer, shorter hit streaks from the contact point

## v88
- Body-part hit zones: head hits do +25% damage, body hits normal, leg hits -15% (HEAD/LEGS callout on hit)
- Training hitbox viewer (key 0) shows the head, body and leg hurtboxes and the strike height of each attack
- Removed the punch/kick motion arc that showed how far an attack reaches

## v87
- Punches look like punches: fist starts at the chin guard, cocks back on heavies, snaps out to a fully straight arm with the shoulder driving forward, then returns to the guard
- Rear hand stays home at the chin during punches
- Boxing gloves sit on the hand: cuff at the wrist, padded fist past it, lined up with the forearm; Rex wears both gloves
- Removed the big expanding circles on hits and the circles around fighters during counter, armor and boss moves

## v86
- Held props (bottle, dynamite, parcel, spray can, shield, cane, gloves) follow the real hand in every pose instead of floating at a fixed spot
- Thrown props leave the hand on release and come back only once the projectile is gone (40oz bottle, Ember dynamite, Kira parcel, Charcoal's coal)

## v85
- Natural fighting stance: both knees bend forward, guard hands up at the chin with elbows tucked (boxing stance)
- Punches and kicks lunge the hips forward with the back foot planted instead of stretching the arm or leg
- Limbs never stretch past their real length (projectile pushes, uppercuts, blockstun)
- Runner's arm swing: hand forward, elbow driven back
- Elbows bend downward on punches, blocks and victory flex
- Swing arcs removed; strikes leave faint shadow frames instead

## v84
- Fix: fighters could sink below the floor after a wall bounce near the ground
- Fix: Restart Match in Survival restarts the whole run (no free full heal)
- Fix: Esc on character select goes back to the Training menu from Training, Combo Trials and Survival
- Combo Trials text moved down so it no longer overlaps the combo counter
- Audit: 256 CPU matchups, rollback replay and every mode checked with no errors

## v83
- Knees and elbows really bend: two-part limbs fold when crouching, jumping and guarding, and straighten on full punches and kicks
- Smoother jump legs, proper legs during air attacks, knocked-down legs lie flat
- Hit shake only during hit-stop instead of the whole hitstun
- Arcade stage screen never shows a knocked-out fighter or an empty quote box
- Version number (v0.083) shown at the top of every menu

## v82
- Training is now a tabbed menu: Training, Combo Trials, Survival
- Combo Trials: 12 saved challenges from a 3-hit combo up to 25 hits, air and wall juggles, damage combos
- Survival: one life against endless random CPUs, one round each, heal 30% per win, best run saved
- UI audit: joke toasts no longer cover menus and buttons
- Title outlines no longer spike; overhead callouts are outlined and no longer overlap
- Frame-advantage popups only in training
- Softer screen flashes (supers, ultimates, big hits); low-health bar pulses instead of strobing
- Floor stains fade out; K.O. text gets a dark band; combo trial list aligned

## v81
- Story doubled to 32 chapters: the Kingpin escapes at Chapter 16, a second act against the Board, and a final crown rematch
- Red health: 40% of each hit can heal back after 2s without being hit
- Air tech: press Grab once launched hitstun ends; mashing early locks you out for 40 frames
- Combo breaker: S+G during a 3+ hit combo, costs 50 meter (free in training)
- Training hitbox viewer (key 0)
- Super defence scaling: hits after a super/ultimate in the same combo do 70%
- Hard knockdowns: supers, ultimates and big launchers can't be ground-teched (50f down)
- Tech roll: hold left/right while teching on landing to roll
- DI: hold up/down/away while launched to change your trajectory
- Training: - freeze, = frame step, [ save state, ] load state
- In-game CHANGELOG screen on the main menu
- Air combos: juggle points (20 per combo; light 1, heavy 2, special 3, supers free) replace the 5-hit air cap
- Air hits float the opponent and hang you in the air; juggle gravity gets heavier as the combo grows
- Air jump-cancel: press up on hit in the air to chase the juggle (once per jump)
- Juggles hang longer, and longer still near the wall (wall juggles)
- Long-combo damage decay so 25–30 hit combos land 30–50%, not a kill
- Removed the green heal rings
- Frame data HUD names the move in startup/active/recovery
- Fix: moves stuck in recovery after landing a hit

## v80
- Story expanded to 16 chapters; roster unlocks through story mode (5 starters)

## v79
- Charcoal recoloured green with gold accents

## v78
- Balance pass: Tommy grab 16→13, Forgotten 150f, Blackout stun 18f, HP retune (CPU win rates 46–55%)

## v77
- Slow-motion instant replay kill cam after every KO (offline, skippable)

## v76
- Audit fixes: netplay determinism for samples and hit text, rollback no longer replays hit sounds or sprites, sprites follow camera, supers on platforms, round reset clears effects

## v75
- Hit sprites fade to soft glows, never square boxes

## v74
- Kenney CC0 hit/UI sounds, jingles and particle sprites; Bangers title font (credited)

## v73
- Super cut-ins, visuals and sounds for every new mechanic

## v72
- Audit fixes (Ghost invisibility, training resets, CPU supers, honest move list, low slides) and rebalance

## v71
- Balance pass from CPU sims; combos and fighter text match the new moves

## v70
- Every super and ultimate has its own mechanic: heal, bounty, armor, confuse, blackout, quake, slow, burn, grapple, invisibility, lifesteal, vortex

## v69
- Backstory moves for Skies, Donna, Ghost, 40oz and Charcoal; move-list text matches the new specials

## v68
- Backstory moves for Ember, Titan, Kingpin and Tommy

## v67
- Backstory moves for Rex, Danny, Brutus, Kira and Sensei

## v66
- Shift dashes (keyboard double-tap removed); How to Play updated

## v65
- Kick lean, two-hand projectile push, victory pose, flat waistband

## v64
- Run cycle, guard stance, jump tuck, hit recoil, grabbed and KO poses

## v63
- Hips so legs join the body

## v62
- Wider stance; back knee no longer bends forward

## v61
- Far arm from the rear shoulder behind the torso; legs in a front/back stance

## v60
- One input tracker in training, arrows and buttons only

## v59
- Clean text (no fake-bold Impact, kerning on), labels fit their boxes, aura particles in front of every fighter, ladder layout fix

## v58
- Outfit detail pass: torso shading, vests, belts, badges, aprons, sashes

## v57
- Every fighter gets their own body colours

## v56
- How to Play split into 8 short tabs that fit on one screen

## v55
- game-icons.net touch icons; plain-language combo key tab

## v54
- Special, super and ultimate are distinct for every fighter; bigger touch icons, no outline

## v53
- Touch buttons with dark outlines and filled icons

## v52
- Line-art icons on touch buttons; buttons more transparent

## v51
- Touch buttons: two big attack buttons, smaller icon buttons in a thumb arc

## v50
- Wide phone screens keep the game's shape; sides extended instead of stretched

## v49
- Fill the whole phone screen; auto fullscreen + landscape on first tap

## v48
- Tap to advance story and other button-less screens

## v47
- Any connected controller drives P1 (fixes ghost pad in slot 0 stealing input)

## v46
- How to Play shows touch controls on phones

## v45
- Touch controls for phones (floating joystick + action buttons)

## v44
- Super/Ult/Rage keys never fall back to attacks; double-tap down drops through platforms

## v42
- One-key Super (U), Ultimate (O), Rage (Space)

## v41
- Removed local Versus mode and P2 keyboard controls

## v40
- Clear controls table in How to Play

## v39
- Story props in every fighter's hand + story-matched projectiles

## v38
- Charcoal ultimate is now Jerk Pit Eruption (marching fire geysers)

## v37
- Charcoal ultimate reworked into smoke-teleport 7-hit flurry; game served directly at index.html, old links redirect to latest

## v36
- Updated How to Play (meter tab, full roster, super/ult/rage keys)

## v35
- Subtler auras

## v34
- Distinct per-fighter auras, Rex uppercut ult, Ember fire-pillar Inferno, Titan ground-smash Final Drive

## v33
- First tracked release; Pages launcher and README
