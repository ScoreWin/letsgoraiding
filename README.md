# Let's Go Raiding!
[![Discord Shield](https://img.shields.io/discord/408094898399608845?style=flat&colorA=000000&colorB=000000&label=discord&logo=discord&logoColor=ffffff)](https://discord.gg/UzKqYSW)

> **Let's Go Raiding!** brings classic mmorpg tactics to the digital card genre. Limited variance and deep strategy put skillful play front-and-center. You will NOT see the word "random" printed on any card in this game.

## Installation
🖥️ **Windows:** [https://lgr.gg/setup](https://lgr.gg/setup)  
🍎 **Mac:** [https://lgr.gg/setup-mac](https://lgr.gg/setup-mac)  
🐧 **Linux:** [https://lgr.gg/setup-linux](https://lgr.gg/setup-linux)  

## Features
⚡ **Progression:** Experience challenging dungeons and epic raids while looting new equipment to enhance your heroes.  
⚡ **Co-op:** Form a raid party with a friend and co-operatively experience both PVE and PVP!  
⚡ **Threat Management:** Experience an intuitive positioning system without the complexities of a combat grid.  
⚡ **Cooldown Management:** Track ability cooldowns to stack and disrupt powerful rotations.  
⚡ **Resource Management:** Every hero starts at full Life and Energy. Conserve your resources or risk going OOM too quickly!  

## Game Modes
⚔️ **[PVP] Standard Queue:** Players face off against each other.  
⚔️ **[PVP] Duo Queue:** Players form a raid party with a friend and face off against an opposing raid party.  
🌎 **[PVE] Practice:** Players can practice Standard Queue vs pre-constructed decks piloted by an AI.  
🌎 **[PVE] Co-op Vs AI:** Players form a raid party with a friend and face off against pre-constructed decks piloted by an AI.  

## Gameplay Loop
- Start of turn:
  - Channeled abilities resolve.
  - Power is generated towards charging Ultimates.
  - Life/Energy regeneration occurs.
  - Abilities are drawn. (Default is 2)
  - Cooldowns progress.
    - Any abilities coming off cooldown are **Surfaced**.
  - Status effects progress.
- Main phase:
  - 1 Ability per hero may be played.
    - Abilities with **Combo** do not count towards this limit.
    - Abilities can be played in any order.
- End of turn:
  - Abilities that remain in hand are **Burried**.
  - Status effects progress.

Each match starts with heroes at full **Life** and **Energy**. Heroes restore a small amount of **Life** and/or **Energy** at the start of turn. Managing these resources is crucial towards success. Greedy deck compositions risk going OOM while waiting to regenerate.

## Threat
LGR supports a simple positioning system that is a metaphor for threat.
When a hero plays an ability, threat is generated.
- **Aggressive** abilities move the hero forward.
- **Defensive** abilities move the hero backward.
- An ability that is neither Aggressive nor Defensive, does not move the hero.

Enemies can only target heroes that are in front of other heroes. This gives opportunity to manage threat and have tanks absorb incoming abilities for squishy backliners.

If two heroes are already **Aggressive** and one use another **Aggressive** ability, then they not have more threat and will move in front of the party.

The positioning system also has a spacial element to it. For example, an ability Knockback will push the affected hero backward, effectively giving access otherwise untargetable heroes.

**Stealth** and **Reach** and **Area** abilities are further ways of accessing the backline.

## Cooldowns
Heroes draw 2 abilities per turn. Whenever they play an ability, it goes on cooldown. The cooldown represents the number of turns that must pass before the ability is placed back on top of your deck. Because it is place on top of your deck, players can progressively stack their rotations throughout the course of a game.

If an ability has a cooldown of 4. After playing it, the player will notice it is added to the timeline. Each turn, the cooldown will tick. On the 4th turn, it will be on top of the deck. On the 5th turn, generally it be drawn.

An exception to this rule is if multiple abilities come off of cooldown at the same time. When this happens, they are added to deck in the order that they were played.

## Ultimates
Ultimates are powerful, unique abilities that define your playstyle. Heroes **Empower** their ultimates by 1 each turn and whenever playing an ability with **Empower**. Ultimates become available when the hero is fully **Empowered**.

When an ultimate is played, they must recharge it before it is available again.

## Reserve
At the end of each turn, any abilities remaining are discarded to the bottom of their hero's deck. However, hero's can reserve an ability for a future turn by either right-clicking the ability or left-clicking once and then clicking the "Reserve" action that appears.

To access a reserved ability, simply reserve a different one.
