# List of changes for this file:
- The movement speed for the projectile and the balls is faster
- Make the game never end, so that the balls reposition themselves when they go out of the window.

## Change 1:
Changed the number by which the projectile's speed is divided, which causes it to go faster.

## Change 2:
We took advantage of the same condition that checks if the target is inside the boundaries, but instead of returning, it warps the target's X position from -200 to 200 and assigns a random Y position.

## Commit tree:
```
*   523856d (HEAD -> main, origin/main) Merge pull request #2 from GabrielPrzz/main
|\  
| *   f064343 Merge branch 'Josemiliowo:main' into main
| |\  
| |/  
|/|   
* | b7c6c61 made gameplay infinite by returning targets
| * fbc2b81 Cambio de velocidad de disparo: cambio en el numero que divide la velocidad del proyectil, haciendolo mas rapido
|/  
* d71b4b0 added game and readme
```
