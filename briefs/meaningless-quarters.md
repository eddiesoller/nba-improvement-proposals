# Meaningless Quarters

The NBA has two engagement problems, and they share the same root cause.

The first is blowouts. One team goes up 35 at halftime. The stars sit. The other team runs its bench. Fans stream for the exits before the third quarter is over, and the ones who stay are checking their phones. At home, people change the channel. The game is over in everything but name.

The second is subtler. Even in close games, the first three quarters function mostly as preamble. Fans have learned to tune in late, because early play rarely decides things — the fourth quarter is where outcomes are actually determined. Experienced viewers don't fully engage until crunch time, because they've internalized that what happens before it is largely overwriteable.

Both problems come from the same structural flaw: under cumulative scoring, early performance can always be overwritten by late performance. A large enough lead makes the remainder of the game meaningless. And even without a large lead, the end of the game is simply worth more than the beginning.

**[NIP 0100 — Match Scoring](../nips/0100.md)** proposes a fix.

---

## The Problem With Cumulative Scoring

The current NBA format adds up every point across four quarters. The team with the higher total wins. Simple — but it has a side effect: a point scored in the first minute of the first quarter is mathematically identical to a point scored in the final minute of the fourth.

This means:

- A team down 30 in the third quarter has no realistic path back. The game is over. Everyone knows it.
- Even in close games, the first three quarters mostly serve as setup for the fourth. Fans learn to tune in late, because early play rarely determines outcomes.

Both problems come from the same root: early performance can always be overwritten by late performance, so only the end really matters.

---

## The Fix: Period Scoring

Instead of cumulative scoring, each 12-minute period is scored independently. The team that wins more periods wins the match — first to 3 periods out of 5.

A team down big in one period isn't out of the match. They just need to win the next period. A 20-point blowout in period 1 is worth exactly as much as a 1-point win in period 1: one period. The lead doesn't carry over.

This eliminates the structural condition that makes blowouts feel meaningless. Stars can't be safely benched with 18 minutes left because the match is genuinely still in play. Every period has stakes.

For tied periods, there's no overtime interval — just **sudden death**: next basket wins the period, no timeouts. One play. High leverage, immediately legible.

---

## Why It's Called a Match

This format is largely inspired by tennis, and the naming follows from that. You win periods to win the match — the same way you win sets to win a tennis match.

---

## Score Reporting

Match results are reported with the period score first, followed by individual period scores:

**MIL 3 – BOS 1** (28-24, 22-31, 19-18†, 25-22)

The † marks a period decided by sudden death. This format makes it immediately clear who dominated, who stole a period late, and which periods went down to a single basket.
