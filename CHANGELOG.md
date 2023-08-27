<h1 align="center"><b>CHANGELOG</h1></b>
<p align="center"><b>day/month/year</b></p>
‎


<h1 align="center"><b>[v1.1.1] - 23/08/2023</h1></b>

- Improved FOMOD overall

### **The Great Cities of JK's North:**
- Removed **Fixes** patch but for real this time (it's been incorporated into the main patch now)
- **Rodryk's Dragon Bridge patch**
  - Apparently there was a deleted navmesh. Super sorry to anyone who had issues due to this!
  - Cleaned with QAC
  - WARNING: Updating might need a new save?
- **Lux Orbis patch**
  - Removed floating firepit in Windhelm


### **RogueUnicorn's City Trees:**
- Removed landscape records from City Trees Whiterun - JK's Skyrim Patch Fix (???? how did they even get there)


### **Skyrim Arrow Overhaul:**
Sorry for taking so long! Everything should be up-to-date with all the SPID changes taken into account. No more crashing!

- **Added The Dragon Cult - A Draugr Overhaul patch**
  - Value changes and keyword forwarding
- **Added The Dragon Cult - A Draugr Overhaul + WACCF patch**
  - Value changes and keyword forwarding
- **Added Thaumaturgy + WACCF patch**
  - Naming consistency
- **Changed No Perk Categories addon**
  - Renamed to "Language Tweaks"
  - Now improves the English on arrowheads, a few perk descriptions, and the newly added book
- Removed redundant patches:
  - Sons of Skyrim
  - Cloaks of Skyrim
  - Manbeast
  - Dragon War
  - COIN
- Adjusted patches:
  - WACCF
  - Sets of Skyrim
  - Sets of Skyrim + WACCF
  - Mysticism
  - Adamant
  - USSEP
  - RoM
  - RoM + WACCF


### **Miscellaneous:**
- **Changed ArteFakes Stripped**
  - Removed templates from weapon records. This would've caused the weapons to not have unique models
  - Re-enabled tempering recipes
  - Many tiny changes
  - **Added RoM Patch**
    - Forwards RoM stats & enchants but keeps ArteFakes' new model
    - Can/should be used instead of the official ArteFakes RoM patch
  - **Added RoM + WACCF Patch**
    - Forwards WACCF keyword changes
  - **Changed WACCF Patch**
    - Removed templates from weapon records
  - **Changed Thaumaturgy Patch**
    - Removed templates from weapon records
  - **Changed SAO Patch**
    - Removed deleted object effects(?)
  - **Changed SAO + WACCF Patch**
    - Removed templates from weapon records
    - Removed deleted object effects(?)


***


<h1 align="center"><b>[v1.1.0] - 01/02/2023</h1></b>

- Added **"Base Object Swapper"** as a manual detection mod
- Added **"Skyrim Arrow Overhaul"** patch page
- Added **"Miscellaneous"** patch section


### **The Great Cities of JK's North:**
- Removed **Fixes** patch; they've been integrated into the main mod now.


### **EEK's Whiterun:**
- **Added "EEK Tree Swap"** (*Base Object Swapper*)
  - For some reason, EEK's Whiterun uses its own base tree object for its Aspen trees, even though it's using vanilla models.
  - This uses Base Object Swapper to change it back to the vanilla base object, meaning your favorite tree mods, that potentially change tree records, can take priority. Use this if you're using Blubbo's Aspens.


### **Skyrim Arrow Overhaul:**
- **Added "No Perk Categories" addon**
  - Removes the categories from perk names (i.e "*Eagle Eye*" > "*Strength: Eagle Eye*")

- **Added USSEP Patch:**
  - Forwards most USSEP changes and keywords

- **Added WACCF Patch:**
  - Forwards WACCF value changes and keywords
  - Forwards tier balancing for Orcish, Elven, and Dwarven bows
  - Forwards recipe condition changes

- **Added Adamant Patch:**
  - Forwards recipe perk condition changes for Nordic and Stahlrim items
  - Takes the Adamant + Mysticism patch from base SAO and seperates it, along with other changes like the above (use this instaed)

- **Added aMidianborn Skyforge Weapons Patch:**
  - Adds SAO keywords and balancing to the Skyforge Steel arrow, arrow recipe, and bow

- **Added Cloaks of Skyrim Patch:**
  - Merges SAO and Cloaks of Skyrim outfits

- **Added C.O.I.N. Patch:**
  - Merges Draugr Treasure Chest record

- **Added Dragon War Patch:**
  - Forwards SAO skeleton keyword to undead dragon race records

- **Added Manbeast Patch:**
  - Forwards SAO werewolf keyword to Werewolf race record

- **Added Mysticism Patch:**
  - Forwards SAO magic armor keyword to Fortify Armor Rating effects
  - Takes the Adamant + Mysticism patch from base SAO and seperates it, along with other changes like the above (use this instaed)

  - **Added Mysticism + Immersive Sounds Patch:**
    - Forwards Mysticism ISC patch changes to sound

- **Added Thaumaturgy Patch:**
  - Removes enchanted bows from leveled lists

- **Added Reliquary of Myth Patch:**
  - Adds SAO keywords and flags to new bows and arrows
  - Adds Ebony Quiver to Dremora Archer outfit
  - Forwards SAO keywords and balancing to bows

  - **Added Reliquary of Myth + WACCF Patch:**
    - Forwards WACCF value changes and keywords
    - Choose one or the other

- **Added Sets of Skyrim Patch:**
  - Forwards SAO changes

  - **Added Sets of Skyrim + WACCF Patch:**
    - Forwards SAO changes *and* WACCF keywords
    - Choose one or the other

- **Added Sons of Skyrim Patch:**
  - Adds Quivers to Sons of Skyrim guard outfit changes

- **Added Skyrim Unbound Patch:**
  - Adds a Bolt Bag and Leather Quiver in the Inventory MCM section

- **Added Unplayable Factions Armor Patch:**
  - Adds Silver Bolts to Silverhand crossbow NPCs
  - Adds Bolt Bags to the new Silverhand outfits
  - Adds Iron Quivers to Bow-wielding Alikr
  - Adds SAO keywords to the new Silverhand Crossbow
  - Changed Silverhand Crossbow to classify as a silver weapon instead of steel (with keywords), just a mini bug-fix. I'm not sure if this would matter in any context though


### **Miscellaneous:**

- **Added ArteFakes Stripped addon:**
  - Makes ArteFakes *just* a unique weapon model replacer, and re-applies vanilla balancing, keywords, flags and recipes
  - Fixes a few very minor bugs
  - Adds the "Briarheart Gais" axe to leveled lists
  - Removes all changes and additions near the Aetherium forge (including the Zahkrii Do Dovahkiin sword)
  - Removes all added objects in the Markarth Treasury House
  - Removes all loading screens
  - Removes the majority of ArteFakes' recipes, and thus, new weapons

  - **Added WACCF Patch:**
    - Forwards WACCF balancing and keywords
    - Works with non-stripped version, but won't touch ArteFake's new weapon records, only vanilla records

  - **Added Thaumaturgy Patch:**
    - Forwards MagicDisallowEnchanting keyword and Editor ID change to the Steel Battleaxe of Fiery Souls
    - Works with non-stripped version, but won't touch ArteFake's new weapon records, only vanilla records

  - **Added Skyrim Arrow Overhaul Patch:**
    - Forwards SAO keywords and descriptions
    - Works with non-stripped version, but won't touch ArteFake's new weapon records, only vanilla records
		- **Added Skyrim Arrow Overhaul + WACCF Patch:**
		- Forwards SAO *and* WACCF keywords
		- Choose one or the other

- **Added Adamant - Disable Default Bow Zoom:**
  - This disables Adamant's default bow zoom perk
  - Useful (and recommended) if using Skyrim Arrow Overhaul, or other mods which overhaul the Archery perk tree

- **Added Book Covers Skyrim - Puzzle Variations Patch:**
  - Forwards BCS's model to Puzzle Variation's edited "Notes on Yngol Barrow"

- **Added Cathedral Mountain Flowers - Mesh Fixes:**
  - Directs Purple Mountain Flower meshes to a seperate texture from Cathedral 3D Pine Grass
    - Fixed conflict when using 3D Pine Grass + Cathedral Mountain Flowers + 3D Pine Grass ENB Complex Grass textures
  - Fixed Snowy Red Mountain Flowers mesh not pointing towards the snowy red mountain flower texture

- **Added Cathedral Mountain Flowers - Swap Windhelm Flowers** (*Base Object Swapper*):
  - Swaps all mountain flowers in Windhelm to snowy versions added by Cathedral
  - Very nice if using Icy Windhelm, but is recommended overall either way
  - Requires Base Object Swapper

- **Added JS Unique Daggers - Reliquary of Myth Patch:**
  - Patched Nettlebane to use JS's model and RoM's balancing and enchantment

- **Added JS Unique Daggers - WACCF Patch:**
  - Forwards WACCF balancing and keywords

- **Added Nature of the Wildlands - No Soulstheim Grass:**
  - Reverts Soulstheim Landscape textures records to vanilla; where there is no grass

- **Added Nature of the Wildlands - Revert Shrubs:**
  - Reverts tree shrub tree records to vanilla
  - Can't remember what this was useful for lol

- **Added Nature of the Wildlands - Revert Whiterun Temple Tree:**
  - Reverts Whiterun's temple tree records to vanilla

- **Added Happy Little Trees - Snow Pine Priority**
  - Adds Happy Little Trees's Snow Pine settings in an ESP, so you can have a mod that uses an ESP for its settings and model file-paths. For example, with NotWL and I think Ulvenwald, you can use this ESP to overwrite their model changes to snow pines. 

- **Added Unplayable Factions Armors - Tamrielic Distribution + Pirates Wield Cutlasses Patch:**
  - Makes certain pirates (Blood Horkers, Blackbloods, and certain NPCs) wear NordWarUA's new armor while using the new cutlasses


***


<h1 align="center"><b>[v1.0.2] - 10/01/2023</h1></b>

- Multiple FOMOD fixes

### **EEK's Whiterun:**
- **Fixes:**
  - Renamed EEK's added guards to "Whiterun Guard"
  - Removed Callon's hunting AI package due to him fighting the whiterun guards
  - Fixes navmesh around a crate
- **No Tree Circle Braziers:**
  - Removed warming hands idle marker around one of the braziers
- Revert Whiterun Market:
  - Moved idle marker
- **Added SunHelm Patch:**
  - Moves the well bucket to fit EEK's new well mesh

### **City Trees:**
- Renamed existing patches:
  - City Trees - JK's Skyrim Patch Fix -> City Trees Whiterun - JK's Skyrim Patch Fix
  - City Trees - EEK's Whiterun Patch -> City Trees Whiterun - EEK's Whiterun Patch
- Re-categorized options in FOMOD
- **Added City Trees Windhelm - Lux Orbis + JK's Skyrim Patch**
  - Removes the two maple vines that clip into the Lux Orbis - JK's Skyrim Patch's two braziers


***


<h1 align="center"><b>[v1.0.1] - 08/01/2023</h1></b>

### **Rodryk's Dragon Bridge:**
- **Added Rodryk's Dragon Bridge + JK's Skyrim - LFFGM Patch Fix**
  - Requires [Rodryks x JK's Skyrim LFFGM Patch by somohexual](https://www.nexusmods.com/skyrimspecialedition/mods/50408)
  - Credit to Tobes from the Patching Pub discord


***


<h1 align="center"><b>[v1.0.0] - 05/01/2023 - Transition Update**</h1></b>

- Happy new year!
- Reworked the entire mod & mod page to be centered around a bunch of city mods instead of just The Great Cities of JK's North
- Reworked and reorganized FOMOD
- Removed "TGCoJN - R's Farmhouse Positioning Fixes" (replaced)
- Removed "TGCoJN + Rodryk's Dragon Bridge - Happy Little Shrubs Patch" (replaced)
### **JK's Skyrim:**
- **Added JK's Skyrim - R's Farmhouse Patch**
	- Works and should be used with all crossover patches here, just let their R's Farmhouse patches load after this one
	- Removes and repositions stonewalls in Morthal
	- Removes stockades in Dragon Bridge and repositions/removes stone walls in Dragon Bridge
- **Added JK's Skyrim - No Extra Nirnroot In Morthal**
	- Removes a vanilla nirnroot in a Morthal pond so that you don't get overlapping nirnroot sounds in the same area
	- Can be used standalone; without JK's
	- Recommended if you're using COTN Morthal + JK's 
### **Rodryk's Dragon Bridge:**
- Moved TGCoJN patches to this section of the FOMOD
- **Added Rodryk's Dragon Bridge - Happy Little Shrubs Patch**
	- Repositions, removes, and replaces a few shrubs
- **Added Rodryk's Dragon Bridge + JK's Skyrim - Fixes**
	- Fixes for the [Rodryks x JK's patch by somohexual](https://www.nexusmods.com/skyrimspecialedition/mods/50408)
	- Repositions the lean marker in Old Bridge Goods
	- Fixes the infinite lock on the Old Bridge Goods doors
	- Made Sillia Krohnsson persistent because she kept mysteriously disappearing
	- Removed clipping fences at the Penitus Oculatus building
	- Repositioned shields at the blacksmith
- **Added Rodryk's Dragon Bridge + JK's Skyrim - Lux Orbis Fix**
	- Requires the [Rodryks x JK's patch by somohexual](https://www.nexusmods.com/skyrimspecialedition/mods/50408)
	- Repositions the two lanterns infront of Old Bridge Goods
- **Added Rodryk's Dragon Bridge + JK's Skyrim - R's Farmhouse Patch**
	- Requires the [Rodryks x JK's patch by somohexual](https://www.nexusmods.com/skyrimspecialedition/mods/50408)
	- Repositions stone walls around Old Bridge Goods
- **Added Rodryk's Dragon Bridge + JK's Skyrim - Happy Little Shrubs Patch**
	- Repositions, removes, and replaces a few shrubs
### **City Trees:**
- **Added City Trees - EEK's Whiterun Patch**
	- Repositions and removes a few trees around the Whiterun market, and removes a floating piece of Hanging Moss
- **Added City Trees - JK's Skyrim Patch Fix**
	- Repositions and removes some trees that their patch missed
### **EEK's Whiterun:**
- **Added EEK's Whiterun - Fixes**
	- Fixes the positioning of the smelter at the Skyforge
	- Fixed EEK_VegBasket.nif texture pathing/missing texture error
	- Re-enables the TundraScrub03 **(subjective)**
	- Removes a duplicate gate
	- Disables two pine shrubs that clip through EEK's hunting station stairs
	- Disables 3 road chunk objects that look very out of place **(maybe subjective?)**
- **Added EEK's Whiterun - Fortified Whiterun Patch**
	- Removes clipping objects with the tower added by Fortified Whiterun
- **Added EEK's Whiterun - Lux Orbis Whiterun Horses Patch**
	- Repositions one of the horse statues and its accompanying fire to stop it from clipping
	- Removes an aspen tree that clips through the main horse statue
	- Removes a few tundra scrubs added by Whiterun Horses
- **Added EEK's Whiterun - Lux Orbis Patch Fix**
	- Fixes an issue in the official Lux Orbis patch for EEK's Whiterun where it doesn't forward EEK disabling a fire at the Skyforge, and instead re-enables it
- **Added EEK's Whiterun - No Tree Circle Braziers**
	- Removes the braziers around the Kynareth tree
- **Added EEK's Whiterun - No Tree Circle Braziers for Lux Orbis**
- **Added EEK's Whiterun - Revert Whiterun Market**
	- Re-enables some of vanilla/JK's decor and disables some of EEK's Whiterun decor around the whiterun market, like the vegetable stands
	- I mostly did this to get rid of the ugly vegetable stands
