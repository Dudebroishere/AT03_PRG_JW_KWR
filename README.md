# AT03_PRG_JW_KWR


## File Naming
(Category) _ (Name) _ (Descriptor) _ (Identifier) . (Extension)

## Features

| Jake White               | Features                                                                                                                             |
|:-------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|
|Player Movement           |                                                                                                                                      |
|                          | The player will move freely in a top-down arena using <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> or the <kbd>Arrow keys.</kbd> |
|                          | Movement will be smooth and the player will be kept inside the arena walls.                                                          |
|                          | The player character will rotate to face the mouse cursor.                                                                           |
|Mouse-Aimed Shooting      |                                                                                                                                      |
|                          | The player will fire projectiles toward the mouse cursor by clicking the <kbd>left mousebutton.</kbd>                                |
|                          | Projectiles will be destroyed on impact with an enemy or a wall.                                                                     |
|                          | A short cooldown between shots will prevent the player from spamming projectiles.                                                    |
|Health and Hit Detection  |                                                                                                                                      |
|                          | The player will start with a set amount of health, displayed on the UI as a health bar.                                              |
|                          | Touching an enemy will deal damage, followed by a brief invincibility period.                                                        |
|                          | When health reaches zero, the game over sequence will be triggered.                                                                  |
|Game Over Screen & Restart|                                                                                                                                      |
|                          | When the player's health reaches **zero**, a game over screen will be displayed.                                                     |
|                          | The game over screen will show the player's final score, the wave reached and the current high score.                                |
|                          | The player will be given options to play again or return to the main menu.                                                           |
|                          | The game over screen will highlight if the player has set a new high score.                                                          |

<br>
<br>

| Kaiden Walker-Ross   | Features                                                                                                                                                                                          |
|:---------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Menu and Options Menu |There will be a main menu which allows players to play and exit the game;  using <kbd>Esc</kbd>.<br><br>The menu will display the game title and highest saved score.<br><br>The menu will be clean and responsive. The menu will use the Unity UI system.|
|High Score Save and Load|Player's highest score will be saved using a JSON or plain text format.<br><br>Highest Score will be available across sessions, and will load automatically when the game starts.<br><br>If there is no save file, then the game will default to zero.<br><br>If the player's score at the end of the round exceeds the previous score, then the save file will be updated automatically.|
|Wave-Based Enemy Spawning|Enemies will spawn in waves from set spawn-points around the edges of the map.<br><br>New waves will contain more enemies than the last wave.<br><br>An on-screen wave number will appear between each wave, which will also be a short break between waves.|
|Enemy Behaviour|Standard enemies will move towards the player and damage them on contact.<br><br>Enemies have health and will be destroyed when their health reaches zero.<br><br>Particle effects will be displayed on death.<br><br>Enemies can be created by modifying health and speed values.|
|Score System and Pickups|Destroyed enemies will contribute points. Different enemy types will contribute different point values.<br><br>Destroyed enemies will have a chance to drop pick-ups.<br><br>Current score and wave will be displayed on the screen in real-time using the Unity UI system.<br><br>Audio effects will be played for gunfire, enemy hits, pickups, etc.|
