# Ashes at the Sphinx
### Oasis of Sia
*Adapted from "Death at the Oasis" (One Night Adventures #ONA-15, Hellebarde Games),
`assets/_raw/Oasis of Sia.../Death_at_the_Oasis_(Levels_2_4).pdf`. Triggers if the party
takes Elmingwed's cooperative offer to reopen the Sia trade route — see
`scenarios/elmingweds-web.md`, Option A.*

**Dramatic question:** *The desert's oldest god doesn't care who's praying to him this
week — the cult, the dead, or the party. Everyone standing in his tomb has to answer to him
on his terms, not theirs.*

**Lore anchors:** [[loc:oasis-of-sia]] · [[subloc:sphinx-sia]] · [[deity:doorne]] ·
[[faction:black-water-cult]] · [[npc:elmingwed]] · [[pc:jiyloo]] · [[npc:feltan]] ·
thread:missing-caravans

---

## Adaptation notes (what's kept, what's changed)

- **The raiders become the Black Water Cult.** The source splits antagonists into Chazim
  slavers (who sacked the oasis) and a separate opportunistic "Cult of Water"/Derivesh
  faction moving in after for the relic. Ajiibwan already has an active, "at full strength"
  antagonist here per the reset (`faction:black-water-cult`) — **consolidate both into one
  Black Water Cult operation**: a raiding party sacked the oasis and took slaves days ago,
  and a stronger retrieval team (with a priest) is due back to collect the relic. It fits
  their name almost too well: reflavor their goal here as one local expression of "the
  Great Design" — reversing desertification by force, in service to Elsrok. Use the
  source's **Derivesh Fanatic/Priest/Subleader stat blocks as-is**, just relabeled.
- **Doorne needs no reskin.** `world/entities.yaml` already has `deity:doorne` (aliases
  include "Doorne") tied directly to `loc:oasis-of-sia` **and to Jiyloo** — Steve had
  already folded this exact module's deity into the compendium. That means **Jiyloo has a
  personal stake in this site** the source doesn't give her: she may be Dorne-faithful, or
  simply raised on "don't rob Doorne's tomb" the way any local would be. Let her push back,
  in-character, if the party starts stripping the temple/tomb for coin.
- **The Scepter of Ice** — keep the mechanics (Staff of Frost + telepathy + burns the
  unfaithful) but consider its irony: an ice relic guarded in the middle of a desert, wanted
  by a *Black Water* cult. That tension is free flavor — lean into it.
- Everything about the tomb's internal guardians (statues, ants, skeletons, the minotaur
  An-Zefful, ghouls, the gargoyle, Sia's wight) is **ancient and faction-blind** — it
  threatens cultists exactly as much as the party. Keep that: it's what makes the "beat the
  cult patrol back" clock genuinely tense rather than a simple race to loot first.

---

## Doorne's Ember — why the raid worked (new lore)

The source doesn't explain why an active holy site sat right next to the tomb and did
nothing while the oasis burned. Here's the answer, invented for this run:

- **Temple al Sia (area 6) keeps a hearth-altar called Doorne's Ember** — a coal that's
  never gone out, said to be a sliver of the sun the god holds in his statue-hand. While lit,
  it wards the whole oasis, not just the temple: Doorne's guardians (the same lineage as the
  Caryatid Columns in 9a, and whatever else still listens in the tomb) sense anyone who means
  the place harm for greed of the tomb's contents, and are moved to act **outside the tomb's
  walls** — not just within them, which is the only place they can normally respond.
- **Ashiq — "the mystic" — disabled it on purpose.** She's the Black Water Cult priest who
  planned this raid and now leads the retrieval patrol (below); reflavor the source's
  unnamed "mystic" as this one person throughout. A day ahead of the main attack, she slipped
  into the temple alone and killed its priest — the source already gives this exact beat
  ("he knew the Inseni would not kill a priest of Doorne"), so keep it, just note her real
  target wasn't the priest, it was the coal. She smothered it in ash and left the temple
  looking untouched (the silver altar and coin lockbox are both still sitting there,
  undisturbed, per the source). Without the Ember lit, the tomb's own guardians stayed
  exactly what they've always been — ancient, faction-blind, dangerous to everyone equally,
  but blind to anything happening outside their own halls. That blindness is what let the
  raid succeed at all.
- **Restoring it.** Sia was entombed with a live fragment of the original hearth-flame — the
  source's "altar with a golden pyramid upon it" in **9p (Tomb of Sia)** is that relic here:
  reflavor it as **Sia's Coal**, a fist-sized golden reliquary that still holds a lit ember
  after centuries (Doorne doesn't let his own fire die). Carrying it back to the temple and
  placing in on the Ember-altar with words spoken over by anyone who genuinely means a prayer
  to Doorne (a cleric, a paladin, Jiyloo, or just someone willing to mean it) will relight it.
- **If it's relit before the patrol returns:** when Ashiq and the retrieval patrol arrive,
  Doorne answers — see the round-by-round guide below. This turns the climax from a second
  dungeon's worth of Fanatics into a real payoff for a side quest, without taking the fight
  away if the party wants one.
- **If it's never restored:** run the patrol straight, full fight, no cavalry — also below.
- **World-state note:** if relit, update `loc:oasis-of-sia`'s status to something like
  "warded — Doorne's Ember restored." That's a real, lasting sandbox change (design
  principle 2) and probably the cleanest payoff available for the reopened trade route —
  Doorne himself is now watching the road.

---

## The clock
Per the source (page 2): the party has **24 hours** from first sighting the ruined oasis
before a Black Water retrieval patrol (5-10 fanatics + a priest, scaling notes on page 2)
arrives to collect the Scepter from the tomb. They'll fight to the death rather than leave
witnesses. If the party is still inside the tomb when the patrol returns to camp and finds
it empty-handed, the patrol *will* come down after them.

The party doesn't need to know this clock exists as GM omniscience — **the sphinx guard
(new beat 2a, below) can tell them.** Capturing and interrogating even one of the dozing
guards left at the sphinx turns "24 hours" from a GM fiat into information the party
actually earned.

## Scene beats

**1 — The ruined oasis (areas 1-8, source pages 3-5).** Burnt tents, bodies, an infested
pond. **Keep this beat exactly as written — it's the best scene in the module:** the
El-Alouph family (Abd, Afara, and daughter Dasara) are hidden in a covered pit near their
wagon shop, alive, starving, with nowhere to go. No fight, no loot — just a decision about
what the party does with three frightened survivors. Don't skip it for the dungeon.

**2 — The Sphinx and the hidden stair (area 9, page 5).** Muddy tracks from the raid lower
the normally-hard Wisdom check to find the entrance between the Sphinx's paws — nice, free
foreshadowing that something's already been through here.

**2a — The sphinx guard (new).** A small contingent of Black Water Cultists — 3-4 — stayed
behind to sit on the tomb entrance while the main raiding party moved on with its slaves.
They're dozing in the sphinx's shade at midday, individually feckless and easy to surprise
(full stats and a short round-by-round guide are in the Combat reference section below).
Capturing rather than killing them is the point: they can be made to give up (1) the
retrieval patrol's ~24-hour timeline, confirmed rather than assumed, and (2) vague, half-
understood gossip that "the mystic" did something to the temple before the attack — the
first thread pulling toward Doorne's Ember, above.

**3 — The tomb (areas 9a-9p, pages 5-10).** Run it room-by-room from the source; the
highlights worth calling out at the table:
- **9c — Hall of the Great God.** The **"Praise Doorne and live"** safe-phrase mechanic is
  already thematically perfect for your Dorne — keep verbatim. Anyone who invokes Doorne's
  names passes unmolested by the animated statues; anyone who doesn't, fights them.
- **9f — An-Zefful, the minotaur guardian.** A real fight, cursed to guard the room and
  hungry for it.
- **9l — the golden scarab.** A cursed treasure (won't let its bearer rest until returned) —
  a fun "obviously don't take this" prop if a player goes for it anyway.
- **9o — the false treasure room.** A trap floor over spikes — telegraph it; this is a
  "clever play rewarded" room, not a gotcha.
- **9p — the Tomb of Sia itself.** Sia's high priest poisoned him and raised him as a
  **wight** to guard the tomb — he attacks the instant the sarcophagus is opened, and holds
  the **Scepter of Ice** plus a genuine fortune (page 10-11 for full treasure and the
  Scepter's stat block).

**4 — The clock lands.** Depending on pacing, either the party clears the tomb and slips
away before the cult patrol arrives (clean win), meets them arriving as the party emerges
(a real fight, possibly with the oasis survivors at risk), or — if they dawdled — gets
caught inside by cultists coming down after them. Any of these is a fine outcome; per
design principle 2, the world doesn't wait on the party's pace.

---

## Combat reference — the tomb

*Stat block conventions (tracker table + reference card, single-die damage encoding, and the
round-by-round GM guide format) are documented once in `dnd/CLAUDE.md` → "Printable stat
blocks." Same paste flow as Durgan's Rest: paste this section into Google Docs as markdown,
then copy the rendered tables straight into the combat sheet.*

*Source conversion note: "Death at the Oasis" was written for Castles & Crusades, not 5e.
Every block below is a from-scratch 5e-ish conversion of the source's C&C stats (AC/HD/HP
carried over close to as-written; attack bonus, damage, and initiative are estimated to fit
the party's level 2-4 range) — treat the numbers as "close enough for a home table," not a
precise port. Flag anything that plays too hard or too soft and I'll adjust.*

*Groups of 4+ identical creatures (ants, skeletons, ghouls) get 2-3 sample tracker rows
instead of one row per instance — paste extras by duplicating the row rather than scrolling
past a dozen identical lines.*

### Round-by-round GM guide — the sphinx guard (beat 2a)

**Surprise round.** The guards are dozing in the sphinx's shade, not braced for a fight.
**Your move:** if the party scouts before engaging (no torches, no shouting), they get a full
surprise round automatically. If they announce themselves instead, run one alert cultist
fumbling for his scimitar rather than a clean ambush either way.

**Round 1 — Drop them fast.** HP 5 each, no real defense — two or three solid hits usually
ends this outright.
**Your move:** this isn't meant to be a fair fight, it's meant to be a fast one. Once half are
down, the rest should be looking for a chance to surrender or bolt, not fight to the last —
that's the "feckless individually" flavor paying off. Let the party choose to kill, capture,
or let one run.

**Round 2+ — Interrogation, not combat.** A captured cultist (or two, played off each other)
will talk — they're not devoted enough to die silent for a schedule they only half understand.
**Your move:** hand over both hooks somewhere in the conversation: the retrieval patrol is
due back within about a day (they're sure of that much), and some fuzzy gossip that "the
mystic" did something to the temple before the attack (they don't know what). Don't make the
party roll for this if they're actually roleplaying the interrogation — reward the scene, not
a Persuasion check.

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Sphinx Guard 1 | 12 | +0 | 5 | +3 | 6 | +1 |
| Sphinx Guard 2 | 12 | +0 | 5 | +3 | 6 | +1 |
| Sphinx Guard 3 | 12 | +0 | 5 | +3 | 6 | +1 |

**Reference card**

**Black Water Cultist** (the sphinx guard) — Medium humanoid, mook
- **Scimitar** +3 to hit, 1d6+1 slashing (the +1 is "Intense Focus," a cult-wide training
  bonus — already baked into Hit Mod and Dmg Mod above).
- **Fanaticism (rules as written, ignore for this scene):** the source says these never
  break morale once fighting starts. Play against it here on purpose — individually they're
  the Black Water Cult's rank and file, lazy and unbothered on guard duty, and will fold fast
  once actually threatened. Save "true fanatic, fights to the death" for Ashiq's patrol below.

### Zombies (areas 1, 3, 9k — same creature, reused across three rooms)

**Tracker** (duplicate this row per zombie active in whichever room you're running)

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Zombie 1 | 12 | -2 | 10 | +2 | 8 | +1 |
| Zombie 2 | 12 | -2 | 10 | +2 | 8 | +1 |

**Reference card**

**Zombie** — Medium undead, mook
- **Slam** +2 to hit, 1d8+1 bludgeoning.
- **Slow:** always acts last in a round regardless of initiative roll — never let one win an
  initiative tie.
- **Mindless undead:** immune to charm/fear/exhaustion, doesn't negotiate, doesn't flee.
- Area 1: two (Jasinia and Amarellen, raised by Ashiq to lie in wait). Area 3: five (former
  inn patrons). Area 9k: four (ancient tomb dead) — these last four are original guardians,
  not Ashiq's work, and won't chase a fleeing party out of the room.

### Mastiff (area 4 — try taming, not fighting)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Mastiff | 13 | +2 | 10 | +4 | 8 | +2 |

**Reference card**

**Mastiff (starving guard dog)** — Medium beast
- **Bite** +4 to hit, 1d8+2 piercing, plus **Trip:** a hit knocks a Medium-or-smaller target
  prone unless it succeeds a STR save.
- **Not actually hostile:** this is the El-Alouph family's trained, domesticated dog, starving
  and desperate, not feral. Food or an Animal Handling-equivalent approach (a Druid's Animal
  Friendship, or just offering rations) calms it instantly — this row only matters if the
  party unties it without a plan and it goes straight for the nearest living thing.

### Water-Claimed Guards (area 7 — Hayawiyya-animated Talifan corpses, four)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Water-Claimed 1 | 14 | +1 | 20 | +4 | 8 | +2 |
| Water-Claimed 2 | 14 | +1 | 20 | +4 | 8 | +2 |
| Water-Claimed 3 | 14 | +1 | 20 | +4 | 8 | +2 |
| Water-Claimed 4 | 14 | +1 | 20 | +4 | 8 | +2 |

**Reference card**

**Water-Claimed Guard** — Medium undead (elemental-possessed corpse)
- **Slam** +4 to hit, 1d8+2 bludgeoning.
- **Animation:** a water elemental spirit (Hayawiyya) is riding this corpse like a puppet —
  kill the body and the spirit dissipates or seeks a new host if one's available nearby.
- **Water affinity:** drawn to water outside combat; won't wander far from the oasis pond.
- **Drowning grab (rare, on a natural 20):** the hit becomes a face-grapple, forcing a
  CON save each round or the target starts suffocating — call this out if you roll a nat 20,
  don't build it into the row's math.
- These four were ordinary Talifan guards until Ashiq's spirits claimed their bodies; there's
  nothing left of the person to negotiate with.

### Lesser Mud Elemental (area 8 — solo, guarding the sunken coffer)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Lesser Mud Elemental | 18 | +0 | 35 | +6 | 10 | +3 |

**Reference card**

**Lesser Mud Elemental** — Large elemental, solo threat
- **Slam** +6 to hit, 1d10+3 bludgeoning.
- **Melded ambush:** stays indistinguishable from the mud bank until someone gets close, then
  attacks — this is a surprise-round monster, not a telegraphed one.
- **Regeneration:** heals a few HP at the start of its turn unless it took fire or acid damage
  since its last turn — mention this if the party is chipping away with non-elemental damage
  and wondering why it's not going down.
- **Weapon resistance:** takes half damage from nonmagical weapons.
- **Won't leave the mud** voluntarily — a party that disengages from the bank is safe.

### Caryatid Columns (area 9a — two, guard the pool hall's inner doors)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Caryatid Column 1 | 14 | +0 | 20 | +4 | 6 | +2 |
| Caryatid Column 2 | 14 | +0 | 20 | +4 | 6 | +2 |

**Reference card**

**Caryatid Column** — Medium construct (animated statue), part of the Brides of Doorne
- **Scimitar** +4 to hit, 1d6+2 slashing.
- **Trigger:** animates and attacks the instant anyone approaches either door **unless**
  someone in the party is visibly wearing/displaying a pyramid symbol of Doorne — no phrase
  needed here, just the symbol (contrast with 9e below, which uses a spoken phrase instead).
- **Won't chase** beyond this hall. Construct: immune to poison, disease, exhaustion, charm,
  fear, sleep.
- These are the same lineage of guardian spirit that (per Doorne's Ember, above) can act
  *outside* the tomb once the Ember is relit — worth a GM callback if the party's already met
  these before reaching the climax.

### Giant Soldier Ants (area 9b — twelve total, two activate per round over six rounds)

**Tracker** (sample rows — duplicate as more ants activate; up to 12 total)

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Giant Ant 1 | 16 | +1 | 10 | +4 | 4 | +1 |
| Giant Ant 2 | 16 | +1 | 10 | +4 | 4 | +1 |

**Reference card**

**Giant Soldier Ant** — Medium beast, mook (activates in waves)
- **Bite** +4 to hit, 1d4+1 piercing.
- **Activation:** all twelve start dormant along the walls; two wake and attack each round
  until all twelve are active (round 6) or the fight ends first. Don't drop all twelve at
  once — the gradual activation is the room's actual threat (attrition), not raw stat block
  difficulty.
- **Acid sting (situational bonus):** on an especially good hit, an ant can add acid damage —
  keep this off the tracker row, call it out narratively on a crit if you want extra bite.
- Fight to the death; any killed are quietly replaced within a few weeks by the room's own
  magic — a detail worth mentioning if the party ever passes back through.

### Skeletal Guardians (area 9d — eight, will chase fleeing PCs)

**Tracker** (sample rows — duplicate up to 8)

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Skeleton 1 | 13 | +0 | 7 | +2 | 6 | +1 |
| Skeleton 2 | 13 | +0 | 7 | +2 | 6 | +1 |
| Skeleton 3 | 13 | +0 | 7 | +2 | 6 | +1 |

**Reference card**

**Skeletal Guardian** — Medium undead, mook
- **Scimitar** +2 to hit, 1d6+1 slashing.
- **Vulnerable to bludgeoning** — worth a heads-up to any player carrying a mace/hammer/staff.
- **Will chase** anyone who runs, unlike most of this tomb's other guardians — the one room
  where retreating doesn't automatically end the encounter.

### Stone Guardian (area 9e — solo, the "Praise Doorne and live" room)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Stone Guardian | 18 | -1 | 24 | +5 | 4 | +2 |

**Reference card**

**Stone Guardian** — Medium construct, solo threat
- **Fists** +5 to hit, 1d4+2 bludgeoning. **Makes two per turn** (roll the row twice).
- **Safe phrase:** anyone who speaks praise to any of Doorne's names ("Doorne the
  All-Knowing," "Mighty Doorne," "Doorne the Omnipotent," "Doorne the Creator") before
  traveling 15+ ft into the room passes unmolested. Said mid-fight, after it's already
  animated, it stops attacking and resets — **unless** it's struck again after the phrase,
  which restarts the fight for good.
- **Resists edged/piercing weapons heavily** (quarter damage); nonmagical missiles do nothing
  and are destroyed; wood weapons have a real chance of breaking on a hit.
- Immune to poison, disease, and mind control; sees invisible creatures. Won't leave the room,
  fights to destruction if provoked past the safe phrase.

### An-Zefful, Minotaur Guardian (area 9f — named solo, real threat)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| An-Zefful | 14 | +0 | 35 | +7 | 8 | +5 |

**Reference card**

**An-Zefful** — Minotaur, cursed guardian, solo boss of this room
- **Battle axe** +7 to hit, 1d8+5 slashing (his default; he always fights with this axe unless
  disarmed).
- **Alt profile if disarmed:** Head Butt + Bite (2d4/1d4) — swap in only if someone actually
  strips his axe away.
- **Powerful Charge (situational):** extra damage if he gets a running start into combat —
  narrate it on round 1 if the room lets him, don't fold it into every hit.
- **Never Surprised.** Has a literal death wish — fights to the death regardless of party
  size, and can't be talked down.
- Cursed to this room specifically: can't follow anyone out, and if magically removed from it
  he simply turns to dust. Killing him is a mercy, not just a fight — worth a line of
  narration when he finally goes down.

### Coffer Corpse (area 9g — solo, guards the rockatrice trap-room)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Coffer Corpse | 12 | -1 | 10 | +3 | 6 | +1 |

**Reference card**

**Coffer Corpse** — Medium undead, solo
- **Clutching hand** +3 to hit, 1d6+1 bludgeoning.
- **Only harmed by magic weapons** — call this out before the fight starts, not after three
  whiffs with a mundane blade.
- **Choke attack (situational):** automatic follow-up damage the round after it hits — keep
  off the row, note it as "if it hit you last round, you're still choking this round."
- Resists turning; won't chase beyond this room.

### Ogre Guardian (area 9h — solo, a "Monster Zombie")

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Ogre Guardian | 12 | -2 | 20 | +4 | 6 | +4 |

**Reference card**

**Ogre Guardian** — Large undead, solo
- **Slam** +4 to hit, 1d6+4 bludgeoning.
- **Slow** (zombie trait): always acts last on an initiative tie.
- Mindless undead immunities as the standard Zombie, above; won't chase past this room.
- The room's citrine "eyes" (22 gems in the walls, 20gp each) are loot, not a hazard — takes
  real time to pry out cleanly.

### Ghoul Guardians (area 9i — four, the dakhma room)

**Tracker** (sample rows — duplicate up to 4)

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Ghoul 1 | 14 | +2 | 10 | +3 | 4 | +1 |
| Ghoul 2 | 14 | +2 | 10 | +3 | 4 | +1 |

**Reference card**

**Ghoul** — Medium undead, mook
- **Claw** +3 to hit, 1d4+1 slashing. **Makes two per turn** (roll the row twice); treat a
  third, rarer bite attack as flavor, not a third roll, unless you want them nastier.
- **Paralysis:** anyone hit by a claw must succeed a STR save or be paralyzed 1d4+1 minutes —
  this is the real danger here, not the damage. Call it out loudly the first time it lands.
- Darkvision; won't chase past this room; fight to destruction.

### Gargoyle (area 9j — solo, one of two statues is real)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Gargoyle | 16 | +0 | 25 | +5 | 6 | +2 |

**Reference card**

**Gargoyle** — Medium monstrosity, solo
- **Bite** +5 to hit, 1d6+2 piercing. Full source stats give it up to four attacks a turn
  (2 claws, bite, gore) — for pace, treat it as **two attacks/round** (roll the row twice);
  use the full four-attack version only if you want this fight to hit harder.
- **Freeze:** looks like an inert statue until it moves — the party likely won't clock it as
  a threat until it's already acting, so consider an automatic surprise round in its favor.
- **Pursues throughout this hallway, but not beyond it.**

### Scarab Beetle Swarm (area 9l — guards the cursed golden scarab)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Scarab Swarm | 16 | +1 | 20 | +3 | 4 | +0 |

**Reference card**

**Scarab Beetle Swarm** — swarm of Tiny beasts, area hazard more than a fair fight
- **Swarming bite** +3 to hit, 1d4 piercing (against whoever's holding the scarab, primarily).
- **Trigger:** pours from the east/west walls the instant someone picks up the golden scarab;
  converges on whoever's holding it. Retreats into the walls at 0 HP.
- **Disease (situational):** a bite can carry disease — this is a status effect, not extra
  damage, so keep it off the row and call it out on a hit.
- The scarab itself is the actual hazard (see scene beats, area 9l) — cursed, won't let its
  bearer rest until it's returned here. This swarm is what makes "just grab it" costly in the
  moment, not just later.

### Dark Creeper (area 9n — nuisance thief, not a real threat)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Dark Creeper | 20 | +3 | 6 | +3 | 6 | +1 |

**Reference card**

**Dark Creeper** — Small fey/humanoid, nuisance
- **Short sword** +3 to hit, 1d6+1 piercing. AC drops to 16 if he's caught in real light.
- **Steals and runs:** grabs the nearest light source and vanishes into shadow rather than
  fighting a real fight.
- **GM note:** let him succeed at least once. This encounter plays better as an annoyance
  ("who's got another torch") than a grind — don't spend more than a round or two on him.

### Sia (area 9p — the Wight, climactic tomb guardian)

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Sia (Wight) | 15 | +1 | 28 | +5 | 6 | +2 |

**Reference card**

**Sia** — Medium undead, solo climax of the tomb
- **Slam** +5 to hit, 1d6+2 bludgeoning.
- **Energy drain (situational, big warning):** a hit can drain vitality rather than just HP —
  don't fold this into the row's average; call it out explicitly the first time it triggers,
  it's meant to be scary.
- **Create spawn (GM discretion):** a humanoid killed by Sia's drain can rise as a new wight —
  a campaign-flavor consequence, not an automatic rule, use only if it serves the story.
- **Trigger:** throws off the sarcophagus lid and attacks the instant anyone opens it. Fights
  relentlessly, chasing anyone who flees — this room doesn't end early.
- Holds the real treasure and the **Scepter of Ice** (below). **Alternate call:** if you want
  Ashiq to have already taken the Scepter during the raid, Sia instead rages about its theft
  the whole fight — your choice, make it before you run this room, not mid-fight.

**Scepter of Ice** — relic, not a creature (no tracker row)
- Functions as a Staff of Frost with one extra power: each morning, a faithful bearer who
  offers thanks to Doorne facing east restores one charge (max one restoration/day). Runs dry
  at zero charges until surrendered by whoever drained it, then recharges naturally at one
  charge/day.
- **Non-faithful bearers take 4d6 cold damage on touch**, and another 4d6 next round if not
  dropped immediately — this is a real hazard for a party member who grabs it without
  thinking, not just flavor text.
- Worth 30,000 gp, but far too recognizable to fence locally, and Jiyloo will be dismayed and
  adversarial toward any attempt to remove it from the temple (per Adaptation notes, above).

### Round-by-round GM guide — the patrol returns

**Setup.** Roughly 24 hours after the party first sights the ruined oasis (or per the source:
24 hrs to arrival, ~5 hrs inside the tomb, then rest before departing), **Ashiq and 5-10
(d6+4) Black Water Fanatics** arrive at the sphinx and head straight for the stair. If the
party's still inside, the patrol comes down after them; if the party's already gone, they
search the tomb, then the oasis, for tracks.
**Your move:** if the party captured or killed the sphinx guards (beat 2a) earlier, the
patrol notices their absence immediately and arrives ready for a fight — no surprise round
for the party this time.

**If Doorne's Ember is relit (see above):**
- **Round 1 — Doorne answers.** As the patrol crosses onto the temple grounds or the sphinx's
  plinth, the ward triggers: stone stirs, sand rises, whatever guardians are still standing
  (or new ones — your call) converge on the patrol from *outside* the tomb, somewhere they've
  never had reason to act before.
  **Your move:** this is the payoff beat — make it big and short, not a second dungeon crawl.
  The patrol should break within a round or two of real fighting. Let the party wade in if
  they want to, but don't require it.
- **Round 2+ — Mop-up or mercy.** Survivors flee or surrender; Ashiq, if she's still standing,
  is the one worth catching — she's the only one who actually knows what was done to the
  Ember and why.
  **Your move:** Ashiq is the actual prize here, not the Scepter. Treat her the way Maghiel's
  escape was treated in Durgan's Rest (a name/lead worth chasing) — except this time, if the
  ward did its job, she can plausibly be caught.

**If Doorne's Ember was never restored:**
- **Round 1 — A real fight.** No cavalry. Run the patrol as written below — Ashiq supports
  from the back, the Fanatics push the front line, and nobody breaks morale (Fanaticism:
  Derivesh/Black Water fanatics never check it).
  **Your move:** they were "instructed not to leave witnesses" — that's real pressure, not
  flavor text. A party that loses ground here should feel it.
- **Round 2+ — Ashiq's exit.** If the fight turns against the patrol, Ashiq disengages rather
  than dies for a lost cause — she has no Maghiel-style hard-rail escape, so if the party
  corners her, let her be caught.
  **Your move:** if she gets away, she's a loose thread pointing at the wider Black Water Cult
  operation — a hook, not a dead end.

**Tracker**

| Name | AC | Init Mod | HP | Hit Mod | Dmg Die | Dmg Mod |
|---|---|---|---|---|---|---|
| Ashiq | 16 | +0 | 20 | +3 | 6 | +1 |
| Black Water Fanatic 1 | 15 | +1 | 11 | +4 | 6 | +2 |
| Black Water Fanatic 2 | 15 | +1 | 11 | +4 | 6 | +2 |
| Black Water Fanatic 3 | 15 | +1 | 11 | +4 | 6 | +2 |
| Black Water Fanatic 4 | 15 | +1 | 11 | +4 | 6 | +2 |
| Black Water Fanatic 5 | 15 | +1 | 11 | +4 | 6 | +2 |

*Roll d6+4 for the actual fanatic count at the table (5-10); the five rows above cover the
low end — duplicate the Fanatic row for any beyond five.*

**Reference cards**

**Ashiq, "the mystic"** — Black Water Cult priest, classed NPC — *support caster, not a
striker*
- Default attack: **Light Mace** +3 to hit, 1d6+1 bludgeoning. She'd rather cast.
- **Prepared spells (support-focused, no direct-damage option):** Detect Magic, Endure
  Elements, First Aid, Light, Cure Wounds (x2), Resist Elements (x2), Aid, Silence.
- **Tactics:** buffs and heals the Fanatics rather than fighting directly — Aid/Resist
  Elements/Shield-of-Faith-equivalent before the front line engages, Cure Wounds mid-fight,
  Silence on whichever PC caster is causing the most trouble.
- Wears a **+1 mail hauberk** (already reflected in her AC above) and carries 100 gp.
- She orchestrated the entire raid — zombies, the mud elemental, the animated Talifan
  corpses — and personally disabled Doorne's Ember (see above). If captured, she's the one
  person who can confirm all of it.

**Black Water Fanatic** (×5-10) — mook, Derivesh-lineage rank-and-file
- **Scimitar** +4 to hit, 1d6+2 slashing (includes Intense Focus, already baked in).
- **Fanaticism:** never checks morale, never breaks — unlike the sphinx guard (beat 2a), play
  these straight. This is the real fight the source promises.

---

## Rewards & consequences
- The Scepter of Ice is worth **30,000 gp** but is far
  too recognizable to sell to any local merchant, and Jiyloo would be absolutely dismayed and adversarial to any attempt to remove it from the temple.
- Resolving this **pays off `thread:missing-caravans`** (Feltan's standing reward for the
  vanished western-route caravans) and satisfies Elmingwed's actual want — the trade route
  reopened.
- **Black Water Cult activity confirmed this close to Tel A'bib** is a genuine escalation
  worth surfacing to Elmingwed and, eventually, the wider setting — this is the same faction
  behind the Kantaroz demon-summoning's larger stakes (per `faction:black-water-cult`'s
  world-level "Great Design"), even though the two threads haven't touched yet.
- The El-Alouph family's fate (taken in by the party, sent to Tel A'bib, left to fend for
  themselves) is a small but real character beat worth tracking if it lands.
- **If Doorne's Ember is restored:** the oasis gets a real, lasting upgrade — Doorne's own
  guardians now watch the road, not just the tomb. This is arguably a better long-term reward
  than the Scepter for a party that can't easily fence a 30,000 gp relic anyway.
- **Ashiq**, captured or escaped, is a loose thread into the wider Black Water Cult
  operation — she personally orchestrated this raid and knows more about "the Great Design"
  than any rank-and-file cultist would.

## Post-game seeds
- **thread:missing-caravans → `resolved`** (or partially, if the cult patrol survives to
  retaliate later).
- **thread:elmingwed-deal** warms further — the route's open, the job's done.
- Note Jiyloo's reaction if the party looted the temple against her wishes — a seed for
  friction or a changed disposition toward the party going forward.
- **If Doorne's Ember was relit:** update `loc:oasis-of-sia`'s status in `world/entities.yaml`
  to reflect the ward — e.g. "cleared of Black Water Cult; warded by a restored Doorne's
  Ember." A concrete, lasting sandbox change per design principle 2.
- **Ashiq → new thread candidate** (`thread:ashiq-black-water`, GM's call whether to formalize
  it) if she escapes: a named Black Water Cult operative the party has personally crossed,
  independent of the Maghiel/Bridged City thread.
