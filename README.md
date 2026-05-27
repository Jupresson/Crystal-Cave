# Crystal Cave
A solo-developed **2D precision platformer** built in Godot 4.3, focused on tight movement mechanics, state machine architecture, and handcrafted pixel art.

<table><tr>
<td>
<table>
  <tr><td><b>Genre</b></td><td>2D Platformer</td></tr>
  <tr><td><b>Engine</b></td><td>Godot 4.3</td></tr>
  <tr><td><b>Language</b></td><td>GDScript</td></tr>
  <tr><td><b>Timeline</b></td><td>X X, 2025 – Apr 15, 2025</td></tr>
  <tr><td><b>Status</b></td><td>Demo · Solo</td></tr>
  <tr><td><b>Role</b></td><td>Designer, Developer & Artist</td></tr>
  <tr><td><b>Art Tool</b></td><td>Pyxel Edit</td></tr>
</table>
</td>
<td align="right">
  <img src="https://jupresson.github.io/ProjectCrystalCaveImageSmall.webp" width="500" alt="Crystal Cave"><br/>
  <a href="https://jupresson.github.io/ProjectCrystalCavePage/">More info →</a>
</td>
</tr></table>

---

## Technical Highlights

**Architecture**
- Script-based state machine for the player, cleanly separating movement states, animations, and transitions.
- Component-structured player script refactored from a monolithic approach after hitting maintainability limits.

**Gameplay**
- Full movement suite: walk, run, dash, jump, wall jump, and double jump — with double jump resetting on wall contact to enable chained wall climbing.
- Crystal pickups scattered in hard-to-reach areas reward mastery of the movement system by healing the player.
- Simple enemy AI that reverses direction on wall collision and deals contact damage to the player.

**Art Pipeline**
- Pixel art created in Pyxel Edit with a fixed tile size and a constrained color palette to keep visual direction consistent throughout solo development.

---

## Known Issues
- Messy one script state machine (need refactoring)
- Game dosent have tutorial to teach player mecanics
