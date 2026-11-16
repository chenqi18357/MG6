# MG6

### Devlog

1. The entire for loop complete before the Update method finishes， because the entire code in update() is called per frame. If I write a for loop that takes a long time to finish, it will make the game lag.

2. Because when the player is going up, the collider of platform is disabled. After they are enabled, the collider of player would overlap with the collider of platforms ,making the player get pushed up.
