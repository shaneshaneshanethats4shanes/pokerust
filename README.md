# Pokémon Rust

**Pokémon Rust** is a ROM hack of **Pokémon Red**, designed as a hard-mode challenge with roguelike elements.

It has been extensively playtested by myself and friends using both emulators and actual hardware.

<img width="480" height="432" alt="Title screen" src="https://github.com/user-attachments/assets/f8555543-cae8-4434-855d-49b976e9b1ae" />

---

## Major Changes

- **Reworked Pokémon learnsets**  
  All Pokémon have had their level-up learnsets adjusted to make battles more challenging. See the [Pokédex](#pokédex) below.
- **Reworked trainer teams**  
  Trainer and Gym Leader teams have been adjusted to provide a greater challenge.
- **No grinding**  
  Experience is only gained from trainer battles.
- **Party-wide EXP**  
  Experience is shared equally among your entire party. Every Pokémon receives 100% of the experience, even if it is KO'd.
- **Set battle mode**  
  The only available battle mode is **Set**. You cannot switch Pokémon when your opponent sends out a new Pokémon.
- **Restricted saving**  
  The only way to create a permanent save is by healing at a Pokémon Center. Saving happens automatically when healing.
- **Pokémon Center restrictions**  
  You cannot save or heal at any of the **last three Pokémon Centers you've used**. Plan your route carefully.
- **Quicksave**  
  Select **Q-SAVE** from the Start menu to create a temporary save and quit the game. Loading the game deletes the quicksave. You must create another quicksave afterwards, otherwise the game will return you to your last permanent save on the next load.
- **Blackouts**  
  If you black out, the game restarts from your last permanent save.
- **Gym Leader / Giovanni healing**  
  Defeating a Gym Leader or Giovanni fully heals your party.

<img width="479" height="432" alt="image" src="https://github.com/user-attachments/assets/c1827d5d-e952-41a2-9efb-38f630c9f888" />



## Other Changes

- **Fly removed**  
  The Fly HM isn't available until the end of the game (speak to Professor Oak).
- **Major glitches patched**  
  The **Trainer-Fly glitch** and **MissingNo.** exploits are no longer possible.
- **Trade evolution NPC**  
  An NPC in the Celadon Department Store will trade you for any Pokémon and immediately trade it back. This allows Pokémon that normally require trading to evolve.
- **Poké Flute reworked**  
  The Poké Flute can no longer be used during battle, but can still wake sleeping Pokémon in the overworld.
- **Safari Zone reworked**  
  **Bait** reduces the likelihood that a Pokémon will flee, while **rocks** increase its catch rate. This makes Safari Zone encounters less dependent on luck (it's completely broken in the original game).
- **Cable Club removed**  
  The Cable Club isn't available until the end of the game (to avoid possible exploits).
- **PC Boxes restricted**  
  All PC Boxes except **Box 1** have been removed for the same reason. Additional boxes may be added in the future.
- **Route restrictions**  
  Certain routes have been blocked off or made accessible only from specific directions to increase difficulty.

> There are many other changes throughout the game, but these are the most important ones to be aware of.

---

## Instructions

To build the ROM, apply [Pokemon Rust.ips](https://github.com/shaneshaneshanethats4shanes/pokerust/releases/download/v1.0.0/Pokemon.Rust.ips) to a Pokémon Red ROM using a patcher such as [ROM Patcher JS](https://www.marcrobledo.com/RomPatcher.js/). This will create a patched ROM that you can play in any Game Boy emulator.

---

# Pokédex

> **Note:** Only moves learned by **leveling up** have been changed. Moves learned via TM are unchanged.

<details>
<summary><strong>001–003 · Bulbasaur → Venusaur</strong></summary>

### 001 · Bulbasaur

| Level | Move |
|---:|---|
| 7 | Poisonpowder |
| 13 | Razor Leaf |
| 22 | Growth |
| 30 | Sleep Powder |
| 38 | Solarbeam |
| 43 | Hyper Beam |
| 45 | Swords Dance |

### 003 · Venusaur

| Level | Move |
|---:|---|
| 7 | Poisonpowder |
| 13 | Razor Leaf |
| 22 | Growth |
| 30 | Sleep Powder |
| 38 | Solarbeam |
| 43 | Hyper Beam |
| 45 | Swords Dance |

</details>

<details>
<summary><strong>004–006 · Charmander → Charizard</strong></summary>

### 004 · Charmander

| Level | Move |
|---:|---|
| 9 | Flamethrower |
| 15 | Slash |
| 24 | Fire Blast |
| 33 | Body Slam |
| 42 | Swords Dance |
| 45 | Earthquake |

### 006 · Charizard

| Level | Move |
|---:|---|
| 9 | Flamethrower |
| 15 | Slash |
| 24 | Fire Blast |
| 33 | Body Slam |
| 42 | Swords Dance |
| 45 | Earthquake |

</details>

<details>
<summary><strong>007–009 · Squirtle → Blastoise</strong></summary>

### 007 · Squirtle

| Level | Move |
|---:|---|
| 8 | Bite |
| 15 | Withdraw |
| 22 | Skull Bash |
| 28 | Hydro Pump |
| 35 | Seismic Toss |
| 42 | Counter |
| 45 | Body Slam |

### 009 · Blastoise

| Level | Move |
|---:|---|
| 8 | Bite |
| 15 | Withdraw |
| 22 | Skull Bash |
| 28 | Hydro Pump |
| 35 | Seismic Toss |
| 42 | Counter |
| 45 | Body Slam |

</details>

<details>
<summary><strong>010–012 · Caterpie → Butterfree</strong></summary>

### 010 · Caterpie

| Level | Move |
|---:|---|
| 9 | Confusion |
| 10 | Poisonpowder |
| 11 | Stun Spore |
| 12 | Sleep Powder |
| 16 | Supersonic |
| 21 | Whirlwind |
| 27 | Psybeam |
| 35 | Psychic |
| 43 | Double Edge |

### 012 · Butterfree

| Level | Move |
|---:|---|
| 9 | Confusion |
| 10 | Poisonpowder |
| 11 | Stun Spore |
| 12 | Sleep Powder |
| 16 | Supersonic |
| 21 | Whirlwind |
| 27 | Psybeam |
| 35 | Psychic |
| 43 | Double Edge |

</details>

<details>
<summary><strong>013–015 · Weedle → Beedrill</strong></summary>

### 013 · Weedle

| Level | Move |
|---:|---|
| 7 | Fury Attack |
| 11 | Focus Energy |
| 15 | Twineedle |
| 20 | Rage |
| 25 | Pin Missile |
| 30 | Agility |
| 35 | Swords Dance |
| 40 | Hyper Beam |

### 015 · Beedrill

| Level | Move |
|---:|---|
| 7 | Fury Attack |
| 11 | Focus Energy |
| 15 | Pin Missile |
| 20 | Rage |
| 25 | Twineedle |
| 30 | Agility |
| 35 | Swords Dance |
| 40 | Hyper Beam |

</details>

<details>
<summary><strong>016–018 · Pidgey → Pidgeot</strong></summary>

### 016 · Pidgey

| Level | Move |
|---:|---|
| 5 | Quick Attack |
| 10 | Whirlwind |
| 15 | Wing Attack |
| 20 | Agility |
| 25 | Mirror Move |
| 30 | Double Edge |
| 35 | Hyper Beam |
| 40 | Reflect |

### 018 · Pidgeot

| Level | Move |
|---:|---|
| 5 | Quick Attack |
| 10 | Whirlwind |
| 15 | Wing Attack |
| 20 | Agility |
| 25 | Mirror Move |
| 30 | Double Edge |
| 35 | Hyper Beam |
| 40 | Reflect |

</details>

<details>
<summary><strong>019–020 · Rattata → Raticate</strong></summary>

### 019 · Rattata

| Level | Move |
|---:|---|
| 5 | Quick Attack |
| 12 | Hyper Fang |
| 17 | Thunderbolt |
| 25 | Focus Energy |
| 32 | Body Slam |
| 39 | Super Fang |
| 45 | Hyper Beam |

### 020 · Raticate

| Level | Move |
|---:|---|
| 5 | Quick Attack |
| 12 | Hyper Fang |
| 17 | Thunderbolt |
| 25 | Focus Energy |
| 32 | Body Slam |
| 39 | Super Fang |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>021–022 · Spearow → Fearow</strong></summary>

### 021 · Spearow

| Level | Move |
|---:|---|
| 9 | Leer |
| 15 | Fury Attack |
| 22 | Mirror Move |
| 29 | Drill Peck |
| 36 | Agility |
| 41 | Hyper Beam |
| 45 | Double Edge |

### 022 · Fearow

| Level | Move |
|---:|---|
| 9 | Leer |
| 15 | Fury Attack |
| 22 | Mirror Move |
| 29 | Drill Peck |
| 36 | Agility |
| 41 | Hyper Beam |
| 45 | Double Edge |

</details>

<details>
<summary><strong>023–024 · Ekans → Arbok</strong></summary>

### 023 · Ekans

| Level | Move |
|---:|---|
| 10 | Poison Sting |
| 17 | Bite |
| 24 | Screech |
| 31 | Glare |
| 38 | Wrap |
| 42 | Earthquake |
| 45 | Hyper Beam |

### 024 · Arbok

| Level | Move |
|---:|---|
| 10 | Poison Sting |
| 17 | Bite |
| 24 | Screech |
| 31 | Glare |
| 38 | Wrap |
| 42 | Earthquake |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>025–026 · Pikachu → Raichu</strong></summary>

### 025 · Pikachu

| Level | Move |
|---:|---|
| 9 | Thunder Wave |
| 16 | Quick Attack |
| 23 | Swift |
| 28 | Body Slam |
| 33 | Agility |
| 43 | Thunderbolt |

### 026 · Raichu

| Level | Move |
|---:|---|
| 9 | Thunder Wave |
| 16 | Quick Attack |
| 23 | Swift |
| 28 | Body Slam |
| 33 | Agility |
| 43 | Thunderbolt |

</details>

<details>
<summary><strong>027–028 · Sandshrew → Sandslash</strong></summary>

### 027 · Sandshrew

| Level | Move |
|---:|---|
| 10 | Sand Attack |
| 17 | Slash |
| 24 | Rock Slide |
| 31 | Substitute |
| 38 | Swords Dance |
| 45 | Earthquake |

### 028 · Sandslash

| Level | Move |
|---:|---|
| 10 | Sand Attack |
| 17 | Slash |
| 24 | Rock Slide |
| 31 | Substitute |
| 38 | Swords Dance |
| 45 | Earthquake |

</details>

<details>
<summary><strong>029–031 · Nidoran♀ → Nidoqueen</strong></summary>

### 029 · Nidoran♀

| Level | Move |
|---:|---|
| 8 | Scratch |
| 14 | Poison Sting |
| 20 | Body Slam |
| 26 | Earthquake |
| 32 | Blizzard |
| 38 | Fire Blast |
| 44 | Thunderbolt |

### 031 · Nidoqueen

| Level | Move |
|---:|---|
| 8 | Scratch |
| 14 | Poison Sting |
| 20 | Body Slam |
| 26 | Earthquake |
| 32 | Blizzard |
| 38 | Fire Blast |
| 44 | Thunderbolt |

</details>

<details>
<summary><strong>032–034 · Nidoran♂ → Nidoking</strong></summary>

### 032 · Nidoran♂

| Level | Move |
|---:|---|
| 8 | Horn Attack |
| 14 | Poison Sting |
| 20 | Thrash |
| 26 | Earthquake |
| 32 | Thunderbolt |
| 38 | Rock Slide |
| 44 | Blizzard |

### 034 · Nidoking

| Level | Move |
|---:|---|
| 8 | Horn Attack |
| 14 | Poison Sting |
| 20 | Thrash |
| 26 | Earthquake |
| 32 | Thunderbolt |
| 38 | Rock Slide |
| 44 | Blizzard |

</details>

<details>
<summary><strong>035–036 · Clefairy → Clefable</strong></summary>

### 035 · Clefairy

| Level | Move |
|---:|---|
| 13 | Sing |
| 18 | Doubleslap |
| 24 | Thunder Wave |
| 31 | Body Slam |
| 39 | Thunderbolt |
| 45 | Hyper Beam |

### 036 · Clefable

| Level | Move |
|---:|---|
| 13 | Sing |
| 18 | Doubleslap |
| 24 | Thunder Wave |
| 31 | Body Slam |
| 39 | Thunderbolt |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>037–038 · Vulpix → Ninetales</strong></summary>

### 037 · Vulpix

| Level | Move |
|---:|---|
| 16 | Quick Attack |
| 28 | Confuse Ray |
| 35 | Fire Spin |
| 42 | Body Slam |
| 45 | Fire Blast |

### 038 · Ninetales

| Level | Move |
|---:|---|
| 16 | Quick Attack |
| 28 | Confuse Ray |
| 35 | Fire Spin |
| 42 | Body Slam |
| 45 | Fire Blast |

</details>

<details>
<summary><strong>039–040 · Jigglypuff → Wigglytuff</strong></summary>

### 039 · Jigglypuff

| Level | Move |
|---:|---|
| 14 | Disable |
| 19 | Defense Curl |
| 24 | Doubleslap |
| 29 | Thunder Wave |
| 34 | Body Slam |
| 39 | Seismic Toss |
| 45 | Hyper Beam |

### 040 · Wigglytuff

| Level | Move |
|---:|---|
| 9 | Pound |
| 14 | Disable |
| 19 | Defense Curl |
| 24 | Doubleslap |
| 29 | Thunder Wave |
| 34 | Body Slam |
| 39 | Seismic Toss |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>041–042 · Zubat → Golbat</strong></summary>

### 041 · Zubat

| Level | Move |
|---:|---|
| 10 | Supersonic |
| 15 | Bite |
| 21 | Confuse Ray |
| 28 | Screech |
| 36 | Double Edge |
| 45 | Mega Drain |

### 042 · Golbat

| Level | Move |
|---:|---|
| 10 | Supersonic |
| 15 | Bite |
| 21 | Confuse Ray |
| 28 | Screech |
| 36 | Double Edge |
| 45 | Mega Drain |

</details>

<details>
<summary><strong>043–045 · Oddish → Vileplume</strong></summary>

### 043 · Oddish

| Level | Move |
|---:|---|
| 11 | Poisonpowder |
| 13 | Stun Spore |
| 15 | Sleep Powder |
| 29 | Swords Dance |
| 42 | Hyper Beam |

### 045 · Vileplume

| Level | Move |
|---:|---|
| 21 | Stun Spore |
| 13 | Wrap |
| 18 | Sleep Powder |
| 26 | Razor Leaf |
| 33 | Swords Dance |
| 42 | Hyper Beam |

</details>

<details>
<summary><strong>046–047 · Paras → Parasect</strong></summary>

### 046 · Paras

| Level | Move |
|---:|---|
| 13 | Leech Life |
| 20 | Stun Spore |
| 27 | Spore |
| 34 | Slash |
| 41 | Mega Drain |

### 047 · Parasect

| Level | Move |
|---:|---|
| 13 | Leech Life |
| 20 | Stun Spore |
| 27 | Spore |
| 34 | Slash |
| 41 | Mega Drain |

</details>

<details>
<summary><strong>048–049 · Venonat → Venomoth</strong></summary>

### 048 · Venonat

| Level | Move |
|---:|---|
| 24 | Poisonpowder |
| 27 | Leech Life |
| 30 | Stun Spore |
| 38 | Double Edge |
| 43 | Sleep Powder |
| 45 | Psychic |

### 049 · Venomoth

| Level | Move |
|---:|---|
| 24 | Poisonpowder |
| 27 | Leech Life |
| 30 | Stun Spore |
| 38 | Double Edge |
| 43 | Sleep Powder |
| 45 | Psychic |

</details>

<details>
<summary><strong>050–051 · Diglett → Dugtrio</strong></summary>

### 050 · Diglett

| Level | Move |
|---:|---|
| 15 | Growl |
| 19 | Dig |
| 24 | Substitute |
| 31 | Slash |
| 40 | Earthquake |
| 45 | Rock Slide |

### 051 · Dugtrio

| Level | Move |
|---:|---|
| 15 | Growl |
| 19 | Dig |
| 24 | Substitute |
| 31 | Slash |
| 40 | Earthquake |
| 45 | Rock Slide |

</details>

<details>
<summary><strong>052–053 · Meowth → Persian</strong></summary>

### 052 · Meowth

| Level | Move |
|---:|---|
| 12 | Bite |
| 17 | Slash |
| 23 | Bubblebeam |
| 33 | Thunderbolt |
| 44 | Body Slam |

### 053 · Persian

| Level | Move |
|---:|---|
| 12 | Bite |
| 17 | Slash |
| 23 | Bubblebeam |
| 33 | Thunderbolt |
| 44 | Body Slam |

</details>

<details>
<summary><strong>054–055 · Psyduck → Golduck</strong></summary>

### 054 · Psyduck

| Level | Move |
|---:|---|
| 28 | Tail Whip |
| 31 | Disable |
| 36 | Confusion |
| 43 | Fury Swipes |
| 45 | Hydro Pump |

### 055 · Golduck

| Level | Move |
|---:|---|
| 28 | Tail Whip |
| 31 | Disable |
| 36 | Confusion |
| 43 | Fury Swipes |
| 45 | Hydro Pump |

</details>

<details>
<summary><strong>056–057 · Mankey → Primeape</strong></summary>

### 056 · Mankey

| Level | Move |
|---:|---|
| 12 | Karate Chop |
| 18 | Fury Swipes |
| 24 | Focus Energy |
| 30 | Rock Slide |
| 36 | Body Slam |
| 42 | Hyper Beam |

### 057 · Primeape

| Level | Move |
|---:|---|
| 12 | Karate Chop |
| 18 | Fury Swipes |
| 24 | Focus Energy |
| 30 | Rock Slide |
| 36 | Body Slam |
| 42 | Hyper Beam |

</details>

<details>
<summary><strong>058–059 · Growlithe → Arcanine</strong></summary>

### 058 · Growlithe

| Level | Move |
|---:|---|
| 13 | Ember |
| 18 | Agility |
| 25 | Body Slam |
| 34 | Fire Blast |
| 45 | Hyper Beam |

### 059 · Arcanine

| Level | Move |
|---:|---|
| 13 | Ember |
| 18 | Agility |
| 25 | Body Slam |
| 34 | Fire Blast |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>060–062 · Poliwag → Poliwrath</strong></summary>

### 060 · Poliwag

| Level | Move |
|---:|---|
| 16 | Hypnosis |
| 19 | Water Gun |
| 25 | Doubleslap |
| 31 | Body Slam |
| 38 | Amnesia |
| 45 | Hydro Pump |

### 062 · Poliwrath

| Level | Move |
|---:|---|
| 16 | Hypnosis |
| 19 | Water Gun |
| 26 | Doubleslap |
| 33 | Body Slam |
| 41 | Amnesia |
| 49 | Hydro Pump |

</details>

<details>
<summary><strong>063–065 · Abra → Alakazam</strong></summary>

### 063 · Abra

_No level-up moves._

### 065 · Alakazam

| Level | Move |
|---:|---|
| 16 | Confusion |
| 20 | Disable |
| 27 | Psybeam |
| 31 | Thunder Wave |
| 38 | Recover |
| 42 | Psychic |
| 45 | Reflect |

</details>

<details>
<summary><strong>066–068 · Machop → Machamp</strong></summary>

### 066 · Machop

| Level | Move |
|---:|---|
| 14 | Low Kick |
| 19 | Leer |
| 26 | Focus Energy |
| 28 | Submission |
| 35 | Body Slam |
| 40 | Earthquake |
| 45 | Hyper Beam |

### 068 · Machamp

| Level | Move |
|---:|---|
| 14 | Low Kick |
| 19 | Leer |
| 26 | Focus Energy |
| 28 | Submission |
| 35 | Body Slam |
| 40 | Earthquake |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>069–071 · Bellsprout → Victreebel</strong></summary>

### 069 · Bellsprout

| Level | Move |
|---:|---|
| 11 | Stun Spore |
| 16 | Wrap |
| 19 | Sleep Powder |
| 24 | Razor Leaf |
| 31 | Swords Dance |
| 40 | Hyper Beam |

### 071 · Victreebel

| Level | Move |
|---:|---|
| 11 | Stun Spore |
| 16 | Wrap |
| 19 | Sleep Powder |
| 24 | Razor Leaf |
| 31 | Swords Dance |
| 40 | Hyper Beam |

</details>

<details>
<summary><strong>072–073 · Tentacool → Tentacruel</strong></summary>

### 072 · Tentacool

| Level | Move |
|---:|---|
| 4 | Supersonic |
| 10 | Wrap |
| 15 | Poison Sting |
| 19 | Water Gun |
| 24 | Wrap |
| 30 | Rest |
| 37 | Surf |
| 45 | Blizzard |

### 073 · Tentacruel

| Level | Move |
|---:|---|
| 4 | Supersonic |
| 10 | Wrap |
| 15 | Poison Sting |
| 19 | Water Gun |
| 24 | Wrap |
| 30 | Rest |
| 37 | Surf |
| 45 | Blizzard |

</details>

<details>
<summary><strong>074–076 · Geodude → Golem</strong></summary>

### 074 · Geodude

| Level | Move |
|---:|---|
| 11 | Defense Curl |
| 16 | Rock Throw |
| 21 | Substitute |
| 26 | Rock Slide |
| 31 | Earthquake |
| 36 | Explosion |

### 076 · Golem

| Level | Move |
|---:|---|
| 11 | Defense Curl |
| 16 | Rock Throw |
| 21 | Substitute |
| 26 | Rock Slide |
| 31 | Earthquake |
| 36 | Explosion |

</details>

<details>
<summary><strong>077–078 · Ponyta → Rapidash</strong></summary>

### 077 · Ponyta

| Level | Move |
|---:|---|
| 30 | Tail Whip |
| 32 | Stomp |
| 36 | Fire Blast |
| 40 | Body Slam |
| 45 | Hyper Beam |

### 078 · Rapidash

| Level | Move |
|---:|---|
| 30 | Tail Whip |
| 32 | Stomp |
| 36 | Fire Blast |
| 40 | Body Slam |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>079–080 · Slowpoke → Slowbro</strong></summary>

### 079 · Slowpoke

| Level | Move |
|---:|---|
| 15 | Disable |
| 19 | Headbutt |
| 24 | Thunder Wave |
| 30 | Rest |
| 37 | Amnesia |
| 45 | Psychic |

### 080 · Slowbro

| Level | Move |
|---:|---|
| 15 | Disable |
| 19 | Headbutt |
| 24 | Thunder Wave |
| 30 | Rest |
| 37 | Amnesia |
| 45 | Psychic |

</details>

<details>
<summary><strong>081–082 · Magnemite → Magneton</strong></summary>

### 081 · Magnemite

| Level | Move |
|---:|---|
| 21 | Sonicboom |
| 25 | Supersonic |
| 29 | Thunderbolt |
| 35 | Thunder Wave |
| 41 | Double Edge |
| 45 | Rest |

### 082 · Magneton

| Level | Move |
|---:|---|
| 21 | Sonicboom |
| 25 | Supersonic |
| 29 | Thunderbolt |
| 35 | Thunder Wave |
| 41 | Double Edge |
| 45 | Rest |

</details>

<details>
<summary><strong>083 · Farfetch'd</strong></summary>

### 083 · Farfetch'd

| Level | Move |
|---:|---|
| 7 | Leer |
| 15 | Fury Attack |
| 23 | Swords Dance |
| 31 | Agility |
| 39 | Slash |
| 45 | Body Slam |

</details>

<details>
<summary><strong>084–085 · Doduo → Dodrio</strong></summary>

### 084 · Doduo

| Level | Move |
|---:|---|
| 20 | Growl |
| 24 | Fury Attack |
| 30 | Drill Peck |
| 36 | Body Slam |
| 40 | Agility |
| 44 | Hyper Beam |

### 085 · Dodrio

| Level | Move |
|---:|---|
| 20 | Growl |
| 24 | Fury Attack |
| 30 | Drill Peck |
| 36 | Body Slam |
| 40 | Agility |
| 44 | Hyper Beam |

</details>

<details>
<summary><strong>086–087 · Seel → Dewgong</strong></summary>

### 086 · Seel

| Level | Move |
|---:|---|
| 21 | Growl |
| 24 | Ice Beam |
| 33 | Rest |
| 39 | Body Slam |
| 45 | Blizzard |

### 087 · Dewgong

| Level | Move |
|---:|---|
| 21 | Growl |
| 24 | Ice Beam |
| 33 | Rest |
| 39 | Body Slam |
| 45 | Blizzard |

</details>

<details>
<summary><strong>088–089 · Grimer → Muk</strong></summary>

### 088 · Grimer

| Level | Move |
|---:|---|
| 20 | Poison Gas |
| 23 | Mega Drain |
| 27 | Body Slam |
| 32 | Thunderbolt |
| 38 | Explosion |
| 45 | Hyper Beam |

### 089 · Muk

| Level | Move |
|---:|---|
| 20 | Poison Gas |
| 23 | Mega Drain |
| 27 | Body Slam |
| 32 | Thunderbolt |
| 38 | Explosion |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>090–091 · Shellder → Cloyster</strong></summary>

### 090 · Shellder

| Level | Move |
|---:|---|
| 13 | Supersonic |
| 18 | Clamp |
| 25 | Explosion |
| 34 | Blizzard |
| 45 | Hyper Beam |

### 091 · Cloyster

| Level | Move |
|---:|---|
| 13 | Supersonic |
| 18 | Clamp |
| 25 | Explosion |
| 34 | Blizzard |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>092–094 · Gastly → Gengar</strong></summary>

### 092 · Gastly

| Level | Move |
|---:|---|
| 29 | Hypnosis |
| 38 | Explosion |
| 45 | Thunderbolt |

### 094 · Gengar

| Level | Move |
|---:|---|
| 29 | Hypnosis |
| 38 | Explosion |
| 45 | Thunderbolt |

</details>

<details>
<summary><strong>095 · Onix</strong></summary>

### 095 · Onix

| Level | Move |
|---:|---|
| 10 | Rage |
| 14 | Bind |
| 18 | Rock Slide |
| 32 | Earthquake |
| 42 | Explosion |

</details>

<details>
<summary><strong>096–097 · Drowzee → Hypno</strong></summary>

### 096 · Drowzee

| Level | Move |
|---:|---|
| 12 | Disable |
| 17 | Confusion |
| 24 | Headbutt |
| 29 | Poison Gas |
| 32 | Psychic |
| 37 | Hypnosis |
| 42 | Thunder Wave |
| 45 | Seismic Toss |

### 097 · Hypno

| Level | Move |
|---:|---|
| 12 | Disable |
| 17 | Confusion |
| 24 | Headbutt |
| 29 | Poison Gas |
| 32 | Psychic |
| 37 | Hypnosis |
| 42 | Thunder Wave |
| 45 | Seismic Toss |

</details>

<details>
<summary><strong>098–099 · Krabby → Kingler</strong></summary>

### 098 · Krabby

| Level | Move |
|---:|---|
| 20 | Vicegrip |
| 25 | Swords Dance |
| 30 | Body Slam |
| 35 | Crabhammer |
| 40 | Hyper Beam |

### 099 · Kingler

| Level | Move |
|---:|---|
| 20 | Vicegrip |
| 25 | Swords Dance |
| 30 | Body Slam |
| 35 | Crabhammer |
| 40 | Hyper Beam |

</details>

<details>
<summary><strong>100–101 · Voltorb → Electrode</strong></summary>

### 100 · Voltorb

| Level | Move |
|---:|---|
| 9 | Sonicboom |
| 14 | Selfdestruct |
| 21 | Screech |
| 28 | Thunder Wave |
| 35 | Thunderbolt |
| 42 | Explosion |

### 101 · Electrode

| Level | Move |
|---:|---|
| 9 | Sonicboom |
| 14 | Selfdestruct |
| 21 | Screech |
| 28 | Thunder Wave |
| 35 | Thunderbolt |
| 42 | Explosion |

</details>

<details>
<summary><strong>102–103 · Exeggcute → Exeggutor</strong></summary>

### 102 · Exeggcute

| Level | Move |
|---:|---|
| 25 | Reflect |
| 28 | Leech Seed |
| 32 | Stun Spore |
| 37 | Explosion |
| 42 | Psychic |
| 48 | Sleep Powder |

### 103 · Exeggutor

| Level | Move |
|---:|---|
| 25 | Reflect |
| 28 | Leech Seed |
| 32 | Stun Spore |
| 37 | Explosion |
| 42 | Psychic |
| 48 | Sleep Powder |

</details>

<details>
<summary><strong>104–105 · Cubone → Marowak</strong></summary>

### 104 · Cubone

| Level | Move |
|---:|---|
| 15 | Thrash |
| 23 | Counter |
| 31 | Earthquake |
| 38 | Fire Blast |
| 45 | Blizzard |

### 105 · Marowak

| Level | Move |
|---:|---|
| 15 | Thrash |
| 23 | Counter |
| 31 | Earthquake |
| 38 | Fire Blast |
| 45 | Blizzard |

</details>

<details>
<summary><strong>106 · Hitmonlee</strong></summary>

### 106 · Hitmonlee

| Level | Move |
|---:|---|
| 33 | Rolling Kick |
| 38 | Jump Kick |
| 41 | Focus Energy |
| 43 | Hi Jump Kick |
| 45 | Mega Kick |

</details>

<details>
<summary><strong>107 · Hitmonchan</strong></summary>

### 107 · Hitmonchan

| Level | Move |
|---:|---|
| 33 | Fire Punch |
| 38 | Ice Punch |
| 41 | Thunderpunch |
| 43 | Mega Punch |
| 45 | Counter |

</details>

<details>
<summary><strong>108 · Lickitung</strong></summary>

### 108 · Lickitung

| Level | Move |
|---:|---|
| 7 | Stomp |
| 15 | Disable |
| 23 | Swords Dance |
| 31 | Body Slam |
| 39 | Earthquake |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>109–110 · Koffing → Weezing</strong></summary>

### 109 · Koffing

| Level | Move |
|---:|---|
| 26 | Sludge |
| 31 | Smokescreen |
| 34 | Selfdestruct |
| 36 | Fire Blast |
| 39 | Thunderbolt |
| 42 | Explosion |
| 45 | Hyper Beam |

### 110 · Weezing

| Level | Move |
|---:|---|
| 26 | Sludge |
| 31 | Smokescreen |
| 34 | Selfdestruct |
| 36 | Fire Blast |
| 39 | Thunderbolt |
| 42 | Explosion |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>111–112 · Rhyhorn → Rhydon</strong></summary>

### 111 · Rhyhorn

| Level | Move |
|---:|---|
| 10 | Stomp |
| 15 | Substitute |
| 20 | Fury Attack |
| 25 | Double Edge |
| 35 | Body Slam |
| 40 | Rock Slide |
| 45 | Earthquake |

### 112 · Rhydon

| Level | Move |
|---:|---|
| 10 | Stomp |
| 15 | Tail Whip |
| 20 | Fury Attack |
| 25 | Double Edge |
| 30 | Substitute |
| 35 | Body Slam |
| 40 | Rock Slide |
| 45 | Earthquake |

</details>

<details>
<summary><strong>113 · Chansey</strong></summary>

### 113 · Chansey

| Level | Move |
|---:|---|
| 15 | Sing |
| 21 | Growl |
| 29 | Thunder Wave |
| 35 | Thunderbolt |
| 39 | Ice Beam |
| 45 | Softboiled |

</details>

<details>
<summary><strong>114 · Tangela</strong></summary>

### 114 · Tangela

| Level | Move |
|---:|---|
| 29 | Absorb |
| 32 | Poisonpowder |
| 36 | Stun Spore |
| 39 | Sleep Powder |
| 45 | Slam |
| 49 | Growth |

</details>

<details>
<summary><strong>115 · Kangaskhan</strong></summary>

### 115 · Kangaskhan

| Level | Move |
|---:|---|
| 25 | Bite |
| 30 | Body Slam |
| 35 | Rock Slide |
| 40 | Earthquake |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>116–117 · Horsea → Seadra</strong></summary>

### 116 · Horsea

| Level | Move |
|---:|---|
| 13 | Water Gun |
| 18 | Bubblebeam |
| 24 | Blizzard |
| 31 | Agility |
| 39 | Hydro Pump |

### 117 · Seadra

| Level | Move |
|---:|---|
| 13 | Water Gun |
| 18 | Bubblebeam |
| 24 | Blizzard |
| 31 | Agility |
| 39 | Hydro Pump |

</details>

<details>
<summary><strong>118–119 · Goldeen → Seaking</strong></summary>

### 118 · Goldeen

| Level | Move |
|---:|---|
| 16 | Supersonic |
| 21 | Horn Attack |
| 27 | Bubblebeam |
| 34 | Blizzard |
| 42 | Agility |
| 45 | Hyper Beam |

### 119 · Seaking

| Level | Move |
|---:|---|
| 16 | Supersonic |
| 21 | Horn Attack |
| 27 | Bubblebeam |
| 34 | Blizzard |
| 42 | Agility |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>120–121 · Staryu → Starmie</strong></summary>

### 120 · Staryu

| Level | Move |
|---:|---|
| 17 | Water Gun |
| 22 | Harden |
| 27 | Recover |
| 32 | Swift |
| 37 | Thunder Wave |
| 42 | Psychic |
| 45 | Blizzard |

### 121 · Starmie

| Level | Move |
|---:|---|
| 17 | Water Gun |
| 22 | Harden |
| 27 | Recover |
| 32 | Swift |
| 37 | Thunder Wave |
| 42 | Psychic |
| 45 | Blizzard |

</details>

<details>
<summary><strong>122 · Mr. Mime</strong></summary>

### 122 · Mr. Mime

| Level | Move |
|---:|---|
| 15 | Confusion |
| 23 | Thunder Wave |
| 31 | Thunderbolt |
| 39 | Psychic |
| 45 | Seismic Toss |

</details>

<details>
<summary><strong>123 · Scyther</strong></summary>

### 123 · Scyther

| Level | Move |
|---:|---|
| 17 | Leer |
| 20 | Focus Energy |
| 24 | Substitute |
| 29 | Slash |
| 35 | Swords Dance |
| 42 | Hyper Beam |

</details>

<details>
<summary><strong>124 · Jynx</strong></summary>

### 124 · Jynx

| Level | Move |
|---:|---|
| 18 | Lick |
| 23 | Doubleslap |
| 25 | Ice Punch |
| 26 | Body Slam |
| 34 | Thrash |
| 45 | Blizzard |

</details>

<details>
<summary><strong>125 · Electabuzz</strong></summary>

### 125 · Electabuzz

| Level | Move |
|---:|---|
| 25 | Thundershock |
| 28 | Thunder Wave |
| 33 | Thunderbolt |
| 40 | Body Slam |
| 45 | Psychic |

</details>

<details>
<summary><strong>126 · Magmar</strong></summary>

### 126 · Magmar

| Level | Move |
|---:|---|
| 24 | Leer |
| 27 | Confuse Ray |
| 31 | Fire Punch |
| 36 | Smokescreen |
| 40 | Body Slam |
| 43 | Fire Blast |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>127 · Pinsir</strong></summary>

### 127 · Pinsir

| Level | Move |
|---:|---|
| 16 | Seismic Toss |
| 21 | Bind |
| 27 | Focus Energy |
| 34 | Substitute |
| 40 | Slash |
| 43 | Swords Dance |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>128 · Tauros</strong></summary>

### 128 · Tauros

| Level | Move |
|---:|---|
| 15 | Stomp |
| 22 | Body Slam |
| 29 | Earthquake |
| 38 | Blizzard |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>129–130 · Magikarp → Gyarados</strong></summary>

### 129 · Magikarp

| Level | Move |
|---:|---|
| 5 | Tackle |

### 130 · Gyarados

| Level | Move |
|---:|---|
| 20 | Bite |
| 25 | Dragon Rage |
| 32 | Body Slam |
| 39 | Blizzard |
| 42 | Hydro Pump |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>131 · Lapras</strong></summary>

### 131 · Lapras

| Level | Move |
|---:|---|
| 15 | Mist |
| 19 | Confuse Ray |
| 23 | Sing |
| 30 | Body Slam |
| 37 | Blizzard |
| 45 | Thunderbolt |

</details>

<details>
<summary><strong>132 · Ditto</strong></summary>

### 132 · Ditto

_No level-up moves._

</details>

<details>
<summary><strong>133–136 · Eevee → Flareon</strong></summary>

### 133 · Eevee

| Level | Move |
|---:|---|
| 24 | Quick Attack |
| 28 | Tail Whip |
| 34 | Bite |
| 42 | Take Down |
| 45 | Hyper Beam |

### 136 · Flareon

| Level | Move |
|---:|---|
| 26 | Rage |
| 29 | Ember |
| 35 | Fire Blast |
| 39 | Body Slam |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>137 · Porygon</strong></summary>

### 137 · Porygon

| Level | Move |
|---:|---|
| 23 | Psybeam |
| 28 | Recover |
| 35 | Agility |
| 42 | Tri Attack |

</details>

<details>
<summary><strong>138–139 · Omanyte → Omastar</strong></summary>

### 138 · Omanyte

| Level | Move |
|---:|---|
| 26 | Ice Beam |
| 31 | Rest |
| 38 | Body Slam |
| 45 | Hydro Pump |

### 139 · Omastar

| Level | Move |
|---:|---|
| 26 | Ice Beam |
| 31 | Rest |
| 38 | Body Slam |
| 45 | Hydro Pump |

</details>

<details>
<summary><strong>140–141 · Kabuto → Kabutops</strong></summary>

### 140 · Kabuto

| Level | Move |
|---:|---|
| 14 | Absorb |
| 19 | Slash |
| 24 | Leer |
| 29 | Hydro Pump |
| 34 | Swords Dance |
| 39 | Hyper Beam |

### 141 · Kabutops

| Level | Move |
|---:|---|
| 14 | Absorb |
| 19 | Slash |
| 24 | Leer |
| 29 | Hydro Pump |
| 34 | Swords Dance |
| 39 | Hyper Beam |

</details>

<details>
<summary><strong>142 · Aerodactyl</strong></summary>

### 142 · Aerodactyl

| Level | Move |
|---:|---|
| 24 | Sky Attack |
| 29 | Fire Blast |
| 36 | Double Edge |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>143 · Snorlax</strong></summary>

### 143 · Snorlax

| Level | Move |
|---:|---|
| 24 | Body Slam |
| 30 | Reflect |
| 37 | Earthquake |
| 45 | Ice Beam |

</details>

<details>
<summary><strong>144 · Articuno</strong></summary>

### 144 · Articuno

| Level | Move |
|---:|---|
| 31 | Agility |
| 35 | Ice Beam |
| 40 | Blizzard |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>145 · Zapdos</strong></summary>

### 145 · Zapdos

| Level | Move |
|---:|---|
| 31 | Thunderbolt |
| 35 | Agility |
| 40 | Thunder Wave |
| 45 | Drill Peck |

</details>

<details>
<summary><strong>146 · Moltres</strong></summary>

### 146 · Moltres

| Level | Move |
|---:|---|
| 31 | Agility |
| 35 | Fire Spin |
| 40 | Fire Blast |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>147–149 · Dratini → Dragonite</strong></summary>

### 147 · Dratini

| Level | Move |
|---:|---|
| 10 | Thunder Wave |
| 20 | Agility |
| 25 | Wrap |
| 35 | Blizzard |
| 45 | Hyper Beam |

### 149 · Dragonite

| Level | Move |
|---:|---|
| 10 | Thunder Wave |
| 20 | Agility |
| 25 | Wrap |
| 35 | Blizzard |
| 45 | Hyper Beam |

</details>

<details>
<summary><strong>150 · Mewtwo</strong></summary>

### 150 · Mewtwo

| Level | Move |
|---:|---|
| 27 | Barrier |
| 30 | Psychic |
| 34 | Recover |
| 39 | Thunderbolt |
| 45 | Amnesia |

</details>

<details>
<summary><strong>151 · Mew</strong></summary>

### 151 · Mew

| Level | Move |
|---:|---|
| 10 | Transform |
| 20 | Mega Punch |
| 30 | Metronome |
| 40 | Psychic |

</details>

---

## Development

Pokémon Rust is based on the [pret Disassembly of Pokémon Red / Blue](https://github.com/pret/pokered) and is written in GBZ80 Assembly.
