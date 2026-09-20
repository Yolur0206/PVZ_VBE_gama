<p align="right">
  English | <a href="./README_CN.md">简体中文</a>
</p>
# Plants vs. Zombies: Vasebreaker Endless Mod

This repository contains a modified version of **Vasebreaker Endless** for the original PC version of *Plants vs. Zombies*.

The mod introduces new level mechanics, enhanced zombies, upgraded plants, Boss battles, special event levels, and three difficulty versions.

---

## Requirements

This mod requires **Cheat Engine (CE)** to run.

- **Cheat Engine:** [https://www.cheatengine.org/](https://www.cheatengine.org/)
- **Game:** The original PC version of *Plants vs. Zombies*
- **Mod files:** The `.CT` tables included in this repository

---

## Difficulty Versions

The repository provides three versions with different difficulty levels:

| Version | Difficulty | Recommended for | Rating |
| --- | --- | --- | --- |
| `older` | Easy | Recommended for first-time players | Reaching Level 20 is already impressive. Reach Level 40 and you are a true master! |
| `teen` | Medium | Players familiar with the mod | Reaching Level 30 makes you an expert. Level 40 is an elite achievement! |
| `hell` | Hard | Players looking for an extreme challenge | Survive 10 levels and you are already a master. Reach Level 20 and you have surpassed the author! |

---

## Quick Start

1. Download and install Cheat Engine.
2. Launch *Plants vs. Zombies*.
3. Use Cheat Engine to attach to the game process.
4. Import one of the `.CT` files included in this repository.
5. Choose the version you want to play. The easier `older` version is recommended for your first run.
6. Enter **Vasebreaker Endless** in the game.
7. Press the following hotkeys in order:

   - `Ctrl + J`: Initialize the mod
   - `Ctrl + K`: Enter the modified game mode

8. Restart the level to begin playing the modified version of Vasebreaker Endless.

---

## Hotkeys

Hotkeys can be customized in Cheat Engine. After loading the `.CT` table, you can inspect its entries to find additional options and shortcuts.

| Hotkey | Function |
| --- | --- |
| Hold `1 (!)` | Slow down the game |
| Hold `2 (@)` | Speed up the game |
| `Ctrl + J` | Initialize the mod or restore the original game mode |
| `Ctrl + K` | Enter the modified game mode |

---

# Major Changes

## Level Mechanics

### Basic Rules

Dave foresaw the arrival of the evil vases in a dream, so he prepared several special devices in his yard:

- Several randomly selected vases will be revealed at the beginning of each level.
- Every lane is protected by one single-use Lawn Mower.
- Plants found inside vases are more randomized.
- Plants can ignore normal placement restrictions.

Plants can even be placed on tiles containing:

- Another plant
- A vase
- A gravestone
- An ice trail

### Crisis Levels

There are two full-moon nights during the game:

- **Level 10: First Full-Moon Night**
  - The first Crisis Level begins.
  - Vases extend as far as the second column.

- **Level 20: Second Full-Moon Night**
  - The second Crisis Level begins.
  - Vases extend as far as the first column.
  - From this point onward, every level will have vases extending to the first column.

Levels 10 and 20 are the only dedicated Crisis Levels.

During a Crisis Level, a plant has a chance to leave behind a gravestone when it dies. This can prevent its normal on-death effect from activating.

### Boss Battles

Boss battles appear on Levels 30, 40, 50, and every tenth level afterward.

These levels contain special vases hiding **Giga-Gargantuars**, so plan carefully before breaking them.

### Encounter Levels

> It looks like quite a few unusual guests are hiding in the vases today!

Encounter Levels appear on Levels 5, 15, 25, and so on.

These levels contain:

- Marigolds as the only plants
- Zombie Yetis and Jack-in-the-Box Zombies as the only zombies
- Additional opportunities to collect sun and resources

### Idol Concert Levels

> GEGE has come to Dave's yard to hold a concert!

These levels contain:

- Hypno-shrooms as the only plants
- Dancing Zombies, Backup Dancers, and Gargantuars as the only zombies

### Carrying Plant Cards Between Levels

If you still have unused plant cards after completing a level, click and hold one with the mouse to carry it into the next level.

This cannot be done immediately before a Boss level because the money bag must be collected first.

---

## Zombie Changes

> Years of brain-eating experience have made some zombies far more aggressive.  
> They may no longer be the slow, clumsy, and poorly fed fools you remember!

Most zombies can now appear inside vases, with the following exceptions:

- Snorkel Zombie
- Dolphin Rider Zombie
- Balloon Zombie
- Dr. Zomboss

This also means that **Giga-Gargantuars** can appear inside vases.

Because Giga-Gargantuars are exceptionally evil, their presence turns the vase black. Always pay close attention to black vases.

### Flag Zombie

The Flag Zombie has evolved into the terrifying **Tongue-Out Flag Zombie**:

- Greatly increased movement speed
- Greatly increased attack damage

Even Dave fears this unusual creature!

### Conehead Zombie

The Conehead Zombie has evolved into the **Antimatter Conehead Zombie**!

After finding an antimatter traffic cone on the road, it decided to wear it as armor. The cone is extremely heavy, making the zombie slower, but its defensive power has increased significantly.

Long-term exposure to antimatter has also made it far more aggressive.

- Greatly increased health
- Greatly increased attack damage
- Reduced movement speed

**Weakness:** Crowd-control projectiles.

### Buckethead Zombie

- Slightly increased bucket durability
- A single Squash may no longer be enough to kill it instantly
- Explosive plants remain highly effective

### Newspaper Zombie

This seemingly kind mathematician has become significantly more dangerous:

- Increased attack damage
- A more fragile newspaper
- Enters an enraged state after losing the newspaper
- Greatly increased movement speed while enraged

Be extremely careful once its newspaper is destroyed!

### Screen Door Zombie

The Screen Door Zombie has evolved into the **Golden Screen Door Zombie**!

After invading the home of a wealthy homeowner, it stole a magnificent golden screen door and gained greatly increased defense.

**Weaknesses:**

- Reverse Repeaters
- Lobbed-shot plants

### Jack-in-the-Box Zombie

Yes, even in the world of Vasebreaker, this is still one of the most unpleasant enemies to encounter.

- Defeating it rewards `100` sun
- This reward does not apply during Encounter Levels

### Digger Zombie

The Digger Zombie has evolved into the **Wage-Collecting Digger Zombie**!

Its employer refused to pay its wages while it was alive, so it developed incredible movement and attack speed while searching for compensation.

Fortunately, it does not eat brains.

### Zombie Yeti

The Zombie Yeti has joined the Jack-in-the-Box Zombie on Dave's bounty list:

- Defeating it rewards `100` sun
- It escapes faster than in the original game
- It has increased attack damage
- It also has a much larger appetite

Defeat it quickly before it runs away!

### Catapult Zombie

This zombie loved singing, dancing, and basketball. After suffering a terrible traffic accident, it was forced to use a wheelchair.

After receiving guidance from Cai Xukun:

- Its basketball-throwing speed is greatly increased
- Its attack damage is reduced

It does not truly wish to hurt the plants. It simply loves playing basketball.

### Imp

The Imp has evolved into the **Hungry Imp**:

- Increased movement speed
- Increased attack damage

This small but extremely hungry creature is now much more dangerous.

### Gargantuar

Gargantuars become progressively stronger as the game continues:

- Every five levels, one additional normal Gargantuar is added.
- One fewer plant appears for every additional Gargantuar.
- After another five levels, the normal Gargantuar evolves into a Giga-Gargantuar.

### Zombotany Zombies

- Pea projectiles deal increased damage.
- Squash Zombies and Jalapeno Zombies move significantly faster.

> **Identification tip**
>
> - When revealed inside a vase, Zombotany Zombies appear to look like regular zombies.
> - Actual regular zombies appear inside vases wearing duck-shaped pool floaties.
>
> Use this difference to identify Zombotany Zombies before breaking their vases.

---

## Plant Changes

> Thanks to Dave's research, the plants have become much stronger.  
> Some of them have even developed entirely new abilities!

| Plant | Changes |
| --- | --- |
| Potato-type plants | Greatly increased damage and can instantly kill any zombie |
| Snow Pea | Increased firing speed |
| Chomper | Significantly increased size and durability; can survive multiple Gargantuar smashes and is the natural enemy of Gargantuars |
| Fume-shroom and Gloom-shroom | Increased damage |
| Scaredy-shroom | Greatly increased firing speed, but remains cowardly; vulnerable to fast attackers such as Pole Vaulting Zombies and Imps |
| Threepeater | Can fire spikes after receiving guidance from Cattail; spikes have a small chance to knock zombies backward |
| Torchwood | Greatly increases the damage of fire peas |
| Tall-nut | Can survive multiple Gargantuar smashes; freezes the entire screen like an Ice-shroom when destroyed |
| Blover | Blows zombies backward several tiles and applies a freezing slowdown effect |
| Starfruit | Projectiles have a 50% chance to hypnotize zombies; placement angle is extremely important |
| Cabbage-pult | Greatly increased firing speed |
| Umbrella Leaf | Greatly increased health; burns an entire lane like a Jalapeno when destroyed |
| Marigold | Randomly produces plant cards instead of coins; Sunflower and Sun-shroom are excluded, but upgrade plants such as Cob Cannon can appear |
| Spikerock | Can withstand an unlimited number of Gargantuar smashes |

---

## Survival Tips

The following strategies may help you survive longer:

1. **Combine crowd-control effects**

   Snow Pea slowdown, butter stuns, and spike knockback can create an extremely powerful control chain. This is especially effective against slow enemies such as the Antimatter Conehead Zombie.

2. **Take advantage of the Gargantuar's large body**

   Gargantuars have extremely large bodies. Try planting a Potato Mine on the tile directly behind one to destroy it.

3. **Use hypnotized zombies against Gargantuars**

   One of a Gargantuar's greatest weaknesses is a hypnotized zombie. Gargantuars will not fight back while other zombies are biting them.

4. **Use Marigolds as defensive fodder**

   Marigolds can be used as temporary shields against Gargantuars, Pole Vaulting Zombies, and Squash Zombies, giving your other plants more time to attack.

5. **Scout ahead during Boss levels**

   Vases are pushed close to the house during Boss levels, allowing zombies to reach your defenses very quickly. Consider purchasing Planterns to reveal the vases in the front columns.

6. **Watch every black vase carefully**

   A black vase may contain a Giga-Gargantuar. Prepare enough crowd control and burst damage before breaking it.

---

## Notes

- Always press `Ctrl + J` to initialize the mod before pressing `Ctrl + K`.
- If the mod does not work, make sure Cheat Engine is attached to the correct game process.
- Compatibility may vary between different versions of *Plants vs. Zombies*.
- The easier `older` version is recommended for first-time players.
- For the full custom texture experience, replace the `main.pak` file in the game directory with the version provided by this repository.
- Back up the original `main.pak` before replacing it.
