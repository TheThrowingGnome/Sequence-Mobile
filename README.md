# Sequence

The Sequence board game for phones and browsers. Open `index.html`, or host the folder on any static site host (GitHub Pages works).

- **Play the computer:** 1 vs 1, 3 players, or teams with computer partners, at three skill levels: Casual, Sharp or Expert.
- **Pass & play:** everyone shares one device; hands stay hidden between turns.
- **Play online:** create a game, share the link, and friends join from their own phones. No accounts.
- **Chat:** in online games, tap **Chat** (bottom right) to send messages or silly emojis to everyone at the table.

Online games connect players' browsers directly (WebRTC via PeerJS, bundled as `peerjs.min.js`), using the free public PeerJS server to introduce them. The person who creates the game hosts it, so their page needs to stay open.
