# Valorant Pro Quick-Reference Cheat Sheet

> 📖 **Master Manual:** For full mathematical calculations, biomechanics, and map geometry diagrams, read **[VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md)**.  
> 🎯 **Crosshair Compendium:** For visual previews, parameter breakdowns, and copy-paste codes, read **[CROSSHAIRS.md](CROSSHAIRS.md)**.

---

## Table of Contents
* [🚨 Emergency Whiff & Tilt Triage (10-Second Reset)](#emergency-triage)
* [🏃 Movement & Deadzoning Cues](#movement-deadzoning-cues)
* [👀 Peeking Catalog Cues](#peeking-catalog-cues)
* [🎯 Aim, Crosshair Placement & Weapon Cues](#aim-crosshair-cues)
* [🛑 Crouching Rules](#crouching-rules)
* [⚔️ Beast's Double Edge Crosshair Quick Select](#crosshair-quick-select)
* [⚙️ Settings & Hardware Diagnostics](#settings-diagnostics)
* [⏱️ Daily Warmup Routine Quick-Check](#daily-warmup-check)

---

<a id="emergency-triage"></a>
## 🚨 Emergency Whiff & Tilt Triage (10-Second Reset)
* **Shooting Error Graph showing Blue bars?** $\rightarrow$ You are clicking before decelerating below `1.62 m/s`. Delay trigger pull by ~50 ms after key release. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#inaccuracy-graph-verification)]
* **Over-flicking or jittery micro-aim?** $\rightarrow$ Loosen mouse grip tension to ~3/10 pressure. Clenched hands lock carpal tendons. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#micro-adjustments-biomechanics)]
* **Stiff wrist when peeking angles?** $\rightarrow$ Lift and re-center mouse on the pad before swinging. A cocked wrist has zero micro-adjustment range. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#pre-peek-wrist-reset)]
* **Flinching / whiffing opening shots?** $\rightarrow$ Visually confirm the enemy head before pulling the trigger. Never shoot on reaction to raw movement or silhouettes. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#anticipation-vs-passive)]
* **Spraying and losing duels?** $\rightarrow$ Enforce the 2-bullet cutoff. If bullets 1–2 miss, strafe 2 paces laterally (375 ms recoil reset) and fire a fresh burst. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#recoil-synchronization)]
* **Panic crouching into deaths?** $\rightarrow$ Lift your pinky off `Ctrl` or unbind crouch for 3 rounds. Low-ELO opponents aim chest-level; crouching walks your head into their bullets. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]

---

<a id="movement-deadzoning-cues"></a>
## 🏃 Movement & Deadzoning Cues
* **Never hold `W` into an angle:** Always peek with pure `A` or `D`. Forward movement flattens lateral speed on the enemy screen, making you trivial to track. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#diagonal-penalty)]
* **Peek from Maximum Distance from Wall:** Always back up as far as terrain allows before swinging. Distance grants **Perspective Advantage** (you see their body first) and ensures **Peeker's Advantage (30–50 ms)** is not destroyed by premature shoulder exposure. Hugging corners gives the enemy free vision. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#perspective-advantage)]
* **Shift-walk vs. Crouch-walk:**
  * *Shift-walking (`3.0 m/s`):* Incurs full movement inaccuracy bloom. Never shoot while Shift-walking. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#velocity-threshold)]
  * *Crouch-walking (`1.5 m/s`):* Drops below the 1.62 m/s threshold $\rightarrow$ **100% standing accuracy** while moving. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#velocity-threshold)]
* **Ropes & Ascenders:** Cancel horizontal momentum $\rightarrow$ hold `Shift` + press `F` to latch silently. Never duel on ropes (rifles = 1.3 base spread; shotguns = 3.0 running spread). Press `Space` at top for bhop entry. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#rope-discipline)]
* **Reversal Deadzone:** Moving `A` $\rightarrow$ release `A` and tap `D` $\rightarrow$ fire 1–2 bullets at the apex transition $\rightarrow$ continue moving `D`. Never freeze stationary. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#reversal-deadzoning)]
* **Stutter Deadzone (Same-Direction):** Sprinting `D` $\rightarrow$ tap `A` for 30–50 ms as a brake $\rightarrow$ fire 1–2 bullets $\rightarrow$ resume `D`. Enables unexpected `D -> D -> D` chains. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#stutter-deadzoning)]
* **Anti-Metronome Cadence:** Never oscillate in a predictable left-right bounce. Double-tap in the same direction (`A -> D -> D -> D -> A`) and alternate short micro-strafes (wrist) with wide slides (arm). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#anti-metronome-strafing)]
* **Silent Box Mount:** Walk forward into crate + hold `Ctrl` $\rightarrow$ press `Space` $\rightarrow$ release `Ctrl` at jump apex (zero landing noise). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#silent-box-mount)]
* **Silent Ledge Drop & Wall Drag:** Tap `Ctrl` right before sliding off ledges (~35–40 cm drop reduction); scrape against angled walls or crates during falls to drag downward speed below audio triggers. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#silent-edge-drops)]

---

<a id="peeking-catalog-cues"></a>
## 👀 Peeking Catalog Cues
* **Defensive Distance & Camera Alignment:** Never hug corners when holding. The first-person camera is centered between the eyes, so hugging geometry exposes your outer shoulder and gun barrel to wide swingers before you gain vision. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#perspective-advantage)]
* **Diagonal Penalty (`W+D` / `W+A`):** Approaching corners diagonally collapses lateral angular speed across the defender's screen, making your model nearly stationary to track. Always approach perpendicular and swing pure `A`/`D`. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#diagonal-penalty)]
* **Slicing the Pie with Through-Wall Pre-Aim:** Clear 5°–10° concentric wedges from max distance. Pre-align crosshair through the wall onto the head coordinate *before* stepping out. When line of sight opens, your crosshair is already on their head so you don't adjust aim, you just click. Keep outer geometry masking secondary angles to isolate duels into sequential 1v1s. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#slicing-the-pie)]
* **Shoulder Peek (<0.22s):** Look 45°–90° into the adjacent wall $\rightarrow$ tap `A`/`D` for 40–70 ms $\rightarrow$ snap back. Exposes only the outer arm hitbox with zero footstep audio; baits sniper shots. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#shoulder-peek)]
* **Pre-Fire Jiggle:** Pre-aim head coordinate through wall $\rightarrow$ micro-strafe out $\rightarrow$ 1–2 shot apex burst $\rightarrow$ snap into cover. Never use identical timing twice. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#prefire-jiggle)]
* **Jump Peek (Parabolic S-Curve):** Knife out (`6.75 m/s`) $\rightarrow$ run parallel with `W` $\rightarrow$ jump and swing `D` $\rightarrow$ whip back with `S + A` to land behind cover with zero landing audio. Baits the Operator's 1.50s bolt rechamber. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#jump-peek)]
* **Ferrari Swing:** Pure `A` or `D` at 5.40 m/s perpendicular to enemy sightline. Maximizes peeker's advantage (30–50 ms client-server lead). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#swing-variations)]
* **Wide Swing:** Sprint 1.5–2 character widths past the standard pre-aim point into open space. Punishes defenders holding tight crosshairs. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#swing-variations)]
* **Poppin Swing:** Wide running swing $\rightarrow$ sudden crouch commit. Breaks enemy aim across both horizontal tracking and vertical recoil axes. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#swing-variations)]
* **Depth-Shift & Compound 2-Axis Re-Peek:** Never re-peek from the exact same physical coordinates. Step 1–2 paces closer or farther behind cover (stepping back widens angle; stepping closer spikes angular speed) AND drop into a crouch to break both horizontal and vertical pre-aim simultaneously. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#depth-shifting)]
* **Anti-Conditioning & Off-Angle Unpredictability:** Never peek the same lane at the same round timer twice (e.g. repeated Mid peeks invite pre-fires and double-peeks). Play unexpected off-angles in open space to break enemy pre-aim, and relocate immediately after securing a duel. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#enemy-pattern-recognition)]

---

<a id="aim-crosshair-cues"></a>
## 🎯 Aim, Crosshair Placement & Weapon Cues
* **Traversing Space Discipline:** Never allow crosshair to sag to chest/floor level during rotations; keep reticle locked to corner geometry at head height 100% of the time, anticipating instant contact. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crosshair-placement)]
* **Distance Ladder:**
  * *0–10m:* 2-bullet burst into crouch pull-down (Vandal) or full spray commit (Phantom). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#gunfight-hygiene)]
  * *10–25m:* Strict 2-bullet burst $\rightarrow$ 2-step strafe $\rightarrow$ deadzone burst. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#gunfight-hygiene)]
  * *25m+:* 2-bullet burst or deadzone 1-tap only. Zero spraying. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#gunfight-hygiene)]
* **Recoil Cooldown Sync:** Vandal reset = 375 ms; Phantom reset = 350 ms. A standard 2-step lateral strafe takes ~375 ms, naturally absorbing the weapon cooldown. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#recoil-synchronization)]
* **4-Bullet Cutoff:** Vandal bullets 5+ have randomized horizontal spread. If the first 3 bullets miss, disengage and strafe. Continuing to spray has a <10% hit rate. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#spray-commit-rules)]
* **Weapon Nuances:**
  * *Sheriff & Guardian:* Lethal 1-tap at deadzone apex; enforce single-shot recoil reset before firing again.
  * *Phantom vs. Vandal:* Phantom allows 5–6 round sprays out to <15m; suppressed barrel emits **zero bullet tracers**, allowing safe smoke spamming. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#spray-commit-rules)]
* **4-Step WASD Aim Sequence (Zero-Adjustment Shooting):** (1) Pre-aim through wall $\rightarrow$ (2) Sweep angle with pure `A`/`D` (mouse neutral) $\rightarrow$ (3) Micro-step `A`/`D` onto skull if off by 10–30px $\rightarrow$ (4) Apex counter-tap & fire. Axiom: *Never flick to an angle you can step into.* [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#wasd-aiming)]
* **Under-Aiming (85%–90% Flick):** Flick slightly short, then micro-snap forward. Over-flicking forces antagonistic muscles to brake and reverse, costing 100–150 ms. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#under-aiming)]
* **Keyboard Micro-Adjustments (Anti-Overflick):** When an enemy is slightly off your reticle (10–30px), **micro-adjust with `A`/`D` instead of flicking with the mouse**. Mouse micro-flicks under adrenaline cause over-flicking and muscle tremor; tapping your movement key walks your crosshair onto their skull with 100% digital precision. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#keyboard-micro-adjustments)]
* **The "Wallhack Mindset" (100% Anticipation):** Expect an enemy head at the exact millimeter of every corner; anticipating the target drops reaction time from ~250 ms to ~160 ms and eliminates startle flinches. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#anticipation-vs-passive)]
* **Angle Holding Depth:**
  * *Default Mid-Hold (60–120px / ~1–1.5 character widths):* **Universal Pro Default.** Catches wide swings on reaction timing; requires only a sub-15px wrist flick for jiggles. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#holding-depth)]
  * *Tight Hold (<40px):* Operator/Marshal or confirmed shift-walkers only. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#holding-depth)]
  * *Extra-Wide Hold (150–250px / 2–3 character widths):* High mobility agents (Neon, Jett), anti-eco rounds, or reading **ego-swings** (1vX clutches, enemies on hot streaks). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#holding-depth)]
* **Map Geometry Rulers:** Top edge of single Radianite crate, seam between stacked crates, and horizontal wall trim / architectural decals = head height. Align with teammate heads during buy phase. On **ramps and inclines**, pre-aim the exact lip where the head first breaches rather than holding parallel to the slope. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#map-rulers)]
* **Enemy Pattern Recognition (Exploiting Habits):**
  * *Push Sequencing:* Track if the enemy spams one site or alternates predictably (`A -> B -> A`). Pre-rotate or stack crossfires early against predictable sequences. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#enemy-pattern-recognition)]
  * *The Dedicated Lurker:* If an enemy consistently lurks late, **never rotate on first contact**. Leave a "lurk-catcher" holding the flank off-angle, or collapse on and hunt the isolated lurker early for a free 5v4 man advantage. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#enemy-pattern-recognition)]
  * *Pacing & Cadence Exploitation:* Against Fast-Rush teams, hold Extra-Wide (150–250px), delay with stall utility, and refuse close 50/50s. Against Slow-Default teams, hold standard Mid-Holds, hoard defensive utility until 0:40, and punish predictable late-round executes. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#enemy-pattern-recognition)]
* **Economy Reads & Weapon Matchups:**
  * *Enemy Eco / Save (Low Money):* **Never hold close angles (<10m).** Back up to long ranges (>20m) to neutralize cheap shotguns (Judge/Shorty) and Classic right-clicks. Exploit **Outlaw (140 body damage)** for instant 1-shot torso kills against Light Shields (125 HP). Hold Extra-Wide for swarming pistol rushes. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#enemy-pattern-recognition)]
  * *Enemy Rich / Surplus (4,700+ Credits):* **Never dry-peek long sightlines with rifles.** Assume an Operator is holding. Enforce Jump Peeks to bait the 1.50s bolt rechamber, flush with flashes/smokes, or coordinate simultaneous trade-swings. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#enemy-pattern-recognition)]

---

<a id="crouching-rules"></a>
## 🛑 Crouching Rules
* ❌ **NEVER crouch on bullet 1:** Low-ELO opponents aim at chest level; crouching pulls your head directly into their crosshair. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]
* ❌ **NEVER crouch at >20m:** Freezes you in open space with zero cover access. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]
* ❌ **NEVER crouch against multiple foes or in open space without cover:** Eliminates retreat mobility and guarantees an immediate trade; maintain lateral mobility (`A`/`D`) to isolate duels into separate 1v1s. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]
* ✅ **ONLY crouch on bullets 3–4 (<10m):** Close-range committed spray to absorb recoil. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]
* ✅ **Radiant Head-Dodge:** Crouch on bullet 2–3 against Tier-1 opponents to duck under their opening headshot burst. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]
* ✅ **Poppin / Compound Swing Lock:** Commit crouch during wide lateral momentum to disrupt enemy horizontal tracking and vertical crosshair pre-aim simultaneously. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#crouching-rules)]

---

<a id="crosshair-quick-select"></a>
## ⚔️ Beast's Double Edge Crosshair Quick Select

The **Double Edge** reticle system delivers the best of both worlds: a clean, high-precision center focal point for 1-taps combined with semi-transparent outer bars providing an instant leveling horizon for spray containment.

> 🧠 **Design Mechanics:** Understand how human foveal vision and peripheral recoil containment interact in **[The Dual-Focal Architecture Guide](CROSSHAIRS.md#dual-focal-architecture)**.

### 1. Beast's Double Edge (V1 — Cyan Micro-Cross)
* **Visual Style:** Micro-cross 4-tick center box (`1-3-1-1`) + compact outer recoil cage (`1-4-12 @ 0.69`).
* **Tactical Focus:** Aggressive rifling, Phantom spray transfers, rapid burst-strafe resets.
* **Import Code:**
  ```text
  0;p;0;s;1;P;c;5;u;2AFF00FF;h;0;f;0;0t;1;0l;3;0v;3;0g;1;0o;1;0a;1;0f;0;1t;1;1l;4;1v;4;1o;12;1a;0.69;1m;0;1f;0;A;o;1;d;1;0b;0;1b;0;S;s;1.373
  ```
👉 **[View Screenshot Preview & Full Parameter Breakdown ↗](CROSSHAIRS.md#beasts-double-edge-v1-cyan)**

### 2. Beast's Double Edge 2 (V2 — Red Dot Bracket)
* **Visual Style:** Solid punchy center bead (`d;1` + `4-1-0-1`) + wide ghosted peripheral bracket (`1-6-16 @ 0.52`).
* **Tactical Focus:** Vandal opening 1-taps, Guardian/Sheriff clicking, long-range pixel peeks.
* **Import Code:**
  ```text
  0;p;0;s;1;P;c;7;u;2AFF00FF;h;0;d;1;z;1;f;0;0t;4;0l;1;0v;1;0g;1;0o;0;0a;1;0f;0;1l;6;1v;6;1o;16;1a;0.52;1m;0;1f;0;A;c;7;o;0;0t;4;0l;1;0v;1;0o;0;0a;1;0f;0;1b;0;S;s;1.34;o;1
  ```
👉 **[View Screenshot Preview & Full Parameter Breakdown ↗](CROSSHAIRS.md#beasts-double-edge-v2-red)**

---

<a id="settings-diagnostics"></a>
## ⚙️ Settings & Hardware Diagnostics
* **Shooting Error Graph $\rightarrow$ "Text & Graph":** Yellow = accurate deadzone. Blue = movement error penalty. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#inaccuracy-graph-verification)]
* **Auto-Equip Prioritizes: Strongest & Don't Auto-Equip Melee: ON:** Prevents pulling knife after spike plants, defuses, weapon drops, or utility. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#critical-in-game-settings)]
* **Raw Input Buffer: ON:** Feeds mouse packets directly into engine ticks, bypassing Windows latency. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#critical-in-game-settings)]
* **NVIDIA Reflex: On + Boost:** Prevents GPU power-state downclocking inside smokes and utility. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#critical-in-game-settings)]
* **Sensitivity Baseline:** 200–260 eDPI sweet spot. Values >320 eDPI introduce micro-jitter under adrenaline. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#sensitivity-tiers)]
* **Mouse DPI (1600 DPI):** Reduces sensor reporting latency by ~1.0–1.5 ms over 400 DPI without firmware smoothing. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#hardware-settings)]
* **Magnetic Keyboard Profile:** Actuation **0.2 mm** (`WASD` & `Ctrl`), Continuous Rapid Trigger **0.1 mm** (0.1 mm deadzone), Snap Tap / SOCD enabled strictly on **`A` & `D`** (last-input priority for instant lateral direction-swap deadzones). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#magnetic-keyboard-profile)]
* **Enable HRTF: ON:** Generates 3D binaural spatial audio for precise vertical and front/back footstep localization (disable Windows virtual surround sound). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#critical-in-game-settings)]

---

<a id="daily-warmup-check"></a>
## ⏱️ Daily Warmup Routine Quick-Check
* **Decoupled Tracking (The Range: 5 min):** Sheriff equipped, track bot heads while continuously strafing, counter-strafing, and crouching without firing. Decouples aim tracking from panic trigger pulling. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#warmup-regimen)]
* **Eliminate 50/100 Bots (Deadzone Rhythm: 10 min):** Continuous `Strafe -> Deadzone -> 1-Tap -> Strafe` (Armor ON). Target >90% headshot accuracy with zero blue bars on the shooting error graph. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#warmup-regimen)]
* **20m Target Dummy Counter-Strafe Drill (5–10 min):** Head outside behind the main hall (overlooking the flying sky drones) to the Accuracy Target board. Select **20m** and spawn the **Target Dummy**. Continuously strafe `A`/`D` while keeping crosshair locked on the bot's head, counter-strafing to dead stops and firing 1-taps. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#warmup-regimen)]
* **Intentional Over-Flick Drill (5 min):** Intentionally flick 1–2 head widths past bot skulls at high speed $\rightarrow$ micro-pause $\rightarrow$ micro-correct horizontally onto skull $\rightarrow$ fire. Automates subconscious recovery reflexes. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#warmup-regimen)]
* **Deathmatch Hygiene (15 min):** Sound OFF or low music, Sheriff/Guardian only, Tab key unbound. Eliminates audio crutches and reinforces pure visual angle-slicing and pre-aim discipline. [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#warmup-regimen)]
* **Aim Trainer Benchmarks (Voltaic Routine):** Static clicking (*VT Sixshot / 1w6ts*) for stopping power; Micro-adjustments (*Microshot Precision*) for jiggle duels; Dynamic vertical (*VT Popcorn*) for aerial mobility targets (Jett/Raze). [[Deep Dive ↗](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md#warmup-regimen)]

---

[📖 Read Comprehensive Movement & Aim Guide ➡️](VALORANT_PRO_MOVEMENT_AND_AIM_GUIDE.md) | [🎯 View Beast's Crosshair Compendium ➡️](CROSSHAIRS.md)
