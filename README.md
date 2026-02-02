# Sports-Betting
Some excel workbook templates and a brief tutorial on how to use them at your own risk. If you lose it all, it's totally on you dude. 

Tutorial: 

1. Go to Sports-reference.com and choose your sport of choice. Ex: Basketball-Reference.com
2. Find the team or player that you are betting on regarding the event, download their season data as an excel file.
  - Tip: Usually 1-3 seasons is enough data, go too far back and you are judging a younger (sometimes weaker or stronger) player in your model.
3. Use the Average Function to get a rolling average of the last "season" (or "season to date" if you're just doing one season), Last 10 Games, Last 5 games, and last 3 games.
  - Tip: You can also add modifiers for things like anticipated playtime (in the game you are betting on), injury news, or other custom modifiers.    
4. On those averages (or modified averages), find the Poisson Cumulative Distribution Factor (PCDF)
  - Tip: The PCDF gives the probability of scoring ≤ k; 1 − PCDF gives the probability of scoring > k (‘over’).
5. Enter the chance of win data into "Chucks Sports Betting Sheet", in the "PCDF Win Chance" space. 
  - Tip: Negative Vig and positive Exepected Value are indicators of potential statistical arbitrage (that's good).
  - Tip: Parlays are like dogs, it's not normal for them to have more than 4 legs.
6. Use the "Total to Bet (Full Kelly)" Cell Amounts to determine your bankroll. For half kelly multiply by .5 and for 2x kelly, conversely, multiply by 2.
7. Enter these into your Betting App or Sports Book of choice.

## Disclaimers ##
- Sports Books, Casinos, and Governmental Jursidictions all have different policies regarding the legality of betting, as well as building informed models while betting. The use of this repo, or any sports betting content put out by the GitHub profile hosting this repo, is done at your own risk and with assumption of compliance with all applicable policies to the user.
- Betting is dangerous and is, statistically, a negative sum game. In plain English, this means most people will lose on average, in the long term. The key to a succesful betting model is to have "edge" over the Sports Book or House's model. They have billions of dollars (that you most likely do not) to build these models.
- With all that said, please have realistic expectations. Betting can be a fun activity that a trivial amount of money can be made in the long term, when done ideally. 
