---
tags:
  - rules
  - exploration
  - dungeons
type: rules
---
# Dungeon Exploration System
*Time is money. And money is Veezy's.*

This system formalizes dungeon exploration into a **repeatable decision loop** using 10-minute turns. Every turn spent underground is a turn closer to running out of light, spells, and patience — and a turn closer to whatever lives down here finding you first.

---

## Core Loop

### The Exploration Turn

Time is divided into **10-minute turns**. Each turn, the party performs **one primary action**.

**Turn Cycle:**
1. Party declares action
2. Time advances by 1 turn (10 minutes)
3. Resolve action
4. Update resources (light, spells, fatigue)
5. Check for consequences (if applicable)

---

## Actions per Turn

Each action consumes **exactly 1 turn** unless otherwise noted.

### Movement

| Mode | Distance | Notes |
|------|----------|-------|
| **Careful Movement** | 120 ft / turn | Includes mapping, trap awareness, stealth posture |
| **Fast Movement** | 600 ft / turn | No mapping, no trap detection, increased encounter risk |

**Fast movement is a gamble.** You cover ground, but you miss threats. In a Veezy dungeon, what you miss tends to find you later.

---

### Exploration Actions

| Action | Resolution |
|--------|------------|
| Search room | Roll Search/Spot |
| Retry failed search | Spend 1 turn — automatic success |
| Listen at door | Roll Listen |
| Force door | Roll Strength |
| Retry forced entry | Spend 1 turn — automatic success |
| Pick lock | Standard Open Lock |
| Disable trap | Standard Disable Device |

> **Design Principle:** *Time can substitute for skill, but increases danger exposure.* A rogue who fails a search can try again — but that's another turn on the clock, another chance for something to come knocking.

---

### Utility Actions

- Cast spell
- Examine object
- Map area
- Interact with environment

---

## Time Pressure Systems

### Wandering Monsters

- Check every **6 turns (1 hour)**
- Base chance: **1-in-6** (roll 1d6)

**Modifiers:**

| Condition | Modifier |
|-----------|----------|
| Loud activity (combat, smashing) | +1 to +2 |
| Resting in unsafe area | +1 |
| Secured location | Reduced frequency (see [[#Resting Rules]]) |

If triggered: encounter occurs immediately or within 1-2 turns.

---

### Noise & Risk

| Activity | Noise Level | Effect |
|----------|------------|--------|
| Stealth movement | Quiet | No modifier |
| Normal movement | Moderate | Standard |
| Combat / smashing | Loud | +1 encounter chance |
| Repeated loud actions | Severe | Stacking risk |

---

### Light Tracking

| Light Source | Duration |
|-------------|----------|
| Torch | 6 turns (1 hour) |
| Lantern | 24 turns (4 hours) |
| Magical light | Per spell duration |

When light expires: darkness penalties apply **immediately**. No grace period. Exploration becomes significantly more dangerous.

---

### Spell Duration Alignment

Spells naturally align with the turn structure:

| Spell Duration | Turn Equivalent |
|---------------|-----------------|
| 1 min/level | ~1 turn at low levels |
| 10 min/level | Multiple turns |
| 1 hour/level | Full expedition duration |

**Implication:** Spell usage becomes a **timing decision**, not just a tactical one. Casting *detect magic* at 10 min/level means you get a window — use it wisely or waste it walking.

---

## Fatigue System

### Mandatory Rest Cycle

After **5 turns (50 minutes)** of activity, the party **must rest for 1 turn**.

### If Ignored:

Cumulative penalty per missed rest:
- -1 attack
- -1 damage
- **Stacks indefinitely**

Pushing through exhaustion is possible. It is not advisable.

---

## Resting Rules

### Short Rest (1 Turn)

- Counts as a normal turn
- Triggers wandering monster checks normally
- The dungeon doesn't care that you're tired

### Securing a Location

Spend **1 turn** preparing defenses:
- Barricades
- Alarm setup (mundane or magical)
- Defensive positioning

**Benefit:** Only **1 wandering monster check per rest period** instead of per-turn.

### Long Rest (8 Hours = 48 Turns)

**Extremely dangerous in-dungeon.** 48 turns = at minimum **8 wandering monster checks**.

Likely interruption unless:
- Safe room (rare, usually trapped or cursed)
- Magical protection (*Leomund's tiny hut*, *rope trick*, etc.)
- Cleared and secured zone

**DM Note:** Long rests in hostile dungeons should feel like a desperate last resort, not a routine reset. If the party is long-resting mid-dungeon, the dungeon should react.

---

## Mapping System

### Mapper Role

One character maintains the map. While mapping:
- Cannot use two-handed weapons
- Cannot use shield

### If the Map Is Lost:

- Navigation checks required to retrace steps
- Risk of getting lost
- Increased time and resource drain

---

## Environmental Pressure (Advanced)

Introduce **global dungeon timers** for high-stakes runs:

Examples:
- Rising water level
- Spreading fire
- Ritual countdown
- Collapsing structure
- Alarm response escalation (guards mobilizing)

### Implementation:

- Trigger every X turns (e.g., every 6 turns)
- Escalate conditions each trigger

**Purpose:** Adds macro-level urgency on top of micro-level turn decisions. Particularly effective for [[Quests/01 - Strahd's Favorite Mirror|heist-style]] operations where the party is on a clock.

---

## Risk vs. Reward Framework

Every decision presents tradeoffs:

| Choice | Benefit | Cost |
|--------|---------|------|
| Move fast | Save time | Miss threats and loot |
| Search thoroughly | Find treasure and traps | Burn turns, trigger encounters |
| Use spells | Solve problems quickly | Consume limited resources |
| Rest early | Avoid fatigue penalties | Risk encounters while vulnerable |
| Push forward | Progress toward objective | Exhaustion stacks |

---

## DM Execution Guidelines

### Keep It Lightweight

- Track turns with simple tally marks
- Batch resource updates when possible
- Avoid excessive bookkeeping — the system should add tension, not paperwork

### Maintain Flow

- Describe fiction first, apply mechanics second
- Don't interrupt pacing to announce turn numbers unless the pressure matters narratively

### Make Consequences Visible

Players should always understand:
- **Time is passing** (torches burning, spells ticking)
- **Risk is increasing** (noise accumulating, patrols shifting)
- **Resources are depleting** (and Veezy's tribute waits for no one)

---

## Minimal Implementation

If full system is too heavy for a session, use:

1. 10-minute turns
2. Wandering monster check every hour (6 turns)
3. Light tracking
4. Mandatory rest every 5 turns

This produces ~80% of the system's benefit with minimal overhead.

---

## Coinspiratorium Integration

This system reinforces the campaign's core economic tension:

- **Every turn spent in a dungeon is a cost.** Torches, spells, hit points, and time are all resources with gold-piece equivalents.
- **Thoroughness yields better loot** — but more risk means more resource expenditure, which means less profit margin on the haul.
- **The party must decide:** do they clear every room for maximum inventory, or grab the target artifact and get out clean? The answer affects what they can stock in [[The Coinspiratorium (Location)|the shop]], what they can pay toward [[Debt and Economy|the debt]], and how much they have left to invest in themselves.

Every dungeon is a business trip. The clock is always running. And [[Vizzok the Opulent|Veezy]] expects a return on investment.

---

## Related

- [[Debt and Economy]] — the economic pressure that makes exploration costs matter
- [[Store Management]] — where the loot goes after the dungeon
- [[Revised Treasure Values]] — what the haul is actually worth
