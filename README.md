# Sports-Betting

## Some Excel workbook templates and a brief tutorial on how to use them—at your own risk. If you lose it all, it’s totally on you, dude.

### Tutorial

1. Pick Your Sport
 - Go to Sports-Reference and choose your sport (e.g., Basketball-Reference).

2. Download Data
  - Find the team or player you’re betting on and download their season data as an Excel file.
  - Tip: 1–3 seasons is usually enough. Too far back, and you might be evaluating a younger (or differently skilled) player.

3. Compute Rolling Averages
  - Use Excel’s AVERAGE() function to calculate rolling averages for:

    - Last season (or season-to-date)

    - Last 10 games

    - Last 5 games

    - Last 3 games

      - Tip: Add modifiers for expected playtime, injuries, or other custom adjustments.

4. Compute Poisson Cumulative Distribution Factor (PCDF)

  - The PCDF gives the probability of scoring ≤ k.

    1 − PCDF gives the probability of scoring > k (an “over”).

5. Enter Win Chance
  - Enter your probabilities into Chucks Sports Betting Sheet under PCDF Win Chance.
    - Tip: Negative Vig and positive Expected Value are indicators of potential statistical arbitrage.
    - Tip: Parlays are like dogs. They don’t normally have more than 4 legs.

6. Determine Bet Size
  - Use the Total to Bet (Full Kelly) cells to determine your bankroll allocation:

    - Half-Kelly → multiply by 0.5

    - Double-Kelly → multiply by 2

7. Place Your Bets
  - Use these amounts to inform your betting choices with your sportsbook or casino of choice.

## Disclaimers ##
- Sports Books, Casinos, and Governmental Jurisdictions all have different policies regarding the legality of betting, as well as the use of informed models while betting. The use of this repo, or any sports betting content put out by the GitHub profile hosting this repo, is done at your own risk and with assumption of compliance with all applicable policies to the user.
- Sports Betting is dangerous and is, statistically, a negative sum game. In plain English, this means most people will lose on average, in the long term. The key to a successful betting model is to have "edge" over the Sports Book or House's model. They have billions of dollars (that you most likely do not) to build these models.
- **Please have realistic expectations**. Betting can be a fun activity that a trivial amount of money can be made in the long term, when done ideally. Be aware: the more you win with a sportsbook, the worse your odds typically become as they adjust to recoup losses from you.
- Finally, don't be an idiot. Having a laptop and spreadsheets out at a casino *can* get security called on you or get the house to stop letting you play. Don't be "that guy" - do your homework at home instead. 
