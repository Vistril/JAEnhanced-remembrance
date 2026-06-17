# JAEnhanced: Remembrance Branch by Vistril/Minerva1148

This is my personal repository for all the balance changes I have made to JAE so I can track them better and get a releasable DLL into the hands of players sooner.

This is built off of JAEnhanced, you should look at that repository's README.md first before you do anything with mine. Just in case. It's here: https://github.com/JAEnhanced/JAEnhanced

---

# Completed Balance Changes + Enhancements
- Allow enemies with certain weapons to alt-fire when it makes sense to (E-11 wielders alt-fire by default, Repeater enemies alt-fire if the range is correct)
- Allow enemies to move and cycle between combat points, cycle ducking faster, move more and resist staying stationary as well as fire during movement. Ranged Enemies now fight like their lives depend on it. However note that some enemies may stay stationary regardless for a multitude of other reasons. I will figure this out soon.
- Reborn no longer reflect rockets (including force-pushed) ones 100% of the time so players who like the RL have a chance against them
- Explosive weapons + the concussion rifle primary fire now gib and dismember enemies

# Planned Balance Changes
- Allow enemy Reborn/Sith to slowly approach you instead of just staring at you and doing nothing
- Grans/TD wielders to use impact-explosive TDs at closer ranges
- Bowcaster wielders to alt-fire
- Perhaps allow certain E-11 wielders to fire upon you from very far away
- Perhaps allow gun wielding enemies to climb atop boxes or structures if it's short enough and do it recursively since several maps have interesting non-force-user traversable structures
- Restore Jedi Outcast's more sophisticated ST_Commander behavior
- Make jetpack stormies & hazardtrooper with concussion rifle guys less annoying (not sure how to do this yet, we'll see if this holds up)
- Possibly give some Stormtroopers 1 or 2 thermal detonators (grenades) and use them if they're in a combat point in which it makes sense to do so from (We'll look at what the TD-wielding Gran does when it comes to AI in code). Luckily TD's make a pretty distinctive sound so I am not so worried about physical system feedback when it comes to this planned change (Original idea was from "Seargent Stacker", thank you!)
- Weapon and sniper shot dodge chance according to g_spskill
- A 5th difficulty setting called "Remembrance", should be on 8-12 g_spskill (this cvar seems to scale indefinitely, so that's cool, but we'll also add Remembrance-specific behaviors later. higher g_spskill also doesn't seem to affect enemy AI_Jedi too much from what I can tell from playtesting)
- And more to come...

---

# Installation Instructions

You must already have these things:
- A copy of Jedi Academy and it's assets (This repository will not provide you those things)
- JAEnhanced itself installed into your GameData folder
- A JAEnhanced DLL that exists in GameData/jaenhanced

From this repository's releases page, download the current DLL, and replace your existing JAEnhanced DLL from GameData/JAEnhanced with the one from this repository.
Changes will take effect immediately.

---

# New CVars

Most of these are going to be arbitrary and the defaults are already tuned to what I feel they should be, but I will list them here anyway:
`g_explosivedismemberment` default: 125. Set to 0 for maximum effect.

---

## Attribution from JAEnhanced that I am also putting here because I am pretty sure it is necessary:

## Maintainers (full list: [@JACoders](https://github.com/orgs/JACoders/people))

Leads:

- [Ensiform](https://github.com/ensiform)
- [razor](https://github.com/Razish)
- [Xycaleth](https://github.com/xycaleth)

## Significant contributors ([full list](https://github.com/JACoders/OpenJK/graphs/contributors))

- [bibendovsky](https://github.com/bibendovsky) (save games, platform support)
- [BobaFett](https://github.com/Lrns123)
- [BSzili](https://github.com/BSzili) (JK2, platform support)
- [Cat](https://github.com/deepy) (infra)
- [Didz](https://github.com/dionrhys)
- [eezstreet](https://github.com/eezstreet)
- exidl (SDL2, platform support)



# This software (JAEnhanced: Remembrance) was independently created by a single individual in Salt Lake City, UT. 
# This software is not intended for sale.
# If you paid for this software, you have been scammed.
