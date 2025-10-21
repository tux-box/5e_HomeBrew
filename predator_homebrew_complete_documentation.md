# Complete Predator Homebrew Package for 5e.tools

## Package Contents

This homebrew package contains everything needed to implement the Predator class and Yautja race in 5e.tools, including all supporting content.

### Core Files

1. **predator_class_final.json** - The main Predator class
2. **yautja_race_final.json** - The Yautja race with four subraces
3. **predator_optional_features.json** - Optional features for customization
4. **predator_items.json** - Equipment and weapons

## File Descriptions

### Predator Class (predator_class_final.json)

**Core Features:**
- **Hit Die:** d10
- **Proficiencies:** Light/medium armor, simple/martial weapons, tinker's tools
- **Saving Throws:** Dexterity, Wisdom
- **Skills:** Choose 2 from Athletics, Perception, Stealth, Survival, Intimidation, Investigation

**Key Class Features:**
- **Hunter's Code** (1st) - Honor-based combat restrictions
- **Wristblades** (1st) - Signature retractable weapons
- **Bio-Mask** (1st) - Multi-vision helmet system
- **Hunter's Shroud** (1st-2nd) - Stealth abilities
- **Plasma Caster** (5th) - Energy weapon
- **Adaptive Camouflage** (5th-13th) - Advanced stealth
- **Trap Mastery** (9th) - Hunting trap expertise
- **Silent Execution** (15th) - Assassination ability
- **Apex Predator** (20th) - Ultimate hunter form

**Subclasses (Hunting Disciplines):**
1. **Stalker** - Stealth and mobility specialist
2. **Gladiator** - Close combat warrior
3. **Engineer** - Technology and gadget expert
4. **Elder** - Leadership and tactical support

### Yautja Race (yautja_race_final.json)

**Base Racial Traits:**
- **Ability Score Increase:** +2 Dex, +1 Con
- **Size:** Medium
- **Speed:** 30 feet
- **Thermal Physiology** - Environmental perception bonuses/penalties
- **Terrain Adaptation** - Long rest terrain bonuses
- **Natural Resilience** - Poison resistance
- **Languages:** Common, Yautja

**Subraces:**
1. **Jungle Hunter** (+1 Dex, +1 Wis) - Forest specialist
2. **City Hunter** (+1 Dex, +1 Int) - Urban specialist  
3. **Elder Yautja** (+1 Str, +1 Cha) - Leadership focused
4. **Wasteland Hunter** (+1 Con, +1 Wis) - Survival expert

### Optional Features (predator_optional_features.json)

**Vision Modes:**
- **Thermal Vision** - See heat signatures through walls
- **Electromagnetic Vision** - Detect invisible and magical
- **Ultraviolet Vision** - Track by scent trails

**Weapon Upgrades:**
- **Serrated Wristblades** - Bleeding damage
- **Extending Wristblades** - Increased reach
- **Dual Wristblades** - Two-weapon fighting
- **Rapid-Fire Plasma Caster** - Multiple shots
- **Overcharged Plasma Caster** - High damage blast

**Trap Enhancements:**
- **Explosive Spear Trap** - Area damage
- **Electrified Net Trap** - Lightning damage
- **Camouflaged Snare** - Harder to detect

**Hunting Techniques:**
- **Trophy Collection** - Intimidation bonuses
- **Honor Code** - Single combat advantages
- **Hunting Pack Tactics** - Team coordination

### Items (predator_items.json)

**Weapons:**
- **Wristblades** - 1d6 slashing, finesse, light
- **Plasma Caster** - 2d8 fire, range 60/120, 20 charges
- **Shock Dart** - 1d4 lightning, stunning effect

**Equipment:**
- **Bio-Mask** - Multiple vision modes, translation
- **Predator Cloak** - Invisibility (3 charges)
- **Self-Healing Module** - Healing (5 charges)

**Traps:**
- **Spear Trap** - 2d8 piercing damage
- **Net Trap** - Restraining effect
- **Snare Trap** - Lift and restrain
- **Portable Mine** - 3d6 fire damage, 10-foot radius

## Implementation Notes

### Loading Order
1. Load the class file first
2. Load the race file
3. Load optional features (provides customization options)
4. Load items (provides equipment references)

### Cross-References
- Class features reference optional features for customization
- Items are referenced in class descriptions
- All files use consistent source naming for proper linking

### Customization
Players can select optional features as they level up to customize their Predator's equipment and abilities, creating unique hunting styles and specializations.

## Usage in 5e.tools

1. Import each JSON file separately through the Homebrew Manager
2. Files can be loaded independently or together
3. All content will appear in appropriate sections (Classes, Races, Optional Features, Items)
4. Cross-references will create clickable links between related content

This complete package provides a fully functional Predator class with extensive customization options, supporting equipment, and the Yautja race for players who want to create the ultimate hunter character.
