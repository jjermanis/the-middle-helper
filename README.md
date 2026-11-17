# the-middle-helper
Experiment with The Middle game - can this tool get better?


## Overview
There is a puzzle game on the web named Middle Word (https://pzlgames.com/games/middleword/). This app helps you play that game better.


## Directions
This app is a tool to help you play an online puzzle game titled Middle Word. It is one of the games on PZL Games. Every day, the puzzle starts with two words. You have to guess which word is in the middle between those two words. You guess words to try to find the word: each guess tells you how close it is and how far away it is.

This app is a tool to help play the game. In Middle Word, it starts with two words. Within this app, the-middle-helper, inside the Start A Round section at the top, enter those two starting words. After you enter the two words and click Find A Guess, it will tell you a word to guess. Guess the word in Middle Word. That game will tell you how far away the answer is, and it is above or below. Back in the-middle-app, say how words away that guess was, and if it was above or below. After that, it will tell you the closest match to the answer it knows. It may even have the correct answer.


## Details
This is a small little app, not a game of itself. The details are extensive for this one. I like working on puzzles. I like creating apps. Apps that help you solve puzzles? I think they are great.

While not super complicated, the algorithm to help solve this game is not obvious. Try playing Middle Words a few times - you can click on the dropdown menu on the upper-left corner and click Change Puzzle to try different puzzles. When you play, it will tell you how far away you are from the answer. In every game, the numbers are relative to each other. How do you share these numbers across all the different puzzles? That is the trick.

The trick is to play words that are close to one another. Let's say you play Argue-Brake on June 16. You save numbers from that date. Later, on July 11m you play Architect-Boundary. You can guess at least one common word in both their games. By doing this, you can expand the total number of words that are known. If you do this enough, you can handle words from A to Z. In my case, I played 47 games of Middle Word (over time) to cover the alphabet.

There are some complexities to this. At the beginning of the game, Middle Word will tell you that the words are 10,000 words away from the answer. I figured out that is an estimate. Once you start guessing, so far as I see, the words away count is accurate. The initial two words are not. Therefore, I do not save those two starting words. This is why you have to guess a number and let it know how far away the answer is. Those two words at the beginning do not tell you how far away the word is. You need to guess a word between those two words - that gives information on where the winning word is.

Also, to advance through the alphabet, you need words to overlap between two games. This is needed as the numbers of the words are built: it always needs to have one known words it can ask you to guess. For two gaps, it was a long time to get those gaps filled. The was a gap for words starting with IN and words starting with UN. The Middle Words (a daily game) started in mid-June. I did not see all the gaps filled until early November.


## Mobile
This game is supported on a mobile tablet. This game is not playable on a smartphone.


## From Release #1 (Build 01.18 on 11/17/26)

* Implements the base version of the game tool.

* All words within the game are less than 1,500 words away from the answer.

