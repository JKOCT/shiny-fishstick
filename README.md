# 📜 First Marks

An incremental (idle) game about a civilization discovering writing, from the first scratch on a cave wall to the Great Library.

## How to play
1. Download `index.html`.
2. Double-click it. It opens in your browser.
3. Click the cave wall to carve marks. Spend marks on **People** who carve for you. Some people also have **Ideas**, which you spend on **Discoveries** (pictograms, the alphabet...) that unlock new people and make everyone stronger.

Your progress saves automatically, and your people keep working while you're away.

## How to change the game
Open `index.html` in any text editor (Notepad, TextEdit, or VS Code). Look for the
**GAME SETTINGS** section. There you can:

- rename people or change their emoji
- change prices (`cost`) and output (`marksPerSecond`, `ideasPerSecond`)
- add a new person or discovery by copying one and editing it
- make the game harder or easier with `PRICE_GROWTH`

Save the file and refresh your browser to see the change.
To change the colors, edit the values under `:root` near the top of the file.
- test faster by setting `GAME_SPEED` to 10
