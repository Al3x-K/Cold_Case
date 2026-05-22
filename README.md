# Cold_Case

Overview

The player wakes up on the floor of a private detective’s office sometime late at night. The office door is locked from the outside, the space is a mess, and someone tore through important documents. The player takes the role of the detective, investigating the aftermath while trapped inside the space. Cold Case is a first-person escape room set in a 1940s noir-inspired detective office. The experience is built around environmental storytelling and close observation rather than combat or action. The central mechanic is a magnifying glass that reveals hidden evidence throughout the room as well as flavor objects. The player reconstructs what happened by carefully examining the environment. 

The atmosphere draws inspiration from classic noir fiction and film. Warm desk lamps and deep shadows create a high-contrast visual style influenced by films such as The Big Sleep and Chinatown. Rain outside the office window, distant thunder, ticking clocks, and creaking floorboards reinforce the sense of isolation and tension.

Narrative structure:
Confusion — The player regains consciousness in the detective’s office with no explanation. The office has clearly been disturbed, and the exit door is locked.
Investigation — Using the magnifying glass, the player examines clues hidden throughout the environment. An interaction with a sequence of objects reveals a locked drawer that holds a key to the door.
Resolution — The player unlocks the drawer, retrieves the office key, and opens the exit door. A final cinematic moment reveals the dark hallway outside, confirming the player’s escape.

How to Play

  1. Open the project in Unreal Engine 5 and run Lvl_FirstPerson.
  2. Use WASD to move and the mouse to look around.
  3. Press E to interact with objects in range.
  4. Pick up the magnifying glass from the desk.
  5. Use the magnifying glass to inspect clues hidden around the office - toggle it on Q.
  6. Examine all clues around the office to reveal the unlock the drawer.
  7. Interact with the locked drawer and open it - only after using the recorder.
  8. Retrieve the key from the drawer.
  9. Unlock the office door and escape.

Stage 1 Reflection

The original Stage 1 proposal was significantly different from the final project. The first concept was set in an industrial warehouse where the player controlled a late-shift worker trapped during a power outage. The warehouse doors automatically locked after the generator failed, and the player needed to restore power to escape.

The original puzzle structure focused on restarting the warehouse generator through a three-step maintenance process. The player first needed to activate the fuel valve, then locate and flip the correct circuit breaker elsewhere in the warehouse, and finally use the ignition panel to restart the generator. A maintenance manual acted as the primary clue source and explained the correct startup sequence.

The warehouse concept strongly emphasised industrial atmosphere and environmental storytelling. Emergency red lighting created long shadows across the space while Niagara effects such as dust particles, sparks, steam, and exhaust smoke reinforced the abandoned industrial setting. The original plan also included a cinematic sequence where the warehouse lights flickered back on and the exit sign illuminated after the generator successfully restarted.

Large amounts of environmental dressing were planned for the warehouse version, including safety posters, forklift tyre marks, oil stains, caution tape, warning signage, water damage, scattered paperwork, and industrial decals. A custom Substrate material was also designed for the generator itself, featuring rust, chipped paint, oil streaking, and worn industrial metal.

During development, the project changed direction completely from industrial horror-inspired escape room to noir detective mystery. While the warehouse concept provided a strong environmental foundation, the detective office setting allowed for more focused storytelling and a puzzle structure more closely tied to investigation and observation.

The final project retained several important ideas from the original concept despite the setting change. Environmental storytelling remained central to the experience, with props and room dressing used to imply events without explicit exposition. The emphasis on atmosphere, lighting, ambient sound, and cinematic presentation also carried across into the final version.

The puzzle structure evolved substantially during development. Instead of a maintenance sequence involving machinery, the final experience became a narrative investigation built around discovering hidden evidence. The completed gameplay flow is structured as follows:
| Step | Object               | Purpose                                                   |
| ---- | -------------------- | --------------------------------------------------------- |
| 1    | Crumpled paper       | Points the player toward the file cabinet below the map   |
| 2    | File cabinet         | Magnifying glass reveals the hidden investigation report  |
| 3    | Investigation report | Directs the player toward the cassette tape               |
| 4    | Cassette tape        | Establishes the need to locate a cassette player          |
| 5    | Cassette player      | Found glowing inside a cabinet drawer                     |
| 6    | Audio recording      | Reveals the location of the office keys                   |
| 7    | Cabinet drawer       | Contains the office keys                                  |
| 8    | Office door          | Final escape point                                        |

The magnifying glass mechanic became the defining feature of the final project. A post-process material was developed to create a circular viewing area aligned with the lens of the magnifying glass. While active, the visible area through the glass desaturates the environment and allows hidden clues to glow green. Without the magnifying glass equipped, these clues remain invisible. This system transformed the act of observation into the core gameplay interaction and reinforced the detective theme directly through mechanics.

Audio design also became more focused. The final game uses layered ambient sound including night street ambience outside the office, low room tone ambience, electrical light buzzing, footsteps, and interaction sounds. The intention was to create a believable and grounded soundscape where every sound has a clear physical source within the environment.

The UI design was intentionally kept minimal. The final implementation includes simple interaction prompts alongside examination widgets displaying the title and description of interactive objects. This approach supported immersion while still providing enough information for players to follow the investigation.

References
- The Big Sleep (1946) Directed by Howard Hawks. United States: Warner Bros.
- Chinatown (1974) Directed by Roman Polanski. United States: Paramount Pictures.
- L.A. Confidential (1997) Directed by Curtis Hanson. United States: Warner Bros.
- L.A. Noire (2011) Developed by Team Bondi. Published by Rockstar Games.
- Firewatch (2016) Developed by Campo Santo. Published by Panic.
- Epic Games (2024) First Person Template [Unreal Engine built-in template]. Unreal Engine 5. Available through Unreal Engine.
- Detective Office Environment Pack (2026) Fab asset pack. Accessed May 2026.
- PC Keyboard & Mouse Icon Pack (UI Icons, Input Icons, Keyboard, Mouse, UI Pack) (2026) Fab asset pack. Accessed May 2026.
