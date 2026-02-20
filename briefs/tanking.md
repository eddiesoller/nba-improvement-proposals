# Tanking

Every year, a handful of NBA teams spend the season deliberately trying to lose. The worse a team's record, the better their odds in the draft lottery. Better draft odds mean a better shot at a franchise-altering top pick. So some franchises shamelessly accept losing seasons, rest healthy players, and trade away veterans, all in the hope of landing a high lottery draft pick.

This is tanking.

Some teams tank late in the season after being eliminated from playoff contention. Others pull the trigger earlier after a star player goes down with a season-ending injury, and suddenly there's no reason to compete. Some franchises may even decide before the season even tips off that their roster has no short or long term chance for meaningful success.

It's bad for the league and bad for fans, but the current system rewards it.

These proposals are designed to make tanking irrational at every stage of the regular season.

---

## The Fix, Part 1: Restructure the Postseason

**[NIP 0300 — Postseason Tournament](../nips/0300.md)**

The current playoff format excludes seven of fifteen teams per conference. If you're out of contention by January, there's nothing left to play for — so why not lose, get a worse record, and improve your lottery odds?

The fix: include every team in a stepladder tournament. All 15 teams participate. The current format already rewards higher seeds with better matchups and home court advantage. This goes further — higher seeds skip rounds entirely, meaning they need fewer wins to become conference champion. Every position from 1 to 15 carries a distinct structural reward.

![NBA Conference Tournament — 15 Team Format](../assets/15-team-postseason-tournament.svg)

The #1 seed enters at the Conference Semifinals and only needs to win two rounds to reach the NBA Finals. The #15 seed enters in the first round and needs to win five.

---

## The Fix, Part 2: Reform the Draft Lottery

**[NIP 0500 — Draft Lottery](../nips/0500.md)**

Even with every team in the postseason, the tanking problem isn't fully solved if lottery odds are still tied to regular season record.

Under this proposal, lottery odds are determined entirely by how far a team went in the postseason before getting eliminated. A team that loses in its first postseason appearance gets the best lottery odds. A team that wins a couple rounds before being eliminated gets lower odds. Regular season record plays no role.

Teams are grouped into three tiers:

| Tier | Description |
|------|-------------|
| 1 | Lost in first postseason appearance |
| 2 | Won one game, lost in second appearance |
| 3 | Won two games, lost in third appearance |

The per-team odds are roughly **5%, 4%, and 3%** for Tiers 1, 2, and 3. Yes, Tier 1 has slightly better odds than Tier 2 — but only by about one percentage point. That spread is intentionally small. In the current system, the worst team in the league has a 14-percentage-point lottery edge over the 14th-worst. Here, deliberately losing a playoff game to fall into a better tier gains you roughly 1 point.

Only teams eliminated before the Conference Semifinals are lottery eligible. Once you've made the Semis, you've proven you're a highly competitive team. The lottery is for teams that genuinely need help. This system still does what the original lottery intended — give struggling teams better access to top draft talent. The mechanism changes, but the spirit doesn't. Weaker teams that exit the tournament early will consistently land in better lottery tiers. Over time, that preferential access to top picks helps rebalance the league.

---

The two proposals together form a coherent system. There's no longer a reward for losing in the regular season. Whether you finish 3rd or 13th, your lottery odds depend entirely on how far you go in the tournament.
