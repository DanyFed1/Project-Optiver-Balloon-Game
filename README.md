# Project-Optiver-Balloon-Game
Optiver and some other trading/market making firms are known for including brain teasing games to its assessment procedures. In this mini project I for fun do different simulations for famous Balloon Game.

**Game conditions**
The objective is simple:

"Earn as much money as you can by pumping air into a balloon.
The bigger the balloon gets the more it’s worth, but if you burst it – you get nothing (in the second round, money is taken off your total as a penalty).

Optiver uses this game to test your risk-taking and learning. How far will you be willing to inflate the balloon before banking what you’ve made and starting over? Will you learn from your previous mistakes?" (Quote: https://www.jobtestprep.com/optiver-test#optiverzapn)

Here are more details on the game based on info from people who passed assessments: You have 39 rounds in total with a balloon. In each round you can either pump the balloon or cash out (round starts with a balance of 0). For each pump you get +10 cents, but there is a non disclosed limit at which the balloon explodes that you don’t know, if ballon explodes you get 0 at this round. It is not known when the balloon will explode in each round, it can happen literally in any moment (after 1 pump or after 100 pumps). Objective: you need to finish the game with maximum amount of money retrieved from 39 rounds.

As I understood it. The game is fundamentally a stochastic process with uncertain rewards. The challenge lies in choosing when to cash out, given that the potential reward increases with each pump, but so does the risk.

**Simulations that I am testing:**
Strategy 1 - "fixed pump strategy" where we always cash out after a set number of pumps.
Strategy 2 - Diversified (mix riskier and conservative pumps).
Strategy 3 - Progressive Strategy with Reset. (Replication of strategy that helped a friend of mine to pass the assessment).

**In Part 2 these strategies are replicated, but this time we include a penalty term for balloon explosion and change the reward per pump**
**For more code details please refere to notebook**

Research papers: Lejuez, C.W., Read, J.P., Kahler, C.W., et al. (2002). Evaluation of a behavioral measure of risk-taking: The Balloon Analogue Risk Task (BART). Journal of Experimental Psychology: Applied, 8(2), 75-84.

**Note**: As it stands as of 13.10.2023, I never did Optiver assessments. I am also not knowing the exact conditions of Optiver assessments, so please do not take this notebook as ypur official prep guide. This project was just done because I found it funny that there are many resources online that sell preparations with 1 or 2 simulations of this game for 50$ per month or even more. So, I thought it would be interesting to try to simulate the game within 1 evening or so.

Also, if you have any ideas how to improve these simulations or you notice some fundamental mistakes, please contact me.
