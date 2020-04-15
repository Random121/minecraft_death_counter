## Layout:

(R1)(C1)(C2)(C3)(C4)

## Commands:

**(R1, Delay: 2):** scoreboard players set @a playerDeath 1

**(C1):** scoreboard players set @e[type=player] playerDeath 0

**(C2):** scoreboard players add @a[scores={playerDeath=1,playerDied=0}] deathCount 1

**(C3):** scoreboard players set @a[scores={playerDeath=1,playerDied=0}] playerDied 1

**(C4):** scoreboard players set @e[type=player,scores={playerDeath=0}] playerDied 0
