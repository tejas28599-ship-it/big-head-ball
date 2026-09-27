# Big Head Ball

A 1v1 side-view football game. Players with big heads run, jump, header and kick the ball into the other goal. Play against the computer and score more goals in 60 seconds.

## Play on any device

**▶ Play now: https://tejas28599-ship-it.github.io/big-head-ball/**

You don't need to install anything. Big Head Ball runs in your browser on any device: phone, tablet or computer.

1. Open the Big Head Ball link above.
2. On a phone, turn it sideways (landscape).
3. Pick a difficulty and tap **Play**. ⚽

On iPhone, turn silent mode off to hear the sound effects.

## How to play

**On a computer**

- **A / D** or **← / →**: move
- **W** or **↑**: jump
- **Space**: kick
- **Esc** or **P**: pause

**On a phone or tablet**, use the on-screen buttons: arrows at the bottom-left, **Jump** and **Kick** at the bottom-right. You can move and jump at the same time.

A goal counts when the ball fully crosses the line under the crossbar. Headers bounce off at the angle they hit your head, and running or jumping into the ball hits it harder. Choose **Easy**, **Normal** or **Hard** for the computer player.

Your total wins are saved on your device and shown on the start screen.

## For developers

The whole game is plain HTML, CSS and JavaScript in a single `index.html` file, with no frameworks, physics libraries, images or audio files. It uses a canvas with a fixed-timestep loop, custom physics, and sounds generated with the Web Audio API.

Physics, player and AI settings are named constants at the top of the script in `index.html` (for example `KICK_POWER`, `P_JUMP_V` and the `DIFFICULTY` table). Add `?debug` to the URL to click anywhere and throw the ball there.
