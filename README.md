# ARCFALL

**Judge the arc. Break the ground. Be the last wizard standing.**

A first-person, turn-based wizard artillery game. Prepare eight spells under a
20-point budget, bank mana for a devastating ritual, and turn your opponent's
cover into a crater. Water is deadly. Position matters as much as damage.

![Eight-player battle on Grand Reach after the first round](images/battle.png)

## Download and play

**[Download ARCFALL for Windows x64](https://github.com/rooster4166/Arcfall-Play/releases/latest)**

1. Download the Windows ZIP and extract the entire folder.
2. Open **Arcfall.exe**. Keep the terrain DLL and other files beside it.
3. Choose **Learn to cast**, then try a duel against AI.

No Godot or Blender installation is needed. Requires Windows x64, a keyboard and
mouse, and a graphics card supporting Vulkan or DirectX 12. If the default
Vulkan launch has a graphics problem, close it and try **Play-DirectX12.cmd**.
The build is unsigned. Tested on an RTX 3060 Ti; this is not a measured minimum
hardware specification.

## Choose your battle

- AI duels and four/eight-player free-for-all against AI.
- Two-player hotseat on one computer.
- Guided practice and a sandbox with all twenty-one spells.
- Three destructible arenas, original 3D artwork, towers, imps and late-game
  rituals with time for opponents to respond.

This is a **local game**. There is no online matchmaking. Returning to the menu
keeps your current battle available until you begin another or close the game;
battles are not saved to disk.

![Tidal Reckoning crossing the island](images/tide.png)

## Your first spell

**WASD** moves; the movement bar shows how many metres remain. **Space** hops.
Hold **left mouse**, adjust your angle, and release to cast. **Right mouse**
cancels. Power controls travel, not damage. **E** switches between moving and
aiming; **V** switches the aiming camera. The game shows the real flight after
release, so use the result to judge your next shot.

**Tab** opens spellbooks. **F2** shows/hides the guide. **Esc** opens settings,
**F11** switches fullscreen, and **O** changes the speed of watching AI turns.
Settings includes optional two-click casting, lower effects and interface scale.

**K** selects Venom Orb: delayed pressure that wards block and Mend cleanses.
**L** selects Stone Wall: destructible cover with open flanks. Eight spellbook
presets support artillery, scouting, siege, poison, control and defensive play.
Opponents evaluate those tools, the terrain and future mana when choosing a turn.
Fire Ball is optional; the Alchemist, Warden and Stormcaller presets use other
tools. Every book retains Blink and the free Staff Spark.

![Stone Wall creates a new defensive position](images/wall.png)

![Alchemist's first Staff Spark: follow the real projectile and learn from its flight](images/learn.png)

*The first-cast and eight-player screenshots were captured from the standalone
1.7 Windows game using keyboard and mouse. The Tidal Reckoning image shows the
same ritual from its original 1.4 release.*

## Feedback

[Report a problem or share feedback](https://github.com/rooster4166/Arcfall-Play/issues).
For a bug, include the game version, battle size, what happened, and steps to
reproduce it. A screenshot or the relevant lines from
`%APPDATA%/Godot/app_userdata/ARCFALL/logs/godot.log` can help.
Check logs before posting and omit personal information.

[Release notes](CHANGELOG.md) describe the current version; credits and
third-party licenses are included in the ZIP. This repository contains
player-facing release information and downloadable builds.
