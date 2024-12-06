# Cataclysm-DDA-Touhou-Mod
This is a fork of Taberone's [Touhou Professions](https://github.com/Taberone/Cataclysm-DDA-Touhou-Mod) mod.

**The mod's folder goes in /data/mods/**.  Last updated for game version: 0.H ~~(Hebert)~~ (Herbert).

Also check the [Expansion](https://github.com/RedMisao/Cataclysm-DDA-Touhou-Expansion) mod!

Also check the [Project Moon](https://github.com/Sliperr34/PM_World) mod!


## About the mod
This mod adds Touhou Project characters as professions.  Characters (2hus) have custom spells, abilities, clothing, martial arts, traits (mutations), appearances, and more.  To pick any of the 2hus, you have to select the "☯ Touhou Mod ☯" scenario when creating a new character.


## 2hus
* **Aya Shameimaru:** Uses wind spells.  The earnest, most pure, fastest Tengu reporter is always on the look of interesting news.
* **Fujiwara no Mokou:** Uses fire spells.  Fights using a custom brawling style.  Her attacks do increased damage with more pain.  Death has no meaning to her.
* **Hong Meiling:** Uses qi.  Fights using a special form of Tai Chi focused on defense, with windows of opportunity after blocking attacks.  Nap time can't come soon enough.
* **Hata no Kokoro:** Uses emotion.  Constantly swaps between four masks representing emotions, each grants her different effects (affects spells too!).
* **Iku Nagae:** Uses electric spells.  Fights by whipping and shocking enemies to death, while dancing on the battlefield.
* **Kasen Ibaraki:** Uses variant taoist techniques.  Fights by weaving blows between her hard hitting arm, and the harder hitting arm.
* **Reisen:** Uses a mysterious ability.  Recently conscripted into the Lunarian Defense Corps, fights aided by her service Lunarian rifle and basic military training.  She's trying her best!
* **Reisen Udongein Inaba:** Uses wavelength manipulation.  Former member of the Elite Lunarian Defense Corps, proficient with firearms and skilled in special operations.  Starts with a Lunarian tech pistol.
* **Remilia Scarlet:** Uses Red Magic.  The charismatic vampire leader of the Scarlet Devil Mansion, nothing can oppose her when she's serious.
* **Rin Kaenbyou :** Uses destructive fire spells and calls forth Vengeful spirits to assist her in battle.  Collects corpses with her wooden wheelbarrow.
* **Sakuya Izayoi:** Uses time manipulation.  Fights by elegantly throwing knives, then cleaning it all perfectly afterwards.
* **Seiga Kaku:** Uses wicked taoist techniques and can pass through walls.  Fights without care for human life or norms, all while forcing "collateral damage" victims back to life to fight for her.
* **Tenshi Hinanawi:** Uses earth spells.  Very resistant to physical damage, very susceptible to boredom, she wields the Sword of Hisou and fights with a martial art focused on critical attacks over anything else.
* **Utsuho Reiuji:** Uses nuclear spells.  She's half Hell Raven, half sun god, half pet, wholly awesome.
* **Yamame Kurodani:** Uses arachnid techniques.  Inflicts illnesses upon her enemies, which she can manipulate further.  Good thing she's a friendly spider!
* **Youmu Konpaku:** Uses sword techniques.  Also trained in gardening, she wields Roukanken and Hakurouken, two Youkai katana capable of cutting anything!


## New mechanics and stuff
* New spell system.  Explore a variety of new spells and spell interactions by yourself :) (or expand the list below)
  * Spell growth.  All character spells and spell effects now scale proportionally to their main skills (and in the future, weapon damage), instead of spell level, growing more naturally alongside of each character's "main" skill.
  * Spell tags.  Some spells can now "tag" monsters, which enables FUN stuff spell interactions
* Auras.  Various characters have toggle-able "aura" style abilities, each granting different effects as long as they're active.  Can be turned ON or OFF by casting them again.
* Blood thirst.  Remi now has to consume blood (or human flesh, with less effectiveness) in any shape or form, in order to keep the thirst at bay.
* Immortality.  Mokou resurrects after dying, immediately restoring her body.  She can die as many times as she wants, but there's a soft cap relative to how many times she has died in a period of time, plus a small-ish pain debuff that stacks, to discourage savescumming.
* Custom Martial arts.  Some characters have martial arts with new effects, such as automatic spell casting at the target (with no cost), cosmetic effects, conditional effects depending on the equipped weapon, the ability to parry, etc.
* Soul damage.  A custom damage, which deals extra damage to spiritual beings, and reduced to extradimensional beings (mostly used at the Expansion)
* Wings/Flight.  Aya, Remi and Utsuho can now fly in three dimensional space, consuming stamina until they're tired enough.  This is done by activating a mutation (View/active mutations key).
* Youkai form toggle.  Kaenbyou, Remi and Yamame can now switch between their human and youkai forms, each having different effects.  This is done by activating a mutation (View/active mutations key).


<details>
    <summary>A more exhaustive list of the mod's spell system:</summary>

  * Spell **tags** alone enable the following:
    * Double damage
    * Spreading diseases between monsters
    * Jump-kicking a target to a location (or in othe words, kick a target and move together to the intended destination.  Or a wall)
    * Corpse explosion!
    * Summoned allies casting spells after the master
    * Literally necromancy (throwback to the good old 0.C times)
    * Ritual spells
  * Some spells were updated to now automatically **cast at a location** without further player input
    * This was expanded to the custom martial arts, so techniques can now proc **mini-spells**
    * This was also expanded by adding **delayed directional spells** without player input
    * Throw weapon.  Kokoro **throws her weapon**
    * **Pull enemy to you**.  Or item.  Or pull yourself tow- oops that's spoilers
    * An active **Parry** mechanic, which counterattacks incoming damage
    * Spell VFX wherever possible, including some custom martial arts techniques
    * Probably more stuff I forgot

</details>


## Clothing
Every 2hu has their own custom set of clothing.  Not all are just cosmetics changes.


## Other/Misc
* A lot of functional-but-as-a-workaround stuff present in master_0.G is now fully functional as intended
* A **lot** of bugfixes, too many I lost count, the issue tracker (at the Expansion) is not even remotely representative. Thank you contributors.


## Minor milestones
Relatively easy things to add, not in order:
* More ritual spells whenever applicable.
* More 2hus: Nitori (WIP) (it's been years omg sorry).  Flandre and Joon are on the backlog, too.
* Visual effects: Can it be done with fields? For example, when Youmu dashes, cherry petals appear on the path.
* Visual indicators: Mainly for dashes, so it can be unbinded from stamina
* Vehicles: Make an engine that can use corpses as fuel (almost as metal as using blood as fuel).  All the data is already present, except I cannot limit it to human/zombie corpses only.  The current system relies on killing humanoid enemies which drop a passive resource that can be crafted into fuel.
* Balance: Numbers, specially those from spells and passives, may be overtuned compared to other mainlined mods.  This is both intentional (2hus are broken) and unintentional (game no fun anymore when me broken).


## Major milestones
Relatively hard or complex things to add, not in order:
* Even MORE 2hus.
* Things that are currently hardcoded, like new resources, new kind of spells (like using proyectiles, different shape, etc.), more mechanics, etc.
* Spellcards?

