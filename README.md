Re-Volt
=======

Nothing great to see here, just myself praticing cpp with the Re-Volt game.

I'm currently trying to find memory address to then write on it. I will post here what I found !

| Address (offset : revolt.exe + ...)        | Type           | Desc  |
| ------------- |:-------------:|:-----|
| 38A568     | 8 bytes      |   Information about FPS (= Frame Per Second ) during a race |
| 3B1BD4      | 4 bytes | Information about rank during a race  |
| 3BAB3C      | 4 bytes | Number of munition  |
| 44CD40      | 4 bytes      |   strlen of the name of the player |
| 44CD44 | String[strlen(name)]      |    Contains the name of the player (your name)|


