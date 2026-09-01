# Appendix B: Creatures

*Gilded Folly*'s combatants are the six Trial champions — each an embodiment of a facet of Greed or Charity — and the Pride Entity that intrudes on the finale. None of these creatures appear anywhere outside their own Trial; there is no roaming encounter table. **Vanka Yuriv**, **Mammeth**, and **Alethia** never fight and have no stat blocks — they are narrators and judges, not combatants.

## Vauryx, Hoarder of Still Gold

*Trial I (Part II: The First Trials)*

A demi-god of stillness wearing his own wealth as flesh, Vauryx doesn't attack so much as endure — confident that anything thrown at him is a loss the thrower will regret. He only becomes dangerous once something forces him to *risk* something of his own.

```statblock
layout: Basic 5e Layout
name: Vauryx, Hoarder of Still Gold
source: MTW
image: D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Vauryx.png
creature: Vauryx, Hoarder of Still Gold
size: Medium
type: Fiend (Demi-God)
alignment: Lawful Neutral
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
skillsaves:
  - Insight: 6
  - Perception: 6
  - Intimidation: 7
condition_immunities: Charmed, Frightened
senses: Darkvision 60ft., Passive Perception 16
languages: Common, Infernal, Celestial
cr: 10
traits:
  - name: Aurum Stasis
    desc: |-
      Vauryx begins combat with Aurum Stasis active.

      While active: resistance to all damage, and he gains 10 temporary HP at the start of his turn.

      While broken: no resistance, no temporary HP, and the first hit against him each round deals an additional 6 (2d6) force damage.
  - name: Cracks in the Hoard
    desc: |-
      At the end of a player's turn, Aurum Stasis breaks if that player:

      - Uses a limited resource
      - Takes a risky commitment action
      - Ends their turn in close combat with Vauryx
  - name: Reassert Greed
    desc: |-
      If a full round passes with no trigger, Aurum Stasis reactivates and Vauryx gains 15 temporary HP.
actions:
  - name: Multiattack
    desc: Vauryx makes two Gilded Grasp attacks.
  - name: Gilded Grasp
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (2d6+4) bludgeoning damage. If Aurum Stasis is active, add 4 (1d8) force damage."
  - name: Weight of Wealth (Recharge 5-6)
    desc: "Vauryx drops a gold-forged weight from thin air onto one target within 5 feet. The target must make a DC 15 Strength saving throw, taking 8 (4d8) force damage and having its speed reduced to 0 until the end of its next turn on a failure, or half damage and no speed reduction on a success."
reactions:
  - name: Claim the Loss
    desc: "When a creature within 5 feet of Vauryx expends a resource, Vauryx gains 10 temporary HP and can move up to 10 feet without provoking opportunity attacks."
```

***Vaelithra's Intervention (Round 2).*** **The Unstable Core** — a pulsing sphere of raw time energy — emerges in the arena. Touching or kicking it counts as a risky commitment action, automatically triggering Cracks in the Hoard for free.

## Feltheris, the Golden Warden

*Trial II (Part II: The First Trials)*

A construct built to stand perfectly still and be respected for it. Feltheris punishes anyone who tries to force him out of position — and falls apart the moment he's actually moved.

```statblock
layout: Basic 5e Layout
name: "Feltheris, the Golden Warden"
source: MTW
image: D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Feltheris.png
size: Medium
type: Construct
alignment: Lawful Neutral
ac: 18
hp: 120
hit_dice: 16d8+48
cr: 5
speed: 25ft
stats: [18,10,16,8,12,10]
saves: [CON: 6, WIS: 4]
condition_immunities: Charmed, Frightened, Poisoned
senses: [Darkvision 60ft, Passive Perception 11]
traits:
  - name: Perfect Alignment
    desc: "If Feltheris has not moved since his last turn and is not prone, he has +2 AC and advantage on saving throws. If he is displaced, forced to move, or his terrain is disrupted, he loses both bonuses and has disadvantage on his next attack."
  - name: Immutable Form
    desc: "Feltheris is immune to effects that would alter his form."
actions:
  - name: Multiattack
    desc: "Feltheris makes two Gilded Slam attacks."
  - name: Gilded Slam
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12 (2d8+4) bludgeoning damage."
  - name: Anchor Pulse (Recharge 5-6)
    desc: "Feltheris slams his weapon into the ground, releasing a golden pulse. Every creature within 15 feet must make a DC 15 Strength saving throw, taking 12 (3d8) force damage and falling prone on a failure, or half damage and no prone on a success."
```

## Citrina, the Lustrous Siren

*Trial II (Part II: The First Trials)*

Where Feltheris demands to be left alone, Citrina demands to be watched. She thrives on being the center of attention and unravels the instant she's ignored.

```statblock
layout: Basic 5e Layout
name: "Citrina, the Lustrous Siren"
source: MTW
image: "D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Citrina.png"
size: Medium
type: Fiend
alignment: Chaotic Neutral
ac: 15
hp: 95
hit_dice: 13d8+39
cr: 4
speed: 30ft
stats: [10,16,16,14,12,18]
saves: [DEX: 6, CHA: 7]
skillsaves: [Deception: 7, Insight: 4, Performance: 7]
condition_immunities: Charmed (Self)
traits:
  - name: Gaze of Value
    desc: "If Citrina is the primary focus of attacks, she has advantage on attack rolls and +2 AC. If ignored for a full round, she loses both and has disadvantage on her attacks instead."
  - name: Alluring Presence
    desc: "A creature that starts its turn within 10 feet of Citrina must make a DC 14 Wisdom saving throw. On a failure, that creature has disadvantage on attacks that don't target Citrina until the start of its next turn."
actions:
  - name: Multiattack
    desc: "Citrina makes two Golden Lash attacks."
  - name: Golden Lash
    desc: "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9 (2d6+3) slashing damage plus 3 (1d6) psychic damage."
  - name: Enthralling Glance (Recharge 5-6)
    desc: "Citrina fixes her gaze on one target, who must make a DC 14 Wisdom saving throw. On a failure, the target is charmed until the end of its next turn. On a success, it is immune to this ability for 1 round."
```

***Vaelithra's Intervention (Round 2).*** **The Gravity Anchor Shards** — throwable stones with a short pull/push effect — can force Feltheris out of position, instantly breaking his Perfect Alignment. **The Distraction Prism**, held by a player, forces Citrina's attention onto the holder for a full round, letting the rest of the party safely ignore her and trigger her Gaze of Value penalty.

## Auric Vex, Arbiter of Dominion

*Trial III (Part III: The Weight of Ownership)*

Auric doesn't hoard objects — he hoards space. Every zone he claims restricts movement and choice, and he only loses his grip when the players refuse to stay inside the lines he's drawn.

```statblock
layout: Basic 5e Layout
source: MTW
cr: 9
name: "Auric Vex, Arbiter of Dominion"
image: "D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Auric Vex.png"
size: Medium
type: Fiend (Demi-God)
alignment: Lawful Neutral
ac: 18
hp: 165
hit_dice: 18d8+72
speed: 30ft
stats: [16,16,18,14,14,18]
saves: [DEX: 7, WIS: 6, CHA: 8]
skillsaves: [Insight: 6, Perception: 6]
condition_immunities: Charmed, Frightened
traits:
  - name: Dominion Field
    desc: |-
      Auric Vex exerts control over the battlefield.

      **Dominion Zones.** At the start of his turn, Auric creates two 10-foot-radius control zones that last until his next turn. A creature inside a zone has its speed halved, has disadvantage on attack rolls, and cannot take reactions.

      **Control Expansion.** If both of his opponents end their turn inside zones, Auric gains +2 AC and advantage on his attacks.

      **Breaking Control.** If both opponents end their turn outside every zone, or something forces Auric himself to move, his Dominion Field collapses: he loses all control bonuses and takes an extra 2d6 damage on the next hit against him.
actions:
  - name: Multiattack
    desc: "Auric makes two Chain of Claim attacks."
  - name: Chain of Claim
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 12 (2d8+4) slashing damage plus 3 (1d6) force damage, and the target is pulled 10 feet toward Auric."
  - name: Domain Collapse (Recharge 5-6)
    desc: "All creatures standing in a Dominion Zone must make a DC 16 Strength saving throw, taking 16 (4d8) force damage and becoming restrained until the end of their next turn on a failure, or half damage and no restraint on a success."
reactions:
  - name: Seize Position
    desc: "When a creature leaves a zone, Auric can move up to 15 feet and create a new zone at that location."
```

***Vaelithra's Intervention (Round 2).*** **The Temporal Anchor Points** — three glowing runes on the floor — grant immunity to Dominion Zone effects to anyone standing on them, making it far easier to coordinate a Breaking Control moment.

## Aurelion, the Keeper of Excess

*Trial IV (Part IV: The Mirror of Intent)*

A living aspect of Greed given form, Aurelion grows stronger with every resource the party burns and every burst of damage they land — and empties out completely the moment they stop feeding him.

```statblock
layout: Basic 5e Layout
source: MTW
image: "D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Aurelion.png"
name: "Aurelion, the Keeper of Excess"
size: Medium
type: Fiend (Greed Aspect)
alignment: Lawful Neutral
ac: 17
cr: 8
hp: 140
hit_dice: 17d8 + 68
speed: 30ft
stats: [16,14,18,12,14,18]
traits:
  - name: Accumulation
    desc: "Each time a player uses a resource or deals burst damage, Aurelion gains 1 stack (maximum 5). Each stack grants +1 AC and +1 to attack rolls. At 5 stacks, he gains an extra attack on his Multiattack."
  - name: Force Released
    desc: "If his opponents delay actions, coordinate low-resource play, and avoid burst damage, all of Aurelion's stacks reset to 0."
actions:
  - name: Multiattack
    desc: "Aurelion makes two Hoarded Strike attacks."
  - name: Hoarded Strike
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d8+4) bludgeoning damage, plus 1 additional damage per Accumulation stack."
  - name: Overflow (Recharge 5-6)
    desc: "Aurelion releases his hoarded power in a burst of golden light. Each creature within 20 feet must make a DC 16 Dexterity saving throw, taking 2d6 force damage per Accumulation stack Aurelion currently has (half as much on a success). All of his stacks then reset to 0."
```

## Seraphel, the Bearer of Burden

*Trial IV (Part IV: The Mirror of Intent)*

Where Aurelion embodies taking, Seraphel embodies sharing — sometimes to a fault. She spreads any damage she takes across her allies, and only becomes truly vulnerable when the party refuses to let her carry it alone.

```statblock
layout: Basic 5e Layout
image: "D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Seraphel.png"
name: "Seraphel, the Bearer of Burden"
source: MTW
cr: 8
size: Medium
type: Celestial (Charity Aspect)
alignment: Lawful Good
ac: 16
hp: 130
hit_dice: 15d8 + 60
speed: 30ft
stats: [14,14,18,12,16,18]
traits:
  - name: Shared Burden
    desc: "When Seraphel takes damage, half of it is transferred to another target of the attacking player's choice, if possible."
  - name: Isolation
    desc: "If her opponents split up and focus her individually rather than staying together, Seraphel cannot transfer damage and takes an extra 6 (2d6) damage from each hit."
actions:
  - name: Multiattack
    desc: "Seraphel makes two Radiant Bind attacks."
  - name: Radiant Bind
    desc: "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 7 (2d6) radiant damage, and the target is linked to another creature of the attacker's choice for the shared-damage effect of Shared Burden."
  - name: Sacrificial Pulse (Recharge 5-6)
    desc: "Seraphel heals all allies within 30 feet for 4d8 hit points."
```

***Vaelithra's Intervention (Round 3).*** **The Shard of Stillness** instantly zeroes Aurelion's stacks when crushed. **The Prism of Isolation** disables Seraphel's damage-transfer for anyone fighting within 5 feet of it.

## Cael Verix, Scion of Xy'loth

*Final Battle (Part V: Scion of Pride)*

The Pride Entity that follows Fradonic Ra and Lunaris Thoht through the rift they tore open — an intruder who considers Gilded Folly's Trials, and everyone in them, beneath his notice. His design punishes repetition at every phase: the same tactic used twice in a row makes him stronger, and only genuine variety and coordination ever cracks his composure.

```statblock
layout: Basic 5e Layout
source: MTW
image: "D&D/Original Adventures/Vaelithra/4. GIlded Folly/Images/Cael Verix.png"
name: "Cael Verix, Scion of Xy'loth"
size: Medium
type: Humanoid (Human)
alignment: Neutral Evil
cr: 26
ac: 23
hp: 900
hit_dice: 38d8+342
speed: 30ft
stats: [20,20,28,24,20,28]
saves: [DEX: 12, CON: 14, WIS: 12, CHA: 14]
skillsaves: [Insight: 12, Perception: 12]
condition_immunities: Charmed, Frightened, Stunned, Paralyzed, Grappled, Restrained
damage_resistances: Bludgeoning, Piercing, Slashing from nonmagical attacks
senses: Truesight 120 ft., Passive Perception 22
traits:
  - name: Legendary Resistance (3/Day)
    desc: "If Cael fails a saving throw, he can choose to succeed instead."
  - name: Phase-Lock Divinity
    desc: "Cael Verix cannot be reduced below 600 HP while in Phase 1, or below 300 HP while in Phase 2, by a single turn's damage. When a threshold is hit, the excess damage is ignored and he immediately transitions to the next phase."
  - name: Adaptive Dominance (Phase 1-2)
    desc: "If a creature uses the same action type (attack, spell, ability) on consecutive turns, Cael gains resistance to that damage type, and that creature suffers a stacking -3 penalty to attack rolls that only resets when it varies its approach."
  - name: Absolute Standard
    desc: "If a creature deals less than 35 damage on a single hit against Cael, that damage is reduced to 0."
  - name: Flawless Counter (Phase 2+)
    desc: "Once per round, when Cael is hit by an attack, he halves the damage and teleports 20 feet."
  - name: Cracking Superiority (Phase 3)
    desc: "Cael loses Adaptive Dominance. If he is hit by three different damage sources in a single round, he gains vulnerability to damage until the start of his next turn."
actions:
  - name: Multiattack
    desc: "Cael makes 4 Superior Strikes."
  - name: Superior Strike
    desc: "Melee Weapon Attack: +15 to hit, reach 5 ft., one target. Hit: 28 (3d12+9) slashing damage plus 18 (4d8) force damage."
  - name: Dismissive Pulse (Recharge 5-6)
    desc: "Each creature within 30 feet must make a DC 22 Constitution saving throw, taking 45 (10d8) force damage and being pushed 30 feet away on a failure, or half damage and no push on a success."
  - name: Punish the Strong (Phase 2+)
    desc: "Cael targets the creature that has dealt the most damage to him so far: +15 to hit, 55 (10d10) force damage, and the target has disadvantage on its next attack roll."
  - name: Collapse Reality (Phase 3, Recharge 5-6)
    desc: "Each creature must make a DC 22 Dexterity saving throw, taking 66 (12d10) force damage on a failure or half as much on a success."
reactions:
  - name: Superiority Shift
    desc: "When targeted by an attack, Cael gains +3 AC against that attack."
legendary_actions_desc: "Cael Verix can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn. Cael regains spent legendary actions at the start of his turn."
legendary_actions:
  - name: Strike
    desc: "Cael makes one Superior Strike."
  - name: Unattainable (Costs 1 Action)
    desc: "Cael teleports 40 feet and clears all of Adaptive Dominance's stacking attack-roll penalties from every creature."
  - name: Reflected Hubris (Costs 2 Actions)
    desc: "One creature Cael can see within 60 feet must succeed on a DC 22 Wisdom saving throw or use its reaction to make a melee attack against itself or an ally of Cael's choice."
  - name: Evaluate (Costs 2 Actions)
    desc: "Cael gains advantage on his next attack roll and marks a target; the next hit against that target deals an extra 27 (6d8) damage."
lair_actions_desc: "On initiative count 20 (losing initiative ties), Cael Verix takes one lair action to cause one of the following effects; he can't use the same effect two rounds in a row."
lair_actions:
  - name: Suppressed Zone
    desc: "Cael selects a 20-foot-radius area he can see. Movement in the area is halved (stacks with other effects). Any creature that starts its turn there, or enters it for the first time on a turn, must make a DC 22 Strength saving throw or take 22 (4d10) force damage and be knocked prone; on a success it takes half damage and isn't knocked prone."
  - name: Mirror of Hubris
    desc: "The golden walls reflect the players' insecurities back at them. Each creature of Cael's choice within 60 feet must succeed on a DC 22 Wisdom saving throw or be blinded until the next initiative count 20, with disadvantage on all saving throws while blinded."
  - name: Gravitational Command
    desc: "Cael intensifies gravity throughout the room. Each creature of his choice must succeed on a DC 22 Charisma saving throw or fall prone; an affected creature can't stand up until the end of its next turn unless it spends its entire movement and takes 11 (2d10) psychic damage."
```

***Phase-by-Phase Summary.*** **Phase 1 — Observation** (above 600 HP): Legendary Resistance, Adaptive Dominance, and Absolute Standard are all active; Cael fights with pure, confident superiority. **Phase 2 — Domination** (600 HP or below): he gains Flawless Counter and Punish the Strong. **Phase 3 — Fractured Perfection** (300 HP or below): he loses Adaptive Dominance but gains Cracking Superiority and Collapse Reality — this is the phase where genuinely varied, coordinated offense finally outpaces raw numbers.

***Support Elements.*** **Fradonic Ra**'s *Solar Flare* (once per combat, reaction) strips all of Cael's damage resistances for the following round the moment a player damages him. **Lunaris Thoht**'s *Lunar Veil* (once per combat, reaction) grants the party immunity to force damage until the end of the current turn, usable against Dismissive Pulse or Collapse Reality. **Mammeth** may throw a Gilded Shard for 50 force damage the moment Cael reaches Phase 3. **Alethia** grants the party 100 temporary HP if they trigger Cracking Superiority.
