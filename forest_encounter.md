# Encounter — The Night Path

*A worked example of the magic system in play, with full dice rolls. This encounter was generated to stress-test the mechanics, not as a narrative showcase. Everything that happens here emerges from the system — friendly fire, backlash, temperature cascades, and the rogue dynamic all arose organically from the rolls.*

---

## Base Mechanics Used

- **Attack:** d20 + STR (melee) or AGI (ranged) vs DC = 10 + target's AGI modifier + armor bonus
- **Damage:** weapon roll + stat modifier
- **Physical save:** d20 + CON or AGI vs assigned DC
- **Armor:** chain mail +3 | rough plate +2 | reinforced leather +2 | leather+shield +2 | furs +0
- **Weapons:** longsword d6 | dagger d4 | shortbow d6 | battleaxe d8 | short spear d6
- **Starting temperature:** Temperate (forest at night)
- **Thermal scale:** Hot → Temperate → Cold → Freezing → Lethal

---

## Character Sheets

### Human Party

**Aldric** — Heavy Warrior
| STR | AGI | CON | INT | WIS | PRE | HP |
|-----|-----|-----|-----|-----|-----|----|
| 16 (+3) | 12 (+1) | 14 (+2) | 8 (-1) | 10 (0) | 10 (0) | 14 |
Equipment: longsword, round shield, chain mail
DC to hit: 10 + 1 + 3 = **14**

---

**Seren** — Agile Warrior
| STR | AGI | CON | INT | WIS | PRE | HP |
|-----|-----|-----|-----|-----|-----|----|
| 13 (+1) | 16 (+3) | 12 (+1) | 10 (0) | 14 (+2) | 8 (-1) | 12 |
Equipment: two daggers, shortbow (12 arrows), reinforced leather
DC to hit: 10 + 3 + 2 = **15**

---

**Veth** — Mage
| STR | AGI | CON | INT | WIS | PRE | HP | EP | Mastery |
|-----|-----|-----|-----|-----|-----|----|----|---------|
| 8 (-1) | 10 (0) | 12 (+1) | 14 (+2) | 16 (+3) | 12 (+1) | 11 | 0% | +2 |

*Mastery: average(CON 12, INT 14, WIS 16) = 14 × channel quality 0.9 ≈ 12 → mod +2*

Components: crystal powder ×3 (reduces EP for small casts), dried elm bark ×1 (medium cast), unidentified dried roots ×1 (unknown effect)
DC to hit: 10 + 0 + 0 = **10**

---

### Hobgoblins

**Grakh** — Brute Warrior
| STR | AGI | CON | INT | WIS | PRE | HP |
|-----|-----|-----|-----|-----|-----|----|
| 17 (+3) | 11 (0) | 15 (+2) | 7 (-1) | 9 (-1) | 8 (-1) | 14 |
Equipment: battleaxe, rough plate armor
DC to hit: 10 + 0 + 2 = **12**

---

**Thrak** — Fast Warrior
| STR | AGI | CON | INT | WIS | PRE | HP |
|-----|-----|-----|-----|-----|-----|----|
| 14 (+2) | 15 (+2) | 12 (+1) | 9 (-1) | 11 (0) | 10 (0) | 12 |
Equipment: short spear, wooden shield, leather
DC to hit: 10 + 2 + 2 = **14**

---

**Muzgash** — Shaman (rogue path)
| STR | AGI | CON | INT | WIS | PRE | HP | EP | Mastery | Instability |
|-----|-----|-----|-----|-----|-----|----|----|---------|-------------|
| 9 (-1) | 11 (0) | 10 (0) | 11 (0) | 15 (+2) | 13 (+1) | 10 | 0% | +1 | **35** |

*Mastery: average(CON 10, INT 11, WIS 15) = 12 × channel quality 0.7 ≈ 8 → mod +1*
*Instability already at 35 — background noise, minor Coherence penalty under pressure*

Components: animal bones in hair ×3 (concentrated Ether charges), bag of ash mixed with fat ×1 (unknown effect)
DC to hit: 10 + 0 + 0 = **10**

---

## Initiative

`d20 + AGI`

| Character | Roll | Mod | Total |
|-----------|------|-----|-------|
| Seren | [d20: **16**] | +3 | **19** |
| Thrak | [d20: **14**] | +2 | **16** |
| Aldric | [d20: **11**] | +1 | **12** |
| Muzgash | [d20: **12**] | +0 | **12** *(tie with Aldric → lower AGI, goes after)* |
| Grakh | [d20: **9**] | +0 | **9** |
| Veth | [d20: **7**] | +0 | **7** |

**Order:** Seren → Thrak → Aldric → Muzgash → Grakh → Veth

---

## Round 1

**Temperature:** Temperate

---

### Seren *(19)*
Spotted the camp first. Targets Muzgash immediately — the mage is always the priority.

- Bow attack on Muzgash: [d20: **15**] + 3 (AGI) = **18** vs DC 10 → **HIT**
- Damage: [d6: **4**] + 1 = **5**
- 🏹 The arrow hits Muzgash in the right shoulder. He doesn't cry out.

> **Muzgash HP: 10 → 5**

---

### Thrak *(16)*
Charges Seren who has given away her position.

- Spear attack on Seren: [d20: **8**] + 2 (STR) = **10** vs DC 15 → **MISS**
- The spear flies wide in the forest darkness.

---

### Aldric *(12)*
Engages Grakh — takes the most dangerous melee threat out of the equation.

- Sword attack on Grakh: [d20: **15**] + 3 (STR) = **18** vs DC 12 → **HIT**
- Damage: [d6: **4**] + 3 = **7**
- ⚔️ The sword finds a gap between plates. Hobgoblin blood on the path.

> **Grakh HP: 14 → 7**

---

### Muzgash *(12)*
Wounded but not in danger. Seren has spotted him — must respond. Takes a bone from his hair.

**Cast:** localized thermal burst on Seren.
*Axes: Magnitude medium (3/5) · Duration instant (1/5) · Complexity low (2/5) · Distance medium (3/5)*

- EP cost without component: 25% → with bone: **12%**
- EP Muzgash: 0% → **12%** *(Stable zone)*
- Coherence DC: **11**
- Coherence Roll: [d20: **13**] + 1 (Mastery) = **14** vs DC 11 → **SUCCESS**

🌡️ *Temperature: slight localized drop. Muzgash's breath becomes visible for a moment.*

- AGI save Seren: [d20: **10**] + 3 = **13** vs DC 12 → Success — half damage
- Damage: [d8: **6**] → **3** (halved)
- 🔥 Seren feels the burning heat on her side. Throws herself sideways, barely avoids.

> **Seren HP: 12 → 9**

---

### Grakh *(9)*
Furious from the hit. Charges Aldric with the battleaxe.

- Axe attack on Aldric: [d20: **18**] + 3 (STR) = **21** vs DC 14 → **HIT**
- Damage: [d8: **7**] + 3 = **10**
- 🪓 Devastating blow to the left side. The chain mail holds but the impact is brutal. Aldric staggers.

> **Aldric HP: 14 → 4**

---

### Veth *(7)*
Aldric is at 4 HP. If Grakh attacks again it's over. Veth decides: pressure wave to push Grakh back, buy time.

**Cast:** ethereal pressure wave on Grakh.
*Axes: Magnitude low (2/5) · Duration instant (1/5) · Complexity low (2/5) · Distance medium (3/5)*

- EP cost: **20%**
- EP Veth: 0% → **20%** *(Stable zone — thermal drop: narrative only)*
- Coherence DC: **10**
- Coherence Roll: [d20: **9**] + 2 (Mastery) = **11** vs DC 10 → **PARTIAL SUCCESS** *(by one point)*

🌡️ *Temperature drops to **Cold**. Everyone's breath becomes visible. Nearby leaves stiffen.*

The wave works — Grakh is pushed back 3 meters, skips next action. But the effect is imprecise, spreads more than intended.

**Collateral on Aldric** (in the wave's cone):
- CON save Aldric: [d20: **5**] + 2 = **7** vs DC 10 → **FAIL**
- Damage: [d4: **3**] = **3**

> **Aldric HP: 4 → 1** 💀 *Standing by a miracle.*
> **Grakh:** pushed back, skips Round 2

---

**End of Round 1**
| Character | HP | Notes |
|---|---|---|
| Aldric | **1** | Critical. One more hit and it's over. |
| Seren | **9** | Stable |
| Veth | **11** | EP 20% |
| Grakh | **7** | Skips Round 2 (pushed back) |
| Thrak | **12** | No damage |
| Muzgash | **5** | EP 12%, Instability 35 |

---

## Round 2

**Temperature:** Cold *(breath is steam, fingers beginning to numb)*

---

### Seren *(19)*
Muzgash is wounded, just cast. If she finishes him now, the magic problem is solved. Second arrow.

- Bow attack on Muzgash: [d20: **6**] + 3 = **9** vs DC 10 → **MISS by 1**
- 🏹 Fingers numb from cold. The arrow misses by centimeters. Muzgash doesn't even move.

---

### Thrak *(16)*
Sees Seren distracted. Charges.

- Spear attack on Seren: [d20: **16**] + 2 (STR) = **18** vs DC 15 → **HIT**
- Damage: [d6: **3**] + 2 = **5**
- 🗡️ The spear finds a gap in the leather. Seren takes the hit, steadies herself.

> **Seren HP: 9 → 4**

---

### Aldric *(12)*
1 HP. Half-blinded by pain. Attacks Thrak — takes pressure off Seren.

- Sword attack on Thrak: [d20: **12**] + 3 (STR) = **15** vs DC 14 → **HIT**
- Damage: [d6: **2**] + 3 = **5**

> **Thrak HP: 12 → 7**

---

### Muzgash *(12)*

5 HP left. An arrow in the shoulder. Things are going badly.

Muzgash looks around. Calculates. Then looks at Thrak.

**Drains Thrak.**

No words, no ritual gesture. Just a sudden warmth leaving Thrak's back toward Muzgash's hands.

- Damage to Thrak: [d6: **3**] = **3**
- Thrak feels cold leaving his bones. Slows down. Doesn't understand what happened.
- EP Muzgash: 12% → **0%** *(forced reset)*
- **Instability Muzgash: 35 → 48** *(drained a living being — an ally — the channel starts to creak)*

> **Thrak HP: 7 → 4**

Now Muzgash uses a second bone component. Wants to end the fight with a single big cast — heat sphere over the area around Seren and Veth, 5-meter radius.

**Cast:** area thermal energy sphere.
*Axes: Magnitude high (5/5) · Duration low (1/5) · Complexity medium (3/5 — area not trivial) · Distance medium (3/5)*

- EP cost without component: 50% → with bone: **35%**
- EP Muzgash: 0% → **35%** *(Strain zone)*
- Coherence DC: **16** *(high magnitude + area)*
- Instability at 48: **-1** penalty to roll
- Coherence Roll: [d20: **4**] + 1 - 1 = **4** vs DC 16 → **CATASTROPHIC FAILURE**

---

**BACKLASH.**

The pattern collapses before forming. Uncontrolled energy discharges back through the channel.

- Backlash damage to Muzgash: [d10: **9**] = **9**

> **Muzgash HP: 5 → -4 → DEAD**

But the energy was already partially released into the Ether. It doesn't all return to Muzgash — a fraction explodes into the surrounding area in a chaotic, formless, directionless way.

**AGI save vs DC 13 for everyone within 4 meters:**

| Character | Roll | Mod | Total | Result | Damage |
|---|---|---|---|---|---|
| Seren | [d20: **7**] | +3 | 10 | FAIL | [d6: **3**] = **3** |
| Veth | [d20: **4**] | +0 | 4 | FAIL | [d6: **5**] = **5** |
| Thrak | [d20: **11**] | +2 | 13 | PASS | — |
| Aldric | [d20: **9**] | +1 | 10 | FAIL | [d6: **2**] = **2** |

> **Seren HP: 4 → 1**
> **Veth HP: 11 → 6**
> **Aldric HP: 1 → -1 → DOWN** 💀

🌡️ **Temperature drops 2 steps → FREEZING**

Muzgash's body lies on ground cracked as if frozen from within. Branches one meter away are crystallized. Everyone can see their breath as thick fog. Those without gloves find their fingers stop responding properly.

---

### Grakh *(9)*
Back in action. Sees Muzgash down. A moment of stillness. Then a shout in Hobgoblin that needs no translation.

Charges Veth — the human mage. The responsible one.

- Axe attack on Veth: [d20: **17**] + 3 (STR) = **20** vs DC 10 → **HIT**
- Damage: [d8: **6**] + 3 = **9**
- 🪓 The axe finds Veth practically defenseless.

> **Veth HP: 6 → -3 → DOWN** 💀

---

**End of Round 2**
| Character | HP | Notes |
|---|---|---|
| Aldric | **-1** | ❌ Down, unconscious |
| Seren | **1** | ⚠️ Last human standing |
| Veth | **-3** | ❌ Down, unconscious |
| Grakh | **7** | Furious, bloody axe |
| Thrak | **4** | Stunned from draining, still standing |
| Muzgash | ❌ **DEAD** | Catastrophic backlash |

**Temperature: FREEZING**
Movement costs extra effort. Inadequately covered characters risk cold damage next round.

---

## Round 3 — The Choice

Seren is alone. 1 HP. Two companions down in the cold left by the backlash. Grakh bloodied but furious. Thrak stunned but standing.

Veth and Aldric are not dead — they are unconscious. Without stabilization, the temperature will finish what the fight started.

**Two options:**

**A — Fight:** attacks Grakh (the most dangerous), hoping to bring him down before one of the two finishes her. A single hit and she's down.

**B — Run:** attempts to drag one companion into the forest darkness, hoping Thrak is too stunned and Grakh too wounded to pursue in the freezing cold.

---

*The session stops here.*

---

## System Post-Mortem

**What worked exactly as designed:**

**Friendly fire** — Veth's partial success in Round 1 nearly killed Aldric. It wasn't a system error, it was the system saying: *when you cast imprecisely, energy goes where you don't want it.*

**Thermal drop as a tactical mechanic** — temperature went from Temperate to Freezing in two rounds. Not by chance, but as a direct consequence of magical choices. The cold is now an active variable: it affected Seren's actions (missed arrow), will determine the next rounds, and may kill the downed characters regardless of combat damage.

**Muzgash as an organic rogue** — nobody declared "I play the rogue path." The situation pushed Muzgash to drain an ally because it was the rationally efficient move. Instability rose, the next cast failed catastrophically, and the backlash hit everyone. The narrative emerged from the mechanic.

**Backlash as a physical event** — Muzgash didn't "just die." His death left a scar on the area: crystallized ground, collapsed temperature, collateral damage to four characters. The fight ends differently for everyone because of that death.

**Mage asymmetry** — Veth played defensively and conservatively, EP at 20%, still operational. Muzgash pushed everything onto a single cast and annihilated himself. Two channeling philosophies, two radically different fates.
