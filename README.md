# data-science-work

## Final Project Ideas

**Chances, Luck and Style at International Football Tournaments**

I'm analyzing event data from six recent men's international soccer tournaments (World Cup 2018 & 2022, Euro 2020 & 2024, AFCON 2023, Copa América 2024) using [StatsBomb Open Data](https://github.com/statsbomb/open-data): every pass, shot and pressure from 314 matches, with pitch coordinates.

**Questions I'm exploring:**
1. **What makes a shot likely to become a goal?** I'm building my own expected-goals (xG) model with logistic regression, using shot distance, angle and where defenders were standing.
2. **Were the tournament winners lucky?** I compare each team's actual goals with the goals its chances deserved, and use simulation to separate luck from skill.
3. **Do teams fall into distinct playing styles, and has the game changed since 2018?** I group teams by how they pass and press (PCA and k-means), compare continents, and track whether teams press higher than they used to. 

[Project repository](https://github.com/tandiahm/soccer-tournaments-project)
