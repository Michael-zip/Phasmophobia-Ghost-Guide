## General Ghost Mechanics

### Hunting
- **Speed**: Most ghosts are of <u>Normal</u> speed and will slightly speed up when a player is in their line of sight. 
- **Start Condition**: Initiates a hunt at 50% sanity or lower.
- **Cooldown**: 25-second cooldown between hunts.
- **Smudge Stick Safety**: 5 seconds of immunity during a hunt. Then after the hunt is over the <u>No-Hunt Timer</u> will start.
- **No-Hunt Timer**: 90 seconds where ghosts can't hunt after lighting a Smudge Stick.
- **Lights**: All lights go out at end of hunts.

### Interactions
- **Object Throwing**: 50% chance to throw an item every 0.5 seconds.
- **EMF-2**: Most of the time this is an indication of a hidden ability

### Electrical
- **Breaker Off**: Restore lights by flipping the breaker back on.
- **Breaker Overload**: Overloading turns off all lights.

### Miscellaneous
- **Models & Stance**: Some ghost will be able to change their stance going from crawling, walking, broken-back, but only the **`Obake`** can change models.
- **Hidden Abilities**: Hidden Abilities will be marked with a `[H]`
- **Speed Information**:
    + **Slow**: `1.4 m/s` *or lower*
    + **Normal**: `1.6 m/s`
    + **Fast**: `2.5 m/s` *Jinn, Raiju*
    + **Very Fast**: `2.7 m/s` *Thaye, Hantu*
    + **Extremely Fast**: `3 m/s` *Only Revenant, Deogen, Moroi*
    ---
    + **Players Walk Speed**: `1.6 m/s` 
    + **Players Sprint Speed**: `3 m/s`

## Spirit 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **No-Hunt Timer**: Extended to 180 seconds (3 minutes) when using a Smudge Stick.

### Strengths and Weaknesses
- **Weaknesses**: Extremely vulnerable to Smudge Sticks; using one extends the No-Hunt Timer to 3 minutes.


## Wraith 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Behavior**: Cannot teleport during hunts.

### Strengths and Weaknesses
- **Strengths**: Teleports to/near players and leaves an EMF reading at the teleport point. `[H]`
- **Weaknesses**: Rarely touches the ground, making it immune to Salt. Use Motion Sensors above Salt for easy detection.

### Interactions
- **Spirit Box**: Highly responsive.
- **Post-Teleport Behavior**: Returns to its preferred room after teleporting.


## Phantom 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Blink Rate**: Exhibits extended periods of invisibility during hunts, making it especially difficult to see. When it does appear, it's for a much shorter duration than other ghosts. `[H]`

### Strengths and Weaknesses
- **Strengths**: Sets a path to a player and leaves an EMF level 2 reading at the start of its path.
- **Weaknesses**: Disappears when photographed during ghost events and potentially hunts as well.

### Interactions
- **Photographic Evidence**: If a photo label reads "Ghost," the Phantom will not be visible in the photograph.


## Poltergeist 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Object Throwing**: Capable of rapidly throwing multiple objects simultaneously during hunts.

### Strengths and Weaknesses
- **Strengths**: Throws objects with extreme force and reduces player sanity by 2% for each object thrown. `[H]`

### Interactions
- **Object Throwing**: Guarantees object throwing every 0.5 seconds if objects are nearby, making it highly active in cluttered environments.


## Banshee 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`). This ghost will Speed up over time during the hunt.
- **Target Selection**: As soon as the house door is unlocked, the Banshee selects a single player as its primary target. This target remains fixed unless the player either dies or leaves the game. If the chosen target isnt in line of sight, the Banshee will temporarily switch its focus to another player until the initial target re-enters the house.
- **Sanity**: Hunts triggered by the sanity level of the chosen target, starting at 50% or lower.

### Strengths and Weaknesses
- **Strengths**: Drains 15% sanity from the player during specific events.
- **Weaknesses**: Often sings, making it easier to identify (not during hunts).

### Interactions
- **Sound Behavior**: 30% chance to scream, detectable via Para Mic.
- **Roaming**: Roams toward its chosen target only if they are on the same floor. This avoids unnecessary travel on large maps.


## Jinn 👻

### Hunting
- **Speed**: Moves at a normal speed of `1.6 m/s` when out of line of sight, but will return to normal speeds `1.6 m/s` when close to a player. When the Jinn spots its target, the speed accelerates to `2.5 m/s` when the Jinn sees its target and maintains line of sight.

### Strengths and Weaknesses
- **Strengths**: Lowers player sanity by 2% when close. Cannot turn off the breaker but can overload it by activating multiple lights, causing the breaker to trip.
- **Weaknesses**: Loses effectiveness if the electrical breaker is off.

### Interactions
- **Electrical Behavior**: Produces an EMF level 2 reading near the breaker when in proximity to players.
- **Breaker Interaction**: The Jinn will not manually turn off the breaker. However, it can cause it to trip by turning on lights throughout the house. You can distinguish this from a manually turned-off breaker by checking the position of the light switches. If they are in the 'off' position, the breaker was tripped, potentially indicating a Jinn.


## Mare 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`).
- **Light Sensitivity**: Initiates a hunt at 60% player sanity in dark areas and 40% in lit areas. Inapplicable in Nightmare mode.

### Strengths and Weaknesses
- **Strengths**: Has a higher chance of breaking lights during ghost events. Less active when the area is well-lit.
- **Weaknesses**: Cannot operate light switches, but can operate everything else.

### Interactions
- **Light Behavior**: Will move to a different room or reduce activity if lights are turned on in its current location. Instantly deactivates light switches in its vicinity.


## Revenant 👻

### Hunting
- **Speed**: Moves at `1.0 m/s` when not targeting a player, and `3.0 m/s` when chasing a player or moving towards players last known location.
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Speed increases drastically when it spots a player. To evade, break line of sight and silence all equipment.
- **Weaknesses**: Slower when not targeting a player.

## Shade 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: Initiates hunts at an average team sanity of 35% or lower.

### Strengths and Weaknesses
- **Strengths**: Highly inactive, making it harder to locate. Increases activity when no one is in the house.
- **Weaknesses**: Less active and won't perform ghost events if team sanity is 100%.

### Interactions
- **Visual Cues**: High chance to appear as a shadow during ghost events. Use Ghost Writing as an easy evidence clue.

## Demon 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: Can hunt regardless of player sanity levels.

### Strengths and Weaknesses
- **Strengths**: Reduced cooldown between hunts. Crucifix effectiveness varies: T1 is `4.5m`, T2 is `6m`, T3 is `7.5m`.
- **Weaknesses**: Smudge sticks provide a 60-second no-hunt window.

## Yurei 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: Initiates hunts when player sanity falls to 50% or lower.

### Strengths and Weaknesses
- **Strengths**: Drops player sanity by 15% if nearby. Confined to its room for 90 seconds after being smudged.
- **Weaknesses**: None specified.

## Oni 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Highly active, performs more events than any other ghost type. Extremely fast blinking (0.1-0.5 seconds) Basically is visible all the time due to its blinking.
- **Weaknesses**: Cannot perform "air ball" ghost events.

### Interactions
- **Sanity Drop**: Drops player sanity by 20% during certain ghost events.

## Yokai 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: Initiates hunts if players talk nearby and have a sanity of 80% or lower.

### Strengths and Weaknesses
- **Strengths**: Activity increases with nearby player conversations.
- **Weaknesses**: Limited range (2m) to hear voices and detect equipment.

### Interactions
- **Audio Cues**: More vocal interactions result in increased activity.

## Hantu 👻

### Hunting
- **Speed**: Very Fast (`2.7 m/s`) in cold areas, slower (`1.4 m/s`) in warm areas. Cold areas include snowy conditions or if the breaker is off.
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Speed increases in cold areas. Prefers to turn off the breaker to make the environment colder.
- **Weaknesses**: Slower in warm areas where lights are on.

### Interactions
- **Evidence**: Always provides Freezing Temperatures as evidence.

## Goryo 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Cannot change ghost room. Visible only through D.O.T.S. and only from a video camera.
- **Weaknesses**: Limited to its ghost room and won't roam very far, might still roam a bit.

### Interactions
- **Evidence**: D.O.T.S. is fixed evidence.

## Myling 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Virtually silent during hunts; footsteps are only audible when it's close. Active on the Parabolic Microphone.
- **Weaknesses**: Can be slightly heard before equipment malfunctions.

## Onryo 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: Can hunt at 60% sanity if no candles are blown out.

### Strengths and Weaknesses
- **Strengths**: Prevented from hunting within a 4m range of an unblown candle. Increases hunting likelihood with more kills.
- **Weaknesses**: Limited by the presence of candles.

### Interactions
- **Audio Cues**: Blown-out candles can indicate an impending hunt. Combine candles and crucifixes to confirm an Onryo.

## The Twins 👻

### Hunting
- **Speed**: Main ghost is `1.76 m/s` (10% faster), Decoy is `1.44 m/s` (10% slower).
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Two entities; one real, one decoy. Unpredictable hunts due to "Twinteraction."
- **Weaknesses**: Decoy is faster but not as lethal as the main ghost.

### Interactions
- **Visual Cues**: Rapid spikes in activity can indicate their presence. Spirit Box and Freezing Temperatures are common evidence.

## Raiju 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`), **Fast**: `2.5 m/s` near electrical items.
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Larger radius to disrupt equipment. Requires active electronics to be affected which means handheld or mounted equiptment.
- **Weaknesses**: Similar to Myling, but can be distinguished by its speed near electrical items.

## Obake 👻

### Hunting
- **Speed**: Normal (`1.6 m/s`)
- **Sanity**: No specific rules.

### Strengths and Weaknesses
- **Strengths**: Rarely leaves fingerprints, which may be six-fingered and are time-sensitive.
- **Weaknesses**: Fingerprints can become invisible under other light sources.

### Interactions
- **Visual Cues**: 6.66% chance to shapeshift during blinks in a hunt. Fingerprints are fixed evidence.

## The Mimic 👻

### General Overview
- **Evidence**: Fingerprints, Spirit Box, Freezing Temperature, and Ghost Orbs (extra)
- **Special Behavior**: Mimics other ghost types periodically.
- **Identification Clue**: Unique in showing Ghost Orbs in addition to its primary three pieces of evidence.

### Hunting
- **Speed**: Normal (`1.6 m/s`) or depends on the ghost it is mimicing.
- **Sanity Trigger**: Initiates hunts at 50% sanity or lower, following general ghost mechanics, or depends on the ghost it is mimicing.

### Strengths and Weaknesses
- **Strengths**: 
  - **Adaptability**: Can imitate any ghost type, inheriting their characteristics like hunt thresholds and special abilities.
  - **Elusiveness**: Its mimicking ability can mislead players.

- **Weaknesses**: 
  - **Static Evidence**: Unlike other evidence, its unique Ghost Orbs remain stationary in the ghost room.
  
### Special Abilities
- **Mimic Timer**: Changes which ghost it imitates every 30 seconds to 2 minutes. Cannot change during hunts.
- **Mimic Limitations**: Cannot imitate certain traits of Goryo and Thaye. Becomes a "default" ghost when mimicking itself or the player.

### Additional Information
- **Identification Strategy**: If you see three pieces of evidence plus Ghost Orbs, suspect a Mimic and confirm with other primary evidence.
- **Nightmare Mode**: Will also show Ghost Orbs, even with reduced evidence.

### Important Notes
- **Static Behavior**: The Mimic cannot change its behavior mid-hunt.
- **Multiple Evidence**: On Professional difficulty and below, it can show up to 4 pieces of evidence.


## Moroi 👻

### Hunting
- **Speed**: Varies with player sanity, up to `2.5 m/s`. Max speed of `3.7 m/s` at 0% sanity.
- **Sanity**: Initiates hunts at 50% sanity.

### Strengths and Weaknesses
- **Strengths**: Drains extra sanity when using Spirit Box or Parabolic Mic. Cursed players must take sanity pills.
- **Weaknesses**: Smudge sticks grant 7.5 seconds of safety.

### Interactions
- **Audio Cues**: Spirit Box is a fixed evidence type.


## Deogen 👻

### Hunting
- **Speed**: `3 m/s` Very fast when far from players; extremely slow `1 m/s` when close to a player.
- **Sanity**: Hunts at 40% sanity.

### Strengths and Weaknesses
- **Strengths**: Always knows player location. Increased chance for Ghost Writing and D.O.T.S.
- **Weaknesses**: Slow speed when near players allows for easy escape.

### Interactions
- **Audio Cues**: 30% chance for special Spirit Box response when close to the ghost. Spirit Box is fixed evidence.

## Thaye 👻

### Age Mechanics
- **Aging**: Starts young and ages when near players, affecting its abilities and behavior. (Dont think the model changes with age?)

### Hunting
- **Speed**: `2.7 m/s` at its youngest. `1 m/s` at oldest.
- **Young Age Sanity Threshold**: Initiates a hunt at 75% sanity.
- **Old Age Sanity Threshold**: At its oldest, will only hunt at 15% sanity.

### Strengths and Weaknesses
- **Young Age**: Behaves like a fast-moving Demon.
- **Old Age**: Becomes a low-activity Shade.

### Aging Process
- **Initial Timer**: A 2-minute timer starts when you unlock the entrance of the map.
- **Aging Event**: If a player is found nearby after the timer, the Thaye ages.
- **Recheck**: If no player is found, sets a 30-second timer for another aging check.

### Interactions
- **Ouija Board**: Helpful for determining the Thaye's current age.
- **Evidence**: Increased likelihood for Ghost Writing and Dots.
