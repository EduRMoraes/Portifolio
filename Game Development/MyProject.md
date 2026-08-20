# 2D Survival Game

> A 2D pixel-art survival game focused on exploration, combat, progression, and environmental storytelling.

## Overview

This project started as an idea for a relatively simple first game: a **vertical structure divided into floors**, where the player progressively descends through an abandoned and post-apocalyptic environment.

The project is intended to be both a playable game and a long-term **Game Development learning project**, allowing me to progressively explore gameplay programming, artificial intelligence, level design, progression systems, narrative design, and worldbuilding.

The initial prototype is intentionally limited in scope. Many of the concepts described here represent the **long-term vision** of the project and may evolve as development progresses and new Game Development concepts are learned.

---

# Core Concept

The player must explore an abandoned vertical structure, survive encounters with hostile creatures and humans, solve environmental puzzles, and find a way to reach lower floors.

Each floor introduces new challenges, environments, enemies, or gameplay concepts.

Progression is organized around **Arcs**, with each Arc containing approximately three floors and its own visual identity, gameplay focus, and narrative atmosphere.

The long-term structure is designed around three major pillars:

* **Exploration**
* **Combat and Survival**
* **Progression and Discovery**

---

# Safe Rooms

Safe Rooms act as the player's primary points of progression and preparation.

Inside Safe Rooms, the player may eventually be able to:

* Craft items
* Upgrade abilities
* Manage equipment
* Recover resources
* Interact with NPCs
* Purchase items from merchants
* Access progression-related systems

Safe Rooms are intended to provide a contrast to the hostile environments surrounding them and give the player a sense of progression and temporary security.

---

# Floors & Arcs

The game is structured around individual floors connected by stairs and, eventually, elevators.

The player's main objective is to find the exit of the current floor and continue descending toward the streets.

Each floor should introduce a specific challenge or gameplay purpose.

### Floor Design Philosophy

Different floors may focus on:

* Direct combat
* Exploration
* Environmental puzzles
* Resource management
* Narrative discovery
* Enemy encounters
* Stealth
* Mixed gameplay

The game should alternate between more aggressive sections and quieter moments, allowing exploration and problem-solving to provide contrast to combat-heavy areas.

---

## Arcs

Each Arc is intended to contain approximately **three floors** and have its own visual and gameplay identity.

Potential Arc themes include:

### Abandoned Building

A relatively simple starting environment.

The player becomes familiar with basic mechanics such as:

* Movement
* Combat
* Items
* Exploration
* Enemy encounters

The environment consists primarily of ordinary but deteriorated apartments, corridors, rooms, kitchens, and bathrooms.

### Bandit Territory

An area controlled by hostile human survivors.

The environment becomes heavily barricaded and emphasizes:

* Human enemies
* Ranged combat
* Tactical encounters
* Environmental cover
* Resource management

### Mutated Territory

A more dangerous area dominated by mutated creatures.

The environment becomes increasingly strange and hostile, introducing more aggressive enemies and unusual environmental conditions.

### Nature-Reclaimed Areas

Open environments where vegetation has overtaken abandoned structures.

These areas can provide a stronger contrast to the enclosed environments found throughout the earlier floors.

### Puzzle-Focused Areas

Some floors may contain little or no direct combat.

Instead, they focus on:

* Environmental puzzles
* Exploration
* Hidden areas
* Collectibles
* Narrative discoveries

---

# Prototype Goal

For the first major prototype, the primary objective is to reach the **10th floor**.

Reaching this point should unlock the main elevator system, allowing the player to travel between previously completed floors.

This creates the foundation for a future **metroidvania-like progression loop**, where previously inaccessible areas or opportunities can become available after acquiring new capabilities.

---

# Future Safe Room & Base System

One long-term idea is to allow certain floors to change depending on the player's actions.

For example, if the player completely clears a bandit-controlled floor, that location could eventually become a new base.

NPCs previously encountered in safer areas could potentially move into this location and establish:

* Shops
* Trading
* Services
* Character interactions
* New progression opportunities

This system is currently outside the scope of the first prototype but represents a possible future expansion of the game's world and progression systems.

---

# Enemies

The game's enemies are divided into two broad categories:

* **Mutated Creatures**
* **Human Survivors**

The underlying cause of the game's post-apocalyptic environment is **radiation**, providing the foundation for the game's mutations and allowing for more unusual creatures and environmental phenomena.

---

## Enemy Classes

Enemies are organized into behavioral and combat classes.

The initial classes are:

* **Tank**
* **Attack**
* **Support**
* **Shooter**

Additional classes may be introduced as the project evolves.

---

## Tank

Tank enemies are designed to absorb damage and apply heavy pressure.

### Example

A large reptilian mutant.

### Characteristics

* High health
* High damage
* Low mobility
* Predictable behavior
* Strong physical presence
* Vulnerable to environmental manipulation

The Tank is intended to create pressure by forcing the player to deal with a durable threat while managing other enemies.

---

## Attack

Attack enemies focus on mobility and direct pressure.

### Example

A mutated wolf-like creature or humanoid stalker.

### Characteristics

* High mobility
* Moderate damage
* Moderate health
* Aggressive behavior
* Environmental awareness

These enemies are designed to exploit openings and pressure the player from closer ranges.

---

## Support

Support enemies prioritize assisting other enemies rather than directly engaging the player.

### Example

A human supporter or mutated creature capable of healing.

### Characteristics

* Low-to-moderate durability
* Healing abilities
* Ranged support
* Prioritizes injured allies
* Uses other enemies as protection

Support enemies should become high-priority targets during combat encounters.

---

## Shooter

Shooter enemies provide ranged pressure and positional control.

### Example

A human survivor acting as a guard or marksman.

### Characteristics

* High ranged damage
* Low durability
* Long engagement range
* Uses environmental cover
* Can hide behind objects and barricades
* Provides defensive support to other enemies

The player should be encouraged to identify and prioritize Shooter enemies during encounters.

---

# Enemy Concepts

## Mutated Creatures

Initial creature concepts include:

* Skeleton-like mutants
* Reptilian creatures
* Mutated humanoids
* Distorted dogs
* Wolf-like creatures
* Mutated cats
* Tiger-like creatures
* Deer-like creatures
* Rat-like creatures
* Other radiation-induced mutations

The visual and behavioral identity of each creature can evolve as the game's worldbuilding develops.

---

## Human Survivors

Human enemies may include:

### Bandits

* Raiders
* Looters
* Armed survivors
* Ranged attackers

### Lunatics

Characters who use unusual equipment and radiation-based effects.

They may eventually use abilities capable of applying status effects and debuffs.

### Insane Survivors

Aggressive close-range enemies focused on direct physical combat.

### Supporters

Human characters capable of healing or supporting other survivors.

---

# Weapons

Weapons are divided into three primary categories:

* **Melee**
* **Ranged**
* **Radion**

---

## Melee Weapons

Melee weapons are divided into **cutting** and **blunt** weapons.

### Cutting

* Knives
* Machetes
* Axes
* Swords
* Spears

### Blunt

* Clubs
* Brass Knuckles
* Shock Batons
* Improvised weapons

The final weapon selection will depend on the game's combat design and technical scope.

---

## Ranged Weapons

Potential ranged weapons include:

* Bows
* Pistols
* Rifles
* Crossbows
* Slingshots

Different ranged weapons can eventually introduce different combat ranges, accuracy, damage profiles, and resource requirements.

---

# Radion

**Radion** is the name currently used for the game's radiation-based weapon and ability system.

It is intended to function as a third weapon category alongside melee and conventional ranged weapons.

Possible Radion types include:

### Biological

* Spores
* Fungi
* Viruses
* Bacteria

### Electrical

* Capacitors
* Tesla coils
* EMP-based devices

### Cryogenic

* Liquid nitrogen
* Cryogels
* Endothermic agents

### Incendiary

* Incendiary gels
* Experimental chemical compounds
* Other radiation-enhanced incendiary effects

Radion is still an experimental concept and may change significantly as the game's systems and lore develop.

---

# Progression & Ranking

The player progresses through a **Recognition** system.

Completing Arcs rewards the player with Recognition Points, which contribute toward their overall Level.

The initial prototype is planned around ten floors and a progression structure with eight ranks.

## Rank Progression

| Rank                 |   Recognition |
| -------------------- | ------------: |
| Newcomer             | Starting Rank |
| Explorer             |      +1 Level |
| Hunter               |      +1 Level |
| Survivor             |      +1 Level |
| Adapted Survivor     |      +1 Level |
| Experienced Survivor |     +2 Levels |
| Specialist           |      +1 Level |
| Veteran              |     +2 Levels |

The exact progression system is subject to change during development and playtesting.

---

# Skills

Skills are intended to improve the player's attributes and provide different progression paths.

The system is planned around the same general classes used by the game's combat design.

> Skill progression is considered a **later-stage feature** and is not a priority for the first playable prototype.

---

## Tank

Focuses on durability and heavy attacks.

Potential attributes:

* Resistance
* Health
* Stamina
* Heavy attack damage
* Blunt weapon effectiveness
* Movement speed trade-offs

---

## Attack

Focuses on mobility and fast close-range combat.

Potential attributes:

* Movement speed
* Stamina
* Attack speed
* Fast attack damage
* Cutting weapon effectiveness
* Mobility

---

## Support

Support skills are divided into two potential specializations.

### Healer

Focuses on recovery and supporting other characters.

Potential attributes:

* Healing effectiveness
* Healing speed
* Target health restoration
* Reduced Radion effectiveness
* Radion recovery

### Lunatic

Focuses on Radion-based abilities and offensive support.

Potential attributes:

* Radion damage
* Radion recovery
* Status effects
* Reduced healing effectiveness

### Shared Support Skills

Both specializations may eventually benefit from:

* Healing item crafting
* Radion item crafting
* Resource efficiency

---

## Shooter

Shooter skills are divided into two potential specializations.

### Assassin

Focuses on stealth and long-range damage.

Potential attributes:

* Long-range damage
* Stealth effectiveness
* Stealth attack damage
* Reduced direct-combat resistance

### Crossfire

Focuses on medium-range combat and durability.

Potential attributes:

* Medium-range damage
* Direct attack damage
* Resistance
* Reduced long-range damage
* Reduced stealth effectiveness

### Shared Shooter Skills

* Increased aiming range
* Improved accuracy
* Weapon handling

---

# Collectibles

Collectibles are optional items hidden throughout the game world.

They are designed to reward:

* Exploration
* Curiosity
* Puzzle solving
* Discovering hidden areas

Collectibles may eventually be used for:

* Achievements
* Currency
* Narrative discovery
* Optional progression
* Completion tracking

Some collectibles may require the player to solve environmental puzzles or reach otherwise hidden locations.

---

# Achievements

The long-term goal is to connect the game's systems to an achievement structure.

Potential achievements may reward players for:

* Completing Arcs
* Defeating specific enemies
* Finding collectibles
* Solving puzzles
* Clearing entire floors
* Completing floors without taking damage
* Discovering hidden locations
* Completing special challenges

The achievement system will be expanded after the core gameplay loop is established.

---

# Future Game Modes

Multiplayer is currently outside the scope of the project.

However, the long-term vision may include additional game modes such as:

### Co-op

Two or more players working together to survive and progress through floors.

### PvP

Player-versus-player combat using the game's existing weapon and ability systems.

### Challenges

Alternative gameplay rules such as:

* Time-limited floor completion
* Hardcore mode
* No-damage challenges
* Limited-resource runs
* Other experimental game modes

These features are considered long-term concepts rather than current development goals.

---

# Visual Direction

The game is intended to use a **pixel-art visual style** with a relatively grounded and realistic color palette.

The visual direction should combine:

* Post-apocalyptic environments
* Realistic color variation
* Strong atmospheric lighting
* Pixel-art characters and environments
* Environmental storytelling
* Contrasting visual identities between Arcs

The goal is to keep the visuals relatively simple while still creating a detailed and atmospheric world.

---

# Environmental Visual Direction

The world should feel abandoned, deteriorated, and lived-in rather than simply destroyed.

Potential environments include:

* Empty corridors
* Abandoned apartments
* Bedrooms
* Kitchens
* Bathrooms
* Stairwells
* Elevators
* Storage areas
* Barricaded buildings
* Overgrown areas
* Abandoned urban spaces

Environmental details should communicate the history of the location and suggest what happened before the player arrived.

---

# Character Visual Direction

Characters should follow a **grounded post-apocalyptic aesthetic**, with practical clothing, improvised equipment, worn materials, and distinct silhouettes.

Survivors should feel visually consistent with the environment rather than appearing overly polished or futuristic.

Mutated creatures should follow the same principle, maintaining recognizable biological origins while introducing radiation-induced distortions.

The final assets will necessarily be much simpler than the visual references that inspire them. The goal is to translate the core visual language into a cohesive pixel-art style.

---

# Multiplayer & Long-Term Scope

The project is intentionally being developed incrementally.

The first objective is not to implement every concept described in this document.

Instead, the development process will follow a gradual approach:

```text
Core Movement
      ↓
Combat
      ↓
Enemies
      ↓
Health & Damage
      ↓
Level Structure
      ↓
Safe Rooms
      ↓
Progression
      ↓
Narrative
      ↓
Advanced Systems
      ↓
Additional Game Modes
```

Each stage provides an opportunity to learn, test, refactor, and expand the project.

---

# Current Development Scope

The initial prototype focuses on establishing the fundamental gameplay loop:

* Player movement
* Jumping
* Combat
* Health and damage
* Basic enemies
* Enemy AI
* Basic level structure
* Floor progression
* Basic interactions

More complex systems such as advanced progression, skill trees, extensive Radion mechanics, achievements, NPC economies, base building, and multiplayer will only be considered once the core gameplay is stable.

---

# Development Philosophy

This project is intentionally being built as a **learning-driven game development project**.

The goal is not to immediately create a complete commercial-scale game, but to progressively understand the disciplines involved in building one.

That includes:

* Programming
* Game architecture
* Game design
* Level design
* Artificial intelligence
* Visual design
* Narrative design
* Worldbuilding
* User experience
* Debugging
* Testing
* Iterative development

As my knowledge of Game Development grows, the project's systems and design will continue to evolve.
