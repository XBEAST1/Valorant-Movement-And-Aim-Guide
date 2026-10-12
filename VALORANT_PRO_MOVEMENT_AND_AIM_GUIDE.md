# Valorant Movement & Aim Guide (Competitive & Radiant Tier)

A high-signal technical reference for movement mechanics, gunfight hygiene, crosshair geometry, hardware settings, and training routines.

> ⚡ **Quick-Reference Cheat Sheet:** For 30-second buy-phase triage and mid-game emergency resets, jump to **[CHEATSHEET.md](CHEATSHEET.md)**.  
> 🎯 **Custom Crosshair Compendium:** For Beast's Double Edge profiles, visual previews, and import codes, see **[CROSSHAIRS.md](CROSSHAIRS.md)**.

---

## Table of Contents
* ⚡ **[Quick-Reference Cheat Sheet](CHEATSHEET.md)**
* 🎯 **[Beast's Crosshair Compendium](CROSSHAIRS.md)**
1. [Engine Physics & Fundamental Velocity Mechanics](#engine-physics)
2. [Deadzoning vs. Counter-Strafing](#deadzoning-vs-counter-strafing)
3. [The Pro Peeking Catalog](#pro-peeking-catalog)
4. [Perspective Advantage & Geometry](#perspective-advantage)
5. [Crosshair Placement & Pre-Aim Discipline](#crosshair-placement)
6. [Gunfight Hygiene & Firing Discipline](#gunfight-hygiene)
7. [Micro-Adjustments & Biomechanics](#micro-adjustments-biomechanics)
8. [Crouching: Pro Rules vs. Low-ELO Suicides](#crouching-rules)
9. [Advanced Elevation & Movement Tech](#advanced-elevation-tech)
10. [Hardware, Sensitivity & In-Game Settings](#hardware-settings)
11. [Daily Pro Warmup & Aim Training Regimen](#warmup-regimen)
12. [Common Bad Habits vs. Pro Habits Matrix](#habits-matrix)

---

<a id="engine-physics"></a>
## 1. Engine Physics & Fundamental Velocity Mechanics

### Deceleration & Friction Dynamics
* **High Ground Friction:** Valorant features high deceleration friction compared to Source-engine titles.
* **Deceleration Benchmarks:**
  * Releasing a movement key (`A` or `D`) drops character velocity to zero in **~8–10 server ticks (~62.5–78 ms)** at 128-tick.
  * Tapping the opposite key (counter-strafing) halts velocity only **~10–20 ms faster** than pure release.
  * *Key Takeaway:* Pros still tap the opposite key primarily as a tactile timing cue to immediately reverse direction into a deadzone burst.

<a id="velocity-threshold"></a>
### The 30% Velocity Threshold Rule
All weapons maintain **100% standing accuracy (zero movement error)** whenever character velocity drops to **$\le$ 30% of maximum run speed**.

| State | Speed | % of Max Run | Accuracy Status |
| :--- | :--- | :--- | :--- |
| **Rifle Full Sprint** | `5.40 m/s` | 100% | Full movement spread penalty |
| **Knife Sprint** | `6.75 m/s` | 100% | N/A (Melee) |
| **Shift-Walking** | `3.00 m/s` | 55.5% | **Inaccurate** (Exceeds 30% threshold) |
| **Rifle Accuracy Threshold** | **`1.62 m/s`** | **30.0%** | **100% Standing Accuracy Boundary** |
| **Crouch-Walking** | `1.50 m/s` | 27.8% | **100% Accurate** (Below 1.62 m/s threshold) |

---

<a id="deadzoning-vs-counter-strafing"></a>
## 2. Deadzoning vs. Counter-Strafing

<a id="reversal-deadzoning"></a>
### 1. Reversal Deadzoning (Direction-Swap)
Used when oscillating laterally across cover or in open duels.

```
Holding A (-5.4 m/s) ---> Tap D ---> Apex (<1.62 m/s) ---> Holding D (+5.4 m/s)
                                            |
                                    [FIRE 1-2 BULLETS]
```

* **Execution:**
  1. Hold `A` at full speed (`5.40 m/s`).
  2. Release `A` and tap `D`.
  3. During the zero-crossing window (~130–150 ms) where speed drops below `1.62 m/s`, fire 1–2 bullets.
  4. Continue holding `D` to build speed in the opposite direction without standing still.

<a id="stutter-deadzoning"></a>
### 2. Stutter Deadzoning (Same-Direction Brake)
Used to chain multiple peeks in one direction (`D -> D -> D`) without bouncing back into the enemy's crosshair.

```
Sprint D (+5.4 m/s) -> Brake A (30-50ms) -> Apex (<1.62 m/s) -> Resume D
                                                   |
                                           [FIRE 1-2 BULLETS]
```

* **Execution:**
  1. Sprint right with `D` (`5.40 m/s`).
  2. Tap `A` for **30–50 ms** as a mechanical brake to pull velocity below `1.62 m/s`.
  3. Fire 1–2 accurate bullets during the deceleration dip.
  4. Immediately press and hold `D` again to resume sprinting right.
* **Tactical Advantage:** The enemy expects you to bounce back left and holds their reticle at the center point. Continuing in the same direction pulls you clean out of their crosshair cone.

---

<a id="inaccuracy-graph-verification"></a>
### Inaccuracy Graph Verification ("Yellow Bar" Test)
1. Set **Settings $\rightarrow$ Video $\rightarrow$ Stats $\rightarrow$ Shooting Error $\rightarrow$ Text & Graph**.
2. **Yellow Bar:** 100% standing accuracy (`0.00°` movement error). Deadzone timing was correct.
3. **Blue Bar:** Movement error triggered. You clicked before dropping under `1.62 m/s`.
4. **Drill:** In The Range (Eliminate 50 Bots, Armor ON), maintain continuous strafing and accept only kills producing consecutive yellow bars.

---

<a id="anti-metronome-strafing"></a>
### Asymmetric & Anti-Metronome Strafing (`A -> D -> D -> D -> A`)
* **The Metronome Trap:** Symmetrical left-right strafing (`A -> D -> A -> D`) allows enemies to simply hold their crosshair still at the center point and wait for your head to bounce back.
* **Asymmetric Patterns:** Combine Reversal and Stutter deadzones (`A -> D -> D -> D -> A`). Double-tapping in the same direction breaks enemy timing prediction and causes them to pre-fire empty air.
* **Amplitude Modulation (Micro-Strafes vs. Wide Slides):**
  * *Short Micro-Strafe (1 pace / ~0.5m):* Keeps the enemy's wrist settled in a narrow micro-correction range.
  * *Wide Slide (2–3 paces / ~1.5–2.0m):* Accelerates past their wrist range, forcing an emergency forearm sweep and causing over-flick whiffs.
  * **Sequence:**
    $$\text{Short Step Left (A)} \longrightarrow \text{Wide Slide Right (D)} \longrightarrow \text{Stutter Right (D)} \longrightarrow \text{Short Step Left (A)}$$

*(See [Section 10](#hardware-settings) for Rapid Trigger switch optimization).*

---

<a id="pro-peeking-catalog"></a>
## 3. The Pro Peeking Catalog

### Universal Peeking Law: Distance from the Wall Enables Peeker's Advantage
* **The Distance Rule:** Always position your model **as far away from the corner wall as terrain allows** before peeking.
* **Why Distance is Mandatory for Peeker's Advantage:** Peeker's advantage (30–50 ms client-server network lead) is completely destroyed if you hug the wall. Hugging corners exposes your outer shoulder and gun barrel to the defender before your camera eye clears the obstacle (giving them *Perspective Advantage*). Peeking from maximum distance ensures your camera sees their body first, allowing peeker's advantage to fully take effect.

<a id="shoulder-peek"></a>
### 1. The Shoulder Peek (Info Bait / Anti-Operator)
* **Goal:** Bait an Operator or sniper shot without exposing your head hitbox.
* **Execution:**
  1. Turn crosshair **45° to 90° into the adjacent wall** (looking away from the opening).
  2. Micro-strafe outward with `A` or `D` for **40–70 ms** so only the outer arm hitbox clears cover.
  3. Immediately counter-strafe back into cover.
  4. Complete the cycle in under **0.22 seconds** to eliminate footstep audio.

<a id="prefire-jiggle"></a>
### 2. The Pre-Fire Jiggle Peek
* **Goal:** Clear a known, high-probability contact point with an instant lethal burst.
* **Execution:** Pre-aim through the wall onto the exact coordinate $\rightarrow$ step out with `A`/`D` $\rightarrow$ fire 1–2 bullets at the apex $\rightarrow$ snap back.
* **Rule:** Never repeat identical cadence twice. Predictable jiggles get pre-fired.

<a id="jump-peek"></a>
### 3. The Jump Peek (Parabolic S-Curve)
* **Goal:** Safely gather visual info against snipers with zero landing audio.
* **Execution:** Knife out (`6.75 m/s`) $\rightarrow$ run parallel with `W` $\rightarrow$ jump and tap `D` (or `A`) past the corner $\rightarrow$ whip back at apex with `S + A` (or `S + D`) $\rightarrow$ land behind cover. Baits the sniper's **1.50-second bolt rechamber delay**.

<a id="swing-variations"></a>
### 4. Swing Variations Comparison

| Peeking Technique | Input Sequence | Speed & Geometry | Tactical Purpose |
| :--- | :--- | :--- | :--- |
| **Ferrari Swing** | Pure `A` or `D` (Perpendicular to line of sight) | Max lateral speed (`5.40 m/s`). No `W`/`S`. | Exploits peeker's advantage (**30–50 ms lead**). Maximum angular velocity across enemy screen. |
| **Wide Swing** | Run 1.5–2 character widths past standard pre-aim point | Constant `5.40 m/s` momentum into open space | Punishes tight crosshair placement by forcing a wide tracking flick. |
| **Poppin Swing** | Wide running swing $\rightarrow$ sudden crouch lock | Full sprint wide $\rightarrow$ instant `Ctrl` lock | Forces two-axis error: enemy must track horizontal speed, then pull down vertically against weapon bloom. |

<a id="slicing-the-pie"></a>
### 5. Slicing the Pie & Through-the-Wall Pre-Aim
* **Concentric Angle Isolation:** Clear unknown 90° corners in **5°–10° isolated wedges** using micro-strafes from maximum distance from the wall.
* **Through-the-Wall Pre-Aiming (Zero-Adjustment Click-Timing):**
  * When you suspect or know an enemy is holding an angle, **pre-align your crosshair through the wall directly onto their expected head position BEFORE stepping out**.
  * As you micro-strafe out and clear the slice, your crosshair emerges already resting on their head.
  * **Zero Aim Adjustment Required:** You do not have to reactively flick or drag your mouse. The engagement becomes a pure **click-timing trigger pull**: the exact millisecond line of sight clears, you simply click and kill them.
* **Isolating Duels:** Geometry masks all other defenders, converting chaotic contested sites into a series of isolated, effortless 1v1 executions.

---

<a id="perspective-advantage"></a>
## 4. Perspective Advantage & Geometry

### Euclidean Distance Law
The player positioned **farther from the corner** sees the opponent first.

```
       [Wall]
         █████
[Close]  █████----------------------> Sees close player's outer shoulder
 (Eye)   █████                     /
   \                               /
    \----------------------------> [Distant Player]
     (Blocked by wall corner)        (Full visual advantage)
```

* The first-person camera is centered between the eyes. Shoulders and weapon barrels extend outward.
* If you hug the wall, your shoulder and gun barrel become visible before your camera eye clears the corner.
* **Why Distance Enables Peeker's Advantage:** Peeker's advantage (30–50 ms client-server network lead) is completely negated if the defender sees your shoulder before you have vision. Peeking from maximum distance gives you geometric perspective advantage, allowing your peeker's advantage to fully take effect.
* **Rule:** Always maximize distance from the corner wall when peeking or holding angles.

<a id="diagonal-penalty"></a>
### Diagonal Peeking Penalty (Holding W+D / W+A)
* Approaching corners with `W + D` or `W + A` directs velocity vectors forward toward the enemy.
* Lateral angular velocity drops significantly on the defender's screen, making you appear to walk slowly forward in a straight line.
* **Rule:** Approach perpendicular to the corner and swing with **pure lateral inputs (`A` or `D` only)**.

<a id="depth-shifting"></a>
### Depth-Shifting on Re-Peeks
* **The Problem:** Re-peeking from the identical spot lets defenders pre-fire your exact head pixel.
* **The Fix:** Step **1–2 paces closer or farther** behind cover before peeking again:
  * *Stepping farther back:* Alters perspective geometry; head model emerges wider from the corner edge.
  * *Stepping closer:* Increases angular emergence speed across their screen.
* **Compound 2-Axis Disruptor:** Combine depth-shifting with crouching on re-peeks to simultaneously break horizontal pre-aim and vertical head height.

---

<a id="crosshair-placement"></a>
## 5. Crosshair Placement & Pre-Aim Discipline

<a id="map-rulers"></a>
### Built-In Map Rulers for Head Height
* **Single Radianite Crate:** Top horizontal edge marks standing head height on level ground.
* **Stacked Crates:** Horizontal groove between crates marks exact head height.
* **Wall Trim & Paint Decals:** Horizontal architectural bands across maps align with player head height.
* **Teammate Calibration:** Align crosshair with a teammate's head during buy phase to calibrate vertical height for that elevation plane.
* **Ramps & Inclines:** Pre-aim at the exact lip where the head first breaches rather than holding parallel to the slope.

---

<a id="holding-depth"></a>
### Holding Depth Spectrum (Tight vs. Mid-Hold vs. Extra-Wide)

```
Tight (<40px)       Default Mid-Hold (60-120px)      Extra-Wide (150-250px)
[WALL]|·            [WALL]|    ·                     [WALL]|            ·
Op / Shift-Walk     Pro Default (1-1.5 Chars)        Ego-swings / Mobility
```

1. **Default Mid-Hold (~60–120px / 1–1.5 Character Widths):**
   * **Universal Pro Default:** Catches wide swings on standard reaction time (~180–200 ms); requires only an effortless sub-15px wrist flick for jiggle-peeks.
2. **Tight Hold (<40px / Corner Edge):**
   * Use strictly with Operator/Marshal, or with verified audio cues that the enemy is shift-walking.
3. **Extra-Wide Hold (150–250px / 2–3 Character Widths):**
   * Use against high-mobility entries (Neon slide, Jett dash) or anti-eco pistol rushes.
   * **The "Ego-Swing" Read:** In 1vX clutches (defenders hunting the final player) or when facing opponents on hot streaks, enemies sprint out aggressively without clearing methodically. Shift crosshair to Extra-Wide so their forward momentum walks directly into your reticle.

---

<a id="wasd-aiming"></a>
### Aiming with Movement (WASD Placement vs. Mouse Flicking)

```
Reactive Aim:  Lazy crosshair -> Swing -> Wide mouse flick (High variance)
Pro WASD Aim:  Pre-aim wall   -> Strafe onto head -> Sub-20px micro-adjust
```

1. **Core Principle:** Your keyboard places the crosshair; your mouse only fine-tunes it. Never flick to an angle you can step into.
2. **Workflow:**
   * *Step 1 (Pre-Aim):* Align crosshair through the wall to the expected target coordinate and head height.
   * *Step 2 (WASD Sweep):* Step out using pure lateral movement (`A` or `D`). Let character movement sweep the reticle across the angle while keeping the mouse hand neutral.
   * *Step 3 (Micro-Correction via Keyboard vs. Mouse):* If the target is slightly off-angle (10–30px), **micro-adjust using a subtle `A` or `D` step to walk your reticle onto their skull rather than micro-flicking with the mouse**. Mouse flicks under adrenaline frequently over-flick or jitter; keyboard micro-steps provide 100% stable, binary alignment.
   * *Step 4 (Deadzone Timing):* Counter-tap the opposite movement key and fire at the apex.

---

<a id="anticipation-vs-passive"></a>
### Anticipation vs. Passive Checking
* **Passive Checking Trap:** Checking angles hoping nobody is there causes surprise lag (~100 ms) and flinching, stretching reaction time to ~250–300 ms.
* **Proactive Expectation:** Approach every corner anticipating an enemy pre-aimed at your head. Pre-visualizing the target cuts cognitive recognition latency, dropping reaction time to **~150–180 ms** and eliminating startle flinches.

---

<a id="enemy-pattern-recognition"></a>
### Tactical Pattern Recognition: Reading & Exploiting Enemy Habits
Crosshair placement, angle holding, and map positioning must adapt dynamically to the opponent's round-to-round macro patterns:

1. **Site Push Sequencing (Site Spam vs. Alternating Cadence):**
   * **The Habit:** Teams frequently develop identifiable push rhythms: either hitting the same site 3 rounds consecutively until punished, or alternating symmetrically (`Round 1: A -> Round 2: B -> Round 3: A`).
   * **The Exploit:**
     * *Against Site Spam:* Stack the favored site early (3–4 players) or execute an aggressive early info-peek to shut down their execution before utility lands.
     * *Against Alternating Cadence:* Pre-rotate an anchor to the anticipated site before the execute begins, placing crosshairs on the primary entry choke while attackers expect a light defense.

2. **The Habitual Lurker Read & Exploit:**
   * **The Habit:** Sentinel or Controller players often separate from the pack every round to execute a late flank or mid lurk while their team creates loud audio contact on site.
   * **The Exploit:**
     * *The Lurk-Catcher Anchor:* **Never rotate on first audio contact.** Designate one player to remain behind holding the flank choke with an off-angle crosshair.
     * *Proactive Lurk Hunt:* Once a lurker's route is identified, send two players to collapse and eliminate the lurker early in the round. Securing this kill yields a free 5v4 man advantage, destroys enemy map control, and forces their main attack into a disorganized push.

3. **Pacing & Cadence Exploitation:**
   * **Fast-Pace Rush Teams:** Hold Extra-Wide crosshair depths (150–250px), delay with mollies/stuns, and avoid taking close dry 50/50 duels.
   * **Slow Default Teams:** Hold standard Mid-Holds, conserve defensive utility until 0:40 on the round timer, and punish predictable late-round executes.

4. **Anti-Conditioning: Becoming Unpredictable & Off-Angle Mastery:**
   * **The Predictability Trap:** If you contest Mid or A-Main at 1:40 on the round timer two rounds in a row, the enemy will adapt: two players will swing together, pre-fire your exact pixel, or dump utility to delete you instantly.
   * **Varying Timings:** Alternate between aggressive opening peeks, delayed mid-round peeks (waiting for initial utility to fade), and passive angle-holding.
   * **Off-Angles vs. Standard Corners:**
     * Standard corners are vulnerable to enemy pre-aiming and "pie slicing".
     * Holding **open, non-standard space (off-angles)** catches opponents while their reticle is pre-placed on adjacent map geometry. The enemy must execute an emergency reactive flick while you enjoy an effortless static click-timing kill.
     * **The "One-and-Done" Relocation Rule:** Once you secure a duel from an off-angle, **relocate immediately**. Never hold the identical off-angle twice in one match. Opponents will pre-aim your exact spot next round.

5. **Economy Reads & Weapon Matchup Exploitation:**
   * **Enemy on Eco / Save (Low Credits & Shotgun Danger):**
     * **The Shotgun Threat:** Eco players compensate for weak firepower by buying cheap shotguns (Judge, Bucky, Shorty) and camping tight corners, smokes, or chokes.
     * **The Positioning Rule:** **Never hold or dry-clear close-contact angles (<10m).** Back up to long-range sightlines (>20m) where rifles hold a 100% mathematical accuracy and damage advantage.
     * **The Outlaw Exploit (One-Shot Body Kills):** On eco rounds, enemies frequently purchase Light Shields (125 total HP) or no shields. The Outlaw deals **140 body damage**, securing an instant 1-shot kill to the torso without needing headshots.
     * **Crosshair Adjustment:** Hold **Extra-Wide (150–250px)**; eco players frequently sprint or swarm chokes together at full speed.
   * **Enemy on Surplus Economy / Full-Buy (Operator & Heavy Shield Threat):**
     * **The Operator Threat:** When the enemy has 4,700+ credits (especially with Jett, Chamber, or defensive anchors), assume long lanes (Ascent Mid, Haven C-Long, Bind B-Long) are locked down with an Operator.
     * **The Peeking Rule:** **NEVER dry-peek long sightlines with a rifle.** Dry-peeking a scoped Operator is an unforced error.
     * **The Counter-Play:** Enforce **Jump Peeks** (Section 3) to safely bait the 1.50-second bolt rechamber delay, flush the sniper with flashes or smokes, or coordinate simultaneous two-man wide trade swings.

---

<a id="crosshair-architecture"></a>
### Crosshair Architecture: Beast's Double Edge Compendium
A player's crosshair must match their aiming biomechanics. Rather than choosing between a pure dot (pinpoint 1-taps but no spray horizon) and standard crosshairs (spray containment but pixel occlusion at 30m+), pro mechanics leverage a **Dual-Focal Architecture**.

👉 **[Read the Full Crosshair Compendium & Visual Previews in CROSSHAIRS.md](CROSSHAIRS.md)**
* **[Beast's Double Edge (V1 — Cyan)](CROSSHAIRS.md#beasts-double-edge-v1-cyan):** Micro-cross center box + tight peripheral spray cage (Phantom / rapid burst focus).
* **[Beast's Double Edge 2 (V2 — Red)](CROSSHAIRS.md#beasts-double-edge-v2-red):** Solid center bead + wide ghosted leveling bracket (Vandal / 1-tap precision focus).

---

<a id="gunfight-hygiene"></a>
## 6. Gunfight Hygiene & Firing Discipline

### Fire Modes & Engagement Distances

```
0m ------------- 10m -------------- 25m -------------- 40m+
   [Full Spray]       [2-Shot Burst]       [2-Shot / Taps]    [Pure 1-Tap]
   (Phantom only)     (Vandal / Phantom)   (Deadzone Strafe)  (Recoil reset)
```

<a id="recoil-synchronization"></a>
### 2-Shot Burst Cadence & Recoil Synchronization
* **Cadence:** `Fire 2 bullets -> Strafe 2 paces (300-375 ms) -> Deadzone -> Fire 2 bullets`.
* **Recoil Cooldowns:**
  * Vandal reset: **375 ms**.
  * Phantom reset: **350 ms**.
  * A 2-pace lateral strafe takes ~350–380 ms. Strafing between bursts naturally absorbs the weapon recoil cooldown.

<a id="spray-commit-rules"></a>
### Spray Commit Rules
* **Vandal Cutoff (3–4 Bullets Max):** Beyond bullet 4, horizontal spread becomes randomized bloom. If bullets 1–2 miss, disengage, strafe 2 steps to reset recoil, and re-engage. Never pull down and spray past bullet 4 at >12m.
* **Phantom Exceptions (<15m):** Sprays up to 5–6 bullets are viable at close range due to higher fire rate (11 rounds/s) and tighter initial spread. Suppressed tracers also make Phantom ideal for spamming smokes.

---

<a id="micro-adjustments-biomechanics"></a>
## 7. Micro-Adjustments & Biomechanics

### Anatomical Role Division
* **Arm (Shoulder/Elbow):** Macro-movements. Clearing 90°/180° angles and tracking high-speed mobility.
* **Wrist (Carpal Joint):** Micro-adjustments. Horizontal corrections within a 50–150 pixel radius.
* **Fingertips (Grip Manipulation):** Recoil compensation. Pulling down on bullets 2–3 of a burst without disturbing horizontal wrist alignment.

<a id="under-aiming"></a>
### Under-Aiming vs. Over-Aiming
* **Over-Aiming Penalty:** Flicking past a target requires muscular braking and firing antagonistic muscles to reverse direction, wasting **100–150 ms**.
* **Under-Aiming (85%–90% Flick):** Flicking slightly short allows completion via a single unidirectional micro-snap or lets target movement walk into the crosshair.

<a id="keyboard-micro-adjustments"></a>
### Keyboard Micro-Adjustments (Anti-Overflick Technique)
* **The Mouse Overflick Risk:** When an enemy is standing slightly off your pre-aim (10–30px away), micro-flicking with the mouse under match adrenaline frequently leads to **over-flicking past the skull, tendon tension, or jittery corrections**.
* **The Keyboard Solution (The "Micro-Step" Alignment):**
  * Keep your mouse hand steady and **micro-tap `A` or `D` to step your crosshair that extra fraction of an inch directly onto their head**.
  * **Why it works:** Keyboard switches provide binary, digital actuation with fixed physical key travel, completely removing analog mouse sensor error, jitter, and overshooting.
  * Once the micro-step brings the reticle over the skull, deadzone and click for an instant kill.

<a id="pre-peek-wrist-reset"></a>
### Pre-Peek Wrist Reset & Mouse Centering
* Turning corners and checking flanks causes the mouse to drift toward the pad edges, leaving the wrist cocked in lateral deviation.
* A bent wrist locks carpal tendons, eliminating micro-adjustment range and inducing jittery aim.
* **Habit:** Subconsciously lift and re-center the mouse to a neutral posture before initiating any peeking strafe.

---

<a id="crouching-rules"></a>
## 8. Crouching: Pro Rules vs. Low-ELO Suicides

| Low-to-Mid ELO Mistake | Radiant / Pro Discipline |
| :--- | :--- |
| Panic crouching on bullet 1 | Standing 2-round burst + lateral strafe |
| Crouching at >20m range | Never crouching at long range |
| Crouching against multiple foes | Mobile burst to isolate individual 1v1s |
| Crouching in open space with no cover | Staying mobile to retreat behind geometry |

### Suicide vs. Pro Usage
* **Suicide Conditions:**
  * *On Bullet 1:* Opponents aiming chest-level hit your head as you duck.
  * *At >20m Range:* Freezes position in the open, making you an easy static target.
  * *Against Multiple Foes:* Eliminates retreat mobility, guaranteeing an immediate trade.
* **Pro-Level Usage:**
  * *Bullet 3–4 Commit (<10m):* Pulls crosshair down with rifle recoil during close-range commitments.
  * *Radiant Head-Level Dodge:* Dropping into a crouch on bullet 2–3 against high-tier opponents ducks under their initial headshot burst.
  * *Poppin / Compound Swings:* Combining wide lateral momentum with a sudden crouch lock breaks enemy tracking across both horizontal and vertical axes.

---

<a id="advanced-elevation-tech"></a>
## 9. Advanced Elevation & Movement Tech

<a id="silent-box-mount"></a>
### Silent Crouch Jump (Crate Mounting)
1. Hold `Ctrl` (crouch) while walking toward the box.
2. Press `Space` (jump) while holding `Ctrl`.
3. Release `Ctrl` (uncrouch) at the exact apex of the jump as feet clear the box lip.
4. Mounts standard Radianite crates on Ascent, Haven, Bind, and Split with zero landing audio.

<a id="silent-edge-drops"></a>
### Silent Edge Drops
* **Crouch-Drop:** Tap `Ctrl` immediately before sliding off an edge. Shortens vertical fall distance by ~35–40 cm, staying below the audible impact velocity threshold.
* **Wall Collision Drag:** Scraping against angled walls or crates during falls decelerates downward velocity below the audio trigger.

<a id="rope-discipline"></a>
### Rope & Ascender Discipline
* **Accuracy Penalty:** Rifles on ropes incur **1.3 base spread**; shotguns incur running spread (3.0). Never take long-range duels on ropes.
* **Silent Latch:** Approach the ascender, cancel horizontal momentum, hold `Shift`, and press `F` (use) to eliminate the metallic attachment audio.
* **Bhop Detach:** Press `Space` at the top of an ascender to convert vertical momentum into a bunnyhop slide for silent site entry.

---

<a id="hardware-settings"></a>
## 10. Hardware, Sensitivity & In-Game Settings

<a id="sensitivity-tiers"></a>
### Sensitivity Tiers & eDPI Distribution
$$\text{eDPI} = \text{Mouse DPI} \times \text{In-Game Sensitivity}$$

* **Competitive Median:** **200–260 eDPI** (~50 to 65 cm/360). ~75% of Tier-1 pros operate between 200 and 300 eDPI.
* **Low-Sens (160–200 eDPI):** Maximum static crosshair stability and micro-precision; requires full arm movement for 180° turns.
* **Medium-Sens (200–260 eDPI):** Balanced sweet spot for wrist micro-adjustments and arm clearance.
* **High-Sens (260–320+ eDPI):** High agility for fast entry and mobility tracking; higher risk of micro-jitter under pressure.

### Hardware Optimizations
* **Mouse DPI (1600 DPI):** Reduces sensor reporting latency by ~1.0–1.5 ms compared to 400 DPI by generating more displacement counts per millimeter, without triggering firmware smoothing (>3200 DPI).
* **Mouse Grips:** Claw grip provides the optimal balance of palm stability for angle holding and finger mobility for micro-corrections.

---

<a id="magnetic-keyboard-profile"></a>
### Magnetic Keyboard Configuration (Hall Effect / Rapid Trigger / Snap Tap)

Magnetic (Hall Effect) keyboards eliminate mechanical switch debounce latency, allowing physical finger movement to map directly to character deceleration.

#### Recommended Profile Settings

| Key | Actuation Point | Rapid Trigger (Press / Release) | Deadzone | Snap Tap / SOCD | Technical Function |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **`A` & `D`** | **0.2 mm** | **0.1 mm / 0.1 mm** (Continuous) | **0.1 mm** | **ON** | Instant lateral actuation; lifts cut engine velocity immediately; Snap Tap eliminates overlap delay during direction-swap deadzones. |
| **`W` & `S`** | **0.2 mm** | **0.1 mm / 0.1 mm** (Continuous) | **0.1 mm** | **OFF** | High-responsiveness forward/back movement. Snap Tap disabled to prevent accidental momentum overrides during utility deployment or planting. |
| **`Ctrl` (Crouch)** | **0.2 mm** | **0.1 mm / 0.1 mm** (Continuous) | **0.1 mm** | **OFF** | Hyper-responsive crouch registration and instantaneous release when un-crouching from committed sprays or head-dodges. |

#### Key Mechanics & Diagnostics
1. **Actuation Point (0.2 mm for WASD & Ctrl):**
   * Drops switch trigger travel from standard mechanical ~2.0 mm down to 0.2 mm. Inputs register nearly the instant downward force begins.
   * *Discipline Note:* Ensure finger posture does not lazily rest on keys; 0.2 mm triggers on slight depression, which can cause inadvertent footsteps if careless.
2. **Continuous Rapid Trigger (0.1 mm Upstroke / Downstroke):**
   * **Upstroke (0.1 mm):** The switch unregisters after only 0.1 mm of upward travel at any point in the stroke. This shaves ~60–80 ms of switch rebound time off every counter-strafe and deadzone.
   * **Continuous Mode: ON:** Tracks relative key travel across the entire stroke, meaning rapid-fire direction changes trigger without returning to the top baseline.
3. **Deadzone Filtering (0.1 mm Top/Bottom):**
   * Filters out magnetic sensor noise/electrical jitter when switches are fully released or bottomed out against the plate. Prevents phantom input chatter.
4. **Snap Tap / SOCD Isolation (`A` & `D` ONLY):**
   * **Why only `A` & `D`:** Lateral movement dictates 100% of rifle gunfights in Valorant. Binding Snap Tap to `A` and `D` prioritizes the most recent input, eliminating the "dead-stop cancel" overlap window when reversing directions during jiggle peeks.
   * **Why keep `W` & `S` OFF:** Forward/backward movement is not used for counter-strafing. Keeping Snap Tap off on `W`/`S` preserves natural momentum control and avoids accidental cancellations when pressing forward into cover or moving diagonally.
   * **The "Double-Release" Habit:** Because Snap Tap prioritizes the last pressed key, releasing `D` while still holding `A` resumes movement left (`A`). To come to a complete zero-velocity dead stop, you must physically release both keys.

---

<a id="critical-in-game-settings"></a>
### Critical In-Game Settings

| Setting | Optimal Configuration | Technical Reason |
| :--- | :--- | :--- |
| **Raw Input Buffer** | **ON** | Bypasses Windows input pump, directly feeding mouse packets into Unreal Engine tick rate. Eliminates dropped inputs at $\ge$1000Hz polling. |
| **NVIDIA Reflex** | **On + Boost** | Locks GPU core clocks at maximum frequency, preventing latency spikes inside smokes and heavy utility. |
| **Scoped Sens Multiplier** | **1.00** | Maintains uniform angular rotation speed between hipfire and scoped ADS. |
| **Auto-Equip Prioritizes** | **Strongest** | Prevents auto-equipping melee after spike plants, defuses, weapon drops, or abilities. Guarantees primary weapon is drawn. |
| **Don't Auto-Equip Melee** | **ON** | Ensures the game never defaults to holding a knife in combat transitions. |
| **Enable HRTF** | **ON** | Simulates 3D binaural spatial audio for accurate elevation (vertical) and directional front/back footstep localization over stereo headphones. Disable third-party virtual surround software to prevent audio distortion. |

---

<a id="warmup-regimen"></a>
## 11. Daily Pro Warmup & Aim Training Regimen

### 1. Decoupled Tracking Drill (The Range: 5–10 Minutes)
* **Objective:** Decouple aiming from panic trigger pulling.
* **Execution:**
  1. Spawn static bots in The Range; hold Sheriff without firing.
  2. Lock crosshair on a bot's head.
  3. Perform continuous lateral strafes, deadzones, jumps, and crouches while keeping the crosshair glued to the head.
  4. Only fire after 5 minutes of tracking, and strictly when the head is 100% visually confirmed under the reticle.

### 2. Eliminate 50/100 Bots (Deadzone Rhythm: 10 Minutes)
* Select **Eliminate 50 or 100 Bots** with Armor ON.
* Maintain continuous strafe rhythm: `Strafe A -> Deadzone -> 1-Tap -> Strafe D -> Deadzone -> 1-Tap`.
* Reset if you fire a panic shot; target >90% headshot accuracy with zero blue bars on the shooting error graph.

### 3. The 20m Outdoor Target Dummy Counter-Strafe Drill (5–10 Minutes)
* **Location & Setup:**
  1. From the main shooting range hall, walk outside into the open-air courtyard overlooking the floating islands and background flying target drones to the **Accuracy Target board**.
  2. Shoot the **`20m`** button on the target console to position the target board at 20 meters.
  3. Shoot the **Target Dummy** button to spawn an immortal practice bot at the 20m line.
* **Objective:** Build isolated, flawless lateral counter-strafe timing and continuous head-tracking at the premier competitive rifle engagement distance.
* **Execution:**
  1. Align your crosshair dead-center on the 20m bot's head.
  2. Hold `A` to strafe left while **smoothly keeping your crosshair locked on the bot's head** during movement.
  3. Release `A` and tap `D` (counter-strafe to a crisp stop under `1.62 m/s`).
  4. Fire a single, perfectly accurate 1-tap on the bot's head (confirming a pure yellow bar on your shooting error graph).
  5. Hold `D` to strafe right while keeping the crosshair glued to the skull $\rightarrow$ tap `A` to counter-strafe $\rightarrow$ fire a single 1-tap.
  6. Alternate rhythmic counter-strafes with unexpected asymmetric cadences (`A -> D -> D -> D -> A`).
* **Golden Rule:** The crosshair must **never leave the bot's head** during lateral movement. Practice this daily to automate your counter-strafe timing and head-level tracking.

### 4. Intentional Over-Flick Correction Drill (5 Minutes)
* **Objective:** Train rapid micro-correction reflexes.
* **Execution:** Intentionally flick past the bot's head by 1–2 head widths at high speed $\rightarrow$ pause for a fraction of a second $\rightarrow$ micro-correct horizontally onto the skull $\rightarrow$ fire.

### 5. Deathmatch Hygiene (15–20 Minutes)
* **Sound OFF / Low Music:** Eliminates audio crutches, forcing 100% reliance on visual angle slicing, pre-aiming, and visual reaction time.
* **Sheriff & Guardian Only:** Enforces strict headshot discipline. Missing the first shot forces you to strafe, reset, and re-aim rather than spraying.
* **Ignore the Scoreboard:** Unbind Tab. Focus purely on clean mechanical execution.

### 6. Aim Trainer Benchmarks (Voltaic Valorant)
* **Static Clicking (VT Sixshot / 1w6ts):** Trains clean primary flick speed with instant stopping power.
* **Micro-Adjustments (Microshot Precision):** Trains horizontal micro-flicks against jiggle-peeking targets.
* **Dynamic Vertical Clicking (VT Popcorn):** Trains target acquisition against vertical mobility abilities.

---

<a id="habits-matrix"></a>
## 12. Common Bad Habits vs. Pro Habits Matrix

| Mechanic | Low-to-Mid ELO Habit | Tier-1 Pro / Radiant Standard |
| :--- | :--- | :--- |
| **Traversing Space** | Lazy crosshair drift to chest/floor level while rotating. | Crosshair locked to corner geometry at head height 100% of the time. |
| **Corner Peeking** | Diagonal peeking with `W + D` or `W + A`. | Pure lateral peeking (`A` or `D` only) perpendicular to enemy sightline. |
| **Corner Clearance** | Sweeping open space in one continuous walk. | Slicing the pie in 5°–10° isolated concentric deadzone steps. |
| **Target Acquisition** | Relying on wide, reactive mouse flicks. | Aiming with movement: WASD sweeps reticle onto target; mouse handles sub-20px micro-adjustments. |
| **First Contact** | Instant panic crouch and full spray commit. | 2-shot burst standing $\rightarrow$ lateral strafe $\rightarrow$ deadzone burst. |
| **Duel Strafe Cadence** | Predictable left-right metronome bounce. | Asymmetric cadence (`A -> D -> D -> D -> A`) breaking enemy timing prediction. |
| **Strafe Amplitude** | Uniform step distances that are easy to track. | Mixing short micro-strafes (wrist) with wide slides (arm) to force enemy over-flicks. |
| **Pre-Peek Wrist Posture** | Peeking with a cocked/tilted wrist at the pad edge. | Lifting and re-centering mouse before swinging; neutral wrist with full micro-adjustment freedom. |
| **Peeking Mindset** | Passively checking angles hoping they are empty. | Proactive expectation: 100% conviction that an enemy head is waiting on your crosshair. |
| **Missed Opening Shot** | Pulling down and spraying through horizontal recoil bloom. | Disengaging, strafing 2 steps to reset recoil, and re-taking the duel. |
| **Angle Holding Depth** | Guessing between extreme tight or extreme wide. | Defaulting to Mid-Hold (~1–1.5 character widths): catches wide swings on timing; easy sub-15px flick for jiggles. |
| **Clutch / Overconfidence** | Holding standard tight/mid depths against aggressive foes. | Reading ego-swings: pushing crosshair Extra-Wide (2–3 character widths) in 1vX clutches or against hot streaks. |
| **Re-Peeking Angles** | Re-peeking from the identical physical spot. | Depth-shifting: taking 1–2 steps closer or farther from cover to break the enemy's pre-placed crosshair. |
| **Operator Response** | Dry-peeking one by one with rifles. | Jump-peek baiting the 1.5s bolt cycle, or executing simultaneous trade swings. |
| **Enemy Pattern Recognition** | Reacting blindly to noise and over-rotating on first contact. | Tracking push sequencing (A-only vs. A -> B -> A), catching habitual lurkers, and pre-stacking sites. |
| **Angle & Timing Predictability** | Peeking the same lane (e.g. Mid) at identical round timings. | Anti-conditioning: varying peek timings, playing unexpected off-angles, and relocating after every duel. |
| **Economy-Based Positioning** | Holding close angles against enemy eco saves (walking into shotguns/Shorty). | Enforcing >20m range against eco; exploiting Outlaw 140 body-shot kills on Light Shields; respecting Op on buy rounds. |
| **Micro-Adjustments** | Frantically micro-flicking with the mouse under pressure (over-flicking). | Keyboard micro-stepping: using subtle `A`/`D` taps to walk the reticle onto the head with zero overshooting. |
