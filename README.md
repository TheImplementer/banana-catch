# 🍌 Banana Catch

A tiny, dependency-free arcade game in a single HTML file. Move the basket, catch the falling bananas, and avoid the rotten ones.

**[▶️ Play it](https://theimplementer.github.io/banana-catch/)** — or just open `index.html` in any browser.

## How to play

Move the basket with your **mouse**, **touch**, or the **← →** arrow keys. Catch bananas to score. Miss three good bananas and it's game over. Bananas fall faster and spawn quicker the more you catch.

## What falls from the sky

| | Item | Points | Notes |
|---|---|---|---|
| 🍌 | Yellow | 1 | Common |
| 🟢 | Green | 2 | Uncommon |
| 🔴 | Red | 3 | Less common |
| 🔵 | Blue | 4 | Rare, glows |
| ✨ | Golden | 100 | Very rare, glows |
| 🌈 | Rainbow | 2000 | Legendary (~1 in 200) |
| 🤢 | Rotten | 0 | **Avoid!** Catching one slows your basket for 5s |
| 🦅 | Falcon | 0 | Grants a **10s shield** that blocks rotten bananas |

Rotten bananas and the falcon cost you nothing if you let them fall — only good bananas cost a life when missed.

## Details

Everything is a single self-contained `index.html`: no build step, no dependencies, no external assets. The bananas and the falcon are hand-written inline SVG, recolored per variant, so they stay crisp at any size. Your best score is saved to `localStorage`.

## License

MIT
