---- Evereign ----
Javascript based 2D fantasy MMORPG using Phaser and Node JS

Factions

Character Races

Character Attributes
    Strength - Increases damage of melee attacks
    Intelligence - Increases mana pool
    Willpower - Resist magic attacks
    Agility - Increase critical hit chance
    Endurance - Increase health points, resist physical attacks
    Personality - Improves quest rewards and trading prices

Character Abilities



Character Equipment slots
    Main Hand
    Off Hand
    Head
    Chest
    Legs
    Feet
    Hands
    Ring
    Necklace
    Trinket (Class-specific item, usually to allow casters to use spells)

Character Skills

    All skills start at level 1 have a maximum level of 500 and are progressed by performing relevant actions
    Characters get better at those skills by using them and unlock unique abilities for reaching certain thresholds per skill

    1 - Training
    100 - Proficiency
    250 - Expert
    500 - Master

    All crafting skills can be used by all characters, however only to a basic level unless they choose to be a specialist in those skills
    Non-specialists can craft common and uncommon quality items 
    Specialists can craft rare and higher quality items
    A character can choose to be a specialist in 5 crafting skills

    Combat
        Swords
        Maces
        Axes
        Rapiers
        Hammers
        Morningstars
        Daggers
        Dual Wielding
        Flails
        Guns
        Bows
        Crossbows
        Heavy Armour
        Medium Armour
        Light Armour
        Shields
        Parry
        Block
        Dodge

    Crafting
        Woodcutting (Felling trees for wood)
        Weapon Smithing (Crafting metal weapons)
        Wood Working (Crafting wooden weapons)
        Armour Smithing (Crafting heavy armour)
        Leatherworking (Crafting Medium armour)
        Tailoring (Crafting light armour)
        Engineering (Creating gadgets and contraptions)
        Alchemy (Creating potions from herbs and plants)
        Herbalism (Collecting herbs and plants)
        Fishing (Collecting fish from fishing spots)
        Cooking (Crafting food from raw food)
        Jewellery (Crafting rings and necklaces etc)
        Mining (Collecting ore from deposits)
        First Aid (Creating healing items)

Character Classes

    -- Gladiator
    Gladiators are relentless warriors, they use their exceptional conditioning and prowess in melee combat to take on foes toe-to-toe. Gladiators are known for 
    their ability to withstand incredible amounts of damage and to fight on even when others would falter.

    -- Subclasses
    Praetorian (Melee, Tank)
    Description: Focuses on defence, rather than offense. Has abilities to take attention away from allies and force enemies to focus on the Praetorian instead.
    Abilities:
    Heavy Armour Training (Allows use of heavy armour)
    Shield Training (Allows use of shields)
    Fortitude (Extra 2 health points per level)
    Draw Attention (Taunt one enemy to focus on you)

    Level 6 Trait: Dauntless (Ability, increase block and parry chance, and gain temporary health points)
    Level 9 Trait: Never falter (Ability, immune to all damage for a short time)
    
    Spellblade (Melee, Physical Damage, Magic Damage)
    Description: Sacrifices some raw strength to study the magical arts, allowing the Spellblade to infuse their attacks with magic
    Abilities:
    Imbue Weapon (Ability, Enchant weapon to deal extra magic damage on hit)
    Force bolt (Ability, Short range attack, deals force damage to target)

    Level 6 Trait: aoe fire spell 
    Level 9 Trait: Magic adept

    Champion (Melee, Physical Damage)
    Description: Focuses on close range mastery, wielding two weapons at once to overwhelm foes
    Abilities: 
    Dual Wield Training (Allows the use of two 1-handed weapons at a time)
    Double Strike (Attack with both equipped weapons for extra damage, generates Adrenaline)

    Level 6: Martial Expert (Passive, weapon attack cooldowns are reduced by 1 second)
    Level 9: Overwhelm (Ability, three weapon attacks in quick succession, costs adrenaline)

    Resource: Adrenaline. Build up by using weaker abilities, consume to use more powerful ones

    -- Starting Abilities
    Light Armour Training
    Medium Armour Training
    Sword Training

    -- Starting Equipment
    Rusted Chailmail
    Dull Longsword
    2x Food
    2x Healing Potions

    Progression:
    Level 1 - Gain starting abilities and equipment
    Level 2 - Rush (Ability, Charge at an enemy and deal damage on contact, generates Adrenaline)
    Level 3 - Choose Subclass (Praetorian, Spellblade or Champion) and gain assosciated abilities
    Level 4 - One crafting specialisation point
    Level 5 - Focused Strikes (Ability, consume Adrenaline to deal extra damage with weapon attacks)
    Level 6 - Subclass Trait (Praetorian: Spellblade: Champion:)
    Level 7 - Sweep (Ability, strike the target, and another within 5 meters for the same damage, costs Adrenaline)
    Level 8 - One crafting specialisation point
    Level 9 - Subclass Trait (Praetorian: Spellblade: Champion:)
    Level 10 - Bloodlust (Ability, restore some health and deal more damage, costs Adrenaline)

    Every level - 1 attribute point, 3 health points
    
    ----------------------------------------------------------------------

    Godsworn
    The Godsworn is a divine warrior, drawing upon the powers granted by the gods to fuel their combat abilities and support their allies. They wield 
    holy magic to heal and protect their comrades, and smite their enemies with divine wrath.

    Subclasses:
    Forsaken (Melee, Tank)
    Mender (Melee, Healer)
    Ascended (Melee, Physical/Magic Damage)
    
    Resource: Retribution

    -- Starting Abilities
    Light Armour Proficiency
    Medium Armour Proficiency
    Shield Proficiency
    Mace Proficiency

    -- Starting Equipment
    Splint Mail
    Shield
    Mace
    2x Food
    2x Healing Scrolls
    Divine Focus
    
    ----------------------------------------------------------------------

    Operative
    The Operative is a master of stealth and subterfuge, skilled at striking at range from the shadows or taking down targets up close with poisons. They can approach 
    their foes unseen and dispatch them with swift and deadly precision.

    Subclasses:
    Marksman (Ranged, Physical Damage)
    Agent (Melee, Physical Damage, Poison)
    Physician (Ranged, Healer)
    
    Resource: Momentum

    Starting Abilities:
    Light Armour Proficiency
    Dagger Proficiency
    Bow Proficiency
    Starting Equipment:
    Leather Armour
    Dagger
    Shortbow
    50x Makeshift Arrows
    2x Food
    2x Healing Potions


{
name: "Arcanist",
description: `The Arcanist is a mage who draws upon the powers of light and life to dispatch their foes.\n 
      They can summon elemental forces and manipulate the energies of life and nature to protect their allies and harm their enemies.\n
      Subclasses:\n
      Lifebringer (Ranged, Healer)\n
      Elementalist (Ranged, Magic Damage)\n
      Battlemage (Melee, Physical Damage, Magic Damage)`,
starting_description: `Resource: Mana\n`,
},

{
name: "Harbinger",
description: `The Harbinger is a dark mage who uses the powers of necromancy and blood magic to bring ruin to their foes.\n
      They can summon the spirits of the dead and harness psychic forces to manipulate the battlefield.\n
      Subclasses:\n
      Corruptor (Ranged, Magic Damage)\n
      Deathless (Ranged, Healer)\n
      Siphoner (Melee, Magic Damage)`,
starting_description: `Resource: Peril\n`,
},
];

module.exports = Classes;