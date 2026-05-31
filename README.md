# Ether — A Physics-Based Magic System

A classless tabletop/digital RPG magic system grounded in thermodynamics rather than mysticism. Designed with digital implementation as the primary target (MUD, text adventure, companion app), but functional for tabletop play.

**Transparency note:** This system was developed and written with LLM assistance. The design decisions, directions, and final calls are human. The writing shows that. If you want to use an LLM to help formulate your critique or stress-test the mechanics before responding, that's actively encouraged.

---

## Core Premise

Magic is not a resource you spend. It is a physical phenomenon you interact with.

The world is permeated by a background energy field called the **Ether** — think cosmic background radiation. In rare individuals, a biological channel exists that allows them to collimate this field: transforming incoherent noise into directed, coherent patterns. The mage is a channel, not a source.

Energy is conserved. Every transformation has a cost paid somewhere. Casting magic creates negative pressure in the local Ether field — energy extracted from the environment manifests as a **temperature drop in the area**. The less skilled the mage, the larger the area affected. The drop is not flavor — it is a tactical variable that affects everyone present.

---

## Documents

| File | Contents |
|---|---|
| [`magic_system.md`](magic_system.md) | Core lore and mechanics — start here |
| [`specializations.md`](specializations.md) | Emergent character profiles (rogue path, monk, thermal mage, social manipulator, illusionist) |
| [`lich.md`](lich.md) | Lore document on the lich as cosmic horror — no combat stats |
| [`forest_encounter.md`](forest_encounter.md) | Full worked example with dice rolls — stress test of the system in play |

---

## Key Design Decisions

**No spell list.** Effects are described by the player and evaluated by the GM (or engine) across four axes: Magnitude, Duration, Complexity, Distance. Complexity is the most penalizing — destruction follows entropy and is cheap; sustained order fights it and is expensive.

**No classes.** Six base stats distributed freely. Specializations emerge from stat investment and skill choices, not class selection. A warrior with high Wisdom doesn't know yet why they have it — but the GM does.

**Mastery is derived, not assigned.**
```
Mastery = average(CON, WIS, INT) × hidden_channel_quality
```
Channel quality is set secretly by the GM at creation. The player discovers it through play.

**The rogue path is an ethical choice, not a class.** Any mage can drain living sources to instantly lower their Ether Pressure. It works. It introduces Instability into the channel, degrading it progressively. The player sees symptoms, not numbers. The exact degradation curve is sealed and set at character creation.

**Thermal magic has physical consequences.** Cold spells extract heat that must go somewhere — into the environment, into the mage's body, or onto a secondary target. Each option has costs and risks. Thermal management is opt-in complexity; if you don't engage with it, the default behavior is ambient dispersal.

**The lich is not a boss encounter.** It is a geological phenomenon with a personality. A civilization-spanning coherent Ether node. Player characters interacting with one are doing so on the scale of ants near a star. See `lich.md`.

---

## Status

Early design stage, pre-playtesting. Looking for theoretical feedback on system structure before committing to playtesting, since some architectural choices are expensive to reverse.

The companion web app (four-axis calculator, EP tracker, Instability tracker, temperature state) is planned but not yet built.

---

## Feedback Welcome

Particularly interested in:
1. Whether the four-axis framework is expressive enough to cover most fantasy magic scenarios without becoming unwieldy
2. Whether the EP/Instability dual-tracker separation feels mechanically clean or adds unnecessary friction
3. Whether classless emergent specializations work as a design principle, or whether the absence of archetypes makes character creation feel directionless
