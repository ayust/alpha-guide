+++  
title = "How to Fit Ships Well"  
toc = true  
date = "2016-11-18T18:56:39-08:00"  
weight = 1  
prev = "/reference/"  
+++

The walkthrough portion of this guide has a number of suggested fits, but perhaps  
you want to design your own fits - or a fit for a ship that isn't mentioned. Well, as they say...give a capsuleer a fit and they'll fly for a day. Teach a capsuleer to fit, and they'll keep flying for the rest of their immortal life.

This page is intended to teach you how to do just that,  
outlining some of the theory and practice of creating your own ship fits.

As an alternate resource written for Omega clones, you can look at the  
[EVE University Fitting Guide](http://wiki.eveuniversity.org/Fitting_Guidelines)  
for another perspective.

### We'll Do It Live!

(Don't do it live.)

You could make a fit by simply buying modules off the market,  
then throwing together whatever you have room for. This will result in a lot  
of wasted money, though, especially when you start messing with Rigs.

Instead, it's better to simulate the fit ahead of time. There's a Simulation Mode built right into the game to help you plan out your fits. If you open your fitting window (with alt+F), then at the top-right, there will  
be a white ship silhouette. Clicking on that will let you enter "Simulation Mode",  
constructing a fit from any modules in the game, using your own skills at the time,  
without having to buy a thing. You'll want to expand the Browser (the wrench on the left)  
and the Attributes (the tab on the right) while building.

Alternately, there's several out-of-game tools to do this, the most notable being  
[Python Fitting Assistant (Pyfa)](https://github.com/pyfa-org/pyfa/releases/),   
[Osmium](https://o.smium.org/),   
and [EVE Fitting Tool (EFT)](https://forums.eveonline.com/default.aspx?g=posts&t=24359),  
though EFT is no longer being updated and is now several months out of date. Some of these have additional features, such as seeing how the fit would  
vary with different skill levels or testing its damage application  
against a variety of targets, or they can just be used  
while you're away from the game client itself.

### Resources

When fitting your ship, there's a few different constraints that limit what you can use:

- The ship's **CPU**.
- The ship's **Power Grid.**
- The ship's **Slot Layout.**
- The ship's **Turret and Launcher Hardpoints.**

You're also limited by your skills in what you can fit,  
and the effectiveness of the modules you do fit.

These resources are limits: you can't fit modules that would take you over your  
maximum CPU or Power Grid, and you can't fit modules to slots you don't have. There's no benefit to "saving" them, though;  
a ship with 100 spare CPU doesn't get any benefit over a ship with  
0.0 spare CPU, but a ship with -0.1 CPU left will have to offline some of its modules  
until it's back under the limit.

A lot of the art of fitting, therefore, lies in spending these resources most efficiently. If you have spare CPU/Grid/Slots, you should be asking yourself  
"Is there a way I could use more of them to improve this fit"? When you're using up a slot by fitting a module, ask yourself  
"How does this module contribute to the goal of the fit?"

### Specialization

In EVE, your ship is not your character; your ship is a tool. Each tool has its own specified purpose. You might be able to use a wrench  
to hammer in nails, or a screwdriver to drill a hole, but it's far better  
to use the tool built to do those things.

Similarly, it's usually better to fit a ship to be very good at one thing,  
rather than mediocre at a lot of things. Then, when flying,  
concentrate on keeping yourself in your optimal situation whenever possible.

For example, it's better to build a ship with a lot of the same type of guns   
in order to be excellent at fighting at a range of about 10km,  
rather than fitting a smattering of different weapons to do  
poor damage anywhere from 1km to 20km. A lot of what you'll be doing when piloting that ship, then,  
is doing whatever you can to ensure that you and your foes stay separated by about 10km.

When coming up with a focus for the fit, a good first stop is to check the ship's bonuses,  
in the "Traits" tab of its "Show Info" window. A ship bonused for armor repairs and hybrid turrets should probably be   
an active-tanked armor fit with blasters, not a shield-buffer droneboat.

One aspect of "specialization" is that you shouldn't "dual-tank". That is, don't fit both shield and armor modules to the same ship;  
focus your resources on having a strong armor tank *or* a strong shield tank. Modules for one don't help the other, and if you can't survive in one "layer",  
it's unlikely that the other will do much better.

### Slots

So, by now you've noticed that your ship has High, Medium, Low, and Rig slots. It might seem a little random what goes where, though. What separates a High slot from a Low slot, or a Medium from a Rig?

Every piece of equipment can be fit to exactly one of these slot types.  
Each type of slot, therefore, has a set of things that you can use that slot on.

If you want to browse what your options are, in the "Hardware" tab of the simulator,  
you can set the filters to only show modules for a given slot type,  
and modules that fit only with your skills and the remaining fitting resources on your ship.

The following sections will outline some of the main things you can use each slot type on.  
The list is not exhaustive, but covers the majority of options.

#### High Slots

High slots primarily bear offensive armament - most notably,   
your ship's weapons, whether Turrets or Launchers. It's almost always best to fit as many Turrets/Launchers as you have hardpoints  
(one or the other, if your ship has both), as that's where most of your damage will come from.

If you have leftover high slots after using up all Hardpoints,  
then you can fit what's known as a "utility high", modules that   
provide some kind of benefit other than direct damage output to your locked target. These can be things like Energy Neutralizers that drain your enemy's capacitor,  
Smartbombs to deal a pulse of area damage around yourself (good for clearing drones),  
Salvagers to pick the bones of wrecks, and so on.

Additionally, high slots hold certain specialized equipment  
for less combat-oriented ships. Probe Launchers for scanning ships,  
Remote Armor Repairers and Remote Shield Boosters to "heal" your allies for logistics ships,  
Tractor Beams for industrials gathering cargo ejected by allied ships,  
and so on.

#### Mid Slots

Mid slots tend to contain CPU-intensive systems.

One module that nearly every ship will want is a Propulsion Module  
of choice - either an Afterburner or a Microwarpdrive.

Mids are also used for Shield modules, meaning that they're the  
primary "defensive" slots of most Caldari and Minmatar ships. Shield Boosters will restore your shields in exchange for large amounts of capacitor,  
while Shield Extenders provide a passive boost to your maximum HP   
(but make your ship slightly easier to hit). Whichever you choose, they're well complemented by Shield Hardeners,  
which increase your shields' resistance to damage.

Mids are also used for Electronic Warfare modules, such as   
stasis webifiers, ECM, sensor dampeners, weapon disruptors, and target painters. Notably for PvP fits, this is where you'll find Warp Disruptors and Warp Scramblers,  
"tackle" modules that prevent your target from simply warping away.

There's also some capacitor-enhancing modules: Capacitor Batteries,  
which increase your maximum capacitor; Capacitor Rechargers,  
which passively increase your recharge rate; and Capacitor Boosters,  
which let you use Cap Booster charges as "ammo" for instant injections of energy.

Finally, there's various modules that let you enhance some aspects of your own  
or other ships, usually in exchange for a small amount of capacitor. Tracking Computers, Sensor Boosters, Missile Guidance Computers,   
and Omnidirectional Tracking Links, among others, fall under this heading.

#### Low Slots

Low slots tend to contain passive modules and/or Power Grid-intensive systems.

One module that nearly every ship will want is a "Damage Control",  
which provides a mild boost to your shield and armor resistances,  
but a huge bonus to the toughness of your hull. A Damage Control  
is one of the most efficient ways to gain EHP (Effective Hit Points),  
and will give you more time to try and warp out - or kill your attacker -   
if things are going badly.

Lows are also used for Armor modules, meaning that they're the primary  
"defensive" slots of most Amarr and Gallente ships. Armor Repairers will restore your armor over time in exchange for capacitor,  
while Armor Plates provide a passive boost to your maximum HP (but slow down your ship). Whichever you choose, they're well complemented by Armor Hardeners,  
which increase your armor's resistance to damage.

The other main use is Damage Mods: passive modules that improve your  
weapons' damage and rate of fire. There's a different type for each weapon system:  
Gyrostabilizers for projectiles, Magnetic Field Stabilizers for hybrids,  
Heat Sinks for lasers, Ballistic Control Systems for missiles,   
and Drone Damage Amplifiers for drones.

Finally, lowslots can contain modules that give your ship more fitting room. Auxiliary Power Cores, Reactor Control Units, and Power Diagnostic Systems  
will give your ship more Power Grid, while Co-Processors will give it more CPU. Try not to spend too many slots on these; usually if you have to spend more  
than one or two slots on "fitting mods", you should be scaling things back elsewhere instead. Slots are a resource, spend them wisely!

#### Rigs

Rigs are passive modifications to your ship,  
which generally trade off one attribute for another.  
Unlike modules, they cannot be removed, only destroyed or replaced with another.

Rigs have a "calibration cost", which is sort of like CPU or Power Grid but applies only to rigs. You can't fit rigs that exceed your ship's maximum Calibration (usually 400, with rigs  
usually costing between 50 and 200 apiece).

Which rig is appropriate to your ship is going to depend highly on what you want your fit to do.  
Some common ones, though this is by no means an exhaustive list:

- Shield/Armor Resistance Rigs (Anti-[TYPE] Screen Reinforcer or Anti-[TYPE] Pump)
- Shield/Armor HP Rigs (Core Defense Field Extender or Trimark Armor Pump)
- Capacitor Rigs (Capacitor Control Circuit or Semiconductor Memory Cell)
- Fitting Rigs (Ancillary Current Router or Processor Overclocking Unit)
- Weapon Rigs ([TYPE] Collision Accelerator or [TYPE] Burst Aerator)

#### Drones

A ship's Drone Bay can be considered part of its weapon system;  
usually the best Drone Bays are found on Gallente and Amarr ships.

Which Drones you can use depends on the ship's Drone Capacity and its Drone Bandwidth.  
You can see these in the "Attributes" tab of the ship's "Show Info" window.

- Light Drones take 5 m3 of space to store and 5 Mbit/sec of bandwidth to control.
- Medium Drones take 10 m3 of space to store and 10 Mbit/sec of bandwidth to control.
- Heavy Drones take 25 m3 of space to store and 25 Mbit/sec of bandwidth to control.

Your pilot can control no more than five drones at any one time, and two "smaller"  
drones is almost always better than one "bigger" drone. So, a ship with 25 Mbit/sec bandwidth and 40 m3 bay, like the Tristan,  
can control a "full flight" of five light drones with three in reserve;  
the Algos, with 35 Mbit/sec and 60 m3, would be better served by a  
primary flight of 2x Medium and 3x Light, with 5x Light in reserve.

As with weapons and ships, bigger isn't always better when it comes to drones; see below.

### Module Size

You've probably been using primarily frigates and destroyers, which use "small" modules. Cruisers and Battlecruisers use "medium" modules, and Battleships use "large". Module sizing is primarily applied to weaponry, defensive modules, and propulsion modules. Capacitor Batteries and Capacitor Injectors also have size variations.

The primary difference is that larger modules have more raw power,  
but take massively increased amounts of powergrid to fit. In the case of weapons, they'll also have difficulty tracking smaller, nimbler targets.

For example, a frigate's 400mm Steel Plates give 900 armor HP,  
but add 350k kg to its mass (making it slower and more sluggish to handle)  
and costing 20 CPU and 30 grid. By contrast, a battleship's 1600mm Steel Plates   
give 3500 HP, but add 3.5 million kg to its mass and cost 30 tf and 500 grid.

Or for weapons, a full rack of 280mm Howitzer Artillery on a Thrasher-class destroyer  
will deal approximately 2000 damage a volley, and cost about 70 grid to fit,  
with a "tracking score" (how well it tracks moving targets;   
see [the UniWiki Gunnery Guide](http://wiki.eveuniversity.org/Gunnery_Guide#Tracking)) of about 100. A rack of 1400mm Howitzer Artillery on a Maelstrom-class battleship  
will deal about 10000 damage per volley, but will cost about 20,000 grid to fit  
and track a hundred times more slowly - it'll have a hard time hitting anything but other battleships.

As such, frigates' small size and high speed lets them evade shots from heavier ships  
with relative ease. If you're thinking about moving up into a cruiser,  
keep this in mind: you should definitely use Medium guns for their better  
range and damage output, but Light drones may be of assistance  
in dispatching the pesky frigates that your guns will have difficulty tracking.

#### Module Caliber

Within size classes, there can be smaller variations.  
Most notably, most guns come in different "calibers" -   
for example, projectile Autocannons come in 125mm, 150mm, and 200mm variants.

A larger-caliber gun deals more damage-per-second, has a longer range,  
and has a slower refire rate (meaning it can have greatly increased "alpha-strike" damage per shot). In exchange, it has poorer tracking, making it less useful against fast, small, close-in targets,  
and has higher fitting costs.

It is most common to try and fit the largest caliber you can initially, for maximum damage,  
and then downsize the guns if you don't have enough CPU or powergrid. There are some exceptions for dedicated anti-small-ship setups.

The "caliber" model somewhat holds for defensive modules, as well;  
for example, a frigate can mount a 100mm, 200mm or 400mm armor plate, with more severe  
fitting costs and speed reductions as the size increases. It's almost always best to fit the largest module you can get away with,  
as this makes the most efficient use of the slot.

If you have sufficient fitting resources, there's nothing to prevent you  
from fitting an "oversized" defensive module, intended for larger size classes,  
such as a battleship's 1600mm Steel Plate mounted on a cruiser. This places severe strain on its powergrid, but grants excellent protection.

This is almost always a bad idea for weapons, however; your ship will not have bonuses for their use,  
they probably won't be suitable to their fighting style/fighting other ships of similar size,  
your ship may not have the capacitor to maintain fire (for Hybrids and Lasers),  
and it's doubtful you'd have the fitting space to mount a full rack in any event.

### Stacking Penalties

It might be tempting to simply cram every low slot full of damage mods,  
with visions of rat-bounty ISK dancing in your head. However, fitting multiple modules that do the same thing will gradually decrease in effectiveness.

You can tell if a module's subject to stacking penalties by looking for the phrase  
"Using more than one type of this module or similar modules that affect the same  
attribute on the ship will be penalized." in the Description tab of their Show Info window.

Two modules of the same type is usually fine, as the 2nd mod is about 87% effective -   
and for modules that add a multiplicative bonus to the stat in question,  
the second can actually wind up more effective than the first.

The third will only be 57% effective, so it may be better to begin looking elsewhere  
for an alternate way to use that slot.

The fourth will be 28% effective; it's almost always better to find something else  
to use the slot on.

The fifth is 10% effective, and the 6th 3% effective. There is basically never  
a reason to fit a module that would be seeing fifth or sixth stacking penalty.

Stacking penalties apply to all bonuses to the same stat. For example, if you   
have an "EM Ward Field" shield hardener boosting your shield's EM resists,  
and an "Anti-EM Screen Reinforcer" rig also boosting your shield's EM resists,  
the rig would face stacking penalties. However, if it was instead an  
"Anti-Thermal Screen Reinforcer" rig to boost your Thermal resists,  
they would be improving different stats and would not be penalized.

Stacking penalties apply in the most favorable order to you:  
the most powerful bonus applies at full strength,  
the next-best at second stacking penalty, and so on. You don't need to worry about the order you fit things.

### Resistance Is Futile

Your ship's resistances are a critical part of its defenses. Having higher resists lets your HP last longer,  
making shield boosting/armor repair more effective   
and multiplying the impact of shield extenders/armor plates.

There's two main strategies for how to improve your resists:

#### Omni Resists

This is the most common strategy, especially for PvP fits. It involves trying to make sure all of your resists  
in your primary tanking layer (shield or armor) are roughly even,  
so that you have no "resist holes" an enemy can exploit.

For shields, this usually means shoring up EM and Thermal.  
For armor, this usually means boosting Explosive and possibly Kinetic.

Once you've equalized your resists, you should start applying omni-resist modules,  
such as Adaptive Nano Platings and Adaptive Invulnerability Fields.

#### Resist Stacking

This is less common, but seen moderately often in PvE fits,  
and occasionally seen in niche PvP fits. If you know the damage type your opponent is going to be using,  
you can simply focus all your resistances in that category. This leaves your ship with glaring "resist holes" against other damage types,  
but so long as nobody shoots you in those, it can make you much stronger against your preferred foe.

Your primary tool for resist stacking will be damage-type-specific  
Shield Hardeners and Armor Hardeners, and possibly resistance rigs.  
Be wary of stacking penalties, however.

Note that canny gankers are well aware of the practice of resist stacking for missions,  
and may specifically load their weapons with a damage type not dealt by the local rats. If you're ratting in dangerous space, or doing missions in an expensive ship  
that may attract unsavory attention, be forewarned of the dangers of leaving a resist hole.

### Meta Is Betta

In the "improved" fits from earlier, you may have noticed some modules with somewhat odd names,  
relative to the relatively simple ones from the starter fits. "Sure, I know what a Light Neutron Blaster is, but what in the world  
is a `Modal Light Neutron Particle Accelerator I`"?

Most modules have what are known as "meta" versions,  
which grant improved effectiveness at lower fitting costs. Meta modules can't be built directly, and are instead looted from rats;  
this means their prices can vary widely, as supply and demand aren't directly linked.

To see the meta versions of a module, check its "Variations" tab.  
You can also directly compare stats of the variations with the "Compare" button at the bottom.

There's two types of common variations: the "meta 1-4" style, and the "specializations" style.

#### Meta 1-4

Some modules, such as guns, simply have four alternate versions with  
gradually increasing effectiveness. If you look in the "Attributes" tab,  
the "Meta Level" lets you know which it is - they're also listed in increasing order  
in the Variations tab (the last one is the meta4).

Each meta level grants about a 5% increase to some aspect of the module. A meta 4 module is about 20% more effective than the baseline version. They also come with reductions in fitting cost,  
though the exact amounts vary from module to module.

Meta 4 modules tend to be much more expensive than the others.  
If you're on a budget, a meta 3 or meta 2 module can often be had for   
dirt cheap - even cheaper than the baseline, meta 0 item.

#### Specializations

The new model, which CCP's gradually converting existing modules to,  
is a more specialization-based concept - rather than "meta 4 is the best",  
each variation has its own specific attribute it focuses on improving.

Modules which follow this pattern have a consistent naming convention:

- "Compact" modules have reduced fitting costs.
- "Enduring" modules have more efficient capacitor usage.
- "Restrained" modules have lower penalties (such as the speed reduction from armor plates).
- "Ample" modules have a larger charge (ammo) capacity.
- "Scoped" modules have a longer range.
- "Upgraded" modules have moderately better stats all around.

They will often still be improvements over the base, meta 0 version even in aspects  
that don't match their specialty; for example, a Restrained Shield Extender  
gives more HP than a baseline Shield Extender.

#### Beyond Meta

After the tech one "meta" modules, there's other improvements:

- Tech II modules (yellow), produced by industrialists,   
    with higher fitting costs and larger penalties,   
    but 20-50% stronger than baseline versions and about 10x as expensive
- Faction modules (green), looted from rare "faction spawn" rats,   
    with substantially easier fitting and better effectiveness than Tech II modules,  
    but about 10x as expensive
- Deadspace modules (blue), looted from Cosmic Anomaly and Cosmic Signature Combat sites  
    ("dungeons" which require powerful and specialized ships to clear), tougher to fit than  
    Faction modules but substantially more effective, and about 10x as expensive
- Officer modules (purple), looted from extremely rare Officer spawns in deep null-security space,  
    the toughest to fit but the most effective, about 10x as expensive as Deadspace modules. Rarely fit to anything short of supercapital vessels due to their sheer expense

Tech II modules are the "gold standard", which most pilots will try to fit as a default. Meta modules let pilots ease up on fitting, while faction and deadspace modules  
allow improvements to a specific aspect of a ship - though at a great cost. Note that meta 4 modules are usually about as effective as Tech II.

As a rough estimate of costs, most modules fall somewhere near the following costs:

- Tech I, meta-0 (baseline) modules: ~50k ISK
- Meta 1-4 modules: ~10k-500k ISK
- Tech II modules: ~1 million ISK
- Faction modules: ~30-100 million ISK
- Deadspace modules: ~250-500 million ISK
- Officer modules: ~2-5 billion ISK

There's some sharp diminishing returns on cost. An officer shield booster, for example,  
costs about a thousand times as much as a Tech II booster,   
but only restores about twice as much shield.

### Fitting Strategies

So, it's all well and good to say "a ship should be fit for a purpose".  
But what purposes should you be fitting for?  
Here's some common types of fits you'll see.

#### PvE

In general, for PvE, you want to fit just enough tank to make sure you survive,  
and then focus the rest of your efforts on dishing out as much damage as possible  
to take out the rats faster.

This means PvE fits tend to have as many lows filled with damage modules as they can get away with.

##### Active-Tank

An "Active Tank" fit focuses on repairing incoming damage faster than it's being taken. This lets them continue fighting as long as they can continue to run their repair modules. This is a natural fit for PvE, where you may be in battle and taking the full attention  
of the NPC pirates for long periods.

The core of an active-tank fit is its Shield Booster or Armor Repairer. These keep the ship in fighting trim. They are almost always supported  
by at least a few Resistance-increasing modules, making them more efficient. An active-tank fit should almost never use Shield Extenders or Armor Plates;  
just as you shouldn't mix shield and armor tanks, you shouldn't mix active and buffer modules.

The second consideration is getting enough capacitor to fuel these hungry modules. Capacitor Control Circuits, Cap Rechargers, and in a pinch Capacitor Flux Coils (for shield fits)  
or Capacitor Power Relays (for armor) will increase your passive capacitor recharge,  
letting you run your repair modules for longer; it's possible to become "cap-stable",  
letting you run them indefinitely. Typically, you won't need to run your repair module  
flat-out at all times, as killing enemy ships will soon reduce incoming damage,  
so don't get too hung up on cap-stability, but it can mean less module micromanagement.

Naturally, fit the best guns and as many damage modules (up to three or four) as you can   
get away with. Tracking Computers/Enhancers, Stasis Webifiers, and the like  
can help you apply more damage as well.

##### Passive-Tank

A "Passive Tank" fit, only used by shield ships, relies on the passive recharge of your shields  
regenerating them faster than you take damage. Since the recharge rate of your shields  
is based on "time to regenerate to full", this usually involves getting a large number  
of shield HP, and is about as close as PvE fits get to the "buffer tanks" of PvP.

Finding the right mix of Shield Extenders, Shield Rechargers and Shield Hardeners  
can require some fiddling. This kind of fit typically requires going all-in, spending nearly every  
low slot on Shield Power Relays and every rig on Core Defense Field Purgers,  
as shield recharge modules are not stacking penalized,  
and thus the multiplicative stacking makes each module more effective than the last.

This tends to leave very few slots left for damage mods or tracking computers,  
and the Shield Power Relays greatly degrade your cap recharge,  
to the point where some ships struggle to even keep a shield hardener active. However, it requires the least micromanagement.

If flying this kind of fit, note that shield recharge is non-linear,  
and peaks at around 25-33% remaining. If your shields dip below 25%,  
you'd say that "your tank is breaking", and it's time to leave.

#### PvP

PvP fits vary widely, depending on the ship, the pilot, and the situation. Remember the specialization mantra, and try to take fights where  
you can keep your optimal situation in place and give yourself the edge.

The most common distinctions, at least for solo PvP, are between "kiting" vs. "brawling" fits,  
and "active" vs. "buffer" tanks. These can be mixed whichever way; you can have an active brawler,  
a buffer brawler, an active kiter, or a buffer kiter.

##### Kiting

Kiting ships focus on high speed and long-ranged weapons to keep themselves  
out of reach of the enemy's retaliation, and are a natural fit for shield ships. They are usually more fragile and with less raw damage output than brawlers. Kiters usually fit a Warp Disruptor for its longer range,  
and a Microwarpdrive for speed.

If flying a kiting ship, beware of enemy ships getting within 10km of you;  
that is the range of Warp Scramblers that can shut off your MWD and prevent  
you from warping out, and Stasis Webifiers that will slow your ship.

##### Brawling

Brawling ships focus on raw muscle, using short-ranged weapons with high damage output  
and mounting powerful tanks to survive enemy fire. They usually have more firepower and defenses than kiters,  
but their slower speed means they may have trouble catching them.

Brawlers usually fit a Warp Scrambler to hold targets down at close range,  
and often a Stasis Webifier to further prevent them from fleeing. A Microwarpdrive is most common, to stand a chance of catching kiting ships,  
but an Afterburner gives them better close-range mobility once the target is caught, as it   
is not shut off by Warp Scramblers and helps them evade fire.

##### Scram-Kiting

At the frigate/destroyer level, some pilots will emply a sort of hybrid of kiting and brawling  
known as "scram-kiting".

The core of scram-kiting is to hold your enemy at the very edge of Warp Scrambler range,  
and fit your ship to be optimized for dealing damage at about 10km,  
and for ensuring that your ship is faster than the enemy under knife-fight conditions  
and thus is able to maintain its preferred range.

A warp scrambler is mandatory for scram-kiting, and a Stasis Webifier is pretty close. Many scram-kiting fits will use afterburners, as they cannot be shut down by a scrambler  
like a Microwarpdrive can, but some will use Microwarpdrives to get in range to begin kiting  
and rely on their webs thereafter, or "dual-prop", fitting both a MWD to get in range  
and an Afterburner to maintain speed during the fight.

Cruiser and battleship are sufficiently long-ranged that they can usually fight back  
against a scram-kiter, so the practice is less common outside of frigates and destroyers.

##### Active-Tank

Active-tanking in PvP can be a risky business, but if you choose your fights appropriately,  
it can leave your opponent helpless to inflict meaningful damage on you  
as you pick their ship apart.

As in PvE, the core of the active tank is an Armor Repairer or Shield Booster,  
attempting to repair damage faster than it's taken.

As small-gang PvP fights tend to be shorter than PvE fights,  
active-tanking PvP pilots will often use the Ancillary Armor Repairer  
and Ancillary Shield Booster modules - special variants of the normal  
modules, which need to be loaded with charges ("ammo") to function most effectively,  
but are much more powerful than the base modules while those charges hold out. The charges will typically last about a minute, then take another minute to reload;  
if the fight isn't concluded by the time the module goes on reload,   
the pilot using it may be in trouble.

As active armor repairers don't show your ship down, unlike armor plates,  
active tanks are a more common option for kiting armor fits than buffer tanks.

Active-tanking is more common in solo PvP and small gangs,  
where incoming damage is limited to a small number of enemy ships  
and you won't be receiving remote repairs from fleetmates. In larger fleet battles, incoming damage from focused fire will be high enough  
that an active tank will simply be overwhelmed.

Note that some opponents will fit Energy Neutralizers, which can attack your ship's  
capacitor directly, leaving you unable to fuel your repair modules.

Remember to fit your ship with omni resists to avoid your opponent  
taking advantage of a resist hole.

##### Buffer-Tank

Buffer-tanking is the practice of simply adding as many effective hitpoints (EHP)  
to your ship as possible, in the hopes that by the time your opponent could chew through them all,  
they'll already be dead.

The Armor Plate or Shield Extender is the core of a buffer-tank fit,  
along with resistance modules to boost their effectiveness.

Remember to fit your ship with omni resists to avoid your opponent  
taking advantage of a resist hole.

Buffer tanks are a natural fit for fleet fights:  
they let you hold up under focused fire long enough for friendly logistics ships  
to lock you and begin repairing you ("catching reps"), and even without logi,  
a buffer fit will usually last longer under concentrated fire than an active fit would. Since your resists will enhance the effectiveness of these remote repairs,  
higher resists can sometimes be worth a small loss in effective HP.

### The Fitting Process

So, after all that hurf blurf about theory - when you're fitting a ship,   
how do you go from a pile of modules and open slots to a finely-tuned weapon of war?

Everyone has their own approach, so the one presented here is just one of many.  
Hopefully it'll give some insight into the thought process at least one pilot uses, though.

#### Step One: Check Bonuses And Slots

The first stop is to check the bonuses on your ship (Show Info > "Traits").  
The things it has bonuses to are probably good things to focus the fit on.

The number of slots it has will also be important in your choice (Show Info > "Fittings".)  
If its slots are heavily biased towards Mid slots, it's probably best  
as a shield or electronic warfare ship. If Lows, it's probably an armor boat.

Check the Drone Bay as well (Show Info > "Attributes") - a good-sized drone bay  
will give you more protection against smaller ships.

#### Step Two: Fit Your Weapons

Use up your Turret or Launcher hardpoints (one or the other, if your ship has both)  
by fitting as many guns as you can, of the largest caliber you have the option for. (If you turn out not to have fitting space later, you can downsize the caliber;  
starting large lets you know what you can get away with.)

Whether to use short- or long-ranged guns depends on how you envision the fit flying. Kiting fits usually want long-ranged weapons. Brawling fits usually want short-ranged ones. Note that long-ranged weapons typically take more fitting space.

For drone boats (Gallente pilots, take note), your drones are your primary weapons system,   
so add them here.

#### Step Three: Fit Your Mandatory Modules

Pretty much every ship is going to want a propulsion module of some kind. Whether that's an Afterburner or a Microwarpdrive depends on your purpose. Most PvP fits will want a MWD; PvE fits may want an Afterburner, for capacitor efficiency.

Pretty much every ship is going to want a Damage Control.

Any PvP fit is going to want a Warp Disruptor or Warp Scrambler.

#### Step Four: Fit Your Tank

Fit whatever tank is appropriate to your ship. They're sometimes referred to  
according to how many slots they use. A three-slot tank is fairly common  
for cruisers; frigates and destroyers often don't have the slots to mount this,  
and will use two or even just one.

If buffer-tanked, this probably means a plate/extender of the largest size you can fit. If active-tanked, this means an armor repairer/shield booster of the largest size you can fit  
and which you can reasonably supply capacitor to run.

Afterwards, you'll probably want a resist module to plug your worst resist hole,   
then an omni-resist module for improvements across the board if you have room.

In the case of active-tanks, you should keep an eye on capacitor here too. If your capacitor will drain exceedingly quickly, put on  
capacitor-enhancing modules - rigs, cap rechargers, or capacitor boosters.

#### Step Five: Add Damage Mods

Throw on up to three damage mods. Pew pew!

#### Step Six: Fill Out Spare Slots

If you have any leftover slots, look at adding things which make your ship more effective.  
Stasis Webifiers, Tracking Computers, Tracking Enhancers, utility highs, and so on.

#### Step Seven: Add Rigs

Rigs might have been added earlier, to plug resist holes or help with capacitor;  
if not, put them in now. If you can't think of something,  
try tank rigs (HP for buffer fits, repair cost/speed for active fits, resist for either)  
or weapon rigs (if you have the spare powergrid to deal with the penalty).

#### Step Eight: Add Drones

Don't forget to fill up your drone bay, if you didn't do that back in Step Two.

#### Review And Iterate

Now, look back over your fit. Do you have enough CPU and Powergrid?  
Does your capacitor last long enough? Do you have enough speed to catch your targets?  
Do you want to deal more damage?

If you don't have enough CPU or Powergrid, try switching to smaller-caliber guns,  
using Compact meta modules, adding fitting rigs/modules, or in a pinch,  
lowering the size of your tank modules. Feel free to ditch utility highs  
if they're putting strain on your fitting room.

If you're still having trouble coming in under CPU limits, you can replace  
lowslots with "free" modules: Nanofiber Internal Structure and Overdrive Injector  
being the main ones, which increase speed/maneuverability at 0 cpu/grid cost. They're not great, but it's better than an empty slot.

If it's still not working, and you don't have any more modules that you can swap out  
without degrading the fit to the point of unusability, it's back to the drawing board;  
the fit just doesn't work.

### Example

So, to demonstrate, let's see an example of how it all comes together. I'll try and walk you through the mental process I was using while  
creating one of the fits used in this guide: the "Improved Cormorant" fit for Caldari.

Here's the Cormorant hull:<object type="image/svg+xml" data="https://o.smium.org/api/convert/118655/svg/118655-cormorant-bare-hull.svg"><a href="https://o.smium.org/loadout/118655">View Cormorant (Bare Hull) on Osmium</a></object>#### Step One: Check Bonuses And Slots

Looking at the Cormorant's Traits, we see that it has a double bonus to Optimal Range,  
and a bonus to Tracking, for Small Hybrids. To leverage that bonus, we're going to  
make it a railgun sniper. The Tracking bonus will help with flexibility a bit, but  
isn't the focus of the fit.

The Cormorant's slot layout is 8/3/2 (high/med/low), with 7 turret hardpoints and no drones. This means a shield tank, as two lows isn't enough for a solid armor tank at the best of times -   
and we'll want that space for damage mods. Besides, Caldari primarily shield-tank anyway.

#### Step Two: Fit Your Weapons

Small railguns come in 75mm, 125mm, and 150mm caliber. We'll want to try to fit 150mm if we can. Opening up the 150mm Railgun I's Variations tab reminds us that the meta 4 version is the  
150mm Prototype Gauss Gun. In the Market, it has an estimated price of 216k ISK;  
that's not too expensive, so we'll use that.

- ADD: 7x `150mm Prototype Gauss Gun`
- CPU REMAINING: 114 of 240
- POWERGRID REMAINING: 18.6 of 81.6

I would try to fit Tech II guns, but this character doesn't have the skills to use them,  
so that's out.

#### Step Three: Fit Your Mandatory Modules

On goes the Damage Control.

For prop, looking at our fitting room, I can see we're already a bit low on grid. We use an Afterburner, for its cheaper fitting costs. Its lower capacitor costs are also of interest, and we use an Enduring afterburner  
to lower them still further, as I'm thinking ahead to Step Four; see below.

This isn't a PvP fit, so we don't add a warp disruptor or scrambler.

- ADD: `Damage Control II`
- ADD: `1MN Monopropellant Enduring Afterburner I`
- CPU REMAINING: 69 of 240
- POWERGRID REMAINING: 7.6 of 81.6

#### Step Four: Fit Your Tank

Since this fit was designed for early PvE, we're making it an active-tanker.

I'd usually prefer to buffer-tank a destroyer,   
but this is a better fit for the purpose of the guide. Destroyer capacitors aren't really suited for extended boosting,  
but long missions with a buffer fit require repeatedly warping out and back in,  
which is a hassle.

As such, we throw on a Medium Shield Booster, the largest boosting module frigates  
and destroyers can usually handle.

We also add an Anti-EM Screen Reinforcer rig to shore up the EM resist hole -   
they're cheap, and they don't use a precious midslot.

- ADD: Medium Shield Booster II
- ADD: Small Anti-EM Screen Reinforcer I
- CPU REMAINING: 11 of 240
- POWERGRID REMAINING: -5.4 of 81.6

**record scratch**

Hmm, that's a problem. We're exceeding our powergrid,  
our CPU is almost exhausted while we've still got two slots to fill,  
and we can barely run the shield booster for 30 seconds before our capacitor runs dry.

If it was just the CPU *or* powergrid, I would probably try and use a fitting module  
or rig to make up the difference. If it was just both of those, I would probably  
try downsizing the gun caliber to 125mm.

But combined with the capacitor pressure, and the difficulty we're going to have in making  
up for that with our limited remaining slots, I decide the best option is to just use  
a smaller shield booster instead. It's just as efficient, it just has lower maximum throughput;  
if we're limited by capacitor anyway, that's fine.

- REMOVE: `Medium Shield Booster II`
- ADD: `Small Shield Booster II`
- CPU REMAINING: 40 of 240
- POWERGRID REMAINING: 4.6 of 81.6

Much more manageable.

#### Step Five: Add Damage Mods

One free lowslot, one mod. Pop!

- ADD: `Magnetic Field Stabilizer II`
- CPU REMAINING: 10 of 240
- POWERGRID REMAINING: 3.6 of 81.6

#### Step Six: Fill Out Spare Slots

We've still got a midslot and two rigs to work with.  
Our capacitor's a bit lacking to run the Shield Booster for extended periods,  
so let's try to improve that.

Capacitor Boosters are a very slot-efficient way to keep modules running;  
however, they require hauling around bulky Cap Booster charges as ammo,  
and I don't like having to continually resupply while missioning -   
or running out mid-mission. We're not *that* far off from being able to run  
the booster for long periods; let's try improving passive recharge instead.

- ADD: `Cap Recharger II`
- CPU REMAINING: **-4.3** of 240
- POWERGRID REMAINING: 2.6 of 81.6

Hmm...we're a bit under on CPU. Not by much, though. Let's keep going for now, and come back  
to see what we can fiddle with later.

#### Step Seven: Add Rigs

We could still use some more capacitor, and cap rigs have no real trade-offs aside from their cost.  
Let's add a couple of those.

- ADD: `Capacitor Control Circuit I` x2
- CPU REMAINING: **-4.3** of 240
- POWERGRID REMAINING: 2.6 of 81.6

#### Step Eight: Add Drones

No drone bay. Easy step.

#### Review And Iterate

So, the fit seems to have pretty much come together. We can run the shield booster  
indefinitely if we're not using anything else, and can keep it active enough of the time  
to feel comfortable while using the guns and the afterburner.

There's still the matter of that CPU deficiency, though; we need to resolve that. We could spend a slot on a Co-Processor or Processor Overclocking rig,  
but losing the slot would be a big blow to the ship's effectiveness.

Let's see if there's something we can meta down instead.

I don't want to meta down the damage control or the damage mod if we can help it,  
as the tech II versions of those give nice, strong benefits. Same for the shield booster.

We could maybe drop the guns to a different meta level...but looking at their CPU costs,  
the meta 4 guns we have installed are the cheapest until you get all the way down to meta 1. I don't really want to lose 15% damage if I can avoid it, either.

That leaves the afterburner and the cap recharger. Fingers crossed...

We started with an Enduring afterburner, to save on capacitor costs. If we swap to a Compact afterburner instead, we can save...two points of CPU and one grid. Not good enough, but it might help in conjunction with something else.

Now the cap recharger. Save me, meta cap recharger, you're my only hope!  
Going from the Tech II cap recharger to the Compact meta version saves us...seven CPU. Huzzah!

- REMOVE: `Cap Recharger II`
- ADD: `Eutectic Compact Cap Recharger`
- CPU REMAINING: 2.4 of 240
- POWERGRID REMAINING: 2.6 of 81.6

If I had any other Compact modules on the fit, I might stop now and review  
whether I could spend my scant remaining CPU and grid to upgrade one of them  
to a variant such as Enduring or Restrained. But I don't, so I won't.

Satisfied with the fit, we load ammo, hop in, and prepare to bring 150mm of antimatter justice  
to any pirate that stands in our way.<object type="image/svg+xml" data="https://o.smium.org/api/convert/118480/svg/118480-alpha-clone---improved-cormorant.svg?privatetoken=988938429179887616"><a href="https://o.smium.org/loadout/private/118480/988938429179887616">View Alpha Clone - Improved Cormorant on Osmium</a></object>