## Layout:

(C1)(R1)>(Re)(O>)(I)(C2)(C3)(C4)

## Commands:

**(C1, C):** execute @a ~ ~ ~ scoreboard players operation @s deathDisplay = @s deathCount

**(R1, Delay: 4):** testfor @a

**(I):** scoreboard objectives remove deathDisplay

**(C2):** scoreboard objectives add deathDisplay dummy "§cPlayer Deaths"

**(C3, C):** scoreboard objectives setdisplay sidebar deathDisplay

**(C4):** scoreboard players add @a deathCount 0
