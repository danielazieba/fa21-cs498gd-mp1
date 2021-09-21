# CS498FA21 MP1: Infinite Matrix

## Features

- Health system: the player, while moving through the tunnels, will lose health on hit with either an enemy or the rotating walls.
- Scoring: the player will gain points for each rotating wall passed through successfully (without hitting the wall), as well as further points for each enemy hit with a projectile.
- Health packs: health packs, visualized as angel statues with a black 1-and-0 motif, heal the player if the player touches them. Cannot be hit with projectiles.
- Enemies: enemies, visualized as white angel statues, 
- Projectile shooting: the player can press left click to launch a projectile which shoots forward at a speed greater than the player. The projectile can collide with enemies, and despawns after a fixed amount of time. TODO delete if colliding with wall mesh..?
- Difficulty increase: over time, the player's base speed increases, up to a certain cap (double the original speed).
- Rainbow aesthetics: the original base game tutorial solely concerns itself with the color green. This more colorful implementation instead rotates between six different colors to reminisce about good times once had on Rainbow Road.