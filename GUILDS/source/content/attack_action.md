Attack Action
=============

During a model Activation you can use its Action to Attack.  
Some models are equipped with 2 Weapon Sets.  
An Attack Action, or Attack Roll is defined by these four phases:

1. Declaring your Attack
2. Rolling ATK Dice
3. ATK check vs DEF stat
4. Applying the Wounds to the target

## Declaring Attack

An Attack Action **uses only one** of the possible Weapons Sets.  
You need to declare which type of Attack you are going to use before rolling any dice, and you need to declare your target, either single models or a Formation.
As seen before, a model or Formation must be in Range and In Vision to be declared as a target.
As seen later, a group of models who share the same Card may Attack all at once with the same Weapon Set.  
Some Weapon sets may inflict elemental Wounds, such as _Fire_ or _Poison_ Wounds.
These kinds of Weapon Sets ATK’s specify in parentheses the type of Wounds inflicted.

```{hint}
Example: You decide to unleash Thunderbeak The Gryphon’s Thunder Breath against a formation of 3 Blackrazor Soldiers.  
With this specific Weapon Set the Gryphon will inflict Thunder Wounds.
```

## Rolling ATK Dices

Once the target is picked and declared, the attacker rolls all its Attack dice with the chosen Weapon Set.  
Melee Attack dice (not Ranged) can be split among all possible Engaged targets: when you do that you must declare how you split and assign your ATK dice before rolling, then roll and resolve all the ATK dice assigned to a single target before doing the same for the following one.  

```{hint}
Example: Uldar the Shapeshifter, a hero with 4 ATK, is engaged with a Kobold and an Ogre.  
During its Activation, after failing a Disengage, he decides to Attack both enemies.
Before rolling his 4 ATK dice, he declares he wants to assign 3 Dice to the Ogre and only 1 to the Kobold, which is much weaker. He rolls 1D6 and wounds the Kobold, killing it, then rolls the remaining 3D6 to kill the Ogre.
```

However, when Attacking a true Formation, it’s always the player who controls the target Formation who decides which model gets the Wounds first.  
In this case, even a single target Spell or Weapon targeting a Formation will potentially Vanquish more targets if enough Wounds are obtained.

## Attack vs Deflection Check

Results of the rolled ATK dice are compared with the target's DEF.  
Each dice that equals or exceeds that value is considered a Success and inflict 1 Wound.
Rolls of natural 6 are Critical Hits: they are always Successful and inflict an additional Wound!

## Shield Roll

Models specialized in the use of the Shield have an "(S)" on the side of their DEF score, like DEF 5 (S).  
These models, when receiving one or more Wounds, automatically perform a free Shield Roll by rolling a D6.
On a **5+**, **1** Wound is ignored during the Attack Action, totally absorbed by the Shield.  
If a Formation with this feature does a Shield Roll, you can roll 1D6 for each model of the Formation and ignore no more than 1 Wound for each one. Shield Roll isn’t available to models possessing a Broken Shield Token.

## Healing

Whenever an effect , Ability or Spell Heals from a Condition, a Token, a Wound or Heroic Wound, it means that you remove that specific Condition/Token/Wound from the model.  
The Healing effect describes exactly how many Wounds, Heroic Wounds or Tokens are removed from the model, or exactly which Condition.  
Some Abilities or Items let you Heal from multiple things at time.  

A Model with (R) in brackets on the side of the Might is a Regenerating Creature, thus healing a Wound at the beginning of each one of its Activation Phase.  

```{note}
Spells and Abilities which Heal from Wounds never Heal from Heroic Wounds.
```

```{hint}
Example: Gino the Brewmaster has 1 Heroic Wounds and 1 normal Wound.  
He uses his Ability “_Gino’s Spiced Brew (T)_” during the End Phase to take a sip of his brew and Heal from 2 Wounds and all his Fatigue Tokens.  
First of all he collects a Torment Token being a Torment Ability, next, he removes 1 Wounds and all the Fatigue Tokens from his Card.  

He can’t recover from the Heroic Wound with this Ability
```

## Resistance and Weakness (R/W)

Certain models have high Resistance, or Weakness, to certain sources of damage, such as Fire Wounds, Frost Wounds, or even large groups of sources like all Wounds coming from Spells.  

For each type of specific damage there is a specific Resistance that reduces it.
Models that receive these types of Wounds and have the corresponding Resistance always suffer 1 less Wound during an Attack Action.
Models with this feature are capable of reducing these kinds of Wounds to 0 if they get just one at time.  

Contrariwise, Weakness to a source of damage will increase the Wounds received by 1 in a single Attack Action.  

Invulnerability are extremely powerful features listed in this same space on the Model Card.
Invulnerability grants total immunity to the source of damages, conditions, spells and so on.
For example a model could be totally invulnerable to Animancy Spells, Terror, Frost Wound and so on.

```{hint}
Example: A Draugr has Weakness to Fire and
Resistance to Frost. This model receives 1 Frost
Wound, and thanks to its Resistance it reduces it
to 0. On the same Round, a Firebolt hits him
causing just 1 Wound: being Weak to Fire, the
Draugr receives 2 Wounds instead and is
Vanquished.
```

## Area of Effect (AoE)

AoE indicates Attacks or Spells that can affect multiple models within a specified area, for example “every model within 10” of a designated point”.  
The AoE could be a Circle, a Cone, a Square or a Line.
Any models that fit into the shape of the AoE Cone/Square/Circle (or models crossed by a Line AoE), are considered targets regardless if they are in a Formation or not.
For this reason, AoE Attacks are especially good at breaking Formations.  

An AOE that gives bonuses to models within its range will typically not require dice to be rolled, like most single target Heals or buffs.  

```{attention}
Unless AoE Attacks, Spells and Abilities specify that they affect only Enemies, they actually affect all models inside a designated area, including allies.  
Be careful with those explosions and cannonballs!
```

### AoE Attacks Dice

AoE Spells, Attacks, Items and Abilities that potentially inflict AoE Wounds are considered AoE Attacks.  
AoE Attacks always indicate a number of AoE ATK Dice.  
These ones differ from regular ATK dice because they are multiplied by the models in the Area.  

The caster of the AoE Attack rolls the corresponding dice to each target separately (one by one), and compares the corresponding dice results to the target Defense before rolling for the next target.  
AoE ATK dice in a range of 0” are Attacks that target all Engaged models, rolling the amount of ATK dice indicated to every target.  

```{hint}
Example: Vesdra the Shaman casts Fire Cannon, which has 2 AoE ATK dice, on an area with 6 Skeletons.  
She needs to roll a total of 12 ATK dice (2 for each Skeleton), so she starts by rolling and comparing 2 dice with the first target, Vanquishing it.
After the first Skeleton has been Vanquished, she proceeds rolling on the next Skeleton.  
After she repeated the process with all 6 skeletons the Spell is terminated.
```
