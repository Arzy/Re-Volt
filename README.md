Re-Volt v1.10
=======

Nothing great to see here, just myself praticing cpp with the Re-Volt game.

I'm currently trying to find memory address to then write on it. I will post here what I found !

| Address (offset : revolt.exe + ...)        | Type           | Desc  |
| ------------- |:-------------:|:-----|
| 0DBFC0     | 4 bytes      |   Number of tries during a championship |
| 38A568     | 8 bytes      |   FPS (= Frame Per Second ) during a race |
| 3B1BD4      | 4 bytes | Rank during a race  |
| 3B2D48      | 4 bytes | Speed Unit (MPH/Scaled MPH/FPM/KPH/Scaled KPH)  |
| 3B6950      | 8 bytes | PICK UP TYPE 0 = "gun", 1 = one firework, 2 = triple firework, 3 = explosive car, 4 = water balloon,5 = lightning, 6 = oil, 7 = billiard ball, 8 = battery, 9 = fake pickup, 10 = star,255 = none |
| 3B772C      | 4 bytes | Current lap during a race |
| 3B7730      | 8 bytes | Current lap time during a race |
| 3B7738      | 8 bytes | Best lap time during a race |
| 3BAA20      | 1 byte | Is player in the right way ? |
| 3BAB3C      | 4 bytes | Number of munition  |
| 44CA28      | 8 bytes | Race Time  |
| 44CD00      | 4 bytes | Number of cars  |
| 44CD04      | 4 bytes | Number of laps  |
| 44CD24      | 1 byte | Pick ups  |
| 44CD40      | 4 bytes      |   strlen of the name of the player |
| 44CD44 | String[strlen(name)]      |    Contains the name of the player (your name)|
| 44CD60      | 1 byte      |   Random cars  |
| 44CD64      | 1 byte      |   Random tracks  |
| 44CD70      | 1 byte      |   Split Time (Local/Download) |



