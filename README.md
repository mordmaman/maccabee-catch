# Maccabee Catch!

A Chanukah catching game, made for fun at home. It's built on our Feed the Monster game.

Slide your finger (or use the mouse or arrow keys) to move the Maccabee and catch things in his shield. Every 10 points a flame falls: catch it to light a candle. Light one candle on night 1, two on night 2, and so on up to all eight.

**Play it:** https://mordmaman.github.io/maccabee-catch/

## How it works

- 🍩 🪙 🥞 🫒 are a point each. A sealed 🏺 oil jar is 2 points and tops up the oil.
- 🔥 lights a candle. A 🕯️ shamash lights one straight away.
- The oil runs down over time. If it runs out, you try the night again.
- Each night adds something new:
  1. Doughnuts and gelt
  2. Burnt latkes (lose 3 points)
  3. Dreidels: Gimmel +10, Hei +5, Nun nothing, Shin −3
  4. Arrows (lose a heart) and the 🔨 hammer, which smashes every bad thing on screen
  5. Wind
  6. 💧 Water, which puts a candle out
  7. Cracked jars (lose 5 points)
  8. Everything at once, then the golden jug to finish
- A rare golden jug is worth 10 points, fills the oil and gives a heart back.
- 5 good catches in a row is a 2 point bonus.
- Finish all eight nights to unlock the endless night.
- Easy mode gives 5 hearts, slower falling and longer-lasting oil.

## Changing the game

Everything is in `index.html`. The easy settings are in the `CONFIG` block at the top of the script, and the story lines are in `NIGHTS` just below it. Set `unlockAll: true` to try the endless night without finishing the story.

Change something, commit, and GitHub Pages updates the game in a minute or so.
