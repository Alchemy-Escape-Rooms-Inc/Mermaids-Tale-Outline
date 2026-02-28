# A Mermaid's Tale — Escape Room Outline

**Room Order:** Captain's Quarters → Pirate Ship → Jungle → Ancient Ruins → Monkey Tomb → Mermaid Cove

---

## ⚓ Captain's Quarters

### Puzzle 1: Captain's Desk & Mermaid Mirror
Players locate the Captain's ornate desk and open the drawer. Inside is a mysterious scroll. Picking up the scroll releases a limit switch hidden in the drawer, triggering the Mermaid Mirror mounted nearby to change — it now displays an ethereal image of a mermaid pointing to a specific icon on the wall.

Players realize they must all simultaneously touch the icon on the wall. When done correctly, the magnetic cuffs release. The cabin door then automatically unlocks and opens on its own, granting access to the Pirate Ship area.

The scroll includes cryptic illustrations of the following icons:
- A mermaid
- A turtle
- A seahorse
- A boat (vessel)
- A trident
- A monkey
- A star constellation

Players will later use this scroll to match images to glyphs in the tomb.

**Materials:** Lockable desk drawer with limit switch, scroll prop (with symbolic iconography), wall-mounted Mermaid Mirror with rear projection or screen, symbol panel with capacitive or proximity sensor, magnetic cuffs, proximity sensors, LED indicators, Arduino controller, auto-unlocking cabin door mechanism.

---

## 🚢 Pirate Ship

### Puzzle 2: Seahorse Compass Dials
Players find three bronze compass housings embedded in the ship's walls and three uniquely sculpted seahorse medallions hidden around the room. Each seahorse matches one specific compass. A graphic on the floor indicates which direction each seahorse must be turned once inserted.

When all three are correctly aligned, the pirate wheel unlocks and Red Beard emerges.

**Materials:** Three compass housings with rotation sensors, three seahorse medallions with magnetic bases or RFID, graphic floor panel, LED feedback, Arduino controller, pirate wheel locking/unlocking mechanism.

---

### Puzzle 3: Cannon Battle
Enemy ships appear on projections. Players load cannonballs into the cannons and fire by pulling a cord. Each successful hit triggers immersive visual, audio, and smoke effects.

**Materials:** Cannon props, cannonball props, smoke machine, projection system, sound system, Arduino controller.

---

### Puzzle 4: Balance Scale
Players weigh leather spice pouches on a brass balance scale, matching spice names to barrels and placing them in the correct order based on rack weight labels.

**Materials:** Brass scale with sensors, spice pouches with weights, barrels with labels and sensors, Arduino controller.

---

### Puzzle 5: Rum Barrel Puzzle
Players locate Red Beard's secret rum recipe and identify the correct barrels, placing them in the correct grouping. Success triggers Red Beard's voice.

**Materials:** Rum barrels with pressure sensors, recipe prop, audio system, Arduino controller.

---

### Puzzle 6: Wheel Map Navigation
Players use the pirate wheel to navigate the ship's mounted map. Turning the wheel in the correct sequence lights up LEDs marking the route. Upon completion, a virtual sail unfurls and the secret sliding door opens to reveal the Jungle.

**Materials:** Wall-mounted map, pirate wheel with rotary encoder, LED system, projection system, Arduino controller, motorized sliding door.

---

## 🌿 Jungle

### NPC Introduction: Evalee
Upon entering the Jungle, players meet Evalee — a virtual archaeologist who guides them through the challenges ahead.

---

### Puzzle 7: Sundial Puzzle
Players correctly identify the numbers and objects on the sundial. Upon solving, Monkey Totem Door 1 on the double door in the Ancient Ruins lights up.

**Materials:** Sundial prop with sensors, Arduino controller, LED feedback to Ancient Ruins totem.

---

### Puzzle 8: Driftwood Assembly
Players restore a wall carving by fitting driftwood pieces into the correct positions on the shrine wall panel. Upon solving, Monkey Totem Door 2 on the double door lights up.

**Materials:** Driftwood pieces with magnets, shrine wall panel with sensors, Arduino controller, LED feedback to Ancient Ruins totem.

---

### Puzzle 9: Fountain Puzzle
Players direct water through a maze using valves and jugs, filling carved basins to the correct levels. Upon solving, Monkey Totem Door 3 on the double door lights up. All three totems lit → the double door opens to the Monkey Tomb.

**Materials:** Water-safe maze, valves, jugs, carved basins with level sensors, Arduino controller, LED feedback to Ancient Ruins totem.

---

## 🏛️ Ancient Ruins

Transition space between the Jungle and Monkey Tomb. Features one large double door with three monkey totem carvings. Each totem carving illuminates as its corresponding jungle puzzle is solved. When all three are lit, the double door opens revealing the Monkey Tomb.

No puzzle occurs here — this space serves as a visual progress tracker and gating mechanism.

---

## 🐒 Monkey Tomb

### Puzzle 10: Hieroglyphics Panel
Players use mechanical monkeys hanging in the room to solve the hieroglyphics panel puzzle. Upon correct completion, the Trident Cabinet opens. Players remove Poseidon's Trident — and the Mermaid Cove door automatically slides open.

**Materials:** Mechanical monkeys, hieroglyphics panel with touch sensors, Arduino controller, motorized/magnetic Trident Cabinet, LED-lit Trident prop, motorized Cove door.

---

## 🧜 Mermaid Cove

### Puzzle 11: Seashell Song
Players touch glowing shell panels in the correct sequence to replicate a melody. Upon completion, the Magic Mirror unlocks.

**Materials:** Touch-sensitive seashell panels, LED lights, sound system, Arduino controller, Magic Mirror unlock mechanism.

---

### Puzzle 12: Magic Mirror + Star Chart + Trident
Players use the Magic Mirror and Poseidon's Trident together to solve the star chart, aligning celestial symbols to complete a glowing constellation.

Upon completion, the virtual finale plays and the exit door opens.

**Materials:** Magic Mirror with projection, star chart panels, Trident prop with sensors, LED constellation system, Arduino controller, projection system, exit door mechanism.

---

## 🗝️ Key Prop Flow Summary

| Prop | Acquired | Used |
|------|----------|------|
| Scroll | Captain's Quarters — Desk Drawer | Monkey Tomb — Hieroglyphics reference |
| Poseidon's Trident | Monkey Tomb — Trident Cabinet | Mermaid Cove — Star Chart puzzle |
| Monkey Totem Light 1 | Jungle — Sundial Puzzle | Ancient Ruins — Double door progress |
| Monkey Totem Light 2 | Jungle — Driftwood Puzzle | Ancient Ruins — Double door progress |
| Monkey Totem Light 3 | Jungle — Fountain Puzzle | Ancient Ruins — Double door opens |

---

## 🚪 Door & Transition Summary

| Transition | Trigger |
|-----------|---------|
| Cabin Door → Pirate Ship | All players simultaneously touch wall icon → cuffs release |
| Pirate Ship → Jungle | Wheel Map Navigation complete → virtual sail unfurls → sliding door opens |
| Jungle → Ancient Ruins | Open passageway — no lock |
| Ancient Ruins → Monkey Tomb | All three totem carvings lit → double door opens |
| Monkey Tomb → Mermaid Cove | Trident removed from cabinet → Cove door slides open |
| Mermaid Cove → Exit | Star Chart + Trident + Mirror complete → virtual finale → exit door opens |
