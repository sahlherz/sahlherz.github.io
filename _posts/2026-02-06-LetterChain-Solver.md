---
title: "Letterchain Solver"
date: 2026-02-05
---

  My professor made a game called LetterChain, playable here: https://homepage.divms.uiowa.edu/~eakrohn/game/index.html
He gave the class a challenge of making a solver, with whatever resources we can get our hands on, which can beat his. You see, every day his solver runs on that day's game and gets a score that he puts on the site as "Best Known Score."
He gave us the incentives of $10 for being able to get a better score, and a substantial amount of extra credit for making a solver that can beat his.

  Naturally, I have been trying at my hand at this, and, as I do and always have with past programming projects, I dove in and quickly became _obsessed_ with it. Still, after sinking at least 30 hours into this over the past week, I have not beaten the professor's solver. I have learned a ton; modifying his code to make the game able to be played with function calls, making a DFS solver, making a beam search solver, making several iterations of evaluation functions, and now beginning to collect data of games and their outcomes to eventually use machine learning for better evaluation.

  It became a problem, though, how much I was thinking about this. Everywhere I went I was on my laptop coding or even mindlessly trying out different combinations of depths for DFS. When I wasn't on my laptop, I would ponder over questions like: Why is it that at any beam width my "stochastic" beam search never outputs scores in the 190-290 range, only scores in the 120-180 and 290-310 ranges? (It was because my evaluation function overemphasized a certain strategy that could only do mediocrely or very well, never in between. In Letterchain, one move can cause a 200-point difference. For that reason, randomizing aspects of the beam search only made the score either the same or much worse, never slightly worse.)
  Since I am trying to actually stay away from obsession in order to be able to spread my gains across many things at once, LetterChain became a big threat to me completing many of the things that consume my time. But, that threat will become a boon; I have decided that I will actually plan not only the times I'm allowed to work on the project (so, scheduling), but also, I will plan what I will actually do haha. So far I've just been winging it, trying things randomly. I want to become a more intentional and thoughtful person, so I will be writing down my short-term plans of what to work on on here before ever working on the actual project!
