# ARCFALL 1.7 — A battle of spellbooks

**Twenty-one spells and eight spellbook presets.** Venom Orb adds delayed damage
that Ward blocks and Mend cleanses. Stone Wall creates destructible cover with
open flanks and open sky. Both have original Blender models and textures in the
existing art style. The wizard's hat now sits slightly lower against the head.

Fire Ball is optional. Alchemist, Warden and Stormcaller join the original five
presets with their own tools; everyone retains Blink and free Staff Spark. An
eight-player preset battle gives each opponent a different book. Fire Ball makes
a smaller crater, while Ward, Imp, Briar and Gale are cheaper to cast.

The AI evaluates threats, firing lanes, book strengths, terrain support, incoming
knockback and spells it can afford over the next two turns. It can bank mana,
counter infection, protect itself, use summons and seek a safe firing position
when trapped. It uses the same spell costs, unlocks and placement rules as players.

**Learn to cast** teaches movement, angle and power through actual actions.
F2 hides or replays the optional guide. Holding and releasing the mouse still
requires judging the shot; no predicted landing point is shown. The movement
bar reports the remaining distance in metres.

Eliminated players can watch, start another battle or return to shore immediately.
A wizard dying during its own movement now correctly finishes that seat's turn.
**O** doubles AI observation speed while preserving the simulation step; human
movement and casting stay at normal speed. **Continue battle** restores the
current match after returning to the menu, during the same application session.

Settings separate Controls, Audio and Display, with alternate two-click casting,
interface scale, lower effects, reduced motion, frame caps and fullscreen (F11).
Windows includes **Play-DirectX12.cmd** as an alternative to the default Vulkan
renderer. Menus support keyboard focus and small-window scrolling.

The final four eight-player AI matches completed with 436 accepted casts across
16 spell types, no rejected AI casts and no deaths during a wizard's own movement.
Fire Ball was 35% of primary casts, down from 63% in the first development cohort.
These are observations from a small sample, not a competitive book ranking.
Focused regression checks cover AI tactics, real spell effects, input, turn flow,
onboarding and playback. Native Windows play and Vulkan/DirectX 12 rendering
were reviewed on an RTX 3060 Ti.

Available modes are AI duels, four/eight-player free-for-all against AI,
two-player local hotseat and practice. This release has no online matchmaking
or disk saves for battles. [Download and controls](README.md).
