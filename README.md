this is a patch for the Chosen Red game, distribution of FireRed Rom is offensive to Nintendo and will get taken down so you can apply this patch to a "Legally" acquired
clean ROM of Pokemon FireRed.  Use the online patcher: https://www.marcrobledo.com/RomPatcher.js/

POKEMON: CHOSEN RED
A narrative-focused romhack where Pokémon feel like characters and the player is chosen, not given power.

NOTE: THIS IS A PET PROJECT OF MINE WHICH I DECIDED TO FULLY DOCUMENT IN CASE ANYONE ELSE WANTED TO USE MY WORK AS A BASE.
      YOU CAN USE MY STUFF BUT BE SURE TO CREDIT ME :) PLAY COOL NO HATE ALL LOVE

Flags used by me:

charmander stalking: 0x0022
berry man easteregg: 0x0023
pikachu interacted route 1: 0x0024
pikachu hidden lab: 0x0025
pokeball received by rival: 0x0026
charmander received: 0x0027
bulbasaur received: 0x0028
squirtle received: 0x002A
thunderbadge: 0x002E
ss anne sailed: 0x0237
bulbasaur stalking: 0x0055
bulbasaur runaway: 0x0060
squirtle stalking: 0x0061
Squirtle runaway: 0x0071
vermillion aura sense: 0x0078
mewtwo stalk: 0x0073
Flags used by Radical Red:
Undocumented (easy to reverse engineer with enough intuition. trust me I had to do it)

Flags used by CFRU:
stop wild encounters: 0x0911 (set = no encounters, clear = encounters)
Check CFRU GitHub (Fully documented)

NOTE: HexManiac has an option to get a random unused flag. Use it while modding to avoid collision.

Changes made:
I made the starter story and some other parts similar to Pokémon Yellow. It's not 100% faithful but it is a cool adaptation.
Story rich, Dynamic Pokémon make the world feel alive and the protagonist feel special.

Gameplay Features:
-Combat mechanics of Radical Red
-Mega Evolution available for Kanto Starters
-Pikachu as starter, rival gets eevee as always
-Increased immersion, find out yourself (no spoilers)
-Appropriate flow
-All 3 kanto starters incorporated with the world itself, like co travellers.
-Red's original team easily assembled, emotionally irreplaceable Mons
-Legendary mon teasers

Technical Features:

a documented, stable, system-driven game built on a constrained engine

-Compact, reused pointers wherever possible, well documented flags, patch provided,users can acquire legal ROM and patch it.
-Made sure that nothing is breakable, every single possible point of failure has a soft fail safe that redirects players 
but doesn't break immersion, makes sure the redirection is convincing story-wise.
-I learned flag safety, low level editing, intuitive reverse engineering, pointer reallocation, engine diversion

Fun Facts:
-Made during my second semester Finals in VIT.
-Was looking for the perfect story ROM with good competitive PvP features but can't find one which had both so I decided to make the best of both worlds.
-My very first romhack, proud.
-I learned to not fight the engine to fit my story in, but rather redirect it.
-The engine constraints of this legacy and not very modification friendly technology forced me to come up with creative and intuitive solutions, it taught me to adapt under stress
 and bend the system without breaking it.

Rom Hack Based on:
Radical Red which is based on Complete FireRed Upgrade [CFRU] which is based on FireRed v1.0 USA
Kudos to the wonderful teams behind Radical Red, CFRU and Gamefreak
Romhack made by: Abinivesh AKA clutchyred

changelog:
NOTE: I DIDNT RELEASE VERSION WISE BUT RATHER WORKED ON IT ON A DAILY BASIS, SO HERE'S A DAILY CHANGELOG

Day 1: (7/04/2026)
  Removed the Radical red region selection menu when talking to protagonist's mom.
  Experimented and learned how to show/ hide and move sprites
  Learned trigger tiles
Day 2: (8/04/2026)
  Started from scratch bcos didn't Backup and accidentally broke stuff
  Learned to create backup of working clean stages through the hard way
  Started to understand the legacy Poke ball system and decode the flags.
     - The base I worked on is a Decompilation of a game ROM so the flags are not like RecievedStarter = True its rather like 0x09A1, which I had to map each flags function by tracing it 
       through various sections
Day 3: (9/04/2026)
  Implemented my own starter system, edited and refined the conversation scripts to align with the current story modifications and installed failsafes for situations which may soft lock or break the game
  Implemented Charmander team join
  Implemented Bulbasaur team join
  Implemented Squirtle team join
Day 4: (10/04/2026)
  Created a system where the Kanto starters stalk the player thought the first part of the journey before acknowledging the player and joining him. (touching, I know)
  Tied in the earlier starter trio team joins with the stalking story line
Day 5: (11/04/2026)
  Refined story and cinematic timings for sprite movement. Starting to learn Camera Mechanics
(yes, I worked on this continuously for the first five days because this was my first experience with creating something that I couldn't find anywhere and its a very good feeling)
Day 6: (14/04/2026)
  Learned how to find flags which are certainly unused, replaced older flags to avoid future conflict (previously i was using CFRU documentation to manually select unused flags but it is risky as RadicalRed might have used some of them)
added an aura sense event near SS ANNE, MewTwo startles red when he leaves SS ANNE after completing it.
Day 7: (19/04/2026)
  changed the title cards and added credits  

To-Do:
  -Create a unique story experience for fan favourite legendaries similar to that of the Kanto Starters 
  -Shadow system
