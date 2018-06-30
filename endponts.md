# HOTS Hero End Points
Base URL: `http://hotsapi.net/api/v1`

## All Heroes
`/heroes`

Returns list of all hero information


## Hero Details
`/heroes/{hero}`

`/heroes/abathur`

Returns details of a specified hero

<details><summary>**Example**</summary>

```javascript
{
  "name": "Abathur",
  "short_name": "abathur",
  "attribute_id": "Abat",
  "translations": [
    "abatur", "абатур", "아바투르", "阿巴瑟", "abathur"
  ],
  "role": "Specialist",
  "type": "Melee",
  "release_date": "2014-03-13",
  "icon_url": {
    "92x93": "http://s3.hotsapi.net/img/heroes/92x93/abathur.png"
  },
  "abilities": [
    {
      "owner": "Abathur",
      "name": "Q1",
      "title": "Symbiote",
      "description": "Assist another allied Unit or Combat Structure, allowing you to shield them and use new Abilities.  Cannot be used on another Hero's Summons.",
      "icon": null,
      "hotkey": "Q",
      "cooldown": 4,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "Abathur",
      "name": "W1",
      "title": "Toxic Nest",
      "description": "Spawn a mine that becomes active after a short time. Deals 153 (+4% per level) damage and reveals the enemy for 4 seconds. Lasts 90 seconds.",
      "icon": null,
      "hotkey": "W",
      "cooldown": 10,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "Abathur",
      "name": "R1",
      "title": "Evolve Monstrosity",
      "description": "Turn an allied Minion or Locust into a Monstrosity. When enemy Minions near the Monstrosity die, it gains 5% Health and 5% Basic Attack damage, stacking up to 40 times.  The Monstrosity takes 50% less damage from non-Heroic enemies.  Using Symbiote on the Monstrosity allows Abathur to control it, in addition to Symbiote's normal benefits.  This Ability can be reactivated to automatically cast Symbiote on his Monstrosity.",
      "icon": null,
      "hotkey": "R",
      "cooldown": 90,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "Abathur",
      "name": "R2",
      "title": "Ultimate Evolution",
      "description": "Clone target allied Hero and control it for 20 seconds. Abathur has perfected the clone, granting it 20% Spell Power, 20% bonus Attack Damage, and 10% bonus Movement Speed. Cannot use their Heroic Ability.",
      "icon": null,
      "hotkey": "R",
      "cooldown": 70,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "Abathur",
      "name": "D1",
      "title": "Locust Strain",
      "description": "Spawns a Locust to attack down the nearest lane every 15 seconds. Locusts last for 25 seconds.",
      "icon": null,
      "hotkey": null,
      "cooldown": 15,
      "mana_cost": null,
      "trait": true
    }, {
      "owner": "Abathur",
      "name": "Z1",
      "title": "Deep Tunnel",
      "description": "Quickly tunnel to a visible location",
      "icon": null,
      "hotkey": "Z",
      "cooldown": 30,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "AbathurSymbiote",
      "name": "Q2",
      "title": "Stab",
      "description": "Shoots a spike towards target area that deals 119 (+4% per level) damage to the first enemy it contacts.",
      "icon": null,
      "hotkey": "Q",
      "cooldown": 3,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "AbathurSymbiote",
      "name": "W2",
      "title": "Spike Burst",
      "description": "Deals 120 (+4% per level) damage to nearby enemies.",
      "icon": null,
      "hotkey": "W",
      "cooldown": 6,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "AbathurSymbiote",
      "name": "E1",
      "title": "Carapace",
      "description": "Shields the assisted ally for 157 (+4% per level). Lasts for 8 seconds.",
      "icon": null,
      "hotkey": "E",
      "cooldown": 12,
      "mana_cost": null,
      "trait": false
    }, {
      "owner": "AbathurSymbiote",
      "name": "R3",
      "title": "Cancel Symbiote",
      "description": "Cancels the Symbiote ability. Releases your ally and returns to controlling Abathur.",
      "icon": null,
      "hotkey": "R",
      "cooldown": 2,
      "mana_cost": null,
      "trait": false
    }
  ],
  "talents": [
    {
      "name": "AbathurCombatStyleSurvivalInstincts",
      "title": "Survival Instincts",
      "description": "Increases Locust's Health by 40% and duration by 40%.",
      "icon": "storm_ui_icon_abathur_spawnlocust.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spawnlocust.png"
      },
      "ability": "D1",
      "sort": 2,
      "cooldown": null,
      "mana_cost": null,
      "level": 1
    }, {
      "name": "AbathurMasteryBallistospores",
      "title": "Ballistospores",
      "description": "Increases Toxic Nest's range to global and increases duration by 25%.",
      "icon": "storm_ui_icon_abathur_toxicnest_var1.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_toxicnest_var1.png"
      },
      "ability": "W1",
      "sort": 2,
      "cooldown": null,
      "mana_cost": null,
      "level": 4
    }, {
      "name": "AbathurMasteryVileNestsToxicNest",
      "title": "Vile Nest",
      "description": "Toxic Nests slow enemy Movement Speed by 40% for 2.5 seconds.",
      "icon": "storm_ui_icon_abathur_toxicnest.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_toxicnest.png"
      },
      "ability": "W1",
      "sort": 2,
      "cooldown": null,
      "mana_cost": null,
      "level": 7
    }, {
      "name": "AbathurHeroicAbilityUltimateEvolution",
      "title": "Ultimate Evolution",
      "description": "Clone target allied Hero and control it for 20 seconds. Abathur has perfected the clone, granting it 20% Spell Power, 20% bonus Attack Damage, and 10% bonus Movement Speed. Cannot use their Heroic Ability.",
      "icon": "storm_ui_icon_abathur_ultimateevolution.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_ultimateevolution.png"
      },
      "ability": "R2",
      "sort": 1,
      "cooldown": 70,
      "mana_cost": null,
      "level": 10
    }, {
      "name": "AbathurCombatStyleBombardStrain",
      "title": "Bombard Strain",
      "description": "Locust's Basic Attacks become a long-range siege attack that deal 70% more damage.",
      "icon": "storm_ui_icon_abathur_spawnlocust_var1.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spawnlocust_var1.png"
      },
      "ability": "D1",
      "sort": 2,
      "cooldown": null,
      "mana_cost": null,
      "level": 13
    }, {
      "name": "AbathurCombatStyleLocustBrood",
      "title": "Locust Brood",
      "description": "Activate to spawn 3 Locusts at a nearby location.",
      "icon": "storm_ui_icon_abathur_spawnlocust.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spawnlocust.png"
      },
      "ability": "Active",
      "sort": 3,
      "cooldown": 45,
      "mana_cost": null,
      "level": 16
    }, {
      "name": "AbathurMasteryEnvenomedNestsToxicNest",
      "title": "Envenomed Nest",
      "description": "Toxic Nests deal 75% more damage over 3 seconds.",
      "icon": "storm_ui_icon_abathur_toxicnest.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_toxicnest.png"
      },
      "ability": "W1",
      "sort": 4,
      "cooldown": null,
      "mana_cost": null,
      "level": 1
    }, {
      "name": "AbathurMasteryProlificDispersal",
      "title": "Prolific Dispersal",
      "description": "Reduces the cooldown of Toxic Nest by 2 seconds and adds 2 additional charges.",
      "icon": "storm_ui_icon_abathur_toxicnest.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_toxicnest.png"
      },
      "ability": "W1",
      "sort": 1,
      "cooldown": null,
      "mana_cost": null,
      "level": 4
    }, {
      "name": "AbathurMasteryPressurizedGlands",
      "title": "Pressurized Glands",
      "description": "Increases the range of Symbiote's Spike Burst by 25% and decreases the cooldown by 1 second.",
      "icon": "storm_ui_icon_abathur_spikeburst.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spikeburst.png"
      },
      "ability": "W2",
      "sort": 1,
      "cooldown": null,
      "mana_cost": null,
      "level": 1
    }, {
      "name": "GenericTalentCalldownMULE",
      "title": "Calldown: MULE",
      "description": "Activate to calldown a Mule that repairs Structures, one at a time, near target point for 40 seconds, healing for 100 Health every 1 second.",
      "icon": "storm_ui_icon_talent_mule.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_talent_mule.png"
      },
      "ability": "Active",
      "sort": 4,
      "cooldown": 60,
      "mana_cost": null,
      "level": 7
    }, {
      "name": "AbathurMasteryLocustMaster",
      "title": "Locust Nest",
      "description": "Activate to create a nest that periodically spawns Locusts. Only one Locust Nest can be active at a time.",
      "icon": "storm_ui_icon_abathur_locustnest.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_locustnest.png"
      },
      "ability": "Active",
      "sort": 4,
      "cooldown": 45,
      "mana_cost": null,
      "level": 20
    }, {
      "name": "AbathurSymbioteAdrenalOverload",
      "title": "Adrenal Overload",
      "description": "Heroic Symbiote hosts gain 25% increased Attack Speed.",
      "icon": "storm_ui_icon_abathur_symbiote.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_symbiote.png"
      },
      "ability": "Q1",
      "sort": 4,
      "cooldown": null,
      "mana_cost": null,
      "level": 4
    }, {
      "name": "AbathurMasteryNeedlespine",
      "title": "Needlespine",
      "description": "Increases the damage and range of Symbiote's Stab by 20%.",
      "icon": "storm_ui_icon_abathur_stab.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_stab.png"
      },
      "ability": "Q2",
      "sort": 1,
      "cooldown": null,
      "mana_cost": null,
      "level": 7
    }, {
      "name": "AbathurHeroicAbilityEvolveMonstrosity",
      "title": "Evolve Monstrosity",
      "description": "Turn an allied Minion or Locust into a Monstrosity. When enemy Minions near the Monstrosity die, it gains 5% Health and 5% Basic Attack damage, stacking up to 40 times.  The Monstrosity takes 50% less damage from non-Heroic enemies.  Using Symbiote on the Monstrosity allows Abathur to control it, in addition to Symbiote's normal benefits.  This Ability can be reactivated to automatically cast Symbiote on his Monstrosity.",
      "icon": "storm_ui_icon_abathur_evolvemonstrosity.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_evolvemonstrosity.png"
      },
      "ability": "R1",
      "sort": 2,
      "cooldown": 90,
      "mana_cost": null,
      "level": 10
    }, {
      "name": "AbathurSymbioteSpikeBurstSomaTransference",
      "title": "Soma Transference",
      "description": "Symbiote's Spike Burst heals the host for 64 (+4% per level) Health per enemy Hero hit.",
      "icon": "storm_ui_icon_abathur_spikeburst.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spikeburst.png"
      },
      "ability": "W2",
      "sort": 4,
      "cooldown": null,
      "mana_cost": null,
      "level": 13
    }, {
      "name": "AbathurSymbioteHivemind",
      "title": "Hivemind",
      "description": "Symbiote creates an additional Symbiote on a nearby allied Hero.  This Symbiote mimics the commands of the first, but does half damage and shielding.",
      "icon": "storm_ui_icon_abathur_symbiote.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_symbiote.png"
      },
      "ability": "Q1",
      "sort": 3,
      "cooldown": null,
      "mana_cost": null,
      "level": 20
    }, {
      "name": "AbathurMasteryRegenerativeMicrobes",
      "title": "Regenerative Microbes",
      "description": "Symbiote's Carapace heals the target for 68 (+4% per level) Health per second over 4 seconds.",
      "icon": "storm_ui_icon_abathur_carapace.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_carapace.png"
      },
      "ability": "E1",
      "sort": 3,
      "cooldown": null,
      "mana_cost": null,
      "level": 1
    }, {
      "name": "AbathurSymbioteCarapaceSustainedCarapace",
      "title": "Sustained Carapace",
      "description": "Increases the Shield amount of Symbiote's Carapace by 40% and allows it to persist after Symbiote ends.",
      "icon": "storm_ui_icon_abathur_carapace.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_carapace.png"
      },
      "ability": "E1",
      "sort": 3,
      "cooldown": null,
      "mana_cost": null,
      "level": 4
    }, {
      "name": "AbathurMasteryAdrenalineBoost",
      "title": "Adrenaline Boost",
      "description": "Symbiote's Carapace increases the Movement Speed of the target by 40% for 3.5 seconds.",
      "icon": "storm_ui_icon_abathur_carapace.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_carapace.png"
      },
      "ability": "E1",
      "sort": 2,
      "cooldown": null,
      "mana_cost": null,
      "level": 16
    }, {
      "name": "AbathurCombatStyleAssaultStrain",
      "title": "Assault Strain",
      "description": "Locust Basic Attacks cleave for 50% damage, and explode on death for 102 (+4% per level) damage.",
      "icon": "storm_ui_icon_abathur_spawnlocust.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spawnlocust.png"
      },
      "ability": "D1",
      "sort": 1,
      "cooldown": null,
      "mana_cost": null,
      "level": 13
    }, {
      "name": "AbathurMasterySpatialEfficiency",
      "title": "Spatial Efficiency",
      "description": "Symbiote's Stab gains 1 additional charge and its Cooldown is reduced by .5 seconds.",
      "icon": "storm_ui_icon_abathur_stab.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_stab.png"
      },
      "ability": "Q2",
      "sort": 3,
      "cooldown": null,
      "mana_cost": null,
      "level": 13
    }, {
      "name": "AbathurMasteryEnvenomedSpikes",
      "title": "Envenomed Spikes",
      "description": "Abathur's Symbiote's Spike Burst also slows enemy Movement Speed by 40% for 2 seconds.",
      "icon": "storm_ui_icon_abathur_spikeburst.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_spikeburst.png"
      },
      "ability": "W2",
      "sort": 1,
      "cooldown": null,
      "mana_cost": null,
      "level": 16
    }, {
      "name": "AbathurSymbioteCarapaceNetworkedCarapace",
      "title": "Networked Carapace",
      "description": "Using Symbiote's Carapace also applies an untalented Carapace Shield to all nearby allied Heroes, Minions, and Mercenaries.",
      "icon": "storm_ui_icon_abathur_carapace.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_carapace.png"
      },
      "ability": "E1",
      "sort": 3,
      "cooldown": null,
      "mana_cost": null,
      "level": 7
    }, {
      "name": "AbathurVolatileMutation",
      "title": "Volatile Mutation",
      "description": "Ultimate Evolution clones and Monstrosities deal 137 (+4% per level) damage to nearby enemies every 3 seconds and when they die.",
      "icon": "storm_ui_icon_abathur_volatilemutation.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_volatilemutation.png"
      },
      "ability": "R1",
      "sort": 4,
      "cooldown": null,
      "mana_cost": null,
      "level": 16
    }, {
      "name": "AbathurUltimateEvolutionEvolutionaryLink",
      "title": "Evolutionary Link",
      "description": "As long as the Ultimate Evolution is alive, the original target of the clone gains a Shield equal to 25% of their maximum Health.  Refreshes every 5 seconds.",
      "icon": "storm_ui_icon_abathur_ultimateevolution.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_ultimateevolution.png"
      },
      "ability": "R2",
      "sort": 1,
      "cooldown": null,
      "mana_cost": null,
      "level": 20
    }, {
      "name": "AbathurMasteryEvolutionComplete",
      "title": "Evolution Complete",
      "description": "Monstrosity gains the ability to Deep Tunnel to any visible location once every 25 seconds.",
      "icon": "storm_ui_icon_abathur_evolvemonstrosity.png",
      "icon_url": {
        "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_evolvemonstrosity.png"
      },
      "ability": "R1",
      "sort": 2,
      "cooldown": null,
      "mana_cost": null,
      "level": 20
    }
  ]
}
```
</details>

## Hero Ability Details
`/heroes/{hero}/abilities/{ability}`

`/heroes/abathur/abilities/Q2`

Returns details of the specified ability

<details><summary>**Example**</summary>

```javascript
{
"owner": "AbathurSymbiote",
"name": "Q2",
"title": "Stab",
"description": "Shoots a spike towards target area that deals 119 (+4% per level) damage to the first enemy it contacts.",
"icon": null,
"hotkey": "Q",
"cooldown": 3,
"mana_cost": null,
"trait": false
}
```
</details>

## Talent Details
`/talents/{talent}`

`/talents/AbathurHeroicAbilityUltimateEvolution`

Returns details of the specified talent

<details><summary>**Example**</summary>

```javascript
{
  "name": "AbathurHeroicAbilityUltimateEvolution",
  "title": "Ultimate Evolution",
  "description": "Clone target allied Hero and control it for 20 seconds. Abathur has perfected the clone, granting it 20% Spell Power, 20% bonus Attack Damage, and 10% bonus Movement Speed. Cannot use their Heroic Ability.",
  "icon": "storm_ui_icon_abathur_ultimateevolution.png",
  "icon_url": {
    "64x64": "http://s3.hotsapi.net/img/talents/64x64/storm_ui_icon_abathur_ultimateevolution.png"
  },
  "ability": "R2",
  "sort": 1,
  "cooldown": 70,
  "mana_cost": null,
  "level": 10,
  "heroes": ["Abathur"]
}
```
</details>

## Notes:
**Abilities:**

Abilities are named based on the default hotkeys.
```javascript
Q, W, E, R, Z, D
```

They are then subdivided by appending a number to the end to distinguish between different states of the ability. For example, Abathur's Symbiote then has specific abilities once a target has been selected.

```javascript
"name": "Q1",
"title": "Symbiote"

"name": "Q2",
"title": "Stab"

"name": "W2",
"title": "Spike Burst"

"name": "E1"
"title": "Carapace",
```
Notice there is no `E2`. Abathur has no `E` ability outside of Symbiote, therefore Abathur only has one E ability.
