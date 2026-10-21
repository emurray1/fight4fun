# Fight for Fun

A Party Animals–style brawler designed by Mason.

Six shape fighters punch, grab and throw each other off Cloud Island. The last one standing wins the round.

## Play

Open `index.html` in a web browser, or play the GitHub Pages version.

## Game modes

- **Free for all:** everyone for themselves. The last fighter on the island wins the round.
- **Team vs team:** Red team against Blue team. You can't punch or grab your teammates. A team wins the round when the whole other team is in the water.

## Play online

1. Click **play online**, type your name and click **host**.
2. Send your friends the 4-letter code.
3. They click **play online**, type the code and click **join**.
4. Everyone picks a fighter, and the host clicks **make fight happen**.

The host's browser runs the fight, and everyone else connects to it directly using [PeerJS](https://peerjs.com/). Keep the host's game window open and in front while you play. Some school or work networks block these direct connections.

## Controls

| | Keys: WASD | Keys: Arrows | Controller |
|---|---|---|---|
| Move | A / D | ← / → | Stick or D-pad |
| Jump (double jump in air) | W | ↑ | A |
| Drop through a cloud | S | ↓ | Stick down |
| Punch | F | K | X |
| Grab, then throw | G, G | L, L | B, B |
| Pause | Esc | Esc | Start |

## Made with

- [Matter.js](https://brm.io/matter-js/) for physics
- [PeerJS](https://peerjs.com/) for online play
- Menu music is an original tune played with the Web Audio API
- Plain HTML, CSS and JavaScript (no build step)
