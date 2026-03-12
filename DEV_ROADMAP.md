Naruto RPG Advanced Combat System - Development Roadmap
Current Build Status: v49.5 Codex Working Build

Current Snapshot
- The old v49.1 target goals are now functionally implemented in the current build.
- The game has moved beyond the older v48 roadmap state and now includes equipment attrition, narrative combat log updates, reserve gear swapping, and bonus-action throwables.

Completed Systems

Core Combat Foundation
- Turn-based combat with alternating player and enemy turns
- Expanded Health, Chakra, and Will Power resource loops
- Element matchup system and jutsu damage typing
- Battle UI with HUD panels, tooltips, and combat log
- Mobile-friendly tooltip support and long-press handling

Advanced Combat Systems
- Three-stance system: Balanced, Offensive, Defensive
- Combo counter with damage scaling
- Full status-effect suite for buffs, debuffs, damage over time, healing over time, immunity, and counters
- Will Power gain, spend, thresholds, and special techniques
- Legendary and tiered summon system with stance requirements

v49.1 Goals Now Completed

Equipment Durability and Attrition
- Functional weapon and armor slots are implemented for combatants
- Equipment stats feed into attack, defense, crit, and evasion calculations
- Durability drops from damage dealt and damage received
- Offensive stance increases weapon wear
- Defensive stance increases armor wear
- Blocking applies extra wear
- Equipment can break and automatically unequip
- HUD now shows equipped gear and durability bars

Battle Dialogue and Narrative Log
- Combat log uses first-person, more descriptive battle text for player actions
- Enemy actions are also converted into lore-style narrative text
- Log entries are color-coded by tone
- Collapsed log shows the last 4 entries
- Expanded log shows full battle history

Inventory and Throwable Items
- Inventory panel is implemented
- Reserve weapon slot is implemented
- Reserve armor slot is implemented
- Swapping reserve equipment is implemented and costs the turn
- Kunai is implemented as a limited-use bonus action
- Smoke Bomb is implemented as a limited-use bonus action

Additional Work Already Present In This Build
- Stance-based player sprite swapping
- Visual effects for attacks, buffs, smoke, and summoning
- Summon tooltip, summon health bar, and summon tier visuals
- Post-battle run flow and checkpoint state resets
- Durability repair item support

Work Still Left

Polish and Balance
- Rebalance durability loss numbers so weapon and armor break rates feel fair over longer fights
- Rebalance Kunai, Smoke Bomb, and Will Power pacing around bonus-action economy
- Tune summon tiers, durations, and thresholds so late-game power spikes stay readable

Content Expansion
- Add more reserve gear options and a wider equipment pool
- Add more throwable tools and item variety
- Add more enemy loadouts so attrition matters across different matchups

Presentation and Cleanup
- Update version labels still showing older versions in the UI and document text
- Add a proper changelog or release notes file for v49.5
- Split the single-file HTML build into separate HTML, CSS, and JS files when ready

Release Prep
- Push current build to a dedicated Git branch
- Review differences against the existing GitHub repo before merging
- Decide whether v49.5 becomes a replacement build or a feature branch merge

Last Updated: March 12, 2026
Recommended Branch Name: feature/v49-5-codex-ui
