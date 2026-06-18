# m264ma_SQ_W6

## Setup and Interaction Instructions

To run the sketch locally, open `index.html` in Google Chrome using Live Server.

**Controls:**
- Move: WASD
- Shoot: Spacebar (shoots in the direction you last moved)
- B: Skip to boss fight (testing only)
- Restart: R (after win or game over)

Explore the world, survive enemy waves as you move north, then enter the glowing boss zone to fight the giant orange blob. Watch the minimap to track enemies off screen.


**Editing the Waves and Boss**
Open `data/enemies.json` to change when waves spawn, how many enemies appear, their speed, and the boss stats. Each wave has a `spawnAt` world Y value — lower values trigger later since the player starts at the bottom of the world.

**Opening the Chrome Console**
- **Windows:** Press `F12` or `Ctrl + Shift + J`, then click the **Console** tab
- **Mac:** Press `Cmd + Option + J`

## Assets

| File                                          | Source                                     |
| ----------------------------------------------| -------------------------------------------|
| `assets'/images/bg_image.jpeg`                | Photo by  Castle Studio / Adobe Stock [2]  |
| `assets'/images/pixel_sprite_sheet.png`       | Photo by Bonsaiheldin / OpenGameArt [1]    |
| `assets'/sounds/bg_music.wav`                 | Sound by MatthewHenry / Freesound [4]      |
| `assets'/sounds/gun_shot.mp3`                 | Sound by PNMCarrieRailfan / Freesound [5]  |
| `assets'/sounds/player_hurt.flac`             | Sound by Iwan Gabovitch / Freesound [3]    |


## References

[1] Bonsaiheldin. 2018. Pixel character with gun, OpenGameArt. Retrived June 17, 2026 from https://opengameart.org/content/pixel-character-with-gun

[2] Castle Studio. top down illustrated asset of a stone bridge environment, material texture, Adobe Stock. Retrived June 17, 2026 from https://stock.adobe.com/search?filters%5Bcontent_type%3Aphoto%5D=1&filters%5Bcontent_type%3Aillustration%5D=1&filters%5Bcontent_type%3Azip_vector%5D=1&filters%5Bcontent_type%3Avideo%5D=1&filters%5Bcontent_type%3Atemplate%5D=1&filters%5Bcontent_type%3A3d%5D=1&filters%5Bfetch_excluded_assets%5D=1&filters%5Binclude_stock_enterprise%5D=1&filters%5Bcontent_type%3Aimage%5D=1&order=relevance&limit=100&search_page=1&search_type=usertyped&acp=&aco=dirt+texture+cartoon&k=dirt+texture+cartoon&get_facets=0&asset_id=674266737

[3] Iwan Gabovitch. 2013. Damage, Freesound. Retrived June 17, 2026 from https://freesound.org/people/MathewHenry/sounds/685597/

[4] MatthewHenry. 2023. Action Music Loop 2 "Hunted", Freesound. Retrived June 17, 2026 from https://freesound.org/people/MathewHenry/sounds/685597/

[5] PNMCarrieRailfan. 2023. Pistol gun shot mix, Freesound. Retrived June 17, 2026 from https://freesound.org/people/PNMCarrieRailfan/sounds/683311/

