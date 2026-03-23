# Dungeon Generation & Exploration Guide

A reusable framework for designing and running dungeon crawls in tabletop RPGs. Covers four concerns: what the dungeon is about (thematic generation), how it's laid out (spatial design), how to run exploration at the table (the stretch system), and how to build encounter tables that are worth rolling on (encounter design).

Adapt the mechanical details (DCs, specific actions, edition-specific rules) to your system. The design principles are edition-agnostic.

---

# Part 1: Designing the Dungeon

## Thematic Generation Framework

Every dungeon should be generated with the following elements defined. These give the dungeon a reason to exist beyond "rooms with monsters."

```
Dungeon Theme
Original Owner
Reason It Exists
Objective / Artifact
Environmental Identity
Guardians
Unique Mechanic
Dungeon Twist
```

### Dungeon Theme

Themes should be strong and unusual. Avoid generic fantasy ruins.

Examples: dragon hoard vault, celestial archive, cursed theater, time-loop prison, planar museum, magical casino, a courthouse for dead gods, a bank that exists in two planes simultaneously.

### Original Owner

Every dungeon once belonged to someone. This determines the dungeon's style, construction, and the logic behind its defenses.

Examples: archmage, dragon, celestial order, lich collector, ancient empire, merchant guild, a god who lost a bet.

### Reason It Exists

Why was this place created? The original purpose informs what the party finds inside and what went wrong.

Examples: vault for powerful artifacts, prison for magical beings, research facility, divine trial chamber, monument to an ego, a failed experiment.

### Objective / Artifact

Every dungeon revolves around something the party needs to acquire, destroy, or interact with.

The objective should be narratively significant, have unusual properties, and justify the danger of retrieving it. Generic treasure hoards are less interesting than objects with personality, history, or consequences.

### Environmental Identity

Give the dungeon a strong visual identity that reinforces the theme. Players should be able to close their eyes and picture it.

Examples: floating rooms connected by chains, endless library corridors, volcanic caverns, rooms filled with water, halls where gravity pulls sideways, architecture that rebuilds itself behind you.

### Guardians

Guardians should match the theme. A celestial archive is guarded by angelic constructs, not random goblins. A cursed theater is haunted by spectral actors trapped in their roles.

Examples: constructs, summoned outsiders, magical traps, cursed spirits, automated defense systems, creatures that are also prisoners.

### Unique Mechanic

Each dungeon should contain a distinct mechanical element that changes how the party interacts with the space.

Examples: rooms rearrange themselves on a timer, gravity changes direction between floors, illusions distort reality and can be weaponized, magical contracts bind players to specific behaviors inside the dungeon, sound propagation rules where loud actions attract guardians.

### Dungeon Twist

The dungeon should contain a narrative surprise that recontextualizes what the party thought they were doing.

Examples: the artifact is sentient and doesn't want to leave, the dungeon itself is alive, removing the artifact triggers catastrophe, the artifact is not what it appears, the "dungeon" is the inside of a creature, the original owner is still here and wants help.

---

## Spatial Design: Jaquaysing the Dungeon

Dungeons should be **nonlinear labyrinths**, not fancy-looking corridors with combat in between. The following principles (derived from Jennell Jaquays' dungeon design, as popularized by Justin Alexander in *So You Want to Be a Game Master*) define how dungeon layouts should work.

The core idea: **if everything is on the same path, the party isn't making exploration choices.** Variable paths create meaningful, informed decisions.

### Map Loops

The most essential structural element. Dungeons should be cyclical.

Loops let you build mazes with hubs. A central room the party keeps returning to helps them orient, while looping paths create a feeling of comprehension as they gradually map their surroundings. Like recognizing a landmark on an unfamiliar drive and realizing you know exactly where you are.

A good hub room offers multiple exits. Five or more directions from a single hub gives the party genuine choice. At least some of those paths should loop back, so exploration doesn't feel like a one-way trip.

**Default to loops. Linear sequences of rooms should be the exception, used deliberately (the final approach to a boss encounter, a trapped gauntlet) rather than out of habit.**

### Level Loops

Dungeons with multiple levels should not be two dungeons back to back. Moving between floors is part of the exploration, not something you do once you've cleared a level.

* **Multiple connections between levels.** Stairways, ladders, holes, collapsed floors, elevator platforms, teleportation circles. Different paths to different parts of the next level.
* **Mid-entry.** The party doesn't have to start on floor one. They could enter on a middle level with paths going up and down.
* **Discontinuous levels.** Floor 3 might connect to both floor 4 and floor 5, but floor 4 has no path to floor 5. The party has to backtrack and find the other route.
* **Minor elevation shifts.** Stairways up and down within a single floor that don't lead to a new level, just provide variation.

### Multiple Entrances

Build several ways into the dungeon. These entrances become exits later, rewarding exploration both inside and outside the dungeon and providing escape routes.

Consider varied entrance types: a front door, a hidden side entrance, a dangerous shortcut straight to a late-game area. When players see a big pit leading into the boss chamber, they can choose to take it and skip the dungeon's loot, or explore properly and arrive prepared. The point is presenting that choice.

### Strange Paths

Hidden or unusual connections between areas. Secret doors into long corridors. Traps that drop into forgotten chambers. Cracks in walls, holes between floors, viewing platforms overlooking rooms you haven't reached yet.

These don't have to be tunnels with ladders. A gap you can jump across, a drainage pipe to crawl through, an observation deck looking down into a room two floors below. Strange paths create the feeling of discovery that makes exploration rewarding.

### Sub-Levels and Divided Dungeons

Play with the dungeon's overall shape:

* **Sub-levels:** Between floor 1 and floor 2, a small self-contained area (floor 1A) with its own content. A dead-end pocket worth exploring.
* **Divided dungeons:** Two separate complexes connected by limited paths. Two towers with bridges between floors. A structure that split in half during a magical catastrophe.
* **Planar connections:** Portals in walls leading to entirely different environments. A room that exists in two planes simultaneously. A shortcut through a demiplane. Use dungeon space as an excuse to visit somewhere unexpected, even briefly.

### Applying Spatial Principles

Not every dungeon needs every technique. These are tools to reach for when appropriate:

* A short dungeon might only need one good loop and a strange path
* A large dungeon should have a clear hub, multiple level connections, and at least one alternate entrance
* Linear sequences are fine when used deliberately
* The turn-based exploration system (see Part 2) amplifies all of this: loops mean the party weighs "explore the new branch or return to the hub?" against their remaining resources and encounter clock pressure

**The goal: meaningful navigation choices throughout the dungeon, not just combat choices in a predetermined sequence of rooms.**

---

# Part 2: Running the Dungeon

## The Stretch System

> Adapted from *Dungeoneering* by Davi / Mystic Arts. Originally designed for 5th Edition; the core time-tracking structure works in any edition.

Combat is tracked in rounds. Travel in hours or days. Dungeon crawls use the **Stretch**: a 10-minute unit of time that makes time a resource the party has to manage.

### Two Types of Rounds

- Combat uses 6-second rounds.
- Crawls use 10-minute stretches.

### What Counts as a Dungeon

Any dangerous location with several encounters and challenges that a party must explore: an underground labyrinth, a ruined tower, a forbidden compound, a haunted manor, a bank under siege, a crashed spelljammer.

### Crawl Strategy

When the party enters a dungeon, the GM collects their **Crawl Strategy** before exploration begins:

- **Marching Order:** Who's first, who's last, everyone else in between. Single file for 5-foot corridors, double file for 10-foot.
- **Default Initiative:** A pre-agreed turn order for minor combat to save time. Players decide among themselves who goes first and whether they go clockwise or counterclockwise around the table. For monsters, roll a die with at least as many faces as there are players and insert the monster before the corresponding player.
- **Visibility:** Which characters carry light sources, what those light sources are, and how long they last. Note which characters have darkvision and at what range.
- **Passive Perception:** Note each character's score. Characters below the system's baseline stealth DC won't spot hidden creatures without an active check.

This initial exchange saves time (no arguments about edge cases) and produces fair results (the agreed strategy holds when things go sideways).

### General Features

When entering a dungeon, establish its baseline properties so you don't repeat the same descriptions for every room:

**Construction Material:**
- **Manors & Estates.** Hardwood flooring, lacquered wood panels.
- **Castles & Keeps.** Worked stone bricks, flagstone floors.
- **Caves & Tunnels.** Rough, unworked stone throughout.
- **Dungeons & Dens.** Featureless hewn stone.

**Ceiling Height:**
- **Underground Complex.** 10 feet in corridors, 15 feet in rooms.
- **Natural Caverns.** As high as the area is wide.
- **Monster Den.** Never higher than 4 feet. Medium creatures squeeze (halved speed, disadvantage on attacks and Dex saves, advantage on attacks against them).

**Lighting:**
- **Darkness.** Completely unlit. Residents have darkvision.
- **Dim Light.** Occasional shafts or bioluminescence. Partial visibility.
- **Bright Light.** Residents have lit the space for their own use.

### Running a Stretch

Tell the party you're tracking time in 10-minute increments. Each stretch follows this cycle:

**1. Start the Stretch.** Players announce their Activities and where they're doing them. Go around the table for rolls.

**2. Resolve Activities.** Announce results of each player's chosen Activity.

**3. End the Stretch:**
- Mark the stretch on your tracking sheet
- Check for random encounters (roll if applicable)
- Resolve any combat before returning to stretches
- If players triggered combat on the same stretch as a random encounter, combine them

**4. Repeat.**

### Stretch Principles

- **Abstraction.** "Close enough" is fine. An 8- or 12-minute stretch doesn't break anything.
- **Real-time dialogue.** Conversations at the table represent conversations in the dungeon. If table talk exceeds 10 minutes, mark a stretch.
- **No fractions.** Don't track time in smaller increments than whole stretches. Incidental actions (lighting a torch, opening a door, drinking a potion, equipping gear) happen as part of whatever Activity a character is doing.
- **No initiative.** Go around the table or let players call out actions. Just make sure everyone gets a turn before anyone takes a second.

### 10-Minute Activities

At the start of each stretch, each player character chooses an Activity. This list is not exhaustive; GMs and players should collaborate on new activities at the table.

**Casting a Spell**
*Prerequisite: A spell you can cast with a casting time of 10 minutes or less (including rituals).*
You spend the stretch casting. For longer casting times, take this activity multiple stretches in a row. If initiative is rolled mid-cast, you can continue casting in combat using your action each turn.

**Helping Out**
*Prerequisite: A relevant skill or tool proficiency.*
Choose a creature within reach. They gain advantage on ability checks during this stretch.

**Interacting**
*Prerequisite: None.*
You interact with an object or environment feature for 10 minutes: reading inscriptions, moving rubble, studying a device. May require ability checks at the GM's discretion.

**Keeping Watch**
*Prerequisite: You can see your surroundings clearly.*
You stand guard. The party cannot be surprised by creatures you can see. If combat starts during this stretch, you may use a reaction before your first turn to take one action: a single attack, dash, dodge, hide, or cast a cantrip.

**Loot Everything**
*Prerequisite: You can see and hear clearly.*
You collect any adventuring gear and valuables that have been discovered or aren't hidden.

**Move Quietly**
*Prerequisite: Proficiency in Stealth.*
For the next 10 minutes, creatures must succeed on a Perception check to find you. The DC is 8 + your Dexterity modifier + your proficiency bonus (double proficiency if you have expertise).

**Search Area**
*Prerequisite: You can see and hear clearly.*
You spend 10 minutes searching a small room or an area no larger than 50 feet in any dimension. Make a Perception or Investigation check. You find everything hidden by a DC equal to or lower than your result: traps, secret doors, hidden loot.

**Take Your Time**
*Prerequisite: None.*
You spend 10 minutes on a single action. You automatically get a 20 on the first check you make as part of that action (with advantage, add +5). Alternatively, when you fail an ability check, you may spend a stretch to retry it as a Take Your Time activity (GM's discretion).

---

## Wandering Monsters & Encounter Tables

Time tracking exists to create the encounter clock: a system where every stretch spent in the dungeon risks triggering a wandering monster. This section covers both the mechanical dials for controlling encounter pressure and the design philosophy for building tables worth rolling on.

### The Three Dials

You control wandering monster pressure through three adjustable settings:

**Encounter Frequency** (how often you roll):
- **Constant.** Roll at the end of every stretch.
- **Medium.** Roll at the end of every third stretch.
- **Hourly.** Roll at the end of every sixth stretch.

**Encounter Likelihood** (what triggers an encounter when you roll):
- **Unlikely.** Encounter on a 6 (d6).
- **Possible.** Encounter on a 5-6 (d6).
- **Inevitable.** Encounter on a 4-6 (d6).

**Encounter Difficulty** (how tough each encounter is):
- **Trivial.** Drains one or two players' resources.
- **Challenging.** The party must spend resources to avoid casualties.
- **Deadly.** Capable of killing a player character.

These dials combine to set the dungeon's overall tension level. A dungeon with Constant/Possible/Challenging frequency is a pressure cooker. One with Hourly/Unlikely/Trivial is a slow burn.

### Unconventional Uses for Stretches

Stretches work outside classic dungeon crawls:

- **Ticking clock adventures.** Replace wandering monsters with a list of events that trigger at specific stretch counts.
- **Haunted houses.** Roll for paranormal activity instead of monsters. Some results lead to encounters, some are atmosphere.
- **Heists.** Track patrol rotations, alarm escalation, and guard responses on a stretch schedule.

### Building Inspiring Encounter Tables

Random encounter tables should be **inspiring prompts**, not rigid stat blocks. The goal is a table where every result excites the GM, and no roll wastes time answering an obvious question.

> Approach drawn from Davi / Mystic Arts, building on principles from Justin Alexander.

#### The Core Problem

A table that says "3d6 wolves" doesn't account for pacing, party level, or mood. If the party is high-level, the wolves are a time-waster. If they just finished a tough fight, another combat might be wrong for the session. And if the result is boring, rolling for it makes the boredom feel mandatory.

A table that's entirely authored (the GM picks every encounter) loses the generative feeling that makes the world seem real. Rolling creates the sensation of peeking into the world and seeing what's happening.

**The solution: do both.** The table provides randomized content. The GM authors the execution.

#### Each Entry Is a Theme

Every entry should be a **theme** with built-in variations. Write each entry with three components:

1. **Meat and potatoes.** The core encounter at baseline.
2. **Special variations.** Harder, stranger, or more interesting versions the GM can reach for when escalation is needed.
3. **Non-combat option.** An alternative that doesn't require initiative. This gives the GM an exit ramp when combat would hurt the pacing.

Example entry:

> **Wolfpack.** A wolfpack circles the camp and charges if they think they can take the party. The pack consists mostly of wolves, but might include direwolves or a werewolf pack leader. For high-level parties, consider a dire bear running with the pack. Alternatively, the party might find a single wounded wolf pup. A successful Animal Handling check and a ration could endear the wolf to a character.

That single entry covers five or more encounters depending on what the moment calls for.

#### No Boring Results

If a boring result exists on the table, it will come up. The solution: no boring results. Every entry should make the GM want to run it.

A grave with rusted armor is not an encounter. A grave where a successful Investigation check reveals a map, letters from a villain, an uncorroded magic item, or a full coin purse is an encounter. It rewards curiosity and good rolls.

**Every entry should contain at least one informed choice for the players.** If there's no decision to make, it's set dressing, not an encounter.

#### Prep DM vs. Running DM

Think of table design as a collaboration between two versions of yourself:

* **Prep DM** knows the world, the lore, the themes. Builds the table with rich entries. Decides what *could* happen.
* **Running DM** knows the pacing, the mood, the party's state. Looks at what Prep DM wrote and decides what *should* happen right now.

**Do all the prep work, none of the planning.** Fill the table with exciting, flexible content. Trust yourself to deploy it well at the table.

#### Use Bell Curves

Use 2d6 (or similar multi-die rolls) instead of a flat d20 or d12. Multiple dice create a bell curve:

* Common encounters (loot, environmental features) go in the middle where they come up most often
* Rare encounters (boss-level threats, major discoveries) sit at the extremes
* The probability distribution does design work for you

A 2d6 table gives ~16% odds on a 7 and under 3% on a 2 or 12. That weighting is built into the dice.

#### Authored vs. Random

Not every encounter needs a roll. Sometimes you know it's time to foreshadow something. Just do it.

* **Setup encounters** are authored. You place footprints with a chain dragging behind them because you're foreshadowing the revenant. No dice.
* **Gameplay encounters** are rolled. The dice say wolves. You decide whether that means a pack, a werewolf, or a pup based on the current mood.

Both are valid. Alternate between them. Roll dice during setup encounters and ignore the result if you want to disguise the difference.

---

# Part 3: Campaign Customization

The sections above are system- and setting-agnostic. This section contains notes for adapting the framework to a specific campaign. Update or replace this section for each project.

## Current Campaign: The Coinspiratorium

**System:** D&D 3.5e (adapt 5e stretch rules accordingly: replace advantage/disadvantage with circumstance bonuses, adjust DCs to 3.5e scale, replace "Magic action" with standard 3.5e casting rules).

**Dungeon Identity:** Dungeons in this campaign are thematic artifact vaults, not generic monster caves. Each dungeon contains a component of the Crown Infinite, Veezy's reality-altering device. The artifact is always the dungeon's centerpiece and should feel mythic, ironic, or symbolic.

**Artifact Requirements:**
* Narratively significant (tied to the Crown Infinite's construction)
* Unusual magical properties
* Desirable to Veezy for reasons the PCs may not fully understand

**Tone:** Guardians of the Galaxy + Breaking Bad + Planescape. Dungeons can be absurd, cosmically weird, or suddenly horrifying. Comedy drops away when real stakes emerge.

**Exploration System:** See `Rules/Dungeon Exploration.md` for the 3.5e-adapted stretch rules used in this campaign. Key interactions with dungeon design:
* Distances between rooms cost turns (movement pressure)
* Light conditions and duration affect resource pressure
* Noise-generating obstacles create encounter risk tradeoffs
* Environmental timers (flooding, collapse, alarms) add macro-urgency
* Room density and searchable content create thoroughness-vs-speed decisions
* Dead ends cost time. Long corridors burn movement. Every turn is a roll on the encounter clock.

**Encounter Table Notes:**
* Each dungeon's table should reflect its theme
* Non-combat entries should interact with the dungeon's unique mechanics or lore
* Weight common encounters (patrols, environmental hazards, minor discoveries) in the middle of the bell curve and rare encounters (the dungeon's guardian, a fragment of the artifact's power, a planar bleed-through) at the extremes
* Entries should make resource-management decisions harder, not just drain hit points

**Planar Connections:** Especially appropriate for this campaign. The entities who built these dungeons had access to planar magic. Use dungeon space to visit other planes, even briefly.

---

# Appendix: Example Dungeon

**Theme:** Celestial Museum

**Original Owner:** Solar archivists

**Reason:** Preserve divine relics from a war between forgotten gods

**Artifact:** Halo of the First Dawn

**Environment:**
* Marble halls with gold-veined floors
* Floating display cases holding relics in stasis fields
* Radiant light that dims in rooms where relics have been disturbed

**Guardians:**
* Animated statues that recite the provenance of each relic before attacking
* Angelic constructs that believe they are still serving a god who died millennia ago

**Mechanic:**
* Relics in the museum test the moral character of anyone who touches them. Each relic asks a question (spoken directly into the character's mind) and the answer determines whether the relic helps, hinders, or ignores the character. There are no right answers, only revealing ones.

**Twist:**
* The Halo of the First Dawn removes free will from its wearer, replacing their desires with a perfect, selfless devotion to the protection of others. The wearer becomes incapable of acting in their own interest. The archivists considered this a feature.

**Spatial Notes (Jaquaysing):**
* The museum is organized in a ring around a central atrium (hub with 6+ exits)
* A second level exists below the main floor, accessible through three different staircases and a collapsed section of flooring in the east wing
* A strange path: one display case contains a portal to a demiplane where a single relic is stored in isolation. The demiplane is small (five rooms) and functions as a sub-level
* Multiple entrances: the front gates (obvious), a maintenance tunnel used by the constructs (hidden), and a crack in the foundation caused by the divine war that created the museum (dangerous, leads directly to the lower level)
