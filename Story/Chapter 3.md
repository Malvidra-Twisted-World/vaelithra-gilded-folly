---
title: Vaelithra – Gilded Folly
chapter: 3
tags: [dnd, module, vaelithra, gilded-folly, combat, trial]
---

# Vaelithra: Gilded Folly
## Chapter 3: Trial I — The Hoarder of Still Gold

---

## Chapter Overview

This chapter introduces:

- The first trial (1v1 combat)
- Behavioral mechanics (Aurum Stasis)
- The philosophy of **Greed as Preservation**

Only **one player** participates.  
Other players observe.

---

## Level Adjustment

Before the trial begins:

> The chosen player becomes **Level 5**

---

> Read:

Something shifts within you.

Not growth—

Adjustment.

As if this place reshapes you into something… more complete.

---

## The Summoning

> Read:

A bell rings.

Once.

The world dulls.

One of you feels it.

A pull.

A certainty.

You are being chosen.

---

## Selecting the Champion

**DM Action:**
- Roll randomly among players

---

> Read to the chosen player:

Everything slows.

Time stretches—

Then leaves everything behind.

Except you.

“You will stand.”

---

## Transition to Arena

> Read:

The floor fractures.

Gold seeps upward through the cracks.

The world folds inward.

Silence.

---

## Arena: The Gilded Chamber

### Description

- Marble floor veined with gold  
- Coins embedded across the ground  
- Endless dim space beyond  
- No visible exit  

### Atmosphere

- Still  
- Heavy  
- Watching  

---

## Champion Introduction

> Read:

At the center stands a figure.

Tall. Unmoving.

His body is layered in gold—

Not worn.

Grown.

Coins orbit him slowly.

His eyes burn like molten metal.

“You will learn,” he says,

“the value of not wasting what is yours.”

---

```statblock
layout: Basic 5e Layout
name: Vauryx, Hoarder of Still Gold
source: MTW
ac: 17
hp: 136
hit_dice: 16d8 + 64
speed: 30ft
stats:
  - 18
  - 14
  - 18
  - 12
  - 14
  - 16
saves:
  - CON: 8
  - WIS: 6
  - CHA: 7
condition_immunities: Charmed, Frightened
cr: 10
traits:
  - name: Aurum Stasis
    desc: |-
      Vauryx Begin Combat in Aurum Stasis Active.

       While Active:
       - Resistance to all damage.
       - Gains 10 Temp HP at the start of turn.

       While Broken:
       - No Resistance
       - No Temp HP
       - First hit each round deals additional 6 (2d6) damage
  - name: Cracks in the Hoard
    desc: |-
      At the end of player's turn, Aurus Stasis breaks if the player:

       - Use a limited resource
       - Takes a risky commitment action
       - Ends their turn in close combat
  - name: Reassert Greed
    desc: |-
      If a full round passes with no trigger:

       - Stasis Returns
       - Vauryx Gain 15 Temp HP
actions:
  - name: Multiattack
    desc: Vauryx can do two attacks of Gilded Graps
  - name: Gilded Grasp
    desc: "*Melee attack*., To Hit: +7, single target, 5ft. On a hit the target takes 7 (2d6+4) bludgeoning damage. If Aurum Stasis Active, add 4 (1d8) force damage."
  - name: Weight of Wealth - Recharge (5-6)
    desc: Vauryx choose one target 5ft from him and drop a gold energy from thin air aim to crushing the target. The target must make a DC 15 Strength Saving Throw, on a fail, the target will take 8 (4d8) force damage, and their speed will be reduced to 0 as their being crushed, this effect will last until the target's next turn. On a success the target takes half damage
image: D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Vauryx.png
skillsaves:
  - Insight: 6
  - Perception: 6
  - Intimidation: 7
senses: Darkvision 60ft., Passive Perception 16
languages: Common, Infernal, Celestial
creature: Vauryx, Hoarder of Still Gold
size: Medium
type: Fiend (Demi-God)
alignment: Lawful Neutral
```

## Vauryx, Hoarder of Still Gold

*Medium Fiend (Demi-God), Lawful Neutral*

---

### Armor Class
17

### Hit Points
136 (16d8 + 64)

### Speed
30 ft.

---

### STR 18 (+4)  
### DEX 14 (+2)  
### CON 18 (+4)  
### INT 12 (+1)  
### WIS 14 (+2)  
### CHA 16 (+3)

---

### Saving Throws
Con +8, Wis +6, Cha +7

### Skills
Insight +6, Perception +6, Intimidation +7

### Condition Immunities
Charmed, Frightened

### Senses
Darkvision 60 ft., Passive Perception 16

### Languages
Common, Infernal, Celestial

---

## Traits

### Aurum Stasis

Vauryx begins combat with Aurum Stasis active.

While active:
- Resistance to all damage  
- Gains 10 temporary HP at the start of his turn  

---

### Cracks in the Hoard

At the end of the player’s turn, Aurum Stasis breaks if the player:

- Uses a limited resource  
- Takes a risky or committed action  
- Ends their turn within 5 ft. after attacking  

---

### While Aurum Stasis is Broken

- Vauryx loses all resistances  
- Does not gain temporary HP  
- The first hit against him each round deals +2d6 force damage  

---

### Reassert Greed

If a full round passes without triggering Cracks in the Hoard:

- Aurum Stasis reactivates  
- Vauryx gains 15 temporary HP  

---

## Actions

### Multiattack
Vauryx makes two Gilded Grasp attacks.

---

### Gilded Grasp
Melee Weapon Attack: +7 to hit, reach 5 ft., one target  

Hit:
- 2d6 + 4 bludgeoning damage  
- +1d8 force damage if Aurum Stasis is active  

---

### Weight of Wealth (Recharge 5–6)

Each creature within 20 ft. must make a DC 15 Strength saving throw:

- Fail: 4d8 force damage and speed becomes 0 until end of next turn  
- Success: Half damage  

---

## Reaction

### Claim the Loss

When a creature within 5 ft. expends a resource:

- Vauryx gains 10 temporary HP  
- Moves up to 10 ft. without provoking opportunity attacks  

---

## Vaelithra’s Intervention (Arena Pick-up)

To assist the DM and players with the **Aurum Stasis** mechanic, the following object appears in the arena during **Round 2**:

### The Unstable Core
*Object (Small)*

> “A pulsing sphere of raw time energy emerges from a crack in the floor. It hums with an impatient rhythm.”

**Interaction (Object Interaction):** A player can touch or kick the core.
**Effect:** The core releases a burst of chaotic energy.
**Mechanical Trigger:** This counts as a **Risky Commitment Action**. It automatically triggers **Cracks in the Hoard**, breaking Vauryx's stasis for 1 round without the player needing to use their own resources.

---

## Running Vauryx (DM Guide)

### Phase 1 — The Wall
- Slow, controlled  
- Confident  
- Absorbs damage  

---

### Phase 2 — The Crack
- First break → let it last  
- Show visible change  

---

### Phase 3 — Overreach
- Aggressive  
- Risk-taking  
- Pushes for hits  

---

## Hinting the Mechanic

Player hesitates:
“The gold tightens.”

Player commits:
“A fracture spreads.”

Player succeeds:
“He pauses… uncertain.”

---

## Victory Condition

Reduce Vauryx to **0 HP**

---

## Defeat Scene

> Read:

The gold collapses inward.

Vauryx falls to one knee.

“To lose…”

“…is to have risked something.”

His body crumbles.

---

## Return to the Lobby

> Read:

The arena dissolves.

You stand once more in the lobby.

Everything is unchanged.

Except—

They are watching you.

---

## Reactions

### Mammeth
“How refreshing.”

“You chose to spend.”

---

### Alethia
“You have learned the first truth.”

---

## Development

Players now understand:

- Behavior matters in combat  
- Risk creates opportunity  
- Greed has a pattern  

---

## End of Chapter

Proceed to:

> **Chapter 4: Between Trials — The Watching Hotel**