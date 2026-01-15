# HOI4 Hardcore Historical Armament Rebalance

A **hardcore historical rebalancing** of tank guns and artillery weapons for  
**Hearts of Iron IV (No Step Back tank designer system)**.

This project is **not** about power fantasy or simple stat inflation.  
Its goal is to restore **historically reasonable relative firepower** between infantry, artillery, and armored units.

---

## Project Motivation

In vanilla HOI4 (and many large mods), armored weapons suffer from a long-standing issue:

> **Tank guns and artillery often deal less effective firepower than infantry units,  
> resulting in situations where armored battalions feel weaker than foot infantry.**

This contradicts both historical reality and common military logic.

For reference, in vanilla HOI4:
- A standard infantry battalion has roughly **9 soft attack**
- A standard artillery battalion has roughly **50 soft attack**

Historically, however:
- A battalion equipped with **36 × 105mm leFH 18 howitzers**
  delivered *far greater* suppression and personnel casualties than
- An armored battalion with **~50 Panzer IV tanks firing Sprgr. 34 HE shells**

This mod aims to correct such inconsistencies.

---

## Core Design Philosophy

This project follows **relative historical effectiveness**, not absolute realism or simple multipliers.

### Three Hardcore Historical Rules

---

### 1️⃣ Howitzers & Close Support Guns  
**Role: Area firepower against infantry and fortifications**

- `soft_attack`: highest of the same technological tier  
- `hard_attack`: limited (only against very light armor)  
- `ap_attack`: intentionally low  

> Howitzers should *never* become universal anti-tank weapons.

---

### 2️⃣ High-Velocity Anti-Tank Guns  
**Role: Dedicated armor killers**

- `ap_attack`: highest in the game  
- `hard_attack`: extremely high  
- `soft_attack`: deliberately restrained  

> High-velocity AT guns are *not* infantry killers.  
> They are precision weapons, not area suppression tools.

---

### 3️⃣ General-Purpose Tank Cannons  
**Role: Balanced direct-fire weapons**

- `soft_attack`: clearly stronger than MGs / autocannons  
- `hard_attack`: reliable but below same-tier HV guns  
- `ap_attack`: scales with caliber and era  

These weapons sit **between howitzers and AT guns**, never replacing either.

---

## What This Mod Changes

### ✔ Fixes the Following Issues
- Tank cannons dealing unrealistically low soft attack  
- Howitzers having excessive armor penetration  
- Anti-tank guns being too effective against infantry  
- Poor firepower progression between early / late / extra-tier weapons (e.g. Road to 56)

### ✔ Rebalanced Content
- Machine guns, autocannons, and AA guns (including AA used in direct fire)
- Small-caliber cannons (e.g. 45mm class)
- Medium cannons and medium howitzers
- High-velocity anti-tank cannons (multiple tiers)
- Heavy cannons, heavy howitzers, and super-heavy cannons
- Road to 56 post-vanilla weapon tiers

All values are adjusted with:
- Caliber
- Ammunition type (HE vs AP)
- Historical battlefield role
- HOI4 combat model amplification in mind

---

## Intended Gameplay Outcome

- ❌ Not a power-fantasy mod  
- ❌ Not a blanket stat buff  
- ❌ Not arcade balance  

- ✅ Clear weapon roles  
- ✅ Historical firepower hierarchy  
- ✅ Meaningful tactical choices  
- ✅ Tank units no longer feel inferior to infantry  

If, after installing this mod:
- Howitzers dominate infantry suppression  
- AT guns excel against armor but not infantry  
- Tanks advance more effectively without absurd soft attack  

Then the mod is working as intended.

---

## Installation & Compatibility

- This mod only modifies **plain text data files**
- No scripts, no executables
- Can be used as:
  - A standalone mod
  - An override mod for vanilla / Road to 56 / other equipment mods

**Starting a new save is strongly recommended**.

---

## Target Audience

- Players seeking historically grounded combat behavior
- Players dissatisfied with vanilla tank firepower
- Modders looking for a historical baseline
- Fans of Road to 56 who want stricter weapon role separation

---

## Disclaimer

This project does **not** aim for 1:1 real-world physics.

“Hardcore historical” here means:

> **Historically accurate relative effectiveness and battlefield roles  
> within the abstraction of HOI4’s combat system.**

---

## Future Plans (Optional)

- AI behavior tuning with rebalanced weapons
- Doctrine and terrain interaction adjustments
- Optional “slightly softer balance” variant

---

Constructive feedback and historical discussion are welcome.  
If a weapon does not *feel* like its historical counterpart, that is exactly what this project aims to address.
