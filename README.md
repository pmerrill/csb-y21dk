# SimQB
A simple football quarterback career simulator.

## Concept
- Start as college football QB
    - 50% chance to be redshirted.
    - Game begins year you become a starter. Could be 4 year, 3 year, 2 year starter.
    - [ ] Random team names
    - [ ] Random age
    - [ ] Pro draft (pick based on college stats), or game end if not good enough.
- Pros
    - 4 year contract. Could add trades/cuts later.
    - High draft pick = 60% starter first year
    - 2nd round pick+ = Backup for first 2 years. Marginal playing time. 1-3 games?
    - Sim each season. Can sim individual games later.
    - After 4 years, team offers new contract if good enough. Otherwise, free agent. Sim free agency (weekly offers, or retire)
    - Make player automatically retire due to old age, playing time, etc.
    - Bonus/future: Submit stats to global leaderboard if above predetermined benchmark.

## Pages
    - Main sim/action screen
        - Nice to have: Performance feedback/happiness
    - Career: College + pro stats in tables
    - Nice to have: Global leaderboard

## Considerations
- [ ] Retire if career rtg below x after x years pro
- [ ] Add isStarter flag to regulate stats. Pass yds around 1,500 is weird.
- [ ] Move logic for QBs into quarterback.js
- [ ] Max TDS and INTs at historical max
- [ ] Teams should be more likely to retain/trade based on career stats
- [ ] Use last season's TD and INT % to influence next season
- [ ] Add colleges and draft. College stats influence draft spot (if at all) and if starter. 
- [ ] Player names and avatars
- [ ] Ability to submit HOF QBs to global leaderboard if rtg > x
