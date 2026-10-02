DOMINO ARENA - GITHUB / PWA EDITION
====================================

All files are intentionally in the repository root. No source folders and no build step.

Upload these files directly to a GitHub repository and enable GitHub Pages.

Files:
- index.html
- app.js
- styles.css
- manifest.json
- sw.js
- icon.svg
- README.txt

Multiplayer:
This static version uses WebRTC through PeerJS. Internet access is required for the PeerJS signaling service, although the game data channel is peer-to-peer after connection.

How to test:
1. Enable GitHub Pages.
2. Open the HTTPS Pages URL on Host phone.
3. Tap Create Game.
4. Share the generated Host ID with the second player.
5. Second player opens the same URL, taps Join Game and enters the Host ID.
6. Host starts the game.

The GitHub version does not need a backend of its own.

For a completely offline same-Wi-Fi experience, use the Offline LAN edition with START-DOMINO.bat.
