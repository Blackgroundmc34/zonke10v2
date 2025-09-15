# Zonke – 5-Line Multiplayer Game for Reddit

**App listing:** https://developers.reddit.com/apps/zonke10v2  
**Demo post:** https://www.reddit.com/r/zonke10v2_dev/comments/1nhtn5g/zonke10v2/  
**Test subreddit:** https://www.reddit.com/r/zonke10v2_dev/  
**Developer(s):** u/Terrible-Topic8700

## Overview
Zonke is a fast, turn-based 2-player game built with Devvit Web (Interactive Posts). Players launch a ball; wherever it lands **between** grid lines advances that **line’s** soldier (Head → Body → L-Arm → R-Arm → L-Leg → R-Leg). After a soldier is complete on a line, future landings on that **same line** add **bullets**. At **10 bullets** the soldier shoots and **wins that line**. When all five lines are decided, the player with more lines wins.

## How to Play
1. On your turn press **HIT**. The timing bar sets the bounce height.
2. Landing **on** a line = no progress.  
   Landing **between** lines = progress that **specific** line for you.
3. First time on a line adds **Head**. Return to the same line to add the next part in order.
4. After all 6 parts, land on that **same line** to add **bullets**.
5. At **10 bullets**, that line is won instantly. When all **5 lines** are decided, most lines wins.

## Tech
- Devvit Web (Interactive Posts)
- React + TypeScript + Canvas
- Client-side state for turns, per-line parts/bullets, and line winners

## Run Locally
```bash
npm install
npm run dev
