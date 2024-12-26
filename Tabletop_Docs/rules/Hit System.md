---
tags:
  - rules
---
---
# Hit System


## overview

the **hit system** basically determines whether an attack successfully strikes its target. this system uses a combination of dice rolls and modifiers to calculate the outcome.

---

## attack procedure

1. **declare target:** choose the target unit for your attack.
2. **roll to hit:** roll a d6 (or specified dice based on weapon/ability).
3. **check modifiers:** apply any modifiers from:
   - weapon bonuses
   - abilities
   - status effects
   - environmental factors
4. **compare to target defense:** compare the final result to the target's defense value.
   - **equal or exceed defense:** the attack hits.
   - **below defense:** the attack misses.

---

## critical hits

- a natural roll of **6** on the hit dice results in a **critical hit**.
- critical hits bypass certain defenses and deal additional damage, depending on weapon or ability effects.

### example:

- **normal hit:** deals standard weapon damage.
- **critical hit:** deals double damage or triggers a special ability.

---

## misses

- a natural roll of **1** on the hit dice always results in a **miss**, regardless of modifiers.

---

## modifiers

### positive modifiers
| source           | bonus |
| ----------------- | ----- |
| high ground      | +1    |
| weapon accuracy  | +1    |
| ability buff     | +1    |

### negative modifiers
| source           | penalty |
| ----------------- | ------- |
| cover            | -1      |
| status effect    | -1      |
| environmental    | -1      |

---
## status effects interaction

certain **status effects** can alter the hit chance:

| effect          | impact on hit system   |
| --------------- | ---------------------- |
| [[fear]]        | cannot attack          |
| [[psychadelic]] | cannot attack          |
| [[acid]]        | reduces target defense |

for more details refer to the [[status effect page]].

---

## examples of play

- **scenario 1:** a unit with a shotgun attacks an enemy in cover.
  - roll: 4
  - modifier: -1 (cover)
  - final result: 3 (miss)

- **scenario 2:** a sniper with high ground attacks a target.
  - roll: 5
  - modifier: +1 (high ground)
  - final result: 6 (hit, critical hit triggered)

---

for more details refer to the [[weapon page]] and [[ability page]].
