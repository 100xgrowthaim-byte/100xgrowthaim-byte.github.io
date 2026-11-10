# 100xgrowthaim-byte.github.io

The website for Murmur: Bird Chain Puzzle, served by GitHub Pages at https://100xgrowthaim-byte.github.io.

| File | Address | Used by |
|---|---|---|
| `index.html` | https://100xgrowthaim-byte.github.io/ | Play Console → Store settings → Website |
| `murmur/index.html` | https://100xgrowthaim-byte.github.io/murmur/ | Support page |
| `murmur/privacy.html` | https://100xgrowthaim-byte.github.io/murmur/privacy.html | Play Console privacy policy, and Murmur's Settings (`PRIVACY_URL`) |
| `app-ads.txt` | https://100xgrowthaim-byte.github.io/app-ads.txt | AdMob and Unity. Must stay at the top level. |

`.nojekyll` makes GitHub serve the files as they are.

- When the app is going live with real ads, paste Unity's seller list into `app-ads.txt` (Unity dashboard → Monetization → Settings → Organization → App-ads.txt) and check the list monthly.
- If the app changes what it collects (a new ad network, analytics, accounts), update `murmur/privacy.html` and its date, and the Data safety form in Play Console.
